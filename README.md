# AI-Reinforcement-Learning-04-RL-Problem
Reinforcement Learning Course on UCL by David Silver

- Major Components of an RL Agent
  - Policy 
    - Deterministic policy: a = π(s)
    - Stochastic policy: π(a|s) = P[At = a|St = s]
  - Value function
  - Model 
    - predicts what the environment will do next
    - P predicts the next state
    - R predicts the next (immediate) reward
    
- Observable Environments
  - Fully Observable Environments
    - agent directly observes environment state
    - Agent state = environment state = information state
  - Partially Observable Environments
    - agent indirectly observes environment
      - A robot with camera vision isn’t told its absolute location
      - A trading agent only observes current prices
      - A poker playing agent only observes public cards
    - Now agent state != environment state
    - Agent must construct its own state representation
      - Complete history
      - Beliefs of environment state
      - Recurrent neural network

- Categorizing RL agents
  - Value and Policy
    - Value Based
      - No Policy (Implicit)
      - Value Function
    - Policy Based
      - Policy
      - No Value Function
    - Actor Critic
      - Policy
      - Value Function
  - Model
    - Model Free
      - Policy and/or Value Function
      - No Model
    - Model Based
      - Policy and/or Value Function
      - Model

