1. How many seconds are there in 42 minutes 42 seconds?

```Julia
julia> 42 * 60 + 42
2562
```

2. How many miles are there in 10 kilometer? Note that there are 1.61 kilometers in a mile.

```Julia
julia> 10 / 1.61
6.211180124223602
```

3. If you run a 10-kilometer race in 37 minutes 48 seconds, what is your average pace (time per mile in minutes and seconds)? What is your average speed in miles per hour?

- 10-kilomter = 6.211180124223602 miles
- 37 minutes 48 seconds = 2268 seconds

  1. Average pace

  ```Julia
  julia> (37 * 60 + 48) / (10 / 1.61)
  365.148
  ```

  Therefore, about 6 minutes 5 seconds per mile.

  2. Average speed

  ```Julia
  julia> 3600 * (10 / 1.61) / (37 * 60 + 48)
  9.859016070196192
  ```

  Therefore, about 9.86 miles per hour.