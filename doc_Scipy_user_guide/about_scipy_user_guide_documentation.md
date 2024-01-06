# SciPy User Guide Tutorials

Link: https://docs.scipy.org/doc/scipy/tutorial/index.html#user-guide

GitHub - https://github.com/scipy

## Linear Algebra [file](scipy_linalg_skp.ipynb)
Documentation Link: https://docs.scipy.org/doc/scipy/tutorial/linalg.html

To import: 
```python
import scipy.linalg as slalg
```

* numpy.matrix vs 2-D numpy.ndarray [web link](https://docs.scipy.org/doc/scipy/tutorial/linalg.html#numpy-matrix-vs-2-d-numpy-ndarray) (`np.mat`, `np.array`, `.dot`)
* Basic Routines [web link](https://docs.scipy.org/doc/scipy/tutorial/linalg.html#basic-routines)
    - Finding the inverse (`.inv`, checking time)
    - Solving a linear system (`.solve`)
    - Finding the determinant (`.det`)
    - Computing norms (`.norm`)
    - Solving linear least-squares problems and pseudo-inverses
    - Generalized inverse
* Decompositions [web link](https://docs.scipy.org/doc/scipy/tutorial/linalg.html#decompositions)
    - Eigenvalues and eigenvectors (`.eig`, `.eigvals`)
    - Singular value decomposition
    - LU, Cholesky, QR
    - Schur
    - Interpolative
* Matrix functions [web link](https://docs.scipy.org/doc/scipy/tutorial/linalg.html#matrix-functions)
    - Arbitary function (`.funm`)
* Special matrices [web link](https://docs.scipy.org/doc/scipy/tutorial/linalg.html#special-matrices)

## Sparse [file](scipy_sparse_skp.ipynb)
Documentation Link: https://docs.scipy.org/doc/scipy/tutorial/sparse.html

To import:
```python
from scipy import sparse
```

Different type of sparse arrays are discussed here. The following formats are available: [scipy.sparse.bsr_array](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.bsr_array.html#scipy.sparse.bsr_array), [scipy.sparse.coo_array](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.coo_array.html#scipy.sparse.coo_array), [scipy.sparse.csr_array](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.csr_array.html#scipy.sparse.csr_array), [scipy.sparse.csc_array](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.csc_array.html#scipy.sparse.csc_array), [scipy.sparse.dia_array](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.dia_array.html#scipy.sparse.dia_array), [scipy.sparse.dok_array](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.dok_array.html#scipy.sparse.dok_array), [scipy.sparse.lil_array](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.lil_array.html#scipy.sparse.lil_array).

## Sparse eigenvalue problems [file](scipy_sparse_linalg_ARPACK.ipynb)
Documentation link: https://docs.scipy.org/doc/scipy/tutorial/arpack.html

All of the functionality provided in ARPACK is contained within the two high-level interfaces [scipy.sparse.linalg.eigs](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.linalg.eigs.html#scipy.sparse.linalg.eigs) and [scipy.sparse.linalg.eigsh](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.linalg.eigsh.html#scipy.sparse.linalg.eigsh). [eigs](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.linalg.eigs.html#scipy.sparse.linalg.eigs) provides interfaces for finding the eigenvalues/vectors of real or complex nonsymmetric square matrices, while [eigsh](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.linalg.eigsh.html#scipy.sparse.linalg.eigsh) provides interfaces for real-symmetric or complex-hermitian matrices.

## FFT [file](scipy_fft_skp.ipynb)
Documentation link: https://docs.scipy.org/doc/scipy/reference/fft.html#module-scipy.fft

