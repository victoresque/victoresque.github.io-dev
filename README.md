# Practice #2

* Histogram equalization
* Gaussian blur
* Median blur

## Compiling

```
make
```
or
```
make all
```

Will generate 3 executables: eql, gau and med.

If you only want to generate one of them, use:
```
make eql
make gau
make med
```

## Running programs

**Put the source image files (*.ppm) in img/ before running the programs.**

```
./decolor
```

Runs the color to gray conversion program.

**No need to prefix "img/" before file names**

Output files will be found in **img/out/ (Y.pgm**).

```
./channel
```

Runs the channel separation program.

**No need to prefix "img/" before file names**

Output files will also be found in **img/out/ (R.pgm, G.pgm, B.pgm**).


## Clean up

```
make clean
```

Deletes all object files in src/, all output ppm/pgm files, and executables.
