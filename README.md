# TradingBot
RL-based Trading bot that uses custom dataset. (Will soon integrate a functional API)

**Note:** This RL Bot trains on custom dataset that has apple, motorola and starbucks stock information of a 5 year period.

## How to run
To train the model:
> python3 linear_rl_trader.py -m train

To view the rewards graph of the trained model
> python3 plot_rl_rewards.py -m train

To test the model: 
> python3 linear_rl_trader.py -m test

To view the rewards graph of the tested model
> python3 plot_rl_rewards.py -m test
