# NengoPRIMs

These files contain a Nengo model that models a mind wandering experiment by Smallwood et al. based on the principles
of PRIMs.

There are two Jupyter notebooks, one that runs on the CPU, and one of the GPU. The GPU version may
need some tweaking to run on your own machine. An R script is supplied to generate the graphs from the paper.

To run the notebooks, you need to install Nengo, e.g. using the following command:

```bash
pip install nengo_spa nengo_gui nengo_ocl  # nengo_ocl is only required for the GPU version
```
