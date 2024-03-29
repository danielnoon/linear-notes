This Exam: Chapters 3, 4, 5

* Determinants (3.1-3.2)
  * 3.3 not on exam
  * How to compute $3\times 3$ to $n\times n$ determinants
  * Cofactor expansion
  * When matrices are easy to find determinants
    * Lots of zeros
    * triangular shapes (product along diagonal)
  * How determinants are affected by
    * Row operations
      * Swap rows (change sign)
      * Scale rows (scale determinant)
      * Row addition (does nothing)
    * Matrix operations
      * inverse (inverse determinant)
      * multiplication (product of determinants)
      * transpose (do nothing)
  * Important property of determinants: If $\det A = 0$, $A$ is not invertible. Add this to long list of invertible matrix properties.
* Subspaces/Coordinates (4.1-4.6)
  * 4.4 not on exam
  * Definition of vectors/subspaces
    * Spanning sets from subspaces of the space where their vectors live (4.1)
    * $\text{span}\{\vec v_1,\dots,\vec v_p\}=\{c_1\vec v_1+c_2\vec v_2+\dots+c_p\vec v_p\}$
  * Important types of subspaces
    * $\text{Nul}A$
    * $\text{Col}A​$
  * Bases (4.3)
    * Smallest linearly independent set that spans a space
      * Previous methods for finding NulA, ColA finds their bases
  * Dimension
    * Number of vectors in a basis
  * Bringing everything together (4.6)
    * Rank is just dimension of the column space of A
    * The “rank theorem” says:
      * $\text{rank} +\dim(\text{Nul}A) = n$ for $A$ $m\times n$.
  * Coordinate Systems (4.7)
    * If $B=\{\vec b_1,\dots,\vec b_n\}$ is a basis of $\mathbb R^n$ then $P_B = [\vec b_1,\dots,\vec b_n]$ is a “[change of basis](4.7-change-of-basis)”
* Eigenstuff (5.1-5.5)
  * 5.3, 5.4 not on exam
  * If $A\vec x = \lambda\vec x$ for $\vec x \ne \vec 0$ and $\lambda$ constant, then $\lambda$ is and “eigenvalue.” $\vec x$ is an “eigenvector.”
  * To find $\lambda$, solve $0=\det(A-\lambda I)$.
  * To find $\vec x$, obtain parametric solutions to $(A-\lambda I)\vec x = 0$.
  * If $A$ is $n\times n$:
    * has at most $n$ $\lambda$s (exactly n counting multiplicity)
    * eigenspace for $\lambda$ is dimension of multiplicity of $\lambda$ *or lower*.
    * There is always *at least one* non-trivial solution.
    * Sometimes, $\lambda$ is complex. These eigenvalues come in pairs.
    * If  $\lambda=0$ is an eigenvalue, $A$ is not invertible.

