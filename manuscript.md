---
title: A Practical Beginner's Guide to Proteomics
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2022-11-01'
author-meta:
- Dina Schuster
- Devasahayam Arokia Balaya Rex
- Martín L. Mayta
- Muralidharan Vanuopadath
- Emma H. Doud
- Benjamin A. Neely
- Amit Kumar Yadav
- Jesse G. Meyer
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta name="citation_title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta property="og:title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta property="twitter:title" content="A Practical Beginner&#39;s Guide to Proteomics" />
  <meta name="dc.date" content="2022-11-01" />
  <meta name="citation_publication_date" content="2022-11-01" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Dina Schuster" />
  <meta name="citation_author_institution" content="Department of Biology, Institute of Molecular Systems Biology, ETH Zurich, Zurich 8093, Switzerland" />
  <meta name="citation_author_institution" content="Department of Biology, Institute of Molecular Biology and Biophysics, ETH Zurich, Zurich 8093, Switzerland" />
  <meta name="citation_author_institution" content="Laboratory of Biomolecular Research, Division of Biology and Chemistry, Paul Scherrer Institute, Villigen 5232, Switzerland" />
  <meta name="citation_author_orcid" content="0000-0001-6611-8237" />
  <meta name="twitter:creator" content="@dina_sch" />
  <meta name="citation_author" content="Devasahayam Arokia Balaya Rex" />
  <meta name="citation_author_institution" content="Center for Systems Biology and Molecular Medicine, Yenepoya Research Centre, Yenepoya (Deemed to be University), Mangalore 575018, India" />
  <meta name="citation_author_orcid" content="0000-0002-9556-3150" />
  <meta name="twitter:creator" content="@rexprem" />
  <meta name="citation_author" content="Martín L. Mayta" />
  <meta name="citation_author_institution" content="School of Medicine and Health Sciences, Center for Health Sciences Research, Universidad Adventista del Plata, Libertador San Martín 3103, Argentina" />
  <meta name="citation_author_institution" content="Molecular Biology Department, School of Pharmacy and Biochemistry, Universidad Nacional de Rosario, Rosario 2000, Argentina" />
  <meta name="citation_author_orcid" content="0000-0002-7986-4551" />
  <meta name="twitter:creator" content="@MartinMayta2" />
  <meta name="citation_author" content="Muralidharan Vanuopadath" />
  <meta name="citation_author_institution" content="School of Biotechnology, Amrita Vishwa Vidyapeetham, Kollam-690 525, Kerala, India" />
  <meta name="citation_author_orcid" content="0000-0002-9364-917X" />
  <meta name="twitter:creator" content="@V_MuraleeDhar" />
  <meta name="citation_author" content="Emma H. Doud" />
  <meta name="citation_author_institution" content="Center for Proteome Analysis, Indiana University School of Medicine, Indianapolis, Indiana, USA" />
  <meta name="citation_author_orcid" content="0000-0003-0049-0073" />
  <meta name="twitter:creator" content="@fireinlab" />
  <meta name="citation_author" content="Benjamin A. Neely" />
  <meta name="citation_author_institution" content="Chemical Sciences Division, National Institute of Standards and Technology, NIST Charleston" />
  <meta name="citation_author_orcid" content="0000-0001-6120-7695" />
  <meta name="twitter:creator" content="@neely615" />
  <meta name="citation_author" content="Amit Kumar Yadav" />
  <meta name="citation_author_institution" content="Translational Health Science and Technology Institute" />
  <meta name="citation_author_orcid" content="0000-0002-9445-8156" />
  <meta name="twitter:creator" content="@theoneamit" />
  <meta name="citation_author" content="Jesse G. Meyer" />
  <meta name="citation_author_institution" content="Department of Computational Biomedicine, Cedars Sinai Medical Center" />
  <meta name="citation_author_orcid" content="0000-0003-2753-3926" />
  <meta name="twitter:creator" content="@j_my_sci" />
  <link rel="canonical" href="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta property="og:url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta property="twitter:url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta name="citation_fulltext_html_url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/" />
  <meta name="citation_pdf_url" content="https://jessegmeyerlab.github.io/proteomics-tutorial/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://jessegmeyerlab.github.io/proteomics-tutorial/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://jessegmeyerlab.github.io/proteomics-tutorial/v/7754ebba816f1413bfa9cfedd3248db22348ec6b/" />
  <meta name="manubot_html_url_versioned" content="https://jessegmeyerlab.github.io/proteomics-tutorial/v/7754ebba816f1413bfa9cfedd3248db22348ec6b/" />
  <meta name="manubot_pdf_url_versioned" content="https://jessegmeyerlab.github.io/proteomics-tutorial/v/7754ebba816f1413bfa9cfedd3248db22348ec6b/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://jessegmeyerlab.github.io/proteomics-tutorial/v/7754ebba816f1413bfa9cfedd3248db22348ec6b/))
