# braces64_55
This repository contains all left braces with additive group isomorphic to C4 × C4 × C4 obtained by Adolfo Ballester-Bolinches, Ramón Esteban-Romero, and Vicent Pérez-Calabuig.
The braces are presented in the form of triply factorised groups.

The tgz archives contain files with names like `BRACES64_55/BRACES_199c8_2q5_672.g`. This file encodes the information to recover with GAP the skew left braces with additive group `SmallGroup(64, 55)` and multiplicative group isomorphic to `SmallGroup(64, 199)` for which the centraliser of action of the multiplicative group on the additive group is isomorphic to `SmallGroup(8, 2)`, the corresponding quotient is isomorphic to   `SmallGroup(8, 5)` (here 8=64/8), and the length of the conjugacy classes of the corresponding regular subgroups in the holomorph is 672.

The trifactorised groups are stored as records that can be read with the function `FromRec2Trifact` of the `trifact2braces.g` file. This function admits a record as an argument and returns a group `G` with `G!.K` as additive group, `G!.C` as multiplicative group, and `G!.D` as diagonal type subgroup. This group can be converted to a skew brace in the sense of hte YangBaxter package for GAP of Konovalov and Vendramin by means of the function `FromTrifact2Skewbrace`.
