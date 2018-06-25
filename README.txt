In this version of LFPsim, the ion channel distribution density and size of the individual compaertments was considered in the LFP calculation.

This is the README for the model associated with the paper:

Parasuram H, Nair B, D'Angelo E, Hines M, Naldi G, Diwakar
S. Computational Modeling of Single Neuron Extracellular Electric
Potentials and Network Local Field Potentials using LFPsim,
Front. Comp. Neurosc., June 13, 2016, 10.3389/fncom.2016.00065
available at
http://journal.frontiersin.org/article/10.3389/fncom.2016.00065/abstract

LFPsim - Simulation scripts to compute Local Field Potentials (LFP)
from cable compartmental models of neurons and networks implemented in
NEURON simulation environment.

LFPsim works reliably on biophysically detailed multi-compartmental
neurons with ion channels in some or all compartments.

Associated Paper:
Parasuram H, Nair B, D'Angelo E, Hines M, Naldi G, Diwakar
S. Computational Modeling of Single Neuron Extracellular Electric
Potentials and Network Local Field Potentials using LFPsim,
Front. Comp. Neurosc., June 13, 2016, 10.3389/fncom.2016.00065
available at
http://journal.frontiersin.org/article/10.3389/fncom.2016.00065/abstract

Edited with inputs on a bug related to area. Thanks to Lucas Koelman for the corrections (https://github.com/lkoelman). 

Last updated 25-June-2018
Developed by : Harilal Parasuram & Shyam Diwakar
Computational Neuroscience & Neurophysiology Lab, School of Biotechnology, Amrita University, India.
Email: harilalp@am.amrita.edu; shyam@amrita.edu
www.amrita.edu/compneuro 
*/

How to run LFPsim
=================

1. Copy all LFPsim files and the directory into your NEURON model
directory downloaded from ModelDB. Copy lfp.mod and mea.mod from
LFPsim to the mechanism directory of the NEURON model.

2. Compile the model; if you had already compiled the model without
LFPsim, include the LFPsim mod files and re-compile using "nrnivmodl"
or "mknrndll".

3. Load your neuron or network model in NEURON.

4. On the terminal type: xopen("extracellular_electrode.hoc") to
initiate LFPsim GUI interface.

5. Set the electrode properties in the GUI.

6. Run the simulation to reconstruct LFP.

A detailed step-by-step procedure is also listed in the
How-To-LFPsim.pdf document.
