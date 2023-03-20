# Multi-agent Airport RL

## Usage:
You can run an existing multi-agent algorithm via weights and biases below.

``` python minimal-marl/idqn.py --env ma_gym:Airport4-v0 ```

``` python minimal-marl/qmix.py --env ma_gym:Airport4-v0 ```

``` python minimal-marl/vdn.py --env ma_gym:Airport4-v0 ```

``` python minimal-marl/maddpg.py --env ma_gym:Airport4-v0 ```

You can also run the environment with the default multi-agent backprop:

``` python examples/random_agent.py --episodes 1000 --env Airport4-v0 ```

## Demo:

https://user-images.githubusercontent.com/31167704/226219901-cc3be595-e004-4067-8a2c-b3f6fa41b86a.mp4


## Setup and Testing:

- Install: ```pip install -e ".[test]" ```
- Run: ```pytest```




