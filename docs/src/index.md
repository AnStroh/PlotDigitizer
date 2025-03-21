```@meta
CurrentModule = PlotDigitizer
```# PlotDigitizer.jl

This is the documentation page of the package Diffusion coupled growth.
# Installation

[PlotDigitizer](https://github.com/AnStroh/PlotDigitizer.jl) is not yet registered and can be added as follows:

```julia
using Pkg; Pkg.add("https://github.com/AnStroh/PlotDigitizer.jl.git")
```
or
```julia-repl
julia> ]

(@v1.10) pkg> add https://github.com/AnStroh/PlotDigitizer.jl.git
```

!!! info "Install from a specific branch"
    However, as the API is changing and not every new feature leads to a new release, one can also clone the main branch of the repository:
    ```julia
    add https://github.com/AnStroh/PlotDigitizer.jl.git#main
    ```

After installation, you can test the package by running the following commands:
```julia-repl
using PlotDigitizer

julia> ]

(@v1.10) pkg> test PlotDigitizer
```
