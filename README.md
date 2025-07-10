# solving multivariable systmes of polynomials equations using newton's method
input - a list of polynomials $f_i(x_1, ..., x_n) \in \mathbb{C}[x_1, ..., x_n]$
output - a soultion $x = (x_1, ..., x_n) \in \mathbb{C}^n$ such that $f_i(x) = 0$ for all $i$

after finding one solution we can use the implict function theorem to find more solutions in the neighborhood of the solution we found.

## proposed algorithm
newton-raphson method for systems of polynomial equations but we alaways select the shortest soultion to the problem J(x) @ dx = F(x) where J(x) is the jacobian of F at x, and F(x) is the vector of polynomials $f_i(x)$.

## run
adjust the parameters in the main of newton.py, and run the following commands

```bash
python -m pip install -r requirements.txt
python newton.py
```
