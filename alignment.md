# Alignment ideas and thoughts
Here I write down random unordered thoughts about AI alignment

## Interpretability playground
- Train a gpt model to play chess or go or whatever
- Questions to answer for trained model:
  - extract game state
  - does it do minimax
  - how fast does it learn the rules/capabilities in supervised vs RL training? (supervised = predict moves from other chess engine that was used to generate training data)

## Deception playground
- Train chessgpt
- Train outcome prediction model (H)
- Now train deceptiveChessGPT: conditioned on two goal "white wins", "black wins"; "H will predict white wins", "H will predict black wins" - achieve both goals
