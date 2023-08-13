# fenicsx-studies

This repository contains practice code for solving PDE using [FEniCSx](https://fenicsproject.org/). The basic tutorial can be found in [here](https://jsdokken.com/dolfinx-tutorial/). 

## installation
- To use `FEniCSx` with additional dependecies such as `gmsh`, generate a docker environment to run jupyterlab. You can find the simple image [here](https://hub.docker.com/r/tck199732/fenicsx). 
```
docker pull tck199732/fenicsx
docker run --init -ti -p 8888:8888 -v $(pwd)/notebooks:/project tck199732/fenicsx:lab-v1.0
```