TITLE
Confocal micrographs and complete dataset of neuromuscular junction morphology of 
pelvic limb muscles of the pig (Sus scrofa)

CONTRIBUTORS
Ines Boehm (1,2), Chandra Logie (3), Alyssa Gibbs (1,2), Olivia Murray (1,2), 
Rizwan Farrukh (1,2), Christopher Proudfoot (3), Richard Clutton (3), Ross A. 
Jones (1,2), Thomas H. Gillingwater (1,2)
1. Edinburgh Medical School: Biomedical Sciences, University of Edinburgh, 
Edinburgh, UK 
2. Euan MacDonald Centre for Motor Neurone Disease Research, University of 
Edinburgh, Edinburgh, UK
3. The Roslin Institute and R(D)SVS, University of Edinburgh, Edinburgh, UK

This documentation file was generated on 2021-06-22 by Ines Boehm 
(https://orcid.org/0000-0002-9343-0944)

------------------------------------
CONTEXTUAL INFORMATION
Dataset description
This dataset entails the complete NMJ dataset for three pigs and the three 
muscles analysed for the publication "Comparative anatomy of the mammalian 
neuromuscular junction" (https://doi.org/10.1111/joa.13260). This includes 
spreadsheets (.csv) containing morphometric variables of neuromuscular junction 
morphology generated using NMJ-morph or aNMJ-morph, as well as muscle fibre 
diameter (MFD) data for completeness. The three muscles analysed are: extensor 
digitorum longus (EDL), peroneus longus (PL) and soleus (S). Data contains raw 
microscope images (.nd2), thresholded and cleaned images of pre- and post-synapse 
(.tif) and the thresholded and cleaned images of the intermediate muscle endplate 
(.tif) for the muscle soleus since the "aNMJ-morph" macro saves this intermediate 
image for measurement of endplate variables.

PURPOSE
This dataset has been generated to evaluate the comparative anatomy of the 
neuromuscular junction between mammalian species.

KEYWORDS
neuromuscular junction, pig, porcine, sus scrofa, NMJ-morph, aNMJ-morph, morphology,
extensor digitorum longus, peroneus longus, soleus

DATA REUSE
This dataset is of interest for (a) beginners wanting to familiarise themselves 
with NMJ-morph (https://doi.org/10.1016/j.celrep.2017.11.008) or aNMJ-morph 
(https://doi.org/10.1098/rsos.200128) as the raw data provides the opportunity 
for comparison; (b) researchers in the field of comparative anatomy wanting to 
compare their species' NMJ-morphology to pig morphology; (c) researchers in the 
field of neuromuscular diseases using porcine models of disease who want to use 
external control data of the healthy porcine/pig neuromuscular junction; (d) 
researchers developing machine learning algorithms for analysis of NMJ-analysis 
who are looking for training datasets.

GENERAL INFORMATION
Biological Context
The neuromuscular junction (NMJ) — a synapse formed between lower motor neurons 
and skeletal muscle fibre — represents a major focus of both basic neuroscience 
research and clinical neuroscience research. 
Although the NMJ is known to play an important role in many neurodegenerative 
conditions affecting humans, the vast majority of anatomical and physiological 
data concerning the NMJ come from lower mammalian (e.g. rodent) animal models. 
However, recent findings have demonstrated major differences between the cellular 
anatomy and molecular anatomy of human and rodent NMJs. 
Therefore, we undertook a comparative morphometric analysis of the NMJ across 
several larger mammalian species, using the standardised worklfow NMJ-morph or 
the macro equivalent aNMJ-morph which yield 21 morphometric variables describing 
NMJ-morphology and associated nerve/muscle measurements. 
In order to generate baseline inter-species anatomical reference data for the NMJ 
and to identify animal models that better represent the morphology of the human 
NMJ in vivo, we analysed 5,385 individual NMJs from lower/pelvic limb muscles 
(EDL, soleus and peronei) of 6 mammalian species (mouse, cat, dog, sheep, pig 
and human). 
There was marked heterogeneity of NMJ morphology both within and between species, 
with no overall relationship found between NMJ morphology and muscle fibre 
diameter or body size. Mice had the largest NMJs on the smallest muscle fibres; 
cats had the smallest NMJs on the largest muscle fibres. 
Of all the species examined, the sheep NMJ had the most closely matched morphology 
to that found in humans. Taken together, we present a series of comprehensive 
baseline morphometric data for the mammalian NMJ and suggest that ovine models 
are likely to best represent the human NMJ in health and disease.

METHODOLOGICAL INFORMATION
(Detailed protocol as per publication Boehm et al., 2020, https://doi.org/10.1111/joa.13260) 
No animals were sacrificed specifically for this project: tissue was sampled 
from animals in existing studies (after experimental endpoints had been reached) 
or from animals submitted for euthanasia (to Dryden Farm or The The Royal (Dick) 
School of Veterinary Studies). Animals were euthanized and samples were harvested 
within 1hr post-mortem. N = 3 pigs; mean age = 18 months were sampled. To 
facilitate cross-species comparison, previously studied muscles were selected 
(Jones et al., 2017, https://doi.org/10.1016/j.celrep.2017.11.008): extensor 
digitorum longus, peroneus longus and soleus.
Full-length muscle fibres from origin to insertion (2–3 cm in length) were 
dissected from each of the hindlimb muscles and immediately fixed in 4% 
paraformaldehyde (PFA) for 3–4 hr. Muscle samples were then washed with 
1× phosphate-buffered saline (PBS) and microdissected into small bundles of 
10–15 individual fibres. All remaining fat and connective tissue were removed to 
reduce potential background staining. NMJs were immunolabelled to visualize 
pre-synaptic nerve terminal proteins (SV2 and 2H3) and post-synaptic acetylcholine 
receptors (AChRs). Muscle samples were mounted on glass slides in Mowiol and kept 
in dark storage to prevent photobleaching.
NMJ images were acquired on a Nikon A1R FLIM confocal system via a Nikon Eclipse 
Ti inverted microscope with a Nikon Apochromat 60x/1.4NA oil immersion objective 
(Nikon Instruments Europe BV, Netherlands), with a pinhole at 1.2 Airy units. 
16-bit pixel, 512x512 frame size, 1-4x optical zoom and 0.5-1 µm Z-stack intervals.
On average a total of 40 en face NMJs were imaged per muscle, where possible, 
to allow for analysis of at least 30-40 NMJs per muscle as recommended per original 
"NMJ-morph guidelines" (Jones et al., 2016, https://doi.org/10.1098/rsob.160240).
Image analysis of EDL and PL was performed using the standardized "NMJ-morph" 
approach to quantify 21 individual morphological vari- ables in each NMJ 
(including pre- and post-synaptic variables and associated nerve/muscle 
measurements (e.g. muscle fibre diameter). Image analysis on soleus was performed 
using the standardized "aNMJ-morph" macro (Minty et al., 2020, https://doi.org/10.1098/rsos.200128).

Description of methods used for collection/generation of data: 
- tissue dissection
- immunofluorescent visualisation of AChRs and pre-synaptic terminal and motor axon
- confocal microscopy
- NMJ-morph (https://datashare.ed.ac.uk/handle/10283/2113)
- aNMJ-morph (https://datashare.ed.ac.uk/handle/10283/3421)

DATASET FOLDER/FILE OVERVIEW
The Methods folder entails general methods used for tissue dissection and 
immunofluorescent visualisation and imaging of NMJs, and NMJ-morph and aNMJ-morph 
workflows.

Each Pig entails three separate folders for each separate muscle (EDL, PL, S).
Each muscle entails a separate folder for raw_images, cleaned_images and 
maximum_intensity_projections (for PL and S)

The naming convention follows: "Species Animal# Muscle TRITC-BTX SV22H3" e.g. 
"Pig 1 EDL TRITC-BTX SV22H3 ".
Most microscope files include a space after the naming system, only Pig 2 does not.

1. Datasets List
   A. Pig 1.zip - this .zip file contains the data of pig 1 NMJs
   B. Pig 2.zip - this .zip file contains the data of pig 2 NMJs
   C. Pig 3.zip - this .zip file contains the data of pig 3 NMJs
   D. Methods.zip - this .zip file contains .txt files of methods used
   E. readme_file.txt
   F. license_text.txt

2. Relationship between folders/files:
Spreadsheets of morphometric data and muscle fibre diameter (MFD) data for each 
muscle are contained within each Pig (1, 2 and 3) folder. 
Raw images (.nd2) are contained within folders corresponding to each individual 
animal and its muscle (e.g. Pig 1 > Pig 1 EDL > ...).
Each folder of raw images contains a folder "cleaned_images" with images (.tif) 
of thresholded and cleaned axon terminals = C1 = channel 1 and muscle endplate = 
C2 = channel 2. 
Soleus was analysed with aNMJ-morph so these files have the prefix 
axon_terminal and muscle_endplate. The soleus cleaned_images folder also containes 
images with the prefix muscle_intermediate_endplate which were used to measure 
endplate morphology.
PL and S across all three Pig folders also contain maximum intensity projection 
versions (.tif) of the raw microscope images (.nd2), those carry the prefix "MAX_".

3. Formats
.csv (spreadsheets of muscle fibre diameters and of NMJ morphometric variables 
within Pig 1-3 folders)
.nd2 (raw microscopy file in the raw_images folder)
.tif (cleaned images in cleaned_images folder; maximum intensity projections = 
MIPs, 2D format now "flattened" of former raw images that previously contained 
Z-stacks, in the maximum_intensity_projections folder)

.nd2 files can be opened with Fiji (https://imagej.net/software/fiji/).

OTHER 
Please do not hesitate to get in touch if there are any questions regarding 
this dataset: iboehm[at]exseed.ed.ac.uk
