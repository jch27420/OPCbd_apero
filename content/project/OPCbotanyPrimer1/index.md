---
title: "OPC Botany Primer1"
subtitle: " "
excerpt: "Flowering plants are not only numerous (i.e. >300,000 species), but also structurally quite diverse. This botany primer covers some of the more common floral terms and concepts used throughout this site."
date: 2025-05-07
author: "JCH"
draft: false
bibliography: OPCbotany.bib
csl: NIH_research.csl
link-citations: yes
tags:
  - hugo-site
categories:
  - Theme Features
  - R
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: USDA - Plants
  url: https://plants.usda.gov/home
- icon: door-open
  icon_pack: fas
  name: HHMI - Biointeractive
  url: https://www.biointeractive.org/classroom-resources
- icon: door-open
  icon_pack: fas
  name: Development & Cell Differentiation
  url: https://www.biointeractive.org/classroom-resources/cellular-differentiation-along-concentration-gradients
- icon: door-open
  icon_pack: fas
  name: Konza Prairie Biological Station
  url: https://kpbs.konza.k-state.edu/
- icon: door-open
  icon_pack: fas
  name:  iNaturalist
  url: https://www.inaturalist.org/
- icon: door-open
  icon_pack: fas
  name:  NIH Human Genome Research Institute
  url: https://www.genome.gov/genetics-glossary
- icon: door-open
  icon_pack: fas
  name:  Jackson Laboratory
  url: https://www.jax.org/education-and-learning
- icon: door-open
  icon_pack: fas
  name:  Cold Spring Harbor - DNA Learning Center
  url: https://www.dnaftb.org/
- icon: door-open
  icon_pack: fas
  name:  iBIOLOGY - Science Education
  url: https://www.ibiology.org/
- icon: door-open
  icon_pack: fas
  name:  PDB - Protein Database
  url: https://www.rcsb.org/
- icon: door-open
  icon_pack: fas
  name:  Berkeley Evolution 101
  url: https://evolution.berkeley.edu/evolution-101/

---

<style type="text/css">
/* ================== */
/*  Photo/Figures CSS */
/* ================== */
.myDiv {
  border: 2px solid gray;
  padding: 5px;
  margin: auto;
  background-color: white;    
}
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 90%;
  }
/* =============================== */
/*          CSS for Links          */
/* =============================== */
a.one:link {color: rgb(0, 0, 200);}
a.one:visited {color: rgb(192, 20, 172);}
a.one:hover {color: rgb(255, 20, 100);}

/* ============================== */
/*     CSS for stylizing text     */
/* ============================== */

#strokeW {
  color: yellow;
  background-color: white;
  text-shadow: 1px 0 #000;
  }

#strokeB {
  color: black;
  background-color: white;
  text-shadow: 1px 0 #000;
  }

#BBlk {
  font-weight: bold;
  color: rgb(0, 0, 0);
  border: 2px solid black;
  margin: 1px;
  }

#Blk20 {
  color: black;
  font-size: 20px;
  text-align: left;
  }

#BBlk20 {
  font-weight: bold;
  color: black;
  font-size: 20px;
  text-align: left;
  }

#BlkS {
  font-weight: bold;
  color: white;
  text-shadow: -1px -1px black, 1px 1px white;
  }

#Blk { font-weight: bold; color: rgb(0, 0, 0); }
#Red { font-weight: bold; color: rgb(255, 10, 20); }
#Red2 { font-weight: bold; color: rgb(255, 50, 50); }
#Dred { font-weight: bold; color: rgb(175, 0, 0); }
#Hpink { font-weight: bold; color: rgb(255, 20, 147); }
#Or { font-weight: bold; color: rgb(255, 140, 0); }
#Or2 { font-weight: bold; color: rgb(245, 90, 0); }
#Gold { font-weight: bold; color: rgb(230, 190, 0); }
#Ly { font-weight: bold; color: rgb(225, 200, 0); }
#Y1 { font-weight: bold; color: rgb(255, 225, 100); }
#Y2 { font-weight: bold; color: rgb(225, 200, 50); }
#GrY { font-weight: bold; color: rgb(240, 240, 0); }
#Grod { font-weight: bold; color: rgb(200, 160, 40); }
#Gr1 { font-weight: bold; color: rgb(25, 200, 25); }
#Gr2 { font-weight: bold; color: rgb(25, 150, 25); }
#Gr3 { font-weight: bold; color: rgb(25, 100, 25); }
#Moss { font-weight: bold; color: rgb(80, 210, 100); }
#BGr { font-weight: bold; color: rgb(50, 205, 170); }
#Teal { font-weight: bold; color: rgb(60, 180, 180); }
#Teal2 { font-weight: bold; color: rgb(60, 100, 220); }
#Blue { font-weight: bold; color: blue; }
#SkyB { font-weight: bold; color: rgb(104, 207, 240); }
#Cb { font-weight: bold; color: rgb(0, 123, 167); }
#Glacialb { font-weight: bold; color: rgb(54, 139, 193); }
#Db2 { font-weight: bold; color: rgb(0, 0, 100); }
#Lb1 { font-weight: bold; color: rgb(50, 215, 255); }
#Lb2 { font-weight: bold; color: rgb(50, 155, 255); }
#Lb3 { font-weight: bold; color: rgb(50, 115, 255); }
#Violet { font-weight: bold; color: rgb(180, 73, 255); }
#V2 { font-weight: bold; color: rgb(183, 137, 211); }
#Purple { font-weight: bold; color: rgb(150, 0, 255); }
#Dpurp { font-weight: bold; color: rgb(95, 0, 161); }
#Vred { font-weight: bold; color: rgb(186, 0, 100); }
#Magenta { font-weight: bold; color: rgb(255, 0, 255); }
#Coral { font-weight: bold; color: rgb(255, 127, 80); }
#Salmon { font-weight: bold; color: rgb(255, 140, 160); }
#Crim { font-weight: bold; color: rgb(220, 20, 60); }
#Rasp { font-weight: bold; color: rgb(227, 11, 92); }
#Lgray { font-weight: bold; color: rgb(220, 220, 220); }
#Silver { font-weight: bold; color: rgb(192, 192, 192); }
#Gray { font-weight: bold; color: rgb(155, 155, 155); }
#Gray2 { font-weight: bold; color: rgb(215, 200, 200); }
#Dgray { font-weight: bold; color: rgb(95, 95, 95); }
#Br { font-weight: bold; color: rgb(165, 42, 42); }
#Rust { font-weight: bold; color: rgb(183, 65, 14); }
#Dbr { font-weight: bold; color: rgb(100, 20, 20); }
#Zinc { font-weight: bold; color: rgb(140, 209, 187); }
#Zinc2 { font-weight: bold; color: rgb(0, 102, 102); }
</style>
<!------------------------------------------------>
<!-------- JAVASCRIPT - enable LaTex MATH -------->
<!------------------------------------------------>
<script type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS_CHTML">
</script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true},
      jax: ["input/TeX","input/MathML","input/AsciiMath","output/CommonHTML"],
      extensions: ["tex2jax.js","mml2jax.js","asciimath2jax.js","MathMenu.js","MathZoom.js","AssistiveMML.js", "[Contrib]/a11y/accessibility-menu.js"],
      TeX: {
      extensions: ["AMSmath.js","AMSsymbols.js","noErrors.js","noUndefined.js"],
      equationNumbers: {
      autoNumber: "AMS"
      }
    }
  });
</script>
<!--------------------------------------->
<!------------ FLOWER FIG   ------------->
<!--------------------------------------->

<div align="center">

<figure>

<img src="images/flowers.jpg" alt="" width="500px"/>

</figure>

</div>

<!------------------------------------->
<!-------- END - FLOWER FIG   --------->
<!------------------------------------->
<!-- this is a subheadline -->
<details>
<summary>
<b>TABLE OF CONTENTS</b>
</summary>

1.  <a href="#Angio"><b>Flowering Plants</b></a>
    - <a href="#FPsf"><b>1.1 Flowering Plants - Structure & Function</b></a>
    - <a href="#Fig1"><b>Fig. 1 - Stem Apical Meristem (<span id="Dred">SAM</span>) Structure</b></a>
2.  <a href="#SCgenes"><b>Flower Plants - Stem Cells & Genes</b></a>
    - <a href="#Fig2"><b>Fig. 2 - Plant Stem Cell Signalling Network</b></a>
3.  <a href="#FAnat"><b>Flower Anatomy</b></a>
    - <a href="#Fig3"><b>Fig. 3 - Flower Structures</b></a>
4.  <a href="#IF"><b>Inflorescence Structure</b></a>
    - <a href="#Fig4"><b>Fig. 4 - Inflorescence Structures</b></a>
    - <a href="#IFG"><b>4.1 Inflorescence Gene Regulation</b></a>
    - <a href="#Fig5"><b>Fig. 5 - Arabidopsis Flowering Mutants</b></a>
    - <a href="#Fig6"><b>Fig. 6 - <span id="strokeB">P</span>hoto<span id="strokeW">P</span>eriod & Flowering</b></a>
    - <a href="#Fig7"><b>Fig. 7 - <span id="strokeB">P</span>hoto<span id="strokeW">P</span>eriod Genes & Flowering</b></a>
    - <a href="#ABCs"><b>4.2 Models of Floral Organ Development</b></a>
    - <a href="#Fig8"><b>Fig. 8 - AE & Quartet Model of Floral Organ Development</b></a>
5.  <a href="#Glos"><b>List of Terms</b></a>
6.  <a href="#Refs"><b>References</b></a>

</details>

<a id="Angio"></a>
<!----------------------------------------------------->
<!--------- SECTION 1 - IMPORTANTCE OF SOILS  --------->
<!----------------------------------------------------->
**<span style="border: 2px solid black;">  1. FLOWERING PLANTS  </span>** Flowering plants, also known as **angiosperms** (Greek: “<i>angeion</i>” = vessel, and “<i>sperma</i>” = seed), are a large group of photosynthetic organisms (\>350,000 species) that provide many of the ecological goods and services that make life possible on this planet (e.g. regulate global <b><a class="one" href="https://opc-project.netlify.app/project/prairie_soil_ecosystem/" target="_blank" title="Go to OPC Soil Ecology">biogeochemical cycles</a></b>, <span id="Gr2">B</span>**GCC**). Although their role in <b><a class="one" href="https://opc-project.netlify.app/project/prairie_soil_ecosystem/" target="_blank" title="Go to OPC Soil Ecology">soil ecology</a></b> has already been briefly discussed, many of the terms used to describe them, particularly as it relates to their identification (i.e. <b><a class="one" href="https://opc-project.netlify.app/gallery/" target="_blank" title="Go to OPC Gallery">gallery section</a></b>), needs some clarification. Like most scientific disciplines there is a seemingly endless number of esoteric terms used to describe plants. Although it’s important to standardize terms and concepts the resulting lexicon often creates a barrier to learning. With that in mind I hope this section will provide some clarity to the subject of flower anatomy and development. Unfortunately some subjects I do discuss below will require some basic chemistry knowledge. Educational links for key concepts are either provided above or are embedded within the text (e.g. consult: <b><a class="one" href="https://opc-project.netlify.app/project/pnps/" target="_blank" title="Go to PNP">Plant Natural Products</a></b>).

