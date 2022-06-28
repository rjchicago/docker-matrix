# Matrix in Docker!

(based on [cmatrix](https://github.com/abishekvashok/cmatrix))

## Run

Running locally is simply...

``` sh
docker run --rm -it rjchicago/matrix
```

## Alias

Create an alias to make running as simple as typing `matrix`!

``` sh
# create alias
alias matrix="docker run --rm -it rjchicago/matrix"
```

``` sh
# follow the white rabbit!
matrix
```

> To make the alias permanent, insert the above alias in your bash profile.

## Build

To build this image:

``` sh
docker build -t rjchicago/matrix:${VERSION:-latest} .
```
