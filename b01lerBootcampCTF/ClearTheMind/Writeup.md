```
They've gotten into your mind, but haven't managed to dive that deep yet. Root them out before it becomes an issue.
```
since e is 3 and c is very small, we can just cube root it to get plain text
```
from decimal import *

x =   '4458558515804625757984145622008292910146092770232527464448
604606202639682157127059968851563875246010604577447368616002300477986613082254856311395681221546841526780960776842385163089662821'

getcontext().prec = 100

x = Decimal(x)
power = Decimal(1)/Decimal(3)

print(hex( x**power))

```
will give us the flag in hex.