<a id="FPsf"></a>
**<span style="border: 2px solid black;">  1.1 FLOWERING PLANTS - STRUCTURE & FUNCTION  </span>** **Angiosperms** have evolved a seemingly endless variety of floral arrangements (i.e. **inflorescences**). Why? Specifically, why devote so much energy to creating all of the morphological and genetic diversity that we see today in flowering plants? Is it simply because plants are forced to constantly evolve (i.e. improve their <b><a class="one" href="https://evolution.berkeley.edu/evolution-101/mechanisms-the-processes-of-evolution/evolutionary-fitness/" target="_blank" title="Go to Evolution 101">fitness</a></b>) in order to keep up with an ever changing environment? Considering a plant’s limited mobility one might also suspect that the answer lies with how plants go about scattering their proverbial “<i>seed</i>”, or more specifically pollen. Mating challenges are nothing new to most species, so using unique floral displays and structures to woo would be pollinators seems like an obvious solution. However, is it simply all about the “<i>birds and the bees</i>”? Plants are also capable of self-pollination and therefore may simply rely upon physical or **abiotic** factors (e.g. wind, water, fire) to ensure reproductive success. Regardless of the reasons, from a purely practical point of view the physical features of plants are the most important factor used to identify them (see <b><a class="one" href="https://opc-project.netlify.app/gallery/" target="_blank" title="Go to Gallery">OPC Photo Gallery</a></b>). This simply means that identifying plant structures will be important if your intention is to identifying plant species in the field. Hopefully more advanced and portable technologies in the future will alleviate much of our species identification problems.  
    So what regulates the structure of plants? Of course aerial traits like the shape of the **inflorescence** are largely controlled by species-specific genes. And the most important cells where this genetic program plays out is no doubt the primary **shoot apical meristem** (<span id="Dred">SAM</span>), a specialized growth centre that houses totipotent **stem cells**. In fact most stem cells housed within different types of **meristems** remain totipotent (i.e. capable of producing any cell type) throughout the plant’s entire life. So for **inflorescence** development the <span id="Dred">SAM</span> is, as **Jürgens** (2001) put it, the “<i>…ultimate source of cells for all aerial parts of the plant</i>”.**<sup>[1](#ref-jurgens_apical-basal_2001)</sup>** **Foster** (1938) noted many years ago that “<i>…the most distinctive feature of the meristem of the shoot apex…is the segregation of its cells into a number of well-defined zones</i>”. Based on his microscope studies several **meristem** zones were proposed, including: **(i) Zone I** as “<i>the position of the apical initial group, from which by anticlinal and periclinal divisions respectively the surface layer (sl) and the internal tissue of the growing point originate</i>”,**<sup>[2](#ref-foster_structure_1938)</sup>** **(ii) Zone II** as the “<i>…prominent cup-shaped mass of large, slowly dividing central <u>mother cells</u></i>”,**<sup>[2](#ref-foster_structure_1938)</sup>** and **(iii) Zone III** as the remaining cells along the periphery and lower margins of the “<i>central mother cells</i>”. These cells are noted for their “<i>…smaller size and frequency of division</i>”.**<sup>[2](#ref-foster_structure_1938)</sup>** For **Foster** **Zone III** represented a transition zone that gave way to “<i>the peripheral subsurface layers (Zone IV) and the rib meristem (Zone V)</i>”.**<sup>[2](#ref-foster_structure_1938)</sup>** Present day descriptions of the apical **meristem** often refer to the surface layer as the **tunica** and the main internal body of cells as the **corpus**. In addition the **tunica** of **angiosperms** like <b><a class="one" href="https://www.arabidopsis.org/" target="_blank" title="Go to TAIR"><i>Arabidopsis thaliana</i></a></b> contains two horizontal layers of cells (i.e. **L1** and **L2**) that are maintained by <u>anti-clinical</u> (i.e. dividing plane is perpendicular to surface) cellular division. In keeping with **Foster’s** zonal model the **apical meristem** is currently divided up into three main zones: (i) the **central zone** or <span id="Dred">CZ</span>, (ii) the **peripheral zone** or <span id="Dred">PZ</span>, and (iii) the **rib zone**, which is also known as the **rib meristem** (<span id="Dred">RM</span>).**<sup>[3](#ref-traas_cellular_2001)</sup>** The totipotent **stem cells** are found within the <span id="Dred">CZ</span> (i.e. occupies part of the **tunica** and **corpus**) and their numbers and identities (i.e. “<i>stem-ness</i>”) are largely controlled by cells within the <u>organizing centre</u> (<span id="Dred">OC</span>) located just below the <span id="Dred">CZ</span>.**<sup>[4](#ref-laux_wuschel_1996)–[6](#ref-schoof_stem_2000)</sup>** There are also secondary **meristems** that are responsible for lateral growth (i.e. increased plant girth), but only apical and axillary **meristems** produce elongating and branching shoots, as well as their leaves and flowers (i.e. **inflorescence**). However, from an ecological stand point, only plant’s with suitable or well adapted **inflorescence** traits (i.e. <b><a class="one" href="https://evolution.berkeley.edu/evolution-101/mechanisms-the-processes-of-evolution/evolutionary-fitness/" target="_blank" title="Go to Evolution 101">fitness</a></b>) will likely survive to produce the next generation of flowers. This was pointed out by Swedish botanist **Göte Turesson** (1922) over a century ago when he stated that “<i>…habitat types represents the genotypical response of the species population to a definite habitat….<u>ecotype</u> is used as an ecological sub-unit to cover the product arising as a result of the genotypical response of an <u>ecospecies</u> to a particular habitat</i>”.**<sup>[7](#ref-turesson_species_1922),[8](#ref-turesson_genotypical_1922)</sup>**

<a id="Fig1"></a>
<!--------------------------------------->
<!------------ FIG 1 - SAM  ------------->
<!--------------------------------------->

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/SAM_Structure1.jpg" alt="" width="800px"/>

</figure>

**Figure 1. Stem Apical Meristem Structure**. Structures called **meristems** (Greek: “<i>merizein</i>” = to divide) contain totipotent **stem cells** that give rise to all of the tissue within adult plants. The <u>primary</u> **apical meristems** are located at opposite ends of the plant (i.e. shoot and root).**<sup>[1](#ref-jurgens_apical-basal_2001),[3](#ref-traas_cellular_2001)</sup>** *Arabidopsis thaliana* is a small annual *cruciferous* plant (cross-shaped flower) that has become one of the few preferred or standard plant research models in biology.**<sup>[9](#ref-fink_anatomy_1998),[10](#ref-kramer_planting_2015)</sup>** During the early vegetative stage of development wild type *Arabidopsis* produces a rosette of 9 to 17 basal leaves.**<sup>[11](#ref-schultz_leafy_1991)</sup>** Floral development begins with a **bolting** stage (i.e. elongation of the primary shoot) followed by the production of **phytomers** with bracts and lateral **meristems** that develop into **indeterminate co-inflorescence** (i.e. mini-versions of the main stem inflorescence). During later stages of development **phytomers** take on a different character, namely they form bract-less nodes with lateral **meristems** that develop into flowers. Overall the plant takes the form of a **compound raceme** typically with three **co-inflorescences** and ~30 flowers. In <i>Arabidopsis</i> a dome shaped mass of cells known as the **shoot apical meristem** (<span id="Dred">SAM</span>) forms early on during embryonic development. Some of the daughter cells generated by <span id="Dred">SAM</span> will go on to form **meristems** at specific locations along the length of the growing stem (e.g. **axillary meristems** located in the leaf **axil**). The typical apical **meristem** (Left box) is divided up into different zones based on varying cytological, histological and molecular characteristics.**<sup>[1](#ref-jurgens_apical-basal_2001),[3](#ref-traas_cellular_2001)</sup>** **Stem cells** reside within the **central zone** (<span id="Dred">CZ</span>) of the **meristem** where they undergo **anti-clinical** and **peri-clinical** cellular divisions giving rise to both horizontal (e.g. **L1**, **L2**) and vertical growth, respectively. These new cells add to the **peripheral zone** (<span id="Dred">PZ</span>) and underlying regions known as the **rib zone** or **rib meristem** (<span id="Dred">RM</span>). As the position of the **apical meristem** continues to climb over <u>time</u> the lower peripheral cells become under the influence of new chemical signals that can trigger <b><a class="one" href="https://www.biointeractive.org/classroom-resources/cellular-differentiation-along-concentration-gradients" target="_blank" title="Go to HHMI">cellular differentiation</a></b>. One of the major factors responsible for maintaining **stem cell** identity is a homeobox containing transcription factor known as **WUSCHEL**, or <span id="Dred">WUS</span> (**Fig. 2**). Transcription of <span id="Dred">WUS</span> is restricted to cells within a small region of the <span id="Dred">RM</span> known as the **organization centre** (<span id="Dred">OC</span>).**<sup>[5](#ref-mayer_role_1998),[6](#ref-schoof_stem_2000)</sup>** <span id="Dred">WUS</span> protein then migrates from the <span id="Dred">OC</span> to the upper **stem cell** compartment via **plasmodesmata** where it directly activates the transcription of **CLAVATA-3** (<span id="Or2">CLV</span>**3**).**<sup>[6](#ref-schoof_stem_2000),[12](#ref-brand_dependence_2000)–[14](#ref-daum_mechanistic_2014)</sup>** Expression of the <span id="Or2">CLV</span>**3** gene confers **stem cell** identity (i.e. **stem cell** marker) and is therefore confined to the <span id="Dred">CZ</span> to limit the size of the **stem cell** population. The latter is partly achieved by <span id="Or2">CLV</span>**3** itself, since it functions as a extracellular signaling molecule that activates plasma membrane receptors that are more widely expressed, including cells within the <span id="Dred">OC</span>.**<sup>[12](#ref-brand_dependence_2000),[15](#ref-fletcher_signaling_1999),[16](#ref-rojo_clv3_2002)</sup>** Here activation of <span id="Or2">CLV</span>**3** receptors triggers a cell signaling cascade that inhibits <span id="Dred">WUS</span> expression (**Fig. 2**). This negative feed-back loop between <span id="Or2">CLV</span>**3** and <span id="Dred">WUS</span> is regulated in part by the transcription factor **Hairy Meristem** (<span id="Purple">HAM</span>),**<sup>[17](#ref-zhou_control_2015),[18](#ref-zhou_hairy_2018)</sup>** which binds to <span id="Dred">WUS</span> and acts as a transcriptional repressor of <span id="Or2">CLV</span>**3** expression.

</div>

<!----------------------------------------------->
<!-------- END - FIG 1 - SAM Structure  --------->
<!----------------------------------------------->

<a id="SCgenes"></a>
**<span style="border: 2px solid black;">  2. FLOWERING PLANTS - STEM CELLS & GENES  </span>** Many studies over the last three decades have identified numerous genes that are involved in regulating plant **meristems**. These genes and the environments or **niches** they operate within ultimately control the “<i>fate</i>” of **stem cells**, namely whether they continue to self-renew and maintain their identity, or differentiate and specialize to produce new tissues and organs. However, describing all of the complex networks of genes regulating **stem cells** is beyond the scope of this short primer. Nevertheless, it is worth exploring a few important regulatory genes that control **stem cells** since the structural identity of plants is largely controlled by them. And arguably the most important genes regulating **stem cells** are transcription factors, particularly those containing a <b><a class="one" href="https://www.ebi.ac.uk/interpro/entry/pfam/PF00046/" target="_blank" title="Go to InterPro">homeobox</a></b> domain.**<sup>[19](#ref-van_der_graaff_wus_2009),[20](#ref-mukherjee_comprehensive_2009)</sup>** The latter refers to a highly conserved region of the protein, approximately 60 amino acids in length, that is responsible for DNA binding. This transcription factor family plays a central role in body plan specification not only in plants but in most multi-cellular organisms.**<sup>[21](#ref-gehring_homeodomain_1994),[22](#ref-burglin_homeodomain_2016)</sup>** For example <span id="Crim">WUS</span>, the founding member of the **WOX** (<b><a class="one" href="https://www.ebi.ac.uk/interpro/protein/UniProt/Q9SB92/" target="_blank" title="Go to InterPro">WUSCHEL</a></b>-**RELATED HOMEOBOX**) family of transcription factors, plays a central role in the maintenance of plant **stem cells**.**<sup>[4](#ref-laux_wuschel_1996),[5](#ref-mayer_role_1998)</sup>** It’s expression is detected early on during development (i.e. 16 cell stage) and subsequently confined to the <span id="Dred">OC</span> of apical and floral **meristems**.**<sup>[5](#ref-mayer_role_1998),[6](#ref-schoof_stem_2000),[23](#ref-yadav_wuschel_2010)</sup>** <span id="Crim">WUS</span> then moves between cells via **plasmodesmata**,**<sup>[13](#ref-yadav_wuschel_2011),[14](#ref-daum_mechanistic_2014)</sup>** a type of cytoplasmic bridge that spans the plant cell wall and links the cytoplasm of adjacent cells.**<sup>[24](#ref-maule_plasmodesmata_2008),[25](#ref-zambryski_plasmodesmata_2008)</sup>** Once it reaches the upper **stem cell** compartment (<span id="Dred">CZ</span>) it directly activates the expression of <span id="Or2">CLV</span>**3** (**CLAVATA3**),**<sup>[6](#ref-schoof_stem_2000),[12](#ref-brand_dependence_2000),[13](#ref-yadav_wuschel_2011),[26](#ref-brand_regulation_2002)</sup>** which functions as a small peptide ligand to several receptor-like proteins, including the heteromeric <span id="Or2">CLV</span>**1**-<span id="Or2">CLV</span>**2** complex.**<sup>[15](#ref-fletcher_signaling_1999),[16](#ref-rojo_clv3_2002),[27](#ref-clark_clavata1_1997)–[31](#ref-shimizu_bam_2015)</sup>** Activation of <span id="Or2">CLV</span>**1**-<span id="Or2">CLV</span>**2** inhibits the expression of <span id="Crim">WUS</span> thus creating a negative feedback-loop between the upper **stem cell** pool and lower <span id="Dred">OC</span>. Research shows that the <span id="Or2">CLV</span>**3**/<span id="Crim">WUS</span> circuit lies at the core of **stem cell** identity within **meristems** (**Fig. 2**).  
    <span id="Crim">WUS</span> also plays a role in maintaining **floral meristems**.**<sup>[4](#ref-laux_wuschel_1996)</sup>** Peripheral **meristem** cells fated to initiate floral organ development must switch from an indeterminate **stem cell** state, maintained by transcription factors like <span id="Crim">WUS</span>, to a determinant state that is devoted to specialized organ development (i.e. differentiation). For <i>Arabidopsis</i> and other **angiosperms** floral development begins with the reorganization or transformation of <span id="Dred">SAM</span> into **inflorescence meristems** (<span id="Blue">IFM</span>). Although <span id="Blue">IFM</span> retains its vegetative potential it can also produce determinate **floral meristems** (<span id="SkyB">FM</span>) that generate flowers (i.e. whorls of **sepals**, **petals**, **stamens** and **carpels**). The **AGAMOUS** gene (<span id="Teal">AG</span>), which encodes for a **MADS** domain containing transcription factor, is a key regulator of floral organ identity since genetic lines of <i>Arabidopsis</i> harbouring mutant alleles of <span id="Teal">AG</span> (e.g. <span id="Teal"><i>ag</i></span>**-1**, <span id="Teal"><i>ag</i></span>**-2**, <span id="Teal"><i>ag</i></span>**-3**)**<sup>[32](#ref-bowman_genes_1989)–[34](#ref-bowman_genetic_1991)</sup>** generate a “<i>flower within a flower</i>” phenotype where the outer two flower whorls (i.e. **sepals** and **petals**) appear normal while the inner whorls (i.e. **stamens** and **carpels**) are replaced by petals (i.e. 4 normal petals + 6 extra petals) and a new flower. As **Saunders** (1921) noted over a century ago when describing the cultivar *Matthiola incana* (i.e. Stock flower, has the same mutant phenotype due to a mutated **MiAG** gene, the orthologue of <i>Arabidopsis</i> <span id="Teal">AG</span>),**<sup>[35](#ref-nakatsuka_molecular_2018)</sup>** this ornamental garden plant “<i>…is a full double…destitute of any semblance of either stamens or carpels</i>”.**<sup>[36](#ref-saunders_note_1921)</sup>** This mutant phenotype also repeats itself resulting in several nested flowers, what could be described as every florist’s dream. Molecular analysis of <span id="SkyB">FM</span> within the <span id="Teal"><i>ag</i></span> mutants (Note: genetic mutants are usually written in lower case to distinguish it from wild type) shows persistent expression of both <span id="Crim">WUS</span> and <span id="Or2">CLV</span>**3**, which largely explains why **floral determinacy** is <u>suppressed</u> within these floral organs. However, what is striking about <span id="Crim">WUS</span> is that it co-operates with the floral activator **LEAFY** (<span id="Gr2">LFY</span>) to directly activate <span id="Teal">AG</span>.**<sup>[11](#ref-schultz_leafy_1991),[37](#ref-lohmann_molecular_2001),[38](#ref-lenhard_termination_2001)</sup>** Elevated levels of <span id="Teal">AG</span> activates **KNUCKLES** (**KNU**), a transcriptional repressor protein that silences <span id="Crim">WUS</span> thereby preventing it from maintaining floral **stem cell** activity.**<sup>[39](#ref-sun_timing_2009)</sup>** This represents a second negative feedback loop involving <span id="Crim">WUS</span> and its regulation of **stem cells**.  
    Another equally important aspect of plant **stem cell** biology is the role the environment plays in the fate of these cells. The **stem cell** “<i>niche</i>” concept is well known among animal **stem cell** researchers,**<sup>[40](#ref-schofield_relationship_1978)</sup>** having emerged not long after the first **stem cells** (i.e. **haematopoietic stem cells**, or <span id="Dred">HSC</span>) were discovered by **Till** and **McCulloch** back in the early 1960s.**<sup>[41](#ref-till_direct_1961),[42](#ref-becker_cytological_1963)</sup>** Subsequent studies of **stem cell niches** clearly show that both neighbouring cells and the molecules they secrete (e.g. growth factors, protein that make up the extracellular matrix or **ECM**) create an unique micro-environment that maintains **stem cell** numbers.**<sup>[43](#ref-moore_stem_2006),[44](#ref-pennings_stem_2018)</sup>** Beyond the confines of this micro-environment **stem cells** usually commit to a specific differentiation program. For example tissue specific epidermal **stem cells** are responsible for constantly replacing old dead keratinocytes.**<sup>[45](#ref-watt_epidermal_1998),[46](#ref-gonzales_skin_2017)</sup>** They reside within the inner most (basal) layer of the skin where they are in constant contact with the basement membrane, a growth factor and **extracellular matrix** (**ECM**) rich layer. **Stem cells** bind to elements of the **ECM** (e.g. fibronectin, collagen) via **integrin** receptors. This in turn triggers specific intracellular signaling cascades that maintain the identity of epidermal **stem cells** (i.e. capacity to self-renew). In fact β<sub>1</sub>-**integrin** is considered a marker of epidermal **stem cells**, and its reduced expression results in **stem cells** loosing contact with the basement membrane and being forced upwards where they differentiate into keratinocytes.**<sup>[47](#ref-adams_changes_1990)–[49](#ref-watt_expression_1993)</sup>**  
    So what types of **niche** signaling factors do flowering plants rely on to regulate **stem cell** activity within **meristems**? It’s well known that phyto-hormones like **auxin** and **cytokinin** (<span id="Coral">CK</span>) control shoot and root development.**<sup>[50](#ref-vernoux_auxin_2010),[51](#ref-kieber_cytokinin_2018)</sup>** For example, <i>Arabidopsis</i> strains containing loss-of-function mutations within all three known <span id="Coral">CK</span> receptors (i.e. <b><a class="one" href="https://www.uniprot.org/uniprotkb/Q9C5U2/entry" target="_blank" title="Go to UniProt">AHK2</a></b>, <b><a class="one" href="https://www.uniprot.org/uniprotkb/Q9C5U1/entry" target="_blank" title="Go to UniProt">AHK3</a></b>, and <b><a class="one" href="https://www.uniprot.org/uniprotkb/Q9C5U0/entry" target="_blank" title="Go to UniProt">AHK4</a></b>) show severe developmental abnormalities, including significantly reduced <span id="Dred">SAM</span> size and activity.**<sup>[52](#ref-higuchi_planta_2004),[53](#ref-nishimura_histidine_2004)</sup>** It’s therefore not surprising that <span id="Coral">CK</span> signaling is also an integral part of the <span id="Crim">WUS</span>/<span id="Or2">CLV</span>**3** signaling network within **stem cells**. Cross-talk between <span id="Crim">WUS</span>/<span id="Or2">CLV</span>**3** and <span id="Coral">CK</span> provides additional levels of control over <span id="Crim">WUS</span> protein levels and transcriptional activity (**Fig. 2**).**<sup>[14](#ref-daum_mechanistic_2014),[18](#ref-zhou_hairy_2018),[54](#ref-leibfried_wuschel_2005)–[61](#ref-plong_clavata3_2021)</sup>** Multiple signal inputs likely require fine-tuned nested threshold responses (e.g. negative feedback loops) given the spatial-temporal nature of cellular differentiation and organ development (e.g. proper inflorescence structure).

<a id="Fig2"></a>
<!--------------------------------------------------------->
<!------------ FIG 2 - SAM Signalling Network ------------->
<!--------------------------------------------------------->

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/SAM_Signaling_Network2.jpg" alt="" width="800px"/>

</figure>

**Figure 2. Plant Stem Cell Signalling Network**. **WUSCHEL**, or simply <span id="Dred">WUS</span>, is one of the most important transcription factors that regulates **stem cells** activity in **meristems**.**<sup>[4](#ref-laux_wuschel_1996)–[6](#ref-schoof_stem_2000),[12](#ref-brand_dependence_2000)</sup>** Unlike the ordered vegetative-to-floral transition seen in wild-type plants (**Fig. 1**) mutant <span id="Dred">WUS</span> plants (<span id="Dred"><i>wus</i></span>) display a discontinuous or “<i>stop-and-go</i>” type of secondary shoot development. **Meristems** emerge from the axils of leaves (i.e. loss of apical dominance) often producing bunches of cauline leaves.**<sup>[4](#ref-laux_wuschel_1996)</sup>** Floral organ development is rare and the few mutant flowers that do emerge lack **carpels** and most **stamens** (Note: on average one central **stamen** develops, as well as a normal complement of outer **sepals** and **petals**). These developmental defects highlight the importance of <span id="Dred">WUS</span> to <span id="Dred">SAM</span> (e.g. loss of **stem cell** maintenance). <span id="Dred">WUS</span> protein has been shown to diffuse out of <span id="Dred">OC</span> cells via **plasmodesmata** (<b>⑥</b>).**<sup>[13](#ref-yadav_wuschel_2011),[14](#ref-daum_mechanistic_2014)</sup>** Upon reaching the upper **stem cell** compartment it activates **CLAVATA-3** (<span id="Or2">CLV</span>**3**) expression (<b>①</b>), which is required to maintain **stem cell** identity (i.e. **stem cell** marker).**<sup>[13](#ref-yadav_wuschel_2011),[57](#ref-perales_threshold-dependent_2016)</sup>** Although the mechanism(s) responsible for confining <span id="Dred">WUS</span> gene expression to the <span id="Dred">OC</span> is not fully understood, both **Hairy Meristem** genes (<span id="Purple">HAM</span>**-1**, **2** and **3**) and <span id="Or2">CLV</span>**3** appear to play important roles in this process.**<sup>[17](#ref-zhou_control_2015),[18](#ref-zhou_hairy_2018),[62](#ref-stuurman_shoot_2002),[63](#ref-engstrom_arabidopsis_2011)</sup>** <span id="Purple">HAM</span>-1 and <span id="Purple">HAM</span>-2 are highly expressed within the <span id="Dred">RM</span> (<b>⑦</b>), which overlaps with <span id="Dred">WUS</span>, and largely absent within **L1** and **L2** (<b>②</b>). By contrast <span id="Or2">CLV</span>**3** expression is largely restricted to **L1** and **L2** within the <span id="Dred">CZ</span>.**<sup>[17](#ref-zhou_control_2015),[18](#ref-zhou_hairy_2018)</sup>** <span id="Purple">HAM</span> has also been shown to bind to <span id="Dred">WUS</span> and inhibit <span id="Or2">CLV</span>**3** expression (<b>⑦</b>).**<sup>[17](#ref-zhou_control_2015),[18](#ref-zhou_hairy_2018)</sup>** The <u>inability</u> of <span id="Dred">WUS</span>:<span id="Purple">HAM</span> hetero-dimers to activate <span id="Or2">CLV</span>**3** expression is a property shared by <span id="Dred">WUS</span> homo-dimers (<span id="Dred">WUS</span>:<span id="Dred">WUS</span>, <b>⑦</b>).**<sup>[57](#ref-perales_threshold-dependent_2016)</sup>** Based on these findings alone it would appear that changes in the protein levels of <span id="Dred">WUS</span> and/or <span id="Purple">HAM</span> strictly control <span id="Or2">CLV</span>**3** transcription within the apical **mersitem**.**<sup>[18](#ref-zhou_hairy_2018),[57](#ref-perales_threshold-dependent_2016),[60](#ref-han_signal_2020)</sup>** However there are post-translational mechanisms that also control <span id="Dred">WUS</span> activity. For example, the unique C-terminal **WUSCHEL-box** appears to govern nuclear retention of the protein, while an **EAR-like** domain controls its nuclear export.**<sup>[14](#ref-daum_mechanistic_2014),[55](#ref-kieffer_analysis_2006),[58](#ref-rodriguez_dna-dependent_2016),[61](#ref-plong_clavata3_2021)</sup>** Regulating <span id="Dred">WUS</span> protein movements using these additional signal inputs likely has a significant affect on its transcriptional activity (i.e. active monomer or inactive homo-dimer).**<sup>[14](#ref-daum_mechanistic_2014),[58](#ref-rodriguez_dna-dependent_2016)</sup>** Less is known about how <span id="Or2">CLV</span>**3** negatively regulates <span id="Dred">WUS</span> expression and transcriptional activity. <span id="Or2">CLV</span>**3** is known to undergo extensive post-translational modifications (e.g. proteolysis <b>②</b>, and the addition of arabinose groups)**<sup>[64](#ref-ni_evidence_2006)–[68](#ref-hirakawa_clavata3_2021)</sup>** prior to being secreted into the extracellular space where it acts as a ligand (<b>③</b>) for several plasma membrane receptor-like protein complexes (Note: collectively symbolized here as <span id="Or2">CLV</span>**3-R**).**<sup>[15](#ref-fletcher_signaling_1999),[16](#ref-rojo_clv3_2002),[27](#ref-clark_clavata1_1997)–[31](#ref-shimizu_bam_2015)</sup>** <span id="Or2">CLV</span>**3** inhibition of <span id="Dred">WUS</span> expression appears to be linked to **cytokinin** (<span id="Coral">CK</span>) signaling. For example, plants carrying mutations within all three known <span id="Coral">CK</span> receptors (i.e. <b><a class="one" href="https://www.uniprot.org/uniprotkb/Q9C5U2/entry" target="_blank" title="Go to UniProt">AHK2</a></b>, <b><a class="one" href="https://www.uniprot.org/uniprotkb/Q9C5U1/entry" target="_blank" title="Go to UniProt">AHK3</a></b>, and <b><a class="one" href="https://www.uniprot.org/uniprotkb/Q9C5U0/entry" target="_blank" title="Go to UniProt">AHK4</a></b>) show severe developmental defects, including significantly reduced <span id="Dred">SAM</span> size and activity.**<sup>[52](#ref-higuchi_planta_2004),[53](#ref-nishimura_histidine_2004)</sup>** <span id="Coral">CK</span> signaling also induces <span id="Dred">WUS</span> expression via <span id="Coral">CLV</span>-dependent and <span id="Coral">CLV</span>-independent mechanisms.**<sup>[56](#ref-gordon_multiple_2009),[69](#ref-lindsay_cytokinin-induced_2006)</sup>** <span id="Dred">WUS</span> (<b>④</b>) can also repress the transcription of type A **Arabidopsis RESPONSE REGULATORS** (**A-ARRs**),**<sup>[54](#ref-leibfried_wuschel_2005)</sup>** and also be transcriptionally activated by type B **Arabidopsis RESPONSE REGULATORS** (**B-ARRs**).**<sup>[59](#ref-wang_cytokinin_2017),[70](#ref-meng_type-b_2017)</sup>** These two different regulators (<b>⑤</b>) perform opposite functions within the <span id="Coral">CK</span> two-component <span id="Red">Ⓟ</span>-relay signaling system. When **B-ARRs** is phosphorylated via the **H**istidine <span id="Red">P</span>hosphotransfer protein (**Arabidopsis HP**, or **AHP**), it transcriptionally activates <span id="Coral">CK</span>-inducible target genes, whereas phosphorylated **A-ARRs** function as negative regulators of **B-ARRs** (i.e. a negative feedback loop).**<sup>[71](#ref-hwang_two-component_2001),[72](#ref-hwang_two-component_2002)</sup>** Recent crystal structural analysis of **B-ARRs** suggests that <span id="Coral">CK</span> induced phosphorylation of its N-terminal receiver domain opens up an otherwise closed protein confirmation that promotes DNA binding and transcriptional activity.**<sup>[73](#ref-zhou_structure_2024)</sup>** However, since **A-ARRs** lack a DNA binding domain it’s currently unclear why its phosphorylation is so critical to its inhibitory function (Note: plants expressing a constitutively activated form of **A-ARR7** that has its phospho-acceptor **Asp** residue mutated have <span id="Dred">SAM</span> defects similar to that of <span id="Dred">WUS</span> mutants).**<sup>[54](#ref-leibfried_wuschel_2005)</sup>** Some suggest that phosphorylated **A-ARRs** may actively bind to and inhibit the function of **B-ARRs**.**<sup>[74](#ref-kim_phosphorylation_2008)</sup>** It’s also possible that some other post-translational mechanism, like **sumoylation** (i.e. alters protein stability), may be operating to alter the protein stability of **A-ARRs** (<b>⑤</b>).**<sup>[75](#ref-kim_scfkmd_2013),[76](#ref-kurepa_cytokinin_2014)</sup>** More recent studies also show that <span id="Coral">CK</span> can stabilize <span id="Dred">WUS</span> monomeric levels by somehow regulating a **degron** signal (i.e. sequence recognized by the ubiquitin-proteasome system) buried within the **WOX-box** domain (<b>⑥</b>).**<sup>[58](#ref-rodriguez_dna-dependent_2016),[77](#ref-snipes_cytokinin_2018)</sup>**

</div>

<!-------------------------------------------------------->
<!-------- END - FIG 2 - SAM Signalling Network  --------->
<!-------------------------------------------------------->

<a id="FAnat"></a>
**<span style="border: 2px solid black;">  3. FLOWER ANATOMY  </span>** Besides their size (e.g. trees) and the bounty they produce, most plants are admired for the beauty of their flowers. However for biologists it’s also a structure devoted to sexual reproduction that showcases some of **Darwin’s** and **Wallace’s** fundamental <b><a class="one" href="https://evolution.berkeley.edu/evolution-101/an-introduction-to-evolution/" target="_blank" title="Go to Evolution101">evolutionary</a></b> principles. **Darwin** knew full well the power of plants, specifically as the living embodiment of <b><a class="one" href="https://evolution.berkeley.edu/evolution-101/mechanisms-the-processes-of-evolution/" target="_blank" title="Go to Evolution101">evolutionary</a></b> forces that select desirable traits (i.e. reproductive success of plants). Although **Darwin** is better known for his Galapagos finches, he also amassed a large collection of pant specimens (\>1,400) during his voyage aboard the HMS Beagle (1831-1836). He also spent a considerable amount of time reflecting on the significance of plant organ development. For example, based on the work of botanists like **Francois Marius Barneoud**,**<sup>[78](#ref-barneoud_note_1846)</sup>** **Darwin** noted that different (i.e. heterogeneous) structures, like petals and sepals, actually arise from very similar looking (i.e. homogeneous) primordial outgrowths (e.g. leaf primordia, **Fig. 1**) that we now know are a product of <span id="Dred">SAM</span>.**<sup>[79](#ref-friedman_charles_2011)</sup>** Viewing evolution through the lens of developmental biology became a powerful explanatory tool for **Darwin** and his supporters. However, perhaps his most powerful argument was likening **natural selection** to **artificial selection**, otherwise known as selective breeding. The latter of course involves breeding only animals and plants with desirable traits, such as pigeons with showy plumage or plants with large beautiful flowers. However, wild plants can only use resources that are available to them within their natural environments. As a result individuals that do survive and go on to reproduce will pass on their traits to the next generation. The genetic makeup of these traits is ultimately what is being selected for over time. Invariably this is a slow “<i>mechanical</i>” process whereby individuals carrying suitable traits (e.g. confer increase mating success) increase in number, ultimately resulting in a shift in the genetic makeup (i.e. increased frequency of favoured <b><a class="one" href="https://www.jax.org/news-and-insights/minute-to-understanding/what-is-an-allele" target="_blank" title="Go to JAX.org">alleles</a></b>) of the population (i.e. evolution). Today we refer to this generation-to-generation change in the genetic structure (i.e. frequency of **alleles**) of a population as <b><a class="one" href="https://evolution.berkeley.edu/evolution-at-different-scales-micro-to-macro/what-is-microevolution/" target="_blank" title="Go to Evolution101">micro-evolution</a></b>. For flowering plants their evolutionary success, as evidenced by their enormous biodiversity, is obviously linked to their reproductive success (i.e. flowers and mating strategies).  
    One advantage that plants have over animals is its modular <u>indeterminate</u> growth pattern. This concept was touched upon earlier when describing plant **stem cell** gene networks and refers to the fact that **meristems** can either produce a specific or <u>determinate</u> body part like a flower (i.e. **floral meristem**) or remain in a <u>vegetative</u> or **indeterminate** state (i.e. **inflorescence** or **apical meristem**). The latter can produce body parts that vary in size and shape, often in response to different environmental conditions. So <u>indeterminate</u> growth can be viewed as a type of **developmental plasticity** that allows individuals of the same species to alter their appearance (e.g. smaller flowers) in response to changing environmental conditions (e.g. climate change). These differences in observable traits (i.e. <b><a class="one" href="https://www.genome.gov/genetics-glossary/Phenotype" target="_blank" title="Go to NIH">phenotypes</a></b>) are largely due to changes in their genetic makeup, which can give rise to genetically distinct populations (i.e. **ecotypes**).**<sup>[7](#ref-turesson_species_1922),[80](#ref-lowry_ecotypes_2012)</sup>** This term, which was coined by the Swedish botanist **Göte Turesson** (1922), was meant to represent an “<i>…ecological unit</i>” that is a product of its “<i>genotypical response….to a particular habitat</i>”.**<sup>[7](#ref-turesson_species_1922)</sup>** As to whether or not **ecotypes** are a “<i>…nonrandom partitioning of genetic variation along the continuum of species formation</i>”**<sup>[80](#ref-lowry_ecotypes_2012)</sup>** is currently open to debate.  
    Flowers are by definition <u>determinate</u> shoot structures that are devoted to the production of **pollen** (♂) and **ovules** (♀) via distinct structures (i.e. <u>heterosporangiate</u>). Specifically each **stamen** (i.e. collectively known as the **androecium**) is made up of a relatively long thin **filament** and an **anther** (bearing **pollen**), whereas each **carpel** (i.e. collectively known as the **gynoecium**) contains a **style**, **stigma** and **ovary** (**Fig. 3**). **Carpels** (i.e. “<i>vessels</i>”) are considered modified leaves, each enclosing one or more **ovules** (i.e. produce seeds when fertilized). All of the main parts of a flower (i.e. **carpels**, **stamens**, **petals** and **sepals**) are arranged around its central axis in a sequential manner (i.e. **whorls**).**<sup>[81](#ref-evert_raven_2013)</sup>** This includes, moving radially outwards from the centre, the **carpels** (i.e. often fused together as one large **pistil**), **stamens**, **petals** (i.e. collectively referred to as the **corolla**) and outer **sepals** (i.e. collectively referred to as the **calyx**). The majority of **angiosperms** possess both **carpels** (♀) and **stamens** (♂), so called **perfect** or **bisexual** flowers.**<sup>[82](#ref-renner_relative_2014)</sup>** In contrast, **imperfect** or **uni-sexual** flowers lack either **stamens** (i.e. **carpellate** or **pistillate** flowers) or **carpels** (i.e. **staminate** flowers). Although many **angiosperms** have **uni-sex** flowers (i.e. **monoecious** or **dioecious**, where **staminate** and **carpellate** flowers are found on either the same plant or different plants, respectively) they constitute the minority of flowering plants.**<sup>[82](#ref-renner_relative_2014),[83](#ref-renner_dioecy_1995)</sup>**  
    The flexible nature of **angiosperm** sexual systems has long fascinated evolutionary biologists. For example, since most **angiosperms** have **hermaphroditic** flowers they are more susceptible to the deleterious affects of self-fertilization, namely inbreeding (i.e. loss of <b><a class="one" href="https://www.dnaftb.org/4/animation.html" target="_blank" title="Go to NIH">heterozygosity</a></b>).**<sup>[84](#ref-carr_recent_2003)</sup>** This increases the expression of deleterious recessive mutations (i.e. recall <b><a class="one" href="https://www.dnaftb.org/3/bio.html" target="_blank" title="Go to CSH">Mendelian</a></b> genetics and the famous <b><a class="one" href="https://www.dnaftb.org/5/animation.html" target="_blank" title="Go to CSH">Punnett</a></b> square)**<sup>[85](#ref-bateson_mendels_1902),[86](#ref-edwards_reginald_2012)</sup>** that could compromise the reproductive success (i.e. fitness) of a species, as well as increase its susceptibility to extinction.**<sup>[87](#ref-newman_increased_1997)</sup>** The latter is particularly disconcerting when rare and endangered species are subjected to habitat loss, reduced access to pollinating species, and climate change. Although **dioecious** species benefit from an out-crossing advantage (i.e. self-fertilization suppressed) they too may be susceptible to climate change since some display spatial segregation of sexes (i.e. sexes prefer different micro-habitats, and consequently adopt new physiological and morphological specializations).**<sup>[88](#ref-bierzychudek_spatial_1988),[89](#ref-hultine_climate_2016)</sup>** Nevertheless, **hermaphroditic** plants do have a survival advantage over **uni-sex** plants under some circumstances (e.g. pollination assurance when geographically isolated).**<sup>[84](#ref-carr_recent_2003)</sup>** **Hermaphroditic** species are also known to develop quite complex self-incompatibility mechanisms to prevent self-fertilization,**<sup>[90](#ref-hiscock_different_2003)</sup>** whereas a small minority have adopted mixed mating systems (i.e. **Gynodioecy** - the co-existence of female and hermaphrodite plants, or the much rarer **Androdioecy** - coexistence of male and hermaphrodite plants).**<sup>[82](#ref-renner_relative_2014),[83](#ref-renner_dioecy_1995)</sup>** Although this latter strategy seems like a reasonable compromise it does not exclude these species from the perils of inbreeding depression.

<a id="Fig3"></a>
<!-------------------------------------------------->
<!------------ FIG 3 - FLOWER Anatomy  ------------->
<!-------------------------------------------------->

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/Plant_Flower_Structures.jpg" alt="" width="800px"/>

</figure>

**Figure 3. Flower Structures**. Flower structures can be rather complex, but they all contain basically two types of components, namely: (i) reproductive or fertile structures (i.e. **stamens** and **carpels**) and (ii) non-reproductive or infertile appendages (e.g. **sepals**, **petals**). From these two basic types of structures a tremendous variety of flower types can be created. For example, a large number of different flowers within the family <i>Asteraceae</i> can produce both **disc florets** and **ray florets** (i.e. generally known as **composite** flowers). The central **disc florets** are relatively small and clustered together to form a head, while the outer halo-like **ray florets** are generally either strap-like or petal-like in shape. Two examples of this specialized flower type are shown above, namely the flower head of **Prairie dock** (<i>Silphium terebinthinaceum</i>, <b>①</b>) and the flower head of **Tall Prairie blazing star** (<i>Liatris aspera</i>, <b>②</b>). The **disc florets** of <i>S. terebinthinaceum</i> are **staminate** (♂) and produce only pollen, while the outer **ray florets** (♀) produce seeds in the form **achenes** (i.e. dry, flat, closed or **indehiscent** fruits). This is quite contrary to what most of us assume about sunflowers, like the well known giant sunflower. The latter flowers produce edible seeds via perfect **disc florets** (♂ and ♀ parts), while the outer **ray florets** are **imperfect** and sterile. In contrast, the large pink button-like flower heads of <i>L. aspera</i>, another type of **Aster**, does not produce **ray florets**. Each of the **disc florets** are petal-like in appearance (i.e. tubular corolla) with five distinct spreading lobes that produce a star shaped pattern. They also have a series of scale-like **bracts** at the base of the flower head that are green and usually tinged with purple (Note: edges or margins of these **bracts** are uneven or rough looking, hence its other common name **Rough blazing star**). Emerging from the centre of each **floret** is a relatively long divided **style** (♀), which gives the **inflorescence** a fuzzy, brush-like appearance. Similar to <i>S. terebinthinaceum</i> the flowers of <i>L. aspera</i> produces dry hairy fruits (i.e. **achenes**) that are dispersed via the wind. Flowers that are not **Asters**, like <i>Agalinis purpurea</i> (**Large purple foxglove**, <b>③</b>), have a more familiar structure. Each tube shaped flower is attached to a small **petiole** and has a 5 lobed pinkish-purple **corolla**. Cupping the base of the flower is a tube shaped **calyx**, which has five pointed triangular lobes. The interior of the **corolla** has the familiar **anther** tipped **stamens** (♂), a single blunt tipped **style** (♀), and colourful markings (i.e. pale yellow stripes, which serve as nectar guides, and dark purple spots). Another common type of flower, that most of us perhaps overlook, is that of **grasses** (<b>④</b>). Known as a **spikelet**, it has the following relatively simple general structure: (i) a **pistil** (♀) consisting of an **ovary** (houses a single **ovule**); (ii) two **styles** (♀), each supporting a feathery **stigma** (♀) with ample surface area for capturing pollen grains; (iii) multiple **stamens** (♂), each consisting of a long wiry **filament** and a terminal **anther** (♂); (iv) no showy petals or sepals; (v) two outer **bracts** known as **glumes**, with the first one usually displaying long hairs (<b>☆</b>); (vi) two inner **bracts** surrounding the grass **floret**, with the one called the **lemma** often anchoring a long appendage called an **awn** (†); (vii) a **palea**, or second inner **bract**; and (viii) the **caryopsis**, or seed **grain**, which is a type of dry fruit. Together the **lemma**, **palea** and inner grain make up a fertile grass **floret**. For example, the **spikelet** of **Indiangrass**, *Sorghastrum nutans* (<b>⑤</b>), has a golden brown to chestnut coloured outer **glume** (‡) that is narrow, pointed and displays some long hairs (<b>☆</b>). A long wiry bent **awn** (†) can be seen emerging from one of the **spikelets**. The white feathery **styles** (♀) and long yellow **stamens** (♂) are also clearly visible (Note: the upper diagram of the grass **spikelet** is meant for illustrative purposes. Its components are not normally spread out in this type of neatly nested manner).

</div>

<!------------------------------------------------>
<!-------- END - FIG 3 - FLOWER Anatomy  --------->
<!------------------------------------------------>

<a id="IF"></a>
**<span style="border: 2px solid black;">  4. INFLORESCENCE STRUCTURE  </span>** This **Linnaean** term refers to the arrangement of flowers on a plant, including the position of the flower heads (i.e. open or closed “<i>canopy</i>”) and the shape of the branches that bear them (i.e. “<i>scaffold</i>” that bears the flowers).**<sup>[91](#ref-tucker_inflorescence_1999)</sup>** The modular nature of plant growth and the architecture it produces is largely thanks to apical **meristems** since they ultimately produce the lateral outgrowths (i.e. **promordia**) that become either new leaves or flowers (e.g. **leaf promordia**, **Fig. 1**). The succession of lateral **primordia** produced by **meristems** gradually move away from each other due to cell growth within the intervening spaces resulting in stem elongation. The new stem segments are known as **inter-nodes**, and the sites that connect successive **inter-nodes** are the **nodes** (i.e. potential sites of leaf, flower, bud or shoot development). Collectively these structures (i.e. **inter-node**, **node** and any attached organs) constitute a **metamer** or **phytomer** (i.e. basic structural unit of a stem).**<sup>[81](#ref-evert_raven_2013)</sup>** During a plant’s vegetative phase both **apical** and **axillary meristems** (<span id="Rust">AxM</span>, located within the leaf **axil**) produce new **phytomers** to either elongate the main stem or secondary axes (i.e. **phytomers** addition to secondary shoots), respectively. **Secondary meristems** located within the vascular cambium also make new additions to the plant (i.e increase its girth) but they are not involved in the production of new stems or branches. Eventually environmental signals like temperature or **photo-period** (<span id="strokeB">P</span><span id="strokeW">P</span>)**<sup>[92](#ref-poethig_phase_2003)</sup>** induce plant flowering. It’s also important to note that the succession of **leaf primordia** (**Fig. 1**) generated by the apical **meristem** take up well defined radial positions along the stem. This process (i.e. **phyllotaxy**) ultimately results in the leaves being arranged in regular patterns around the stem (e.g. spirally = 137.5° of separation or **Fibonacci** angle; alternately = 180° of separation).**<sup>[93](#ref-fleming_formation_2005),[94](#ref-palauqui_phyllotaxis_2011)</sup>** Since **axillary meristems** are located within the **axil** of each leaf it therefore follows that **phyllotaxy** greatly influences branching patterns (i.e. **inflorescence** development). **Phytomers** also show considerable structural variations (i.e. **heteroblasty**).**<sup>[95](#ref-zotz_heteroblastyreview_2011),[96](#ref-diggle_modularity_2014)</sup>** For example, the size of leaves or the length of the **corolla** (**Fig. 4**, **raceme** of *Lupinus perennis*) can change as you move up the stem. Nevertheless, despite the pervasive nature of **heteroblasty** many closely related species often display the same type of **inflorescence** (e.g. **milkweed** and **umbels**).  
    One of the major classification criteria of an **inflorescence** is the presence or <u>absence</u> of a flower at the shoot apex. When the flower is present it is referred to as a closed or <u>determinate</u> **inflorescence**, and when it is absent it is called an open or <u>indeterminate</u> **inflorescence**. For example, in **racemose** type plants like *Arabidopsis* (**Fig. 4**) the <span id="Dred">SAM</span> can remain in a vegetative (indeterminate) state and continue to add new **phytomers** to the main stem axis. However, as *Arabidopsis* matures and <span id="Dred">SAM</span> enters its reproductive phase dormant <span id="Rust">AxM</span> become activated (i.e. regain **meristem** potential) and generate new secondary shoots. However, if the **apical meristem** is not fully differentiated (e.g. form an **apical** or **terminal bud**) it can still exert its dominance over secondary **meristems** depending upon developmental or environmental conditions. In fact the ability of buds to cycle between a dormant and an active state is vital to both normal development (i.e. protects against uncontrolled growth) and the survival of plants (e.g. damage to apical region caused by browsing herbivores).**<sup>[97](#ref-shimizu-sato_control_2001)–[99](#ref-choa_current_2007)</sup>**  
    Another important criteria is the branching pattern of the **inflorescence**.**<sup>[81](#ref-evert_raven_2013),[100](#ref-endress_disentangling_2010)</sup>** There appears to be two main alternate **inflorescence** patterns within flowering plants, namely **racemose** and **cymose** (**Fig. 4**). The former is the simplest with only a single main stem (i.e. primary or 1<sup>st</sup> order axis) and a variable number of lateral branches (i.e. secondary or 2<sup>nd</sup> order axes). Although the branching order is fixed (i.e. no more than two) several variations on the **racemose** theme are possible, namely: (i) a simple **spike** configuration has a long primary axis and short or absent secondary axes (i.e. **stachyum** = open, **stachyoid** = closed); (ii) in a **raceme** both primary and secondary axes are relatively long (i.e. **botryum** = open, **botryoid** = closed); (iii) in an **umbel** the primary axis is short within the branching region while the secondary axes are relatively longer (i.e. **sciadium** = open, **sciadioid** = closed); (iv) in a **head** both primary and secondary axes are short within the branching region (i.e. **capitulum** or **cephalium** = open, **cephalioid** = closed); and (v) **compound racemes** can arise when secondary axes are replaced by one or more **racemose** subunits (e.g. double raceme or **diplobotryum**).**<sup>[81](#ref-evert_raven_2013),[100](#ref-endress_disentangling_2010)</sup>** In contrast a **cymose** pattern is characterized by a primary axis having a maximum of two secondary axes or branches. However these branches can undergo higher order branching (i.e. not limited). If all the secondary axes have a pair of lateral branches (e.g. tertiary axes) it is **dichasium**, whereas if all axes have only one lateral branch then it is **monochasium** (**Fig. 4**). Also a compound **cyme** having both **dichasial** and **monochasial** subunits usually begins **dichasial** and ends **monochasial** (<span id="SkyB">D</span> → <span id="Blue">M</span>, **Fig. 4**). Another type of compound **inflorescence** called a **thyrse** (open) or **thyroid** (closed) has both **racemose** (primary branching) and **cymose** (secondary branching) subunits. Lastly, there is also a third type of **inflorescence** called a **panicle**. Even though **panicles** are fairly common, albeit less so among temperate **angiosperms**,**<sup>[101](#ref-prusinkiewicz_evolution_2007)</sup>** botanists consider them to be a special case since they have characteristics that strictly exclude them from being classified as either **cymose** and **racemose**. For example, unlike a **cymose** a **panicle** has more than 2 lateral branches of the next higher order, and unlike a **racemose** a **panicle** has branches with more than 2 branching orders (i.e. no limits on branching orders). In addition, each branch terminates in a flower and the branching order usually becomes progressively smaller towards the top of the plant (**Fig. 4**).**<sup>[100](#ref-endress_disentangling_2010)</sup>**

<a id="Fig4"></a>
<!------------------------------------------------------------>
<!------------ FIG 4 - INFLORESCENCE Structures  ------------->
<!------------------------------------------------------------>

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/Inflorescence_Architecture.jpg" alt="" width="800px"/>

</figure>

**Figure 4. Inflorescence Structures**. The reproductive success of flowering plants depends in large part on the shape and size of its **inflorescence**. Branching patterns and the extent of a plant’s floral display all have obvious functional consequences with respect to reproductive success. Specifically branches deliver nutrients to flowers and also provides physically support so that they can attract potential pollinators. Promoting flower-pollinator interactions in this way ultimately impacts the flow of genetic information between plants within a population (i.e. evolutionary potential). For example **panicles** are more prevalent among tropical plants and are considered an ideal **inflorescence** for wind and insect pollination.**<sup>[101](#ref-prusinkiewicz_evolution_2007),[102](#ref-harder_interplay_2013)</sup>** Tropical habitats have an abundance of pollinators and are less constrained by **abiotic** factors (e.g. temperature, sunlight, precipitation). For these reasons tropical plants can extend their vegetative growth phase to produce a profusion of branches and flowers. However tropical environments are home to large populations of herbivores, which means that plants must also devote a substantial amount of energy to secondary metabolite production as a means of chemical defence (e.g. toxic latex production). By contrast **angiosperms** in more northern latitudes are subject to less favourable growth and reproductive conditions (i.e. seasonal growth, less precipitation and sunlight, limited access to pollinators). Thus the timing and extent of vegetative and reproductive growth phases have to be carefully regulated in order to ensure reproductive success. This may explain why plants in temperate habitats generally have more modest branching patterns (i.e. **racemose** or **cymose**).**<sup>[101](#ref-prusinkiewicz_evolution_2007),[102](#ref-harder_interplay_2013)</sup>**

</div>

<!----------------------------------------------->
<!-------- END - FIG 4 - INFLORESCENCE  --------->
<!----------------------------------------------->

<a id="IFG"></a>
**<span style="border: 2px solid black;">  4.1 INFLORESCENCE GENE REGULATION  </span>** Flower development is ultimately governed by genetic regulatory networks operating within **meristems** in response to changing environmental conditions (e.g. **photo-period**, <span id="strokeB">P</span><span id="strokeW">P</span>). For example in the model plant species *Arabidopsis thaliana* the <u>indeterminate</u> (vegetative) apical **meristems** generate short vertical **phytomers** (inter-nodes) and lateral organ **primordia** that develop into spirally arranged stem leaves. However as the plant transitions into the reproductive phase of its life cycle the apical **meristems** also undergo a transition or re-organization resulting in a new type of **inflorescence meristem** (<span id="Blue">IFM</span>). The <span id="Blue">IFM</span> produces long **phytomers** and small spiralling stem leaves. It also produces spirally arranged **floral meristems** (<span id="SkyB">FM</span>) as lateral organs instead of leaf **primordia**. These specialized **meristems** provide all of the cells needed to form a flower, which (as mentioned previously) is composed of concentric arrangements (i.e. **whorls**) of four distinct organs namely outer **sepals**, **petals**, **stamens** (♂) and central **carpels** (♀). In the early 1990s an elegant **ABC** model was proposed that specified three distinct (i.e. **A**, **B** and **C**) floral functions carried out by different classes of <b><a class="one" href="https://www.ibiology.org/development-and-stem-cells/homeotic-genes/" target="_blank" title="Go to iBIOLOGY">homeotic</a></b> genes (**Fig. 8**).**<sup>[103](#ref-coen_war_1991),[104](#ref-weigel_abcs_1994)</sup>** These three functions overlap with one another since each one controls the fate of two adjacent **whorls** resulting in unique combinations of floral **homeotic** genes. This model emerged from the study of different mutant lines of *Arabidopsis* that harbour genetic mutations within a specific floral <b><a class="one" href="https://www.ibiology.org/development-and-stem-cells/homeotic-genes/" target="_blank" title="Go to iBIOLOGY">homeotic</a></b> gene. Some of the more notable genes include **LEAFY** (<span id="Gr2">LFY</span>), **APETALA1** (<span id="Moss">AP</span>**1**) and **TERMINAL FLOWER1** (<span id="Magenta">TFL</span>**1**). Given their importance to **inflorescence** development a brief discussion of them is provided below. As always this discussion will only serve as a primer of the numerous flower developmental studies carried out over the last few decades.

<a id="Fig5"></a>
<!---------------------------------------------------->
<!------------ FIG 5 - Arabidopsis Mutants  ---------->
<!---------------------------------------------------->

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/Arabidopsis_Mutants.jpg" alt="" width="800px"/>

</figure>

**Figure 5. Arabidopsis Flowering Mutants**. *Arabidopsis thaliana* is a small annual *cruciferous* plant that has a number of convenient traits which makes it ideal for genetic study, including: (i) its small size and ease of growth; (ii) its self-fertilizing and has a short generation time (~6 weeks); (iii) flowering is synchronized and yields a large number of seed pods or **siliques** per plant (~10,000 seeds per plant); (iv) seeds are long lived and highly viable making them ideal for mutagenesis screens; (v) it has a relatively small genome (2*n* = 10 chromosomes); and (vi) there are a variety of available **ecotypes** (i.e. trait variations among wild type lines).**<sup>[9](#ref-fink_anatomy_1998),[10](#ref-kramer_planting_2015),[105](#ref-redei_supervital_1962),[106](#ref-shindo_natural_2007)</sup>** Over the years genetic screens of *Arabidopsis* have identified several important mutants with very distinct floral defects. Three of the more notable ones are illustrated above namely: (i) **LEAFY** (<span id="Gr2"><i>lfy</i></span>) - these mutant lines produce abnormal but fertile **carpeloid** like flower structures that lack **petals** and **stamens**. Most of flowers that should appear are instead replaced by indeterminate **co-inflorescence** like branches that bear **cauline** leaves;**<sup>[11](#ref-schultz_leafy_1991),[107](#ref-huala_leafy_1992),[108](#ref-weigel_leafy_1992)</sup>** (ii) **APETALA 1** (<span id="Moss"><i>ap</i></span>**1**) - these mutants produce flowers that have no **petals** (2<sup>nd</sup> flower **whorl**) or in some instances very rudimentary **petaloid** like flower structures.**<sup>[109](#ref-irish_function_1990),[110](#ref-bowman_control_1993)</sup>** Moreover, secondary flower-like structures emerge from the axils of the first **whorl** within the primary flowers. This appears to be an iterative process since these secondary flower like structures can beget tertiary flowers (and so on).**<sup>[110](#ref-bowman_control_1993)</sup>** These <span id="Moss"><i>ap</i></span>**1** mutants also produce leafy bract-like structures instead of **sepals** (1<sup>st</sup> flower **whorl**); and (iii) **Terminal Flower 1** (<span id="Hpink"><i>tfl</i></span>**1**) - these mutant plants flower early (Note: number of leaves often used as a proxy for flowering time) and have a severely truncated **inflorescence**.**<sup>[111](#ref-shannon_mutation_1991),[112](#ref-alvarez_terminal_1992)</sup>** The normal indeterminate **inflorescence** seen in wild type plants is instead replaced by terminal floral **meristems** that bear few flowers. Occasionally no lateral branches are produced and, unlike wild type plants, the main stem produces a terminal floral structure (i.e. determinate).

</div>

<!---------------------------------------------------->
<!-------- END - FIG 5 - Arabidopsis Mutants --------->
<!---------------------------------------------------->

    <span id="Gr2">LEAFY</span> mutants (Note: mutants like <span id="Gr2"><i>lfy</i></span> are usual written in lower case, and the gene in upper case) generated using forward genetic screening techniques (i.e. EMS, irradiation, or transposon tagging),**<sup>[113](#ref-smyth_how_2023)</sup>** all share the same general phenotype (Note: phenotype severity varies among alleles, for example <span id="Gr2"><i>lfy</i></span>-6 \> <span id="Gr2"><i>lfy</i></span>-5), which is flowers being replaced by indeterminate axillary branches (**Fig. 5**).**<sup>[11](#ref-schultz_leafy_1991),[107](#ref-huala_leafy_1992),[108](#ref-weigel_leafy_1992),[114](#ref-shannon_genetic_1993)</sup>** Another notable feature of <span id="Gr2"><i>lfy</i></span> mutants is the presence of apical flowers that have varying degrees of floral identity. The presence of these determinate structures suggests that other genes must be operating along side wild type <span id="Gr2">LFY</span> to promote floral identity within **meristems**. This became more evident when researchers crossed different mutant lines to produced double mutants, such as <span id="Gr2"><i>lfy</i></span>/<span id="Moss"><i>ap</i></span>**1**, that generate stronger flower-to-inflorescence shoot phenotypes.**<sup>[107](#ref-huala_leafy_1992),[110](#ref-bowman_control_1993)</sup>** Clearly the activities of both wild type <span id="Gr2">LFY</span> and <span id="Moss">AP</span>**1** genes play important roles in regulating <span id="Rust">AxM</span> floral identity and/or specific floral organ development. Once <span id="Gr2">LFY</span> was cloned (1992) its RNA was shown to be strongly expressed within early floral **primordia** (i.e. lateral <span id="SkyB">FM</span> produced by <span id="Blue">IFM</span>)**<sup>[108](#ref-weigel_leafy_1992)</sup>** long before the expression of floral <b><a class="one" href="https://www.ibiology.org/development-and-stem-cells/homeotic-genes/" target="_blank" title="Go to iBIOLOGY">homeotic</a></b> genes <span id="BGr">AP</span>**3** and <span id="Teal">AG</span> (Note: as depicted in **Fig. 8** <span id="BGr">AP</span>**ETALA3** and <span id="Teal">AG</span>**AMOUS** are **MADS**-domain proteins required for either **B**-type **petal** and **stamen** development, or **C**-type **stamen** and **carpel** development respectively).**<sup>[33](#ref-yanofsky_protein_1990),[115](#ref-jack_homeotic_1992)</sup>** More detailed studies of <span id="Gr2">LFY</span> showed that it functions as a rather unique plant specific DNA binding transcriptional factor.**<sup>[116](#ref-maizel_floral_2005),[117](#ref-moyroud_leafy_2010)</sup>** Downstream genes targeted by <span id="Gr2">LFY</span> (activated or repressed) include among others transcriptional regulators that control either <span id="SkyB">FM</span> identity (i.e. <span id="Moss">AP</span>**1**, <span id="Teal2">CAL</span>)**<sup>[110](#ref-bowman_control_1993),[118](#ref-mandel_molecular_1992)–[124](#ref-pastore_late_2011)</sup>** or floral organ development (i.e. <span id="Teal">AG</span>, <span id="BGr">AP</span>**3**).**<sup>[37](#ref-lohmann_molecular_2001),[38](#ref-lenhard_termination_2001),[122](#ref-william_genomic_2004),[125](#ref-busch_activation_1999),[126](#ref-lamb_regulation_2002)</sup>** Its role as a master regulator of flower development is particularly evident within <span id="Gr2">LFY</span> transgenic plants.**<sup>[127](#ref-weigel_developmental_1995)</sup>** Constitutive expression of <span id="Gr2">LFY</span> using a well known plant cauliflower mosaic virus promoter <b><i>35S</i></b> resulted in truncated vegetative growth of the primary shoot and fewer basal rosette leaves (i.e. affects shoot **meristem**), while secondary shoot **meristems** and the terminus of the primary shoot are transformed into solitary flowers (i.e. determinate growth). Remarkably this so called “<i>precocious flowering</i>” phenotype could be replicated when the <b><i>35S</i>::</b><span id="Gr2">LFY</span> transgene is expressed within the perennial tree aspen. Normally only adult (\>8 years of age) aspens produce flowers (i.e. catkins from leaf axils), but constitutive expression of the transgene triggered a “<i>precocious flower</i>” like phenotype within regenerating 5 month old aspen shoots.**<sup>[127](#ref-weigel_developmental_1995)</sup>** In *Arabidopsis* when the <b><i>35S</i>::</b><span id="Gr2">LFY</span> transgene was expressed against a mutant <span id="Moss"><i>ap</i></span>**1** background the “<i>precocious flower</i>” phenotype was significantly suppressed. Solitary flowers that usually form in the leaf axils of transgenic plants instead developed into complex shoots (i.e. average of 10 nodes), suggesting that the activities of wild type <span id="Gr2">LFY</span> and <span id="Moss">AP</span>**1** are closely linked (i.e. dependent to some degree) when transforming <span id="Blue">IFM</span> into <span id="SkyB">FM</span>. It’s also important to note that the “<i>precocious flower</i>” phenotype seen in <b><i>35S</i>::</b><span id="Gr2">LFY</span> transgenic plants is reproduced by both <b><i>35S</i>::</b><span id="Moss">AP</span>**1** transgenic plants and <span id="Magenta"><i>tfl</i></span>**1** loss-of-function mutant plants.**<sup>[111](#ref-shannon_mutation_1991),[112](#ref-alvarez_terminal_1992),[121](#ref-liljegren_interactions_1999),[128](#ref-mandel_gene_1995)</sup>** Moreover, the co-operative nature of <span id="Gr2">LFY</span> and <span id="Moss">AP</span>**1** is further highlighted by the even more dramatic “<i>precocious flower</i>” phenotype seen within <b><i>35S</i>::</b><span id="Gr2">LFY</span>/<span id="Moss">AP</span>**1** double transgenic plants (i.e. all primary and secondary shoots are converted into flowers, and leaves are smaller and fewer in number).**<sup>[121](#ref-liljegren_interactions_1999)</sup>**

<a id="Fig6"></a>
<!-------------------------------------------------->
<!------------ FIG 6 - PP Signal Network  ---------->
<!-------------------------------------------------->

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/CircadR_Floral_Gene_Activation.jpg" alt="" width="800px"/>

</figure>

**Figure 6. Photo-Period & Flowering**. <span id="Gr2">Phyto</span>chromes (<span id="Gr2">PHY</span>) and <span id="SkyB">Crypto</span>chromes (<span id="SkyB">CRY</span>) are two major groups of **photoreceptors** found in a wide range of single and multi-cellular organisms. In higher plants they play important roles in various **photomorphogenic** responses (e.g. seed germination, photo-tropism, shade avoidance, leaf morphogenesis, chloroplast movement, and flowering transition).**<sup>[129](#ref-rockwell_phytochrome_2006)–[131](#ref-li_phytochrome_2011)</sup>** <span id="Gr2">PHY</span> usually form soluble dimers of **chromoprotein** subunits each harbouring a single thio-ester linked **<a class="one" href="https://iupac.qmul.ac.uk/tetrapyrrole/TP1.html" target="_blank" title="Go to IUPAC">tetrapyrrole</a>** **chromophore** (i.e. light harvesting molecule). Currently there are five distinct <span id="Gr2">PHY</span> in *Arabidopsis* (<span id="Gr2">PHY</span>**A**-**E**). The ability of the **chromophore** to sense changes in the quality or quantity of light is based on its ability to quickly switch between two relatively stable conformations, namely an inactive <span id="Red">P<sub>r</sub></span> (<span id="Red">red light</span> absorbing) and an active <span id="Rust">P<sub>fr</sub></span> (<span id="Rust">far red light</span> absorbing). Upon light irradiation the active cytosolic <span id="Rust">P<sub>fr</sub></span> moves into the nucleus either unassisted (i.e. <span id="Gr2">PHY</span>**B**) or with the aid of nuclear import proteins (i.e. <span id="Gr2">PHY</span>**A**), where it initiates rapid changes in gene expression.**<sup>[130](#ref-quail_phytochromes_2010)</sup>** The dynamics of this switching process dictates the relative levels of each conformer and thus serves as a rudimentary form of colour vision for photosynthetic plants. Switching to the active <span id="Rust">P<sub>fr</sub></span> conformer involves <span id="Red">red light</span> induced isomerization of the **<a class="one" href="https://iupac.qmul.ac.uk/tetrapyrrole/TP1.html" target="_blank" title="Go to IUPAC">tetrapyrrole</a>** **chromophore** about the **C15**-**C16** double bond (between **C** and **D** rings), as well as conformational changes within the **chromoprotein** backbone itself.**<sup>[129](#ref-rockwell_phytochrome_2006),[131](#ref-li_phytochrome_2011)</sup>** The relatively less stable active conformer can switch to the inactive conformer either via a slow non-photoinduced reaction (thermal reversion) or a much faster <span id="Rust">far red</span> induced reaction. The thermal reversion reaction likely involves a <span id="Rust">P<sub>fr</sub></span> resonance structure with a single-bond instead of a double bond between **C15** and **C16**. The presence of a single-bond instead of a double-bond would allow thermal rotation about this bond (Note: this proposed intermediate can be easily picture by simply shifting the **<a class="one" href="https://openbooks.lib.msu.edu/oclue/chapter/chapter-8-conjugated-compounds-and-aromaticity/" target="" title="Go to OCLUE">conjugated pi-bonds</a>** one carbon over beginning with the carbonyl group at C-19, which becomes protonated, and ending with C-6 which forms a double bond with the adjacent <span id="Gr2">N</span> atom). <span id="SkyB">CRY</span>, unlike <span id="Gr2">PHY</span>, employ **flavin adenine dinucleotide** (<span id="Magenta">FAD</span>) as the light harvesting **chromophore**. The gene encoding for the **chromoprotein** subunit is homologous to microbial <span id="Magenta">flavo</span>**enzymes** that catalyzes DNA-repair reactions in response to UV light (aka: DNA **photolyases**).**<sup>[132](#ref-ahmad_hy4_1993)–[134](#ref-lin_expression_1995)</sup>** In addition to the conserved <span id="Magenta">FAD</span>-binding **photolyase** homologous related (**PHR**) domain there is a variable carboxy-terminal domain commonly referred to as <span id="SkyB">C</span>**CT**. Current structural and biochemical studies suggests that light dependent changes in the intra-molecular interactions between the **PHR** and <span id="SkyB">C</span>**CT** domains are responsible for the conformational dependent activation of plant <span id="SkyB">CRY</span>. The photo-excited <span id="Magenta">FAD</span> buried within the **PHR** domain receives electrons from the surface of the protein courtesy three highly conserved tryptophan residues (**W** triad).**<sup>[135](#ref-chaves_cryptochromes_2011),[136](#ref-wang_mechanisms_2020)</sup>** The so called <span id="Magenta">FAD</span> photo-reduction hypothesis suggests that subtle conformational changes in the co-factor caused by the photo-reduction process is propagated, in a step-wise manner, through the **W** triad resulting in large scale conformational changes that permit homo-dimerization. Significant conformational changes in a highly conserved arginine residue (**R433**) apparently facilitates the dimerization process by “<i>anchoring</i>” within a deep pocket formed by the adjacent molecule.**<sup>[136](#ref-wang_mechanisms_2020)–[139](#ref-shao_oligomeric_2020)</sup>** Ultimately light induced activation of <span id="Gr2">PHY</span> and <span id="SkyB">CRY</span> triggers multiple protein-protein interactions (**PPI**) that leads to: (i) altered **ubiquitin** (**Ub**) dependent protein catabolism (i.e. **COP1**-**SPA** complexes);**<sup>[140](#ref-wang_direct_2001)–[143](#ref-podolec_photoreceptor-mediated_2018)</sup>** (ii) the activation or repression of gene expression;**<sup>[138](#ref-wang_photoactivation_2016),[144](#ref-liu_photoexcited_2008)</sup>** and (iii) increased protein phosphorylation which modulates the activity of both <span id="SkyB">CRY</span> and <span id="Gr2">PHY</span>.**<sup>[138](#ref-wang_photoactivation_2016),[145](#ref-shalitin_regulation_2002)–[153](#ref-viczian_phytochrome_2024)</sup>** A major concept in floral **photo-morphogenesis** is how plants respond to incoming light signals (e.g. length of day, quality of light) in a timely manner at different stages of development. This is largely co-ordinated by **circadian response proteins** (<span id="SkyB">CR</span>**P**) and downstream **flowering proteins** (<span id="Hpink">F</span>**P**). For example, when *Arabidopsis* is exposed to a long <span id="strokeB">P</span><span id="strokeW">P</span> the protein levels of key transcription factors (e.g. <span id="SkyB">CO</span>) stabilize, allowing them to activate floral identity genes like <span id="Moss">AP</span>**1**.**<sup>[154](#ref-abe_fd_2005),[155](#ref-wigge_integration_2005)</sup>** This vegetative-to-floral transition triggers **bolting**, which is an early floral stage when the primary shoot elongates and rises above the lower leaf rosette.

</div>

<!-------------------------------------------------->
<!-------- END - FIG 6 - PP Signal Network --------->
<!-------------------------------------------------->

    Since floral identity (i.e. <span id="Blue">IFM</span> → <span id="SkyB">FM</span>) is promoted by <span id="Gr2">LFY</span> and <span id="Moss">AP</span>**1** and actively antagonized by <span id="Magenta">TFL1</span> (i.e. maintain <span id="Blue">IFM</span>), exactly <i>How</i> do these genes co-ordinate life cycle changes in response to seasonal changes (e.g. <span id="strokeB">P</span><span id="strokeW">P</span>)? Most people know that spring and summer bring not only warmer weather but also a new generation of flowering plants. The timing of flowering within plants, particularly at higher latitudes, are adapted to the periodic changes in the length of day light (i.e. <span id="strokeB">P</span><span id="strokeW">P</span>). This is important to **dioecious** plants since all members of a population must flower at the same time under favourable conditions to ensure successful reproduction (i.e. out-crossing to produce fertile seeds). So perhaps a more reasonable question to ask would be: <i>How</i> is the activity of floral <b><a class="one" href="https://www.ibiology.org/development-and-stem-cells/homeotic-genes/" target="_blank" title="Go to iBIOLOGY">homeotic</a></b> genes like <span id="Gr2">LFY</span> or <span id="Moss">AP</span>**1** controlled by changes in the length of day?  
    First one needs to understand that *Arabidopsis* is a facultative <u>long day</u> (**LD**) plant. This means that although **LD** growth conditions (e.g. 16:8 hr light:dark cycle) can rapidly induce vegetative-to-floral transition it’s not an absolute requirement since short day (**SD**) treatments will eventually trigger flowering (**Fig. 6**). With this in mind researchers went about screening for <span id="strokeB">P</span><span id="strokeW">P</span> mutants.**<sup>[105](#ref-redei_supervital_1962),[156](#ref-koornneef_genetic_1991)</sup>** For example **Koornneef** (1991) performed a mutagenic screen (i.e. EMS, or irradiation treated seeds) to generate lines of late flowering mutant plants under **LD** greenhouse conditions. While most wild **ecotypes** of *Arabidopsis* (e.g. *Columbia* and *Landsberg erecta*) flower within 3-4 weeks under **LD** conditions, the average flowering time of the mutants ranged between 34 and 55 days.**<sup>[156](#ref-koornneef_genetic_1991)</sup>** One mutant allele named <span id="SkyB"><i>co</i></span>-3 (i.e. <span id="SkyB">CO</span>NSTANS) showed delayed flowering only in response to **LD** conditions (i.e. did not respond to either **S**hort **D**ay, **vernalization** or combined treatments), suggesting that there is at least one gene capable of sensing changes in <span id="strokeB">P</span><span id="strokeW">P</span>. A few years later the <span id="SkyB">CO</span> gene was cloned (1995) and shown (based on sequence homology alone) to encode a zinc finger transcription factor.**<sup>[157](#ref-putterill_constans_1995)</sup>** This allowed researchers to construction various transgenes, including one containing the <span id="SkyB">CO</span> gene fused in frame with a portion of the rat glucocorticoid receptor (transgene: <b><i>35S</i>::</b><span id="SkyB">CO</span>**-GR**).**<sup>[158](#ref-simon_activation_1996)</sup>** This unique construct allowed researchers to more precisely control the activity of <span id="SkyB">CO</span> since the constitutively expressed <span id="SkyB">CO</span>**-GR** fusion protein remains inactive within the cytoplasm (i.e. where it’s complexed with heat shock proteins) until the plant is treated with <u>**dex**amethasone</u> (Note: **dex** is a <u>ligand</u> of **GR** that allows the fusion protein to be transported into the nucleus). Steroid treatment of <b><i>35S</i>::</b><span id="SkyB">CO</span>**-GR** transgenic <span id="SkyB"><i>co</i></span>-2 plants (Note: <span id="SkyB"><i>co</i></span>-2 plants have no background <span id="SkyB">CO</span> expression) at different developmental stages resulted in a “<i>precocious flowering</i>” phenotype regardless of the <span id="strokeB">P</span><span id="strokeW">P</span> (i.e. **LD** or **SD** treatments). Constitutive expression of <span id="SkyB">CO</span> not only overcame delayed flowering caused by **SD** treatment, but also induced <span id="Gr2">LYF</span> transcription similar to what is seen in **LD** shifted wild type plants. By comparison <span id="Moss">AP1</span> transcription in the **SD** grown transgenic plants was slightly more delayed (i.e. 120 hrs) when compared to wild type plants (i.e. 72 hrs). Another notable feature of the **dex**-treated transgenic plants was the determinate nature of the **inflorescence**, with abnormal flowers appearing at the apex of each shoot. This “<i>precocious flowering</i>” phenotype is similar to the ones seen in <span id="Magenta"><i>tfl</i></span>**1** loss-of-function mutants, as well as <b><i>35S</i>::</b><span id="Gr2">LFY</span> and <b><i>35S</i>::</b><span id="Moss">AP</span>**1** transgenic plants.**<sup>[111](#ref-shannon_mutation_1991),[112](#ref-alvarez_terminal_1992),[127](#ref-weigel_developmental_1995),[128](#ref-mandel_gene_1995)</sup>** Since <span id="Magenta">TFL</span>**1** transcript levels within dexamethasone treated transgenic plants are similar to that of wild type plants, this suggests that <span id="SkyB">CO</span> can overcome the shoot promoting activity of wild type <span id="Magenta">TFL</span>**1**. These results suggested that <span id="SkyB">CO</span> likely activates <span id="Gr2">LYF</span> but not <span id="Moss">AP</span>**1** as part of its floral identity promoting activity.  
    However the most important gene activated by <span id="SkyB">CO</span> is arguably **Flowering Locus T** (<span id="Rasp">FT</span>).**<sup>[159](#ref-kardailsky_activation_1999)–[165](#ref-yoo_constans_2005)</sup>** In both *Arabidopsis* and rice (i.e. **Hd3a** is the <b><a class="one" href="https://www.nlm.nih.gov/ncbi/workshops/2023-08_BLAST_evol/ortho_para.html" target="_blank" title="Go to NIH">ortholog</a></b> of <span id="Rasp">FT</span>) <span id="Rasp">FT</span> functions as a mobile floral signaling factor (i.e. **florigen**). It travels from the leaves (Note: <span id="strokeB">P</span><span id="strokeW">P</span> is perceived primarily by mature plant leaves) to the floral **meristems** via the **phloem** where it binds to the transcription factor <span id="Crim">FD</span> and activates the floral identity gene <span id="Moss">AP</span>**1** (**Fig. 7**).**<sup>[154](#ref-abe_fd_2005),[155](#ref-wigge_integration_2005),[166](#ref-an_constans_2004)–[170](#ref-tamaki_hd3a_2007)</sup>** The <span id="Rasp">FT</span> genetic locus was originally identified by **Koornneef** (1991) during the same flowering-time mutant screen of *Arabidopsis* that uncovered multiple <span id="SkyB"><i>co</i></span> alleles.**<sup>[156](#ref-koornneef_genetic_1991)</sup>** Activation of <span id="Rasp">FT</span> also appears to be unique to <span id="SkyB">CO</span> transgenic plants since neither <b><i>35S</i>::</b><span id="Gr2">LYF</span> nor <b><i>35S</i>::</b><span id="Moss">AP</span>**1** activate <span id="Rasp">FT</span> transcription (Note: all three transgenic lines generate a “<i>precocious flowering</i>” phenotypes).**<sup>[160](#ref-kobayashi_pair_1999)</sup>** The mobility of <span id="Rasp">FT</span> requires at least two membrane associated protein transporters called **FT INTERACTING PROTEIN 1** (<span id="Rasp">FTIP</span>**1**)**<sup>[171](#ref-liu_ftip1_2012)</sup>** and **SODIUM POTASSIUM ROOT DEFECTIVE 1** (<span id="Rasp">NaKR</span>**1**).**<sup>[172](#ref-zhu_nakr1_2016)</sup>** <span id="Rasp">FT</span> has been shown to specifically interact with <span id="Rasp">FTIP1</span> within the **PD** that connects companion cells (i.e. site of <span id="Rasp">FT</span> production) to **phloem** sieve elements (i.e. elongated tubular cells). Unlike <span id="SkyB">CO</span> the expression levels of <span id="Rasp">FTIP</span>**1** are not subject to <span id="strokeB">P</span><span id="strokeW">P</span> induced oscillations (i.e. circadian rhythm).**<sup>[171](#ref-liu_ftip1_2012)</sup>** However <span id="Rasp">FE</span>, a transcription factor responsible for activating both <span id="Rasp">FT</span> and <span id="Rasp">FTIP</span>**1** transcription,**<sup>[173](#ref-abe_fe_2015)</sup>** was previously shown to be involved in promoting flowering in response to **LD** conditions (i.e. <span id="Rasp"><i>fe</i></span>-1, a mutant allele of <span id="Rasp">FE</span>).**<sup>[156](#ref-koornneef_genetic_1991)</sup>** Unlike <span id="SkyB"><i>co</i></span> alleles the lone <span id="Rasp"><i>fe</i></span> mutant causes delays in flowering in response to both **LD** and **SD** conditions. Since this dual <span id="strokeB">P</span><span id="strokeW">P</span> response of <span id="Rasp"><i>fe</i></span> is shared by both <span id="Rasp"><i>ft</i></span> and <span id="Rasp"><i>fd</i></span> alleles **Koornneef** (1991) proposed that these three genetic loci must be part of the same flowering pathway.**<sup>[156](#ref-koornneef_genetic_1991)</sup>** Obviously this hypothesis proved to be fruitful since subsequent research has shown: (i) <span id="Rasp">FT</span> partners with <span id="Crim">FD</span> to activate the transcription of <span id="Moss">AP</span>**1**; (ii) <span id="SkyB">CO</span>, which is the central regulator of <span id="strokeB">P</span><span id="strokeW">P</span> responses within *Arabidopsis*, also serves as key transcriptional activator of <span id="Rasp">FT</span>; and (iii) <span id="Rasp">FE</span> activates both <span id="Rasp">FT</span> and <span id="Rasp">FTIP</span>**1** expression, with the latter serving as an important transporter of the **florigen** <span id="Rasp">FT</span>. As for <span id="Rasp">NaKR</span>**1** it appears to regulate the transport of <span id="Rasp">FT</span> within **phloem** in a manner unlike that of <span id="Rasp">FTIP</span>**1**.**<sup>[172](#ref-zhu_nakr1_2016)</sup>** Instead of blocking the loading of <span id="Rasp">FT</span> into **phloem** sieve elements <span id="Rasp">NaKR</span>**1** mutations appear to inhibit the final stages of <span id="Rasp">FT</span> transport (i.e. entry into the apical **meristem**).**<sup>[172](#ref-zhu_nakr1_2016)</sup>** This step is essential since mutations that inhibit the function of <span id="Rasp">NaKR</span>**1** significantly delay flowering in response to **LD** conditions. Another important physiological aspects of <span id="Rasp">NaKR</span>**1** is its <span id="strokeB">P</span><span id="strokeW">P</span> induced expression pattern. Similar to <span id="SkyB">CO</span> the RNA levels of <span id="Rasp">NaKR</span>**1** normally fluctuates in response to a **LD** conditions resulting in a distinctive diurnal peak (i.e. after ~10 hours of light). Although the peak in <span id="Rasp">NaKR</span>**1** expression coincides with the early <span id="strokeB">P</span><span id="strokeW">P</span> induced rise in <span id="SkyB">CO</span> and <span id="Red">FT</span> expression, it is relatively fleeting when compared to either of these latter two transcription factors.**<sup>[163](#ref-suarez-lopez_constans_2001),[164](#ref-yanovsky_molecular_2002)</sup>** Nevertheless <span id="SkyB">CO</span> has been shown to physically bind to key regulatory elements within the <span id="Rasp">NaKR</span>**1** promoter and activate its expression.**<sup>[172](#ref-zhu_nakr1_2016)</sup>**

<a id="Fig7"></a>
<!--------------------------------------------------->
<!------------ FIG 7 - PP Signal Network2  ---------->
<!--------------------------------------------------->

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/CircadR_Floral_Gene_Activation_Part2.jpg" alt="" width="800px"/>

</figure>

**Figure 7. Photo-Period Genes & Flowering**. The expression levels of a key transcription factor known as **CONSTANS** (<span id="SkyB">CO</span>) is controlled by circadian clock regulatory genes, including **GIGANTEA** (**GI**),**<sup>[174](#ref-fowler_gigantea_1999),[175](#ref-park_control_1999)</sup>** **LATE ELONGATED HYPOCOTYL** (**LHY**)**<sup>[176](#ref-koornneef_genetic_1980),[177](#ref-schaffer_late_1998)</sup>** and **CIRCADIAN CLOCK ASSOCIATED 1** (**CCA1**).**<sup>[178](#ref-wang_constitutive_1998)</sup>** In response to long days (**LD**) the protein levels of <span id="SkyB">CO</span> peak later in the day, which results in the activation of **FLOWERING LOCUS T** (<span id="Hpink">FT</span>).**<sup>[163](#ref-suarez-lopez_constans_2001),[164](#ref-yanovsky_molecular_2002),[179](#ref-turck_regulation_2008)</sup>** The transcription factor <span id="Hpink">FT</span> is a mobile **florigen** capable of travelling via the **phloem** to the apical **meristems** where it activates floral promoting genes like <span id="Moss">AP</span>**1**.**<sup>[154](#ref-abe_fd_2005),[155](#ref-wigge_integration_2005)</sup>** The activity of <span id="SkyB">CO</span> is promoted by <span id="SkyB">CRY</span> and <span id="Gr2">PHY</span>**A**, while <span id="Gr2">PHY</span>**B** delays flowering by promoting the proteolytic degradation of <span id="SkyB">CO</span>.**<sup>[164](#ref-yanovsky_molecular_2002),[180](#ref-guo_regulation_1998)–[183](#ref-valverde_photoreceptor_2004)</sup>** The ability of <span id="SkyB">CRY</span> to form active **homodimers** in response to blue light is inhibited by **BIC1** (blue-light inhibitor of <span id="SkyB">CRY</span>1).**<sup>[138](#ref-wang_photoactivation_2016)</sup>** Both **BIC1** and <span id="SkyB">CRY</span> are either directly or indirectly targeted for destruction by the ubiquitin-dependent proteolytic complex **COP1**-**SPA**.**<sup>[140](#ref-wang_direct_2001)–[143](#ref-podolec_photoreceptor-mediated_2018),[184](#ref-laubinger_arabidopsis_2006)–[186](#ref-lian_blue-light-dependent_2011)</sup>** Other notable **COP1**-**SPA** targets include the transcription factors <span id="SkyB">CO</span> and **ELONGATED HYPOCOTYL 5** (**HY5**). The latter is a transcription factor that has been shown to specifically activate **BIC** gene expression when the **COP1**-**SPA** complex is inhibited by <span id="SkyB">CRY</span>. This represents an important negative-feedback loop between <span id="SkyB">CRY</span> and **BIC**.**<sup>[187](#ref-wang_crybic_2017)</sup>**

</div>

<!--------------------------------------------------->
<!-------- END - FIG 7 - PP Signal Network2 --------->
<!--------------------------------------------------->

<a id="ABCs"></a>
**<span style="border: 2px solid black;">  4.2 MODELS OF FLORAL ORGAN DEVELOPMENT  </span>** The original **ABC** model of floral organogenesis states that the identity of each floral organ (i.e. **sepals**, **petals**, **stamens** and **carpels**) is specified by a set of **homeotic** genes that belong to three different functional **classes** (i.e. **A**, **B**, **C**). As **Bowman** (1991) stated in his seminal paper mutations within these floral organ identity genes affect:

> “<i>..the differentiation of two adjacent whorls of organs, and thus falls into one of three classes: those affecting the first and second whorls, those affecting the second and third whorls, and those affecting the third and fourth whorls. The flower primordium can, consequently, be divided into <u>concentric fields</u> made up of pairs of adjacent whorls. The term ‘<b>field</b>’ is introduced here to refer to pairs of adjacent whorls, since these pairs of <b>whorls</b>, rather than single whorls, appear to be the <u>domains of action</u> of each of the classes of homeotic genes…..Field A is made up of <b>whorls</b> 1 and 2…..<b>whorls</b> 2 and 3 constitute field B…and field C is made of <b>whorls</b> 3 and 4…..it is important to recognize that by ‘<b>whorl</b>’ we mean a <u>geographic location</u>, within which organs of any identity can arise, and not the group of organs themselves. <b>Whorls</b> are thus identified by their position in the developing flower, and by the number and disposition of the organs within them, but not by the identity of these organs</i>.”<b><sup>[34](#ref-bowman_genetic_1991)</sup></b>

So to reiterate class **A** factors (i.e. <span id="Moss">AP</span>**1**, <span id="BGr">AP</span>**2**) specify **sepal** identity (outer **whorl** 1 position), and both class **A** and **B** factors (i.e. <span id="Moss">AP</span>**3**, <span id="Moss">PI</span>) are required to specify **petal** identity (**whorl** 2 position). Class **B** factors in combination with the class **C** factor <span id="Teal">AG</span> specify **stamen** identity (**whorl** 3 position), while the fourth inner most **whorl** of **carpels** is specified by the lone class **C** factor <span id="Teal">AG</span> (**Fig. 8**). All of the above **homeotic** factors, with the exception of <span id="BGr">AP</span>**2**, are members of the **MADS-box** gene family. However, regardless of how successful the **ABC** model is in predicting the phenotypes of various *Arabidopsis* mutants it unfortunately does not predict the phenotype produced by triple mutants comprised of all three classes of floral **homeotic** genes (e.g. <span id="BGr"><i>ap</i></span>**2**/<span id="Moss"><i>ap</i></span>**3**/<span id="Teal"><i>ag</i></span> or <span id="BGr"><i>ap</i></span>**2**/<span id="Moss"><i>pi</i></span>/<span id="Teal"><i>ag</i></span>).**<sup>[34](#ref-bowman_genetic_1991)</sup>**

> “<i>…It is tempting to speculate that the known three homeotic pathways are sufficient to specify floral organs and that, in their absence, only vegetative organs can form. The developmental ground state, however, appears not to be entirely vegetative.</i>”<b><sup>[34](#ref-bowman_genetic_1991)</sup></b>

Despite its short comings the **ABC** model does provide a insightful framework to understand various aspects of flower development in *Arabidopsis* as well as other flower species. Identifying all of the important genes that play a role in specifying floral organ development has always been challenging. Moreover the identity of the so called floral “<i>ground state</i>” is both an interesting and fundamental question in developmental biology, one that even the well known German polymath **Johann Wolfgang von Goethe** spent time contemplating. Although **Goethe** is better known for his play **Faust**, he also wrote an influential book entitled the **Metamorphosis of Plants** (1790) in which he proposed that all floral organs were essentially modified leaf-like structures.**<sup>[188](#ref-goethe_versuch_1790)</sup>** For the origin of flowers to be a primordial leaf-like structure that transforms into different organs via different cell signaling pathways (with the help of environmental cues) is certainly an attractive hypothesis. It’s also consistent with the conservative nature of body plan development (i.e. evolutionary time scales),**<sup>[189](#ref-niklas_evolutionary_2009)</sup>** even though genetic plasticity among **angiosperms** is a common theme (e.g. **heteroblasty**, variety of species).  
    The **carpel**-like features of triple **ABC** mutants (e.g. <span id="BGr"><i>ap</i></span>**2**/<span id="Moss"><i>pi</i></span>/<span id="Teal"><i>ag</i></span>) certainly highlights the fact that there must be other important floral **homeotic** genes, particularly ones that specify **carpel** development in the absence of <span id="Teal">AG</span> (i.e. only known class **C** gene). This void was soon filled by the discovery of a small group of closely related <span id="Teal">AG</span> like genes (aka: <span id="Teal">AGL</span>) called **SEPALLATA**s (i.e. <i>“lots of sepals</i>”) or simply <span id="Purple">SEP</span> .**<sup>[190](#ref-ma_agl1-agl6_1991),[191](#ref-huang_arabidopsis_1995)</sup>** These **MADS**-box genes, four of which are found in *Arabidopsis* (<span id="Purple">SEP</span>**1**, <span id="Purple">SEP</span>**2**, <span id="Purple">SEP</span>**3**, and <span id="Purple">SEP</span>**4**), have been shown to control the identity of all four floral organ types and as a result constitute class **E** floral identity genes.**<sup>[192](#ref-pelaz_b_2000)–[195](#ref-ditta_sep4_2004)</sup>** The other class **D** functioning **homeotic** genes specify **ovule** (i.e. seeds) identity and will only be mentioned here for clarity without any further discussion.**<sup>[196](#ref-alvarez_crabs_1999)–[198](#ref-pinyopich_assessing_2003)</sup>** However the important role that class **E** <span id="Purple">SEP</span> genes play in regulating **ABC** floral genes does require some further clarification.  
    Perhaps the most important early experiment that demonstrated the importance of class **E** genes was the generation of a triple <span id="Purple"><i>sep</i></span>**1**/<span id="Purple"><i>sep</i></span>**2**/<span id="Purple"><i>sep</i></span>**3** mutant.**<sup>[192](#ref-pelaz_b_2000),[193](#ref-honma_complexes_2001)</sup>** The resulting phenotype consisted of green **sepal**-like structures that replaced **petals** (**whorl** 2), **stamens** (**whorl** 3) and **carpels** (**whorl** 4). In addition these mutant flowers displayed an indeterminate phenotype as evidenced by aberrant floral organs being continuously produced inside of the fourth floral **whorl** (i.e. iterative process). Another notable feature of the triple <span id="Purple">SEP</span> mutant was the intact expression of both **B** (<span id="BGr">AP</span>**3**, <span id="Moss">PI</span>) and **C** (<span id="Teal">AG</span>) type **homeotic** genes. This suggested that **B** and **C** floral genes are to some degree transcriptionally independent of <span id="Purple">SEP</span>. Nevertheless both **B** and **C** floral **homeotic** genes do require functional <span id="Purple">SEP</span> proteins to carry out their own important developmental functions. Also the fact that both the triple mutant and **BC** double mutants (i.e. <span id="BGr"><i>ap</i></span>**3**/<span id="Teal"><i>ag</i></span>, <span id="Moss"><i>pi</i></span>/<span id="Teal"><i>ag</i></span>) share the same **sepal**-only phenotype is certainly consistent with the proposed role of <span id="Purple">SEP</span> in regulating **B** and **C** type floral **homeotic** function.**<sup>[32](#ref-bowman_genes_1989)</sup>** Eventually a quadruple mutant (genotype: <span id="Purple"><i>sep</i></span>**1**/<span id="Purple"><i>sep</i></span>**2**/<span id="Purple"><i>sep</i></span>**3**/<span id="Purple"><i>sep</i></span>**4**) was generated which showed a more basic leaf-like phenotype (i.e. all four floral organs were converted into leaf-like structures).**<sup>[195](#ref-ditta_sep4_2004)</sup>** The researchers also showed that a single functional <span id="Purple">SEP</span>**3** allele against a double <span id="Purple"><i>sep</i></span>**1**/<span id="Purple"><i>sep</i></span>**1** mutant background (genotype: <span id="Purple"><i>sep</i></span>**1** <span id="Purple"><i>sep</i></span>**2** <span id="Purple"><i>sep</i></span>**3/+**) is capable of generating fairly normal looking fertile flowers, albeit with reduced **stamen** numbers. Clearly given the **sepal**-only phenotype of the triple *null* mutant (<span id="Purple"><i>sep</i></span>**1**/<span id="Purple"><i>sep</i></span>**2**/<span id="Purple"><i>sep</i></span>**3**) removal of the remaining copy of <span id="Purple">SEP</span>**3** significantly impacted the development of floral organs. In retrospect this is certainly consistent with the strong transcriptional activity of <span id="Purple">SEP</span>**3** seen *in vitro*.**<sup>[193](#ref-honma_complexes_2001)</sup>** Moreover, when the heterologous triple mutant was combined with <span id="Purple"><i>sep</i></span>**4** (genotype: <span id="Purple"><i>sep</i></span>**1** <span id="Purple"><i>sep</i></span>**2** <span id="Purple"><i>sep</i></span>**3/+** <span id="Purple"><i>sep</i></span>**4**) floral organ numbers and identity were greatly affected (i.e. appearance of sepal-like organs, sepal-petal hybrids, abnormal stamens and carpels) suggesting that <span id="Purple">SEP</span>**4** plays a role in normal floral organ development. These results complemented earlier transgenic studies where ectopic expression of <span id="Purple">SEP</span> genes (i.e. **<i>35S</i>::**<span id="Purple">SEP</span>**3**, or both **<i>35S</i>::**<span id="Purple">SEP</span>**2** and **<i>35S</i>::**<span id="Purple">SEP</span>**3**) in combination with class **A** (**<i>35S</i>::**<span id="Moss">AP</span>**1**) and **B** (**<i>35S</i>::**<span id="BGr">AP</span>**3** + **<i>35S</i>::**<span id="Moss">PI</span>) **homeotic** genes were shown to convert vegetative **rosette** leaves into **petals**.**<sup>[194](#ref-pelaz_conversion_2001)</sup>** Close inspection (Scanning Electron Microscopic) of the mutant leaf cells showed that they are largely indistinguishable from that of wild type petals cells. Collectively these observations confirm **Johann Wolfgang von Goethe**’s (1790) hypothesis that floral organs arise from a basic leaf-like archetype or ground state.  
    Given the importance of <span id="Purple">SEP</span> transcription factors to floral development researchers have logically spent much of their efforts trying to identify downstream gene targets. Also questions about what regulates <span id="Purple">SEP</span> binding to DNA and other regulatory proteins have also been intensively investigated. For transcription factors like <span id="Purple">SEP</span> it’s important to remember that they do not operate alone. They often form multiple protein complexes in order to carry out various functions, whether it be DNA binding or other more complex transcriptional activities like chromatin remodelling (e.g. DNA looping).**<sup>[199](#ref-finzi_measurement_1995)–[201](#ref-mendes_mads_2013)</sup>** For <span id="Purple">SEP</span> proteins investigators learned that they readily form homo- or hetero-dimers, as well as hetero-tetramers (under more favourable conditions) with other **MADS-box** transcription factors.**<sup>[193](#ref-honma_complexes_2001),[201](#ref-mendes_mads_2013)–[206](#ref-puranik_structural_2014)</sup>** They not only help organize these multi-protein complexes (perhaps in a scaffold-like capacity), but are also transcriptional active *in vitro* and *in vivo*.**<sup>[207](#ref-hugouvieux_sepallata-driven_2024)</sup>** <span id="Purple">SEP</span> proteins bind to specific *cis*-regulatory **C-A-rich-G** consensus sequences (core **CArG**-box sequence: **CC(A/T)<sub>6</sub>GG**)**<sup>[208](#ref-kaufmann_target_2009),[209](#ref-pajoro_dynamics_2014)</sup>** using their **MADS** domain. The **MADS** name is based on the initials of four founding members of this transcription factor family, namely **M**inichromosome maintenance 1 (yeast), <span id="Teal">AG</span> (*Arabidospsis*), **D**EFICIENS A (*Antirrhinum majus* homologue of <span id="Moss">AP</span>**3**) and **S**erum response factor (humans).**<sup>[33](#ref-yanofsky_protein_1990),[210](#ref-sommer_deficiens_1990)</sup>** All floral **homeotic** genes that contain a **MADS** domain (i.e. <span id="Moss">AP</span>**1**, <span id="Moss">AP</span>**3**, <span id="Moss">PI</span>, <span id="Teal">AG</span>, <span id="Purple">SEP</span>**1-4**) belong to the type II or **MIKC** type **MADS** genes. Compared to the type I genes **MIKC** type genes are structurally more complex owing to the increased number of exons and the modular nature of the proteins.**<sup>[204](#ref-smaczniak_characterization_2012),[211](#ref-becker_major_2003)–[213](#ref-kaufmann_mikc-type_2005)</sup>** The **MIKC** name itself is an acronym of the four domains that make up these proteins, namely: (i) **M domain**, which is a highly conserved N-terminal 56 amino acid DNA-binding **MADS-box**; (ii) **I domain**, which is an alpha helical **Intervening** sequence important for DNA binding;**<sup>[214](#ref-riechmann_dimerization_1996)–[216](#ref-lai_intervening_2021)</sup>** (iii) **K domain**, which is a plant-specific coiled-coil Keratin-like oligomerization domain needed for dimerization and tetramerization;**<sup>[202](#ref-fan_specific_1997),[206](#ref-puranik_structural_2014),[217](#ref-yang_k_2003),[218](#ref-yang_defining_2004)</sup>** and (iv) **C domain**, which is a variable and unstructured C-terminal portion of the protein.  
   Although differences in tissue expression patterns and variations in protein stability have all been documented for floral **homeotic** genes including <span id="Purple">SEP</span>, other biochemical and biophysical factors can also affects their function. For example <span id="Purple">SEP</span>**3** has strong transcriptional activity both *in vitro* and *in vivo*. This activity is based in part on its ability to recognize specific DNA sequences (core **CArG**-box)**<sup>[208](#ref-kaufmann_target_2009),[209](#ref-pajoro_dynamics_2014)</sup>** within gene regulatory regions (e.g. promoter and enhancer elements). However powerful high throughput sequencing technologies (e.g. Chromatin immuno-precipitation sequencing, or **ChIP-seq**) that can identify transcription factor binding events across an entire genome has shown that only a subset of these transcription factor binding sites are occupied at any given time. For this reason alone the presence of a transcription factor binding site does not necessarily mean that it plays a role in regulating gene expression. Other biophysical considerations such as protein concentrations, as well as protein-DNA and protein-protein binding dynamics are also important factors that regulate gene expression. In fact the energetic constraints associated with these types of binding events would be ideal “<i>tunable</i>” factors from an evolutionary stand point (i.e. sequence mutations → altered protein-DNA binding → altered gene expression → altered phenotype → natural selection). The fact that many **MADS-box** transcription factors recognize similar or identical **CArG** motifs (albeit with somewhat different affinities) also means that it would be unreasonable to assign <span id="Purple">SEP</span> specific gene targets simply based on the presence of their preferred **CArG**-box binding motif. Also **MADS-box** transcription factors like <span id="Purple">SEP</span>**3** bind to DNA as obligate dimers (i.e. homo- or hetero-dimers recognize a given **CArG** motif) that combine to form tetramers *in vitro* and *in vivo* courtesy their oligomerization domains (**K** and **I**). Detailed structural analysis of <span id="Purple">SEP</span>**3** shows that its **K** domain forms two non-interacting amphipathic α-helices that are oriented 90° apart from each other courtesy a small intervening hydrophobic kinked region (i.e. forms a distinctive L-shape, **Fig. 8**).**<sup>[206](#ref-puranik_structural_2014),[207](#ref-hugouvieux_sepallata-driven_2024)</sup>** The first α-helix (**K1** sub-domain) and a N-terminal portion of the second α-helix (**K2** sub-domain) forms the binding interface between two anti-parallel arranged <span id="Purple">SEP</span>**3** monomers (i.e. dimerization), while the C-terminal portion of the second α-helix (**K3** sub-domain) forms the binding interface between two dimers (i.e. tetramerization). Note that the two anti-parallel L-shaped **K** domains of each monomer form a T-shaped dimer, with the stem of the T representing the two anti-parallel **K1** sub-domains and the top of the T representing the two anti-parallel second α-helices (**K2** and **K3** sub-domains).**<sup>[206](#ref-puranik_structural_2014)</sup>** The N-terminal **M domain** of each monomer would constitute the foot of the T where it binds to the **CArG**-box. When <span id="Purple">SEP</span> dimers form tetramers they can bind to two separate **CArG**-boxes in a stereo-specific manner (i.e. integral number of helical turns) resulting in DNA looping (i.e. intervening sequence). Structurally when the two T-shaped dimers come together to form a tetramer it takes on a cross-like shape (which seems appropriate given the cruciferous status of *Arabidopsis* ;). For some hetero-dimers (e.g. <span id="Moss">AP</span>**1**-<span id="Moss">PI</span>) partnering with <span id="Purple">SEP</span> dimers is advantageous since in their absence they show weak tetramer forming activity.**<sup>[219](#ref-melzer_reconstitution_2009)</sup>** Experimental manipulations of the intervening sequences connecting tandem **CArG** motifs also shows that the stereo-specific constraints of DNA-binding varies among the different <span id="Purple">SEP</span> complexes. For example the ability of <span id="Purple">SEP</span>**3** tetramers to bind to tandem **CArG** motifs is far less constrained by the length (short or long) of the intervening sequence than the other three <span id="Purple">SEP</span>.**<sup>[205](#ref-jetha_arabidopsis_2014)</sup>** Having biophysical properties that promote this type of co-operative binding could help to explain why <span id="Purple">SEP</span>**3** has such strong transcriptional activity and perhaps why it targets certain genes (i.e. specificity). The evolutionary significance of these types of protein-protein interactions has been explored with respect to the tetramerization domains (**K3** sub-domain) of <span id="Purple">SEP</span>**3**. A few studies have shown that several leucine residues that serve as key contact points along the α-helix of the **K3** sub-domain are not only highly conserved among many flowering plant species, but also appears to be vital to the function of <span id="Purple">SEP</span>**3** tetramers.**<sup>[207](#ref-hugouvieux_sepallata-driven_2024),[220](#ref-rumpler_conserved_2018),[221](#ref-lai_genome-wide_2020)</sup>** The stereo-specific nature of these hydrophobic residues are typical of a coiled-coil, which is a common type of protein secondary structure (Note: coiled coils are characterized by a seven residue sequence repeat, designated *a*-to-*g*, with positions *a* and *d* being hydrophobic residues. Interfacing helices with leucines occupying these critical positions often form so called “<i>leucine zippers</i>” since the leucine side chains extending from each α-helix inter-digitate with one another to facilitate dimerization).**<sup>[222](#ref-landschulz_leucine_1988),[223](#ref-liu_seven-helix_2006)</sup>** The fact that these non-polar leucine residues are very highly conserved among <span id="Purple">SEP</span>**3** related transcription factors in multiple flower species suggests that they are essential for tetramerization and by extension tetramer or *quartet* function. It’s interesting to note that **MADS** domain proteins unable of form tetramers prefer residues other than leucine at homologous positions within the heptad sequence of their α-helices.**<sup>[220](#ref-rumpler_conserved_2018)</sup>**  
    Finally it should be noted that the ability of <span id="Purple">SEP</span>**3** to control the formation of protein complexes (i.e. floral *quartets*) made up of a combination of **B** and **C** floral identity proteins suggests that it plays a key role integrating floral signals during development. This claim is supported by the recent identification of thousands of significant (i.e. near genes, *<b>F</b>alse <b>D</b>iscovery <b>R</b>ate* \<0.001) <span id="Purple">SEP</span>**3** binding sites across the entire *Arabidopsis* genome using **ChIP-seq** techniques,**<sup>[208](#ref-kaufmann_target_2009),[209](#ref-pajoro_dynamics_2014)</sup>** many of which undergo significant changes in occupancy (≥ 2 fold) during different stages of floral development (e.g. 1,118 genomic regions between days 2 and 4).**<sup>[209](#ref-pajoro_dynamics_2014)</sup>** This seemingly small quantitative change in binding site occupancy belies the complex molecular binding dynamics that occur within regulatory DNA sequences. The concentrations and binding affinities of different **MADS** domain transcription factors (e.g. competition) as well as the presence of **nucleosomes** (i.e. **histone** binding complexes that compact DNA and “<i>silence</i>” transcription) affect the probability that a binding event will trigger a given transcriptional outcome (i.e. activation or repression). This competition between **nucleosomes** and other DNA binding transcription factors ultimately affects gene expression patterns. It’s important to remember that only a small fraction of the genome is in an “<i>open</i>” transcriptionally active state (i.e. so called **euchromatin**), which allows DNA regulatory factors access to potential DNA binding sites. In fact a few floral **homeotic** genes like <span id="Gr2">LFY</span> and <span id="Purple">SEP</span>**3** itself have been shown to alter chromatin structure and accessibility by recruiting chromatin-remodelling factors such as **SPLAYED** (**SYD**) and **BRAHMA** (**BRM**) (**SWI2**/**SNF2** family **AT<span id="Red">P</span>ase** subunits).**<sup>[224](#ref-wu_swi2snf2_2012)</sup>** These **AT**<span id="Red">P</span> hydrolyzing factors help catalyze changes in **histone**–DNA interactions resulting in increased accessibility to gene regulatory elements.**<sup>[225](#ref-clapier_biology_2009),[226](#ref-tang_structure_2010)</sup>** The influence that <span id="Purple">SEP</span>**3** has on chromatin remodelling is particularly interesting in light of the number of transcription factors that are direct transcriptional targets of <span id="Purple">SEP</span>**3**, including itself (i.e. positive feedback loop). This type of auto-regulation may help to explain why <span id="Purple">SEP</span>**3** expression persists after being activated during the early stages of floral development.**<sup>[208](#ref-kaufmann_target_2009),[209](#ref-pajoro_dynamics_2014),[227](#ref-urbanus_planta_2009)</sup>**

<a id="Fig8"></a>
<!------------------------------------------------>
<!------------ FIG 8 - SEP Signalling ------------>
<!------------------------------------------------>

<div style="border: 2px solid gray; padding: 5px;">

<figure>

<img src="images/Fig8_AE_Model.jpg" alt="" width="800px"/>

</figure>

**Figure 8. AE & Quartet Model of Floral Organ Development**. **(A)** Multiple **MADS-box** transcription factors are classified according to their function within the **AE** model that ultimately form **tetramers** to carry out their transcriptionally duties *in vivo* (i.e. **Quartet** model). As detailed previously different functional **classes** of floral **homeotic** genes, most being **MADS** proteins, includes **Apetala1-2** (**class A**, <span id="Moss">AP</span>**1**, <span id="Moss">AP</span>**2**), **Apetala3** (**class B**, <span id="Moss">AP</span>**3**), **Pistillata** (**class B**, <span id="Moss">PI</span>), **Agamous** (**class C**, <span id="Teal">AG</span>), **Shatterproof** (**class D**, <span id="Vred">SHP</span>**1-2**), **Seedstick-like** (**class D**, <span id="Vred">STK</span>), and four **Sepallata**s (**class E**, <span id="Purple">SEP</span>**1-4**).**<sup>[34](#ref-bowman_genetic_1991),[103](#ref-coen_war_1991),[203](#ref-immink_sepallata3_2009),[219](#ref-melzer_reconstitution_2009),[228](#ref-theissen_plant_2001)</sup>** According to the **AE** model specific combinations of **MADS-box** proteins specify each type of floral organ (i.e. **sepals**, **petals**, **stamens**, **carpels**, and **ovules**).**<sup>[34](#ref-bowman_genetic_1991),[103](#ref-coen_war_1991)</sup>** For example, the combination of **class A** (<span id="Moss">AP</span>**1**) and **E** (<span id="Purple">SEP</span>**3**) genes would specify the development of **sepals** according to the **AE model**. Alternatively the **Quartet model** stipulates that **sepals** are specified by a transcriptionally active tetramer comprised of two hetero-dimers of **class A** (e.g. <span id="Moss">AP</span>**1**) and **E** (e.g. <span id="Purple">SEP</span>**3**) proteins.**<sup>[203](#ref-immink_sepallata3_2009),[219](#ref-melzer_reconstitution_2009),[228](#ref-theissen_plant_2001)</sup>** Both models rely on overlapping protein gradients (i.e. fields) to specify the position of a visible floral organ **whorl**. The only slight exception are the **ovules** or seeds that develop unseen within the **carpels** (i.e. **ovary**). Recent structural studies (i.e. protein-DNA and protein-protein interactions) have provided a much deeper understanding of how these transcription factors operate during flower development.**<sup>[206](#ref-puranik_structural_2014),[207](#ref-hugouvieux_sepallata-driven_2024),[216](#ref-lai_intervening_2021),[229](#ref-lai_structural_2019)</sup>** Specifically **MADS** domain transcription factors bind to DNA as obligate dimers via their N-terminal **M domains** (each recognizing half of a **CArG** motif), with the ~30 amino acid long **I**ntervening region (**I domain**) providing a key helical-fold that helps stabilize the DNA-binding **M domain**.**<sup>[216](#ref-lai_intervening_2021),[229](#ref-lai_structural_2019)</sup>** **Dimerization** and **tetramerization** domains are found within the L-shaped **K** domain. Both ionic and hydrophobic residues lining the multiple alpha-helical folds (**K1-3** sub-domains) provide critical contact points between monomers (i.e. **dimerization**) and dimers (i.e. **tetramerization**).**<sup>[206](#ref-puranik_structural_2014),[207](#ref-hugouvieux_sepallata-driven_2024),[220](#ref-rumpler_conserved_2018),[229](#ref-lai_structural_2019)</sup>** The **Quartets** of **MIKC** type **MADS** domain proteins have a characteristic cross-shape owing to the L-shaped monomers that serve as its building blocks. Opposite ends of a functional tetramer can bind to separate **CArG-box** motifs and thus alter the shape of the chromatin (i.e. DNA <i>looping</i>). Normally this takes place where DNA is open or free of **nucleosomes**. However only a small fraction of the genome is typically in an “<i>open</i>” or active transcriptional state (i.e. **euchromatin**). Nevertheless some so called “<i>pioneering</i>” transcription factors, such as <span id="Gr2">LYF</span>, can bind to **heterochromatin** (i.e. compacted DNA regions populated by **nucleosomes**) and initiate chromatin remodelling to promote transcription (i.e. create open **euchromatin**).**<sup>[209](#ref-pajoro_dynamics_2014),[224](#ref-wu_swi2snf2_2012),[230](#ref-jin_leafy_2021),[231](#ref-yamaguchi_leafy_2021)</sup>**  
**(B)** The structure of the <span id="Purple">SEP</span>**3<sup>75-178</sup>**/<span id="Teal">AG</span>**<sup>90-189</sup>** hetero-tetramer has recently been published (<b><a class="one" href="https://www.rcsb.org/structure/8CRA" target="_blank" title="Go to PDB">PDB code: 8CRA</a></b>).**<sup>[207](#ref-hugouvieux_sepallata-driven_2024)</sup>** The above images of the protein crystal structure were generated using the <b><a class="one" href="https://www.cgl.ucsf.edu/chimerax/" target="_blank" title="Go to UCSF">ChimeraX</a></b> v1.9 program.**<sup>[232](#ref-pettersen_ucsf_2021)</sup>** The crystal structure contains all three **K** sub-domains (**K1-3**), as well as a small part of the **I domain** and a few residues of the **C domain**. As noted previously the overall tetramer structure is shaped like a cross. Each <span id="Teal">AG</span>**<sup>90-189</sup>** monomer is highlighted in a colour gradient with the amino or <span id="Blue">N</span>**-terminus** in <span id="Blue">blue</span> and the downstream carboxyl or <span id="Red">C</span>**-terminus** in <span id="Red">red</span>. Each <span id="Purple">SEP</span>**3<sup>75-178</sup>** monomer is depicted in solid green and grey for contrast. The structure on the left renders the molecular surface of the monomers while the structure on the right only depicts the core secondary structures of the monomers (i.e. α-helices and unstructured kinked region between **K1** and **K2**). The latter structure provides a clear picture of the contact area that constitutes the tetramerization domain (i.e. **K3** sub-domain), as well as how closely intertwined the **K1** α-helices are within each dimer.

</div>

<!---------------------------------------------->
<!-------- END - FIG 8 - SEP Signalling -------->
<!---------------------------------------------->
<a id="Glos"></a>

<div align="center">

<h3>
LIST OF COMMON PLANT ANATOMY TERMS
</h3>

</div>

**Angiosperm:** are flowering plants that produce seeds encased within a fruit. They are largely made up of *Monocotyledonae* (~90,000 species), commonly known as **monocots** (e.g. grasses, lilies, irises, orchids, cattails, and palms), and *Eudicotyledonae* (~200,000 species), which are referred to as **eudicots** (e.g. deciduous trees, shrubs, and many herbaceous plants).**<sup>[81](#ref-evert_raven_2013)</sup>**

**Anther:** upper portion of the **stamen** that holds pollen.

**Awn:** long, bristle-like appendage often attached to a grass **floret**.

**Axil:** (Greek: <i>axilla</i>, armpit) is the upper angle between a stem and an attached twig or leaf. An **axillary bud** arises from this same region.

**Bract:** is a modified leaf sometimes associated with a flower. It sometimes resembles a small petal or a scale.

**Calyx:** outermost **whorl** of infertile flower parts known as **sepals**. Often green in colour and encloses the developing flower bud.

**Carpel:** houses the **ovules** (♀) which develop into seeds after fertilization. The carpel itself develops into the fruit wall.

**Catkin:** dense cylinder-like cluster of uni-sexual flowers. They usually lack petals and are found only in woody plants (e.g. aspen, willow, oaks).

**Cauline:** growing from or on the stem of a plant.

**Complete Flowers:** have all four **whorls** (i.e. **sepals**, **petals**, **stamens** and **carpels**).

**Composite flower head:** are specialized flowers belonging to the **Aster** family (<i>Asteraceae</i>). They are composed of tiny flowers clustered together on the **receptacle** that resembles a single bloom. They can be either <u>symmetrical</u> **disk flowers** or strap-shaped **ray flowers**.

**Compound leaf:** is composed of multiple **leaflets** arranged along the leaf stem. They can be either <u>bilaterally symmetrical</u> (i.e. **pinnate**) or <u>radially symmetrical</u> (i.e. **palmate**). **Leaflets**, unlike a true leaf, do not have a small bud where it joins the stem.

**Cordate leaf:** a heart-shaped leaf characterized by its rounded-notched base and acute or pointed tip.

**Corolla:** collective term for all of the flower **petals**.

**Cotyledon:** is a seed **leaf** (i.e. produced in the embryo and usually the first structure to emerge). Flowering plants have traditionally been divided into **Monocotyledons** (i.e. **monocots**) and **Dicotyledons** (i.e. **dicots**) based on the presence of one or two **cotyledons**. Also **dicots** are characterized by having flower parts in multiples of 4’s or 5’s. Currently **dicots** are divided into two groups, namely **eudicots** and a smaller group of **primitive (basal) dicots**.

**Dioecious:** Greek for “<i>two houses</i>”, where **staminate** and **carpellate** flowers are found on separate plants.

**Disk floret:** is a tiny, symmetrical flower of a **composite** flower head (i.e. sunflower family, <i>Asteraceae</i>) that often make up the central platform or base of the flower head.

**Filament:** is the thread-like part of the male reproductive structure that supports the anther.

**Floret:** is one flower within a **composite** flower head or one flower and bract of a grass (<i>Poaceae</i>).

**Flower head:** a group of flowers clustered on a common base.

**Glume:** one of two scale-like **bracts** at the base of a grass **spikelet**.

**Gymnosperm:** plants that produce **ovules** that are unprotected by ovary or fruit (e.g. conifers).

**Gynoecium:** is the collective term for the **carpels** (i.e. ovule-bearing part of flower). Flower may contain one or more **carpels** that may be separate, or fused in part or altogether. The **carpels** are commonly referred to as a **pistil**.

**Imperfect Flower:** is one that lacks either **stamens** or **carpels** (i.e. uni-sexual). Flowers that only have **stamens** are referred to as **staminate**, while those that only have **carpels** are referred to as **carpellate**.

**Incomplete Flowers:** are ones that lack one of the four **whorls** (i.e. sepals, petals, stamens, or carpels). It is therefore possible to have an **incomplete flower** that is either **perfect** (has both **stamen** and **carpel** whorls) or **imperfect** (lacks either a **stamen** and **carpel** whorl).

**Inflorescences:** cluster or aggregation of flowers.

**Involucre:** is a group of **bracts**, or **phyllaries**, that form a unit below a flower, flower cluster, flower head (composite flower) or fruit.

**Lanceolate:** term used to describe leaves that are much longer than broad, and widest near the base.

**Lemma:** the lower of two **bracts** at the base of a grass **floret**, with the upper **bract** being called the **palea**.

**Locules:** chamber of the **ovary** that contains **ovules**.

**Monocotyledon:** or **monocot** is a flowering plant characterized by having one **cotyledon** and flower parts usually in multiples of three.

**Monoecious:** (Greek: “<i>one house</i>”) a plant that contains both **staminate** and **carpellate** flowers.

**Node:** point on the stem where a root, leaf or branch originates.

**Obovate:** term used to describe leaves that are are shaped like an inverted egg (i.e. somewhat longer than wide, and widest near the top).

**Ovary:** lower part of the **carpel** (or **pistil**) which encloses the **ovules**.

**Ovate:** term used to describe leaves that are shaped like an egg with widest part near plant.

**Palea:** the small **bract** at the base of a grass **disk floret**.

**Palmate:** **compound** leaves that have **leaflets** radiating from a common point or arranged like fingers around a palm.

**Pappus:** a <u>hairy</u> modified **calyx** on the seeds of some composite flowers that aids in seed dispersal.

**Peduncle:** stalk of an **inflorescence** or a solitary flower.

**Pedicel:** stalk of an individual flower within an **inflorescence**.

**Perfect Flower:** contains both **stamens** and **carpels** (i.e. bi-sexual).

**Ploidy:** cells with either one or more sets of chromosomes (e.g. **<i>n</i>** = **haploid**; **2<i>n</i>** = **diploid**; **4<i>n</i>** = **tetraploid**). Alternating between **diploid** and **haploid** phases is the basis of sexual reproduction.

**Perianth:** structure formed by both the **calyx** and **corolla**.

**Petals:** sterile leaf-like appendages that are usually thin and brightly coloured. They collectively form the **corolla**.

**Phyllary:** a single **bract** at the base of a **composite** flower head.

**Pinnate:** term used to describe compound leaves that have their **leaflets** bilaterally arranged along a common stem axis, somewhat reminiscent of a feather.

**Pistil:** female reproductive structure of the flower that includes the **ovary**, **style** and **stigma**.

**Pollinium:** a single packet of **pollen** grains (e.g. milkweed flowers).

**Ray floret:** tiny strap-like flowers within a **composite** flower head that often form an outer halo.

**Receptacle:** part of the plant to which a flower is attached.

**Sepals:** sterile leaf-like appendages that are usually green and relatively thick. They are attached to the receptacle just below the **petals** and collectively form the **calyx**.

**Sessile:** lacking either a **pedicel** (i.e. in case of flowers) or a **petiole** (i.e. in case of leaves), resulting in direct contact with the stem.

**Simple leaf:** an intact or undivided leaf (i.e. no leaflets).

**Stamens:** pollen bearing part of the fertile flower collectively called the **androecium**. It is usually made up a slender stalk called the **filament** and an **anther** containing four pollen sacs or **microsporangia**.

**Stigma:** upper portion of the **pistil** responsible for capturing pollen.

**Stipules:** appendages at the base of a leaf that may appear as scales, spines, or glands.

**Style:** middle of the **carpel** where the **pollen tube** will grow as it migrates toward the **ovules** to fertilize them.

**Tepals:** term often used to refer to both the **sepals** and **petals** together.

**Trichome:** a hair-like structure that may be glandular in nature.

**Umbel:** a flower arrangement in which the flower stalks or **pedicels** emerge from a single point.

**Whorls:** is a circle of flower parts of one kind.

<img src="images/underconstruction_logo.gif" width="300" />

------------------------------------------------------------------------

<hr style="border:2px solid gray">
<!--------------------------------------------------------------------->

© Jeffrey C. Howard B.Sc. M.Sc. Ph.D. B.Ed. - The material contained within this website may be copied, distributed and displayed without alterations for noncommercial purposes only provided that it is accompanied by acknowledgements to the author. All commercial and non-commercial rights are reserved to the author.  
<!--------------------------------------------------------------------->

<hr style="border:2px solid gray">

<a id="Refs"></a>  
**REFERENCES:**

<script src='https://storage.ko-fi.com/cdn/scripts/overlay-widget.js'></script>
<script>
  kofiWidgetOverlay.draw('jch274202227', {
    'type': 'floating-chat',
    'floating-chat.donateButton.text': 'Help Support',
    'floating-chat.donateButton.background-color': '#00b9fe',
    'floating-chat.donateButton.text-color': '#fff'
  });
</script>

<div id="refs" class="references csl-bib-body" entry-spacing="0">

<div id="ref-jurgens_apical-basal_2001" class="csl-entry">

<span class="csl-left-margin">1 </span><span class="csl-right-inline">Jürgens G. Apical-basal pattern formation in Arabidopsis embryogenesis. *The EMBO Journal* 2001;**20**:3609–16. <https://doi.org/10.1093/emboj/20.14.3609>.</span>

</div>

<div id="ref-foster_structure_1938" class="csl-entry">

<span class="csl-left-margin">2 </span><span class="csl-right-inline">Foster AS. Structure and Growth of the Shoot Apex in Ginkgo Biloba. *Bulletin of the Torrey Botanical Club* 1938;**65**:531–56. <https://doi.org/10.2307/2480793>.</span>

</div>

<div id="ref-traas_cellular_2001" class="csl-entry">

<span class="csl-left-margin">3 </span><span class="csl-right-inline">Traas J, Doonan JH. [Cellular basis of shoot apical meristem development](https://doi.org/10.1016/S0074-7696(01)08004-4). *International Review of Cytology*, vol. 208. Academic Press; 2001. p. 161–206.</span>

</div>

<div id="ref-laux_wuschel_1996" class="csl-entry">

<span class="csl-left-margin">4 </span><span class="csl-right-inline">Laux T, Mayer KF, Berger J, Jürgens G. The WUSCHEL gene is required for shoot and floral meristem integrity in Arabidopsis. *Development (Cambridge, England)* 1996;**122**:87–96. <https://doi.org/10.1242/dev.122.1.87>.</span>

</div>

<div id="ref-mayer_role_1998" class="csl-entry">

<span class="csl-left-margin">5 </span><span class="csl-right-inline">Mayer KF, Schoof H, Haecker A, Lenhard M, Jürgens G, Laux T. Role of WUSCHEL in regulating stem cell fate in the Arabidopsis shoot meristem. *Cell* 1998;**95**:805–15. <https://doi.org/10.1016/s0092-8674(00)81703-1>.</span>

</div>

<div id="ref-schoof_stem_2000" class="csl-entry">

<span class="csl-left-margin">6 </span><span class="csl-right-inline">Schoof H, Lenhard M, Haecker A, Mayer KF, Jürgens G, Laux T. The stem cell population of Arabidopsis shoot meristems is maintained by a regulatory loop between the CLAVATA and WUSCHEL genes. *Cell* 2000;**100**:635–44. <https://doi.org/10.1016/s0092-8674(00)80700-x>.</span>

</div>

<div id="ref-turesson_species_1922" class="csl-entry">

<span class="csl-left-margin">7 </span><span class="csl-right-inline">Turesson G. The Species and the Variety as Ecological Units. *Hereditas* 1922;**3**:100–13. <https://doi.org/10.1111/j.1601-5223.1922.tb02727.x>.</span>

</div>

<div id="ref-turesson_genotypical_1922" class="csl-entry">

<span class="csl-left-margin">8 </span><span class="csl-right-inline">Turesson G. The Genotypical Response of the Plant Species to the Habitat. *Hereditas* 1922;**3**:211–350. <https://doi.org/10.1111/j.1601-5223.1922.tb02734.x>.</span>

</div>

<div id="ref-fink_anatomy_1998" class="csl-entry">

<span class="csl-left-margin">9 </span><span class="csl-right-inline">Fink GR. Anatomy of a revolution. *Genetics* 1998;**149**:473–7. <https://doi.org/10.1093/genetics/149.2.473>.</span>

</div>

<div id="ref-kramer_planting_2015" class="csl-entry">

<span class="csl-left-margin">10 </span><span class="csl-right-inline">Krämer U. Planting molecular functions in an ecological context with Arabidopsis thaliana. *eLife* 2015;**4**:e06100. <https://doi.org/10.7554/eLife.06100>.</span>

</div>

<div id="ref-schultz_leafy_1991" class="csl-entry">

<span class="csl-left-margin">11 </span><span class="csl-right-inline">Schultz EA, Haughn GW. LEAFY, a Homeotic Gene That Regulates Inflorescence Development in Arabidopsis. *The Plant Cell* 1991;**3**:771–81. <https://doi.org/10.1105/tpc.3.8.771>.</span>

</div>

<div id="ref-brand_dependence_2000" class="csl-entry">

<span class="csl-left-margin">12 </span><span class="csl-right-inline">Brand U, Fletcher JC, Hobe M, Meyerowitz EM, Simon R. Dependence of stem cell fate in Arabidopsis on a feedback loop regulated by CLV3 activity. *Science (New York, NY)* 2000;**289**:617–9. <https://doi.org/10.1126/science.289.5479.617>.</span>

</div>

<div id="ref-yadav_wuschel_2011" class="csl-entry">

<span class="csl-left-margin">13 </span><span class="csl-right-inline">Yadav RK, Perales M, Gruel J, Girke T, Jönsson H, Reddy GV. WUSCHEL protein movement mediates stem cell homeostasis in the Arabidopsis shoot apex. *Genes & Development* 2011;**25**:2025–30. <https://doi.org/10.1101/gad.17258511>.</span>

</div>

<div id="ref-daum_mechanistic_2014" class="csl-entry">

<span class="csl-left-margin">14 </span><span class="csl-right-inline">Daum G, Medzihradszky A, Suzaki T, Lohmann JU. A mechanistic framework for noncell autonomous stem cell induction in Arabidopsis. *Proceedings of the National Academy of Sciences of the United States of America* 2014;**111**:14619–24. <https://doi.org/10.1073/pnas.1406446111>.</span>

</div>

<div id="ref-fletcher_signaling_1999" class="csl-entry">

<span class="csl-left-margin">15 </span><span class="csl-right-inline">Fletcher JC, Brand U, Running MP, Simon R, Meyerowitz EM. Signaling of cell fate decisions by CLAVATA3 in Arabidopsis shoot meristems. *Science (New York, NY)* 1999;**283**:1911–4. <https://doi.org/10.1126/science.283.5409.1911>.</span>

</div>

<div id="ref-rojo_clv3_2002" class="csl-entry">

<span class="csl-left-margin">16 </span><span class="csl-right-inline">Rojo E, Sharma VK, Kovaleva V, Raikhel NV, Fletcher JC. CLV3 is localized to the extracellular space, where it activates the Arabidopsis CLAVATA stem cell signaling pathway. *The Plant Cell* 2002;**14**:969–77. <https://doi.org/10.1105/tpc.002196>.</span>

</div>

<div id="ref-zhou_control_2015" class="csl-entry">

<span class="csl-left-margin">17 </span><span class="csl-right-inline">Zhou Y, Liu X, Engstrom EM, Nimchuk ZL, Pruneda-Paz JL, Tarr PT, *et al.* Control of plant stem cell function by conserved interacting transcriptional regulators. *Nature* 2015;**517**:377–80. <https://doi.org/10.1038/nature13853>.</span>

</div>

<div id="ref-zhou_hairy_2018" class="csl-entry">

<span class="csl-left-margin">18 </span><span class="csl-right-inline">Zhou Y, Yan A, Han H, Li T, Geng Y, Liu X, *et al.* HAIRY MERISTEM with WUSCHEL confines CLAVATA3 expression to the outer apical meristem layers. *Science* 2018;**361**:502–6. <https://doi.org/10.1126/science.aar8638>.</span>

</div>

<div id="ref-van_der_graaff_wus_2009" class="csl-entry">

<span class="csl-left-margin">19 </span><span class="csl-right-inline">Graaff E van der, Laux T, Rensing SA. The WUS homeobox-containing (WOX) protein family. *Genome Biology* 2009;**10**:248. <https://doi.org/10.1186/gb-2009-10-12-248>.</span>

</div>

<div id="ref-mukherjee_comprehensive_2009" class="csl-entry">

<span class="csl-left-margin">20 </span><span class="csl-right-inline">Mukherjee K, Brocchieri L, Bürglin TR. A comprehensive classification and evolutionary analysis of plant homeobox genes. *Molecular Biology and Evolution* 2009;**26**:2775–94. <https://doi.org/10.1093/molbev/msp201>.</span>

</div>

<div id="ref-gehring_homeodomain_1994" class="csl-entry">

<span class="csl-left-margin">21 </span><span class="csl-right-inline">Gehring WJ, Affolter M, Bürglin T. Homeodomain proteins. *Annual Review of Biochemistry* 1994;**63**:487–526. <https://doi.org/10.1146/annurev.bi.63.070194.002415>.</span>

</div>

<div id="ref-burglin_homeodomain_2016" class="csl-entry">

<span class="csl-left-margin">22 </span><span class="csl-right-inline">Bürglin TR, Affolter M. Homeodomain proteins: An update. *Chromosoma* 2016;**125**:497–521. <https://doi.org/10.1007/s00412-015-0543-8>.</span>

</div>

<div id="ref-yadav_wuschel_2010" class="csl-entry">

<span class="csl-left-margin">23 </span><span class="csl-right-inline">Yadav RK, Tavakkoli M, Reddy GV. WUSCHEL mediates stem cell homeostasis by regulating stem cell number and patterns of cell division and differentiation of stem cell progenitors. *Development (Cambridge, England)* 2010;**137**:3581–9. <https://doi.org/10.1242/dev.054973>.</span>

</div>

<div id="ref-maule_plasmodesmata_2008" class="csl-entry">

<span class="csl-left-margin">24 </span><span class="csl-right-inline">Maule AJ. Plasmodesmata: Structure, function and biogenesis. *Current Opinion in Plant Biology* 2008;**11**:680–6. <https://doi.org/10.1016/j.pbi.2008.08.002>.</span>

</div>

<div id="ref-zambryski_plasmodesmata_2008" class="csl-entry">

<span class="csl-left-margin">25 </span><span class="csl-right-inline">Zambryski P. Plasmodesmata. *Current Biology* 2008;**18**:R324–5. <https://doi.org/10.1016/j.cub.2008.01.046>.</span>

</div>

<div id="ref-brand_regulation_2002" class="csl-entry">

<span class="csl-left-margin">26 </span><span class="csl-right-inline">Brand U, Grünewald M, Hobe M, Simon R. Regulation of CLV3 expression by two homeobox genes in Arabidopsis. *Plant Physiology* 2002;**129**:565–75. <https://doi.org/10.1104/pp.001867>.</span>

</div>

<div id="ref-clark_clavata1_1997" class="csl-entry">

<span class="csl-left-margin">27 </span><span class="csl-right-inline">Clark SE, Williams RW, Meyerowitz EM. The CLAVATA1 gene encodes a putative receptor kinase that controls shoot and floral meristem size in Arabidopsis. *Cell* 1997;**89**:575–85. <https://doi.org/10.1016/s0092-8674(00)80239-1>.</span>

</div>

<div id="ref-jeong_arabidopsis_1999" class="csl-entry">

<span class="csl-left-margin">28 </span><span class="csl-right-inline">Jeong S, Trotochaud AE, Clark SE. The Arabidopsis CLAVATA2 Gene Encodes a Receptor-like Protein Required for the Stability of the CLAVATA1 Receptor-like Kinase. *The Plant Cell* 1999;**11**:1925–33. <https://doi.org/10.1105/tpc.11.10.1925>.</span>

</div>

<div id="ref-muller_receptor_2008" class="csl-entry">

<span class="csl-left-margin">29 </span><span class="csl-right-inline">Müller R, Bleckmann A, Simon R. The Receptor Kinase CORYNE of Arabidopsis Transmits the Stem Cell–Limiting Signal CLAVATA3 Independently of CLAVATA1. *The Plant Cell* 2008;**20**:934–46. <https://doi.org/10.1105/tpc.107.057547>.</span>

</div>

<div id="ref-ishida_heterotrimeric_2014" class="csl-entry">

<span class="csl-left-margin">30 </span><span class="csl-right-inline">Ishida T, Tabata R, Yamada M, Aida M, Mitsumasu K, Fujiwara M, *et al.* Heterotrimeric G proteins control stem cell proliferation through CLAVATA signaling in Arabidopsis. *EMBO Reports* 2014;**15**:1202–9. <https://doi.org/10.15252/embr.201438660>.</span>

</div>

<div id="ref-shimizu_bam_2015" class="csl-entry">

<span class="csl-left-margin">31 </span><span class="csl-right-inline">Shimizu N, Ishida T, Yamada M, Shigenobu S, Tabata R, Kinoshita A, *et al.* BAM 1 and RECEPTOR-LIKE PROTEIN KINASE 2 constitute a signaling pathway and modulate CLE peptide-triggered growth inhibition in Arabidopsis root. *The New Phytologist* 2015;**208**:1104–13. <https://doi.org/10.1111/nph.13520>.</span>

</div>

<div id="ref-bowman_genes_1989" class="csl-entry">

<span class="csl-left-margin">32 </span><span class="csl-right-inline">Bowman JL, Smyth DR, Meyerowitz EM. Genes directing flower development in Arabidopsis. *The Plant Cell* 1989;**1**:37–52. <https://doi.org/10.1105/tpc.1.1.37>.</span>

</div>

<div id="ref-yanofsky_protein_1990" class="csl-entry">

<span class="csl-left-margin">33 </span><span class="csl-right-inline">Yanofsky MF, Ma H, Bowman JL, Drews GN, Feldmann KA, Meyerowitz EM. The protein encoded by the Arabidopsis homeotic gene agamous resembles transcription factors. *Nature* 1990;**346**:35–9. <https://doi.org/10.1038/346035a0>.</span>

</div>

<div id="ref-bowman_genetic_1991" class="csl-entry">

<span class="csl-left-margin">34 </span><span class="csl-right-inline">Bowman JL, Smyth DR, Meyerowitz EM. Genetic interactions among floral homeotic genes of Arabidopsis. *Development (Cambridge, England)* 1991;**112**:1–20. <https://doi.org/10.1242/dev.112.1.1>.</span>

</div>

<div id="ref-nakatsuka_molecular_2018" class="csl-entry">

<span class="csl-left-margin">35 </span><span class="csl-right-inline">Nakatsuka T, Koishi K. Molecular characterization of a double-flower mutation in Matthiola incana. *Plant Science: An International Journal of Experimental Plant Biology* 2018;**268**:39–46. <https://doi.org/10.1016/j.plantsci.2017.12.009>.</span>

</div>

<div id="ref-saunders_note_1921" class="csl-entry">

<span class="csl-left-margin">36 </span><span class="csl-right-inline">Saunders ER. Note on the evolution of the double stock (Matthiola incana). *Journal of Genetics* 1921;**11**:69–74. <https://doi.org/10.1007/BF02983035>.</span>

</div>

<div id="ref-lohmann_molecular_2001" class="csl-entry">

<span class="csl-left-margin">37 </span><span class="csl-right-inline">Lohmann JU, Hong RL, Hobe M, Busch MA, Parcy F, Simon R, *et al.* A molecular link between stem cell regulation and floral patterning in Arabidopsis. *Cell* 2001;**105**:793–803. <https://doi.org/10.1016/s0092-8674(01)00384-1>.</span>

</div>

<div id="ref-lenhard_termination_2001" class="csl-entry">

<span class="csl-left-margin">38 </span><span class="csl-right-inline">Lenhard M, Bohnert A, Jürgens G, Laux T. Termination of stem cell maintenance in Arabidopsis floral meristems by interactions between WUSCHEL and AGAMOUS. *Cell* 2001;**105**:805–14. <https://doi.org/10.1016/s0092-8674(01)00390-7>.</span>

</div>

<div id="ref-sun_timing_2009" class="csl-entry">

<span class="csl-left-margin">39 </span><span class="csl-right-inline">Sun B, Xu Y, Ng K-H, Ito T. A timing mechanism for stem cell maintenance and differentiation in the Arabidopsis floral meristem. *Genes & Development* 2009;**23**:1791–804. <https://doi.org/10.1101/gad.1800409>.</span>

</div>

<div id="ref-schofield_relationship_1978" class="csl-entry">

<span class="csl-left-margin">40 </span><span class="csl-right-inline">Schofield R. [The relationship between the spleen colony-forming cell and the haemopoietic stem cell](https://www.ncbi.nlm.nih.gov/pubmed/747780). *Blood Cells* 1978;**4**:7–25.</span>

</div>

<div id="ref-till_direct_1961" class="csl-entry">

<span class="csl-left-margin">41 </span><span class="csl-right-inline">Till JE, McCULLOCH EA. [A direct measurement of the radiation sensitivity of normal mouse bone marrow cells](https://www.ncbi.nlm.nih.gov/pubmed/13776896). *Radiation Research* 1961;**14**:213–22.</span>

</div>

<div id="ref-becker_cytological_1963" class="csl-entry">

<span class="csl-left-margin">42 </span><span class="csl-right-inline">Becker AJ, McCULLOCH EA, Till JE. Cytological demonstration of the clonal nature of spleen colonies derived from transplanted mouse marrow cells. *Nature* 1963;**197**:452–4. <https://doi.org/10.1038/197452a0>.</span>

</div>

<div id="ref-moore_stem_2006" class="csl-entry">

<span class="csl-left-margin">43 </span><span class="csl-right-inline">Moore KA, Lemischka IR. Stem cells and their niches. *Science (New York, NY)* 2006;**311**:1880–5. <https://doi.org/10.1126/science.1110542>.</span>

</div>

<div id="ref-pennings_stem_2018" class="csl-entry">

<span class="csl-left-margin">44 </span><span class="csl-right-inline">Pennings S, Liu KJ, Qian H. The Stem Cell Niche: Interactions between Stem Cells and Their Environment. *Stem Cells International* 2018;**2018**:4879379. <https://doi.org/10.1155/2018/4879379>.</span>

</div>

<div id="ref-watt_epidermal_1998" class="csl-entry">

<span class="csl-left-margin">45 </span><span class="csl-right-inline">Watt FM. Epidermal stem cells: Markers, patterning and the control of stem cell fate. *Philosophical Transactions of the Royal Society of London Series B, Biological Sciences* 1998;**353**:831–7. <https://doi.org/10.1098/rstb.1998.0247>.</span>

</div>

<div id="ref-gonzales_skin_2017" class="csl-entry">

<span class="csl-left-margin">46 </span><span class="csl-right-inline">Gonzales KAU, Fuchs E. Skin and Its Regenerative Powers: An Alliance between Stem Cells and Their Niche. *Developmental Cell* 2017;**43**:387–401. <https://doi.org/10.1016/j.devcel.2017.10.001>.</span>

</div>

<div id="ref-adams_changes_1990" class="csl-entry">

<span class="csl-left-margin">47 </span><span class="csl-right-inline">Adams JC, Watt FM. Changes in keratinocyte adhesion during terminal differentiation: Reduction in fibronectin binding precedes alpha 5 beta 1 integrin loss from the cell surface. *Cell* 1990;**63**:425–35. <https://doi.org/10.1016/0092-8674(90)90175-e>.</span>

</div>

<div id="ref-jones_separation_1993" class="csl-entry">

<span class="csl-left-margin">48 </span><span class="csl-right-inline">Jones PH, Watt FM. Separation of human epidermal stem cells from transit amplifying cells on the basis of differences in integrin function and expression. *Cell* 1993;**73**:713–24. <https://doi.org/10.1016/0092-8674(93)90251-k>.</span>

</div>

<div id="ref-watt_expression_1993" class="csl-entry">

<span class="csl-left-margin">49 </span><span class="csl-right-inline">Watt FM, Jones PH. [Expression and function of the keratinocyte integrins](https://www.ncbi.nlm.nih.gov/pubmed/8049472). *Development (Cambridge, England) Supplement* 1993:185–92.</span>

</div>

<div id="ref-vernoux_auxin_2010" class="csl-entry">

<span class="csl-left-margin">50 </span><span class="csl-right-inline">Vernoux T, Besnard F, Traas J. Auxin at the Shoot Apical Meristem. *Cold Spring Harbor Perspectives in Biology* 2010;**2**:a001487. <https://doi.org/10.1101/cshperspect.a001487>.</span>

</div>

<div id="ref-kieber_cytokinin_2018" class="csl-entry">

<span class="csl-left-margin">51 </span><span class="csl-right-inline">Kieber JJ, Schaller GE. Cytokinin signaling in plant development. *Development* 2018;**145**:dev149344. <https://doi.org/10.1242/dev.149344>.</span>

</div>

<div id="ref-higuchi_planta_2004" class="csl-entry">

<span class="csl-left-margin">52 </span><span class="csl-right-inline">Higuchi M, Pischke MS, Mähönen AP, Miyawaki K, Hashimoto Y, Seki M, *et al.* In planta functions of the Arabidopsis cytokinin receptor family. *Proceedings of the National Academy of Sciences of the United States of America* 2004;**101**:8821–6. <https://doi.org/10.1073/pnas.0402887101>.</span>

</div>

<div id="ref-nishimura_histidine_2004" class="csl-entry">

<span class="csl-left-margin">53 </span><span class="csl-right-inline">Nishimura C, Ohashi Y, Sato S, Kato T, Tabata S, Ueguchi C. Histidine kinase homologs that act as cytokinin receptors possess overlapping functions in the regulation of shoot and root growth in Arabidopsis. *The Plant Cell* 2004;**16**:1365–77. <https://doi.org/10.1105/tpc.021477>.</span>

</div>

<div id="ref-leibfried_wuschel_2005" class="csl-entry">

<span class="csl-left-margin">54 </span><span class="csl-right-inline">Leibfried A, To JPC, Busch W, Stehling S, Kehle A, Demar M, *et al.* WUSCHEL controls meristem function by direct regulation of cytokinin-inducible response regulators. *Nature* 2005;**438**:1172–5. <https://doi.org/10.1038/nature04270>.</span>

</div>

<div id="ref-kieffer_analysis_2006" class="csl-entry">

<span class="csl-left-margin">55 </span><span class="csl-right-inline">Kieffer M, Stern Y, Cook H, Clerici E, Maulbetsch C, Laux T, *et al.* Analysis of the transcription factor WUSCHEL and its functional homologue in Antirrhinum reveals a potential mechanism for their roles in meristem maintenance. *The Plant Cell* 2006;**18**:560–73. <https://doi.org/10.1105/tpc.105.039107>.</span>

</div>

<div id="ref-gordon_multiple_2009" class="csl-entry">

<span class="csl-left-margin">56 </span><span class="csl-right-inline">Gordon SP, Chickarmane VS, Ohno C, Meyerowitz EM. Multiple feedback loops through cytokinin signaling control stem cell number within the Arabidopsis shoot meristem. *Proceedings of the National Academy of Sciences* 2009;**106**:16529–34. <https://doi.org/10.1073/pnas.0908122106>.</span>

</div>

<div id="ref-perales_threshold-dependent_2016" class="csl-entry">

<span class="csl-left-margin">57 </span><span class="csl-right-inline">Perales M, Rodriguez K, Snipes S, Yadav RK, Diaz-Mendoza M, Reddy GV. Threshold-dependent transcriptional discrimination underlies stem cell homeostasis. *Proceedings of the National Academy of Sciences of the United States of America* 2016;**113**:E6298–306. <https://doi.org/10.1073/pnas.1607669113>.</span>

</div>

<div id="ref-rodriguez_dna-dependent_2016" class="csl-entry">

<span class="csl-left-margin">58 </span><span class="csl-right-inline">Rodriguez K, Perales M, Snipes S, Yadav RK, Diaz-Mendoza M, Reddy GV. DNA-dependent homodimerization, sub-cellular partitioning, and protein destabilization control WUSCHEL levels and spatial patterning. *Proceedings of the National Academy of Sciences of the United States of America* 2016;**113**:E6307–15. <https://doi.org/10.1073/pnas.1607673113>.</span>

</div>

<div id="ref-wang_cytokinin_2017" class="csl-entry">

<span class="csl-left-margin">59 </span><span class="csl-right-inline">Wang J, Tian C, Zhang C, Shi B, Cao X, Zhang T-Q, *et al.* Cytokinin Signaling Activates WUSCHEL Expression during Axillary Meristem Initiation. *The Plant Cell* 2017;**29**:1373–87. <https://doi.org/10.1105/tpc.16.00579>.</span>

</div>

<div id="ref-han_signal_2020" class="csl-entry">

<span class="csl-left-margin">60 </span><span class="csl-right-inline">Han H, Yan A, Li L, Zhu Y, Feng B, Liu X, *et al.* A signal cascade originated from epidermis defines apical-basal patterning of Arabidopsis shoot apical meristems. *Nature Communications* 2020;**11**:1214. <https://doi.org/10.1038/s41467-020-14989-4>.</span>

</div>

<div id="ref-plong_clavata3_2021" class="csl-entry">

<span class="csl-left-margin">61 </span><span class="csl-right-inline">Plong A, Rodriguez K, Alber M, Chen W, Reddy GV. CLAVATA3 mediated simultaneous control of transcriptional and post-translational processes provides robustness to the WUSCHEL gradient. *Nature Communications* 2021;**12**:6361. <https://doi.org/10.1038/s41467-021-26586-0>.</span>

</div>

<div id="ref-stuurman_shoot_2002" class="csl-entry">

<span class="csl-left-margin">62 </span><span class="csl-right-inline">Stuurman J, Jäggi F, Kuhlemeier C. Shoot meristem maintenance is controlled by a GRAS-gene mediated signal from differentiating cells. *Genes & Development* 2002;**16**:2213–8. <https://doi.org/10.1101/gad.230702>.</span>

</div>

<div id="ref-engstrom_arabidopsis_2011" class="csl-entry">

<span class="csl-left-margin">63 </span><span class="csl-right-inline">Engstrom EM, Andersen CM, Gumulak-Smith J, Hu J, Orlova E, Sozzani R, *et al.* Arabidopsis Homologs of the Petunia HAIRY MERISTEM Gene Are Required for Maintenance of Shoot and Root Indeterminacy. *Plant Physiology* 2011;**155**:735–50. <https://doi.org/10.1104/pp.110.168757>.</span>

</div>

<div id="ref-ni_evidence_2006" class="csl-entry">

<span class="csl-left-margin">64 </span><span class="csl-right-inline">Ni J, Clark SE. Evidence for functional conservation, sufficiency, and proteolytic processing of the CLAVATA3 CLE domain. *Plant Physiology* 2006;**140**:726–33. <https://doi.org/10.1104/pp.105.072678>.</span>

</div>

<div id="ref-kondo_plant_2006" class="csl-entry">

<span class="csl-left-margin">65 </span><span class="csl-right-inline">Kondo T, Sawa S, Kinoshita A, Mizuno S, Kakimoto T, Fukuda H, *et al.* A plant peptide encoded by CLV3 identified by in situ MALDI-TOF MS analysis. *Science (New York, NY)* 2006;**313**:845–8. <https://doi.org/10.1126/science.1128439>.</span>

</div>

<div id="ref-ohyama_glycopeptide_2009" class="csl-entry">

<span class="csl-left-margin">66 </span><span class="csl-right-inline">Ohyama K, Shinohara H, Ogawa-Ohnishi M, Matsubayashi Y. A glycopeptide regulating stem cell fate in Arabidopsis thaliana. *Nature Chemical Biology* 2009;**5**:578–80. <https://doi.org/10.1038/nchembio.182>.</span>

</div>

<div id="ref-somssich_clavata-wuschel_2016" class="csl-entry">

<span class="csl-left-margin">67 </span><span class="csl-right-inline">Somssich M, Je BI, Simon R, Jackson D. CLAVATA-WUSCHEL signaling in the shoot meristem. *Development* 2016;**143**:3238–48. <https://doi.org/10.1242/dev.133645>.</span>

</div>

<div id="ref-hirakawa_clavata3_2021" class="csl-entry">

<span class="csl-left-margin">68 </span><span class="csl-right-inline">Hirakawa Y. CLAVATA3, a plant peptide controlling stem cell fate in the meristem. *Peptides* 2021;**142**:170579. <https://doi.org/10.1016/j.peptides.2021.170579>.</span>

</div>

<div id="ref-lindsay_cytokinin-induced_2006" class="csl-entry">

<span class="csl-left-margin">69 </span><span class="csl-right-inline">Lindsay DL, Sawhney VK, Bonham-Smith PC. Cytokinin-induced changes in CLAVATA1 and WUSCHEL expression temporally coincide with altered floral development in Arabidopsis. *Plant Science* 2006;**170**:1111–7. <https://doi.org/10.1016/j.plantsci.2006.01.015>.</span>

</div>

<div id="ref-meng_type-b_2017" class="csl-entry">

<span class="csl-left-margin">70 </span><span class="csl-right-inline">Meng WJ, Cheng ZJ, Sang YL, Zhang MM, Rong XF, Wang ZW, *et al.* Type-B ARABIDOPSIS RESPONSE REGULATORs Specify the Shoot Stem Cell Niche by Dual Regulation of WUSCHEL. *The Plant Cell* 2017;**29**:1357–72. <https://doi.org/10.1105/tpc.16.00640>.</span>

</div>

<div id="ref-hwang_two-component_2001" class="csl-entry">

<span class="csl-left-margin">71 </span><span class="csl-right-inline">Hwang I, Sheen J. Two-component circuitry in Arabidopsis cytokinin signal transduction. *Nature* 2001;**413**:383–9. <https://doi.org/10.1038/35096500>.</span>

</div>

<div id="ref-hwang_two-component_2002" class="csl-entry">

<span class="csl-left-margin">72 </span><span class="csl-right-inline">Hwang I, Chen H-C, Sheen J. Two-Component Signal Transduction Pathways in Arabidopsis. *Plant Physiology* 2002;**129**:500–15. <https://doi.org/10.1104/pp.005504>.</span>

</div>

<div id="ref-zhou_structure_2024" class="csl-entry">

<span class="csl-left-margin">73 </span><span class="csl-right-inline">Zhou C-M, Li J-X, Zhang T-Q, Xu Z-G, Ma M-L, Zhang P, *et al.* The structure of B-ARR reveals the molecular basis of transcriptional activation by cytokinin. *Proceedings of the National Academy of Sciences* 2024;**121**:e2319335121. <https://doi.org/10.1073/pnas.2319335121>.</span>

</div>

<div id="ref-kim_phosphorylation_2008" class="csl-entry">

<span class="csl-left-margin">74 </span><span class="csl-right-inline">Kim J. [Phosphorylation of A-Type ARR to function as negative regulator of cytokinin signal transduction](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2634280). *Plant Signaling & Behavior* 2008;**3**:348–50.</span>

</div>

<div id="ref-kim_scfkmd_2013" class="csl-entry">

<span class="csl-left-margin">75 </span><span class="csl-right-inline">Kim HJ, Chiang Y-H, Kieber JJ, Schaller GE. SCF(KMD) controls cytokinin signaling by regulating the degradation of type-B response regulators. *Proceedings of the National Academy of Sciences of the United States of America* 2013;**110**:10028–33. <https://doi.org/10.1073/pnas.1300403110>.</span>

</div>

<div id="ref-kurepa_cytokinin_2014" class="csl-entry">

<span class="csl-left-margin">76 </span><span class="csl-right-inline">Kurepa J, Li Y, Smalle JA. Cytokinin signaling stabilizes the response activator ARR1. *The Plant Journal: For Cell and Molecular Biology* 2014;**78**:157–68. <https://doi.org/10.1111/tpj.12458>.</span>

</div>

<div id="ref-snipes_cytokinin_2018" class="csl-entry">

<span class="csl-left-margin">77 </span><span class="csl-right-inline">Snipes SA, Rodriguez K, DeVries AE, Miyawaki KN, Perales M, Xie M, *et al.* Cytokinin stabilizes WUSCHEL by acting on the protein domains required for nuclear enrichment and transcription. *PLoS Genetics* 2018;**14**:e1007351. <https://doi.org/10.1371/journal.pgen.1007351>.</span>

</div>

<div id="ref-barneoud_note_1846" class="csl-entry">

<span class="csl-left-margin">78 </span><span class="csl-right-inline">Barneoud FM. [Note on the Organogeny of Irregular corollas](http://archive.org/details/biostor-95114). *Annals And Magazine of Natural History* 1846;**18**:132–3.</span>

</div>

<div id="ref-friedman_charles_2011" class="csl-entry">

<span class="csl-left-margin">79 </span><span class="csl-right-inline">Friedman WE, Diggle PK. Charles Darwin and the Origins of Plant Evolutionary Developmental Biology. *The Plant Cell* 2011;**23**:1194–207. <https://doi.org/10.1105/tpc.111.084244>.</span>

</div>

<div id="ref-lowry_ecotypes_2012" class="csl-entry">

<span class="csl-left-margin">80 </span><span class="csl-right-inline">Lowry DB. Ecotypes and the controversy over stages in the formation of new species. *Biological Journal of the Linnean Society* 2012;**106**:241–57. <https://doi.org/10.1111/j.1095-8312.2012.01867.x>.</span>

</div>

<div id="ref-evert_raven_2013" class="csl-entry">

<span class="csl-left-margin">81 </span><span class="csl-right-inline">Evert RF, Eichhorn SE. *Raven Biology of Plants*. 8th ed. 41 Madison Avenue, New York, NY: W. H. Freeman; Company Publishers; 2013.</span>

</div>

<div id="ref-renner_relative_2014" class="csl-entry">

<span class="csl-left-margin">82 </span><span class="csl-right-inline">Renner SS. The relative and absolute frequencies of angiosperm sexual systems: Dioecy, monoecy, gynodioecy, and an updated online database. *American Journal of Botany* 2014;**101**:1588–96. <https://doi.org/10.3732/ajb.1400196>.</span>

</div>

<div id="ref-renner_dioecy_1995" class="csl-entry">

<span class="csl-left-margin">83 </span><span class="csl-right-inline">Renner SS, Ricklefs RE. Dioecy and its correlates in the flowering plants. *American Journal of Botany* 1995;**82**:596–606. <https://doi.org/10.1002/j.1537-2197.1995.tb11504.x>.</span>

</div>

<div id="ref-carr_recent_2003" class="csl-entry">

<span class="csl-left-margin">84 </span><span class="csl-right-inline">Carr DE, Dudash MR. Recent approaches into the genetic basis of inbreeding depression in plants. *Philosophical Transactions of the Royal Society of London Series B, Biological Sciences* 2003;**358**:1071–84. <https://doi.org/10.1098/rstb.2003.1295>.</span>

</div>

<div id="ref-bateson_mendels_1902" class="csl-entry">

<span class="csl-left-margin">85 </span><span class="csl-right-inline">Bateson W. *[Mendel’s principles of heredity: A defence (with translation of Mendel’s original papers on Hybridization)](https://agris.fao.org/search/en/providers/122376/records/6474732679cbb2c2c1b30564)*. London, England: C. J. Clay & Sons, Cambridge University Press; 1902.</span>

</div>

<div id="ref-edwards_reginald_2012" class="csl-entry">

<span class="csl-left-margin">86 </span><span class="csl-right-inline">Edwards AWF. Reginald Crundall Punnett: First Arthur Balfour Professor of Genetics, Cambridge, 1912. *Genetics* 2012;**192**:3–13. <https://doi.org/10.1534/genetics.112.143552>.</span>

</div>

<div id="ref-newman_increased_1997" class="csl-entry">

<span class="csl-left-margin">87 </span><span class="csl-right-inline">Newman D, Pilson D. INCREASED PROBABILITY OF EXTINCTION DUE TO DECREASED GENETIC EFFECTIVE POPULATION SIZE: EXPERIMENTAL POPULATIONS OF CLARKIA PULCHELLA. *Evolution* 1997;**51**:354–62. <https://doi.org/10.1111/j.1558-5646.1997.tb02422.x>.</span>

</div>

<div id="ref-bierzychudek_spatial_1988" class="csl-entry">

<span class="csl-left-margin">88 </span><span class="csl-right-inline">Bierzychudek P, Eckhart V. Spatial Segregation of the Sexes of Dioecious Plants. *The American Naturalist* 1988;**132**:34–43. <https://doi.org/10.1086/284836>.</span>

</div>

<div id="ref-hultine_climate_2016" class="csl-entry">

<span class="csl-left-margin">89 </span><span class="csl-right-inline">Hultine KR, Grady KC, Wood TE, Shuster SM, Stella JC, Whitham TG. Climate change perils for dioecious plant species. *Nature Plants* 2016;**2**:16109. <https://doi.org/10.1038/nplants.2016.109>.</span>

</div>

<div id="ref-hiscock_different_2003" class="csl-entry">

<span class="csl-left-margin">90 </span><span class="csl-right-inline">Hiscock SJ, Tabah DA. The different mechanisms of sporophytic self–incompatibility. *Philosophical Transactions of the Royal Society of London Series B: Biological Sciences* 2003;**358**:1037–45. <https://doi.org/10.1098/rstb.2003.1297>.</span>

</div>

<div id="ref-tucker_inflorescence_1999" class="csl-entry">

<span class="csl-left-margin">91 </span><span class="csl-right-inline">Tucker SC, Grimes J. The inflorescence: Introduction. *The Botanical Review* 1999;**65**:303–16. <https://doi.org/10.1007/BF02857752>.</span>

</div>

<div id="ref-poethig_phase_2003" class="csl-entry">

<span class="csl-left-margin">92 </span><span class="csl-right-inline">Poethig RS. Phase change and the regulation of developmental timing in plants. *Science (New York, NY)* 2003;**301**:334–6. <https://doi.org/10.1126/science.1085328>.</span>

</div>

<div id="ref-fleming_formation_2005" class="csl-entry">

<span class="csl-left-margin">93 </span><span class="csl-right-inline">Fleming AJ. Formation of primordia and phyllotaxy. *Current Opinion in Plant Biology* 2005;**8**:53–8. <https://doi.org/10.1016/j.pbi.2004.11.013>.</span>

</div>

<div id="ref-palauqui_phyllotaxis_2011" class="csl-entry">

<span class="csl-left-margin">94 </span><span class="csl-right-inline">Palauqui J-C, Laufs P. Phyllotaxis: In search of the golden angle. *Current Biology* 2011;**21**:R502–504. <https://doi.org/10.1016/j.cub.2011.05.054>.</span>

</div>

<div id="ref-zotz_heteroblastyreview_2011" class="csl-entry">

<span class="csl-left-margin">95 </span><span class="csl-right-inline">Zotz G, Wilhelm K, Becker A. Heteroblasty—A Review. *The Botanical Review* 2011;**77**:109–51. <https://doi.org/10.1007/s12229-010-9062-8>.</span>

</div>

<div id="ref-diggle_modularity_2014" class="csl-entry">

<span class="csl-left-margin">96 </span><span class="csl-right-inline">Diggle PK. Modularity and intra-floral integration in metameric organisms: Plants are more than the sum of their parts. *Philosophical Transactions of the Royal Society B: Biological Sciences* 2014;**369**:20130253. <https://doi.org/10.1098/rstb.2013.0253>.</span>

</div>

<div id="ref-shimizu-sato_control_2001" class="csl-entry">

<span class="csl-left-margin">97 </span><span class="csl-right-inline">Shimizu-Sato S, Mori H. Control of Outgrowth and Dormancy in Axillary Buds. *Plant Physiology* 2001;**127**:1405–13. <https://doi.org/10.1104/pp.010841>.</span>

</div>

<div id="ref-horvath_knowing_2003" class="csl-entry">

<span class="csl-left-margin">98 </span><span class="csl-right-inline">Horvath DP, Anderson JV, Chao WS, Foley ME. Knowing when to grow: Signals regulating bud dormancy. *Trends in Plant Science* 2003;**8**:534–40. <https://doi.org/10.1016/j.tplants.2003.09.013>.</span>

</div>

<div id="ref-choa_current_2007" class="csl-entry">

<span class="csl-left-margin">99 </span><span class="csl-right-inline">Choa WS, Horvath DP, Foley ME, Anderson JV. [Current review on signals regulating dormancy in vegetative buds](https://www.ars.usda.gov/research/publications/publication/?seqNo115=201350). *International Journal of Plant Developmental Biology* 2007;**1**:49–56.</span>

</div>

<div id="ref-endress_disentangling_2010" class="csl-entry">

<span class="csl-left-margin">100 </span><span class="csl-right-inline">Endress PK. Disentangling confusions in inflorescence morphology: Patterns and diversity of reproductive shoot ramification in angiosperms. *Journal of Systematics and Evolution* 2010;**48**:225–39. <https://doi.org/10.1111/j.1759-6831.2010.00087.x>.</span>

</div>

<div id="ref-prusinkiewicz_evolution_2007" class="csl-entry">

<span class="csl-left-margin">101 </span><span class="csl-right-inline">Prusinkiewicz P, Erasmus Y, Lane B, Harder LD, Coen E. Evolution and development of inflorescence architectures. *Science (New York, NY)* 2007;**316**:1452–6. <https://doi.org/10.1126/science.1140429>.</span>

</div>

<div id="ref-harder_interplay_2013" class="csl-entry">

<span class="csl-left-margin">102 </span><span class="csl-right-inline">Harder LD, Prusinkiewicz P. The interplay between inflorescence development and function as the crucible of architectural diversity. *Annals of Botany* 2013;**112**:1477–93. <https://doi.org/10.1093/aob/mcs252>.</span>

</div>

<div id="ref-coen_war_1991" class="csl-entry">

<span class="csl-left-margin">103 </span><span class="csl-right-inline">Coen ES, Meyerowitz EM. The war of the whorls: Genetic interactions controlling flower development. *Nature* 1991;**353**:31–7. <https://doi.org/10.1038/353031a0>.</span>

</div>

<div id="ref-weigel_abcs_1994" class="csl-entry">

<span class="csl-left-margin">104 </span><span class="csl-right-inline">Weigel D, Meyerowitz EM. The ABCs of floral homeotic genes. *Cell* 1994;**78**:203–9. <https://doi.org/10.1016/0092-8674(94)90291-7>.</span>

</div>

<div id="ref-redei_supervital_1962" class="csl-entry">

<span class="csl-left-margin">105 </span><span class="csl-right-inline">Rédei GP. Supervital Mutants of Arabidopsis. *Genetics* 1962;**47**:443–60. <https://doi.org/10.1093/genetics/47.4.443>.</span>

</div>

<div id="ref-shindo_natural_2007" class="csl-entry">

<span class="csl-left-margin">106 </span><span class="csl-right-inline">Shindo C, Bernasconi G, Hardtke CS. Natural genetic variation in Arabidopsis: Tools, traits and prospects for evolutionary ecology. *Annals of Botany* 2007;**99**:1043–54. <https://doi.org/10.1093/aob/mcl281>.</span>

</div>

<div id="ref-huala_leafy_1992" class="csl-entry">

<span class="csl-left-margin">107 </span><span class="csl-right-inline">Huala E, Sussex IM. LEAFY Interacts with Floral Homeotic Genes to Regulate Arabidopsis Floral Development. *The Plant Cell* 1992;**4**:901–13. <https://doi.org/10.1105/tpc.4.8.901>.</span>

</div>

<div id="ref-weigel_leafy_1992" class="csl-entry">

<span class="csl-left-margin">108 </span><span class="csl-right-inline">Weigel D, Alvarez J, Smyth DR, Yanofsky MF, Meyerowitz EM. LEAFY controls floral meristem identity in Arabidopsis. *Cell* 1992;**69**:843–59. <https://doi.org/10.1016/0092-8674(92)90295-n>.</span>

</div>

<div id="ref-irish_function_1990" class="csl-entry">

<span class="csl-left-margin">109 </span><span class="csl-right-inline">Irish VF, Sussex IM. Function of the apetala-1 gene during Arabidopsis floral development. *The Plant Cell* 1990;**2**:741–53. <https://doi.org/10.1105/tpc.2.8.741>.</span>

</div>

<div id="ref-bowman_control_1993" class="csl-entry">

<span class="csl-left-margin">110 </span><span class="csl-right-inline">Bowman JL, Alvarez J, Weigel D, Meyerowitz EM, Smyth DR. Control of flower development in Arabidopsis thaliana by APETALA1 and interacting genes. *Development* 1993;**119**:721–43. <https://doi.org/10.1242/dev.119.3.721>.</span>

</div>

<div id="ref-shannon_mutation_1991" class="csl-entry">

<span class="csl-left-margin">111 </span><span class="csl-right-inline">Shannon S, Meeks-Wagner DR. A Mutation in the Arabidopsis TFL1 Gene Affects Inflorescence Meristem Development. *The Plant Cell* 1991;**3**:877–92. <https://doi.org/10.1105/tpc.3.9.877>.</span>

</div>

<div id="ref-alvarez_terminal_1992" class="csl-entry">

<span class="csl-left-margin">112 </span><span class="csl-right-inline">Alvarez J, Guli CL, Yu X-H, Smyth DR. Terminal flower: A gene affecting inflorescence development in Arabidopsis thaliana. *The Plant Journal* 1992;**2**:103–16. <https://doi.org/10.1111/j.1365-313X.1992.00103.x>.</span>

</div>

<div id="ref-smyth_how_2023" class="csl-entry">

<span class="csl-left-margin">113 </span><span class="csl-right-inline">Smyth DR. How flower development genes were identified using forward genetic screens in Arabidopsis thaliana. *Genetics* 2023;**224**:iyad102. <https://doi.org/10.1093/genetics/iyad102>.</span>

</div>

<div id="ref-shannon_genetic_1993" class="csl-entry">

<span class="csl-left-margin">114 </span><span class="csl-right-inline">Shannon S, Meeks-Wagner DR. Genetic Interactions That Regulate Inflorescence Development in Arabidopsis. *The Plant Cell* 1993;**5**:639–55. <https://doi.org/10.1105/tpc.5.6.639>.</span>

</div>

<div id="ref-jack_homeotic_1992" class="csl-entry">

<span class="csl-left-margin">115 </span><span class="csl-right-inline">Jack T, Brockman LL, Meyerowitz EM. The homeotic gene APETALA3 of Arabidopsis thaliana encodes a MADS box and is expressed in petals and stamens. *Cell* 1992;**68**:683–97. <https://doi.org/10.1016/0092-8674(92)90144-2>.</span>

</div>

<div id="ref-maizel_floral_2005" class="csl-entry">

<span class="csl-left-margin">116 </span><span class="csl-right-inline">Maizel A, Busch MA, Tanahashi T, Perkovic J, Kato M, Hasebe M, *et al.* The floral regulator LEAFY evolves by substitutions in the DNA binding domain. *Science (New York, NY)* 2005;**308**:260–3. <https://doi.org/10.1126/science.1108229>.</span>

</div>

<div id="ref-moyroud_leafy_2010" class="csl-entry">

<span class="csl-left-margin">117 </span><span class="csl-right-inline">Moyroud E, Kusters E, Monniaux M, Koes R, Parcy F. LEAFY blossoms. *Trends in Plant Science* 2010;**15**:346–52. <https://doi.org/10.1016/j.tplants.2010.03.007>.</span>

</div>

<div id="ref-mandel_molecular_1992" class="csl-entry">

<span class="csl-left-margin">118 </span><span class="csl-right-inline">Mandel MA, Gustafson-Brown C, Savidge B, Yanofsky MF. Molecular characterization of the Arabidopsis floral homeotic gene APETALA1. *Nature* 1992;**360**:273–7. <https://doi.org/10.1038/360273a0>.</span>

</div>

<div id="ref-parcy_genetic_1998" class="csl-entry">

<span class="csl-left-margin">119 </span><span class="csl-right-inline">Parcy F, Nilsson O, Busch MA, Lee I, Weigel D. A genetic framework for floral patterning. *Nature* 1998;**395**:561–6. <https://doi.org/10.1038/26903>.</span>

</div>

<div id="ref-wagner_transcriptional_1999" class="csl-entry">

<span class="csl-left-margin">120 </span><span class="csl-right-inline">Wagner D, Sablowski RW, Meyerowitz EM. Transcriptional activation of APETALA1 by LEAFY. *Science (New York, NY)* 1999;**285**:582–4. <https://doi.org/10.1126/science.285.5427.582>.</span>

</div>

<div id="ref-liljegren_interactions_1999" class="csl-entry">

<span class="csl-left-margin">121 </span><span class="csl-right-inline">Liljegren SJ, Gustafson-Brown C, Pinyopich A, Ditta GS, Yanofsky MF. Interactions among APETALA1, LEAFY, and TERMINAL FLOWER1 specify meristem fate. *The Plant Cell* 1999;**11**:1007–18. <https://doi.org/10.1105/tpc.11.6.1007>.</span>

</div>

<div id="ref-william_genomic_2004" class="csl-entry">

<span class="csl-left-margin">122 </span><span class="csl-right-inline">William DA, Su Y, Smith MR, Lu M, Baldwin DA, Wagner D. Genomic identification of direct target genes of LEAFY. *Proceedings of the National Academy of Sciences of the United States of America* 2004;**101**:1775–80. <https://doi.org/10.1073/pnas.0307842100>.</span>

</div>

<div id="ref-saddic_leafy_2006" class="csl-entry">

<span class="csl-left-margin">123 </span><span class="csl-right-inline">Saddic LA, Huvermann B, Bezhani S, Su Y, Winter CM, Kwon CS, *et al.* The LEAFY target LMI1 is a meristem identity regulator and acts together with LEAFY to regulate expression of CAULIFLOWER. *Development (Cambridge, England)* 2006;**133**:1673–82. <https://doi.org/10.1242/dev.02331>.</span>

</div>

<div id="ref-pastore_late_2011" class="csl-entry">

<span class="csl-left-margin">124 </span><span class="csl-right-inline">Pastore JJ, Limpuangthip A, Yamaguchi N, Wu M-F, Sang Y, Han S-K, *et al.* LATE MERISTEM IDENTITY2 acts together with LEAFY to activate APETALA1. *Development* 2011;**138**:3189–98. <https://doi.org/10.1242/dev.063073>.</span>

</div>

<div id="ref-busch_activation_1999" class="csl-entry">

<span class="csl-left-margin">125 </span><span class="csl-right-inline">Busch MA, Bomblies K, Weigel D. Activation of a floral homeotic gene in Arabidopsis. *Science (New York, NY)* 1999;**285**:585–7. <https://doi.org/10.1126/science.285.5427.585>.</span>

</div>

<div id="ref-lamb_regulation_2002" class="csl-entry">

<span class="csl-left-margin">126 </span><span class="csl-right-inline">Lamb RS, Hill TA, Tan QK-G, Irish VF. Regulation of APETALA3 floral homeotic gene expression by meristem identity genes. *Development (Cambridge, England)* 2002;**129**:2079–86. <https://doi.org/10.1242/dev.129.9.2079>.</span>

</div>

<div id="ref-weigel_developmental_1995" class="csl-entry">

<span class="csl-left-margin">127 </span><span class="csl-right-inline">Weigel D, Nilsson O. A developmental switch sufficient for flower initiation in diverse plants. *Nature* 1995;**377**:495–500. <https://doi.org/10.1038/377495a0>.</span>

</div>

<div id="ref-mandel_gene_1995" class="csl-entry">

<span class="csl-left-margin">128 </span><span class="csl-right-inline">Mandel MA, Yanofsky MF. A gene triggering flower formation in Arabidopsis. *Nature* 1995;**377**:522–4. <https://doi.org/10.1038/377522a0>.</span>

</div>

<div id="ref-rockwell_phytochrome_2006" class="csl-entry">

<span class="csl-left-margin">129 </span><span class="csl-right-inline">Rockwell NC, Su Y-S, Lagarias JC. Phytochrome structure and signaling mechanisms. *Annual Review of Plant Biology* 2006;**57**:837–58. <https://doi.org/10.1146/annurev.arplant.56.032604.144208>.</span>

</div>

<div id="ref-quail_phytochromes_2010" class="csl-entry">

<span class="csl-left-margin">130 </span><span class="csl-right-inline">Quail PH. Phytochromes. *Current Biology* 2010;**20**:R504–507. <https://doi.org/10.1016/j.cub.2010.04.014>.</span>

</div>

<div id="ref-li_phytochrome_2011" class="csl-entry">

<span class="csl-left-margin">131 </span><span class="csl-right-inline">Li J, Li G, Wang H, Wang Deng X. Phytochrome Signaling Mechanisms. *The Arabidopsis Book* 2011;**9**:e0148. <https://doi.org/10.1199/tab.0148>.</span>

</div>

<div id="ref-ahmad_hy4_1993" class="csl-entry">

<span class="csl-left-margin">132 </span><span class="csl-right-inline">Ahmad M, Cashmore AR. HY4 gene of A. Thaliana encodes a protein with characteristics of a blue-light photoreceptor. *Nature* 1993;**366**:162–6. <https://doi.org/10.1038/366162a0>.</span>

</div>

<div id="ref-lin_association_1995" class="csl-entry">

<span class="csl-left-margin">133 </span><span class="csl-right-inline">Lin C, Robertson DE, Ahmad M, Raibekas AA, Jorns MS, Dutton PL, *et al.* Association of flavin adenine dinucleotide with the Arabidopsis blue light receptor CRY1. *Science (New York, NY)* 1995;**269**:968–70. <https://doi.org/10.1126/science.7638620>.</span>

</div>

<div id="ref-lin_expression_1995" class="csl-entry">

<span class="csl-left-margin">134 </span><span class="csl-right-inline">Lin C, Ahmad M, Gordon D, Cashmore AR. Expression of an Arabidopsis cryptochrome gene in transgenic tobacco results in hypersensitivity to blue, UV-A, and green light. *Proceedings of the National Academy of Sciences* 1995;**92**:8423–7. <https://doi.org/10.1073/pnas.92.18.8423>.</span>

</div>

<div id="ref-chaves_cryptochromes_2011" class="csl-entry">

<span class="csl-left-margin">135 </span><span class="csl-right-inline">Chaves I, Pokorny R, Byrdin M, Hoang N, Ritz T, Brettel K, *et al.* The cryptochromes: Blue light photoreceptors in plants and animals. *Annual Review of Plant Biology* 2011;**62**:335–64. <https://doi.org/10.1146/annurev-arplant-042110-103759>.</span>

</div>

<div id="ref-wang_mechanisms_2020" class="csl-entry">

<span class="csl-left-margin">136 </span><span class="csl-right-inline">Wang Q, Lin C. Mechanisms of Cryptochrome-Mediated Photoresponses in Plants. *Annual Review of Plant Biology* 2020;**71**:103–29. <https://doi.org/10.1146/annurev-arplant-050718-100300>.</span>

</div>

<div id="ref-sang_n-terminal_2005" class="csl-entry">

<span class="csl-left-margin">137 </span><span class="csl-right-inline">Sang Y, Li Q-H, Rubio V, Zhang Y-C, Mao J, Deng X-W, *et al.* N-terminal domain-mediated homodimerization is required for photoreceptor activity of Arabidopsis CRYPTOCHROME 1. *The Plant Cell* 2005;**17**:1569–84. <https://doi.org/10.1105/tpc.104.029645>.</span>

</div>

<div id="ref-wang_photoactivation_2016" class="csl-entry">

<span class="csl-left-margin">138 </span><span class="csl-right-inline">Wang Q, Zuo Z, Wang X, Gu L, Yoshizumi T, Yang Z, *et al.* Photoactivation and inactivation of Arabidopsis cryptochrome 2. *Science (New York, NY)* 2016;**354**:343–7. <https://doi.org/10.1126/science.aaf9030>.</span>

</div>

<div id="ref-shao_oligomeric_2020" class="csl-entry">

<span class="csl-left-margin">139 </span><span class="csl-right-inline">Shao K, Zhang X, Li X, Hao Y, Huang X, Ma M, *et al.* The oligomeric structures of plant cryptochromes. *Nature Structural & Molecular Biology* 2020;**27**:480–8. <https://doi.org/10.1038/s41594-020-0420-x>.</span>

</div>

<div id="ref-wang_direct_2001" class="csl-entry">

<span class="csl-left-margin">140 </span><span class="csl-right-inline">Wang H, Ma LG, Li JM, Zhao HY, Deng XW. Direct interaction of Arabidopsis cryptochromes with COP1 in light control development. *Science (New York, NY)* 2001;**294**:154–8. <https://doi.org/10.1126/science.1063630>.</span>

</div>

<div id="ref-yang_signaling_2001" class="csl-entry">

<span class="csl-left-margin">141 </span><span class="csl-right-inline">Yang HQ, Tang RH, Cashmore AR. The signaling mechanism of Arabidopsis CRY1 involves direct interaction with COP1. *The Plant Cell* 2001;**13**:2573–87. <https://doi.org/10.1105/tpc.010367>.</span>

</div>

<div id="ref-zuo_blue_2011" class="csl-entry">

<span class="csl-left-margin">142 </span><span class="csl-right-inline">Zuo Z, Liu H, Liu B, Liu X, Lin C. Blue light-dependent interaction of CRY2 with SPA1 regulates COP1 activity and floral initiation in Arabidopsis. *Current Biology* 2011;**21**:841–7. <https://doi.org/10.1016/j.cub.2011.03.048>.</span>

</div>

<div id="ref-podolec_photoreceptor-mediated_2018" class="csl-entry">

<span class="csl-left-margin">143 </span><span class="csl-right-inline">Podolec R, Ulm R. Photoreceptor-mediated regulation of the COP1/SPA E3 ubiquitin ligase. *Current Opinion in Plant Biology* 2018;**45**:18–25. <https://doi.org/10.1016/j.pbi.2018.04.018>.</span>

</div>

<div id="ref-liu_photoexcited_2008" class="csl-entry">

<span class="csl-left-margin">144 </span><span class="csl-right-inline">Liu H, Yu X, Li K, Klejnot J, Yang H, Lisiero D, *et al.* Photoexcited CRY2 interacts with CIB1 to regulate transcription and floral initiation in Arabidopsis. *Science (New York, NY)* 2008;**322**:1535–9. <https://doi.org/10.1126/science.1163927>.</span>

</div>

<div id="ref-shalitin_regulation_2002" class="csl-entry">

<span class="csl-left-margin">145 </span><span class="csl-right-inline">Shalitin D, Yang H, Mockler TC, Maymon M, Guo H, Whitelam GC, *et al.* Regulation of Arabidopsis cryptochrome 2 by blue-light-dependent phosphorylation. *Nature* 2002;**417**:763–7. <https://doi.org/10.1038/nature00815>.</span>

</div>

<div id="ref-shalitin_blue_2003" class="csl-entry">

<span class="csl-left-margin">146 </span><span class="csl-right-inline">Shalitin D, Yu X, Maymon M, Mockler T, Lin C. Blue light-dependent in vivo and in vitro phosphorylation of Arabidopsis cryptochrome 1. *The Plant Cell* 2003;**15**:2421–9. <https://doi.org/10.1105/tpc.013011>.</span>

</div>

<div id="ref-yu_arabidopsis_2007" class="csl-entry">

<span class="csl-left-margin">147 </span><span class="csl-right-inline">Yu X, Klejnot J, Zhao X, Shalitin D, Maymon M, Yang H, *et al.* Arabidopsis cryptochrome 2 completes its posttranslational life cycle in the nucleus. *The Plant Cell* 2007;**19**:3146–56. <https://doi.org/10.1105/tpc.107.053017>.</span>

</div>

<div id="ref-medzihradszky_phosphorylation_2013" class="csl-entry">

<span class="csl-left-margin">148 </span><span class="csl-right-inline">Medzihradszky M, Bindics J, Ádám É, Viczián A, Klement É, Lorrain S, *et al.* Phosphorylation of phytochrome B inhibits light-induced signaling via accelerated dark reversion in Arabidopsis. *The Plant Cell* 2013;**25**:535–44. <https://doi.org/10.1105/tpc.112.106898>.</span>

</div>

<div id="ref-nito_tyrosine_2013" class="csl-entry">

<span class="csl-left-margin">149 </span><span class="csl-right-inline">Nito K, Wong CCL, Yates JR, Chory J. Tyrosine phosphorylation regulates the activity of phytochrome photoreceptors. *Cell Reports* 2013;**3**:1970–9. <https://doi.org/10.1016/j.celrep.2013.05.006>.</span>

</div>

<div id="ref-muller_atp_2014" class="csl-entry">

<span class="csl-left-margin">150 </span><span class="csl-right-inline">Müller P, Bouly J-P, Hitomi K, Balland V, Getzoff ED, Ritz T, *et al.* ATP binding turns plant cryptochrome into an efficient natural photoswitch. *Scientific Reports* 2014;**4**:5175. <https://doi.org/10.1038/srep05175>.</span>

</div>

<div id="ref-liu_molecular_2017" class="csl-entry">

<span class="csl-left-margin">151 </span><span class="csl-right-inline">Liu Q, Wang Q, Deng W, Wang X, Piao M, Cai D, *et al.* Molecular basis for blue light-dependent phosphorylation of Arabidopsis cryptochrome 2. *Nature Communications* 2017;**8**:15234. <https://doi.org/10.1038/ncomms15234>.</span>

</div>

<div id="ref-choi_regulation_2023" class="csl-entry">

<span class="csl-left-margin">152 </span><span class="csl-right-inline">Choi D-M, Kim S-H, Han Y-J, Kim J-I. Regulation of Plant Photoresponses by Protein Kinase Activity of Phytochrome A. *International Journal of Molecular Sciences* 2023;**24**:2110. <https://doi.org/10.3390/ijms24032110>.</span>

</div>

<div id="ref-viczian_phytochrome_2024" class="csl-entry">

<span class="csl-left-margin">153 </span><span class="csl-right-inline">Viczián A, Nagy F. Phytochrome B phosphorylation expanded: Site-specific kinases are identified. *The New Phytologist* 2024;**241**:65–72. <https://doi.org/10.1111/nph.19314>.</span>

</div>

<div id="ref-abe_fd_2005" class="csl-entry">

<span class="csl-left-margin">154 </span><span class="csl-right-inline">Abe M, Kobayashi Y, Yamamoto S, Daimon Y, Yamaguchi A, Ikeda Y, *et al.* FD, a <span class="nocase">bZIP</span> protein mediating signals from the floral pathway integrator FT at the shoot apex. *Science (New York, NY)* 2005;**309**:1052–6. <https://doi.org/10.1126/science.1115983>.</span>

</div>

<div id="ref-wigge_integration_2005" class="csl-entry">

<span class="csl-left-margin">155 </span><span class="csl-right-inline">Wigge PA, Kim MC, Jaeger KE, Busch W, Schmid M, Lohmann JU, *et al.* Integration of Spatial and Temporal Information During Floral Induction in Arabidopsis. *Science* 2005;**309**:1056–9. <https://doi.org/10.1126/science.1114358>.</span>

</div>

<div id="ref-koornneef_genetic_1991" class="csl-entry">

<span class="csl-left-margin">156 </span><span class="csl-right-inline">Koornneef M, Hanhart CJ, Veen JH van der. A genetic and physiological analysis of late flowering mutants in Arabidopsis thaliana. *Molecular & General Genetics: MGG* 1991;**229**:57–66. <https://doi.org/10.1007/BF00264213>.</span>

</div>

<div id="ref-putterill_constans_1995" class="csl-entry">

<span class="csl-left-margin">157 </span><span class="csl-right-inline">Putterill J, Robson F, Lee K, Simon R, Coupland G. The CONSTANS gene of Arabidopsis promotes flowering and encodes a protein showing similarities to zinc finger transcription factors. *Cell* 1995;**80**:847–57. <https://doi.org/10.1016/0092-8674(95)90288-0>.</span>

</div>

<div id="ref-simon_activation_1996" class="csl-entry">

<span class="csl-left-margin">158 </span><span class="csl-right-inline">Simon R, Igeño MI, Coupland G. Activation of floral meristem identity genes in Arabidopsis. *Nature* 1996;**384**:59–62. <https://doi.org/10.1038/384059a0>.</span>

</div>

<div id="ref-kardailsky_activation_1999" class="csl-entry">

<span class="csl-left-margin">159 </span><span class="csl-right-inline">Kardailsky I, Shukla VK, Ahn JH, Dagenais N, Christensen SK, Nguyen JT, *et al.* Activation tagging of the floral inducer FT. *Science (New York, NY)* 1999;**286**:1962–5. <https://doi.org/10.1126/science.286.5446.1962>.</span>

</div>

<div id="ref-kobayashi_pair_1999" class="csl-entry">

<span class="csl-left-margin">160 </span><span class="csl-right-inline">Kobayashi Y, Kaya H, Goto K, Iwabuchi M, Araki T. A pair of related genes with antagonistic roles in mediating flowering signals. *Science (New York, NY)* 1999;**286**:1960–2. <https://doi.org/10.1126/science.286.5446.1960>.</span>

</div>

<div id="ref-onouchi_mutagenesis_2000" class="csl-entry">

<span class="csl-left-margin">161 </span><span class="csl-right-inline">Onouchi H, Igeño MI, Périlleux C, Graves K, Coupland G. Mutagenesis of plants overexpressing CONSTANS demonstrates novel interactions among Arabidopsis flowering-time genes. *The Plant Cell* 2000;**12**:885–900. <https://doi.org/10.1105/tpc.12.6.885>.</span>

</div>

<div id="ref-samach_distinct_2000" class="csl-entry">

<span class="csl-left-margin">162 </span><span class="csl-right-inline">Samach A, Onouchi H, Gold SE, Ditta GS, Schwarz-Sommer Z, Yanofsky MF, *et al.* Distinct roles of CONSTANS target genes in reproductive development of Arabidopsis. *Science (New York, NY)* 2000;**288**:1613–6. <https://doi.org/10.1126/science.288.5471.1613>.</span>

</div>

<div id="ref-suarez-lopez_constans_2001" class="csl-entry">

<span class="csl-left-margin">163 </span><span class="csl-right-inline">Suárez-López P, Wheatley K, Robson F, Onouchi H, Valverde F, Coupland G. CONSTANS mediates between the circadian clock and the control of flowering in Arabidopsis. *Nature* 2001;**410**:1116–20. <https://doi.org/10.1038/35074138>.</span>

</div>

<div id="ref-yanovsky_molecular_2002" class="csl-entry">

<span class="csl-left-margin">164 </span><span class="csl-right-inline">Yanovsky MJ, Kay SA. Molecular basis of seasonal time measurement in Arabidopsis. *Nature* 2002;**419**:308–12. <https://doi.org/10.1038/nature00996>.</span>

</div>

<div id="ref-yoo_constans_2005" class="csl-entry">

<span class="csl-left-margin">165 </span><span class="csl-right-inline">Yoo SK, Chung KS, Kim J, Lee JH, Hong SM, Yoo SJ, *et al.* CONSTANS activates SUPPRESSOR OF OVEREXPRESSION OF CONSTANS 1 through FLOWERING LOCUS T to promote flowering in Arabidopsis. *Plant Physiology* 2005;**139**:770–8. <https://doi.org/10.1104/pp.105.066928>.</span>

</div>

<div id="ref-an_constans_2004" class="csl-entry">

<span class="csl-left-margin">166 </span><span class="csl-right-inline">An H, Roussot C, Suárez-López P, Corbesier L, Vincent C, Piñeiro M, *et al.* CONSTANS acts in the phloem to regulate a systemic signal that induces photoperiodic flowering of Arabidopsis. *Development (Cambridge, England)* 2004;**131**:3615–26. <https://doi.org/10.1242/dev.01231>.</span>

</div>

<div id="ref-corbesier_ft_2007" class="csl-entry">

<span class="csl-left-margin">167 </span><span class="csl-right-inline">Corbesier L, Vincent C, Jang S, Fornara F, Fan Q, Searle I, *et al.* FT protein movement contributes to long-distance signaling in floral induction of Arabidopsis. *Science (New York, NY)* 2007;**316**:1030–3. <https://doi.org/10.1126/science.1141752>.</span>

</div>

<div id="ref-jaeger_ft_2007" class="csl-entry">

<span class="csl-left-margin">168 </span><span class="csl-right-inline">Jaeger KE, Wigge PA. FT protein acts as a long-range signal in Arabidopsis. *Current Biology* 2007;**17**:1050–4. <https://doi.org/10.1016/j.cub.2007.05.008>.</span>

</div>

<div id="ref-mathieu_export_2007" class="csl-entry">

<span class="csl-left-margin">169 </span><span class="csl-right-inline">Mathieu J, Warthmann N, Küttner F, Schmid M. Export of FT protein from phloem companion cells is sufficient for floral induction in Arabidopsis. *Current Biology* 2007;**17**:1055–60. <https://doi.org/10.1016/j.cub.2007.05.009>.</span>

</div>

<div id="ref-tamaki_hd3a_2007" class="csl-entry">

<span class="csl-left-margin">170 </span><span class="csl-right-inline">Tamaki S, Matsuo S, Wong HL, Yokoi S, Shimamoto K. Hd3a protein is a mobile flowering signal in rice. *Science (New York, NY)* 2007;**316**:1033–6. <https://doi.org/10.1126/science.1141753>.</span>

</div>

<div id="ref-liu_ftip1_2012" class="csl-entry">

<span class="csl-left-margin">171 </span><span class="csl-right-inline">Liu L, Liu C, Hou X, Xi W, Shen L, Tao Z, *et al.* FTIP1 is an essential regulator required for florigen transport. *PLoS Biology* 2012;**10**:e1001313. <https://doi.org/10.1371/journal.pbio.1001313>.</span>

</div>

<div id="ref-zhu_nakr1_2016" class="csl-entry">

<span class="csl-left-margin">172 </span><span class="csl-right-inline">Zhu Y, Liu L, Shen L, Yu H. NaKR1 regulates long-distance movement of FLOWERING LOCUS T in Arabidopsis. *Nature Plants* 2016;**2**:16075. <https://doi.org/10.1038/nplants.2016.75>.</span>

</div>

<div id="ref-abe_fe_2015" class="csl-entry">

<span class="csl-left-margin">173 </span><span class="csl-right-inline">Abe M, Kaya H, Watanabe-Taneda A, Shibuta M, Yamaguchi A, Sakamoto T, *et al.* FE, a phloem-specific Myb-related protein, promotes flowering through transcriptional activation of FLOWERING LOCUS T and FLOWERING LOCUS T INTERACTING PROTEIN 1. *The Plant Journal: For Cell and Molecular Biology* 2015;**83**:1059–68. <https://doi.org/10.1111/tpj.12951>.</span>

</div>

<div id="ref-fowler_gigantea_1999" class="csl-entry">

<span class="csl-left-margin">174 </span><span class="csl-right-inline">Fowler S, Lee K, Onouchi H, Samach A, Richardson K, Morris B, *et al.* GIGANTEA: A circadian clock-controlled gene that regulates photoperiodic flowering in Arabidopsis and encodes a protein with several possible membrane-spanning domains. *The EMBO Journal* 1999;**18**:4679–88. <https://doi.org/10.1093/emboj/18.17.4679>.</span>

</div>

<div id="ref-park_control_1999" class="csl-entry">

<span class="csl-left-margin">175 </span><span class="csl-right-inline">Park DH, Somers DE, Kim YS, Choy YH, Lim HK, Soh MS, *et al.* Control of circadian rhythms and photoperiodic flowering by the Arabidopsis GIGANTEA gene. *Science (New York, NY)* 1999;**285**:1579–82. <https://doi.org/10.1126/science.285.5433.1579>.</span>

</div>

<div id="ref-koornneef_genetic_1980" class="csl-entry">

<span class="csl-left-margin">176 </span><span class="csl-right-inline">Koornneef M, Rolff E, Spruit CJP. Genetic Control of Light-inhibited Hypocotyl Elongation in *Arabidopsis thaliana* (L.) Heynh. *Zeitschrift Für Pflanzenphysiologie* 1980;**100**:147–60. <https://doi.org/10.1016/S0044-328X(80)80208-X>.</span>

</div>

<div id="ref-schaffer_late_1998" class="csl-entry">

<span class="csl-left-margin">177 </span><span class="csl-right-inline">Schaffer R, Ramsay N, Samach A, Corden S, Putterill J, Carré IA, *et al.* The late elongated hypocotyl mutation of Arabidopsis disrupts circadian rhythms and the photoperiodic control of flowering. *Cell* 1998;**93**:1219–29. <https://doi.org/10.1016/s0092-8674(00)81465-8>.</span>

</div>

<div id="ref-wang_constitutive_1998" class="csl-entry">

<span class="csl-left-margin">178 </span><span class="csl-right-inline">Wang ZY, Tobin EM. Constitutive expression of the CIRCADIAN CLOCK ASSOCIATED 1 (CCA1) gene disrupts circadian rhythms and suppresses its own expression. *Cell* 1998;**93**:1207–17. <https://doi.org/10.1016/s0092-8674(00)81464-6>.</span>

</div>

<div id="ref-turck_regulation_2008" class="csl-entry">

<span class="csl-left-margin">179 </span><span class="csl-right-inline">Turck F, Fornara F, Coupland G. Regulation and identity of florigen: FLOWERING LOCUS T moves center stage. *Annual Review of Plant Biology* 2008;**59**:573–94. <https://doi.org/10.1146/annurev.arplant.59.032607.092755>.</span>

</div>

<div id="ref-guo_regulation_1998" class="csl-entry">

<span class="csl-left-margin">180 </span><span class="csl-right-inline">Guo H, Yang H, Mockler TC, Lin C. Regulation of flowering time by Arabidopsis photoreceptors. *Science (New York, NY)* 1998;**279**:1360–3. <https://doi.org/10.1126/science.279.5355.1360>.</span>

</div>

<div id="ref-el-din_el-assal_qtl_2001" class="csl-entry">

<span class="csl-left-margin">181 </span><span class="csl-right-inline">El-Din El-Assal S, Alonso-Blanco C, Peeters AJ, Raz V, Koornneef M. A QTL for flowering time in Arabidopsis reveals a novel allele of CRY2. *Nature Genetics* 2001;**29**:435–40. <https://doi.org/10.1038/ng767>.</span>

</div>

<div id="ref-cerdan_regulation_2003" class="csl-entry">

<span class="csl-left-margin">182 </span><span class="csl-right-inline">Cerdán PD, Chory J. Regulation of flowering time by light quality. *Nature* 2003;**423**:881–5. <https://doi.org/10.1038/nature01636>.</span>

</div>

<div id="ref-valverde_photoreceptor_2004" class="csl-entry">

<span class="csl-left-margin">183 </span><span class="csl-right-inline">Valverde F, Mouradov A, Soppe W, Ravenscroft D, Samach A, Coupland G. Photoreceptor regulation of CONSTANS protein in photoperiodic flowering. *Science (New York, NY)* 2004;**303**:1003–6. <https://doi.org/10.1126/science.1091761>.</span>

</div>

<div id="ref-laubinger_arabidopsis_2006" class="csl-entry">

<span class="csl-left-margin">184 </span><span class="csl-right-inline">Laubinger S, Marchal V, Le Gourrierec J, Wenkel S, Adrian J, Jang S, *et al.* Arabidopsis SPA proteins regulate photoperiodic flowering and interact with the floral inducer CONSTANS to regulate its stability. *Development (Cambridge, England)* 2006;**133**:3213–22. <https://doi.org/10.1242/dev.02481>.</span>

</div>

<div id="ref-liu_cop1-mediated_2008" class="csl-entry">

<span class="csl-left-margin">185 </span><span class="csl-right-inline">Liu L-J, Zhang Y-C, Li Q-H, Sang Y, Mao J, Lian H-L, *et al.* COP1-mediated ubiquitination of CONSTANS is implicated in cryptochrome regulation of flowering in Arabidopsis. *The Plant Cell* 2008;**20**:292–306. <https://doi.org/10.1105/tpc.107.057281>.</span>

</div>

<div id="ref-lian_blue-light-dependent_2011" class="csl-entry">

<span class="csl-left-margin">186 </span><span class="csl-right-inline">Lian H-L, He S-B, Zhang Y-C, Zhu D-M, Zhang J-Y, Jia K-P, *et al.* Blue-light-dependent interaction of cryptochrome 1 with SPA1 defines a dynamic signaling mechanism. *Genes & Development* 2011;**25**:1023–8. <https://doi.org/10.1101/gad.2025111>.</span>

</div>

<div id="ref-wang_crybic_2017" class="csl-entry">

<span class="csl-left-margin">187 </span><span class="csl-right-inline">Wang X, Wang Q, Han Y-J, Liu Q, Gu L, Yang Z, *et al.* A CRY–BIC negative-feedback circuitry regulating blue light sensitivity of Arabidopsis. *The Plant Journal* 2017;**92**:426–36. <https://doi.org/10.1111/tpj.13664>.</span>

</div>

<div id="ref-goethe_versuch_1790" class="csl-entry">

<span class="csl-left-margin">188 </span><span class="csl-right-inline">Goethe JW von. *[Versuch die Metamorphose der Pflanzen zu erklären](https://agris.fao.org/search/en/providers/122376/records/65119f618ed6443ca193be3e)*. bey Carl Wilhelm Ettinger; 1790.</span>

</div>

<div id="ref-niklas_evolutionary_2009" class="csl-entry">

<span class="csl-left-margin">189 </span><span class="csl-right-inline">Niklas KJ, Kutschera U. The evolutionary development of plant body plans. *Functional Plant Biology* 2009;**36**:682–95. <https://doi.org/10.1071/FP09107>.</span>

</div>

<div id="ref-ma_agl1-agl6_1991" class="csl-entry">

<span class="csl-left-margin">190 </span><span class="csl-right-inline">Ma H, Yanofsky MF, Meyerowitz EM. AGL1-AGL6, an Arabidopsis gene family with similarity to floral homeotic and transcription factor genes. *Genes & Development* 1991;**5**:484–95. <https://doi.org/10.1101/gad.5.3.484>.</span>

</div>

<div id="ref-huang_arabidopsis_1995" class="csl-entry">

<span class="csl-left-margin">191 </span><span class="csl-right-inline">Huang H, Tudor M, Weiss CA, Hu Y, Ma H. The Arabidopsis MADS-box gene AGL3 is widely expressed and encodes a sequence-specific DNA-binding protein. *Plant Molecular Biology* 1995;**28**:549–67. <https://doi.org/10.1007/BF00020401>.</span>

</div>

<div id="ref-pelaz_b_2000" class="csl-entry">

<span class="csl-left-margin">192 </span><span class="csl-right-inline">Pelaz S, Ditta GS, Baumann E, Wisman E, Yanofsky MF. B and C floral organ identity functions require SEPALLATA MADS-box genes. *Nature* 2000;**405**:200–3. <https://doi.org/10.1038/35012103>.</span>

</div>

<div id="ref-honma_complexes_2001" class="csl-entry">

<span class="csl-left-margin">193 </span><span class="csl-right-inline">Honma T, Goto K. Complexes of MADS-box proteins are sufficient to convert leaves into floral organs. *Nature* 2001;**409**:525–9. <https://doi.org/10.1038/35054083>.</span>

</div>

<div id="ref-pelaz_conversion_2001" class="csl-entry">

<span class="csl-left-margin">194 </span><span class="csl-right-inline">Pelaz S, Tapia-López R, Alvarez-Buylla ER, Yanofsky MF. Conversion of leaves into petals in Arabidopsis. *Current Biology* 2001;**11**:182–4. <https://doi.org/10.1016/s0960-9822(01)00024-0>.</span>

</div>

<div id="ref-ditta_sep4_2004" class="csl-entry">

<span class="csl-left-margin">195 </span><span class="csl-right-inline">Ditta G, Pinyopich A, Robles P, Pelaz S, Yanofsky MF. The SEP4 gene of Arabidopsis thaliana functions in floral organ and meristem identity. *Current Biology* 2004;**14**:1935–40. <https://doi.org/10.1016/j.cub.2004.10.028>.</span>

</div>

<div id="ref-alvarez_crabs_1999" class="csl-entry">

<span class="csl-left-margin">196 </span><span class="csl-right-inline">Alvarez J, Smyth DR. CRABS CLAW and SPATULA, two Arabidopsis genes that control carpel development in parallel with AGAMOUS. *Development (Cambridge, England)* 1999;**126**:2377–86. <https://doi.org/10.1242/dev.126.11.2377>.</span>

</div>

<div id="ref-favaro_mads-box_2003" class="csl-entry">

<span class="csl-left-margin">197 </span><span class="csl-right-inline">Favaro R, Pinyopich A, Battaglia R, Kooiker M, Borghi L, Ditta G, *et al.* MADS-box protein complexes control carpel and ovule development in Arabidopsis. *The Plant Cell* 2003;**15**:2603–11. <https://doi.org/10.1105/tpc.015123>.</span>

</div>

<div id="ref-pinyopich_assessing_2003" class="csl-entry">

<span class="csl-left-margin">198 </span><span class="csl-right-inline">Pinyopich A, Ditta GS, Savidge B, Liljegren SJ, Baumann E, Wisman E, *et al.* Assessing the redundancy of MADS-box genes during carpel and ovule development. *Nature* 2003;**424**:85–8. <https://doi.org/10.1038/nature01741>.</span>

</div>

<div id="ref-finzi_measurement_1995" class="csl-entry">

<span class="csl-left-margin">199 </span><span class="csl-right-inline">Finzi L, Gelles J. Measurement of lactose repressor-mediated loop formation and breakdown in single DNA molecules. *Science (New York, NY)* 1995;**267**:378–80. <https://doi.org/10.1126/science.7824935>.</span>

</div>

<div id="ref-zurla_direct_2009" class="csl-entry">

<span class="csl-left-margin">200 </span><span class="csl-right-inline">Zurla C, Manzo C, Dunlap D, Lewis DEA, Adhya S, Finzi L. Direct demonstration and quantification of long-range DNA looping by the lambda bacteriophage repressor. *Nucleic Acids Research* 2009;**37**:2789–95. <https://doi.org/10.1093/nar/gkp134>.</span>

</div>

<div id="ref-mendes_mads_2013" class="csl-entry">

<span class="csl-left-margin">201 </span><span class="csl-right-inline">Mendes MA, Guerra RF, Berns MC, Manzo C, Masiero S, Finzi L, *et al.* MADS domain transcription factors mediate short-range DNA looping that is essential for target gene expression in Arabidopsis. *The Plant Cell* 2013;**25**:2560–72. <https://doi.org/10.1105/tpc.112.108688>.</span>

</div>

<div id="ref-fan_specific_1997" class="csl-entry">

<span class="csl-left-margin">202 </span><span class="csl-right-inline">Fan HY, Hu Y, Tudor M, Ma H. Specific interactions between the K domains of AG and AGLs, members of the MADS domain family of DNA binding proteins. *The Plant Journal: For Cell and Molecular Biology* 1997;**12**:999–1010. <https://doi.org/10.1046/j.1365-313x.1997.12050999.x>.</span>

</div>

<div id="ref-immink_sepallata3_2009" class="csl-entry">

<span class="csl-left-margin">203 </span><span class="csl-right-inline">Immink RG, Tonaco IA, Folter S de, Shchennikova A, Dijk AD van, Busscher-Lange J, *et al.* SEPALLATA3: The ’glue’ for MADS box transcription factor complex formation. *Genome Biology* 2009;**10**:R24. <https://doi.org/10.1186/gb-2009-10-2-r24>.</span>

</div>

<div id="ref-smaczniak_characterization_2012" class="csl-entry">

<span class="csl-left-margin">204 </span><span class="csl-right-inline">Smaczniak C, Immink RGH, Muiño JM, Blanvillain R, Busscher M, Busscher-Lange J, *et al.* Characterization of MADS-domain transcription factor complexes in Arabidopsis flower development. *Proceedings of the National Academy of Sciences* 2012;**109**:1560–5. <https://doi.org/10.1073/pnas.1112871109>.</span>

</div>

<div id="ref-jetha_arabidopsis_2014" class="csl-entry">

<span class="csl-left-margin">205 </span><span class="csl-right-inline">Jetha K, Theißen G, Melzer R. Arabidopsis SEPALLATA proteins differ in cooperative DNA-binding during the formation of floral quartet-like complexes. *Nucleic Acids Research* 2014;**42**:10927–42. <https://doi.org/10.1093/nar/gku755>.</span>

</div>

<div id="ref-puranik_structural_2014" class="csl-entry">

<span class="csl-left-margin">206 </span><span class="csl-right-inline">Puranik S, Acajjaoui S, Conn S, Costa L, Conn V, Vial A, *et al.* Structural basis for the oligomerization of the MADS domain transcription factor SEPALLATA3 in Arabidopsis. *The Plant Cell* 2014;**26**:3603–15. <https://doi.org/10.1105/tpc.114.127910>.</span>

</div>

<div id="ref-hugouvieux_sepallata-driven_2024" class="csl-entry">

<span class="csl-left-margin">207 </span><span class="csl-right-inline">Hugouvieux V, Blanc-Mathieu R, Janeau A, Paul M, Lucas J, Xu X, *et al.* SEPALLATA-driven MADS transcription factor tetramerization is required for inner whorl floral organ development. *The Plant Cell* 2024;**36**:3435–50. <https://doi.org/10.1093/plcell/koae151>.</span>

</div>

<div id="ref-kaufmann_target_2009" class="csl-entry">

<span class="csl-left-margin">208 </span><span class="csl-right-inline">Kaufmann K, Muiño JM, Jauregui R, Airoldi CA, Smaczniak C, Krajewski P, *et al.* Target genes of the MADS transcription factor SEPALLATA3: Integration of developmental and hormonal pathways in the Arabidopsis flower. *PLoS Biology* 2009;**7**:e1000090. <https://doi.org/10.1371/journal.pbio.1000090>.</span>

</div>

<div id="ref-pajoro_dynamics_2014" class="csl-entry">

<span class="csl-left-margin">209 </span><span class="csl-right-inline">Pajoro A, Madrigal P, Muiño JM, Matus JT, Jin J, Mecchia MA, *et al.* Dynamics of chromatin accessibility and gene regulation by MADS-domain transcription factors in flower development. *Genome Biology* 2014;**15**:R41. <https://doi.org/10.1186/gb-2014-15-3-r41>.</span>

</div>

<div id="ref-sommer_deficiens_1990" class="csl-entry">

<span class="csl-left-margin">210 </span><span class="csl-right-inline">Sommer H, Beltrán JP, Huijser P, Pape H, Lönnig WE, Saedler H, *et al.* Deficiens, a homeotic gene involved in the control of flower morphogenesis in Antirrhinum majus: The protein shows homology to transcription factors. *The EMBO Journal* 1990;**9**:605–13. <https://doi.org/10.1002/j.1460-2075.1990.tb08152.x>.</span>

</div>

<div id="ref-becker_major_2003" class="csl-entry">

<span class="csl-left-margin">211 </span><span class="csl-right-inline">Becker A, Theissen G. The major clades of MADS-box genes and their role in the development and evolution of flowering plants. *Molecular Phylogenetics and Evolution* 2003;**29**:464–89. <https://doi.org/10.1016/s1055-7903(03)00207-0>.</span>

</div>

<div id="ref-parenicova_molecular_2003" class="csl-entry">

<span class="csl-left-margin">212 </span><span class="csl-right-inline">Parenicová L, Folter S de, Kieffer M, Horner DS, Favalli C, Busscher J, *et al.* Molecular and phylogenetic analyses of the complete MADS-box transcription factor family in Arabidopsis: New openings to the MADS world. *The Plant Cell* 2003;**15**:1538–51. <https://doi.org/10.1105/tpc.011544>.</span>

</div>

<div id="ref-kaufmann_mikc-type_2005" class="csl-entry">

<span class="csl-left-margin">213 </span><span class="csl-right-inline">Kaufmann K, Melzer R, Theissen G. MIKC-type MADS-domain proteins: Structural modularity, protein interactions and network evolution in land plants. *Gene* 2005;**347**:183–98. <https://doi.org/10.1016/j.gene.2004.12.014>.</span>

</div>

<div id="ref-riechmann_dimerization_1996" class="csl-entry">

<span class="csl-left-margin">214 </span><span class="csl-right-inline">Riechmann JL, Krizek BA, Meyerowitz EM. Dimerization specificity of Arabidopsis MADS domain homeotic proteins APETALA1, APETALA3, PISTILLATA, and AGAMOUS. *Proceedings of the National Academy of Sciences of the United States of America* 1996;**93**:4793–8. <https://doi.org/10.1073/pnas.93.10.4793>.</span>

</div>

<div id="ref-riechmann_dna-binding_1996" class="csl-entry">

<span class="csl-left-margin">215 </span><span class="csl-right-inline">Riechmann JL, Wang M, Meyerowitz EM. DNA-binding properties of Arabidopsis MADS domain homeotic proteins APETALA1, APETALA3, PISTILLATA and AGAMOUS. *Nucleic Acids Research* 1996;**24**:3134–41. <https://doi.org/10.1093/nar/24.16.3134>.</span>

</div>

<div id="ref-lai_intervening_2021" class="csl-entry">

<span class="csl-left-margin">216 </span><span class="csl-right-inline">Lai X, Vega-Léon R, Hugouvieux V, Blanc-Mathieu R, Wal F van der, Lucas J, *et al.* The intervening domain is required for DNA-binding and functional identity of plant MADS transcription factors. *Nature Communications* 2021;**12**:4760. <https://doi.org/10.1038/s41467-021-24978-w>.</span>

</div>

<div id="ref-yang_k_2003" class="csl-entry">

<span class="csl-left-margin">217 </span><span class="csl-right-inline">Yang Y, Fanning L, Jack T. The K domain mediates heterodimerization of the Arabidopsis floral organ identity proteins, APETALA3 and PISTILLATA. *The Plant Journal: For Cell and Molecular Biology* 2003;**33**:47–59. <https://doi.org/10.1046/j.0960-7412.2003.01473.x>.</span>

</div>

<div id="ref-yang_defining_2004" class="csl-entry">

<span class="csl-left-margin">218 </span><span class="csl-right-inline">Yang Y, Jack T. Defining subdomains of the K domain important for protein-protein interactions of plant MADS proteins. *Plant Molecular Biology* 2004;**55**:45–59. <https://doi.org/10.1007/s11103-004-0416-7>.</span>

</div>

<div id="ref-melzer_reconstitution_2009" class="csl-entry">

<span class="csl-left-margin">219 </span><span class="csl-right-inline">Melzer R, Theissen G. Reconstitution of ’floral quartets’ in vitro involving class B and class E floral homeotic proteins. *Nucleic Acids Research* 2009;**37**:2723–36. <https://doi.org/10.1093/nar/gkp129>.</span>

</div>

<div id="ref-rumpler_conserved_2018" class="csl-entry">

<span class="csl-left-margin">220 </span><span class="csl-right-inline">Rümpler F, Theißen G, Melzer R. A conserved leucine zipper-like motif accounts for strong tetramerization capabilities of SEPALLATA-like MADS-domain transcription factors. *Journal of Experimental Botany* 2018;**69**:1943–54. <https://doi.org/10.1093/jxb/ery063>.</span>

</div>

<div id="ref-lai_genome-wide_2020" class="csl-entry">

<span class="csl-left-margin">221 </span><span class="csl-right-inline">Lai X, Stigliani A, Lucas J, Hugouvieux V, Parcy F, Zubieta C. Genome-wide binding of SEPALLATA3 and AGAMOUS complexes determined by sequential DNA-affinity purification sequencing. *Nucleic Acids Research* 2020;**48**:9637–48. <https://doi.org/10.1093/nar/gkaa729>.</span>

</div>

<div id="ref-landschulz_leucine_1988" class="csl-entry">

<span class="csl-left-margin">222 </span><span class="csl-right-inline">Landschulz WH, Johnson PF, McKnight SL. The leucine zipper: A hypothetical structure common to a new class of DNA binding proteins. *Science (New York, NY)* 1988;**240**:1759–64. <https://doi.org/10.1126/science.3289117>.</span>

</div>

<div id="ref-liu_seven-helix_2006" class="csl-entry">

<span class="csl-left-margin">223 </span><span class="csl-right-inline">Liu J, Zheng Q, Deng Y, Cheng C-S, Kallenbach NR, Lu M. A seven-helix coiled coil. *Proceedings of the National Academy of Sciences* 2006;**103**:15457–62. <https://doi.org/10.1073/pnas.0604871103>.</span>

</div>

<div id="ref-wu_swi2snf2_2012" class="csl-entry">

<span class="csl-left-margin">224 </span><span class="csl-right-inline">Wu M-F, Sang Y, Bezhani S, Yamaguchi N, Han S-K, Li Z, *et al.* SWI2/SNF2 chromatin remodeling ATPases overcome polycomb repression and control floral organ identity with the LEAFY and SEPALLATA3 transcription factors. *Proceedings of the National Academy of Sciences of the United States of America* 2012;**109**:3576–81. <https://doi.org/10.1073/pnas.1113409109>.</span>

</div>

<div id="ref-clapier_biology_2009" class="csl-entry">

<span class="csl-left-margin">225 </span><span class="csl-right-inline">Clapier CR, Cairns BR. The biology of chromatin remodeling complexes. *Annual Review of Biochemistry* 2009;**78**:273–304. <https://doi.org/10.1146/annurev.biochem.77.062706.153223>.</span>

</div>

<div id="ref-tang_structure_2010" class="csl-entry">

<span class="csl-left-margin">226 </span><span class="csl-right-inline">Tang L, Nogales E, Ciferri C. Structure and Function of SWI/SNF Chromatin Remodeling Complexes and Mechanistic Implications for Transcription. *Progress in Biophysics and Molecular Biology* 2010;**102**:122–8. <https://doi.org/10.1016/j.pbiomolbio.2010.05.001>.</span>

</div>

<div id="ref-urbanus_planta_2009" class="csl-entry">

<span class="csl-left-margin">227 </span><span class="csl-right-inline">Urbanus SL, Folter S de, Shchennikova AV, Kaufmann K, Immink RGH, Angenent GC. In planta localisation patterns of MADS domain proteins during floral development in Arabidopsis thaliana. *BMC Plant Biology* 2009;**9**:5. <https://doi.org/10.1186/1471-2229-9-5>.</span>

</div>

<div id="ref-theissen_plant_2001" class="csl-entry">

<span class="csl-left-margin">228 </span><span class="csl-right-inline">Theissen G, Saedler H. Plant biology. Floral quartets. *Nature* 2001;**409**:469–71. <https://doi.org/10.1038/35054172>.</span>

</div>

<div id="ref-lai_structural_2019" class="csl-entry">

<span class="csl-left-margin">229 </span><span class="csl-right-inline">Lai X, Daher H, Galien A, Hugouvieux V, Zubieta C. Structural Basis for Plant MADS Transcription Factor Oligomerization. *Computational and Structural Biotechnology Journal* 2019;**17**:946–53. <https://doi.org/10.1016/j.csbj.2019.06.014>.</span>

</div>

<div id="ref-jin_leafy_2021" class="csl-entry">

<span class="csl-left-margin">230 </span><span class="csl-right-inline">Jin R, Klasfeld S, Zhu Y, Fernandez Garcia M, Xiao J, Han S-K, *et al.* LEAFY is a pioneer transcription factor and licenses cell reprogramming to floral fate. *Nature Communications* 2021;**12**:626. <https://doi.org/10.1038/s41467-020-20883-w>.</span>

</div>

<div id="ref-yamaguchi_leafy_2021" class="csl-entry">

<span class="csl-left-margin">231 </span><span class="csl-right-inline">Yamaguchi N. LEAFY, a Pioneer Transcription Factor in Plants: A Mini-Review. *Frontiers in Plant Science* 2021;**12**:701406. <https://doi.org/10.3389/fpls.2021.701406>.</span>

</div>

<div id="ref-pettersen_ucsf_2021" class="csl-entry">

<span class="csl-left-margin">232 </span><span class="csl-right-inline">Pettersen EF, Goddard TD, Huang CC, Meng EC, Couch GS, Croll TI, *et al.* UCSF ChimeraX: Structure visualization for researchers, educators, and developers. *Protein Science: A Publication of the Protein Society* 2021;**30**:70–82. <https://doi.org/10.1002/pro.3943>.</span>

</div>

</div>
