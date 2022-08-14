# README

Reference: https://github.com/flame/how-to-optimize-gemm

According to the reference repo, learn optimizing GEMM step by step

## how to run
1. change the `make file`, for example

```
OLD  := MMult0
NEW  := MMult1
```

2. execute `make run`

3. view the optimization

```
octave:1> PlotAll 
```
