---
title: A Practical Beginner's Guide to Proteomics
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2022-05-10'
author-meta:
- Muralidharan Vanuopadath
- Devasahayam Arokia Balaya Rex
- Amit Kumar Yadav
- Martín L. Mayta
- Dina Schuster
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
  <meta name="dc.date" content="2022-05-10" />
  <meta name="citation_publication_date" content="2022-05-10" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Muralidharan Vanuopadath" />
  <meta name="citation_author_institution" content="School of Biotechnology, Amrita Vishwa Vidyapeetham, Kollam-690 525, Kerala, India" />
  <meta name="citation_author_orcid" content="0000-0002-9364-917X" />
  <meta name="twitter:creator" content="@V_MuraleeDhar" />
  <meta name="citation_author" content="Devasahayam Arokia Balaya Rex" />
  <meta name="citation_author_institution" content="Center for Systems Biology and Molecular Medicine, Yenepoya Research Centre, Yenepoya (Deemed to be University), Mangalore 575018, India" />
  <meta name="citation_author_orcid" content="0000-0002-9556-3150" />
  <meta name="twitter:creator" content="@rexprem" />
  <meta name="citation_author" content="Amit Kumar Yadav" />
  <meta name="citation_author_institution" content="Translational Health Science and Technology Institute" />
  <meta name="citation_author_orcid" content="0000-0002-9445-8156" />
  <meta name="twitter:creator" content="@theoneamit" />
  <meta name="citation_author" content="Martín L. Mayta" />
  <meta name="citation_author_institution" content="School of Medicine and Health Sciences, Center for Health Sciences Research, Universidad Adventista del Plata, Libertador San Martín 3103, Argentina" />
  <meta name="citation_author_institution" content="Molecular Biology Department, School of Pharmacy and Biochemistry, Universidad Nacional de Rosario, Rosario 2000, Argentina" />
  <meta name="citation_author_orcid" content="0000-0002-7986-4551" />
  <meta name="twitter:creator" content="@MartinMayta2" />
  <meta name="citation_author" content="Dina Schuster" />
  <meta name="citation_author_institution" content="Department of Biology, Institute of Molecular Systems Biology, ETH Zurich, Zurich 8093, Switzerland" />
  <meta name="citation_author_institution" content="Department of Biology, Institute of Molecular Biology and Biophysics, ETH Zurich, Zurich 8093, Switzerland" />
  <meta name="citation_author_institution" content="Laboratory of Biomolecular Research, Division of Biology and Chemistry, Paul Scherrer Institute, Villigen 5232, Switzerland" />
  <meta name="citation_author_orcid" content="0000-0001-6611-8237" />
  <meta name="twitter:creator" content="@dina_sch" />
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
  <link rel="alternate" type="text/html" href="https://jessegmeyerlab.github.io/proteomics-tutorial/v/7a3657f321af82db6a35323abd7f01b4bf1b9d70/" />
  <meta name="manubot_html_url_versioned" content="https://jessegmeyerlab.github.io/proteomics-tutorial/v/7a3657f321af82db6a35323abd7f01b4bf1b9d70/" />
  <meta name="manubot_pdf_url_versioned" content="https://jessegmeyerlab.github.io/proteomics-tutorial/v/7a3657f321af82db6a35323abd7f01b4bf1b9d70/manuscript.pdf" />
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
([permalink](https://jessegmeyerlab.github.io/proteomics-tutorial/v/7a3657f321af82db6a35323abd7f01b4bf1b9d70/))
was automatically generated
from [jessegmeyerlab/proteomics-tutorial@7a3657f](https://github.com/jessegmeyerlab/proteomics-tutorial/tree/7a3657f321af82db6a35323abd7f01b4bf1b9d70)
on May 10, 2022.
</em></small>

## Authors



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
Therefore, bottom-up proteomics does not actually measure proteins, but must infer their presence [@URL:https://doi.org/10.1021/ac0341261]. 
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


1. Types of experiments enabled by proteomics
2. Protein extraction
3. proteolysis
4. Isotopic Labeling
5. Enrichments
6. Peptide purification
7. Mass Spectrometry
8. Peptide Ionization
9. Data Acquisition
10. Basic Data Analysis
11. Biological Interpretation
12. Experimental considerations and design




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

First, proteins must be isolated from the sample matrix. Because some proteins alter other proteins, the goal is to simultaneously solubilizw and denature proteins. This is achieved with a combination of salt and chaotropic agent. 

1. Choice of Lysis buffer
* Urea can cause chemical modifications 
2. Sample type and homogenisation methods
* specialised sample preparation protocols for non-denaturing protein isolation (i.e. for LiP-MS, HDMX-MS etc) 
4. chemicals to avoid: PEGs, detergents etc
5. removal of contaminations, Protein Precipitation
* detergent reomoval resins, S-TRAP (Protifi) etc
7. protein alkylation
* choices of reduction and alkylation reagents, TCEP/DTT/2BME, Chloroacetamide/iodoacetamide, n-ethyl maleimide



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


## Peptide and Protein Labeling {.page_break_before}

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

Data acquisition strategies for proteomics fall generally within targeted or untargeted, and they can depend on the data (data dependent acquisition or DDA) or be data independent (data-independent acquisition or DIA). 


### DDA

#### Targeted DDA

#### Untargeted DIA


### DIA

#### Targeted DIA

#### Untargeted DIA




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
Peptides are also often combined into a protein group through protein inference, which combines multiple peptide identifications into a single protein identification [@DOI:https://doi.org/10.1074/mcp.R500012-MCP200] [@DOI:10.1016/j.jprot.2016.08.002].
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
All search prarameters like peptide and fragment mass errors (i.e. MS1 and MS2 tolerances), enzyme specificity, number of missed cleavages, chemical artefacts (fixed modifications) and potential biological modifications (variable/dynamic modifications) are specified before executing the search.
The search algorithm scores each query spectrum against its possible peptide matches [@DOI:10.1002/mas.21543]. 
A spectrum and its best scoring candidate peptide are called a peptide spectrum match (PSM).
The scores reflect a _goodness-of-fit_ between an experimental spectrum and a theoretical one and do not necessarily depict the correctness of the peptide assignment.

For evaluating the matches, a decoy database is preferred as a null model for peptide matching.
A randomized or reversed version of target database is used as a nonparametric null model.
The decoy database can be searched separate from the target database (Kall's method)[@DOI:10.1021/pr700600n] or it can be combined with the target database before search (Elias and Gygi method)[@DOI:10.1038/nmeth1019].
Using either separate method or concatenated database search method, an estimate of false hits can be calculated which is used to estimate the false discovery rate (FDR) [@DOI:10.1007/978-1-4939-3106-4_7]. 
The FDR denotes the proportion of false hits in the population accepted as true.
For Kall's method: the false hits are estimated to be the number of decoys above a given threshold. 
It is assumed that the number of decoy hits that pass a threshold are the false hits. 
A similar number of target population may also be false. 
Therefore, the FDR is calculated as:

$$FDR = \frac{Decoy PSMs}{Target PSMs}$$

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

### Statistical hypothesis testing




## Biological Interpretation {.page_break_before}


1. term enrichment analysis (KEGG, GO)
2. network analysis methods
3. structure analysis
4. isoform analysis
5. follow-up experiments


## Experiment Design

This section should discuss trade offs and balancing them to design an experiment. 
1. constraints: Each experiment will have different constraints, which may include the number of samples needed for analysis, or desire to quantify a specific subset of proteins within a sample.
2. sample size
3. statistics
4. costs


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
