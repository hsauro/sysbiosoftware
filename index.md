---
title: Home
layout: home
---

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |


| Name         | Description            | OS    | License | SBML Support |
|:-------------|:-----------------------|:------|:--------|:-------------|
| [iBioSim] | iBioSim  is a computer-aided design (CAD) tool for the modeling, analysis, and design of genetic circuits. | multiplatform (Java/C++) | Apache | Yes |
| [CompuCell3D] | GUI/Scripting tool | for building and simulating multicellular models. | multiplatform (C++/Python) | MIT | Yes, but only for reactions. |
| [COPASI] | GUI tool for analyzing and simulating SBML models. | multiplatform (C++) | Artistic License | http://www.copasi.org | Yes |
| [Cytosim] || Spatial simulator for flexible cytoskeletal filaments and motor proteins | Mac, Linux, Cygwin (C++) | GPL3 | Not applicable |
| [libroadrunner] | High-performance software library for simulation and analysis of SBML models | multiplatform (C/C++) | Apache License |  Yes |
| [massPy] | Simulation tool | multiplatform (Python) MIT | Yes |
| [MCell] | GUI tool for particle-based spatial stochastic simulation with individual molecules | multiplatform | MIT and GPLv2 | Not applicable |
| [OpenCOR] | A cross-platform modelling environment, which is aimed at organizing, editing, simulating, and analysing CellML files on Microsoft Windows|Windows, Linux and macOS. | ultiplatform (C++/Python) | GPLv3 | Uses CellML |
| [PhysiBoSS] | A specialized form of the PhysiCell agent-based modeling platform that directly integrates Boolean signaling networks into cell | multiplatform (C++) | BSD-3 | Yes, but only for reactions |
| [PhysiCell] | A agent-based modeling framework for multicellular systems biology. |multiplatform (C++)| BSD-3 | Yes, but only for reactions |
| [PySCeS] | Python tool for modeling and analyzing SBML models | multiplatform (Python| BSD-3 | https://pysces.sourceforge.net/ | Yes |
| [pySB] | Python-based platform with specialization in rule-based models. | multiplatform (Python)| BSD-3 | Partial |
| [ReaDDy] | Particle-based spatial simulator with intermolecular potentials | Linux and Mac | Custom  | Not applicable |
| [SBSCL] | Java library with efficient and exhaustive support for SBML | multiplatform (Java) | LGPL | https://draeger-lab.github.io/SBSCL/ | Yes
| [SBW] | A distributed workbench that includes many modeling tools | multiplatform (C/C++) | BSD-3  | Yes |
| [Smoldyn] | Particle-based simulator for spatial stochastic simulations with individual molecules | multiplatform (C/C++/Python) | LGPL  Not applicable |
| [Spatiocyte] | Spatial modeling software that uses a fine lattice with up to one molecule per site | multiplatform | Unknown | Not applicable |
| [SpringSaLaD] | Particle-based spatial simulator in which molecules are spheres that are linked by springs | multiplatform | Unknown | Not applicable |
| [STEPS] | Stochastic reaction-diffusion and membrane potential solver on distributed meshes | multiplatform (C++/Python) | GPLv2 | 
| [Tellurium (software)] | Simulation environment that packages multiple libraries into one platform. | multiplatform (Python) | Apache License | Yes |
| [URDME] | Stochastic reaction-diffusion simulation on unstructured meshes | MatLab on Mac, Linux | GPL3 | Not applicable |
| VCell | Comprehensive modeling platform for non-spatial, spatial, deterministic and stochastic simulations, including both reaction networks and reaction rules. 
| multiplatform (Java) | MIT | Yes |

This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, just click "[use this template]"!

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[iBioSim]: https://github.com/MyersResearchGroup/iBioSim
[VCell]: https://vcell.org
[COPASI]: https://github.com/sys-bio/roadrunner
[STEPS]: https://steps.sourceforge.net
[MCell]: https://mcell.org/index.html
[PhysiCell]: http://physicell.org
[OpenCor]: https://opencor.ws/
[URDME]: http://urdme.github.io/urdme/
[SBSCL]: https://sbw.sourceforge.net/
[PySCeS]: https://pysb.org/
[Smoldyn]: https://www.smoldyn.org/
[SpringSaLaD]: https://vcell.org/ssalad 
[STEPS]: http://google.com
[libroadrunner]:  http://libroadrunner.org
[massPy]: https://github.com/SBRG/MASSpy 
[PhysiBoSS]: https://github.com/PhysiBoSS/PhysiBoSS
[CompuCell3D]: https://compucell3d.org 
[Cytosim]: http://cytosim.org 
[pySB]: https://pysb.org/
[Tellurium (software)]: https://github.com/sys-bio/tellurium 
[SBW]: https://sbw.sourceforge.net/
[ReaDDy]:https://readdy.github.io/index.html
[Spatiocyte]: https://spatiocyte.org

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
