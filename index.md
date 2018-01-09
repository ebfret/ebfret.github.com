### Consensus analysis of many single-molecule FRET time series

ebFRET is a library written in Matlab for the analysis of single-molecule FRET time series with hidden Markov models. 

![Example Traces](images/ebfret_mainwindow.png)

ebFRET is the successor of [vbFRET](http://vbfret.sourceforge.net), which it improves upon by performing combined analysis of multiple time series at once. This approach, known as _empirical Bayes_, is both more accurate and statistically robust. It also enables more advanced analysis use cases such as sub-population detection.

### Get the Source

The ebFRET source code (with graphical user interface) can be downloaded here [[git](https://github.com/ebfret/ebfret-gui); [zip](https://github.com/ebfret/ebfret-gui/releases/)]. Please see [README](https://github.com/ebfret/ebfret-gui/blob/master/README.md) and [User Guide](https://github.com/ebfret/ebfret-gui/blob/master/documentation/ebfret_user_guide.pdf?raw=true) for installation instructions.  

A command-line version of the code is also available for advanced analysis tasks, such as detection of subpopulations, which cannot be directly accomplished in the GUI [[git](https://github.com/ebfret/ebfret-script); [zip](https://github.com/ebfret/ebfret-script/archive/master.zip)].

Code to plot transition density plots (TDP) as per ``Observation and Analysis of RAD51 Nucleation Dynamics at Single-Monomer Resolution'' in Methods in Enzymology by Subramanyam et al. can be found [here](https://github.com/ebfret/TransitionDensityPlots).

### Papers

_``Hierarchically-coupled hidden Markov models for learning kinetic rates from single-molecule data.''_
Jan-Willem van de Meent (@jwvdm), Jonathan E. Bronson, Frank Wood, Ruben L. Gonzalez Jr., Chris H. Wiggins. [International Conference on Machine Learning 2013](http://icml.cc/2013/) [[pdf](https://github.com/ebfret/paper-icml/raw/master/vandemeent_icml_2013.pdf)]

_``Empirical Bayes methods enable advanced population-level analyses of single-molecule FRET experiments.''_
Jan-Willem van de Meent (@jwvdm), Jonathan E. Bronson, Chris H. Wiggins, Chris H. Wiggins, Ruben L. Gonzalez Jr. Accepted for publication in the [Biophysical Journal](http://www.cell.com/biophysj/home) [[pre-print](pdf/vandemeent_bpj_2014_preprint.pdf); [supplementary](pdf/vandemeent_bpj_2014_supplementary.pdf)]

### Slides

_``Learning Kinetic Models from Single-Molecule Experiments''_, ICML 2013 [[pdf](pdf/jwvdm_icml_spotlight.pdf)] 

_``Learning Kinetic Pathways from Single-Molecule FRET Measurements''_, Columbia 2012 [[pdf](pdf/jwvdm_ibio_columbia.pdf)]