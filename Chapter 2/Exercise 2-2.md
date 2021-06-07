1. We've seen that `n = 42` is legal. What about `42 = n`?

```Julia
julia> 42 = n
ERROR: syntax: invalid assignment location "42"
Stacktrace:
 [1] top-level scope at REPL[27]:1
```

2. How about `x = y = 1`?

```Julia
julia> x = y = 1
1
```

3. In some languages every statement ends with a semicolon `;`. What happens if you put a semicolon at the end of a Julia statement?

```Julia
julia> 32 + 47
79

julia> 32 + 47;

```

4. What if you put a period at the end of a statement?

```Julia
julia> 32 + 47.
79.0
```

5. In math notation you can multiply `x` and `y` like this: `x y`. What happens if you try that in Julia? What about `5x`?

```Julia
julia> x = 5
5

julia> y = 6
6

julia> x y
ERROR: syntax: extra token "y" after end of expression
Stacktrace:
 [1] top-level scope at REPL[34]:0

julia> 5x
25
```