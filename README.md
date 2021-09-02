# Carnac The Magnificent
 Carnac The Magnificent: Pancakeswap Prediction Market Bot

In hommage to the late, great Johnny Carson's character, "Carnac The Magnificent". Carnac could predict the contents of a letter.

Carnac.py will "guess" the next bet. Currently, it simly checks the price oracle at the beginning of the round and near the end of the round, if the price is going up, we bet UP. If the price is going down, we bet DOWN. Feel free to change the logic to your liking.

## Commands

### Pick a random bet amount between two numbers

```python3 Carnac.py --randmin 0.002 --randmax 0.015```

### If the ending price is HIGHER than the beginning price, bet UP. Otherwise, bet DOWN. HIGHER is DEFAULT.

```python3 Carnac.py --higher --amount 0.01```

### If the ending price is LOWER than the beginning price, bet UP. Otherwise, bet DOWN.

```python3 Carnac.py --lower --amount 0.01```

### Carnac.py may or may not pick the correct bet. Mileage may vary, use at your own risk. This is not finance advice. 