was automatically generated
from [jessegmeyerlab/proteomics-tutorial@7754ebb](https://github.com/jessegmeyerlab/proteomics-tutorial/tree/7754ebba816f1413bfa9cfedd3248db22348ec6b)
on November 1, 2022.
</em></small>

## Authors



+ **Dina Schuster**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-6611-8237](https://orcid.org/0000-0001-6611-8237)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [dschust-r](https://github.com/dschust-r)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [dina_sch](https://twitter.com/dina_sch)<br>
  <small>
     Department of Biology, Institute of Molecular Systems Biology, ETH Zurich, Zurich 8093, Switzerland; Department of Biology, Institute of Molecular Biology and Biophysics, ETH Zurich, Zurich 8093, Switzerland; Laboratory of Biomolecular Research, Division of Biology and Chemistry, Paul Scherrer Institute, Villigen 5232, Switzerland
  </small>

+ **Devasahayam Arokia Balaya Rex**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-9556-3150](https://orcid.org/0000-0002-9556-3150)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [ArokiaRex](https://github.com/ArokiaRex)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [rexprem](https://twitter.com/rexprem)<br>
  <small>
     Center for Systems Biology and Molecular Medicine, Yenepoya Research Centre, Yenepoya (Deemed to be University), Mangalore 575018, India
  </small>

+ **Martín L. Mayta**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-7986-4551](https://orcid.org/0000-0002-7986-4551)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [martinmayta](https://github.com/martinmayta)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [MartinMayta2](https://twitter.com/MartinMayta2)<br>
  <small>
     School of Medicine and Health Sciences, Center for Health Sciences Research, Universidad Adventista del Plata, Libertador San Martín 3103, Argentina; Molecular Biology Department, School of Pharmacy and Biochemistry, Universidad Nacional de Rosario, Rosario 2000, Argentina
  </small>

+ **Muralidharan Vanuopadath**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-9364-917X](https://orcid.org/0000-0002-9364-917X)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [vanuopadathmurali](https://github.com/vanuopadathmurali)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [V_MuraleeDhar](https://twitter.com/V_MuraleeDhar)<br>
  <small>
     School of Biotechnology, Amrita Vishwa Vidyapeetham, Kollam-690 525, Kerala, India
  </small>

+ **Emma H. Doud**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-0049-0073](https://orcid.org/0000-0003-0049-0073)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [edoud1](https://github.com/edoud1)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [fireinlab](https://twitter.com/fireinlab)<br>
  <small>
     Center for Proteome Analysis, Indiana University School of Medicine, Indianapolis, Indiana, USA
  </small>

+ **Benjamin A. Neely**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-6120-7695](https://orcid.org/0000-0001-6120-7695)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [neely](https://github.com/neely)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [neely615](https://twitter.com/neely615)<br>
  <small>
     Chemical Sciences Division, National Institute of Standards and Technology, NIST Charleston
     · Funded by NIST
  </small>

+ **Amit Kumar Yadav**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-9445-8156](https://orcid.org/0000-0002-9445-8156)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [aky](https://github.com/aky)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [theoneamit](https://twitter.com/theoneamit)<br>
  <small>
     Translational Health Science and Technology Institute
     · Funded by Grant BT/PR16456/BID/7/624/2016 (Department of Biotechnology, India); Grant Translational Research Program (TRP) at THSTI funded by DBT
  </small>

+ **Jesse G. Meyer**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-2753-3926](https://orcid.org/0000-0003-2753-3926)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [jessegmeyerlab](https://github.com/jessegmeyerlab)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [j_my_sci](https://twitter.com/j_my_sci)<br>
  <small>
     Department of Computational Biomedicine, Cedars Sinai Medical Center
     · Funded by Grant R21 AG074234; Grant R35 GM142502
  </small>



## Abstract {.page_break_before}

Proteomics is the large scale study of protein structure and function from biological systems.  
"Shotgun proteomics" or "bottom-up proteomics" is the prevailing strategy, in which proteins are hydrolyzed into peptide that are analyzed by mass spectrometry.
Proteomics studies can be applied to diverse studies ranging from simple protein identification to studies of protein-protein interactions, absolute and relative protein quantification, post-translational modifications, and protein stability. 
To enable this range of different experiments, there are diverse strategies for proteome analysis. 
The nuances of how proteomic workflows differ may be difficult to understand for new practitioners. 
Here, we provide a comprehensive tutorial of different proteomics methods. 
Our tutorial covers all necessary steps starting from protein extraction and ending with biological interpretation. 
We expect that this work will serve as a basic resource for new practitioners of the field of shotgun or bottom-up proteomics. 


## Introduction {.page_break_before}

Proteomics is the large scale study of protein structure and function. 
Proteins are translated from mRNAs that are transcribed from the genome. 
Although the genome encodes potential cellular functions and states, the study of proteins is necessary to truly understand biology. 
Currently, proteomic studies are facilitated by mass spectrometry, although alternative methods are being developed.

Modern proteomics started around the year 1990 with the introduction of soft ionization methods that enabled, for the first time, transfer of large biomolecules into the gas phase without destroying them [@DOI:10.1126/science.2675315; @DOI:10.1002/rcm.1290020802]. 
Shortly afterward, the first computer algorithm for matching peptides to a database was introduced [@PMID:24226387]. 
Another major milestone that allowed identification of over 1000 proteins were actually improvements to chromatography [@DOI:10.1021/ac010617e]. 
As the volume of data exploded, methods for statistical analysis transitioned use from the wild west to modern informatics based on statistical models [@DOI:10.1021/ac0341261] and the false discovery rate [@DOI:https://doi.org/10.1038/nmeth1019]. 
<!-- Todo: figure 1: major milestones in proteomics technology since 1990 -->

Two strategies of mass spectrometry-based proteomics differ fundamentally by whether proteins are cleaved into peptides before analysis: "top-down" and "bottom-up". 
Bottom-up proteomics (also refered to as shotgun proteomics) is defined by the hydrolysis of proteins into peptide pieces [@DOI:10.1038/nature19949]. 
Therefore, bottom-up proteomics does not actually measure proteins, but must infer their presence [@DOI:10.1021/ac0341261]. 
Sometimes proteins are infered from only one peptide sequence representing a small fraction of the total protein sequence predicted from the genome. 
In contrast, top-down proteomics attempts to measure all proteins intact [@DOI:10.1039/C9MO00154A]. 
The potential benefit of top-down proteomics is the ability to measure proteoforms [@DOI:10.1126/science.aat1884]. 
However, due to analytical challenges, the depth of protein coverage that is achievable by top-down proteomics is less than the depth that is achievable by bottom-up proteomics. 

In this tutorial we focus on the bottom-up proteomics workflow. 
The most common version of this workflow is generally comprised of the following steps. 
First, proteins in a biological sample must be extracted. 
Usually this is done by denaturing and solubilizing the proteins while disrupting DNA and tissue. 
Next, proteins are hydrolyzed into peptides, usually using a protease like trypsin. 
Peptides from proteome hydrolysis must be purified.
Most often this is done with reversed phase chromatography cartridges or tips. 
The peptides are then almost always separated by liquid chromatography before they are ionized and introduced into a mass spectrometer. 
The mass spectrometer then collects precursor and fragment ion data from those peptides. 
The data analysis is usually the rate limiting step.
Peptides must be identified, and proteins are inferred and quantities are assigned. 
Changes in proteins across conditions are determined with statistical tests, and results must be interpreted in the context of the relevant biology.

There are many variations on this workflow. The wide variety of experimental goals that are achievable with proteomics technology leads to a wide variety of potential proteomics workflows. Even choice is important and every choice will affect the results. In this tutorial, we cover all of the required steps in detail to serve as a tutorial for new proteomics practioners.



1. Biochemistry basics
2. Types of experiments enabled by proteomics
3. Protein extraction
4. proteolysis
5. Isotopic Labeling
6. Enrichments
7. Peptide purification
8. Mass Spectrometry
9. Peptide Ionization
10. Data Acquisition
11. Basic Data Analysis
12. Biological Interpretation
14. Sample Fractionation
15. Tandem MS
16. Experimental considerations and design



## Biochemistry Basics {.page_break_before}

### Proteins

Proteins are large biomolecules or biopolymers made up of amino acids which are linked by peptide bonds. 
They perform various functions in living organisms ranging from having structural roles to functional involvement in cellular signaling and the catalysis of chemical reactions (enzymes). 
Proteins are made up of 20 different amino acids (not counting pyrrolysine and selenocysteine, which only occur in specific organisms) and their sequence is encoded in their corresponding genes.
The human genome encodes more than 20,000 different proteins.
Each protein is present at a different abundances.
Previous studies have shown that the concentration range of proteins can span over a range of at least seven orders of magnitude to up to 20 000 000 copies per cell and that their distribution is tissue-specific[@DOI:10.1038/msb.2011.82][@DOI:10.1016/j.cell.2020.08.036].
Due to genetic variations, as well as alternative splicing and post-translational modifications, multiple different proteoforms can be produced from one single gene[@DOI:10.1038/nmeth.2369].

#### PTMs

Proteins can be post-translationally modified through enzymatic and non-enzymatic reactions _in vivo_ and _in vitro_ [@doi:10.1093/database/baab012]. 
Post-translational modifications (PTMs) can be reversible or non-reversible covalent modifications of amino acids.
The most commonly studied and biologically relevant post-translational modifications include ubiquitinations (Lys, Cys, Ser, Thr, N-term), succinylations (Lys), methylations (Arg, Lys, His, Glu, Asn, Cys), disulfide bonds (Cys-Cys), oxidations (Met, Trp, His, Cys), phosphorylations (Ser, Thr, Tyr, His), acetylations (Lys, N-term), glycosylations (Arg, Asp, Cys, Ser, Thr, Tyr, Trp) and lipidations.
Post-translational modification of a protein can alter its function, activity, structure, location and interactions. 
Deregulation of PTMs is linked to cellular stress and diseases[@doi:10.1038/s41570-020-00223-8].

#### Protein Structure

Almost all proteins (except for intrinsically disordered proteins[@doi:10.1146/annurev-biochem-072711-164947]) fold into 3D structures either by themselves or assisted through chaperones[@doi:10.1007/s12013-021-00970-5]. 
There are four levels relevant to the folding of any protein: 

- Primary structure: 
The protein's linear amino acid sequence, with amino acids connected through peptide bonds.

- Secondary structure: 
The amino acid chain's folding: α-helix, β-sheet or turn.

- Tertiary structure: 
The three-dimensional structure of the protein. 

- Quarternary structure: 
The structure of several protein molecules/subunits in one complex.

#### Biochemical and biophysical techniques for studying complex protein mixtures

##### Concentration/total protein amount determination

- UV-Vis Spectrophotometry (Bradford assay, BCA assay, Lowry, Folin)

##### **Electrophoresis**

- SDS-PAGE (sodium dodecyl sulfate-polyacrylamide gel electrophoresis)
- 2D-PAGE
- Isoelectric focussing (IEF)
- Western blotting

#### Biochemical and biophysical analytical techniques for studying purified proteins

##### **Concentration determination**

- UV-Vis Spectrophotometry

##### **Protein size and aggregation**

- Dynamic light scattering (DLS)
- Size-exclusion chromatography (SEC) or size-exclusion with multi angle laser light scattering (SEC-MALLS)
- SDS-PAGE
- Mass photometry

##### **Structural techniques**

- Circular dichroism (CD) spectropolarimetry
- X-ray crystallography
- Protein nuclear magnetic resonance spectroscopy (NMR)
- (cryo-)Electron microscopy (EM)

##### **Interactions and binding kinetics**

- Surface plasmon resonance (SPR)
- Isothermal titration calorimetry (ITC)

### Buffers


## Types of Experiments {.page_break_before}
A wide range of questions are addressable with proteomics technology, which translates to a wide range of variations of proteomics workflows. 
Sometimes identifying what proteins are present is desired, and sometimes the quantities of as many proteins as possible are desired. 
Proteomics experiments can be both qualitative and quantitative. 

### Qualitative experiments
- Identifying proteins 
- Identifying post translational modifications
- Identifying protein isoforms

### Quantitative experiments
- Protein abundance changes
- Phosphoproteomics
- Glycoproteomics
- Structural techniques (XL-MS, HDX-MS, FPOP, protein-painting, LiP-MS, radical footprinting, ion mobility)
- Protein stability and small molecule binding (Thermal proteome profiling, TPP, or cellular thermal shift assay, CETSA)
- Protein-protein interactions (PPIs): AP-MS, APEX, BioID




## Protein Extraction {.page_break_before}

Protein extraction from the sample of interest is the initial phase of any mass spectrometry-based proteomics experiment. 
Thought should be given to any planned downstream assays, specific needs of proteolysis (LiP-MS, post translational modification enrichments, enzymatic reactions, glycan purification or hydrogen-deuterium exchange experiments) long term project goals (reproducibility, multiple sample types, low abundance samples) as well as to the initial experimental question (coverage of a specific protein, subcellular proteomics, global proteomics, protein-protein interactions or immune or affinity enrichment of a specific classes of modifications.) 
The 2009 version of Methods in Enzymology: guide to Protein Purification [@isbn:978-0-12-374536-1] serves as a deep dive into how molecular biologists and biochemists traditionally thought about protein extraction. 
The Protein Protocols handbook [@isbn:978-1-59745-198-7] and the excellent review by Linn [@PMID:19892162] are good sources of general proteomics protocols for a scientist new to the field.
Any change in extraction conditions should be expected to create potential changes in downstream results. 
Be sure to think about and optimize the protein extraction step first and stick with a protocol that works for your needs. 
If a collaborator is attempting to reproduce your results, make sure they begin with the same extraction protocols. 

### Buffer choice 
#### General proteomics 

A common question to proteomics core facilities is, “What is the best buffer for protein extraction?”
Unfortunately, there is no one correct answer. 
For global proteomics experiments where maximizing the number of protein or peptide identifications is a goal, a buffer of neutral pH (50-100 mM PBS, Tris, HEPES, ammonium bicarbonate, triethanolamine bicarbonate; pH 7.5-8.5) is used in conjunction with a chaotrope or surfactant to denature and solubilize proteins (e.g., 8 M urea, 6 M guanidine, 5% SDS) [@PMID:16152629; @PMID:20722421]. 
Often other salts like 50-150 mM NaCl are also added. 
Complete denaturation of the proteins in the sample in a timely fashion is an advantage as it generally prevents changes to protein status by endogenous proteases, kinases, phosphotases, and other enzymes.
If intact protein separations are planned (based on size or isoelectric point) choose a denaturant compatible with those methods, such as SDS[@PMID:31249407]. 
Compatibility with protease (typically trypsin) and peptide cleanup steps will need to be considered. 
8 M urea must be diluted to 2 M or less for trypsin and chymotrypsin digestions, while guanidine and SDS should be removed either through protein precipitation, through filter-assisted sample preparation (FASP), or similar solid phase digestion techniques. 
Note that some buffers can potentially introduce modifications onto proteins such as carbamylation from urea at high temperatures [@PMID:24161613]. 

#### Protein-protein interactions 
Denaturing conditions will efficiently extract proteins – but they will denature/disrupt most protein-protein interactions. 
If you are working on an immune- or affinity purification of a specific protein and expect to analyze enzymatic activity, structural features, and/or protein-protein interactions, a non-denaturing lysis buffer should be utilized [@PMID:21364760; @PMID:10504710]. 
Check the calculated pI and hydrophobicity (the Expasy.org resource ProtParam is useful fo this) for a good idea of starting pH/conductivity, but you may need to perform a stability screen. 
In general, a good starting point for the buffer will still be close to neutral pH with 50-250 mM NaCl, but specific proteins may require pH as low as 2 or as high as 9 for stable extraction. 
A low percent of mass spec compatible detergent may also be used.
Newer mass spectrometry compatible detergents are also useful for protein extraction and ease of downstream processing – including Rapigest® (Waters), N-octyl-β-glucopyranoside, Azo [@PMID:33232116], PPS silent surfactant [@PMID:21280217], sodium laurate [@PMID:23555778], and sodium deoxycholate[@PMID:17022626]. 
AVOID the use of tween-20, triton-X, NP-40, and PEGs as these compounds are challenging to remove after digestion [@PMID:29726681]. 

#### Optional additives 
For non-denaturing buffer conditions, which preserve tertiary and quaternary protein structures, additional additives may not be necessary for successful extraction and to prevent proteolysis or PTM modifications throughout the extraction process. 
Protease, phosphatase and deubiquitinase inhibitors are optional additives in less denaturing conditions or in experiments focused on specific post-translational modifications. 
Keep in mind that protease inhibitors may impact digestion conditions and will need to be diluted or removed prior to trypsin addition. 
For extraction of DNA or RNA binding proteins, addition of a small amount of nuclease or benzonase might be useful for degradation of any bound nucleic acids and result in a more consistent digestion [@PMID:23792921].

### Mechanical or Sonic Disruption 
#### Cell lysis 
One typical lysis buffer is 8 M urea in 100 mM Tris, pH 8.5; the pH based on optimum trypsin activity [@PMID:25664860]
Small mammalian cell pellets and exosomes will lyse almost instantly upon addition denaturing buffer. 
If non-denaturing conditions are desired, osmotic swelling and subsequent shearing or sonication can be applied [@DOI:10.1080/10826068.2020.1728696].
Efficiency of extraction and degradation of nucleic acids can be improved using various sonication methods: 1) probe sonicator with ice; 2) water bath sonicator with ice or cooling; 3) bioruptor® sonication device 4) Adaptive focused acoustics (AFA®) [@PMID:21060726]. 
Key to these additional lysis techniques are to keep the temperature of the sample from rising significantly which can cause proteins to aggregate or degrade. 
Some cell types may require additional force for effective lysis (see below). 
For cells with cell walls (i.e. bacteria or yeast), lysozyme is often added in the lysis buffer. 
Any added protein will be present in downstream results, however, so excessive addition of lysozyme is to be avoided unless tagged protein purification will occur. 

#### Tissue/other lysis 
Although small pieces of soft tissue can often be successfully extracted with the probe and sonication methods described above, larger/harder tissues as well as plants/yeast/fungi are better extracted with some form of additional mechanical force. 
If proteins are to be extracted from a large amount of sample, such as soil, feces, or other diffuse input, one option is to use a dedicated blender and filter the sample, followed by centrifugation. 
If samples are smaller, such as tissue, tumors, etc., cryo-homogenization is recommended. 
The simplest form of this is grinding the sample with liquid nitrogen and a mortar and pestle.
Tools such as bead beaters (i.e. FastPrep-24®) are also used, where the sample is placed in a tube with appropriately sized glass or ceramics beads and shaken rapidly. 
Cryo-mills are chambers where liquid nitrogen is applied around a vessel and large bead or beads. 
Cryo-fractionators homogenize samples in special bags that are frozen in liquid nitrogen and smashed with various degrees of force [@PMID:34002278]. 
After homogenization, samples can be sonicated by one of the methods above to fragment DNA and increase solubilization of proteins. 

