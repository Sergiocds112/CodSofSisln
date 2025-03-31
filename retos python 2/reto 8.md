```python
def fizzbuzz(max_num):
        
    three_mul = 'fizz'
    five_mul = 'buzz'
    num1 = 3
    num2 = 5 

    for i in range(1,max_num):
        if i%num1==0 and i%num2==0:
            print(i,three_mul+five_mul)
        elif i%num1==0:
            print(i,three_mul)
        elif i%num2==0:
            print(i,five_mul)

if __name__=='__main__':
    fizzbuzz(100)
```

    3 fizz
    5 buzz
    6 fizz
    9 fizz
    10 buzz
    12 fizz
    15 fizzbuzz
    18 fizz
    20 buzz
    21 fizz
    24 fizz
    25 buzz
    27 fizz
    30 fizzbuzz
    33 fizz
    35 buzz
    36 fizz
    39 fizz
    40 buzz
    42 fizz
    45 fizzbuzz
    48 fizz
    50 buzz
    51 fizz
    54 fizz
    55 buzz
    57 fizz
    60 fizzbuzz
    63 fizz
    65 buzz
    66 fizz
    69 fizz
    70 buzz
    72 fizz
    75 fizzbuzz
    78 fizz
    80 buzz
    81 fizz
    84 fizz
    85 buzz
    87 fizz
    90 fizzbuzz
    93 fizz
    95 buzz
    96 fizz
    99 fizz
    


```python

```
