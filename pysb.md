---
layout: default
title: pySB
parent: index
nav_order: 2
---

{{Infobox software
| name                   = PySB
| logo                   = <!-- [[File: ]] -->
| screenshot             = <!-- [[File: ]] --> 
| caption                = 
| collapsible            = 
| author                 = 
| developer              = 
| released               = {{Start date and age|2019|05|15}}
| latest release version = 1.14
| latest release date    = {{Start date and age|2022|08|29}}
| programming language   = [[Python]]
| operating system       = [[Linux]], [[macOS]] and [[Microsoft Windows]]
| platform               = [[Python]]
| size                   = 
| language               = 
| status                 = 
| genre                  = 
| license                = [[BSD License]]
| website                = {{URL|https://pysb.org/}}
}}

== PySB ==

PySB..<ref>{{cite journal |last1=Lopez |first1=Carlos F |last2=Muhlich |first2=Jeremy L |last3=Bachman |first3=John A |last4=Sorger |first4=Peter K |title=Programming biological models in Python using PySB |journal=Molecular Systems Biology |date=January 2013 |volume=9 |issue=1 |pages=646 |doi=10.1038/msb.2013.1|pmid=23423320 |pmc=3588907 }}</ref> is a Python-based open-source simulator for cellular systems developed by Carlos Lopez. The primary capability of pySB than makes it stand out from other similar simulators is that it supports [[rule-based modeling]]<ref>{{cite journal |last1=Chylek |first1=Lily A. |last2=Harris |first2=Leonard A. |last3=Tung |first3=Chang‐Shung |last4=Faeder |first4=James R. |last5=Lopez |first5=Carlos F. |last6=Hlavacek |first6=William S. |title=Rule‐based modeling: a computational approach for studying biomolecular site dynamics in cell signaling systems |journal=WIREs Systems Biology and Medicine |date=January 2014 |volume=6 |issue=1 |pages=13–36 |doi=10.1002/wsbm.1245|pmid=24123887 |pmc=3947470 }}</ref>. The software runs on all major platforms, Windows, Mac OS, and Linux. PySB is also discussed at [[Multi-state modeling of biomolecules]].

== Capabilities<ref>{{cite web |title=readthedocs for pysb |url=https://pysb.readthedocs.io/en/stable/}}</ref> ==

* Can be used to describe rule-based models of complex biochemical pathways, particularly signaling pathways. 
* Can be used to create model libraries based on macros to reuse.
* Uses standard python sci-py numerical libraries for carrying out simulations.

== Applications of pySB ==

pySB has been used in a variety of research projects. The following lists a small number of those studies (out of a total of 230 mentions in the scientific literature (as of Oct 2022).

* Studies on substrate selectivity in cyclooxygenase-2<ref>{{cite journal |last1=Mitchener |first1=Michelle M. |last2=Hermanson |first2=Daniel J. |last3=Shockley |first3=Erin M. |last4=Brown |first4=H. Alex |last5=Lindsley |first5=Craig W. |last6=Reese |first6=Jeff |last7=Rouzer |first7=Carol A. |last8=Lopez |first8=Carlos F. |last9=Marnett |first9=Lawrence J. |title=Competition and allostery govern substrate selectivity of cyclooxygenase-2 |journal=Proceedings of the National Academy of Sciences |date=6 October 2015 |volume=112 |issue=40 |pages=12366–12371 |doi=10.1073/pnas.1507307112|pmid=26392530 |pmc=4603459 |bibcode=2015PNAS..11212366M |doi-access=free }}</ref>

* Information discrimination in T-cell signaling<ref>{{cite journal |last1=Ganti |first1=Raman S. |last2=Lo |first2=Wan-Lin |last3=McAffee |first3=Darren B. |last4=Groves |first4=Jay T. |last5=Weiss |first5=Arthur |last6=Chakraborty |first6=Arup K. |title=How the T cell signaling network processes information to discriminate between self and agonist ligands |journal=Proceedings of the National Academy of Sciences |date=20 October 2020 |volume=117 |issue=42 |pages=26020–26030 |doi=10.1073/pnas.2008303117|pmid=33020303 |pmc=7585026 |bibcode=2020PNAS..11726020G |doi-access=free }}</ref>

* Modeling of [[JNK3]] cascade<ref>{{cite journal |last1=Perry |first1=Nicole A. |last2=Kaoud |first2=Tamer S. |last3=Ortega |first3=Oscar O. |last4=Kaya |first4=Ali I. |last5=Marcus |first5=David J. |last6=Pleinis |first6=John M. |last7=Berndt |first7=Sandra |last8=Chen |first8=Qiuyan |last9=Zhan |first9=Xuanzhi |last10=Dalby |first10=Kevin N. |last11=Lopez |first11=Carlos F. |last12=Iverson |first12=T. M. |last13=Gurevich |first13=Vsevolod V. |title=Arrestin-3 scaffolding of the JNK3 cascade suggests a mechanism for signal amplification |journal=Proceedings of the National Academy of Sciences |date=15 January 2019 |volume=116 |issue=3 |pages=810–815 |doi=10.1073/pnas.1819230116|pmid=30591558 |pmc=6338856 |bibcode=2019PNAS..116..810P |doi-access=free }}</ref>

* Inverted control of eukaryotic gene expression<ref>{{cite journal |last1=Park |first1=Heungwon |last2=Subramaniam |first2=Arvind R. |title=Inverted translational control of eukaryotic gene expression by ribosome collisions |journal=PLOS Biology |date=18 September 2019 |volume=17 |issue=9 |pages=e3000396 |doi=10.1371/journal.pbio.3000396|pmid=31532761 |pmc=6750593 }}</ref>

* Construction of Cellular Responses and Global Drug Mechanisms of Action<ref>{{cite journal |last1=Norris |first1=Jeremy L. |last2=Farrow |first2=Melissa A. |last3=Gutierrez |first3=Danielle B. |last4=Palmer |first4=Lauren D. |last5=Muszynski |first5=Nicole |last6=Sherrod |first6=Stacy D. |last7=Pino |first7=James C. |last8=Allen |first8=Jamie L. |last9=Spraggins |first9=Jeffrey M. |last10=Lubbock |first10=Alex L. R. |last11=Jordan |first11=Ashley |last12=Burns |first12=William |last13=Poland |first13=James C. |last14=Romer |first14=Carrie |last15=Manier |first15=M. Lisa |last16=Nei |first16=Yuan-wei |last17=Prentice |first17=Boone M. |last18=Rose |first18=Kristie L. |last19=Hill |first19=Salisha |last20=Van de Plas |first20=Raf |last21=Tsui |first21=Tina |last22=Braman |first22=Nathaniel M. |last23=Keller |first23=M. Ray |last24=Rutherford |first24=Stacey A. |last25=Lobdell |first25=Nichole |last26=Lopez |first26=Carlos F. |last27=Lacy |first27=D. Borden |last28=McLean |first28=John A. |last29=Wikswo |first29=John P. |last30=Skaar |first30=Eric P. |last31=Caprioli |first31=Richard M. |title=Integrated, High-Throughput, Multiomics Platform Enables Data-Driven Construction of Cellular Responses and Reveals Global Drug Mechanisms of Action |journal=Journal of Proteome Research |date=3 March 2017 |volume=16 |issue=3 |pages=1364–1375 |doi=10.1021/acs.jproteome.6b01004|pmid=28088864 }}</ref>

These have all been impactful studies (Google Scholar) and indicate that pySB is being used in a variety of important research areas.

== Notability ==

There are a number of distinguishing features of pySB that make it standout from other similar cellular modeling platforms:

* PySB is the only python-based simulation package for systems biology that supports [[rule-based modeling]]. 

* PySB can translate BioNetGen<ref>{{cite journal |last1=Blinov |first1=M. L. |last2=Faeder |first2=J. R. |last3=Goldstein |first3=B. |last4=Hlavacek |first4=W. S. |title=BioNetGen: software for rule-based modeling of signal transduction based on the interactions of molecular domains |journal=Bioinformatics |date=22 November 2004 |volume=20 |issue=17 |pages=3289–3291 |doi=10.1093/bioinformatics/bth378|pmid=15217809 }}</ref> and Kappa<ref>{{cite journal |last1=Boutillier |first1=Pierre |last2=Maasha |first2=Mutaamba |last3=Li |first3=Xing |last4=Medina-Abarca |first4=Héctor F |last5=Krivine |first5=Jean |last6=Feret |first6=Jérôme |last7=Cristescu |first7=Ioana |last8=Forbes |first8=Angus G |last9=Fontana |first9=Walter |title=The Kappa platform for rule-based modeling |journal=Bioinformatics |date=1 July 2018 |volume=34 |issue=13 |pages=i583–i592 |doi=10.1093/bioinformatics/bty272|pmid=29950016 |pmc=6022607 }}</ref> rules into its own rule-based language. 

* PySB also allows users to divide models into modules and to call libraries of reusable elements (macros) that encode standard biochemical actions. 

A number of reviews and commentaries have been written that discuss pySB:

* Slater<ref>{{cite journal |last1=Slater |first1=Ted |title=Recent advances in modeling languages for pathway maps and computable biological networks |journal=Drug Discovery Today |date=February 2014 |volume=19 |issue=2 |pages=193–198 |doi=10.1016/j.drudis.2013.12.011|pmid=24444544 }}</ref>. describes in detail the pros and cons of a variety of rule-based languages and platforms, including pySB

* Mitra and Hlaveck<ref>{{cite journal |last1=Mitra |first1=Eshan D. |last2=Hlavacek |first2=William S. |title=Parameter estimation and uncertainty quantification for systems biology models |journal=Current Opinion in Systems Biology |date=December 2019 |volume=18 |pages=9–18 |doi=10.1016/j.coisb.2019.10.006|pmid=32719822 |pmc=7384601 }}</ref> briefly discuss the importance of pySB, where they state: "Another package of note is PySB which has support for BNGL"

* Chicklet et al<ref>{{cite journal |last1=Chylek |first1=Lily A. |last2=Harris |first2=Leonard A. |last3=Tung |first3=Chang‐Shung |last4=Faeder |first4=James R. |last5=Lopez |first5=Carlos F. |last6=Hlavacek |first6=William S. |title=Rule‐based modeling: a computational approach for studying biomolecular site dynamics in cell signaling systems |journal=WIREs Systems Biology and Medicine |date=January 2014 |volume=6 |issue=1 |pages=13–36 |doi=10.1002/wsbm.1245|pmid=24123887 |pmc=3947470 }}</ref>, discuss at length a variety of rule-based modeling platforms but particularly pySB.

== SBML Support ==

pySB is able to export [[SBML]] in flattened form<ref>{{cite web |title=pySB Export |url=https://pysb.readthedocs.io/en/stable/modules/export/index.html}}</ref>. That is, the rule-based model is converted into explicit reactions. This means that the rule-based formalism is not preserved. 

For import, pySB converts the SBML into [[BioNetGen]] first using [[BioNetGen]] application. pySB then imports the BioNetGen format using the pySB [[BioNetGen]] importer. This means import is limited by the import capabilities of [[BioNetGen]]<ref>{{cite web |title=pySB Import |url=https://pysb.readthedocs.io/en/stable/modules/importers/index.html}}</ref>

== See also ==
* [[List of systems biology modeling software]]

== References ==
<!-- Inline citations added to your article will automatically display here. See en.wikipedia.org/wiki/WP:REFB for instructions on how to add citations. -->
{{reflist}}

== External links ==
* [https://pysb.org/ home page]
* [https://github.com/pysb/pysb GitHub page]

<!--- Categories --->
[[:Category:Systems biology]]
[[:Category:Ordinary differential equations]]
[[:Category:Software using the BSD license]]
