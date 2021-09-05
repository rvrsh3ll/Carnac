# Carnac The Magnificent
 Carnac The Magnificent: Pancakeswap Prediction Market Bot

In hommage to the late, great Johnny Carson character, "Carnac The Magnificent". Carnac could predict the contents of a letter.

Carnac.py will "guess" the next bet. Currently, it simply checks the price oracle at the beginning of the round and near the end of the round, if the price is going up, we bet UP. If the price is going down, we bet DOWN. There area a few other options so, check the examples below.


## Panckakeswap Prediction BETA
[Prediction BETA](https://pancakeswap.finance/prediction)

## Setup

```pip3 install web3```

## Commands

### Pick a bet amount

```python3 Carnac.py --amount 0.01```

### Pick a random bet amount between two numbers

```python3 Carnac.py --randmin 0.002 --randmax 0.015```

### If the ending price is HIGHER than the beginning price, bet DOWN. If the ending price is LOWER than the beginning price, bet UP.

```python3 Carnac.py --opposite --amount 0.01```

### Use BTCB price to influence the bet. For example, if both BNB and BTCB go UP, multiply the bet. If BNB goes UP and BTCB goes DOWN, bet DOWN.

```python3.9.exe .\Carnac.py --randmin 0.002 --randmax 0.009 --btcbFactor --multiplier 1.25```


### Carnac.py may or may not pick the correct bet. Mileage may vary, use at your own risk. This is not finance advice. 

If you find this bot helpful, feel free to donate on BSC ```0x4fbeC728161A8A252ea09335b68292A452054B59```