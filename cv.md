# Maroz Anton
## Beginner frontend developer
---
## Contact Information:
* __Location:__ Minsk, Belarus
* __GitHub:__ HUEUKA
* __Telegram:__ @hyouka_sama
* __Phone:__ +375 33 318 47 30
* __E-mail:__ morozanton1996@gmail.com
* __Discord:__ HUEUKA#2921 (@HUEUKA)
* __CodeWars:__ HUEUKA
---
## Skills:
* HTML / CSS
* Git / GitHub / VS Code
* Phuton (Basic)
---
## Codewars:
![codewars](https://www.codewars.com/users/HUEUKA/badges/large)

---
## Code Examples:
_Write a function `compute_binom(n, k)`, which takes two natural numbers as arguments `n` and `k` and returns the binomial coefficient value, equal:_
$$ \frac{n!}{k!(n-k)} $$
    ```
    def compute_binom(n, k):
     from math import factorial
      n1 = factorial(n)
      k1 = factorial(k)
      z1 = factorial(n - k)
      return int(n1 / (k1 * z1))

    n = int(input())
    k = int(input())

    print(compute_binom(n, k))
    ```
---