# `biome-repro-useSortedProperties`

## Biome

`npm run biome`

```
> biome check index.css

index.css:1:6 assist/source/useSortedProperties ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  × The properties are not sorted.

  > 1 │ .foo {
      │      ^
  > 2 │   position-anchor: --position-anchor;
  > 3 │ }
      │ ^
    4 │
    5 │ .bar {


index.css:5:6 assist/source/useSortedProperties ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  × The properties are not sorted.

     3 │ }
     4 │
   > 5 │ .bar {
       │      ^
   > 6 │   position-anchor: --position-anchor;
   > 7 │   position: relative;
   > 8 │   box-sizing: border-box;
   > 9 │ }
       │ ^
    10 │
    11 │ .baz {


index.css:11:6 assist/source/useSortedProperties ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  × The properties are not sorted.

     9 │ }
    10 │
  > 11 │ .baz {
       │      ^
  > 12 │   position: relative;
  > 13 │   position-anchor: --position-anchor;
  > 14 │   box-sizing: border-box;
  > 15 │ }
       │ ^
    16 │
    17 │ .qux {


index.css:17:6 assist/source/useSortedProperties ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  × The properties are not sorted.

    15 │ }
    16 │
  > 17 │ .qux {
       │      ^
  > 18 │   position: relative;
  > 19 │   box-sizing: border-box;
  > 20 │   position-anchor: --position-anchor;
  > 21 │ }
       │ ^
    22 │


Checked 1 file in 800µs. No fixes applied.
Found 4 errors.
check ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  × Some errors were emitted while running checks.
```

## Stylelint

`npm run stylelint`

```
> stylelint index.css
```
