## SMART Image Browser

[SMART](https://doi.org/10.1038/s41587-021-00986-5) stands for “**S**erial sectioning and clearing, 3-dimensional **M**icroscopy, with semi-**A**utomated **R**econstruction and **T**racing”. It is an integrative technology for high-throughput imaging and analysis that combines primate-optimized tissue sectioning and clearing with ultrahigh-speed, large-scale, volumetric fluorescence microscopy, capable of completing whole-brain imaging of a rhesus monkey at 1 µm × 1 µm × 2.5 µm voxel resolution within 100 hours.

The full dataset of a macaque brain is ~250 TB 16-bit TIFF images. Below are sample images of several slices.

## Sample 2D projections
### Imageset 1: superior collicuclus
This rhesus monkey was injected with AAV-Cre plus AAV-DIO-eGFP, and AAV-Cre plus AAV-DIO-mCherry into bilateral superior collicuclus (SC). The brain was sectioned into 300-µm slices, which were also stained with NeuroTrace 640/660 (NT640), a fluorescent Nissl stain. 

Example 3-channel maximum intensity projection (MIP) images resliced (50-µm each) from a sections could be viewed in the SMART Image Browser: (Related to Fig. 1m-n)

[http://smart.siat.ac.cn/slides.html?data=200309-006-156&slide=784&site=l](http://smart.siat.ac.cn/slides.html?data=200309-006-156&slide=784&site=l)

### Imageset 2: mediodorsal nucleus
This rhesus monkey was injected with AAV-Cre plus AAV-DIO-eGFP, and AAV-Cre plus AAV-DIO-mCherry into bilateral mediodorsal nucleus of thalamus (MD). The brain was sectioned into 300-µm slices, imaged and analyzed following the SMART pipeline.

Example 2-channel maximum intensity projection (MIP) images resliced (50-µm each) from 6 consecutive sections could be viewed in the SMART Image Browser: (Related to Fig. 2e) 

[http://smart.siat.ac.cn/slides.html?data=006-9095-6&site=l](http://smart.siat.ac.cn/slides.html?data=006-9095-6&site=l)

### Imageset 3: staining of neurons and glial cells
This monkey brain slice was stained with Anti-Glial Fibrillary Acidic Protein (GFAP), a marker for astrocytes, and NT640. 

Example 2-channel maximum intensity projection (MIP) images resliced (30-µm each) from this slice could be viewed in the SMART Image Browser: (Related to Supplementary Fig. 3) 

[http://smart.siat.ac.cn/slides.html?data=GFAP_NT640_1_SP3&site=l](http://smart.siat.ac.cn/slides.html?data=GFAP_NT640_1_SP3&site=l)


## Sample 3D image blocks
### Imageset 3: axonal morphology
[Lychnis tracer](https://github.com/SMART-pipeline/Lychnis-tracing) is for 3D fiber tracing in raw image spaces.

A series of image blocks that are surrounding a thalamocortical axon (RM006-004; shown in Fig. 4, Supplementary Fig. 13, and Supplementary Video 6) is accessible from the [zenodo link](https://doi.org/10.5281/zenodo.4451992) provided in the manuscript. Due to the limit of file size in zenodo and figshare, the current version in zenodo is of lower resolution. The dataset with larger size could be accessed via the following link:

[http://smart.siat.ac.cn/static-files/RM006-004-lychnis.zip](http://smart.siat.ac.cn/static-files/RM006-004-lychnis.zip) (5.8 GB compressed file)

It can be loaded for viewing and tracing in _Lychnis tracer_. [Lychnis version 1.2.5](https://github.com/SMART-pipeline/Lychnis-tracing/releases/download/1.2.5/Lychnis-1.2.5.zip) has been tested for this dataset on a desktop computer running Windows 10.

Step-by-step tutorial for playing with the demo data:
1. Unzip the package and run lychnis-1.2.5.exe directly.
2. Choose File -> Open Project
3. Select the project file (F5.json) and open it.

Detailed manual of Lychnis could be found in the [project page](https://github.com/SMART-pipeline/Lychnis-tracing).


For more details see [our paper published in Nature Biotechnology](https://doi.org/10.1038/s41587-021-00986-5).

## Support or Contact

Having any questions? Contact us (Fang Xu, xufun@ustc.edu.cn) and we’ll help you sort it out.
