# Practice #3

* K-means

## Compiling

```
make
```
Will generate 1 executable: kms.

## Running the programs

**Put the source image files (*.ppm) in img/ before running the programs.**

**No need to prefix "img/" before the file name in program options**

### K-means
```
./kms [-Ooptimize] filename k iteration
```
    -O0     Color depth = 8 * 3
    -O1     Color depth = 7 * 3
    -O2     Color depth = 6 * 3     default
    -O3     Color depth = 5 * 3
    -O4     Color depth = 4 * 3

Output file is **img/out/kms.pgm**.

## Report

See Report.pdf

## Clean up

```
make clean
```

Deletes all object files in src/, all output ppm/pgm files, and executables.
