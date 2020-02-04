# haskell-notes
## First notes:

### Beta Normal Form
BNF is when you cannot beta reduce (apply lambdas to arguments)

### Combinators: 
A combinator is a lambda term with no free variables. Combinators, as the name suggests, serve only to combine the arguments they are given.

𝜆𝑦.𝑥

y is bound, but x is free

### Divirgence: 
Divergence here means that the reduction process never terminates or ends. Reducing terms should ordinarily converge to beta normal form, and divergence is the opposite of convergence, or normal form. Here’s an example of a lambda term called omega that diverges:
1. (𝜆𝑥.𝑥𝑥)(𝜆𝑥.𝑥𝑥)
𝑥 in the first lambda’s head becomes the second lambda



