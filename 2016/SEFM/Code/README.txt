The Maude files in this directory have been developed by Antonio Cerone.


This file contains instruction on running MAUDE one the 2 case studies
contained in this directory.


The MAUDE system can be downloaded at

http://maude.cs.illinois.edu/w/index.php?title=Maude_download_and_installation


Documentation on MAUDE is available at

http://maude.cs.illinois.edu/w/index.php?title=The_Maude_System#Maude_Documentation

The first three chapter of the Maude Primer are sufficient to understand
the two case studies (but does not include anything about model checking).
For the model-checking refers to Chapter 10 of the Maude Manual.

MAUDE can also be used with an ECLIPSE plugin.


LOADING THE GENERIC FRAMEWORK

Load in the following order the two modules:
1. entities.maude
2. architecture.maude
Then load the case study.


ATM CASE STUDY

Load in the following order the modules:
1. case-1-atm-task.maude
2. case-1-atm-interfaces.maude
3. case-1-atm-exp-old.maude
4. case-1-atm-exp-new.maude

Simulation is performed by loading module
   case-1-atm-simulation.maude
which produces the first step of the simulation.
The next step of the simulation is performed by typing
in the Maude shell the following command:
   continue 1 .
Command
   continue n .
make the simulation progress by n steps.

Model checking is performed by loading modules
1. model-checker.made (predefined Maude module)
2. case-1-atm-preds.maude
3. case-1-atm-check.maude


ATC CASE STUDY

Load in the following order the modules:
1. case-2-atc-task.maude
2. case-2-atc-interfaces.maude

Simulation is performed by loading module
   case-2-atc-simulation.maude
which produces the first step of the simulation
and typing
   continue 1 .
to perform the next steps.

Model checking is performed by loading modules
1. model-checker.made (predefined Maude module)
2. case-2-atc-preds.maude
3. case-2-atc-check-incomplete.maude (incomplete decomposition)
4. case-2-atc-check-complete.maude (complete decomposition)


NOTE

The current interface state is incorporated within the interface
as the last sub-term.
Therefore, current interface state and content of the STM appear
as the last part of the term produced by the simulation or
counterexample produced by the model checker






