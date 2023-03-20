# Multi-agent Airport RL

## Usage:
``` python ma_gym/minimal-marl/idqn.py --env ma_gym:Airport4-v0 ```

``` python ma_gym/minimal-marl/qmix.py --env ma_gym:Airport4-v0 ```

``` python ma_gym/minimal-marl/vdn.py --env ma_gym:Airport4-v0 ```

``` python ma_gym/minimal-marl/maddpg.py --env ma_gym:Airport4-v0 ```

``` # running environment with multi-agent backprop (default) ```

``` python examples/random_agent.py --episodes 1000 --env Airport4-v0 ```

## Setup and Testing:

- Install: ```pip install -e ".[test]" ```
- Run: ```pytest```




