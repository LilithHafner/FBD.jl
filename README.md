# Functional Ball Dropping

## fast hypergraph generation

[![Build Status](https://github.com/LilithHafner/FBD.jl/workflows/CI/badge.svg)](https://github.com/LilithHafner/FBD.jl/actions)
[![Coverage](https://codecov.io/gh/LilithHafner/FBD.jl/branch/main/graph/badge.svg)](https://codecov.io/gh/LilithHafner/FBD.jl)

Usage:

```jl
]add https://github.com/LilithHafner/FBD.jl
using FBD
graph = example(Kronecker_sampler, 30)
display(graph)
```

```jl
10-element Vector{Tuple{Int64, Int64, Int64}}:
 (6, 0, 2)
 (3, 0, 0)
 (0, 5, 5)
 (1, 2, 2)
 (4, 2, 1)
 (0, 4, 0)
 (2, 6, 4)
 (1, 4, 5)
 (5, 7, 6)
 (0, 2, 0)
```

See [`src/examples.jl`](src/examples.jl) for examples!
