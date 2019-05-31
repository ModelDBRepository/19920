NEURON mod files for CaT currents from the paper:
McRory et al., J.Biol.Chem. 276:3999 (2001).

Running the kinetics.hoc simulation file will show 
the activation and inactivation steady-states and time constants
of the three members of the LVA calcium channels family studied
in this paper (alpha-1G, -1H, and -1I), with kinetic parameters 
from functional expression in transfected cells.

Parameters for activation/inactivation are from the paper.
However, not all the parameters used to fit (with single exponentials)
the experimental values for the time constants were given in the paper. 
Those explicitly reported were used to constrain a fit 
of experimental values derived from Fig.6.

Ca++ reversal potential is calculated from Nerst equation, using
internal and external Ca++ concentrations.
Default values are [Ca]i=50nM and [Ca]o=2mM.

Under unix systems:
to compile the mod files use the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui kinetics.hoc

Under Windows:
to compile the mod files use the "mknrndll" command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

Questions on the model parameters should be directed to the 
authors of paper.

Questions on how to use this model with NEURON
should be directed to michele@pa.ibf.cnr.it
