# Laws of Boolean Algebra

Operations with 0 and 1:
1. $X+0 = X$
2. $X+1 =X$
1D. $X \cdot 1  = X$
2D. $X \cdot 0 = X$


Idempotent laws:
3. $X + X= X$
3D. $X \cdot X = X$


Involution law:
4. $(X')' = X$

Laws of complementarity:
5. $X + X' = 1$
5D. $X \cdot X' = 0$

Commutative laws:
6. $X + Y = Y + X$
6D. $XY = YX$


Associative laws:
7. $(X + Y) + Z = X + (Y + Z) = X + Y + Z$
7D. $(XY)Z = X(YZ) = XYZ$

Distributive laws:
8. $X(Y+Z) = XY + XZ$
8D. X+ YZ = (X +Y)(X+Z)

DeMorgan's laws:
9. $(X+Y)' = X' \cdot Y'$
9D. $(XY)' = X' + Y'$

----
# Duality 
## Principle of duality 
- a true Boolean equation $\Rightarrow$ dual equation is true

- $\forall$ expr $\in$ Boolean algebra in terms of ANDs, ORs, and NOTs,
  $\exists$ a dual identity by exchanging ANDs and ORs

- More specifically, a dual of a Boolean expression is obtained by replacing the symbols with their counterpart
	- 0 becomes 1
	- 1 becomes 0
	- AND becomes OR
	- OR becomes AND

# Useful Simplification Theorems
## Uniting
$XY + XY' = X$
dual form: $(X+Y)(X+Y') = X$

## Absorption
$X + XY = X$
dual form: $X(X+Y)=X$

## Elimination
$X+X'Y = X +Y$
dual form: $X(X' + Y) =XY$


## Consensus
$XY + X'Z + YZ = XY + X'Z$
$(X + Y)(X' + Z)(Y+Z) = (X + Y) (X' + Z)$


---
Additional
$XY + X'Z = (X + Z)(X' + Y)$
>[!pf]-
>$(X + Z)(X' + Y) = XX' + XY + ZX' + ZY = XY + ZX' + ZY = XY + X'Z$
>by consensus

