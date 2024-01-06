# SymPy Documentation Tutorials

Link: https://docs.sympy.org/latest/index.html

GitHub - https://github.com/sympy

**Importing sympy:** Use the following code -
```python
import sympy as sp
sp.init_printing(use_unicode=True)
```

# Tutorials
[folder](sympy1_tutorials_skp/)

## Introduction [file](sympy1_tutorials_skp/introduction_gotchas_skp.ipynb)
Completed
## Gotchas [file](sympy1_tutorials_skp/introduction_gotchas_skp.ipynb)
Completed

## SymPy Features
Documentation Link: https://docs.sympy.org/latest/tutorials/intro-tutorial/features.html
### Basic Operations [file](sympy1_tutorials_skp/features_basic_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/tutorials/intro-tutorial/basic_operations.html

- **Substitution** (`expr.subs`)

- **Converting strings to sympy expressions - sympify** (`sp.sympify`)
- **evalf** (`.evalf`)
- **lambdify** (`sp.lambdify`)

### Printing [file](sympy1_tutorials_skp/features_basic_skp.ipynb)
## Features - Printing
Documentation Link: https://docs.sympy.org/latest/tutorials/intro-tutorial/printing.html

Skipped
### Simplification [file](sympy1_tutorials_skp/features_simplification_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/tutorials/intro-tutorial/simplification.html

* **simplify:** (`sp.simplify`)
* **Polynomial/Rational Function Simplification**
    - **expand:** (`sp.expand`)
    - **factor:** (`sp.factor`, `sp.factor_list`)
    - **collect:** (`sp.collect`, `expr.coeff`)
    - **cancel:** (`sp.cancel`)
    - **apart:** (`sp.apart`)

* **Trigonometric Simplification**
    - **trigsimp** (`sp.trigsimp`)
    - **expand_trig** (`sp.expand_trig`)

* **Powers**
    - **powsimp** (`sp.powsimp`)
    - **expand_power_exp / expand_power_base** (`sp.expand_power_exp` and `sp.expand_power_base`)
    - **powdenest** (`sp.powdenest`)

* **Exponentials and logarithms**
    - **expand_log** (`sp.expand_log`)
    - **logcombine** (`sp.logcombine`)

* **Special Functions** (`sp.factorial`, `sp.bionomial`, `sp.gamma`, `sp.hyper`)
    - **rewrite** (`expr.rewrite`)
    - **expand_func** (`sp.expand_func`)
    - **hyperexpand** (`sp.hyperexpand`)
    - **combsimp** (`sp.combsimp`)
    - **gammasimp** (`sp.gammasimp`)
    
* **Example: Continued Fractions**

(ongoing)

### Calculus [file](sympy1_tutorials_skp/features_calculus_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/tutorials/intro-tutorial/calculus.html

* **Derivatives:** (`sp.diff()` or `expr.diff()`)
* **Integrals:** (`sp.integrate`)
* **Limits:** (`sp.limit`)
* **Series Expansion:** (`expr.series()`)
* **Finite differences:** (`sp.differentiate_finite()`, `expr.as_finite_difference()`, `sp.finite_diff_weights()`, `sp.apply_finite_diff
()`)

### Solvers [file](sympy1_tutorials_skp/features_solvers_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/tutorials/intro-tutorial/solvers.html

* **A Note about Equations** (`sp.Eq`, `sp.solveset`)

* **Solving Equations Algebraically**
    - **System of linear equations** (`sp.linsolve`)
    - **Non-linear system of equations** (`sp.nonlinsolve`)
    - **Limitations** (`sp.solve`)
    
* **Solving Differential Equations** (`sp.dsolve`)

### Matrices [file](sympy1_tutorials_skp/features_matrices_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/tutorials/intro-tutorial/matrices.html

Matrix in sympy: `sp.Matrix`
* **Basic Operations**
    - **Shape** (`sp.shape`, `matrix.shape`)
    - **Accessing Rows and Columns** (`matrix.row`, `matrix.col`)
    - **Deleting and Inserting Rows and Columns** (`.row_del`, `.col_del`, `.row_insert`, `.col_insert`)
* **Basic Methods** (`.T`)
* **Matrix Constructors** (`sp.zeros`, `sp.ones`, `sp.diag`)
* **Advanced Methods**
    - **Determinant** (`.det`)
    - **RREF** (`.rref`)
    - **Nullspace** (`.nullspace`)
    - **Columnspace** (`.columnspace`)
    - **Eigenvalues, Eigenvectors, and Diagonalization** (`eigenvals`, `eigenvects`, `diagonalize`)
* **Possible Issues**
    - **Zero Testing**

### Advanced Expression Manipulation [file](sympy1_tutorials_skp/features_adv_expr_manipulations_skp.ipynb)

# How-to Guides
[folder](sympy2_how_to_guides_skp/)
# Explanations
[folder](sympy3_explanations_skp/)

# API References - Basics
[folder](sympy4_api_ref_basics_skp/)
# API References - Code Generation
[folder](sympy4_api_ref_code_generation_skp/)
# API References - Logic
[folder](sympy4_api_ref_logic_skp/)
# API References - Matrices
[folder](sympy4_api_ref_matrices_skp/)
## Matrices (Linear Algebra) [file](sympy4_api_ref_matrices_skp/matrices1_linear_algebra_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/modules/matrices/matrices.html

