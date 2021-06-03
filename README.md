
In this implementation of A3C, the critics learn the value function while multiple actors are trained in parallel and get synced with global parameters from time to time. Hence, A3C is designed to work well for parallel training. The agent learns a policy and a state value function and uses bootstrapped n-step returns to reduce variance over REINFORCE with a baseline.
