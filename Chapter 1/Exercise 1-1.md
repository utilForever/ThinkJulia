1. In a print statement, what happens if you leave out one of the parentheses, or both?

```Julia
julia> println("Hello, World!"

```

```Julia
julia> println"Hello, World!"
ERROR: LoadError: UndefVarError: @println_str not defined
in expression starting at REPL[10]:1
```

2. If you are typing to print a string, what happens if you leave out ont of the quotation marks, or both?

```Julia
julia> println("Hello, World!)

```

```Julia
julia> println(Hello, World!)
ERROR: UndefVarError: Hello not defined
Stacktrace:
 [1] top-level scope at REPL[11]:1
```

3. You can use a minus sign to make a negative number like `-2`. What happens if you put a plus sign before a number? What about `2++2`?

```Julia
julia> +2
2
```

```Julia
julia> 2++2
ERROR: UndefVarError: ++ not defined
Stacktrace:
 [1] top-level scope at REPL[13]:1
```

4. In math notation, leading zeros are okay, as in `02`. What happens if you try this in Julia?

```Julia
julia> 02
2
```

5. What happens if you have two values with no operator between them?

```Julia
julia> 3 2
ERROR: syntax: extra token "2" after end of expression
Stacktrace:
 [1] top-level scope at REPL[14]:0
```
