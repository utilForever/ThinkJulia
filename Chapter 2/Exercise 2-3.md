1. The volume of a sphere with radius `r` is `(4/3)πr^3`. What is the volume of a sphere with radius 5?

```Julia
julia> 4/3 * π * 5^3
523.5987755982989
```

2. Suppose the cover price of a book is $24.95, but bookstores get a 40% discount. Shipping costs $3 for the first copy and 75 cents for each additional copy. What is the total wholesale cost for 60 copies?

```Julia
julia> (24.95 * 0.6) * 60 + (3 * 1 + 0.75 * 59)
945.4499999999999
```

3. If I leave my houst at 6:52 a.m. and run 1 mile at an easy pace (8:15 per mile), then 3 miles at tempo (7:12 per mile) and 1 mile at easy pace again, what time do I get home for breakfast?

```Julia
julia> (8 * 60 + 15) + 3 * (7 * 60 + 12) + (8 * 60 + 15)
2286

julia> div(2286, 60)
38

julia> mod(2286, 60)
6
```

Therefore, about 7:30 a.m.