### Measuring the efficiency of protein extraction 
Following protein extraction, samples should be centrifuged (10-14,000 g for 10-30 min depending on sample type) to remove debris and any unlysed material prior to determinining protein concentration. 
The amount of remaining insoluble material should be noted throughout an experiment as a large change may indicate protein extraction issues. 
Protein concentration can be calculated using a number of assays or tools [@PMID:18429326; @PMID:12703310]; generally absorbance measuremnts are facile, fast and affordable, such as Bradford or BCA assays. 
Protein can also be estimated by tryptophan fluorescence, which has the benefit of not consuming sample [@DOI:10.1021/ac504689z].
A nanodrop UV spectrophotometer may be used to measure absorbance at UV280. 
Consistency in this method is important as each method will have inherent bias and error [@PMID:26342307; @PMID:30234128]. 
Extraction buffer components will need to be compatible with any assay chosen; alternatively, buffer may be removed (see below) prior to protein concentration calculation.

### Reduction and alkylation 
Typically, disulfide bonds in proteins are reduced and alkylated prior to proteolysis in order to disrupt structures and simplify peptide analysis. 
This allows better access to all residues during proteolysis and removes the crosslinked peptides created by S-S inter peptide linkages. 
There are a variety of reagent options for these steps. 
For reduction, the typical agents used are 5-15 mM concentration of tris(2-carboxyethyl)phosphine hydrochloride (TCEP-HCl), dithiothreitol (DTT), or 2-mercaptoethanol (2BME).
TCEP-HCl is an efficient reducing agent, but it also significantly lowers sample pH, which can be abated by increasing sample buffer concentration or resuspending TCEP-HCl in an appropriate buffer system (i.e 1M HEPES pH 7.5).      
Following the reducing step, a slightly higher 10-20mM concentration of alkylating agent such as chloroacetamide/iodoacetamide or n-ethyl maleimide is used to cap the free thiols [PMID:29019370; @PMID:15351294; @PMID:28539326]. 
In order to monitor which cysteine residues are linked or modified in a protein, it is also possible to alkylate free cysteines with one reagent, reduce di-sulfide bonds (or other cysteine modifications) and alkylate with a different reagent [@PMID:32132231; @PMID:28445428; @PMID:23074338]. 
Alkylation reactions are generally carried out in the dark at room temperature to avoid excessive off-target alkylation of other amino acids.

### Removal of buffer/interfering small molecules
If extraction must take place in a buffer which is incompatible for efficient proteolysis (check the guidelines for the protease of choice), then protein cleanup should occur prior to digestion. 
This is generally performed through precipitation of proteins. 
The most common types are 1) acetone, 2) trichloroacetic acid (TCA), and 3) methanol/chloroform/water [@PMID:14753699; @PMID:19892180]. 
Proteins are generally insoluble in most pure organic solvents, so cold ethanol or methanol are sometimes used. 
Pellets should be washed with organic solvent for complete removal especially of detergents. 
Alternatively, solid phase based digestion methods such as S-trap [@PMID:33750040], FASP [@PMID:19377485; @PMID:30259475], SP3 [@PMID:3117935; @PMID:28948796] and on column/bead can allow for proteins to be applied to a solid phase and buffers removed prior to proteolysis [@PMID: 29754492]. 
Specialty detergent removal columns exist (Pierce/Thermo Fisher Scientific) but add expense and time consuming steps to the process. 
Relatively low concentrations of specific detergents, such as 1% deoxycholate (DOC), or chaotropes (i.e. 1M urea) are compatible with proteolysis by trypsin/Lys-C.
Often proteolysis-compatible concentrations of these detergents and chaotropes are achieved by diluting the sample in appropriate buffer (i.e. 100 mM ammonium bicarbonate, pH 8.5) after cell or tissue lysis in a higher concentration. 
DOC can then be easily removed by precipitation or phase separation [@PMID:18183947] following digestion by acidification of the sample to pH 2-3.   
Any small-molecule removal protocol should be tested for efficiency prior to implementing in a workflow with many samples as avoiding detergent (or polymer) contamination in the LC/MS is very important. 

### Summary 
Often you will be given protein extraction conditions from molecular biologists or biochemistry which you will have to make work with downstream mass spectrometry applications. 
For bottom-up proteomics, the overreaching goal is efficient and consistent extraction and digestion. 
A range of mechanical and non-mechanical extraction protocols have been developed and the use any one specific technique is generally dictated by sample type or assay requirements (i.e. native versus non-native extraction).
Extraction can be aided by the addition of detergents and/or chaotropes to the sample, but care should be taken that these additives do not interfere with the sample digestion step or downstream mass-spectrometry applications. 




## Proteolysis {.page_break_before}

Proteolysis is the defining step that differentiates bottom-up or shotgun proteomics from top-down proteomics. 
Hydrolysis of proteins is extremely important because it defines the population of potentially identifyable peptides. 
Generally peptides between a length of 7-35 amino acids are considered useful for mass spectrometry analysis.
Peptides that are too long are difficult to identify by tandem mass spectrometry, or may be lost during sample preparation due to irreversible binding with solid-phase extraction sorbents.
Peptides that are too short are also not useful because they may match to many proteins during protein inference. 
There are many choices of enzymes and chemicals that hydrolyze proteins into peptides. 
This section summarizes potential choices and their strengths and weaknesses. 

Trypsin is the most common choice of protease for proteome hydrolysis [@DOI:10.1002/mas.21376].
Trypsin is favorable because of its specificity, availability, efficiency and low cost. 
Trypsin cleaves at the C-terminus of basic amino acids, Arg and Lys. 
Many of the peptides generated from trypsin are short in length (less than ~ 20 amino acids), which is ideal for chromatographic separation, MS-based peptide fragmentation and identification by database search.
The main drawback of trypsin is that majority (56%) of the tryptic peptides are ≤ 6 amino acids, and hence using trypsin alone limits the observable proteome [@PMID:20113005; @PMID:25823410; @PMID:30687733].
This limits the number of identifiable protein isoforms and post-translational modifications.

3. theoretical studies of proteolysis enzymes [@DOI:10.1155/2014/960902]
4. Challenges associated with alternative enzyme choices (non-specific and semi-specific enzymes)

Many alternative proteases are available with different specificities that complement trypsin to reveal different proteomic sequences [@PMID:12643544; @PMID:20113005], which can help distinguish protein isoforms [@PMID:27123950].
The enzyme choice mostly depends on the application.
In general, for a mere protein identification mostly trypsin is the choice due to the reasons aforementioned.
However, alternative enzymes can facilitate _de novo_ assembly when the genomic data information is limited in the public database repositories [@pmid:31615963; @pmid:30622160; @pmid:29990557; @doi:10.1016/j.actatropica.2022.106324; @DOI:10.1021/pr400173d].
Use of multiple proteases for proteome digestion also can improve the sensitivity and accuracy of protein quantification [@PMID:30336047].
Moreover, by providing an increased peptide diversity, the use of multiple proteases can expand sequence coverage and increase the probability of finding peptides which are unique to single proteins [@DOI:10.1021/acs.jproteome.9b00330; @DOI:10.1074/mcp.M113.034710; @DOI:10.1155/2014/960902]. 
A multi-protease approach can also improve the identification of N-Termini and signal peptides for small proteins [@DOI:10.1021/acs.jproteome.1c00115]. 
Overall, integrating multiple-protease data can increase the number of proteins identified [@DOI:10.3390/ijms20225630; @DOI:10.1074/mcp.M113.035170], the number of identified post-translational modifications detected [@DOI:10.1021/acs.jproteome.9b00330; @DOI:10.1016/j.celrep.2015.05.029; @DOI:10.1074/mcp.M113.034710] and decrease the ambiguity of the protein group list [@DOI:10.1021/acs.jproteome.9b00330].

Lysyl endopeptidase (Lys-C) obtained from  _Lysobacter enzymogenesis_ is a serine protease involved in cleaving carboxyl terminus of Lys [@PMID:6359954, @PMID:25823410].
Like trypsin, the optimum pH range required for its activity is from 7 to 9. 
A major advantage of Lys-C is its resistance to denaturing agents, including 8 M urea - a chaotrope commonly used to denature proteins _prior_ to digestion [@PMID:27123950].
Trypsin is less efficient at cleaving Lys than Arg, which could limit the quality of quantitation from tryptic peptides.
Hence, to achieve complete protein digestion with minimal missed cleavages, Lys-C is often used simultaneously with trypsin digestion [@PMID:23017020].

Alpha-lytic protease (aLP) is also secreted by the soil bacterial _Lysobacter enzymogenesis_ [@PMID:3053694].
Wild-type aLP (WaLP) and an active site mutant of aLP, M190A (MaLP), have been used to expand proteome coverage [@DOI:10.1074/mcp.m113.034710].
Based on observed peptide sequences from yeast proteome digestion, WaLP showed a specificity for small aliphatic amino acids like alanine, valine, and glycine, but also threonine and serine. 
MaLP showed specificity for slightly larger amino acids like methionine, phenylalanine, and surprisingly, a preference for leucine over isoleucine. 
The specificity of WaLP for threonine enabled the first method for mapping endogenous human SUMO sites [@PMID:29079793].

Glutamyl peptidase I, commonly known as Glu-C or V8 protease, is a serine protease obtained from _Staphyloccous aureus_ [@PMID:4627743].
Glu-C cleaves at the C-terminus of glutamate, but also after aspartate [@PMID:4627743; @PMID:26748652].

Peptidyl-Asp metallopeptidase, commonly known as Asp-N, is a metalloprotease obtained from _Pseudomonas fragi_ [@PMID:2669754].
Asp-N catalyzes the hydrolysis of peptide bonds at the N-terminal of aspartate residues. 
The optimum activity of this enzyme occurs at a pH range between 4 and 9.  
As with any metalloprotease, chelators like EDTA should be avoided for digestion buffers when using Asp-N.
Studies also suggest that Asp-N cleaves at the amino terminus of glutamate when a detergent is present in the proteolysis buffer [@PMID:2669754]. 
Asp-N often leaves many missed cleavages [@PMID:27123950].

Chymotrypsin or chymotrypsinogen A is a serine protease obtained from porcine or bovine pancreas with an optimum pH range from 7.8 to 8.0 [@PMID:3555886]. 
It cleaves at the C-terminus of hydrphobic amino acids Phe, Trp, Tyr and barely Met and Leu residues.
Since the transmembrane region of membrane proteins commonly lacks tryptic cleavage sites, this enzyme works well with membrane proteins having more hydrophobic residues [@PMID:24870543; @PMID:24696503; @PMID:27123950].
The chymotryptic peptides generated after proteolysis will cover the proteome space orthogonal to that of tryptic peptides both in a quantitative and qualitative manner [@PMID:24290761; @PMID:22669647; @PMID:24696503]

Clostripain, commonly known as Arg-C, is a cysteine protease obtained from _Clostridium histolyticum_ [@PMID:4332560].
It hydrolyses mostly the C-terminal Arg residues and sometimes Lys residues, but with less efficiency.
The peptides generated are generally longer than that of tryptic peptides.
Arg-C is often used with other proteases for improving qualitative proteome data and also for investigating PTMs [@PMID:25823410]. 

LysargiNase, also known as Ulilysin, is a recently discovered protease belonging to the metalloprotease family. 
It is a thermophilic protease derived from _Methanosarcina acetivorans_ that specifically cleaves at the N-terminus of Lys and Arg residues [@PMID:25419962].
Hence, it enabled discovery of C-terminal peptides that were not observed using trypsin.
In addition, it can also cleave modified amino acids such as methylated or dimethylated Arg and Lys [@PMID:25419962].

Peptidyl-Lys metalloendopeptidase, or Lys-N, is an metalloprotease obtained from _Grifola frondosa_ [@PMID:19195997]. 
It cleaves N-terminally of Lys and has an optimal activity at pH 9.0.
Unlike trypsin, Lys-N is more resistant to denaturing agents and can be heated up to 70 °C [@PMID:25823410].
Reports suggest that the peptides generated after Lys-N digestion produces more of c-type ions in a ETD-based mass spectrometer [@PMID:18425140]. 
Hence this can be used for analysing PTMs, identification of C-terminal peptides and also for _de novo_ sequencing strategies [@PMID:18425140; @PMID:20953479].

