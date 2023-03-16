# Content Plan

This is my current plan for the content of the Jupyter notebooks. This is subject to change, and the specifics are yet to be worked out, but it is important for me to have at least a vague outline to work from.

### Notebook 1. Mathematical Review

- Reviewing general vector spaces.
- Reviewing general vector calculus and differential equations.
- Reviewing numerical computation concepts - matrix solvers, differential equations solvers, etc.
- Recalling the inner product.
- Recalling interpolation and how to perform it.

### Notebook 2. New Mathematical Concepts

- Defining $L^2$-spaces and the $L^2$-norm.
- Defining piecewise polynomial spaces and meshes.
- Defining PDEs in variational form using the Poisson equation as an example.
- Derivation of a linear system from the weak form.

### Notebook 3. Using FENICSx to Solve the Poisson Equation

- Setting up DOLFINx on Windows using WSL2, Ubuntu and Docker.
- Overviewing the steps one needs to take to solve the a problem using DOLFINx. Includes setting up the problem's function spaces, generating a mesh, setting the linear and bilinear terms, solving, visualizing with pyvista.
- Exploring different types of mesh generation.
- Running code in parallel to speed up computation.

### Chapter 4. Explore Other PDE Problems and their FEM Solvers

- Solving for complex valued functions such as the Helmholtz Equation
- Introducing time dependent problems and solving them using a finite difference scheme




