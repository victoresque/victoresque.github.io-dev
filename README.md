# Practice #2

* Histogram equalization
* Gaussian blur
* Median blur

## Compiling

```
make
```
Will generate 3 executables: eql, gau and med.

If you only want to generate one of them, use:
```
make eql
make gau
make med
```

## Running the programs

**Put the source image files (*.pgm) in img/ before running the programs.**

**No need to prefix "img/" before the file name in program options**

### Histogram equalization
```
./eql filename
```

Output file is **img/out/eql.pgm**.

### Gaussian blur
```
./gau [-D|-S[I]] filename sigma
```
    -D        Direct 2D.          O(r²)
    -S        Separable.          O(r)
    -SI       Separable + IIR.    O(1)         default
    
    sigma     Standard deviation

Output file is **img/out/gau.pgm**.

### Median blur
```
./med [-D|-C] filename radius
```
    -D        Direct 2D.          O(r²logr)
    -C        Constant time.      O(1)         default
    
    radius    Filter radius.

Output file is **img/out/med.pgm**.

## Clean up

```
make clean
```

Deletes all object files in src/, all output ppm/pgm files, and executables.