Pepsin A, commonly known as pepsin, is an aspartic protease obtained from bovine or porcine pancreas [@PMID:12089768].
Pepsin was one of several proteins crystalized by John Northrop, who shared the 1946 Nobel prize in chemistry for this work [@PMID:19872561;@PMID:19872562; @PMID:17758437;@URL:https://www.nobelprize.org/prizes/chemistry/1946/speedread/].
Pepsin works at an optimum pH range from 1 to 4 and specifically cleaves Trp, Phe, Tyr and  Leu [@PMID:25823410]. 
Since it possess high enzyme activity and broad specificity at lower pH, it is preferred over other proteases for MS-based disulphide mapping [@PMID:12476442; @PMID:24980484].
Pepsin is also used extensively for structural mass spectrometry studies with hydrogen-deuterium exchange (HDX) because the rate of back exchange of the amide deuteron is minimized at low pH [@DOI:10.1021/ac902477u; @DOI:10.1002/mas.21565].  
 
Proteinase K was first isolated from the mold _Tritirachium album_ Limber [@PMID:4373242]. 
The epithet 'K' is derived from its ability to efficiently hydrolyse keratin [@PMID:4373242].
It is a member of the subtilisin family of proteases and is relatively unspecific with a preference for proteolysis at hydrophobic and aromatic amino acid residues [@DOI:https://doi.org/10.1016/B978-0-12-382219-2.00714-6]. 
The optimal enzyme activity is between pH 7.5 and 12.
Proteinase K is used at low concentrations for limited proteolysis (LiP) and the detection of protein structural changes in the eponymous technique LiP-MS [@PMID:29072706]. 

![**Multiple protease proteolysis improves protein inference**
The use of other proteases beyond Trypsin such as Lysyl endopeptidase (Lys-C), Peptidyl-Asp metallopeptidase (Asp-N), Glutamyl peptidase I, (Glu-C), Chymotrypsin, Clostripain (Arg-C) or Peptidyl-Lys metalloendopeptidase (Lys-N) can generate a greater diversity of peptides. 
This improves protein sequence coverage and allows for the correct identification of their N-termini. 
Increasing the number of complimentary enzymes used will increase the number of proteins identified by single peptides and decreases the ambiguity of the assignment of protein groups. 
Therefore, this will allow more protein isoforms and post-translational modifications to be identified than using Trypsin alone.](images/Proteolysis_v03.png){#fig:Multiple-protease-proteolysis tag="1" width="100%"}


## Peptide Quantification {.page_break_before}

Discussion of methods to isotopically label peptides or proteins that enable quantification

1. SILAC/SILAM
2. iTRAQ
3. TMT
4. dimethyl labeling

<!-- todo: not sure if this is the best place for this figure about quantification strategies, do we need a whole section on quant? -->

![**Quantitative strategies commonly used in proteomics.**
A) Label-free quantitation. 
Proteins are extracted from samples, enzymatically hydrolyzed into peptides and analyzed by mass spectrometry.
Chromatographic peak areas from peptides are compared across samples that are analyzed sequentially. 
B) Metabolic labelling. 
Stable isotope labeling with amino acids in cell culture (SILAC) is based on feeding cells stable isotope labeled amino acids (“light” or “heavy”). 
Samples grown with heavy or light amino acids are mixed before cell lysis.
The relative intensities of the heavy and light peptide are used to compute protein changes between samples.
C) Isobaric or chemical labelling. 
Proteins are isolated separately from samples, enzymatically hydrolyzed into peptides, and then chemically tagged with isobaric stable isotope labels. 
These isobaric tags produce unique reporter mass-to-charge (m/z) signals that are produced upon fragmentation with MS/MS. 
Peptide fragment ions are used to identify peptides, and the relative reporter ion signals are used for quantification.
](images/Summay_peptide-protein-labeling_.svg){#fig:quant-summary tag="1" width="100%"}




## Peptide or Protein Enrichment

### Protein enrichment (e.g. for protein protein interactions)
* coIP
* APEX
* bioID
* bioplex


### Peptide enrichment 
* antibody enrichments of modifications, e.g. lysine acetylation [@DOI:10.1002/pmic.201800123].
* TiO2 and Fe enrichment of phosphorylation
* Glycosylation
* SISCAPA



## Methods for Peptide Purification {.page_break_before}

1. Reverse phase including tips and cartridges
2. stage tips
3. in stage tip (iST)
4. SP2, SP3
5. s traps



## Types of Mass Spectrometers used for Proteomics {.page_break_before}

1. QQQ
2. Q-TOF
3. Q-Orbitrap
4. LTQ-Orbitrap
5. TOF/TOF
6. FT-ICR
7. types of ion mobility
* SLIM
* FAIMS
* traveling wave
* tims


## Peptide Ionization {.page_break_before}
Until the early 1990s, peptides analysis by mass spectrometry was challenging. 
Hard ionization techniques in use at the time, like fast atom bombardment, were not directly applicable to peptides without destroying or breaking them.
The soft ionization tehniques however, revolutionized the proteomics field and it became possible to routinely ionize and analyze peptides using MALDI and ESI techniques at high-throughput scale. 
These two techniques were so impactful that the 2002 Nobel Prize in Chemistry was co-awarded to John Fenn (ESI) and Koichi Tanaka (MALDI) "for their development of soft desorption ionisation methods for mass spectrometric analyses of biological macromolecules" [@URL:https://www.nobelprize.org/prizes/chemistry/2002/summary/]. 

### MALDI
The term, Matrix-assisted LASER desorption ionization (MALDI), was coined by Hillenkamp and Karas in 1985[@URL:https://pubs.acs.org/doi/abs/10.1021/ac00291a042]. 
Karas and Hillenkamp discovered the MALDI technique first, although a similar ionization method was shown by Koichi Tanaka in 1988 [@DOI:10.1002/rcm.1290020802]. 
A few months later, Karas and Hillenkamp also demonstrated MALDI applied to protein ionization [@DOI:10.1021/ac00171a028].
It also created a controversy that the widely used method of MALDI from these two people had been overlooked, and the Nobel prize was awarded to Tanaka, whose system was rarely used[@URL:https://web.archive.org/web/20070517202246/http://cmbi.bjmu.edu.cn/news/0212/55.htm].

MALDI first requires the peptide sample to be co-crystallized with a matrix molecule, which is usually a volatile, low molecular-weight, organic aromatic compound.
Some examples of such compounds are cyno-hydroxycinnamic acid, dihyrobenzic acid, sinapinic acid, alpha-hydroxycinnamic acid, ferulic acid etc [@URL:https://pubmed.ncbi.nlm.nih.gov/23681820/].
Subsequently, the analyte is placed in a vacuum chamber in which it is irradiated with a LASER, usually at 337nm [@DOI:10.1021/cr010375i].
This laser energy is absorbed by the matrix, which then transfers that energy along with its free protons to the co-crystalized peptides without significantly breaking them.
The matrix and co-crystallized sample generate plumes, and the volatile matrix imparts its protons to the peptides as it gets ionized first.
The weak acidic conditions used as well as the acidic nature of the matrix allows easy exchange of protons for the peptides to get ionized and fly under the electrical field in the mass spectrometer.
These ionized peptides generally form the metastable ions, most of them will fragment quickly [@DOI:10.1021/ac00099a029].
However, it can take several milliseconds and the mass spectrometry analysis can be performed before this time.
Peptides ionized by MALDI almost always take up a single charge and thus observed and detected as [M+H]+ species.

#### MALDI Mechanism
![**MALDI**
The analyte-matrix mixture is irradiated by a laser source, leading to ablation. 
Desorption and proton transfer ionize the analyte molecules that can then be accelerated into a mass spectrometer.](images/MALDI.png){#fig:MALDI-mechanism tag="1" width="100%"}

### Electrospray Ionization
ESI was first applied to peptides by John Fenn and coworkers in 1989 [@DOI:10.1126/science.2675315].
Concepts related to electrospray Ionization (ESI) were published at least as early as 1882, when Lord Rayleigh described the number of charges that could assemble on the surface of a droplet [@DOI:10.1080/14786448208628425]. 
ESI is usually coupled with reverse-phase liquid-chromatography of peptides directly interfaced to a mass spectrometer.
A high voltage (~ 2 kV) is applied between the spray needle and the mass spectrometer.
As solvent exits the needle, it forms droplets that take on charge at the surface, and through a debated mechanism, those charges are imparted to peptide ions.
The liquid phase is generally kept acidic to help impart protons easily to the analytes.

Tryptic peptides ionized by ESI usually carry one charge one the side chain of their c-terminal residue (Arg or Lys) and one charge at their n-terminal amine.
Peptides can have more than one charge if they have a longer peptide backbone, have histidine residues, or have missed cleavages leaving extra Arg and Lys.
In most cases, peptides ionized by ESI are observed at more than one charge state.
Evidence suggests that the distribution of peptide charge states can be maniupulated through chemical additives [@PMID:22610994].

#### Electrospray Mechanism
![**Electrospray Ionization** 
Charged droplets are formed, their size is reduced due to evaporation until charge repulsion leads to Coulomb fission and results in charged analyte molecules.](images/ESI.png){#fig:ESI-mechanism tag="1" width="100%"}

The main goal of ESI is the production of gas-phase ions from electrolyte ions in solution. 
During the process of ionization, the solution emerging from the electrospray needle or capillary is distorted into a Taylor cone and charged droplets are formed.
The charged droplets subsequently decrease in size due to solvent evaporation.
As the droplets shrink, the charge density and Coulombic repulsion increase. 
This process destabilizes the droplets until the repulsion between the charges is higher than the surface tension and they fission (Coulomb explosion) [@PMID:19551695] [@PMID:23134552].
Typical bottom-up proteomics experiments make use of acidic analyte solutions which leads to the formation of positively charged analyte molecules due to an excess presence of protons.

<!-- TODO, explicitly describe the taylor cone and coulombic explosion -->
<!-- TODO: discussion of ionizaation mechanisms, ion evaporation versus charge residue model -->



## Data Acquisition {.page_break_before}

<!-- Figures:
1. show a plot of the polularity of MRM/DIA/DDA/ over time? 
-->

Hybrid mass spectrometers used for modern proteome analysis offer the flexibility to collect data in many different ways. 
Data acquisition strategies differ in the sequence of precursor scans and fragment ion scans, and in how analytes are chosen for MS/MS. 
Constant innovation to develop better data collection methods improves our view of the proteome, but many method options may confuse newcomers. 
This section provides an overview of the general classes of data collection methods. 

Data acquisition strategies for proteomics fall into one of two groups.

1. Data dependent acquisition (DDA), in which the exact scan sequence in each analysis depends on the data that the mass spectrometer observes.
2. Data independent acquisition (DIA), in which the exact scan sequence in each analysis DOES NOT depend on the data; the collected scans are the same whether you inject yeast peptides, human peptides, or a solvent blank.  

DDA and DIA can both be futher subdivided in to targeted and untargeted methods. 

<!-- to do: figure showing the four basic types of data acquisition and their names, like four squares? -->

### DDA

In most cases, the peptide masses that will be observed are not known before doing the experiment. 
Data collection methods must account for this.
DDA was invented in the early 1990s, which enabled collecting MS/MS spectra for observed peptides as they eluting from the LC column [@DOI:10.1006/meth.1994.1031; @DOI:10.1021/ac00104a020; @PMID:24203425]. 

#### Untargeted DDA
A common method currently used in modern proteomics is untargeted DDA. 
The MS collects precursor (MS1) scans iteratively until precursor mass envelopes meeting certain criteria are detected. 
Criteria for selection are usually specific charge states and a minimum signal intensity.
When those ions meet these criteria, the MS selects those masses for fragmentation.

Because ions are selected as they are observed, repeated DDA of the same sample will produce a different set of identifications. 
This stochasticity is the main drawback of DDA. 
To ameliorate this issue, often strategies are used to transfer identifications between multiple sample analyses. 
This transfer of IDs across runs is known as "match between runs", which was originally made famous by the processing software MaxQaunt [@DOI:10.1074/mcp.M113.031591; @DOI:10.1038/nprot.2016.136]. 
There are several other similar tools and strategies, including the accurate mass and time approach [@DOI:10.1002/mas.20071], Q-MEND [@DOI:10.1021/pr0606880], IDEAL-Q [@DOI:10.1074/mcp.M900177-MCP200] and superHIRN [@DOI:10.1002/pmic.200700057].
More recent work has introducted statistical assessment of MBR methods using a two-proteome model [@DOI:10.1021/acs.jproteome.9b00492].
Statistically controlled MBR is currently available in the IonQuant tool [@DOI:10.1016/j.mcpro.2021.100077].

Because DDA is required for quantification of proteins using isobaric tags like TMT, this stochasiticity of DDA limits the ability to compare quantities across batches. 
For example, if you have 3o samples, you can use two sets of the 16-plex kit to label 15 samples in each set with one channel labeled by a pooled sample to enable comparison across the groups.
When you collect DDA data from each of those sets, each set will have MS/MS data from an overlapping but different set of peptides. 
If one set has MS/MS from a peptide but the other set does not, then that peptide cannot be quantified in the whole sample group. 
This limits the number of quantified proteins in large TMT experiments with multiple batches. 
<!-- mention intelligent DDA and real time search? -->

#### Targeted DDA
Targeted DDA is not common in modern proteomics. 
In targeted DDA, in addition to general criteria like a minimum intensity and a certain charge state, the mass spectrometer looks for specific masses.
These masses might be previously observed signals that were previously missed by MS/MS [@DOI:10.1021/pr800828p; @DOI:10.1074/mcp.M700029-MCP200].
In these studies, the sample is first analyzed by LC-MS to detect precursor ion features with some software, and then subsequent analyses target those masses for fragmentation with inclusion lists until they are all fragmeted. 
This was shown to increase proteome converage. 

#### DDA methods for modifications
There are also DDA methods that look for specific fragment or neutral loss ions in the resulting spectra. 
For example, when linear ion traps were the main proteomics workhorses, CID analysis of phosphopeptides would result in predominantly neutral loss of the phosphate with limited sequence ion information. 
To gain sequence ions in these experiemnts, instruments could be set to isolate a loss of 98 Thompsons for MS3 [@DOI:10.1073/pnas.0404720101; @DOI:10.1002/pmic.200800283].
The newer collisional dissociation technique HCD significantly improves the detection of peptide fragments with the phosphorylation intact on fragment ions, and thus, this neutral loss scanning technique is no longer common. 

A similar strategy was introduced for N-linked glycopeptides [@DOI:10.1021/pr300257c]. 
Collisional dissociation of glycosylated peptides produces oxonium ions at 204.09 (HexNAc) or 366.14 (HexHexNAc). 
In oxonium ions from the glycosylation were detected in the top 20 fragments of the HCD spectra, then an ETD scan was triggered. 
This ETD scan provides information about the peptide sequence, while the original HCD scan provides glycan structure information. 

### DIA
The simplest method to operate a mass spectrometer is to have predefined scans that are collected for each sample analysis.
This is DIA; the scans that are collected do not depend on the data that the instrument observes. 
Thus, the scan sequence is the same every time. 
Although simple in terms of data collection, when the scan sequence includes MS/MS, sophisticated software is required to analyze the data. 
Like DDA, DIA can also be either targeted or untargeted [@DOI:10.1080/14789450.2017.1322904]:
The two targeted DIA methods are selected reaction monitoring (SRM) or multiple reaction monitoring (MRM), and untargeted DIA (uDIA) is often referred to simply as "DIA" or SWATH (Figure 4).

![**Types of DIA.**
A) SRM/MRM. 
Peptides are ionized by ESI and although there are many peptides entering the mass spectrometer at any time, the first quadruople (Q1) isolates one mass, which is then fragmented by HCD. 
Fragment masses from the peptide are then selected in the third quadruople (Q3). 
This leads to very low noise and high sensitivity.
B) PRM. 
Like MRM, peptides are selected in the first quadruople, but this analysis is done on a high resolution instrument like an Orbitrap or TOF. 
Selectivity is gained by exploiting the high mass accuracy and resolution to monitor multiple fragment ions. 
C) uDIA/SWATH. 
Like MRM and PRM, peptides are isolated with Q1, but in this case a much wider isolation window is used. 
This usually results in co-isolation of many peptides simultaneously. 
Fragments from many peptides are measured with high resolution and high mass accuracy.
Special software is used to get peptide identities and quantities from the fragment ions. 
](images/data-acquisition-DIA-types.svg){#fig:DIA-types tag="4" width="100%"}

#### Targeted DIA
The first type of targeted DIA is called SRM or MRM [@DOI:10.1016/j.ymeth.2013.05.004].
The popularity of this method in the literature peaked in 2014, with just under 1,500 documents on pubmed that year resulting from a search for "MRM".
In this strategy, the QQQ MS is set so that the first quadrupole selects the precursor mass of the peptide(s) of interest, the second quadrupole fragments the peptide, and the third quadruople monitors the product of specific fragments from that peptide. 
This strategy is very sensitive and has the benefit of very low noise. 
The fragments monitored in Q3 are chosen such that it is unlikely these fragments could arise from another peptide. 
Usually at least a few transitions are monitored for each peptide in order to get multiple measures for that peptide. 

An early example of MRM applied to quantify c-reactive protein was in 2004 [@DOI:10.1002/pmic.200300670].
Around the same time, SRM was combined with antibody enrichment of peptides from target proteins [@DOI:10.1021/pr034086h].
This approach was popular for analysis of plasma proteins [@DOI:10.1074/mcp.M500331-MCP200].
These early examples led to many more studies that used QQQ MS instruments to get accurate quantitation of many proteins in one injection [@DOI:10.1016/j.aca.2017.01.059; @DOI:10.1586/erm.12.32]. 
Scheduling MRM measurement when chromatography is stable additionally enabled better utilization of instrument duty cycle and therefore monitoring of more peptides per injection [@DOI:10.1074/mcp.M700132-MCP200].
Efforts even developed libraries of transitions that allow quantification of any protein in model organisms [@DOI:10.1038/nmeth1108-913].

Another similar targeted DIA method is called parallel reaction monitoring (PRM) [@DOI:10.1074/mcp.O112.020131].
Instead of using a QQQ instrument, PRM uses a hybrid MS with a quadrupole and a high resolution mass analyzer, such as an Q-TOF or Q-Exactive. 
The idea is that instead of monitoring specific fragments in Q3, the high mass accuracy can be used to filter peptide fragments for high selectivity and accurate quantification. 
Studies have found that PRM and MRM/SRM have comparable dynamic range and linearity [@DOI:10.1016/j.jprot.2014.10.017].


#### Untargeted DIA

There were many implementations of uDIA over the years, starting in 2003 by Purvine et al from the Goodlett lab [@DOI:10.1002/pmic.200300362]. 
In this first work they demonstrated uDIA using a Q-TOF with in source fragmentation, and showed that extracted ion chromatograms of precursor and fragment ions matched in shape suggesting that this could be used to identify and quantify peptides. 
The following year, Venable et al from the Yates lab introduced uDIA with an ion trap [@DOI:10.1038/nmeth705].
Subsequent methods include MSE [@DOI:10.1002/rcm.2550], PAcIFIC [@DOI:10.1021/ac900888s], all ions fragmentation (AIF) [@DOI:10.1074/mcp.M110.001537].
Computational methods were also developed to automate interpretation of this data, such as DeMux [@DOI:10.1074/mcp.M110.001537], XDIA [@DOI:10.1093/bioinformatics/btq031], and ETISEQ [@DOI:10.1186/1471-2105-10-244].

The paper that is often cited for uDIA that led to widespread adoption was by Gillet et al. from the Aebersold group in 2012 [@DOI:10.1074/mcp.O111.016717].
In this paper they branded the idea as SWATH.
Widespread adoption may have been facilitated by the co-marketing of this idea by ABSciex as a proteomics solution on their new 5600 Q-TOF (called "tripleTOF" despite containing only one TOF, likely a portmanteau of "triple quadrupole" and "Q-TOF"). 
Importantly, in the Gillet et al. paper the authors described a computational method to extract information from SWATH where peptides of interest were queried against the data.
They also demonstrated the application of SWATH to measure proteomic changes that happen in diauxic shift, and showed that SWATH can reveal modified peptides, in this case a methionine oxidation. 

There are also many papers describing uDIA with orbitraps.
One early example described combining random isolation windows together and then demultiplexing the chimeric spectra [@DOI:10.1038/nmeth.2528].
In another landmark paper, over 6,000 proteins were identified from mouse tissue by at least 2 peptides [@DOI:10.1074/mcp.RA117.000314]. 
In 2018, the new model orbitrap at that time (HF-X) enabled identification of nearly 6,000 human proteins in only 30 minutes. 
Currently orbitraps have all but replaced the Sciex Q-TOFs for DIA data collection. 

A new direction in uDIA is the addition of ion separation by ion mobility. 
This has appeared in two forms.
On the timsTOF, diaPASEF makes use of the trapped ion mobility to increase speed and sensitivity of analysis [@DOI:10.1038/s41592-020-00998-0].
On the orbitrap, the combination of FAIMS and DIA has enabled the identification of over 10,000 proteins from one sample, which is a major milestone [@DOI:10.1021/acs.jproteome.2c00023].







## Analysis of Raw Data {.page_break_before}

The goal of basic data analysis is to convert raw spectral data into identities and quantities of peptides and proteins that can be used for biologically-focused analysis. 
This step may often include measures of quality control, cross-run data normalization, quantification on different levels (precursor, peptide, protein), protein inference, PTM (post translational modification) localization and also first steps of data analysis, such as statistical hypothesis tests. 

In typical bottom-up proteomics experiments, proteins are digested into peptides and further analyzed with LC-MS/MS systems. 
Peptides can have different PTMs and ionize differently depending on their length and amino acid distributions. 
Therefore, mass spectrometers often record different charge and modification states of one single peptide. 
The entity that is recorded on a mass spectrometer is usually referred to as a precursor ion (peptide with its modification and charge state). 
This precursor ion is fragmented and the precursor or peptide sequences are obtained though spectral matching. 
The quantity of a precursor is estimated with various methods.
The measured precursor quantities are combined to generate a peptide quantity. 
Peptides are also often combined into a protein group through protein inference, which combines multiple peptide identifications into a single protein identification [@PMID:16009968] [@DOI:10.1016/j.jprot.2016.08.002].
Protein inference is still a challenge in bottom-up proteomics. 

Due to the inherent differences in the data structures of DDA and DIA measurements, there exist different types of software that can facilitate the steps mentioned above. 
The existing software for DDA and DIA analysis can be further divided into freeware and non-freeware:

#### DDA freeware 

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| MaxQuant |Cox and Mann, 2008[@DOI:10.1038/nbt.1511]|[MaxQuant](https://www.maxquant.org/)    |
| MSFragger|   Kong et al., 2017[@DOI:10.1038/nmeth.4256]    |    [MSFragger](https://msfragger.nesvilab.org/) |
| Mascot   |Perkins et al., 1999[@PMID:10612281]             |    [Mascot](https://www.matrixscience.com/)     |
| MS-GF+   |Kim et al., [@DOI:10.1038/ncomms6277]            | [MS-GF+](https://github.com/MSGFPlus/msgfplus)  |
| X!Tandem |Craig et al., [@DOI:10.1002/rcm.1198;@DOI:10.1093/bioinformatics/bth092]  | [GPMDB](https://www.thegpm.org/tandem/) |


#### DIA freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| MaxDIA |Cox and Mann, 2008[@DOI:10.1038/nbt.1511]|        [MaxQuant](https://www.maxquant.org/)    |
| Skyline|MacLean et al., 2010[@DOI:10.1093/bioinformatics/btq054]|[Skyline](https://skyline.ms/project/home/software/Skyline/begin.view) |
| DIA-NN|Demichev et al., 2019[@DOI:10.1038/s41592-019-0638-x]  |    [DIA-NN](https://github.com/vdemichev/DiaNN)     |


#### Targeted proteomics freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| Skyline|MacLean et al., 2010[@DOI:10.1093/bioinformatics/btq054]|[Skyline](https://skyline.ms/project/home/software/Skyline/begin.view) |


#### DDA non-freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| ProteomeDiscoverer ||[ProteomeDiscoverer](https://www.thermofisher.com/ch/en/home/industrial/mass-spectrometry/liquid-chromatography-mass-spectrometry-lc-ms/lc-ms-software/multi-omics-data-analysis/proteome-discoverer-software.html)|
| Mascot             |Perkins et al., 1999[@PMID:10612281]             |    [Mascot](https://www.matrixscience.com/)     |
| Spectromine   |           |    [Spectromine](ttps://biognosys.com/software/spectromine/?gclid=Cj0KCQiAoY-PBhCNARIsABcz770mjUz6iavBr9Ql7RPUdMvaHu9RYgPNrEfZco1wExEeoFwnQXuCHscaAlgBEALw_wcB)     |
| PEAKS   |Tran et al., 2018[@DOI:10.1038/s41592-018-0260-3] | [PEAKS](https://www.bioinfor.com/peaks-studio/)  |


#### DIA non-freeware:

|   Name   |         Publication           |             Website               |
|:--------:|:-----------------------------:|:---------------------------------:|
| Spectronaut |Bruderer et al., 2015[@DOI:10.1074/mcp.M114.044305]|[Spectronaut](https://biognosys.com/software/spectronaut/)|
| PEAKS   |Tran et al., 2018[@DOI:10.1038/s41592-018-0260-3] | [PEAKS](https://www.bioinfor.com/peaks-studio/)  |


#### Data Summary and Interpretation
|    Name    |            Publication     |                 Website              |
|:----------:|:--------------------------:|:------------------------------------:|
|Peptide Shaker|Vaudel _et al._, 2015[@DOI:10.1038/nbt.3109;@DOI:10.1021/acs.jproteome.1c00678]|[PeptideShaker](http://compomics.github.io/projects/peptide-shaker.html), [Peptide Shaker Online](https://github.com/barsnes-group/peptide-shaker-online)|


### Analysis of DDA data
DDA data analysis either directly uses the vendor proprietary data format directly with a proprietary search engine like Mascot, Sequest (through Proteome Discoverer), Paragon (through Protein Pilot), or it can be processed through one of the many freely available search engines or pipelines, for example, MaxQuant, MSGF+, X!Tandem, Morpheus, MSFragger, and OMSSA. 
Tables 1 and 4 give weblinks and citations for these software tools.
<!-- todo: need to make sure all these are listed in the table and cited -->
<!-- todo: need a paragraph discussing intergration environments like the transproteomics pipeline (TPP) and IDpicker -->
For analysis with freeware, raw data is converted to either text-based MGF (mascot generic format) or into a standard open XML format like mzML [@DOI:10.1074/mcp.R110.000133] [@PMID:20013381][@DOI:10.1074/mcp.R112.019695]. 
The appropriate FASTA file containing proteins predicted from that organism's genome is chosen as a reference database to search the experimental spectra.
All search parameters like peptide and fragment mass errors (i.e. MS1 and MS2 tolerances), enzyme specificity, number of missed cleavages, chemical artefacts (fixed modifications) and potential biological modifications (variable/dynamic modifications) are specified before executing the search.
The search algorithm scores each query spectrum against its possible peptide matches [@DOI:10.1002/mas.21543]. 
A spectrum and its best scoring candidate peptide are called a peptide spectrum match (PSM).
The scores reflect a _goodness-of-fit_ between an experimental spectrum and a theoretical one and do not necessarily depict the correctness of the peptide assignment.

For evaluating the matches, a decoy database is preferred as a null model for peptide matching.
A randomized or reversed version of target database is used as a nonparametric null model.
The decoy database can be searched separate from the target database (Kall's method)[@DOI:10.1021/pr700600n] or it can be combined with the target database before search (Elias and Gygi method)[@PMID:17327847].
Using either separate method or concatenated database search method, an estimate of false hits can be calculated which is used to estimate the false discovery rate (FDR) [@DOI:10.1007/978-1-4939-3106-4_7]. 
The FDR denotes the proportion of false hits in the population accepted as true.
For Kall's method: the false hits are estimated to be the number of decoys above a given threshold. 
It is assumed that the number of decoy hits that pass a threshold are the false hits. 
A similar number of target population may also be false. 
Therefore, the FDR is calculated as [@DOI:10.1021/acs.jproteome.6b00144]:

$$FDR = \frac{Decoy PSMs + 1}{Target PSMs}$$

For Elias and Gygi Method, the target population in which FDR is estimated changes.
The target and decoy hits coming from a joint database compete against each other.
For any spectrum, either a target or a decoy peptide can be the best hit.
It is argued that the joint target-decoy population has decoy hits as confirmed false hits.
However, due to the joint database search, the target database may also have equal number of false hits. 
Thus, the number of false hits is multiplied by two for FDR estimation.

$$FDR = \frac{2 * Decoy PSMs}{Target + Decoy PSMs}$$


### Strategies for analysis of DIA data

### Targeted proteomics data analysis

### Quality control

Quality control should be a central aspect of any mass spectrometry-based study to ensure reproducibility of generated results.
There are two types of quality controls that can be conducted for any kind of mass spectrometry experiment.
The first one is focused on monitoring the perfomance of the instruments themselves (e.g. HPLC and mass spectrometer), whereas the second one is focused on your experiments. 
For further reading, we recommend to take a look at issue 11 on quality control published in the journal _Proteomics_ in 2011 [@DOI:10.1002/pmic.201190020], especially the review by Köcher _et al._ [@DOI:10.1002/pmic.201000578], as well as the review published by Bittremieux _et al._ in 2017 [@DOI:10.1002/mas.21544].

#### Instrument Performance

It is generally advisable to monitor instrument performance regularly. 
Instrument calibrations in regular intervals help ensure that performance is maintained.
Often basic calibration and sensitivity can be checked by direct infusion of a standard.
During the calibration you can check injection times (for ion trap instruments) and intensity of the ions in the calibration mix.

After ensuring good calibration and signal with the simple calibration mixture, it is advisable to analyze complex samples, such as tryptic digests of whole-cell lysates (e.g. HeLa cells, HEK cells, yeast, etc.) or tryptic digests of purified proteins.
The additional check with a complex sample ensures all aspects of the system are working together correctly, especially the liquid chromatography and emitter.
These digests should be analyzed after every instrument calibration and periodically between samples when acquiring more extensive batches.
Data measured from tryptic digests should be analyzed by the software of your choice and the numbers of identified peptide precursors and proteins can be compared with previous controls for consistency.

Another strategy is to analyze digested purified proteins, which easily enable discovery of retention time shifts and mass accuracy problems. 
In case you are working with a Thermo mass spectrometer, you can open the acquired .raw file directly either in FreeStyle or in Qual Browser and look for specific m/z values of your peptides.
Looking at the intensity of the extracted peaks will help identify sensitivity fluctuations. 

Carry-over between different measurments can be identified from blank measurements which are subsequently analyzed with your search software of choice.
Blank measurements can be injections of different buffers, water or the starting conditions of your liquid chromatography. 
In case of increased detection of carry-over, injections with trifluoroethanol can be performed.

Another factor to take into consideration is the stability of your electrospray.
Electrospray stability tends to worsen over time as columns wear, as well as when measuring samples with residual contaminants, such as salts or detergents. 
You will notice spray instabilities either in the total ion chromatogram (TIC) as thin spikes with short periods of no measured signal or if you install cameras at your ESI source.
Suboptimal spray conditions will usually result in droplets forming on the emitter, being released into the mass spectrometer (also referred to as "spitting"). 
Real-time quality control software (listed in the table below) can help you identify instrument issues right away.

#### Data Quality Control

Apart from instrument performance, any kind of data analysis should have proper quality control in place to identify problematic measurements and to exclude them if necessary. 
It is recommended to develop a standardized system for data quality control early on and to keep this consistent over time. 
Adding indexed retention time (iRT) peptides can help identify and correct gradient and retention time inconsistencies between samples at the data analysis stage.
Decoy searches help monitor and control the false-discovery rate. 
Inlcuding common contaminants, such as keratins, in the FASTA files used for searches can help identify sample preparation issues.
Other parameters to check in your analysis are the consistency of the number of peptide-spectrum matches, identified peptides and proteins over all samples of your study, as well as your coefficients of variation between your replicates.
Before and after data normalization (if normalization is performed) it is good to compare the median intensities of all measurments to identify potential measurement or normalization issues. 
Precursor charge distributions, missed cleavage numbers, peak width, as well as the number of points per peak are additional parameters that can be checked.
In case you are analyzing different conditions, you can perform hierarchical clustering or a principal component analysis to check if your samples cluster as expected.

#### Quality Control Software

##### Raw file and real-time analysis

|    Name    |         Supported instrument vendors        |            Website/Download           |            publication            |           Note               |
|:----------:|:-------------------------------------------:|:-------------------------------------:|:---------------------------------:|:----------------------------:|
| QuiC | Thermo Scientific, AB SCIEX, Agilent, Bruker, Waters |[QuiC](https://biognosys.com/resources/quic-manual/)|                      | requires Biognosys iRT peptides |
| AlphaPept |  Thermo Scientific, Bruker              | [AlphaPept](https://github.com/MannLabs/alphapept) | [@DOI:10.1101/2021.07.23.453379]    |                      |
| RawMeat 2.1 | Thermo Scientific | [RawMeat](https://proteomicsresource.washington.edu/protocols06/RawMeat_1007.exe) |      |          |
| rawDiag | Thermo Scientific | [rawDiag](https://github.com/fgcz/rawDiag) |   [@DOI:10.1021/acs.jproteome.8b00173]        |                 |
| rawrr | Thermo Scientific | [rawrr](https://github.com/fgcz/rawrr) |  [@DOI:10.1021/acs.jproteome.0c00866]    |                       |
| rawBeans |  Thermo or mzML   | [rawBeans](https://bitbucket.org/incpm/prot-qc/downloads/)|   [@DOI:10.1021/acs.jproteome.0c00956]     |                  |
| SIMPATIQCO | Thermo Scientific | [SIMPATIQCO](https://ms.imp.ac.at/index.php?action=simpatiqco) | [@DOI:10.1021/pr300163u]    |                     |
| QC-ART |                     | [QC-ART](https://github.com/stanfill/QC-ART) | [@DOI:10.1074/mcp.RA118.000648] |                      |
| SprayQc | Thermo Scientific, AB SCIEX, extensible to other instrumentation | [SprayQc](http://sourceforge.org/projects/sprayqc) | [@DOI:10.1021/pr201219e] |               |
| Metriculator |         | [Metriculator](http://github.com/princelab/metriculator) | [@DOI:10.1093/bioinformatics/btt510] |            |
| MassQC |               | [MassQC](https://massqc.proteomesoftware.com/) |                   |                     |
| OpenMS |               | [OpenMS](https://www.openms.de/) |  [@DOI:10.1038/nmeth.3959]   |                  |

##### Search result QC

|    Name    |       Website/Download/publication        |              publication        |              Note           |
|:----------:|:-----------------------------------------:|:-------------------------------:|:----------------------------:|
| MSStats |[MSStats](https://github.com/Vitek-Lab/MSstats) |  [@DOI:10.1093/bioinformatics/btu305]|   can use output from MaxQuant, Proteome Discoverer, Skyline, Progenesis, Spectronaut |
| MSStatsQC |[MSStatsQC](https://msstats.org/msstatsqc/)   |  [@DOI:10.1074/mcp.M116.064774]    |               |
| PTXQC |[PTXQC](https://github.com/cbielow/PTXQC) |[@DOI:10.1021/acs.jproteome.5b00780] | requires MaxQuant search engine output | 
| protti | [protti](https://github.com/jpquast/protti) | [@DOI:10.1093/bioadv/vbab041]      |                   |

<!-- todo: this table is probably very incomplete. Add more tools -->


### Statistical hypothesis testing




## Databases {.page_break_before}

### What are they and where do you get them?

#### Protein Database Sources and Types
Many mass spectrometry-based proteomic techniques use search algorithms that require a defined theoretical search space to identify peptide sequences based on precursor mass and fragmentation patterns, which are then used to infer the presence and abundance of a protein. 
The search space is calculated from the potential proteins in a sample, which includes the proteome (often a single species) and expected contaminants. 
This is called database searching and the flat file of protein sequences in FASTA format acts as a protein database. 
In this section, we will describe major resources for proteome FASTA files (protein sequence collections), how to retrieve them, and suggested best practices for preserving FASTA file provenance to improve reproducibility.  

In general, FASTA sequence collections can be retrieved from three central clearing houses: UniProt, RefSeq, and Ensembl. 
These will be discussed separately below as they each have specific design goals, data products, and unique characteristics. 
It is important to learn the following three points for each resource: the source of the underlying data, canonical versus non-canonical sequences, and how versioning works. 
These points, along with general best practices, such as using a taxonomic identifier, are essential to understand and communicate search settings used in analyses of proteomic datasets. 
Finally, it is critical to understand that sequence collections from these three resources are not the same, nor do they offer the same sets of species.

Key terminology may vary between resources, so these terms are defined here. 
The term “taxon identifier” is used across resources and is based on the NCBI taxonomy database. 
Every taxonomic node has a number, e.g., Homo sapiens (genus species) is 9606 and Mammalia (class) is 40674. 
This can be useful when retrieving and describing protein sequence collections. 
Another term used is “annotation”, which has different meanings in different contexts. 
Broadly, a “genome annotation” is the result of an annotation pipeline to predict coding sequences, and often a gene name/symbol if possible. 
Two examples are MAKER [@PMID:22192575] and the RefSeq annotation pipeline [@URL:https://www.ncbi.nlm.nih.gov/genome/annotation_euk/process]. 
Alternatively, “protein annotation” (or gene annotation) often refers to the annotation of proteins (gene products) using names and ontology (i.e., protein names, gene names/symbols, functional domains, gene onotology, keywords, etc.). 
Protein annotation is termed “biocuration” and described in detail by UniProt [@URL:https://www.uniprot.org/help/biocuration]. 
Lastly, there are established minimum reporting guidelines for referring to FASTA files established in MIAPE: Mass Spectrometry Informatics that are taxon identifier and number of sequences [@URL:https://www.psidev.info/sites/default/files/2018-03/MIAPE_MSI_1.1.pdf; @PMID:23500130]. 
The FASTA file naming suggestions below are not official but are suggested as a best practice.

##### UniProt
The Universal Protein Resource (UniProt) [@PMID:14681372], has three different products: UniProt Knowledgebase (UniProtKB), the UniProt Reference Clusters (UniRef), and the UniProt Archive (UniParc). 
The numerous resources and capabilities associated with the UniProt are not explored in this section, but these are well described on UniProt’s website. 
UniProtKB is the source of proteomes across the Tree of Life and is the resource we will be describing herein. 
There are broadly two types of proteome sequence collections: Swiss-Prot/TrEMBL and designated proteomes. 
The Swiss-Prot/TrEMBL type can be understood by discussing how data is integrated into UniProt. 
Most protein sequences in UniProt are derived from coding sequences submitted to EMBL-Bank, GenBank and DDBJ. 
These translated sequences are initially imported into TrEMBL database, which is why TrEMBL is also termed “unreviewed”. 
There are other sources of protein sequences, as described by UniProt [@URL:https://www.uniprot.org/help/sequence_origin]. 
These include the Protein Data Bank (PDB), direct protein sequencing, sequences derived from the literature, gene prediction (from sources such as Ensembl) or in-house prediction by UniProt itself. 
Protein sequences can then be manually curated into the Swiss-Prot database using multiple outlined steps (described in detail by UniProt here [@URL:https://www.uniprot.org/help/manual_curation]) and is why Swiss-Prot is also termed “reviewed”. 
Note that more than one TrEMBL entry may be removed and replaced by a single Swiss-Prot entry during curation. 
A search of “organism:9606” at UniProtKB will retrieve both the Swiss-Prot/reviewed and TrEMBL/unreviewed sequences for Homo sapiens. 
The entries do not overlap, so users often either use just Swiss-Prot or Swiss-Prot combined with TrEMBL, the latter being the most exhaustive option. 
With ever-increasing numbers of high-quality genome assemblies processed with robust automated annotation pipelines, TrEMBL entries will contain higher quality protein sequences than in the past. 
In other words, if a mammal species has 20 000 to 40 000 entries in UniProtKB and many of these are TrEMBL, users should be comfortable using all the protein entries to define their search space (more on this later when discussing proteomes at UniProtKB). 
Determining the expected size of a well-annotated proteome requires additional knowledge, but tools to answer these questions continue to improve. 
As more and more genome annotations are generated, the backlog of manual curation continues to increase. 
However, automated genome annotations are also rapidly improving, blurring the line between Swiss-Prot and TrEMBL utility.
	
The second type of protein sequence collections available at UniProtKB are designated proteomes, with subclasses of “proteome”, “reference proteome” or “pan-proteome”. 
As defined by UniProt, a proteome is the set of proteins derived from the annotation of a completely sequenced genome assembly (one proteome per genome assembly). 
This means that a proteome will include both Swiss-Prot and TrEMBL entries present in a single genome annotation, and that all entries in the proteome can be traced to a single complete genome assembly. 
This aids in tracking provenance as assemblies change, and metrics of these assemblies are available. 
These metrics include Benchmarking Universal Single-Copy Ortholog (BUSCO) score, and “Completeness” as Standard, Close Standard or Outlier based on the Complete Proteome Detector (CPD). 
Given the quality of genome annotation pipelines, using a proteome as a FASTA file for a species is the preferred method of defining search spaces now. 
Outside of humans, no higher eukaryotic Swiss-Prot sequence collections are complete enough for use in proteomics analyses, but this does not mean that the available Swiss-Prot plus TrEMBL protein sequence collection precludes accurate proteomic data analysis. 
Lastly, the difference between reference proteome and proteome is used to highlight model organisms or organisms of interest, but not to imply improved quality. 
UniProt also has support for the concept of “pan proteomes” (consensus proteomes for a closely related set of organisms) but this is mostly used for bacteria (e.g., strains of a given species will share a pan proteome). 

When retrieving protein sequence collections as Swiss-Prot/TrEMBL or designated proteomes, there is an option of downloading “FASTA (canonical)” or “FASTA (canonical & isoform)”. 
The later includes additional manually annotated isoforms for Swiss-Prot sequences. 
Each Swiss-Prot entry has one canonical sequence chosen by the manual curator. 
Any additional sequence variants (mostly from alternative slicing) are annotated as differences with respect to the canonical sequence. 
Specifying “canonical” will select only one protein sequence per Swiss-Prot entry while specifying “canonical & isoforms” will download additional protein sequences by including isoforms for Swiss-Prot entries. 
Recently, an option to “download one protein sequence per gene (FASTA)” has been added. 
These FASTA files include Swiss-Prot and TrEMBL sequences to number about 20 000 protein sequences for a wide range of higher eukaryotic organisms.

The number of additional isoforms varies considerably by species. 
In the human, mouse, and rat proteomes of the total number of entries, 26 %, 40 % and 72 % are canonical, respectively. 
The choice of including isoforms is related to the search algorithm and experimental goals. 
For instance, if differentiating isoforms is relevant, they should be included otherwise they will not be detected. 
In cases where isoforms are present in the FASTA (evident by shared protein names) but these cannot be removed prior to downloading (e.g., California sea lion, Zalophus californianus, proteome UP000515165, release 2022_01), non-redundant FASTA files can be manually generated (i.e., “remove_duplicates.py” via [@URL:https://github.com/pwilmart/fasta_utilities]). 
If possible, retrieving canonical protein sequences via proteomes is the most straight forward approach and in general appropriate for most search algorithms, versus the method of searching and downloading Swiss-Prot and/or TrEMBL entries.

Though FASTA files are the typical input of many search algorithms, UniProt also offers an XML and GFF format download. 
In contrast to the flat FASTA file format, the XML format includes sequence information as well as associated information like PTMs, which is used in some search algorithms like MetaMorpheus [@PMID:26418581].

Once a protein sequence collection has been selected and retrieved, there is the evergreen question of how to name and report this to others in a way that allows them to reproduce the retrieval. The minimum reporting information is the taxon identified and number of sequences used [@URL:https://www.psidev.info/sites/default/files/2018-03/MIAPE_MSI_1.1.pdf; @PMID:23500130]. The following naming format (and those below) augments this and is suggested for UniProtKB FASTA files (the use of underscores or hyphens is not critical): 
[common or scientific name]-[taxon id]-uniprot-[swiss-prot/trembl/proteome]-[UP# if used]-[canonical/canonical plus isoform]-[release]
example of a Homo sapiens (human) protein fasta from UniProtKB:

Human-9606-uniprot-proteome-UP000005640-canonical-2022_01.fasta

The importance of the taxon identifier has already been described above and is a consistent identifier across time and shared across resources. The choices of Swiss-Prot and TrEMBL in some combination was discussed above, and Proteome can be “proteome”, “reference proteome” or “pan-proteome”. The proteome identifier (‘UP’ followed by 9 digits) is conserved across releases, and release information should also be included. A confusing issue to newcomers is what the term “release” means. This is a year_month format (e.g., 2022_01), but it is not the date a FASTA file was downloaded or created, nor does it imply there are monthly updates. This release “date” is a traceable release identifier that is listed on UniProt’s website. Including all this information ensures that the exact provenance of a FASTA file is known and allows the FASTA file to be regenerated.

##### RefSeq
NCBI is a clearing house of numerous types of data and databases. 
Specific to protein sequence collections, NCBI Reference Sequence Database (RefSeq) provides annotated genomes across the Tree of Life. 
The newly developed NCBI Datasets portal [@URL:https://www.ncbi.nlm.nih.gov/datasets] is the preferred method for accessing the myriad of NCBI data products, though protein sequence collections can also be retrieved from RefSeq directly[@URL:https://www.ncbi.nlm.nih.gov/genome/annotation_euk/all; @URL:https://www.ncbi.nlm.nih.gov/refseq/about/prokaryotes]. 
Like UniProt described above, most of the additional functionality and information available through NCBI Datasets and RefSeq will not be described here, although the Eukaryotic RefSeq annotation dashboard [@URL:https://www.ncbi.nlm.nih.gov/genome/annotation_euk/status] is a noteworthy resource to monitor the progress of new or re-annotations. 
We recommend exploring the resources available from NCBI [@URL:https://www.ncbi.nlm.nih.gov/guide/training-tutorials], utilizing their tutorials and help requests.

RefSeq is akin to the “proteome” sequence collection from UniProtKB, where a release is based on a single genome assembly. 
If a more complete genome assembly is deposited or additional secondary evidence (e.g., RNA sequencing) is deposited, RefSeq can update the annotation with a new annotation release. 
Every annotation release will have an annotation report that contains information on the underlying genome assembly, the new genome annotation, secondary evidence used, and various statistics about what was updated. 
The current annotation release is referred to as the “reference annotation”, but each annotation is numbered sequentially starting at 100 (the first release). 
Certain species are on scheduled re-annotation, like human and mouse, while other species are updated as needed based on new data and community feedback (ex. release 100 of taxon 9704 was in 2018, but a more contiguous genome assembly resulted in re-annotation to release 101 in 2020). 
This general process for new and existing species is described in Heck and Neely [@PMID:32786681].

Since RefSeq is genome assembly-centric, its protein sequence collections are retrieved for each species. 
This contrasts with being able to use a higher-level taxon identifier like 40674 (Mammalia) in UniProt to retrieve a single FASTA. 
To accomplish this same search in NCBI Datasets requires a Mammalia search, followed by browsing all 2083 genomes and then filtering the results to reference genomes with annotations, and those resulting 188 could be bulk downloaded, though this will still be 188 individual FASTA files. 
It is possible to download a single FASTA from an upper-level taxon identifier using the NCBI Taxonomy Browser, though this service may be redundant with the new NCBI Datasets portal. 
Given the constant development of NCBI Datasets, these functionalities may change, but the general RefSeq philosophy of single species FASTA should be kept in mind. 
Likewise, when retrieving genome annotations there is no ability to specify canonical entries only, but it is possible to use computational tools to remove redundant entries (“remove_duplicates.py” from [@URL:https://github.com/pwilmart/fasta_utilities]). 

Similar to the UniProtKB FASTA file naming suggestion, the following naming format is suggested for RefSeq protein sequence collection FASTA (the use of underscores or hyphens is not critical): 
[common or scientific name]-[taxon id]-refseq-[release number]
example of a Equus caballus (horse) protein FASTA from RefSeq:
Equus_caballus-9796-refseq-103.fasta
The release number starts at 100 and is consecutively numbered. 
Note, the human releases only recently began following this consecutive numbering for Release 110, and previously had a much longer number to be included (e.g., NCBI Release 109.20211119). 
Also, in a few species (Human and Chinese hamster, currently), there is a reference and an alternate assembly, both with an available annotation. 
In these cases, including the underlying assembly identifier would be needed. Note that when you retrieve the protein FASTA from NCBI it will include two more identifiers that aren’t required in the file name since it can be determined from the taxon identifier and release number. 
These are the genome assembly used (this is generated by the depositor and follows no naming scheme) and the RefSeq identifier (GCF followed by a number string). 
These aren’t essential for FASTA naming, but are for comparing between UniProt, RefSeq and Ensembl when the same underlying assembly is used (or not, indicating how up to date one is versus the other).

##### Ensembl
There are two main web portals for Ensembl sequence collections: the Ensembl genome browser [@URL:https://ensembl.org] has vertebrate organisms and the Ensemble Genome project [@URL:ensemblgenomes.org] has specific web portals for different non-vertebrate branches of the Tree of Life. 
This contrasts with NCBI and UniProt where all branches are centrally available. 
Recently, Ensembl has created a new portal “Rapid Release” focusing on quickly making annotations available (replacing the “Pre-Ensemble” portal), albeit without the full functionality of the primary Ensembl resources. 
Overall, Ensembl provides diverse comparative and genomic tools that should be explored, but, specific to this discussion, they provide species-specific genome annotation products similar to RefSeq. 

To retrieve a protein sequence collection from Ensemble at any of the portals, a species can be searched using a name, which will then have taxon identifier displayed (but searching by identifier is not readily apparent). 
From the results you can select your species and follow links for genome annotation. 
Caution should be used when browsing the annotation products since the protein coding sequence (abbreviated “cds”) annotations are nucleic acid sequences (a useable via 3-frame translation if using certain software), while actual translated peptide sequences are in the “pep” folders. 
The pep folders contain file names with “ab initio” and “all” in the FASTA file names (file extensions are “fa” for FASTA and “gz” indicating gzip compression algorithm), while there may only be one pep product for certain species in the “Rapid Release” portal. 
The “ab initio” FASTA files contain mostly predicted gene products. 
The “all” FASTA files are the usable protein sequence collections. 
Ensembl FASTA files usually have some protein sequence redundancy.

Ensembl provides a release number for all the databases within each portal. 
Similar to the UniProt file naming suggestion, the following naming format is suggested for Ensembl protein sequence collection FASTA (the use of underscores or hyphens is not critical): 

[common or scientific name]-[taxon id]-ensembl-[abinitio/all]-[rapid]-[release number]

example of a Sus scrofa (pig) protein FASTA from Ensembl:

Pig-9823-ensembl-all-106.fasta

Similar to the FASTA download from RefSeq, the downloaded file name can include additional identifying information related to the underlying genome assembly. 
Again, this is not required for labeling, but is useful to easily compare assembly versions. 

Since much of the data from Ensembl is also regularly processed into UniProt, using UniProt sequence collections instead may be preferred. 
That said, they are not on the same release schedule nor will the FASTA files contain the same proteins. 
Ensembl sequences still must go through the established protein sequence pipeline at UniProt to remove redundancy and conform to UniProt accession and FASTA header formats. 
Moreover, the gene-centric and comparative tools built into Ensembl may be more experimentally appropriate and using an Ensembl protein sequence collection can better leverage those tools.

#### Other resources
There are other locations of protein sequence collections, and these will likewise have different FASTA file formatting; sequences may have unusual characters, and formats of accessions and FASTA header lines may need to be reformatted to be compatible with search software. 
These alternatives include institutes like the Joint Genome Institute’s microbial genome clearing house, species-specific community resource (e.g., PomBase, FlyBase, WormBase, TryTrypDB, etc.), and one-off websites tenuously hosting in-house annotations. 
It is preferred to use protein sequence collection from the main three sources described here, since provenance can be tracked, and versions maintained. 
It is beyond the scope of this discussion to address other genome annotation resources, how they are versioned, or the best way to describe FASTA files retrieved from those sources. 
In these cases, defaulting to the minimum requirements of listing number of entries and supplying the FASTA along with data are necessary.

#### Contaminants
Samples are rarely comprised of only proteins from the species of interest. 
There can be protein contamination during sample collection or processing. 
This may include proteins from human skin, wool from clothing, particles from latex, or even porcine trypsin itself, all of which contain proteins that can be digested along with the intended sample and analyzed in the mass spectrometer. 
Avoiding unwanted matching of mass spectra originating from contaminant proteins to the cellular proteins due to sequence similarities is important to the identification and quantitation of as many cellular proteins as possible.
To avoid random matching, repositories of supplementary sequences for contaminant proteins have been added to a reference database for MS data searches.
Appending a contaminants database to the reference database allows the identification of peptides that are not exclusive to one species.
Peptides that are exclusive to the organism of interest are used to calculate abundance to avoid inflated quantitative results due to potential contaminant peptides.

As early as 2004, The Global Proteome Machine was providing a protein sequence collection of these common Repository of Adventitious Proteins (cRAP), while another contaminant list was published in 2008 [@PMID:18790129]. 
The current cRAP version (v1.0) was described in 2012 [@URL:https://www.thegpm.org/crap] and is still widely in use today. 
cRAP is the contaminant protein list used in nearly all modern database searching software, though the documentation, versioning or updating of many of these “built-in” contaminant sequence collections is difficult to follow. 
There is also another contaminant sequence collection distributed with MaxQuant. 
Together, the cRAP and MaxQuant contaminant protein sequence collections are found in some form across most software, including MetaMorpheus and Philosopher (available in FragPipe) [@PMID:32669682]. 
This list of known frequently contaminating proteins can either be automatically included by the software or can be retrieved as a FASTA to be used along with the primary search FASTA(s). 
Recently the Hao Lab has revisited these common contaminant sequences in an effort to update the protein sequences, test their utility on experimental data, and add or remove entries [@DOI:10.1101/2022.04.27.489766]. 

In addition to these environmentally unintended contaminants, there are known contaminants that also have available protein sequence collections (or can be generated using the steps above) and should be included in the search space. 
These can include the media cells were grown in (e.g., fetal bovine serum [@PMID:20641139; @PMID:33532042], food fed to cells/animals (e.g., Caenorhabditis elegans grown on Escherichia coli) or known non-specific binders in affinity purification (i.e., CRAPome [@PMID:23921808]). 
The common Repository of Fetal Bovine Serum Proteins (cRFP)[@PMID:31475827] are protein lists of common protein contaminants and fetal serum bovine sequences used to reduced the number of falsely identified proteins in cell culture experiments.
Cells washed or cultured in contaminant free media before harvest or the collection of secreted proteins depletes most high abundance contaminant proteins but the sequence similarity between contaminant and secreted proteins can cause false identifications and overestimation of the true protein abundance leading to wasted resources and time on validating false leads.
As emphasized throughout this section, accurately defining the search space is essential for accurate results and, especially in the case of contaminants, requires knowledge of the experiment and sample processing to adequately define possible background proteins.



### Choosing the right database


<!-- add greater exploration of how to choose a database -->

Proteomics data analysis requires carefully matching the search space (defined by the database choice) with the expected proteins. 
A properly chosen database will minimize false positives and false negatives. 
Choosing a database that is too large will increase the number of false positives, or decoy hits, which in turn will reduce the total number of identifiable proteins.
For this reason it is ill advised to search against all possible protein sequences ever predicted from any genomic sequence. 
On the other hand, choosing a database that is too small may increase false negatives, or missed protein identifications, because in order for a protein to be identified it must be present in the database. 
Thus, proteomics practitioners must do their best to predict the proteins that might be in their sample before they analyze their data.

Proteomics data analysis requires carefully aligning the search space with the expected proteome and the statistical approach of the search algorithm. 
Search algorithms can self-correct when a database is overly large such that higher identity thresholds are required for identification to minimize false positives (e.g., Mascot), while smaller experiment-specific search spaces (also referred to as “subsets”) can have unintended effects on false positives if not managed appropriately [@PMID:34236864; @PMID:30560673; @PMID:26125591] or may even improve protein identifications [@PMID:27975281]. 
Whether to employ a search space that is sample-specific (i.e., subset), species-specific (with only canonical proteins, described below), exhaustive species-specific (including all isoforms), or even larger clade-level protein sequence set (e.g., the over 14 million protein sequences associated with Fungi, taxon identifier 4751) is a complex issue that is experiment and software dependent. 
Moreover, in cases where no species-specific protein sequence collection exists, homology-based searching can be used (as described in [@PMID:32786681]). 
In each of these cases, proteomics practitioners must understand their specific experimental sample and search algorithm in order to know how to best define the search space, which is essential to yielding accurate results. See more discussion of database choice in the following section. 


## Biological Interpretation {.page_break_before}


1. term enrichment analysis (KEGG, GO)
2. network analysis methods
3. structure analysis
4. isoform analysis
5. follow-up experiments


## Methods for protein or peptide fractionation {.page_break_before}
Protein fractionation
* SDS-PAGE

Peptide fractionation
* bRP


## Tandem Mass Spectrometry and Peptide Fragmentation {.page_break_before}

### Tandem Mass Spectrometry
Why do we need tandem mass spectra data for proteomics? 
As mass accuracy and resolution increase, the number of potential peptide matches decrease.
Still, there are many potential matches to a human peptide with a 5 ppm mass tolerance window (citation).
Additional information is required to uniquely assign a signal to a peptide. 
Early approaches described use of accurate mass and time data to uniquely identify peptides [@DOI:10.2144/04374RV01]. 
Most current research, however, has pursued using the pattern of peptide fragment masses helps narrow down the number of potential peptides. 


### Peptide Fragmentation

*how it works*
Modern proteomics utilizes hybrid mass spectrometers, where hybrid means there are multiple mass analyzers working in harmony.
Most hybrid mass spectrometers combine a quadrople for mass selection before a high resolution analyzer, usually a TOF or an orbitrap. 
In these hybrid mass spectrometers, mass selection happens using the first quadrupole to isolate a small mass range around that mass (usually less than 1 thompson).
The selected ions then pass to the collision cell where fragmentation happens. 

<!-- linear ion traps don't need a quadrupole first -->

1. Nomenclature of backbone fragments (abc, xyz, internal, losses).
2. Mechanisms of peptide fragmentation, collision based (CID and HCD, PQD?) versus electron based (ECD and ETD).


### Basic Spectral Interpretation
Segway into the section on raw data analysis. 






## Experiment Design

This section should discuss trade offs and balancing them to design an experiment. 
1. constraints: Each experiment will have different constraints, which may include the number of samples needed for analysis, or desire to quantify a specific subset of proteins within a sample.
2. sample size
3. statistics
4. costs


## Acknowledgements {.page_break_before}

The authors thank Phil Wilmarth for helpful input. 
Identification of certain commercial equipment, instruments, software, or materials does not imply recommendation or endorsement by the National Institute of Standards and Technology, nor does it imply that the products identified are necessarily the best available for the purpose.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>