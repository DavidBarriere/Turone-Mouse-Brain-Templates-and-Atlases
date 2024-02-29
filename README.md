# The Turone Mouse Brain Template and Atlas

The current document is a short description of the TMBTA resources for the mouse brain MRI data normalization. For a full description of the resources and the methodologies used to create them please consult the main publication (Barriere D.A. et al 2021, https://doi.org/10.1016/j.neuroimage.2021.117776).


The Turone Mouse Brain Template and Atlas (TMBTA) resources offer to the preclinical neuroimaging community a complete set of ex vivo template, tissues priors as well as anatomical atlas of the mouse brain. This new set of resources allows both linear and non-linear coregistration of multimodal acquisitions performed on the same animal (functional, anatomical and diffusion), leading to an accurate identification of the brain territories involved in a physiological or pathophysiological process. The TMBTA is a support for the standardization of MRI preclinical research. The TMBTA resources were developped as part of the ImaCervoRepro project, a collaborative project funded by the regional council of the Centre Val-de-Loire (convention 201500104011, 2015-2018). TMBTA provides a unified and standardized framework for the analysis of multimodal mouse brain data, allowing the reporting of results using the coordinate system of the Brain ALLEN atlas. 

## Organisation of the TMBTA resources
The TMBTA resources have been organized as three sections : anatomical template, brain atlas, brain meshes.

  ### Anatomical Template
A high-resolution ex vivo T2-weighted anatomical template and its associated GM, WM and CSF tissue probability maps + brain mask

Spatial resolution 0.06x0.06x0.06mmm.

      TMBTA_Brain_Mask.nii
      MBTA_Brain_Template.nii
      TMBTA_CSF.nii
      TMBTA_Grey.nii
      TMBTA_White.nii

  ### Mouse brain atlas
Anatomical whole-brain atlas composed of 1318 structures, derived from the merge of from the AMBMC brain template (http://www.imaging.org.au) and the ALLEN brain mice atlas (https://scalablebrainatlas.incf.org) + List of 1318 labels created in ITKSnap Format

Spatial resolution 0.06x0.06x0.06mmm.

      TMBTA_Brain_Atlas.nii
      TMBTA_ItK_Label_File.txt
      TMBTA_ListofStructures.xlsx
      TMBTA_RGB_Label_File.xls

  ### Mouse brain meshes
Brain meshes images suitable for data visualization with common neuroimaging software (gifti and nv format).

Spatial resolution 0.06x0.06x0.06mmm.

      TMBTA_BrainMesh.gii
      TMBTA_BrainMesh.nv

## Important Note
The TMBTA resources are provided at the scanner resolution and are oriented in anterior commisure/posterior commisure axis. Center of the images have been set at the anterior commisure level (Bregma 0 mm). Nevertheless, users are invited to increase the resolution of the current images for using in SPM or FSL methods for accurate coregistration and normalization steps (we recommand x10 increasing).

For any questions regarding the TMBTA ressource, please email David A. Barrière (david.barriere@cnrs.fr).

# REFERENCES
Lein ES et al. Genome-wide atlas of gene expression in the adult mouse brain. Nature. 2007 Jan 11;445(7124):168-76. doi: 10.1038/nature05453. Epub 2006 Dec 6. PMID: 17151600.

Janke AL et al. Robust methods to create ex vivo minimum deformation atlases for brain mapping. Methods. 2015 Feb;73:18-26. doi: 10.1016/j.ymeth.2015.01.005. Epub 2015 Jan 22. PMID: 25620005.

# RELATED WORKS USING THE TMBTA RESSOURCES
Barrière DA et al. Brain orchestration of pregnancy and maternal behavior in mice: A longitudinal morphometric study. Neuroimage. 2021 Apr 15;230:117776. doi: 10.1016/j.neuroimage.2021.117776. Epub 2021 Jan 29. PMID: 33516895.

Mouton L et al. Noninvasive Assessment of Neurodevelopmental Disorders after In Utero Irradiation in Mice: An In Vivo Anatomical and Diffusion MRI Study. Radiat Res. 2021 Jun 1;195(6):568-583. doi: 10.1667/RADE-20-00136.1. PMID: 33826744.
