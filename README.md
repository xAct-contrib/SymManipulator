SymManipulator
======
 SymManipulator is a package for handling symmetrized tensor expressions. Some relevant features of the package are:
A flexible SymH object that can represent a general symmetrized tensor expression.
The complete symmetry of the symmetrized object can be computed. When imposing a symmetric or antisymmetric group, a special quicker code is used. Older versions computed only a subgroup, but from version 0.8.5 the complete group is computed.
Canonicalization of the SymH representation using the internal symmetries can also be done.
Computation of a complete irreducible decomposition of an arbitrary spinor expression can be done using a single tool. (New in version 0.8.3)
Fundamental spinor operators and tools for handling them are introduced. These are the irreducible parts of the covariant derivative acting on symmetric spinors. (New feature as of version 0.9.0)
Improved code for some group theoretical algorithms in the external xperm executable. (New in version 0.9.2)
IndepIrrDecompose can remove dependencies between irreducible pieces of IrrDecompose. (New in version 0.9.4)
