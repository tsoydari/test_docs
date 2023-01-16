# QUICK START

## Test
### 1. Getting token
\# TODO

### 2. python example
```python
import os

def test(num: int):
    if num % 2 == 0:
        print('even number')
    else:
        print('odd number')

# Test running
try:
    test(4)
    test('a')
except Exception as e:
    print("Exception", e)
```