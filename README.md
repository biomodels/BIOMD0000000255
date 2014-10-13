

This is A431 IERMv1.0 model described in the article  
**Input-output behavior of ErbB signaling pathways as revealed by a mass action model trained against dynamic data.**   
William W Chen, Birgit Schoeberl, Paul J Jasper, Mario Niepel, Ulrik B
Nielsen, Douglas A Lauffenburger and Peter K Sorger. _Molecular Systems
Biology_ 2009; 5:239. PMID:
[19156131](http://www.ncbi.nlm.nih.gov/pubmed/19156131) , DOI:
[10.1038/msb.2008.74](http://dx.doi.org/10.1038/msb.2008.74)

Abstract:  
The ErbB signaling pathways, which regulate diverse physiological responses
such as cell survival, proliferation and motility, have been subjected to
extensive molecular analysis. Nonetheless, it remains poorly understood how
different ligands induce different responses and how this is affected by
oncogenic mutations. To quantify signal flow through ErbB-activated pathways
we have constructed, trained and analyzed a mass action model of immediate-
early signaling involving ErbB1-4 receptors (EGFR, HER2/Neu2, ErbB3 and
ErbB4), and the MAPK and PI3K/Akt cascades. We find that parameter sensitivity
is strongly dependent on the feature (e.g. ERK or Akt activation) or condition
(e.g. EGF or heregulin stimulation) under examination and that this context
dependence is informative with respect to mechanisms of signal propagation.
Modeling predicts log-linear amplification so that significant ERK and Akt
activation is observed at ligand concentrations far below the K(d) for
receptor binding. However, MAPK and Akt modules isolated from the ErbB model
continue to exhibit switch-like responses. Thus, key system-wide features of
ErbB signaling arise from nonlinear interaction among signaling elements, the
properties of which appear quite different in context and in isolation.

The sbml model is available as supplemental material to the article and at
<http://www.cdpcenter.org/resources/models/chen-et-al-2008/> . It was slightly
changed to make it valid SBML and to incorporate the step functions, described
in the readme file and needed for inhibitor preincubation. the equilibration
processes end at 1800 sec, so to reproduce the dynamics shown in the
publication and supplemental material, only the time points after 1800 need to
be considered. The parameter set is the hand fitted one used for Sfigure 3 in
the supplemental materials. All species are in molecules, apart from HRG, EGF
and Inh, which are in M.

The results shown in SFigure 3 can be calculated dividing the parameters
_ERK_PP_ , _AKT_PP_ and _ERB_B1_P_tot_ by _ERK_t_ , _AKT_t_ and _EGFR_t_ ,
respectively. Somehow we did not find the right scaleing factor for the
phosphorylated ErbB1 receptor. Therefore the model does only qualitatively
reproduces the timecourses shown in the first row of Sfigure 3.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Nov������re N., Bornstein B.,
Broicher A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra
M., Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)

