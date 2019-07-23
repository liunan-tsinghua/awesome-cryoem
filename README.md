# Awesome CryoEM
A collaborative list of awesome CryoEM (Electron Cryo-Microscopy) resources. Feel free to contribute!
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
</br>

<img src="imgs/cryoem1.png" width = "360px" height = "180px" alt="Cryo-EM" />



### Contributing

Please take a quick look at the [contribution guidelines](.github/CONTRIBUTING.md) first. If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you to all [contributors](https://github.com/barrykui/awesome-cryoem/graphs/contributors); you rock!

### Contents

- [Guides](#guides)
    - [Official Guides](#official-guides)
    - [Third party Guides](#third-party-guides)
- [Softwares](#softwares) 
- [Technologies](#technologies)
- [Computational Problems](#computational-problems)
- [Validation Metrics](#validation-metrics)
- [DataBases](#database)
- [Active Groups](#active-groups)


## Guides
*An awesome list of CryoEM related guides.* 




### Official Guides
[back to top](#readme) 

* [3 Mins Introduction of CryoEM](https://www.youtube.com/watch?v=BJKkC0W-6Qk) - 3 Mins Introduction of CryoEM for beginners.
* [Single-particle cryo-electron microscopy](http://www.nature.com/nmeth/journal/v13/n1/full/nmeth.3700.html) - Nature Method Review.
* [CryoEM Course](https://www.coursera.org/learn/cryo-em)
* [CryoEM 101](https://cryoem101.org)
* [MRC lab CryoEM](https://www2.mrc-lmb.cam.ac.uk/research/scientific-training/electron-microscopy/)
* [Big data in Cryo-EM](https://www.sciencedirect.com/science/article/pii/S1369527417301315)

### Third party Guides
[back to top](#readme) 

* [EMAN2 Video Tutorials](http://blake.bcm.edu/emanwiki/EMAN2/VideoTutorials)

## Methods and Softwares
[back to top](#readme) 

* [UCSF Chimera](https://www.cgl.ucsf.edu/chimera/) - An interactive visualization and analysis of structures.
* [Relion](http://www2.mrc-lmb.cam.ac.uk/relion/index.php/Main_Page) - A Bayesian approach to refinement of 3D reconstructions or 2D class averages.
    * [`New` 2.1 ](ftp://ftp.mrc-lmb.cam.ac.uk/pub/scheres/relion21_tutorial.pdf) - Tutorial (v2.1) (The quickest way to learning RELION) 
    * [Nature Protocol Paper](http://www.nature.com/nprot/journal/v11/n11/full/nprot.2016.124.html) - Resolving macromolecular structures from electron cryo-tomography data using subtomogram averaging in RELION

* [COOT](http://www2.mrc-lmb.cam.ac.uk/personal/pemsley/coot/) - A interactive visualization model building, model completion and validation.
* [EMAN2](http://blake.bcm.edu/emanwiki/EMAN2) - A scientific image processing software suite with a focus on CryoEM and CryoET.
* [PHENIX](https://www.phenix-online.org/) - Automated determination of molecular structures using X-ray crystallography and other methods.
* [Rosetta](https://www.rosettacommons.org/) - A software suite includes algorithms for computational modeling and analysis of protein structures.
    * [RosettaCM](http://www.sciencedirect.com/science/article/pii/S0969212613002979?via%3Dihub) - High-Resolution Comparative Modeling with RosettaCM
    * [RosettaES](http://www.nature.com/nmeth/journal/v14/n8/full/nmeth.4340.html) - RosettaES: a sampling strategy enabling automated interpretation of difficult cryo-EM maps(2017) 
* [FREALIGN: high-resolution refinement of single particle structures](#)
* [SIMPLE: Software for ab initio reconstruction of heterogeneous single-particles](#)
* [PRIME: probabilistic initial 3D model generation for single-particle cryo-electron microscopy](#)
* [SPIDER](http://spider.wadsworth.org) - System for Processing Image Data from Electron microscopy and Related fields.
* [CCP4](http://www.ccp4.ac.uk/) - Collaborative Computational Project No. 4 Software for Macromolecular X-Ray Crystallography.
    * [Buccaneer](#)
    * [SFTOOLS](#)
* [ResMap](http://resmap.sourceforge.net/) - computing the local resolution of 3D density maps.
* [DeepPicker](https://arxiv.org/abs/1605.01838) - Fully Automated Particle Picking using deep learning.
* [FindEM](http://www.ccpem.ac.uk/ccpem_projects.php) - CCP-EM projects, automated particle picking from electron micrographs, using Fortran
* [EMfold](http://www.meilerlab.org/index.php/servers/show?s_id=18) - Meiler Lab,  placement of helices is restricted to CryoEM density regions.
* [De novo protein structure determination from near-atomic-resolution cryo-EM maps](http://www.nature.com/doifinder/10.1038/nmeth.3287)
* [Atomic accuracy models from 4.5 Å cryo-electron microscopy data with density-guided iterative local refinement](http://www.nature.com/doifinder/10.1038/nmeth.3286)
* [cryoSPARC: algorithms for rapid unsupervised cryo-EM structure determination](http://www.nature.com/nmeth/journal/v14/n3/full/nmeth.4169.html)
    * [Building proteins in a day: Efficient 3D molecular reconstruction(CVPR2015)](#)
* [Pathwalker](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3307788/pdf/nihms350767.pdf) - Constructing and Validating Initial Cα Models from Subnanometer Resolution Density Maps with Pathwalking, TSP
* [EMBuilder](https://www.nature.com/articles/s41598-017-02725-w) - EMBuilder: A Template Matching-based Automatic Model-building Program for High-resolution Cryo-Electron Microscopy Maps

## Technologies
[back to top](#readme) 

* [Single Particle](#)
* [Tomography](#)
* [MircoED](#)

## Computational Problems
[back to top](#readme) 

### Particle Picking
* Fully Automatic
    * [DeepPicker](https://arxiv.org/abs/1605.01838) - Fully Automated Particle Picking using deep learning.
    * [FindEM](http://www.ccpem.ac.uk/ccpem_projects.php) - CCP-EM projects, automated particle picking from electron micrographs, using Fortran
    * [DeepEM](http://arxiv.org/pdf/1605.05543v1.pdf) - A deep learning approach to single-particle recognition in cryo-electron microscopy,Yanan Zhu, Qi Ouyang, Youdong Mao.
    * [SPHIRE-crYOLO](https://www.biorxiv.org/content/early/2018/06/26/356584) - SPHIRE-crYOLO: A fast and well-centering automated particle picker for cryo-EM.
    * [PIXER](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2614-y) - PIXER: an automated particle-selection method based on segmentation using a deep neural network.
    * [A fast method for particle picking in cryo-electron micrographs based on fast R-CNN](https://aip.scitation.org/doi/pdf/10.1063/1.4982020)
    * [Real-time cryo-EM data pre-processing with warp](https://www.biorxiv.org/content/10.1101/338558v1)
    * [Positive-unlabeled convolutional neural networks for particle picking in cryo-electron micrographs](https://arxiv.org/pdf/1803.08207)
    * [DRPnet](https://www.biorxiv.org/content/biorxiv/early/2019/05/05/616169.full.pdf) - Automated Particle Picking in Cryo-Electron Micrographs using Deep Regression. 
    
* Semi Automatic
    * [AutoPicker](https://www.sciencedirect.com/science/article/pii/S1047847714002615) - Semi-automated selection of cryo-EM particles in RELION-1.3.
    
### 2D Classification
### 3D Classification
* [Relion](http://www2.mrc-lmb.cam.ac.uk/relion/index.php/Main_Page) - A Bayesian approach to refinement of 3D reconstructions or 2D class averages.
* [cryoSPARC](http://www.nature.com/nmeth/journal/v14/n3/full/nmeth.4169.html) - cryoSPARC: algorithms for rapid unsupervised cryo-EM structure determination
* [AuTom](http://www.sciencedirect.com/science/article/pii/S1047847717301284) - AuTom: A novel automatic platform for electron tomography reconstruction 

### Denoising
* [GAN](https://www.biorxiv.org/content/early/2018/02/12/256792) - Generative adversarial networks as a tool to recover structural information from cryo-electron microscopy data.

### Motion Correction
* [Electron counting and beam-induced motion correction enable near-atomic-resolution single-particle cryo-EM](http://www.nature.com/nmeth/journal/v10/n6/full/nmeth.2472.html) - Xueming Li's work.  

### CTF Correction
### Model Building
* [EMAN2](http://blake.bcm.edu/emanwiki/EMAN2) - A scientific image processing software suite with a focus on CryoEM and CryoET.
* [PHENIX](https://www.phenix-online.org/) - Automated determination of molecular structures using X-ray crystallography and other methods.
* [Rosetta](https://www.rosettacommons.org/) - A software suite includes algorithms for computational modeling and analysis of protein structures.
* [De novo protein structure determination from near-atomic-resolution cryo-EM maps](http://www.nature.com/doifinder/10.1038/nmeth.3287)
* [Atomic accuracy models from 4.5 Å cryo-electron microscopy data with density-guided iterative local refinement](http://www.nature.com/doifinder/10.1038/nmeth.3286)
* [EMfold](http://www.meilerlab.org/index.php/servers/show?s_id=18) - Meiler Lab,  placement of helices is restricted to CryoEM density regions.
* SSE based methods.
* Backbone tracing methods.
* [Pathwalker](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3307788/pdf/nihms350767.pdf) - Constructing and Validating Initial Cα Models from Subnanometer Resolution Density Maps with Pathwalking, TSP
* [EMBuilder](https://www.nature.com/articles/s41598-017-02725-w) - EMBuilder: A Template Matching-based Automatic Model-building Program for High-resolution Cryo-Electron Microscopy Maps
* [Book chapter, Review](https://www.sciencedirect.com/science/article/pii/S0076687916301136?via%3Dihub) - Tools for Model Building and Optimization into Near-Atomic Resolution Electron Cryo-Microscopy Density Maps
* [MAINMAST](https://www.nature.com/articles/s41467-018-04053-7) - from [Kihara Lab](http://kiharalab.org/mainmast/),  Terashi, Genki, and Daisuke Kihara. "De novo main-chain modeling for EM maps using MAINMAST." Nature communications 9.1 (2018): 1618. 
* [A^2-Net](https://arxiv.org/abs/1901.00785), A^2-Net: Molecular Structure Estimation from Cryo-EM Density Volumes, The 33rd AAAI Conference on Artificial Intelligence (AAAI) (2019) 
* [Map_to_model](https://www.nature.com/articles/s41592-018-0173-1),[biorxiv Version](https://www.biorxiv.org/content/biorxiv/early/2018/02/16/267138.full.pdf), A fully automatic method yielding initial models from high-resolution electron cryo-microscopy	
### Model Validation

### Tomography
* [EMAN2.2](https://www.nature.com/nmeth/journal/v14/n10/full/nmeth.4405.html) - Convolutional neural networks for automated annotation of cellular cryo-electron tomograms
* [Convolutional Neural Networks for　Automated Annotation of Cellular CryoElectron　Tomograms](https://arxiv.org/pdf/1701.05567.pdf)
* [Deep learning based subdivision approach for large scale macromolecules
structure recovery from electron cryo tomograms](https://arxiv.org/pdf/1701.08404.pdf)
*  [pytom](http://pytom.org/)  [Tutorial](http://pytom.org/doc/pytom/tutorial.html) 

## Validation Metrics
[back to top](#readme) 

* [RMSD](https://en.wikipedia.org/wiki/Root-mean-square_deviation_of_atomic_positions) - Root Mean Square Deviation
* [FSC](https://en.wikipedia.org/wiki/Fourier_shell_correlation) - Fourier shell correlation.
* [B-factor](http://www.cmbi.ru.nl/bdb/theory/) -  A measure of (local) mobility in the (macro)molecule.
* [GDT-HA](http://onlinelibrary.wiley.com/doi/10.1002/prot.21753/full) - The percentage of correctly aligned residues in the 5 Å LGA sequence-independent superposition of the model and experimental structure of the target.
* [GDT-TS](#)
* [AL0](#)

## DataBases
[back to top](#readme) 

* [EMDB](https://www.ebi.ac.uk/pdbe/emdb/index.html) - The Electron Microscopy Data Bank (EMDB)
* [EMPIAR](https://www.ebi.ac.uk/pdbe/emdb/empiar) - EMPIAR, the Electron Microscopy Pilot Image Archive, is a public resource for raw, 2D electron microscopy images.
    * [EMPIAR: a public archive for raw electron microscopy image data](http://www.nature.com/doifinder/10.1038/nmeth.3806)
* [PDB](http://www.rcsb.org/pdb/home/home.do) - Protein Data Bank
* [PDBe](http://www.ebi.ac.uk/pdbe) - Protein Data Bank in Europe
* [PDBj](http://www.pdbj.org) - Protein Data Bank Japan 
* [wwPDB](http://www.wwpdb.org) - WorldWide Protein Data Bank 
* [sbkb](http://www.sbkb.org) - Structural Biology Knowledgebase, A comprehensive resource for developments both in structural genomics and structural biology.


## Active Groups

* [MRC](http://www2.mrc-lmb.cam.ac.uk/) - MRC Laboratory of Molecular Biology
    * [Richard Henderson](http://www2.mrc-lmb.cam.ac.uk/group-leaders/h-to-m/richard-henderson/) - Richard Henderson Lab (**The Nobel Prize in Chemistry 2017**)
    * [Scheres](http://www2.mrc-lmb.cam.ac.uk/groups/scheres/) - Relion Author. 
* [Joachim Frank](http://franklab.cpmc.columbia.edu/franklab) -  Franklin Lab (**The Nobel Prize in Chemistry 2017**)
* [Bob Glaeser](http://mcb.berkeley.edu/faculty/all/glaeserr) - Single-particle electron cryo-microscopy.
* [Yifan Cheng](http://cryoem.ucsf.edu/) - TRPA1.
* [Yigong Shi](http://ygshi.life.tsinghua.edu.cn/home.htm) - Spliceosome, pre-mRNA splicing, γ-Secretase, Apoptosis.
* [Eva Nogales](http://cryoem.berkeley.edu/) - CryoEM. 
* [David Baker](http://www.ipd.uw.edu/people/ipd-faculty-staff/david-baker/) - Rosetta.
* [Frank DiMaio](https://faculty.washington.edu/dimaio/wordpress/) - CryoEM model building.
* [Xueming Li](http://life.tsinghua.edu.cn/faculty/faculty/2730.html) - Motion Correction.
* [Hong-wei Wang](http://cryoem.life.tsinghua.edu.cn)
* [Marcus Brubakero](http://www.cs.toronto.edu/~mbrubake/) - CryoEM 3D Molecular Reconstruction, Machine Learning, CVPR 2015.
* [Meiler Lab](http://www.meilerlab.org/index.php) - Computational Chemical and Structural Biology, `EMfold`.
* [Sriram Subramaniam](https://electron.nci.nih.gov/publications)
* [Michael Cianfrocco Lab](http://www.lsi.umich.edu/labs/michael-cianfrocco-lab)
* [Kihara Lab](http://kiharalab.org/mainmast/)

[3D-EM Laboratories](http://3dem.ucsd.edu/labs_a_c.shtm)


## Workshop Docs

* [EMAN2 ](http://blake.bcm.edu/emanwiki/EMAN2/Tutorials)
* [Resource from Meiler Lab](http://www.meilerlab.org/index.php/jobs/resources) - Rosetta Tutorials, Teaching Resources, etc.

## Websites

* [Software Tools For Molecular Microscopy](http://en.wikibooks.org/wiki/Software_Tools_For_Molecular_Microscopy)
* [3D-EM Laboratories](http://3dem.ucsd.edu/labs_a_c.shtm)


## TODO
- [x] More usefull tools should be added in.
- [x] SSE prediction based model building methods.
- [x] Prepare for Tomograpy methods.



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