* **Creating Matrices:** (`sp.Matrix()`. Generating elements using functions.)
* **Basic Manipulation**
    - **indexing and slicing**
    - **arithmetic operations**
    - **deleting rows and columns**
    - **vector operations** (`v1.cross(v2)`)
    - **joining matrices** (`row_join`, `col_join`)
* **Operations on entries** (`matrix.applyfunc()`, `.subs`)
* **Linear algebra** (`matrix.inv()`)

(ongoing)
# API References - Number Theory
[folder](sympy4_api_ref_number_theory_skp/)

# API References - Physics
[folder](sympy4_api_ref_physics_skp/)

Documentation Link: https://docs.sympy.org/latest/reference/public/physics/index.html

## Hydrogen Wavefunctions [file](sympy4_api_ref_physics_skp/hydrogen_wavefunctions_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/modules/physics/hydrogen.html

Module: **`sympy.physics.hydrogen`**. Under this, the functions availabe are -

* **`E_nl()`:** (energy in Hartree atomic units)
* **`E_nl_dirac()`:** (relativistic energy)

* **`Psi_nlm()`:** (Total wavefunction $\psi_{nlm}(r,\phi,\theta)$)
* **`R_nl()`:** (Radial part of wavefunction $R_{nl}(r)$)

## Matrices, Pauli Algebra [file](sympy4_api_ref_physics_skp/matrices_paulialgebra_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/modules/physics/matrices.html

Module: `sympy.physics.matrices`. In this module the following functions are available -
* `mgamma` (Dirac gamma matrix $\gamma^\mu$)

* `msigma(i)` (Pauli matrix $\sigma_i$ for $i=1,2,3$)
* `pat_matrix` (Parallel Axis Theorem matrix to translate the inertia matrix a distance of $(dx,dy,dz)$ for a body of mass $m$.)

Documentation Link: https://docs.sympy.org/latest/modules/physics/paulialgebra.html

Module: `sympy.physics.paulialgebra`. In this module the following functions are available -
* `Pauli`
* `evaluate_pauli_product`
## Quantum Harmonic Oscillator 1D and 3D [file](sympy4_api_ref_physics_skp/qho1d_sho_skp.ipynb)
Documentation Link: https://docs.sympy.org/latest/modules/physics/qho_1d.html

Module: **`sympy.physics.qho_1d`**. The following functions are available here -
* `E_n` (energy)
* `coherent_state`
* `psi_n` (wavefunction $\psi_n$)

Documentation Link: https://docs.sympy.org/latest/modules/physics/sho.html

Module: **`sympy.physics.sho`**. Following functions are available here -

* `E_nl`: (Energy $E_{nl} = (2n+l+\frac{3}{2})\hbar\omega$ of a 3d isotropic harmonic oscillator)

* `R_nl`: (Radial wavefunction $R_{nl}(r)$ of a 3d isotropic harmonic oscillator)

## The Physics Vector Module [file](sympy4_api_ref_physics_skp/physics_vector_skp.ipynb)

Documentation Link: https://docs.sympy.org/latest/modules/physics/vector/index.html

To import this module, do use the following code:
```python
import sympy as sp
sp.init_printing(use_unicode=True)

import sympy.physics.vector as spvec
spvec.init_vprinting(pretty_print=True)
```

* **Vector and ReferenceFrame [web link](https://docs.sympy.org/latest/modules/physics/vector/vectors.html#vector)** (`.ReferenceFrame()`)
    - **Vector Algebra** (`.dot`, `.cross`, `.normalize`, `.magnitude`, `.to_matrix`)

    - **Vector Calculus** (`.diff`, `.orient`, `.dcm`, `.orientnew`, `.dt`)

* **Kinematics [web link](https://docs.sympy.org/latest/modules/physics/vector/kinematics.html)** (`.dynamicsymbols()`, `.set_ang_vel`, `.ang_vel_in`)
    - Multiple bodies with angular velocities defined relative to each other

    - Point (`.Point`, `.locatenew`, `.pos_from`, `.set_vel`, `.vel`, `.set_acc`, `.acc`)
    - Particle moving on a ring (`.v2pt_theory`, `a2pt_theory`)
* **Potential Issues/Advanced Topics/Future Features in Physics/Vector Module [web link](https://docs.sympy.org/latest/modules/physics/vector/advanced.html)**
    - **Inertia** (import `sympy.physics.mechanics`, `.inertia`, `.to_matrix`)
    
    - **ReferenceFrame** (with `indices` and `latexs`)
    - **dynamicsymbols**
* **Scalar and Vector Field Functionality [web link](https://docs.sympy.org/latest/modules/physics/vector/fields.html)**
    - **Fields [web link](https://docs.sympy.org/latest/modules/physics/vector/fields.html#implementation-of-fields-in-sympy-physics-vector)** (`.express`)
    
    - **Field operators and other related functions [web link](https://docs.sympy.org/latest/modules/physics/vector/fields.html#field-operators-and-other-related-functions)**
        + *Curl* (`.curl`)
        + *divergence* (`.divergence`)
        + *gradient* (`.gradient`)
        + *Conservative and Solenoidal fields* (`.is_conservative`, `.is_solenoidal`)

        + *Scalar potential functions* (`.scalar_potential`, `.scalar_potential_difference`)

* **Physics Vector API [web link](https://docs.sympy.org/latest/modules/physics/vector/api/index.html)**

# API References - Utilities
[folder](sympy4_api_ref_utilities_skp/)
# API References - Topics
[folder](sympy4_api_ref_topics_skp/)
