# Weyl
Apply the weyl equation to calculate the number of roots from a specified electron configuration

The weyl equation:

<img width="447" alt="Bildschirmfoto 2020-11-29 um 17 38 28" src="https://user-images.githubusercontent.com/62510148/100548036-4f1aa300-326a-11eb-8869-ccdb8a97d66d.png">

with N being the number of orbitals, n the number of electrons and S the total spin.

Example:

A C atom has configuration 1s2 2s2 2p2. We can ignore the closed shells, so we look at 2p2. This has n = 3, N = 2, S = 0 (singlet) or 1 (triplet).

Giving N and n to the script outputs:

Type number of electrons: 2
Type number of spatial orbitals: 2

The total number of states for your system is:      6

Your possible spin multiplicities are: 3 1

The number of roots for the multiplicity   3 is:    1
The number of roots for the multiplicity   1 is:    3

The weigths of the roots are: 0.250000, 0.750000

Sum of (Multiplicity x number of roots) gives:      6

Everything correct!
