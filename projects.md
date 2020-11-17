@def title="Projects"
@def author="Edwin Bedolla"

# Projects

All of the code bases presented here can be perused on my [GitHub page](https://github.com/edwinb-ai).

## Software

These are some of the software research projects I haven been working on.

- [Brownies.jl](https://github.com/edwinb-ai/Brownies.jl) and [dbfort](https://github.com/edwinb-ai/dbfort) are written to perform Brownian Dynamics simulations to study dynamical properties of hard-sphere systems. They work almost identically except that the former is written in `Julia` and the latter is written in `Fortran`.
- [Cubed.jl](https://github.com/edwinb-ai/Cubed.jl) attempts to be a CUDA implementation of the above project. This research code was meant as a learning project on how to employ Graphical Processing Units as means of faster computation.
- [Newtman.jl](https://github.com/edwinb-ai/Newtman.jl) is my side project on [metaheuristics](https://en.wikipedia.org/wiki/Metaheuristic), a type of optimizers based on randomness and general rules to solve non-linear optimization problems. This project started with the purpose of using them to tune hyperparameters in my other Machine Learning projects.
- [segmed](https://github.com/DCI-NET/segmed), written in Python, is a research project focused on the ability to perform image segmentation using modern Deep Learning techniques. This project is quite complete as it contains robust unit testing and good software practices.
- [Elysivm.jl](https://github.com/edwinb-ai/Elysivm), the newest addition, is an implementation of [Least Squares Support Vector Machines](https://link.springer.com/article/10.1023/A:1018628609742). This type of Machine Learning models are a reformulation of classic Support Vector Machines, but instead of solving a quadratic convex optimization problem, they solve a least squares optimization problem, which is faster.