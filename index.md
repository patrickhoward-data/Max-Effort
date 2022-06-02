@def title = "Food Trucks"
@def hasmath = true
@def hascode = true

# Food Trucks

How many Food Trucks are there in Southern California?

We will explore the available data to see how we might help those operating Food Trucks

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```
