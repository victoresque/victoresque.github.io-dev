# Practice #1

* Separating color channels
* Converting color to grey

## Compiling

```
make
```
Will generate two executables: channel and decolor.

If you only want to generate one of them, use:
```
make channel
```

or

```
make decolor
```

## Running programs

**Put the source image files (*.ppm) in img/** before running the programs.

```
./decolor
```

Runs the color to gray conversion program.

Output files will be found in img/out/ (**Y.pgm**).

```
./channel
```

Runs the channel separation program.

Output files will also be found in img/out/ (**R.pgm, G.pgm, B.pgm**).


## Clean up

```
make clean
```

Deletes all object files in src/, all ppm/pgm files, and executables.
