ACOTSPQAP: Ant Colony Optimization Algorithms for the Travelling Salesman Problem and the Quadratic Assignment Problem
===============================================================================
        
Manuel López-Ibáñez and Thomas Stützle
<http://iridia.ulb.ac.be/aco-tsp-qap/>

-------------------------------------------------------------------------------

ACOTSPQAP is a software package that implements various Ant Colony Optimization
algorithms for the symmetric travelling salesman problem (TSP) and the
quadratic assignment problem (QAP). The ACO algorithms implemented are Ant
System (AS), Elitist Ant System (EAS), MAX-MIN Ant System (MMAS), Rank-based
Ant System (RAS), Best-Worst Ant System (BWAS), and Ant Colony System
(ACS).  These algorithms may be combined with problem-specific local search.

The goal of this software is to provide a reasonable high-performing
implementation of ACO algorithms under a component-wise framework.  Individuals
components of the ACO algorithms can be tuned by using more than 40
command-line parameters (see `--help`).  Additional parameters control
parameter variation (see [2]).

The implementation builds upon the earlier [ACOTSP](http://iridia.ulb.ac.be/~mdorigo/ACO/aco-code/public-software.html) package.

Relevant literature:

1. Manuel López-Ibáñez, Thomas Stützle, and Marco Dorigo. Ant Colony
   Optimization: A Component-Wise Overview. In R. Martí, P. M. Pardalos, and
   M. G. C. Resende, editors, Handbook of Heuristics, pages 1–37. Springer
   International Publishing, 2017. doi: 10.1007/978-3-319-07153-4_21-1

2. M. López-Ibáñez and T. Stützle. Automatically improving the anytime
    behaviour of optimisation algorithms. European Journal of Operational
    Research, 2013. doi:10.1016/j.ejor.2013.10.043.


Content
-------

The package contains the setup files required to tune the parameters using
[irace](https://mlopez-ibanez.github.io/irace/)

License
-------

ACOTSPQAP is Copyright (c) 2013-2015 
Manuel Lopez-Ibanez <manuel.lopez-ibanez@ulb.ac.be>
Thomas Stuetzle <stuetzle@ulb.ac.be>

This program is free software (software libre); you can redistribute
it and/or modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

IMPORTANT NOTE: Please be aware that the fact that this program is
released as Free Software does not excuse you from scientific
propriety, which obligates you to give appropriate credit! If you
write a scientific paper describing research that made substantive use
of this program, it is your obligation as a scientist to (a) mention
the fashion in which this software was used in the Methods section;
(b) mention the algorithm in the References section. The appropriate
citation is given above.

The original ACOTSP is Copyright (c) Thomas Stuetzle, 2002.
The README and license information of the original ACOTSP is
reproduced verbatim below can be found in the file `README-ACOTSP.txt`
