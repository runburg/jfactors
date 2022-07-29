# jfactors
These are the data products associated with arXiv:2110.09653
Please contact Jack Runburg at runburg [at] hawaii [dot] edu if you have any questions

Each directory corresponds to a different dark matter distribution rho(r). Note that we use scale-free quantities throughout.
Details on restoring units are in the paper.

For the NFW profiles, the number appended onto the directory (e.g., 0-8  indicates that the DM profile used is a generalized NFW profile with gamma=0.8 (we avoid dots in the path name to avoid any ambiguities)).
For the Einasto profiles, the numbers correspond to the value of alpha.

In each directory, there are four files:

phi.txt: contains the scale-free gravitational potential Phi(r) where the first column of the data are the r values and the second column are the Phi values.
f.txt: contains the scale-free velocity distribution f(E) where the first column of the data are E values and the second column are the f values.
p2.txt: contains P2 (which is the analog of the square of the DM profile rho^2) where the first column are the r values, the second column are P2 for s-wave DM, the third column are P2 for p-wave DM, the third column are P2 for d-wave DM and the fourth column are P2 for Sommerfeld DM
j.txt: contains the scale-free J-factor, J(theta), where the first column are the theta values, the second column are J for s-wave DM, the third column are J for p-wave DM, the third column are J for d-wave DM and the fourth column are J for Sommerfeld DM. Note that these values are unnormalized. To get the same values as those seen in Figs. 1-4 of the paper, divide by J^{tot} (see Eq. 6 of the paper).

