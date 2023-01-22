---
title: pysb
layout: home
---

name                   = PySB

released               = Start date and age: 2019/05

latest release version = 1.14

latest release date    = Start date and age: 2022/08/29

programming language   = Python

operating system       = Linux, macOS and Microsoft Windows

platform               = Python

license                = BSD License

website                = [https://pysb.org/](https://pysb.org/)

PySB
----

PySB.Programming biological models in Python using PySB, (Molecular Systems Biology, January 2013, 9(1), p646, doi=10.1038/msb.2013.1) is a Python-based open-source simulator for cellular systems developed by Carlos Lopez. The primary capability of pySB than makes it stand out from other similar simulators is that it supports rule-based modeling (Rule‐based modeling: a computational approach for studying biomolecular site dynamics in cell signaling systems, WIREs Systems Biology and Medicine,January 2014, 6(1), p13–36, doi=10.1002/wsbm.1245). The software runs on all major platforms, Windows, Mac OS, and Linux. PySB is also discussed at Multi-state modeling of biomolecules.

Capabilties
-----------
 
* Can be used to describe rule-based models of complex biochemical pathways, particularly signaling pathways. 
* Can be used to create model libraries based on macros to reuse.
* Uses standard python sci-py numerical libraries for carrying out simulations.

Applications of pySB
--------------------

pySB has been used in a variety of research projects. The following lists a small number of those studies (out of a total of 230 mentions in the scientific literature (as of Oct 2022).

* Studies on substrate selectivity in cyclooxygenase-2 (Competition and allostery govern substrate selectivity of cyclooxygenase-2, Proceedings of the National Academy of Sciences, October 2015, 112(40), p12366–12371, doi=10.1073/pnas.1507307112)

* Information discrimination in T-cell signaling (How the T cell signaling network processes information to discriminate between self and agonist ligands, Proceedings of the National Academy of Sciences, 20 October 2020, 117(42), p26020–26030, doi=10.1073/pnas.2008303117)

* Modeling of JNK3 cascade (Arrestin-3 scaffolding of the JNK3 cascade suggests a mechanism for signal amplification, Proceedings of the National Academy of Sciences, 15 January 2019, 116(3), p810–815, doi=10.1073/pnas.1819230116)

* Inverted control of eukaryotic gene expression (Inverted translational control of eukaryotic gene expression by ribosome collisions, PLOS Biology, September 2019, 17 (9), pe3000396, doi=10.1371/journal.pbio.3000396)

* Construction of Cellular Responses and Global Drug Mechanisms of Action (Integrated, High-Throughput, Multiomics Platform Enables Data-Driven Construction of Cellular Responses and Reveals Global Drug Mechanisms of Action, Journal of Proteome Research, March 2017, 16(3), p1364–1375, doi=10.1021/acs.jproteome.6b01004)

These have all been impactful studies (Google Scholar) and indicate that pySB is being used in a variety of important research areas.

Notability
----------

There are a number of distinguishing features of pySB that make it standout from other similar cellular modeling platforms:

* PySB is the only python-based simulation package for systems biology that supports rule-based modeling. 

* PySB can translate BioNetGen (BioNetGen: software for rule-based modeling of signal transduction based on the interactions of molecular domains, Bioinformatics, November 2004, 20, (17), p3289–3291, doi=10.1093/bioinformatics/bth378) rules into its own rule-based language. 

* PySB also allows users to divide models into modules and to call libraries of reusable elements (macros) that encode standard biochemical actions. 

A number of reviews and commentaries have been written that discuss pySB:
,
* Slater (Recent advances in modeling languages for pathway maps and computable biological networks, Drug Discovery Today, February 2014, 19(2), p193–198 , doi=10.1016/j.drudis.2013.12.011). describes in detail the pros and cons of a variety of rule-based languages and platforms, including pySB

* Mitra and Hlaveck (Parameter estimation and uncertainty quantification for systems biology models, Current Opinion in Systems Biology, December 2019, 18,p9–18, doi=10.1016/j.coisb.2019.10.006) briefly discuss the importance of pySB, where they state: "Another package of note is PySB which has support for BNGL"

* Chicklet et al (Rule‐based modeling: a computational approach for studying biomolecular site dynamics in cell signaling systems, WIREs Systems Biology and Medicine, January 2014, 6(1), p13–36, doi=10.1002/wsbm.1245) discuss at length a variety of rule-based modeling platforms but particularly pySB.

SBML Support
------------

pySB is able to export SBML in flattened form.. That is, the rule-based model is converted into explicit reactions. This means that the rule-based formalism is not preserved. 

For import, pySB converts the SBML into BioNetGen first using BioNetGen application. pySB then imports the BioNetGen format using the pySB BioNetGen importer. This means import is limited by the import capabilities of BioNetGen


