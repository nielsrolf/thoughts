# How would I build AGI?

1. Train a GPT like model on all kinds of modalities (text, video frames, audio, code, trajectories of trained RL agents)
    - code:
        - generate git diff conditioned on PR description
        - summarize a codebase in language. Then implement the codebase conditioned on the summary and unit tests, and train with the objective to make unit tests work
    - RL trajectories: learning to learn
2. Train to follow instructions, mainly for easier training in the next steps.
3. Add long term memory:
- predict memory tokens: train to summarize a context C=(t_1, ..., t_m) with tokens M=(m_1, ..., m_n), such that:
    - n is small (high compression)
    - for any new context C_new = (t_{m+1}, ... t_M): the output of the model for f(C, C_new) is as close as possible to f(M, C_new)
- train on longer sequences, with regular 'context-to-memory' compressions
4. Add a new type of modality: thoughts. Thoughts would be the same multimodal tokens as the rest of the environment and is simply something the model can output. Train it to use thoughts by some chain-of-thought prompting and adding the thought identifier to the embeddings. Then train difficult tasks such as predicting code output in RL fashion to use thoughts. Thoughts give the model the ability to spend as much compute as needed to arrive at an answer. Thoughts can integrate external tools, e.g. whenever it outputs <PYTHON-EXEC>5 * 12</PYTHON-EXEC> we append <OUT>60</OUT>
5. Selfplay in an environment where:
    - cooperation is needed an agents can output text into the environment
    - competition exists
