---
title: "Plant Natural Products"
subtitle: " "
excerpt: "Plant Natural Products (secondary metabolites) provide many essential ecosystem goods and services (e.g. food, medicine, pollination, UV protection, defence, etc.). This project takes a closer look at the biology and chemistry of some of these remarkable compounds."
date: 2023-04-07
author: "JCH"
featured: true
draft: false
tags:
- hugo-site
categories:
- Theme Features
- R
# layout options: single or single-sidebar
layout: single
links:
- icon: "door-open"
  icon_pack: fas
  name: PubChem
  url: https://pubchem.ncbi.nlm.nih.gov/
- icon: "door-open"
  icon_pack: fas
  name: "HHMI - Biointeractive"
  url: "https://www.biointeractive.org/classroom-resources/photosynthesis"
- icon: "door-open"
  icon_pack: fas
  name: Protein Data bank
  url: https://pdb101.rcsb.org/motm/59
- icon: "door-open"
  icon_pack: fas
  name: Royal Society Chemistry
  url: "https://www.chemistryworld.com/podcasts/frankincense-and-myrrh/8106.article"
- icon: "door-open"
  icon_pack: fas
  name: UCSF ChimeraX
  url: https://www.cgl.ucsf.edu/chimerax/
- icon: "door-open"
  icon_pack: fas
  name: Evolution 101
  url: "https://evolution.berkeley.edu/aposematic-animals/"
- icon: "door-open"
  icon_pack: fas
  name: ClinicalTrials.gov
  url: https://beta.clinicaltrials.gov/
- icon: "door-open"
  icon_pack: fas
  name: LibreText Chemistry
  url: https://chem.libretexts.org/
- icon: "door-open"
  icon_pack: fas
  name: NASA Education
  url: https://ozonewatch.gsfc.nasa.gov/education/index.html
- icon: "door-open"
  icon_pack: fas
  name: ICS
  url: https://stratigraphy.org/chart
- icon: "door-open"
  icon_pack: fas
  name: ChemistryTalk
  url: https://chemistrytalk.org/
- icon: "door-open"
  icon_pack: fas
  name: HyperPhysics
  url: "http://hyperphysics.phy-astr.gsu.edu/hbase/hph.html"
- icon: "door-open"
  icon_pack: fas
  name: James Lind Library
  url: https://www.jameslindlibrary.org/
- icon: "door-open"
  icon_pack: fas
  name: Science History Institute
  url: https://www.sciencehistory.org/
- icon: "door-open"
  icon_pack: fas
  name: NCI Dictionaries
  url: https://www.cancer.gov/publications/dictionaries
- icon: "door-open"
  icon_pack: fas
  name: "EMBL-EBI"
  url: https://www.ebi.ac.uk/
---

<style type="text/css">

/* ====================== */
/*  CSS for Photo/Figures */
/* ====================== */

figure {
  border: 2px solid;
  align: center;
  color: rgb(200, 200, 200);
  padding: 4px;
  margin: auto;
}

figcaption {
  color: black;
  padding: 2px;
  text-align: left;
}

.FRight100 {
  float: right;
  border: white;
  height: 100px;
  padding: 5px 5px 5px 5px;
  clear: right;
}

.FLeft100 {
  float: right;
  border: white;
  height: 100px;
  padding: 5px 5px 5px 5px;
  clear: right;
}

.FRight150 {
  float: right;
  border: white;
  height: 150px;
  padding: 5px 5px 5px 5px;
  clear: right;
}

.FRight180 {
  float: right;
  border: white;
  height: 180px;
  padding: 5px 5px 5px 5px;
  clear: right;
}

.FRight200 {
  float: right;
  border: white;
  height: 200px;
  padding: 5px 5px 5px 5px;
  clear: right;
}

/* ========================== */
/*         TABLE CSS          */
/* ========================== */

.Table {
  border-collapse: collapse;
  overflow: auto;
  width: 100%
  margin: 1px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.55);
}

.Table thead tr {
  border: 2px solid;
  padding: 1px;
  text-align: center;
  text: bold;
}

.Table thead th {
  border: 2px solid;
  text-align: center;
  text: bold;
  font-size: 24px;
}

.Table thead th.f18 {
  border: 2px solid;
  text-align: center;
  text: bold;
  font-size: 18px;
}

.Table tbody td {
  border: 2px solid;
  text-align: left;
  text: bold;
  font-size: 14px;
  background-color: white;
}

.Table tbody td.tmid {
  border: 2px solid;
  text-align: center;
  text: bold;
  font-size: 14px;
  background-color: white;
}

td:first-child + td { text-align: center; }

td:first-child + td + td.tcell { text-align: center; }

.Table tbody tr {
  border-bottom: 2px solid #dddddd;
}

.Table tbody tr:last-of-type {
  border-bottom: 2px solid #009879;
}

/* ============================= */
/*   CSS for Na Pump Animation   */
/* ============================= */

.cf {
  position: relative;
  height: 500px;
  width: 400px;
}

.cf img {
  position: absolute;
}

.top {
  animation-name: fade;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
  animation-duration: 6s;
  animation-direction: alternate;
}

@keyframes fade {
  0% {
    opacity: 1;
  }
  25% {
    opacity: 1;
  }
  75% {
    opacity: 0;
  }
  100% {
    opacity: 0;
  }
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

.head16 {
  color: black;
  font-weight: bold;
  font-size: 16px;
  text-align: center;
  }

#Blk20 {
  color: black;
  font-size: 20px;
  text-align: left;
  }

#BBlk {
  font-weight: bold;
  color: rgb(0, 0, 0);
  border: 2px solid black;
  margin: 1px;
  }

.Rborder {
  border-width:2px;
  border-style:solid;
  border-color: rgb(175, 0, 0);
}

#Blk { font-weight: bold; color: rgb(0, 0, 0); }
#Red { font-weight: bold; color: rgb(255, 10, 20); }
#Dred { font-weight: bold; color: rgb(175, 0, 0); }
#Lred { font-weight: bold; color: rgb(255, 200, 200); }
#Or { font-weight: bold; color: rgb(255, 140, 0); }
#Ror { font-weight: bold; color: rgb(255, 55, 0); }
#Gold { font-weight: bold; color: rgb(230, 190, 0); }
#Ly { font-weight: bold; color: rgb(255, 242, 150); }
#Gr { font-weight: bold; color: rgb(20, 160, 20) }
#Gr2 { font-weight: bold; color: rgb(25, 200, 25); }
#Gr3 { font-weight: bold; color: rgb(100, 200, 70); }
#Cop { font-weight: bold; color: rgb(100, 215, 175); }
#Fgr { font-weight: bold; color: rgb(20, 120, 20); }
#Turq { font-weight: bold; color: rgb(67, 198, 219); }
#Teal { font-weight: bold; color: rgb(0, 128, 128); }
#Seagr { font-weight: bold; color: rgb(78, 137, 117); }
#Blue { font-weight: bold; color: rgb(0, 0, 255); }
#Cfb { font-weight: bold; color: rgb(100, 149, 237); }
#Glacialb { font-weight: bold; color: rgb(54, 139, 193); }
#Glacialb2 { font-weight: bold; color: rgb(54, 139, 255); }
#Orchidb { font-weight: bold; color: rgb(31, 69, 252); }
#Db2 { font-weight: bold; color: rgb(0, 0, 100); }
#Lb { font-weight: bold; color: rgb(148, 202, 202); }
#Lb2 { font-weight: bold; color: rgb(100, 180, 255); }
#Lb3 { font-weight: bold; color: rgb(0, 132, 255); }
#V { font-weight: bold; color: rgb(180, 73, 255); }
#Purple { font-weight: bold; color: rgb(150, 0, 255); }
#Dpurp { font-weight: bold; color: rgb(95, 0, 161); }
#Magenta { font-weight: bold; color: rgb(255, 0, 255); }
#Coral { font-weight: bold; color: rgb(255, 127, 80); }
#Crim { font-weight: bold; color: rgb(220, 20, 60); }
#Rasp { font-weight: bold; color: rgb(227, 11, 92); }
#Lgray { font-weight: bold; color: rgb(190, 190, 190); }
#Gray { font-weight: bold; color: rgb(155, 155, 155); }
#Dgray { font-weight: bold; color: rgb(95, 95, 95); }
#Brown { font-weight: bold; color: rgb(165, 42, 42); }
#Rust { font-weight: bold; color: rgb(183, 65, 14); }
#Dbr { font-weight: bold; color: rgb(100, 20, 20); }
#OrRed { font-weight: bold; color: rgb(255, 70, 0); }
#OrRed2 { font-weight: bold; color: rgb(255, 100, 0); }
#BRed { font-weight: bold; color: rgb(170, 0, 255); }
#BRed2 { font-weight: bold; color: rgb(140, 0, 255); }
#GrY { font-weight: bold; color: rgb(190, 220, 0); }
#GrY2 { font-weight: bold; color: rgb(240, 240, 25); }
#GrY3 { font-weight: bold; color: rgb(240, 240, 5); }
</style>


<div align=center> </div>

<details>
  <summary><b>TABLE OF CONTENTS</b></summary>
  
  1. <a href="#PNP">Overview of Plant Natural Products (<span id="Gr">PNP</span>)</a>
     * <a href="#Fig_AcCoA"><b>Fig.1:</b> <span id="Red">Acetyl-CoA</span> Metabolism</a>
  2. <a href="#BB_PNP"><b>Section 1:</b> Building Blocks of <span id="Gr">PNP</span></a>
     * <a href="#Fig_OoL"><b>Fig. 2:</b> <span id="Red">Acetyl-CoA</span> & Origins of Life</a>
     * <a href="#Fig_PNP"><b>Fig. 3:</b> Biochemical Pathways of <span id="Gr">PNP</span></a>
  3. <a href="#Terp"><b>Section 2:</b> <span id="Dred">Terpenoids</span></a>
     * <a href="#Fig_Ret"><b>Fig. 4:</b> Retinoid Cycle</a>
     * <a href="#Fig_RA"><b>Fig. 5:</b> Retinoic Acid Signaling</a>
     * <a href="#Terp_Class"><b>Section 2.1:</b> Classes of <span id="Dred">Terpenoid</span></a>
     * <a href="#TerpTable"><b>Table. 1:</b> <span id="Dred">Terpenoids</span></a>
     * <a href="#NatRub"><b>Section 2.2:</b> Natural Rubber</a>
     * <a href="#Cgs"><b>Section 2.3:</b> Cardiac Glycosides (<span id="Blue">CG</span>)</a>
     * <a href="#CGTab"><b>Table 2:</b> Common <span id="Blue">CG</span></a>
     * <a href="#CGmech"><b>Section 2.3.1:</b> Mechanism of <span id="Blue">CG</span></a>
     * <a href="#Fig_NKA"><b>Fig. 6:</b> <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span><b>ase</b> structure</a>
     * <a href="#Fig_NKAcycle"><b>Fig. 7:</b> <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span><b>ase</b> Mechanism</a>
     * <a href="#Fig_NKAouabain"><b>Fig. 8:</b> Structure of Ouabain bound <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span><b>ase</b></a>
     * <a href="#Fig_NKAbs"><b>Fig. 9:</b> <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span><b>ase</b> &alpha;-subunit Multi-Sequence Alignment</a>
     * <a href="#Fig_NKAtree"><b>Fig. 10:</b> Phylogenetic Tree of Insect <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span><b>ase</b></a>
     * <a href="#CGmed"><b>Section 2.3.2:</b> Medical Application of <span id="Blue">CG</span></a>
  4. <a href="#Prot"><b>Section 3:</b> <span id="Dred">Proteases</span></a>
     * <a href="#Fig_SerProt"><b>Figure 11:</b> Serine <span id="Dred">Proteases</span></a>
     * <a href="#Prot_Func"><b>Section 3.1:</b> <span id="Dred">Protease Function</span></a>
     * <a href="#Prot_Table"><b>Table 3:</b> Plant Latex <span id="Dred">Proteases</span></a>  
  5. <a href="#Phenolics"><b>Section 4:</b> <span id="Dred">Phenolics</span></a>  
     * <a href="#Phen_Class"><b>Section 4.1:</b> <span id="Dred">Phenolic</span> Classes</a>  
     * <a href="#PhenTab"><b>Table 4:</b> Common Plant <span id="Dred">Phenolics</span></a>  
     * <a href="#Phen_Shik"><b>Section 4.2:</b> <span id="Dred">Phenolic</span> Biosynthesis</a>   
     * <a href="#Fig_ShikPath"><b>Figure 12:</b> <span id="Dred">Shikimic acid</span> Pathway</a>  
     * <a href="#Mlkwd_PNPquant"><b>Table 5:</b> Milkweed <span id="Dred">Cardenolide</span> and <span id="Dred">Phenolic</span> Content<span id="Dred"> </span></a>  
  6. <a href="#PKs"><b>Section 5:</b> <span id="Dred">Polyketides</span></a>  
     * <a href="#PKs"><b>Section 5.1:</b> <span id="Dred">Polyketides</span></a>  
     * <a href="#Fig_PKS"><b>Figure 13:</b> Plant <span id="Dred">Polyketide</span> Synthesis</a>  
     * <a href="#Tab6_Antho"><b>Table 6:</b> Common Plant <span id="Glacialb">Anthocyanins</span></span></a>  
     * <a href="#Fig_Oxygen"><b>Figure 14:</b> Chemistry of Molecular <span id="Red">O</span><b>xygen</b> and <i><span id="Rasp">Free Radicals</span></i></a>  
     * </a><a href="#Fig_VitCE"><b>Figure 15:</b> <span id="Gold">Lipid</span> <b>peroxidation</b> and <i><span id="Rasp">Free Radical</span></i> scavenging by <b>Vitamin</b> <span id="Or">C</span> and <b>E</b></a>  
  7. <a href="#Refs"><b>References</b></a>  
</details>

<!------------------------------------------------------>
<!-------- INTRO - PLANT NATURAL PRODUCTS (PNP) -------->
<!------------------------------------------------------>
<a id="PNP"></a>&nbsp; &nbsp; It is quite remarkable that most people around the world still rely on traditional medicine as their primary form of health care.**<sup>1,2</sup>** This speaks to the important role that <b>Plant Natural Products</b> (<span id="Gr">PNP</span>) play in the daily lives of most people around the world. Some of the more storied <span id="Gr">PNP</span> include the *analgesic* **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5288826">Morphine</a>** and the *anti-malarials* **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:15854">Quinine</a>** and **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:223316">Artemisinin</a>**. Although the building blocks of <span id="Fgr">PNP</span> are ultimately derived from **<a class="one" href="https://www.biointeractive.org/classroom-resources/photosynthesis">Photosynthesis</a>**, they do not play a major role in *basal cellular metabolism* (i.e. **primary metabolism**) and were once considered "*waste*" products. Fortunately we now know that **secondary metabolites** play a vital role in the survival of plants, particularly in relation to <u>environmental stresses</u> (e.g. herbivory, pathogens, damaging UV-radiation, water and nutrient shortages). Although there are an enormous number (>200,000) and variety of <span id="Gr">PNP</span>, their chemical building blocks are surprisingly few in number, with **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:15351">acetyl-Coenzyme A</a>** being perhaps the most important one of all of them (**Fig. 1**). 

<!---------------------------------------------------------------->
<!---------------- FIG 1 - Acetyl-CoA METABOLISM ----------------->
<!---------------------------------------------------------------->
<a id="Fig_AcCoA"></a>
<div align=center>
<figure>
<img src="images/Fig1_AcetylCoA_Met.jpg" alt="" width="600px"/>
<figcaption>
<b><u>Figure 1: <span id="Red">Acetyl-CoA</span> and Cellular Metabolism</u></b>. <span id="Red">Acetyl-CoA</span> is a well known product of several <i>catabolic</i> (<span id="Red">arrows</span>) pathways, as well as a key <i>anabolic</i> (<span id="Blue">arrows</span>) metabolite used in the production of lipids. It is also recognized as a key secondary messenger in cells where it is involved in regulating protein translation and gene regulation. As shown above <span id="Red">acetyl-CoA</span> can be produced via the breakdown (i.e. <i>catabolism</i>) of <b>sugars</b> (Glycolysis), <b>fatty acids</b> (&beta;-oxidation), and <b>amino acids</b> (deamination/oxidation). The high energy contained within the thioester bond of <span id="Red">acetyl-CoA</span> is captured by co-factors known as hydrogen carriers (<span id="Lb3">NADH</span>, <span id="Lb3">NADPH</span>, <span id="Lb3">FADH</span><sub>2</sub>) during the <b>Citric Acid Cycle</b>. These molecules carry high energy electrons to the <b><a class="one" href="https://www.biointeractive.org/classroom-resources/electron-transport-chain">Electron Transport Chain</a></b> where they are used in the production of <span id="Red">ATP</span>, the main "<i>fuel</i>" of cells. The intermediates of the <b>Citric Acid Cycle</b> are also used in the synthesis of amino acids.
</figcaption>
</figure>
</div>

<!-------------------------------------------------->
<!-------- SECTION 1 -- PNP Building Blocks -------->
<!-------------------------------------------------->
<a id="BB_PNP"></a>
<span id="BBlk">&thinsp; 1. BUILDING BLOCKS OF PNP &thinsp;</span>**:** Cellular <span id="Red">acetyl-CoA</span> serves as an <u>activated</u> carrier of **acetyl** groups (**C**<span id="Blue">H</span><sub>3</sub>**-C=**<span id="Red">O</span>), just like <span id="Red">ATP</span> is an <u>activated</u> carrier of *phosphoryl* groups (<span id="Purple">P</span><span id="Red">O</span><sub>3</sub><sup>-2</sup>). The two carbon (**C**<sub>2</sub>) **acyl** group (**R-C=**<span id="Red">O</span>) attached to <span id="Red">CoA</span> is *activated* because it is linked to <span id="Red">CoA</span> via a <u>high energy</u> **thioester** bond (**Note:** 2 carbon **acetyl** group is the most common **acyl** group linked to <span id="Red">CoA</span>). The *Gibbs free energy of hydrolysis* (**&Delta;G<sup>o&prime;</sup>**) for an **acetyl** group bound to <span id="Red">CoA</span> has a high negative value (**&Delta;G<sup>o&prime;</sup>** = **-35.1 kJ/mol**) that even exceeds the hydrolysis of the terminal phosphate group of <span id="Red">ATP</span> (**&Delta;G<sup>o&prime;</sup>** = **-34.54 kJ/mol**). Enzymes often use *exergonic* reactions (i.e. reactions with **&Delta;G<sup>o&prime;</sup>** < 0 release energy, such as the hydrolysis or "*breaking*" of a high energy **thioester** bond) to carry out *endergonic* reactions (i.e. reactions with **&Delta;G<sup>o&prime;</sup>** > 0 absorb energy, such as the synthesis of biomolecules). Cellular metabolism is largely made possible by the <u>coupling</u> of *exergonic* reactions with *endergonic* reactions.  
&nbsp; &nbsp; Plants and animals use a number of metabolic pathways to produce <span id="Red">acetyl-CoA</span> (**Fig. 1**), but for some anaerobic bacteria <span id="Red">acetyl-CoA</span> is the end product of a carbon *fixation* pathway known as the reductive <span id="Red">acetyl-CoA</span> or **Wood–Ljungdahl** pathway. This important biochemical pathway reduces **C**<span id="Red">O</span><sub>2</sub> using <span id="Blue">H</span><sub>2</sub> as the electron donor and transition metal co-factors as catalysts.**<sup>3</sup>** The energetically favourable manner in which this pathway produces <span id="Red">acetyl-CoA</span> (i.e. linear, *exergonic* **C**<span id="Red">O</span><sub>2</sub> fixation pathway) is of particular interest to **Origins of Life** (<span id="Dred">OoL</span>) researchers, since the key intermediates of this pathway (i.e. formate, acetate, and pyruvate) can be generated <u>abiotically</u> using the **<a class="one" href="https://www.biointeractive.org/classroom-resources/how-giant-tube-worms-survive-hydrothermal-vents">hydrothermal vent</a>** alloy **awaruite** (<span id="Lb2">Ni</span><sub>3</sub><span id="Dred">Fe</span>) as a catalyst.**<sup>4</sup>** The natural ease by which <span id="Blue">H</span><sub>2</sub> and **C**<span id="Red">O</span><sub>2</sub> can be converted to pyruvate (**C**<sub>3</sub>) using a simple inorganic catalyst provides allot of credibility to the idea that this ancient pathway was patterned on *exergonic* abiotic reactions naturally occurring within submarine **hydrothermal vent** systems --- one of the favoured sites for the <span id="Dred">OoL</span>.**<sup>5-9</sup>** Of course, when we talk about <span id="Dred">OoL</span> research most scientists immediately picture the famous **Miller-Urey** experiments of the early 1950s.**<sup>10</sup>** These two pioneers, who were inspired by the theoretical work of Oparin (1924) and Haldane (1929),**<sup>11,12</sup>** showed that complex biomolecules, like amino acids, can be synthesized from simple gases (<span id="Blue">H</span><sub>2</sub>, **C**<span id="Blue">H</span><sub>4</sub>, <span id="Gr">N</span><span id="Blue">H</span><sub>3</sub>, <span id="Blue">H</span><sub>2</sub><span id="Red">O</span>) using a small electric discharge.**<sup>13,14</sup>** Although Earth's early atmosphere more than 4 *billion years ago* (**Gya**) was not as *reducing* as Miller's experiments, it did lack free <span id="Red">O</span><sub>2</sub> (i.e. *anoxic*) and was therefore mildly *reducing* if not chemically neutral compared to today's atmosphere.**<sup>15-17</sup>** Although no single environment would have likely provided all of the chemical and physical conditions required for the <span id="Dred">OoL</span>, few have garnered more attention than submarine hydrothermal vents.**<sup>18</sup>** Some of these systems, like the *Lost City Hydrothermal Field* (**LCHF**),**<sup>19</sup>** vent warm (40-75<sup>o</sup>C) <span id="Blue">H</span><sub>2</sub> and **C**<span id="Blue">H</span><sub>4</sub> rich alkaline (pH 9-10) water that reacts with the cold seawater to produce relatively large (10-60 m) chimney-like carbonate structures.**<sup>20,21</sup>** Submarine vents, like the **LCHF** have presumably existed since the **Hadean**, and the large network of small pores found in them may have served as an ideal "*incubator*" for chemical reactions. The mixing of warm crustal water and cold seawater within these pores would have created temperature and pH gradients that promote the spontaneous *fixation* of **C**<span id="Red">O</span><sub>2</sub> (**Fig. 2B**).**<sup>22</sup>**  

<!--------------------------------------------------------->
<!---------------- FIG 2 - Acetyl-CoA OoL ----------------->
<!--------------------------------------------------------->
<a id="Fig_OoL"></a>
<div align=center>
<figure>
<img src="images/OoL.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 2: Life's Rocky Origins</u></b>. <b>(A)</b> Geochemical proxies and geochronological evidence suggests that life likely evolved very early on during the latter part of the <b>Hadean</b> eon, which spanned the first 500 million years of Earth's history. Although the exact timing of the <b>Origin of Life</b> (<span id="Dred">OoL</span>) is not known it probably occurred a few hundred million years after the cataclysmic Moon forming impact ~4.5 billion years ago (<b>Gya</b>).<b><sup>22</span></b> Chemical analysis of <b>Hadean</b> era zircons (i.e. crystals of zirconium silicate, <span id="Dbr">Zr</span><span id="Purple">Si</span><span id="Red">O</span><sub>4</sub>) suggest that oceans existed some 4.4 <b>Gya</b>.<b><sup>23-25</span></b> Yet, despite the existence of liquid water during the <b>Hadean</b> the earliest fossil evidence of life dates back only to ~3.5 <b>Gya</b>.<b><sup>26-29</span></b> Fortunately, indirect evidence in the form of <i>biogenic</i> carbon isotopes from ancient bedrock formations does suggest that life emerged much earlier (Greenland, ~3.8 <b>Gya</b>; Canada , ~3.95 <b>Gya</b>; Australia, ~4.1 <b>Gya</b>).<b><sup>29-33</span></b> The planet's early atmosphere is also poorly understood. Nevertheless, geological evidence and computer models suggest that it was largely dominated by nitrogen (<span id="Gr">N</span><sub>2</sub>) and carbon dioxide (<b>C</b><span id="Red">O</span><sub>2</sub>). For example, [<span id="Gr">N</span><sub>2</sub>] during the <b>Hadean</b> eon appears to have been similar to or somewhat less than modern levels, while [<b>C</b><span id="Red">O</span><sub>2</sub>] were 10-to-1000 times higher than current levels.<b><sup>17</span></b> Other gases, such as methane (<b>C</b><span id="Blue">H</span><sub>4</sub>), hydrogen (<span id="Blue">H</span><sub>2</sub>), carbon monoxide (<b>C</b><span id="Red">O</span>), ammonia (<span id="Gr">N</span><span id="Blue">H</span><sub>3</sub>) and hydrogen sulphide (<span id="Blue">H</span><sub>2</sub><span id="Gold">S</span>) were also present, but in relatively smaller amounts.<b><sup>34,17</span></b> One of the likely consequences of the elevated levels of <b>C</b><span id="Red">O</span><sub>2</sub> (and other greenhouse gases) is that early Earth had a relatively mild climate (i.e. >0<sup>o</sup>C). This is an important point given that the sun was ~25% less luminous 4 <b>Gya</b> than it is today.<b><sup>35,36,15</span></b> Without these elevated levels of greenhouse gases the planet would have been frozen for much of the <b>Hadean</b> and <b>Archean</b>. The absence of molecular oxygen (<span id="Red">O</span><sub>2</sub>) during these early eons is also worth noting, since under <b>anoxic</b> conditions <span id="Blue">reductive</span> chemical synthesis (shown in <b>B</b>) would have been favourable. However, when <span id="Red">oxygenic</span> <span id="Gr">photosynthesis</span> evolved (~2.4 <b>Gya</b>) the atmosphere became more <span id="Red">oxidizing</span> in nature. This transition to an <i>oxidizing</i> atmosphere was not only marked by the <span id="Red">G</span>reat <span id="Red">O</span>xidation <span id="Red">E</span>vent (<span id="Red">GOE</span>, 2-to-2.4 <b>Gya</b>), but preceded by the appearance of oxidized <b>manganese</b> (<span id="Purple">Mn</span>) deposits in the geological record. <span id="Purple">Mn</span> is a critical component of the <span id="Dred">W</span>ater <span id="Dred">O</span>xidation <span id="Dred">C</span>omplex (<span id="Dred">WOC</span>) of <b><a class="one" href="https://pdb101.rcsb.org/motm/59">Photosystem II</a></b> that strips electrons from water (i.e. "<i>splits</i>" water) to replace lost photo-activated electrons in chlorophyll (i.e. <i>resets</i> Photosystem II for photo-activation).<b><sup>37,38</span></b> The appearance <span id="Purple">Mn</span> deposits just prior to the emergence of <b>oxygenic photosynthesis</b> suggests that this <span id="Purple">Mn</span> powered <span id="Dred">WOC</span> likely evolved from an pre-existing <span id="Purple">Mn</span> powered electron donor complex used by <b>anoxygenic photosynthetic</b> microbes.<b><sup>37,38</span></b> The rapid rise in atmospheric [<span id="Red">O</span><sub>2</sub>] during the <span id="Red">GOE</span> led to the dawn of <span id="Red">aerobic</span> <b>respiration</b> and the eventual emergence of multicellular life (<b>Note:</b> <span id="Red">aerobic</span> <b>respiration</b> produces ~18 times more energy in the form of <span id="Red">ATP</span> than <span id="Purple">anaerobic</span> <b>respiration</b>).<br>
<b>(B)</b> The cornerstone of autotrophic organisms is the ability to convert inorganic carbon (e.g. <b>C</b><span id="Red">O</span><sub>2</sub>) into useful organic compounds (i.e. <i>carbon fixation</i>). Although the <u>prebiotic</u> origins of this chemical reaction are not known, recent research suggests that key intermediates of the reductive <span id="Red">acetyl-CoA</span> or <b>Wood–Ljungdahl</b> pathway<b><sup>3</span></b> can be produced under hydrothermal vent like conditions.<b><sup>39</span></b> These experiments used hydrothermal vent <u>minerals</u> (e.g. <b>Greigite</b> -- <span id="Dred">Fe</span><sub>3</sub><span id="Gold">S</span><sub>4</sub>, <b>Magnetite</b> -- <span id="Dred">Fe</span><sub>3</sub><span id="Red">O</span><sub>4</sub> and <b>Awaruite</b> -- <span id="Lb2">Ni</span><sub>3</sub><span id="Dred">Fe</span>) as <b>catalysts</b> for the <span id="Blue">H</span><sub>2</sub> dependent reduction of <b>C</b><span id="Red">O</span><sub>2</sub>. The production of simple <b>C</b><sub>1</sub> (methyl), <b>C</b><sub>2</sub> (acetyl) and <b>C</b><sub>3</sub> (pyruyl) intermediates of the <b>Wood–Ljungdahl</b> pathway with no additional energy inputs, other than the inherent chemical reactivity of the mineral surfaces and dissolved gases, supports the idea that the geochemistry of hydrothermal vent systems played a major role in the <span id="Dred">OoL</span>.<b><sup>5,9,18,40,41</span></b>  
</figcaption>
</figure>
</div>

&nbsp; &nbsp; The main sources of <span id="Red">acetyl-CoA</span> (**Fig. 3**) include the enzymatic **decarboxylation** of <u>pyruvate</u> (**C<sub>3<sup>**), an &alpha;-keto-acid product of **Glycolysis**, and the enzymatic &beta;-oxidation of <u>fatty acids</u>. The latter metabolic pathway cleaves **lipids**, like **Oleic acid** (**C<sub>18</sub>**), two carbon units (**C<sub>2</sub>**) at a time (i.e. new **acyl** group attached to <span id="Red">CoA</span>). A third source of <span id="Red">acetyl-CoA</span> comes from the **oxidative** breakdown of <u>amino acids</u>. However, unlike <u>glucose</u> and <u>fatty acids</u>, the *catabolism* of amino acids involves their **deamination**, an enzymatic step where an **amino** group (&ndash;<span id="Gr">N</span><span id="Blue">H</span><sub>2</sub>) is removed resulting in the formation of toxic *ammonia* (<span id="Gr">N</span><span id="Blue">H</span><sub>3</sub>). Fortunately this toxic metabolite is quickly converted to **urea** (aka: *carbamide*), a water soluble and largely non-toxic small molecule, via the addition of carbon dioxide in the **Urea Cycle**. For example, the **deamination** of **glutamic acid** produces &alpha;-ketoglutarate (aka: **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/51">2-oxoglutarate</a>**), which is a key intermediate within the **<a class="one" href="https://www.biointeractive.org/classroom-resources/citric-acid-cycle">Citric Acid Cycle</a>**. Regardless of the source, <span id="Red">acetyl-CoA</span> is the key <u>building block</u> for two major groups of <span id="Gr">PNPs</span>, namely <span id="Dred">Polyketides</span> and <span id="Dred">Terpenoids</span>, with the latter group boasting the largest number of <span id="Gr">PNPs</span> (i.e. >50,000 structures).**<sup>42</span>**  

<!------------------------------------------------->
<!----- FIGURE 3: PNP -- BIOCHEMICAL PATHWAYS ----->
<!------------------------------------------------->
<a id="Fig_PNP"></a>
<div align=center>
<figure>
<img src="images/Fig3_PNP_Pathways.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 3: Biochemical Pathways of <span id="Gr">PNPs</span></u></b>. The major classes of <span id="Gr">PNPs</span>, also known as plant <i>secondary metabolites</i>, include: (i) <span id="Dred">Terpenoids</span>, (ii) <span id="Dred">Polyketides</span>, (iii) <span id="Dred">Phenolics</span> and (iv) <span id="Dred">Alkaloids</span> (bottom of figure). <span id="Dred">Terpenoids</span> are synthesized via <b>mevalonate</b> <u>dependent</u> and <u>independent</u> pathways. The first step in the latter pathway is the synthesis of <b>deoxy-xylulose 5-phosphate</b> from two <b>Gylcolytic</b> pathway intermediates <b>pyruvate</b> and <b>glyceraldehyde 3-phosphate</b> (<b>G3P</b>), while in the former pathway the intermediate <b>mevalonate</b> is formed from three molecules of <span id="Dred">acetyl-CoA</span>. The synthesis of <span id="Dred">Polyketides</span> also requires <span id="Dred">acetyl-CoA</span>. Multiple <b>acetyl groups</b> provided by this carrier molecule are attached to "<i>starter</i>" material in <i>chain</i>-like fashion (i.e. <b>R-</b>(<b>C</b><span id="Blue">H</span><sub>2</sub><b>-C=</b><span id="Red">O</span>)<sub>n</sub><b>-starter</b>). Some of the <i>starter</i> materials are <span id="Dred">Phenolics</span> and <span id="Dred">Alkaloids</span>. The attached <span id="Dred">polyketides</span> <b>chains</b> often undergo intramolecular cyclization and aromatization as well as other chemical modifications (e.g. hydroxylation, glycosylation, methylation, etc.), resulting in structurally diverse compounds. The major building blocks of <span id="Dred">Phenolics</span> are produced by the <span id="Dred">Shikimic acid</span> <b>pathway</b>, which is responsible for making the three <i>aromatic</i> <u>amino acids</u> <b>Phenylalanine</b> (<span id="Gr">Phe</span>), <b>Tyrosine</b> (<span id="Gr">Tyr</span>) and <b>Tryptophan</b> (<span id="Gr">Try</span>). Two of these <i>aromatic</i> <u>amino acids</u> (i.e. <span id="Gr">Phe</span> and <span id="Gr">Tyr</span>) are the main building blocks of plant <span id="Dred">Phenolics</span>. Like <span id="Dred">Phenolics</span> the synthesis of <span id="Gr">nitrogen</span> containing <span id="Dred">Alkaloids</span> is also dependent on <u>amino acid</u> metabolism.
</figcaption>
</figure>
</div>

<!--------------------------------------------------->
<!---------- SECTION 2: PNP -- Terpenoids ----------->
<!--------------------------------------------------->
<a id="Terp"></a>
<span id="BBlk">&thinsp; 2. TERPENOIDS &thinsp;</span>**:** are the largest class of <span id="Gr">PNPs</span>.**<sup>43,44</sup>** Although some <span id="Dred">Terpenoids</span> do play a role in <u>primary metabolism</u>, such as **quinones** (e.g. **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5281915">ubiquinone</a>**, plastoquinone), most are classified as <u>secondary metabolites</u>. Some of these include &beta;-**ocimene** (i.e. common floral scent and plant defence),**<sup>45</sup>** **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/637566">Geraniol</a>** (component of essential oils),**<sup>43</sup>** <span id="Blue">C</span>ardiac <span id="Blue">G</span>lycosides (<span id="Blue">CG</span>, defense against herbivores),**<sup>46</sup>** and **carotenoids** (photo-oxidative stress protection).**<sup>47-49</sup>**  
&nbsp; &nbsp; Humans have long used <span id="Dred">Terpenoids</span> for a variety of purposes, including (among others) food additives (i.e. flavours, like lemon oil), pharmaceuticals (e.g. <span id="Blue">CG</span>), fragrances (e.g. **<a class="one" href="https://www.chemistryworld.com/podcasts/frankincense-and-myrrh/8106.article">Frankincense</a>**, Myrrh), and insecticides (e.g. **Caryophyllene**).**<sup>50-54</sup>** Moreover, some <span id="Dred">Terpenoids</span> are essential nutrients. For example **vitamin A**  (i.e. retinol, retinal, retinyl esters and retinoic acid --- collectively referred to as **retinoids**) is a well known <span id="Dred">diterpenoid</span> (**C**<sub>20</sub>) that we often consume in the form of its <span id="Dred">tetraterpenoid</span> (**C**<sub>40</sub>) precursor &beta;-**carotene** (**Table 1**, **Fig. 4**). This latter <span id="Dred">Terpenoid</span> is a common orange coloured pigment found in many fruits and vegetables (e.g. carrots, yams). The light absorbing abilities of these **retinoid** pigments plays a key role in animal vision systems. As shown in **Figure 4**, the *photoreceptor* <span id="Dred">Rhodopsin</span> is formed when the light-sensitive *chromophore* **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5280490">11-<i>cis</i>-retinal</a>** chemically binds to the protein **opsin** via a **C**arbon-<span id="Gr">N</span>itrogen double bond (R<sub>1</sub>-**C**=<span id="Gr">N</span>-R<sub>2</sub>), also known as a *Schiff* base, to form **11-*cis*-retinylidene**. Absorption of light by this bound *chromophore* triggers its geometric *isomerization* (i.e. type of molecular "*twisting*") from an **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5280490">11-<i>cis</i></a>** to an **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/638015"><i>all</i>-<i>trans</i></a>** state. This initial *photo*-activation step triggers a signal transduction cascade that ultimately leads to electrical impulses along the optic nerve to the brain.**<sup>55-60</sup>** To reset the visual-retinoid cycle the inactive **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/638015"><i>all</i>-<i>trans</i>-retinal</a>** is released from **opsin** and metabolized, via a series of enzymatic reactions, to regenerate the active *chromophore* **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5280490">11-<i>cis</i>-retinal</a>**.  
<!-------------------------------------------------->
<!------------- FIG 4 - RETINOID CYCLE ------------->
<!-------------------------------------------------->
<a id="Fig_Ret"></a>
<div align=center>
<figure>
<img src="images/Fig4_RetinoidCycle.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 4: Retinoid Cycle</u></b>. When <span id="Dred">Rhodopsin</span> absorbs a photon of light <i>photo-isomerization</i> of the bound <b>retinal</b> takes place (i.e. <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5280490">11-<i>cis</i></a></b> &rArr; <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/638015"><i>all</i>-<i>trans</i></a></b>) resulting in cell signaling events. The <b><i>all</i>-<i>trans-retinal</i></b> is then released from <b>opsin</b> and enzymatically reduced to <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/445354"><i>all</i>-<i>trans</i>-retinol</a></b>. This is followed by the <i>esterification</i> of the <b><i>all</i>-<i>trans</i>-retinol</b>, which facilitates its movement between cells. The accumulated <b>all-trans-retinyl ester</b>, which forms structures called <b>retinosomes</b>, is enzymatically converted to <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5280382">11-<i>cis</i>-retinol</a></b> and finally <b>11-<i>cis</i>-<i>retinal</i></b>, which can recombine with <b>opsin</b> and thus regenerate <span id="Dred">Rhodopsin</span> to complete the cycle.
</figcaption>
</figure>
</div>

&nbsp; &nbsp; Despite the vital role played by **retinal** and **retinol** in animal visual systems, they are not the most biologically active **retinoid**. That distinction goes to **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:17336"><i>all</i>-<i>trans</i>-retinoic acid</a>** (**ATRA**). This **retinoid** possesses potent hormone-like activity in both developing embryos and adults.**<sup>61-66</sup>** As a result the cellular levels of **ATRA** are tightly regulated (**Fig. 5**). Notably, the synthesis of **ATRA** is counter balanced by its metabolic breakdown courtesy specific members of the **Cytochrome P450** superfamily of mono-oxygenases (i.e. **CYP26** subfamily). These enzymes convert **ATRA** into more polar inactive metabolites, primarily **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/6438629">4-hydroxyretinoic acid</a>**.**<sup>67</sup>** On the other hand, active **ATRA** can be either exported out of the cell, where it can signal in paracrine-like fashion, or transported to the nucleus where it binds to the **retinoic acid receptor** (**RAR**).**<sup>68,69</sup>** However, **RAR** does not operate alone. In the nucleus it forms heterodimers with the **retinoid X receptor** (**RXR**). Together **RAR/RXR** binds to conserved stretches of DNA, termed **retinoic acid responsive elements** (**RARE**), located within the promoter regions of target genes. In the absence of **ATRA** the DNA bound **RAR/RXR** interacts with protein complexes known as **co-repressors** that block the transcription of downstream target genes. However, upon **ATRA** binding, **RAR/RXR** changes shape and releases the *co-repressor* complex. This in turn leads to the recruitment of **co-activator** complexes that promote the transcription of the target gene. Nevertheless, other studies also suggest that **ATRA** is capable of silencing the transcription of target genes when bound to the **RAR/RXR** complex.**<sup>64,65,70,71</sup>** 

<!-------------------------------------------------------------------->
<!----------------- FIG 5 - RETINOIC ACID SIGNALING ------------------>
<!-------------------------------------------------------------------->
<a id="Fig_RA"></a>
<div align=center>
<figure>
<img src="images/Fig5_ATRApathway.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 5: Retinoic Acid Signaling</u></b>. The <span id="Dred">Terpenoid</span> <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:17336">ATRA</a></b> is a specific ligand for the <b>retinoic acid receptor</b> (<b>RAR</b>). The receptor protein resides within the nucleus as part of a DNA bound heterodimer complex involving the <b>retinoid X receptor</b> (<b>RXR</b>) protein. Formation of the DNA bound <u>trimer</u> (<b>ATRA</b>/<b>RAR</b>/<b>RXR</b>) can either promote or inhibit the transcription of target genes that contain binding sites for the <b>RAR</b>/<b>RXR</b> heterodimer (i.e. <b>RARE</b>: retinoic acid receptor elements). In the absence of <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:17336">ATRA</a></b> the DNA bound heterodimer <b>RAR</b>/<b>RXR</b> silences gene transcription with the help of nuclear proteins known as <b>co-repressors</b>. However, when <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:17336">ATRA</a></b> binds to <b>RAR</b>/<b>RXR</b> gene transcription can be either enhanced, due to the recruitment of transcriptional activator proteins, or further silenced by the binding of transcriptional repressor proteins.<b><sup>65</sup></b>    
</figcaption>
</figure>
</div>

<!----------------------------------------------------------->
<!---------- PNP SECTION 2.1: Terpenoids Classes ----------->
<!----------------------------------------------------------->
<a id="Terp_Class"></a>
<figure class="FRight150">
<img src="images/Isoprene.jpg" alt="" height="150px"/>
</figure>  

<span id="BBlk">&thinsp; 2.1 TERPENOID CLASSES &thinsp;</span>**:** Structurally, <span id="Dred">Terpenoids</span> are composed of one or more **isoprene** units (2-methylbuta-1,3-diene (**C**<sub>5</sub><span id="Blue">H</span><sub>8</sub>)<sub>n</sub>), with the number of **carbons** (**C**) defining the <u>class</u> of <span id="Dred">Terpenoid</span>. Moreover, the basic **C**<sub>5</sub>-skeleton of these compounds can be folded to produce rings (e.g. steroids), as well as *functionalized* by the introduction of oxygen or other elements. As shown in **Table 1**, <span id="Dred">Terpenoids</span> are some of the most common compounds found in nature, including **natural rubber** (e.g. **poly-isoprene** particles found in **Milkweed latex**). As mentioned previously when talking about **Milkweeds**, this sticky hydrocarbon dissuades insects from eating plants by either: (i) *gumming-up* their mouth parts, or (ii) trapping and killing them. However, perhaps the most important <span id="Dred">Terpenoid</span> found in Milkweeds are the **Cardiac Glycosides** (<span id="Blue">CG</span>). As noted in **Table 1**, the central portion of these <span id="Blue">CG</span> is a <u>steroid</u>, which is synthesized from the <span id="Dred">triterpenoid</span> **squalene**.  

<!--------------------------------------------------------------->
<!-------------------- TABLE 1 - TERPENOIDS --------------------->
<!--------------------------------------------------------------->
<a id="TerpTable"></a>

<table class="Table">
    <thead>
      <tr style="text-align:left">
        <td colspan="3"><span id="Blk20"><span id="Blk">TABLE 1.</span> Classes of <span id="Dred">Terpenoids</span>.</span></td>
      </tr>
    <thead>
    <thead>
      <tr>
        <th class="f18"><span id="Blk">Class</span></th>
        <th class="f18"><span id="Blk">Carbons</span></th>
        <th class="f18"><span id="Blk">Examples</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><span id="Blk">HEMITERPENOIDS</span></td>
        <td><span id="Blk">C<sub>5</sub></span></td>
        <td><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/6557">Isoprene</a> - basic building block of terpenoids.</td>
      </tr>
      <tr>
        <td><span id="Blk">MONOTERPENOIDS</span></td>
        <td><span id="Blk">C<sub>10</sub></span></td>
        <td><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/22311">Limonene</a></b> - oil extracted from the fruit peel of lemons is used as flavoring. <b><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/92770">Nepetalactone</a></strong> - an insect repellent produced by the plant <i>Nepeta cataria</i> that is also the major constituent of catnip. <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/637566">Geraniol</a></b> - found in essential oils (e.g. rose oil, citronella, lemongrass, lavender).</td>
      </tr>
      <tr>
        <td><span id="Blk">SESQUITERPENOIDS</span></td>
        <td><span id="Blk">C<sub>15</sub></span></td>
        <td><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/29746">Geosmin</a> - major constituent of the earthy aroma produced when rain falls on dry soil.</td>
      </tr>
      <tr>
        <td><span id="Blk">DITERPENOIDS</span></td>
        <td><span id="Blk">C<sub>20</sub></span></td>
        <td><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/445354">Retinol</a> - vitamin A1. <a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/36314">Paclitaxol</a> (Taxol) - major cancer drug isolated from the Pacific yew tree.</td>
      </tr>
      <tr>
        <td><span id="Blk">TRITERPENOIDS</span></td>
        <td><span id="Blk">C<sub>30</sub></span></td>
        <td><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/638072">Squalene</a> - precursor to steroids such as <span id="Blue">Cardiac Glycosides</span> (e.g. <a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/439501">Ouabain</a>).</td>
      </tr>
      <tr>
        <td><span id="Blk">TETRATERPENOIDS</span></td>
        <td><span id="Blk">C<sub>40</sub></span></td>
        <td><span id="Red">Red</span> (<a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/446925">Lycopene</a>), <span id="Or">Orange</span> (<a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/5280489">&beta;-carotene</a>) and <span id="Gold">Yellow</span> (<a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/5281243">Lutein</a>) Carotenoid pigments are vital to photosynthesis and animal health.</td>
      </tr>
      <tr>
        <td><span id="Blk">POLYTERPENOIDS</span></td>
        <td><span id="Blk">>C<sub>40</sub></span></td>
        <td><b>Natural Rubber</b> is made up of long <u>isoprene</u> polymers and was originally isolated from the Brazilian rubber tree (<i>Hevea braziliensis</i>).</td>
      </tr>
    </tbody>
</table>

<!------------------------------------------------------------------->
<!---------- PNP SECTION 2.2: Terpenoids - Natural Rubber ----------->
<!------------------------------------------------------------------->
<a id="NatRub"></a>
<span id="BBlk">&thinsp; 2.2 NATURAL RUBBER &thinsp;</span>**:** This natural polymer of **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:35194">isoprene</a>** (see above Figure) has a long and storied past. Many people know that this component of plant **latex** was used by ancient *Mesoamerican* people to make figurines and other artifacts, including the balls used in the famous Mesoamerican *ball game*.**<sup>72</sup>** However, the earliest scientific report of *natural rubber* did not appear until 1735 AD, courtesy **Charles de la Condamine**. This French explorer came across *natural rubber* during a trip to Peru where he learned that indigenous tribes harvested it from a native tree (*Hevea Brasiliensis*). He also made detailed studies of the *Cinchona* tree, whose bark is the source of the <u>anti-malarial</u> compound **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/3034034">quinine</a>**. Needless to say, *natural rubber* gained great notoriety when people learned of the many wondrous products that could be fashioned from it, including (among others) the indispensable eraser (1770, Edward Nairne), raincoats (1823, Charles Macintosh) and balloons (1824, Michael Faraday). However, it was not until 1839, when Charles Goodyear discovered a way to make *rubber* more temperature resistant (i.e. "*vulcanization*" process: heating **polyisoprene** in the presence of sulfur and lead carbonate), that the manufacturing of rubber became a truly global lucrative market.**<sup>73</sup>** Although most of the *rubber* manufactured today is synthetic, the harvesting of *natural rubber* is still an economic interest of many Southeast Asian countries.  
&nbsp; &nbsp; As mentioned previously, the defensive nature of plant **latex** is due in large part to its *natural rubber* content. The aggregation of these **polyisoprene** particles produces long sticky strands that the plant uses to either dissuade predatory insects from eating them, or seal wounds and thus protect itself from infectious pathogens. In response insects that feed on **latex** producing plants, like Milkweeds, often cut the **lactifer** tubes that hold the **latex** prior to feeding on them.**<sup>74-76</sup>** This so-called "*sabotaging*" behaviour is in fact quite effective in blocking the flow of **latex** and thus reducing the build up of toxic compounds the insect would otherwise ingest.**<sup>77-80</sup>** Further support for the *defensive* role of **latex** comes from research that shows **jasmonic acid**, a highly conserved "*danger*" signal among plants,**<sup>81-83</sup>** regulates the levels of **latex** produced in some Milkweed species.**<sup>84-86</sup>** 

<!------------------------------------------------->
<!------ PNP SECTION 2.4: Terpenoids - CGs -------->
<!------------------------------------------------->
<a id="CGs"></a>
<figure class="FRight200">
<img src="images/Digoxin.jpg" alt="" height="195px"/>
</figure>  

<span id="BBlk">&thinsp; 2.3 CARDIAC GLYCOSIDES &thinsp;</span>**:** These remarkable compounds are well known animal poisons and can be divided into two classes, namely: **(i)** <span id="Dred">Cardenolides</span> (e.g. foxglove **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/2724385">Digoxin</a>**), and **(ii)** <span id="Dred">Bufadienolides</span> (e.g. toad venom **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/9547215">Bufalin</a>**).**<sup>87,88</sup>** Structurally <span id="Blue">CG</span> have three main parts: **(i)** a core *steroid* group; **(ii)** a *sugar* (i.e. glycoside) moiety; and **(iii)** a *lactone* ring (i.e. cyclic carboxylic ester). Although structurally quite similar, these two classes of <span id="Blue">CG</span> can be distinguished from one another based on the size of the *lactone* ring (i.e 5 versus 6 member heterocyclic ring, respectively). It should also be pointed out that most animal produced <span id="Dred">Bufadienolides</span> are not glycosylated, which has resulted in the use of **Cardio-Tonic Steroids** (<span id="Blue">CTS</span> ) as an alternative name for these two groups of toxins. <span id="Blue"><span id="Dred">Cardenolides</span></span> are more commonly found in plants and have garnered considerable attention because of their many medical applications (see **Table 2**, see <a id="CGmed">Section 2.4</a>). For example, **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/2724385">Digoxin</a>** is used by millions of heart patients in North America, with an estimated 1.68 million prescriptions per year in Canada alone.**<sup>89</sup>**  

<!----------------------------------------------------->
<!---------- TABLE 2 - Cardiotonic Steroids ----------->
<!----------------------------------------------------->
<a id="CGTab"></a>

<table class="Table">
    <thead>
      <tr style="text-align:left">
        <td colspan="4"><span id="Blk20"><span id="Blk">TABLE 2.</span> Cardiotonic Steroids (<span id="Dred">CTS</span>) found in various plants and animals</span></td>
      </tr>
    <thead>
      <tr>
        <th class="f18"><span id="Blk">CLASS</span></th>
        <th class="f18"><span id="Blk">NAME</span></th>
        <th class="f18"><span id="Blk">FORMULA</span></th>
        <th class="f18"><span id="Blk">COMMENTS</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><span id="Blk">Cardenolide</span></td>
        <td><span id="Blk"><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/439501">Ouabain</a></span></td>
        <td class="tcell"><span id="Blk">C<sub>29</sub><span id="Blue">H</span><sub>44</sub><span id="Red">O</span><sub>12</sub></span></td>
        <td>Also known as <b><i>g-Strophanthin</i></b>. Found in <i>Strophantus gratus</i> (climbing oleander) and <i>Acocanthera schimperi</i> (Ouabaio tree). Historically used in Africa as an arrow poison (c. 3<sup>rd</sup> century BC) and once used to treat heart ailments. Potential use in the treatment of cancers owing to its ability to sensitize cancer to <i>apoptotic</i> cell death.</td>
      </tr>
      <tr>
        <td><span id="Blk">Cardenolide</span></td>
        <td><span id="Blk"><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/2724385">Digoxin</a></span></td>
        <td class="tcell"><span id="Blk">C<sub>41</sub><span id="Blue">H</span><sub>64</sub><span id="Red">O</span><sub>14</sub></span></td>
        <td>First isolated (c. 1930) from the foxglove plant, <i>Digitalis lanata</i>. Main form of <b>Digitalis therapy</b> for treating congestive heart failure and irregular heartbeat. Historically used by herbalists and doctors to treat a variety of maladies, most notably "<i>dropsy</i>" (i.e. <b>edema</b> - swelling of soft tissues due to excess accumulation of water). Potential use in the treatment of cancers owing to its ability to sensitize cancer cells to <i>apoptotic</i> cell death.</td>
      </tr>
      <tr>
        <td><span id="Blk">Cardenolide</span></td>
        <td><span id="Blk"><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/11541511">Oleandrin</a></span></td>
        <td class="tcell"><span id="Blk">C<sub>32</sub><span id="Blue">H</span><sub>48</sub><span id="Red">O</span><sub>9</sub></span></td>
        <td>Found in <b>Oleander</b> (<i>Nerium oleander</i>). Historically used in the treatment of heart maladies. Potential use in the treatment of cancers owing to its ability to sensitize cancer cells to <i>apoptotic</i> cell death.</span></td>
      </tr>
      <tr>
        <td><span id="Blk">Bufadienolide</span></td>
        <td><span id="Blk"><a class="one" href="http://pubchem.ncbi.nlm.nih.gov/compound/9547215">Bufalin</a></span></td>
        <td class="tcell"><span id="Blk">C<sub>24</sub><span id="Blue">H</span><sub>34</sub><span id="Red">O</span><sub>4</sub></span></td>
        <td>Originally isolated from Chinese toad venom. Long history in traditional Chinese medicine. Potential use in the treatment of cancers owing to its ability to sensitize cancer cells to <i>apoptotic</i> cell death.</td>
      </tr>
    </tbody>
</table>

<!----------------------------------------------------->
<!------ SECTION 2.3.1: CGs Cellular Mechanisms ------->
<!----------------------------------------------------->
<a id="CGmech"></a>
<span id="BBlk">&thinsp; 2.3.1 CARDIAC GLYCOSIDE CELLULAR MECHANISM OF ACTION &thinsp;</span>**:** The cardio-toxic properties of these plant steroids are due to their inhibition of <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span>**ase**, a ubiquitous animal enzyme that is also known as the plasma membrane <span id="Purple">Na</span><sup>+</sup><span id="Dred">pump</span> (**Fig. 6**).**<sup>90</sup>** This enzyme belongs to the <span id="Red">P</span>-type family of <u>active</u> (requires <span id="Red">ATP</span>) cation transporters since it uses a *phosphorylated* intermediate during its catalytic cycle (**Fig. 7**).**<sup>91-93</sup>** This essential "*house keeping*" protein transports <span id="Purple">Na</span><sup>+</sup> and <span id="Dbr">K</span><sup>+</sup> across the plasma membrane <u>against</u> their respective cation concentration gradients (**Fig. 7**, [<span id="Purple">Na</span><sup>+</sup>]<sub>in</sub> <  [<span id="Purple">Na</span><sup>+</sup>]<sub>out</sub> and [<span id="Dbr">K</span><sup>+</sup>]<sub>in</sub> > [<span id="Dbr">K</span><sup>+</sup>]<sub>out</sub>). What makes the <span id="Purple">Na</span><sup>+</sup><span id="Dred">pump</span> so remarkable is that the **electrochemical gradient** it creates helps to maintain the overall **electrochemical potential** (**&Delta;&psi;**) of the plasma membrane (**Fig. 7**). This difference in electric potential across the plasma membrane (**<span id="Dred">V</span><sub>m</sub>**) is used by other transport systems to move essential biomolecules and ions across the plasma membrane (e.g. <span id="Dgray">Ca</span><sup>+2</sup>, <span id="Blue">H</span><sup>+</sup>, <span id="Gr3">Cl</span><sup>-</sup>, <span id="Purple">Mg</span><sup>+2</sup>, glucose, amino acids, neurotransmitters).**<sup>94</sup>** For example, the electrical signaling events (i.e. action potentials) that power cardiac muscle contraction and neuronal communication are both made possible by this electrogenic transport system. Given the fundamental role that <span id="Purple">Na</span><sup>+</sup> transport plays in cells, some have gone so far as to hypothesized that it may be a product of the early geochemical environment where life itself first emerged.**<sup>95</sup>** This idea embraces the principle of *chemical conservation* which implies:

> "...*chemical composition of living beings is more conservative than the chemical composition of their environment. Therefore, the conserved organismal chemistry can retain information about the ancient environmental conditions. The most popular manifestation of this principle is the similarity between the chemical composition of sea water and the internal liquids of multicellular animals. The latter are characterized by high sodium content even if organisms live in fresh water or on the land ...[this] appears to reflect the emergence of the first multicellular organisms in the sea waters*." **<sup>96</sup>**  

<!------------------------------------------------------------------------->
<!-------------------- FIG 6 - Na Pump - Chimera pics --------------------->
<!------------------------------------------------------------------------->
<a id="Fig_NKA"></a>

<div class="cf" align=center>
  <img class="bottom" src="images/NaKATPase_ab.jpg" alt="" height="500px"/>
  <img class="top" src="images/NaKATPase_g.jpg" alt="" height="500px"/>
</div>

<caption><span id="Blk"><u>Figure 6: <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span>ase Structure</u>.</span> The first high resolution X-ray crystal structure (<b><a class="one" href="https://www.rcsb.org/structure/3B8E">3B8E</a></b>)<b><sup>97</sup></b> of the <span id="Purple">Na</span><sup>+</sup>-<span id="Dred">pump</span> protein isolated from pig (<i>Sus scrofa</i>) kidneys is shown in this <u>ribbon</u> diagram (i.e. protein backbone: &alpha;-helix, &beta;-strands &rArr; thick arrows, and connecting loops of unstructured stretches of amino acid residues). This image of the protein crystal structure was generated with <b><a class="one" href="https://www.cgl.ucsf.edu/chimerax/">UCSF ChimeraX</a></b> program.<b><sup>98</sup></b> Large portions of the three subunits are represented in this model (i.e. &alpha;-subunit: residues 19-to-1016, &beta;-subunit: residues 28-to-73 of the transmembrane segment, &gamma;-subunit: residues 23-to-51). Bound (occluded) <span id="Magenta">Rb</span><sup>+</sup> ions (<span id="Magenta">magenta</span> spheres) are also part of the model since they were used to stabilize the solublized membrane protein complex for X-ray crystallography.</caption>  

&nbsp;  
Certainly based on the essential role the <span id="Purple">Na</span><sup>+</sup><span id="Dred">pump</span> plays in maintaining the electrochemical potential of cell membranes, as well as its high levels of expression (e.g. ~50 million in kidney cells)**<sup>99</sup>** and amounts of energy (<span id="Red">ATP</span>) that some cells use to power it (i.e. gray matter neurons: ~20% of total energy budget),**<sup>100-102</sup>** one could easily argue that it is one of the most important cellular proteins found in multicellular organisms. This may also help to explain why so many plants produce compounds that specifically target it, since their survival depends upon mounting an effective defence against many different kinds of herbivores.  

<!---------------------------------------------------------------------->
<!-------------------- FIG 7 - NaKATPase Mechanism --------------------->
<!---------------------------------------------------------------------->
<a id="Fig_NKAcycle"></a>
<div align=center>
<figure>
<img src="images/NaKATPase_cycle_mech.jpg" alt="" width="700px"/>
<figcaption>
<b><u>Figure 7: <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span>ase Mechanism of Action</u>.</b> The above cartoon of the <span id="Purple">Na</span><sup>+</sup>-<span id="Dred">pump</span> is largely based on the review article by <b>Werner Kühlbrandt</b> (2004).<b><sup>92</sup></b> The catalytic activity of the <span id="Purple">Na</span><sup>+</sup>-<span id="Dred">pump</span> resides within its <b>&alpha;</b>-subunit.<b><sup>91-93</sup></b> This subunit has four important domains: <b>(i)</b> a cytoplasmic <span id="Red">P</span>hosphorylation domain, <b>(ii)</b> a cytoplasmic <span id="Red">A</span>ctuator domain, <b>(iii)</b> a cytoplasmic <span id="Red">N</span>ucleotide binding domain, and <b>(iv)</b> a <span id="Purple">M</span>embrane spanning domain consisting of 10 alpha helices (i.e. &alpha;-TM1-10) some of which contribute to the formation of an ion channel. At the start of the catalytic cycle three cytoplasmic <span id="Purple">Na</span><sup>+</sup> ions move through the ion channel of the <span id="Purple">M</span> domain to specific binding sites. The movement of these <u>polar</u> (+ charged) ions through the <u>non-polar</u> plasma membrane is made possible by polar amino acid residues that make up the ion channel. The low and high energy barriers created by the channel's polar and non-polar residues help guide the ions through the membrane in a unidirectional manner (<b>Note:</b> -70 mV resting potential of the cell's plasma membrane represents a significant energy barrier for transporting cations against their concentration gradients). <span id="Purple">Na</span><sup>+</sup> binding is associated with protein phosphorylation (<b>E1-</b><span id="Red">P</span> state) and the closing of the intracellular side of the channel. This conformational change in the protein unlocks the extracellular side of the ion channel allowing <span id="Purple">Na</span><sup>+</sup> to exit and <span id="Dbr">K</span><sup>+</sup> to enter the channel and occupy designated binding sites (<b>E2-</b><span id="Red">P</span> state). Binding of <span id="Dbr">K</span><sup>+</sup> is associated with another key "<i>pivoting</i>" movement of the transporter that involves the closing of the extracellular side of the ion channel, dephosphorylation and binding of a new molecule of <span id="Red">ATP</span> (<b>E2</b> state). This is followed by the opening of the intracellular side of the channel and the release of <span id="Dbr">K</span><sup>+</sup> into the cytoplasm (<b>E1</b> state). The cycle can now begin again with the binding of a new triad of <span id="Purple">Na</span><sup>+</sup> ions.<b><sup>91-93,103-105</sup></b>
</figcaption>
</figure>
</div>  
&nbsp;  

<div>
<img src="images/Mkwd_icon2.jpg" alt="" style="float:left; width:55px;"/>
<img src="images/Mkwd_icon2.jpg" alt="" style="float:right; width:55px;"/>
<div class="head16">
<i>How do Cardiac Glycosides (CG) disrupt the function of the sodium pump?<br>
How do animals that regularly comsume these toxic compounds survive?<br>
Moreover, what are the evolutionary benefits and costs of comsuming CG?</i>  
</div>
</div>

&nbsp; &nbsp; One of the more interesting defensive strategies that animals have evolved is the use of chemical toxins coupled with conspicuous colouration patterns. The great **<a class="one" href="https://www.biointeractive.org/classroom-resources/animated-life-r-wallace">Alfred Wallace</a>** (1867) was the first to offer an explanation for this adaptation, namely that bright coloration patterns advertise their unpalatability to potential predators.**<sup>106,107</sup>** A little later **Slater** (1877) made an insightful addition to Wallace's grand idea by stating that:  
>"...*strikingly-coloured insects, not otherwise specially protected, will be found to feed upon poisonous plants, or upon such as, though not poisonous, possess unpleasant, or at least very powerful, odours or flavours. From such a diet I conceive that the insects in question may receive properties positively injurious, or at least disgusting, to their enemies, and that a brilliant colouring may therefore here serve as a danger signal, like the quarantine flag, warning all comers to keep their distance*." **<sup>108</sup>**  

&nbsp; &nbsp; By the end of the 19<sup>th</sup> century **Edward B. Poulton** (1890) had published a book entitled "*The Colours of Animals*" that described in detail all of the observations about animal coloration patterns and the potential uses species gain from them (i.e. species survival).**<sup>109</sup>** While most people don't recognize the name **Poulton**, or his book, many people likely do know something about **aposematic colours**, a term he introduced in the final chapter of his book. The brightly coloured **Monarch butterfly** (*Danaus plexippus*), which specializes on toxic **Milkweeds**, is a prime example of **<a class="one" href="https://evolution.berkeley.edu/aposematic-animals/">aposematism</a>**. Clues as to the chemical nature of this anti-predator phenomena in **Monarchs** finally came in 1965 when **Parson** partially purified toxic compounds from the tissues of *D. plexippus*. These compounds, which he called **Plexippens**, shared many pharmacological properties with that of **digitalis**, including its characteristic cardiovascular (i.e. ventricular fibrillation) and gastroinstestinal effects (i.e. **emesis**).**<sup>110</sup>** Moreover, he was also able to show, like **Schatzmann** (1953) and **Repke** (1963) had done before him with **digitalis**,**<sup>111,112</sup>** that **Plexippens** could inhibit the enzymatic activity of the plasma membrane <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>**ase** previously discovered by **<a class="one" href="https://www.nobelprize.org/prizes/chemistry/1997/skou/facts/">Skou</a>** in 1957 (Note: **Skuo** would win the 1997 Nobel prize in Chemistry for his discovery of the <span id="Purple">Na</span><sup>+</sup><span id="Dred">pump</span>).**<sup>90</sup>** Finally, with the help of yet another Nobel Prize (1950) winning chemist **<a class="one" href="https://www.nobelprize.org/prizes/medicine/1950/reichstein/facts/">Tadeus Reichstein</a>**, **Parson** and his colleagues **Von Euw** and **Rothchild** went on to show that their precious **Plexippens** were indeed <span id="Blue">CG</span>.**<sup>113</sup>** Although some of the mystery surrounding the **apomastic coloration** of **Monarchs** was solved there were many molecular and mechanistic details that remained unanswered. Specifically, whether or not <span id="Dred">cardenolides</span> bind to the <span id="Purple">Na</span><sup>+</sup><span id="Dred">pump</span>, and if so what parts of the transporter protein are important to the binding of these plant toxins. Once the catalytic &alpha;-subunit of the transporter had been cloned (1985)**<sup>114</sup>** several mutagenesis studies were carried out to identify key structural features of the enzyme.**<sup>115-117</sup>** These early studies clearly showed that a short stretch of amino acid residues (<sup>&star;</sup>Sheep: 111-<span id="Blue">Q</span>**AAT**<span id="Ror">EEE</span>**P**<span id="Blue">Q</span><span id="Blue">N</span><span id="Ror">D</span><span id="Blue">N</span>-122) located between the first two transmembrane domains (**Fig. 8**) contained a binding site that was likely responsible for the cardenolide sensitivity of this enzyme. Ecologists quickly followed up on these new findings by looking for similar genetic changes within the &alpha;-subunit of cardenolide insensitive *D. plexippus*. Fortunately for **Holzinger** and colleagues (1992) the recent advent of **<a class="one" href="https://www.biointeractive.org/classroom-resources/polymerase-chain-reaction-pcr">PCR</a>** made this a relatively easy task to perform.**<sup>118</sup>** They **PCR** amplified the genomic **DNA** of *D. plexipppus* using sequence specific primers that spanned the putative cardenolide-binding site, and then used standard molecular biology techniques to produce enough of this DNA for **<a class="one" href="https://www.biointeractive.org/classroom-resources/sanger-sequencing">sequencing</a>**. There they found several variations within the **DNA** sequence, including two nucleotide changes within **<a class="one" href="https://www.genome.gov/genetics-glossary/Codon">codon</a> 122** (i.e. **AAT**&rarr;<span id="Red">C</span>**A**<span id="Red">C</span>). In cardenolide <u>sensitive</u> species (e.g. humans, sheep, fruit flies) this **codon** encodes for <span id="Blue">Asparagine</span> (**AAT**<sup>122</sup> &rArr; <span id="Blue">Asn</span>-122), while in the cardenolide <u>insensitive</u> *D. plexippus* the altered codon encodes for <span id="Purple">Histidine</span> (<span id="Red">C</span>**A**<span id="Red">C</span><sup>122</sup> &rArr; <span id="Purple">His</span>-122). Although there were other changes within this short amino acid sequence, including one that would later be shown to be important (<span id="Blue">Asn</span>111**Val**),**<sup>119</sup>** the replacement of the highly conserved <span id="Blue">Asn</span>-122 with <span id="Purple">His</span>-122 appeared to be the key change responsible for the cardenolide <u>insensitivity</u> in *D. plexippus*.**<sup>118</sup>** Eventually a much clearer picture of the enzyme's cardenolide binding pocket emerged when high resolution crystal structures of the protein became available (**Figure 8**).**<sup>97,120,121</sup>**  

<!----------------------------------------------------->
<!------- FIG 8 - NaKATPase - oubain structure -------->
<!----------------------------------------------------->
<a id="Fig_NKAouabain"></a>
<div align=center>
<figure>
<img src="images/NKA_ouabain_structure.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 8: Crystal Structure of <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span>ase bound to <a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:472805">Ouabain</a></u></b>. <b>(A)</b> The <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup>-<span id="Red">ATP</span><b>ase</b> used to make this high resolution (2.9 &Aring;) crystal structure (PDB ID: <b><a class="one" href="https://www.ebi.ac.uk/pdbe/entry/pdb/3A3Y">3A3Y</a></b>) was isolated from the salt glands of a spiny dogfish (<i>Squalus acanthias</i>). The solublized protein was fixed in a state analogous to that of <b>E2</b>&middot;2<span id="Dbr">K</span><sup>+</sup>&middot;<span id="Red">P</span> using <span id="Purple">Mg</span><span id="Rust">F</span><sub>4</sub><sup>-2</sup> as a stable phosphate analog.<b><sup>120</sup></b> Like <b>Figure 6</b> this representation of the crystal structure was rendered using the <b><a class="one" href="https://www.cgl.ucsf.edu/chimerax/">UCSF ChimeraX</a></b> program.<b><sup>98</sup></b> A ribbon diagram of all three subunits (<span id="Teal">&alpha;</span>: residues 32-1,023, <span id="Cfb">&beta;</span>: residues 28-to-160/169-217/223-305, <span id="Ror">&gamma;</span>: residues 5-to-42) is shown along with the bound <b>ouabain</b> and <span id="Dbr">K</span><sup>+</sup> ions.<br> <b>(B)</b> A closer look at the ouabain binding site (<b>Note:</b> atomic surface rendering using standard element colours: polar <span id="Red">O</span>xygen and <span id="Blue">N</span>itrogen, and non-polar <span id="Dgray">C</span>arbon) shows several amino acid side chains (stick models) in close proximity (<5 &Aring;) to the bound toxin (<b>Note:</b> identified using <i>select</i> and <i>zone</i> features of <b>ChimeraX</b>), including <span id="Purple">Asn</span>-129 (i.e. putative <b>cardenolide</b> binding site. <sup>&star;</sup>Note: in accordance with the original <i>O. aries</i> cloning study the authors did not count the first 5 amino acids in <i>S. acanthus</i> sequence since they are presumably removed during post-translational processing).<b><sup>114</sup></b> <b>(C)</b> Part of a <b>CLUSTAL</b> multi-sequence alignment (default settings, <b><a class="one" href="https://www.jalview.org/">Jalview</a></b> workbench)<b><sup>122</sup></b> shows the stretch of 12 amino acid residues that make up part of the <span id="Blue">CG</span> binding site within the &alpha;-subunit.<b><sup>115-117</sup></b> Sequences from four different species were used in the alignment (<i>S. acanthus</i>, <i>O. aries</i>, <i>D. plexippus</i>, <i>D. melanogaster</i>). Variations in the identity of the amino acids at each of the 12 positions is evident in the <b>CLUSTAL</b> generated consensus sequence. Notice that <i>D. plexippus</i> contains four distinct amino acid substitutions (boxed amino acid residues) when compared to the three toxin-sensitive species. The numbers atop the alignment correspond to the sheep sequence (customary practice since the &alpha;-subunit gene was first cloned from sheep).  
</figcaption>
</figure>
</div>

&nbsp; &nbsp; Since the discovery of these genetic variants in *D. plexippus* ecologists have been trying to determine what role they play in the **<a class="one" href="https://evolution.berkeley.edu/evolution-101/macroevolution/">evolution</a>** of cardenolide-adapted insects. For example, are the number of possible amino acid substitutions for a highly conserved protein like <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>**ase** constrained during its evolution? And what about the favorable mutations that do emerge within a population? Do they arise by chance (e.g. gene flow), or do ecological pressures select them over a longer time frame? Nevertheless, here is what we do know about this trait:  
**(i)** Many cardenolide-adapted species from across six known taxonomic **Orders** have evolved cardenolide-insensitive variants of <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>**ase** (**Fig. 9, 10**).**<sup>123-125</sup>** The amino acid substitutions to the cardenolide-binding site of these variants confer resistance to the toxin and is often referred to as <u>target site insensitivity</u> (**TSI**).    
**(ii)** Cardenolide-adapted species often share the same amino acid substitutions within the catalytic &alpha;-subunit of this enzyme (**Fig. 9, 10**). Ecologists studying evolution often cite this as an example of molecular **convergence**.**<sup>123-125</sup>**  
**(iii)** Several cardenolide-adapted insects have multiple copies (i.e. inferred gene duplication events) of the <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>**ase** &alpha;-subunit gene (e.g. *Oncopeltus fasciatus*, *Phytomyza hellibori*).**<sup>123,126-130</sup>** These copies have one or more different amino acid substitutions that appear to contribute to their tissue specific function.**<sup>123,131,132</sup>** Namely cardenolide <u>insensitive</u> copies are preferentially expressed in the digestive tract, where they are in direct contact with the ingested toxins, while the cardenolide-sensitive variants are preferentially expressed in muscle and neuronal tissue. This molecular "*diversity*" may help to alleviate the deleterious effects that some amino acid substitutions have on enzyme function and species fitness.**<sup>128,129,133</sup>** It is interesting to note that **Ala**119<span id="Dred">Ser</span>, one of the most common amino acid substitutions (**Fig. 9, 10**), appears to compensate for the lethal affects of many commonly observed mutations (e.g. <span id="Blue">Gln</span>111**Leu**, <span id="Blue">Gln</span>111**Val**, <span id="Blue">Gln</span>111<span id="Dred">Thr</span>, <span id="Blue">Asn</span>122<span id="Purple">His</span>).**<sup>133</sup>**  

<!-------------------------------------------------------->
<!------- FIG 9 - NaKATPase - oubain binding site -------->
<!-------------------------------------------------------->
<a id="Fig_NKAbs"></a>
<div align=center>
<figure>
<img src="images/NKA_CGbinding_site_MSA.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 9: Multiple amino acid substitutions within the &alpha;-subunit of <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>ase</u></b>. The diagram profiles the changing patterns in the amino acid sequence of the &alpha;-subunit of <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span><b>ase</b> within 46 different animal species (protein sequences downloaded from <b><a class="one" href="https://www.uniprot.org/">UniProt</a></b> database). Species from five major invertebrate insect <b>Orders</b> were chosen (<b>H</b> = Hemiptera, <b>O</b> = Orthoptera, <b>D</b> = Diptera, <b>C</b> = Coleoptera, <b>L</b> = Lepidoptera) along with a few vertebrate (<b>V</b>) species. Four regions of the &alpha;-subunit were examined based on the analysis of the protein crystal structure in <b>Fig. 8B</b> (i.e. notable side chains of amino acid residues that come within 5 &Aring; of bound <b>ouabain</b>). Some amino acids within these regions are highlighted, including the first the extracellular <span id="Blue">CG</span> binding site (e.g. 111-<span class="Rborder"><span id="Blue">Q</span><b>A</b><span id="Dred">STS</span><span id="Ror">EE</span><b>PA</b><span id="Ror">DD</span><span id="Blue">N</span></span>-122) located between <b>TM-1</b> and <b>TM-2</b> (<b>Fig. 7</b>,<b>8</b>). The blue coloured rows identifies species that either specialize on <b>cardenolide</b> producing plants, or are known to be "<i>insensitive</i>" to these toxins (e.g. <i>M. musculus</i> and <i>R. norvegicus</i>).<b><sup>112,117</sup></b> The light yellow coloured rows are known <span id="Blue">CG</span>-sensitive species (reference sequences). The amino acid identities shown on the top are those of <i>O. areis</i> (reference). Structural studies (<b>Fig. 8</b>) show that the side chains of several of these referenced amino acid residues affect <b>cardenolide</b>-binding. The multisequence alignment (MSA) was generated with the <b>T-COFFEE</b> algorithm (default settings) using the <b><a class="one" href="https://www.jalview.org/">Jalview</a></b> workbench.<b><sup>122</sup></b> Dots indicate identity, dashes indicate missing amino acid sequences, and letters identify amino acid substitutions. Although many of the amino acid residues are conserved (<b>Note:</b> see <b>consensus</b> sequence and the associated variants at each position), there are several sites that appear to be mutational "<i>hotspots</i>" (i.e. <span id="Blue">Gln</span>-111, <span id="Dred">Ser</span>-115, <b>Ala</b>-119 and <span id="Blue">Asn</span>-122). One so-called <u>permissive</u> substitution, <b>Ala</b>119<span id="Dred">Ser</span>, has recently been shown to compensate for the lethal affects of other commonly observed amino acid substitutions (i.e. <span id="Blue">Gln</span>111<b>Leu</b>, <span id="Blue">Gln</span>111<b>Val</b>, <span id="Blue">Gln</span>111<span id="Dred">Thr</span>, <span id="Blue">Asn</span>122<span id="Purple">His</span>, <span id="Blue">Gln</span>111<b>Val</b>/<span id="Blue">Asn</span>122<span id="Purple">His</span>, <span id="Blue">Gln</span>111<span id="Dred">Thr</span>/<span id="Blue">Asn</span>122<span id="Purple">His</span>).<b><sup>133</sup></b> It was estimated that <b>Ala</b>119<span id="Dred">Ser</span> in combination with either <span id="Blue">Gln</span>111<b>Leu</b>, <span id="Blue">Gln</span>111<b>Val</b>, <span id="Blue">Gln</span>111<span id="Dred">Thr</span>, and <span id="Blue">Asn</span>122<span id="Purple">His</span>, increased the level of cardenolide-insensitivity by <b>7</b>, <b>11</b>, <b>28</b> and <b>178</b>-<b>fold</b> fold, respectively.<b><sup>133</sup></b>  
</figcaption>
</figure>
</div>

&nbsp; &nbsp; If <span id="Blue">CG</span> consuming insects do not carry toxin-insensitive genetic variants of 
<span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>**ase**, than how do they survive? Although polar <span id="Blue">CG</span> are unable to passively cross the **<a class="one" href="https://www.ncbi.nlm.nih.gov/books/NBK27105/">gut epithelial</a>** or **<a class="one" href="https://www.ncbi.nlm.nih.gov/books/NBK570152/">perineurial</a> barriers**,**<sup>134,135</sup>** the more toxic non-polar <span id="Blue">CG</span> can, and thus represent a significant challenge for phytophagous insects that specialize on these toxic plants. Fortunately, most organisms can metabolize toxic lipophilic compounds using **mixed function oxidases** (**MFO**), otherwise known as **cytochrome P450 mono-oxygenases** (**CYP450**).**<sup>136-140</sup>** During the initial phase of the detoxification process **CYP450** catalyze the **oxidation** of toxins, typically via **hydroxylation** (i.e. addition of a **hydroxyl** group, --<span id="Red">O</span><span id="Blue">H</span>) or **epoxidation** (i.e. formation of an **epoxide** group, a cyclic **ether** where oxygen is covalently bonded to two adjacent carbon atoms) reactions.**<sup>140,141</sup>** Generally the added **hydroxyl** groups serve as attachment sites for much larger hydrophilic moieties, specifically **glutathione** and **glucuronic acid**.**<sup>142-146</sup>** The **transferases** responsible for these reactions (i.e. **Glutathione S-transferases** and **UDP-glucuronyltransferases**, respectively) constitute **<a class="one" href="https://www.ncbi.nlm.nih.gov/books/NBK13169/">Phase II</a>** of the detoxification process. Being more polar (i.e. water soluble) and less toxic these metabolized toxins can now be eliminated from the cell via protein efflux pumps (**<a class="one" href="https://www.ncbi.nlm.nih.gov/books/NBK13169/">Phase III</a>**), such as **P-Glycoprotein**.**<sup>146-149</sup>** This well known <span id="Red">ATP</span>-**binding cassette transporter** (**ABC transporter**) is not only responsible for multi-drug resistant in many cancer cells,**<sup>150</sup>** but also transports many metabolized products of **CYP450** enzymes.**<sup>151,152</sup>** 
It is interesting to note the "*double edge*" nature of **CYP450** enzymes, in that plants use these **oxidases** to make important <span id="Dred">terpenoids</span> like <span id="Blue">CG</span>,**<sup>153</sup>** whereas some insect **CYP450** are used to break down these toxic <span id="Dred">terpenoids</span>. This underscores the universal nature of **CYP450** (i.e. found in all 5 biological **Kingdoms**) and how their functions (i.e. majority used in synthesis or oxidation of steroids and other <span id="Dred">terpenoids</span>) have been tailored to the needs of the organism.**<sup>154</sup>** Another prime example of this would be how some plant **CYP450** are used by to synthesize <span id="Gr">lignins</span> whereas some fungal **CYP450** are used to degrade these <span id="Dred">terpenoids</span> (i.e. 2<sup>nd</sup> most abundant biopolymer on the planet).**<sup>154,155</sup>** 

<!------------------------------------------------------->
<!------- FIG 10 - NaKATPase - Phylogenetic Tree -------->
<!------------------------------------------------------->
<a id="Fig_NKAtree"></a>
<div align=center>
<figure>
<img src="images/NKA_PhyloGen_TREE.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 10: Evolutionary Analysis of the &alpha;-subunit of <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>ase</u></b>. A linear phylogenetic tree was generated with the aid of the Molecular Evolutionary Genetics Analysis software package (<b>MEGA11</b>).<b><sup>156</sup></b> The evolutionary analysis of the 41 distinct amino acid sequences was inferred by using the <b>Maximum Likelihood</b> method and JTT matrix-based model.<b><sup>157</sup></b> The resulting bootstrap consensus tree is taken to represent the evolutionary history of the insect taxa. Branches corresponding to partitions reproduced in less than 50% bootstrap replicates are collapsed. The percentage of replicate trees in which the associated taxa clustered together in the bootstrap test (100 replicates) are shown next to the branches.<b><sup>158</sup></b> Initial tree(s) for the heuristic search were obtained automatically by applying Neighbor-Join and BioNJ algorithms to a matrix of pairwise distances estimated using the JTT model, and then selecting the topology with superior log likelihood value. Representative insect species that specialize on cardenolide-producing plants were chosen from 5 different taxonomic <b>Orders</b> (&#x24BD; = Hemiptera, &#x24C4; = Orthoptera, &#x24B9; = Diptera, &#x24B8; = Coleoptera, and &#x24C1; = Lepidoptera). Four commonly substituted amino acids within the cardenolide-binding site of the enzyme have been mapped (using colored spheres) onto the phylogenetic tree (i.e. <span id="Blue">Gln</span>111<b>Leu</b>, <span id="Blue">Gln</span>111<b>Val</b>, <span id="Blue">Gln</span>111<span id="Dred">Thr</span>, <span id="Blue">Gln</span>111<span id="Purple">His</span>, <span id="Dred">Ser</span>115<b>Val</b>, <span id="Dred">Ser</span>115<span id="Or">Glu</span>, <b>Ala</b>119<span id="Dred">Ser</span>, <span id="Blue">Asn</span>122<span id="Purple">His</span>) to help visualize their evolutionary history. The tree topology (branching horizontal lines) has also been color coded to highlight these four favoured mutations. One clear pattern is the wide phylogenetic distribution of the <b>Ala</b>119<span id="Dred">Ser</span> substitution, and more select phylogenetic distribution of the <span id="Blue">Asn</span>122<span id="Purple">His</span> substitution. Many of the later species actively sequester <span id="Dred">cardenolides</span> within their tissues (e.g. <i>D. plexippus</i>, <i>D. erippus</i>, <i>O. fasaciatus</i>).  

</figcaption>
</figure>
</div>

<!---------------------------------------------------->
<!------ SECTION 2.3.2: Terpenoids - CG Med. --------->
<!---------------------------------------------------->
<a id="CGmed"></a>
<span id="BBlk">&thinsp; 2.3.2 MEDICAL APPLICATIONS OF CARDIAC GLYCOSIDES &thinsp;</span>**:** <span id="Blue">CG</span> (i.e. **digoxin**, **digitoxin**) derived from *Digitalis lanata* and *Digitalis purpurea* (foxglove plants) have been used for many years to treat chronic heart failure and some arrhythmias. It was first championed over 200 years ago (1785 AD) by **William Withering**, an English physician who described its use in a publication entitled "*An Account of the Foxglove, and Some of its Medical Uses: with Practical Remarks on Dropsy, and Other Diseases*".**<sup>159</sup>** The term <u>dropsy</u> used in the publication's title is an old word for **edemia** (i.e. an abnormal accumulation of body fluid), a condition commonly associated with congestive heart failure. Despite its long use by herbalists and physicians to treat heart failure, the cellular mechanism of action of <span id="Blue">CG</span> only emerged after Cattel and Gold (1938) demonstrated that it could enhance the contraction of heart muscle proteins (i.e. positive inotropic effect).**<sup>160</sup>** Today, we know that inhibition of <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>**ase** by <span id="Blue">CG</span> raises cytoplasmic sodium levels, which in turn inhibits the <span id="Purple">Na</span><sup>+</sup>/<span id="Gold">Ca</span><sup>+2</sup><span id="Dred">exchanger</span>. The latter protein removes <span id="Gold">Ca</span><sup>+2</sup> from cells in exchange for <span id="Purple">Na</span><sup>+</sup> using the energy stored in the aforementioned **electrochemical gradient**. Ultimately, it is this increase in the intracellular [<span id="Gold">Ca</span><sup>+2</sup>] that stimulates heart muscle contraction.**<sup>161</sup>** However, the mechanism of action of <span id="Blue">CG</span> appears to be much more complex than simply inhibiting the <span id="Purple">Na</span><sup>+</sup><span id="Dbr">K</span><sup>+</sup><span id="Red">ATP</span>**ase**. Since the late 1990s many studies have shown that <span id="Blue">CG</span> can stimulate cell signaling events at doses (i.e. 1-10 nM) far below those needed (i.e. >1 &micro;M) to significantly inhibit the <span id="Purple">Na</span><sup>+</sup><span id="Dred">pump</span> (i.e. intracellular [<span id="Purple">Na</span><sup>+</sup>] unaltered).**<sup>162-167</sup>** Moreover, the <span id="Purple">Na</span><sup>+</sup><span id="Dred">pump</span> is not the only intracellular protein that binds to <span id="Blue">CG</span>. In a recent high-throughput drug screening study <span id="Dred">bufalin</span> was show to specifically bind to **Steroid receptor co-activator 3** (**SRC3**), a prominent activator of steroid receptors and transcription factors.**<sup>168</sup>**  
&nbsp; &nbsp; Although <span id="Blue">CG</span> like **digitoxin** are not the drug of choice in the treatment of chronic heart disease, they appear to have found new life as potential anti-cancer drugs. Despite initial reports of their anti-neoplastic activity back in the late 1960s, it was not until the 1980s when clinical studies formally showed that <span id="Blue">CG</span> could be used in anti-cancer therapies.**<sup>169-171</sup>** Since that time many *in vitro* (cell culture) and *in vivo* (animal) studies have shown <span id="Blue">CG</span> can inhibit the growth of many types of human cancer cells.**<sup>172-176</sup>** Moreover, numerous on-going clinical trials are evaluating the use of several <span id="Blue">CG</span> like **<a class="one" href="https://beta.clinicaltrials.gov/search?distance=50&term=digoxin&cond=Neoplasms&limit=100&page=1">digoxin</a>** and **<a class="one" href="https://beta.clinicaltrials.gov/search?distance=50&term=Huachansu&cond=Neoplasms&limit=100">Huachansu</a>** (i.e. traditional Chinese medicine, derived from *Bufo bufo gargarizans Cantor*) in the treatment of various cancers. Part of the excitement surrounding <span id="Blue">CG</span> stems from their potential use in the treatment of "*troublesome*" cancers that are resistant to conventional chemotherapeutic agents.**<sup>176</sup>** Since <span id="Blue">CG</span> can trigger more than one type of cell death (i.e. necrotic, autophagy, apoptosis, anoikis, or immunogenic) they may help sensitize cancer cells to conventional radiotherapy and chemotherapeutic agents.**<sup>177-181</sup>**  

<!---------------------------------------------->
<!----------- SECTION 3: Proteases ------------->
<!---------------------------------------------->
<a id="Prot"></a>
<span id="BBlk">&thinsp; 3. PROTEASES &thinsp;</span>**:** This large group of catalytic proteins (also known as **proteinases**, **peptidases** or **proteolytic enzymes**) are a common component of plant **latex**.**<sup>76</sup>** Functionally <span id="Dred">proteases</span> catalyze the *cleavage* of **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:16670">peptide bonds</a>** that link amino acids together, and how they achieve this (i.e. mechanisms) serves as a convenient way of classifying them.**<sup>182-185</sup>**  In total there are six distinct groups, namely: **(i) cysteine** (**Cys**); **(ii) serine** (**Ser**); **(iii) threonine** (**Thr**); **(iv) aspartic** (**Asp**); **(v) glutamic** (**Glu**) and **(vi) metallo** <span id="Dred">proteases</span>. The first three enzyme classes use either a **Cys**, **Ser** or **Thr** amino acid (respectively) as a **<a class="one" href="http://www.chem.ucla.edu/~harding/IGOC/N/nucleophile.html">nucleophile</a>** to "*attack*" the **peptide bond**, while the other three groups use an <u>activated</u> water molecule to perform the same task. Note that a **nucleophile** ("*nucleus*" loving) is an <u>electron-rich</u> reactant (e.g. *functional* group of an amino acid side chain) that shares a pair of electrons with an **<a class="one" href="http://www.chem.ucla.edu/~harding/IGOC/E/electrophile.html">electrophile</a>** ("*electron*" loving) when forming a new covalent bond (**Fig. 11**). The side chain of <span id="Gold">Cys</span> (-**C**<span id="Blue">H</span><sub>2</sub>-<span id="Gold">S</span><span id="Blue">H</span>), <span id="Dred">Ser</span> (-**C**<span id="Blue">H</span><sub>2</sub>-<span id="Red">O</span><span id="Blue">H</span>) and <span id="Dred">Thr</span> (-**C**<sub>2</sub><span id="Blue">H</span><sub>5</sub>-<span id="Red">O</span><span id="Blue">H</span>) all contain reactive <u>nucleophilic</u> atoms (i.e. <span id="Red">O</span>, <span id="Gold">S</span>). This is also true of the water molecule (<span id="Blue">H</span><sub>2</sub><span id="Red">O</span>) which is *activated* by <u>electrostatic interactions</u> with either a **metal ion** (e.g. <span id="Rasp">Zn</span><sup>+2</sup>) or the negatively charged side chains of <span id="Or">Asp</span> or <span id="Or">Glu</span>. These types of interactions between neighbouring amino acid side chains is why normally unreactive amino acids are capable of carrying out chemical reactions (**Fig. 11**).  

<!---------------------------------------------------->
<!------- FIG 11 - Serine Protease Mechanism  -------->
<!---------------------------------------------------->
<a id="Fig_SerProt"></a>
<div align=center>
<figure>
<img src="images/Triad_SerProt_mech.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 11: Serine Proteases</u></b>. <b>(A)</b> This well characterized enzyme family possesses a <u>triad</u> of active amino acids at its catalytic core, with the <span id="Red">O</span> atom of the <span id="Dred">serine</span> (<span id="Dred">Ser</span>) side chain serving as a <b><a class="one" href="http://www.chem.ucla.edu/~harding/IGOC/N/nucleophile.html">nucleophile</a></b> that initiates the chemical "<i>attack</i>" on the <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:16670">peptide bond</a></b>. Structural studies suggest that the <u>triad</u> functions like a "<i>charge-relay system</i>", where negatively charged electrons flow from "<i>electron-rich</i>" atoms (i.e. <b><a class="one" href="http://www.chem.ucla.edu/~harding/IGOC/N/nucleophile.html">nucleophiles</a></b>) to "<i>electron-deficient</i>" atoms (i.e. <b><a class="one" href="http://www.chem.ucla.edu/~harding/IGOC/E/electrophile.html">electrophiles</a></b>).<b><sup>186</sup></b> Arrows illustrate the direction of the electron flow (i.e. arrow head pointing directly at the electrophilic atom). Formal negative charges (i.e. "<i>charge centers</i>") that develop within the <u>triad</u> are highlighted. The "<i>charge-relay</i>" begins when a pair of electrons moves from the negatively charged <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:91007">carboxylate group</a></b> (&ndash;<b>C</b><span id="Red">OO</span><sup>-</sup>) of <b>Aspartic acid</b> (<span id="Or">Asp</span>) to the <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:14434">imidazole group</a></b> (&ndash;<b>C</b><sub>3</sub><span id="Gr">N</span><sub>2</sub><span id="Blue">H</span>) of <b>Histidine</b> (<span id="Purple">His</span>, steps &#9312; &rArr; &#9313;). This in turn allows the nucleophilic <span id="Gr">N</span> atom of <span id="Purple">His</span> to catalyze the removal of a proton (<span id="Blue">H</span><sup>+</sup>) from the hydroxyl group of <span id="Dred">Ser</span> (steps &#9314;). The leftover electron pair remains with the <span id="Red">O</span> atom creating a new "<i>charge center</i>" in the process (step &#9315;). The newly activated <span id="Dred">Ser</span> can now "<i>attack</i>" the <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:23019">carbonyl group</a></b> (&ndash;<b>C</b>=<span id="Red">O</span>) of the <b>peptide bond</b> (<b>B</b>, step &#9316;). This "<i>nucleophilic attack</i>" triggers the movement of a pair of electrons from the double bond to the adjacent <span id="Red">O</span> atom, producing a short-lived <b>oxyanion</b> species (&ndash;<b>C</b>&ndash;<span id="Red">O</span><sup>-</sup>) that is stabilized by electrostatic interactions within the <b>oxyanion hole</b> (step &#9317;). The eventual collapse of the <b>oxyanion</b> re-establishes the carbonyl group (&ndash;<b>C</b>=<span id="Red">O</span>, step &#9318;), severing the <b>peptide bond</b> in the process (step &#9319;). This process is made possible by the formation of a good leaving group (<b>R</b><sub>1</sub>&ndash;<span id="Gr">N</span><span id="Blue">H</span><sub>2</sub>) courtesy of <span id="Purple">His</span> which donates a <span id="Blue">H</span><sup>+</sup> to help catalyze the reaction (<b>C</b>, &#9320;). Following the release of the <span id="Gr">N</span>-terminal half of the protein a <b>hydrolysis</b> reaction takes place that triggers the flow of electrons to the remaining half of the protein (<b>D</b>, steps &#9323; &rArr; &#9326;). A new short-lived <b>oxyanion</b> species (&ndash;<b>C</b>&ndash;<span id="Red">O</span><sup>-</sup>) is formed (<b>E</b>, step &#9327;), which quickly collapses resulting in the formation of a new <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:91007">carboxylate group</a></b> (&ndash;<b>C</b><span id="Red">OO</span><sup>-</sup>) on the <span id="Gr">N</span>-terminal end of the leaving protein and the movement of electrons in the direction of <span id="Or">Asp</span> to reset of the "<i>charge relay</i>" system (<b>E</b>, steps &#9328; &rArr; &#9331;).  

</figcaption>
</figure>
</div>

<!---------------------------------------------->
<!----------- SECTION 3.1: Proteases ------------->
<!---------------------------------------------->
<a id="Prot_Func"></a>
<span id="BBlk">&thinsp; 3.1 PROTEASE FUNCTIONS &thinsp;</span>**:** These enzymes not only break down proteins that are misfolded, damaged or deemed harmful (e.g. toxins), but also help regulate most biological processes, including the response of plants to pests and pathogens.**<sup>187</sup>** The importance of **proteases** to plants is highlighted by the sheer number of **protease** encoding genes found in most plant **genomes**. For example, the **genome** of *Arabidopsis thaliana*, an important model organism in biology, encodes over 800 **protease** genes.**<sup>185</sup>**  
&nbsp; &nbsp; Historically, the proteolytic activity of plant **latex** was used not only as a meat tenderizer (e.g. **papain** found in tropical papaya tree *Carica papaya* latex),**<sup>188</sup>** but also for the treatment of various ailments, including burns, wounds and gastro-intestinal parasites.**<sup>189-193</sup>** Current evidence also suggests that **latex** derived **proteases** may complement current anti-cancer therapies due to their anti-inflammatory and immune modulating activity.**<sup>194-196</sup>** As for Milkweed **latex**, we know that they do indeed contain several **proteases**. In fact, the earliest scientific report of **latex** derived proteolytic activity was a 1940 study of Showy Milkweed, *Asclepias speciosa*.**<sup>197</sup>** Today we know that the **latex** of more than 100 different species of plants contain at least one **protease**.**<sup>188</sup>**   

<!------------------------------------------>
<!---------- TABLE 3 - PROTEASES ----------->
<!------------------------------------------>
<a id="ProtTab"></a>

<table class="Table">
    <thead>
      <tr style="text-align:left">
        <td colspan="4"><span id="Blk20"><span id="Blk">TABLE 3.</span> Plant Latex <span id="Dred">Proteases</span></span></td>
      </tr>
    <thead>
      <tr>
        <th class="f18"><span id="Blk">CLASS</span></th>
        <th class="f18"><span id="Blk">NAME</span></th>
        <th class="f18"><span id="Blk">PLANT</span></th>
        <th class="f18"><span id="Blk">DESCRIPTION</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><span id="Blk">SERINE PEPTIDASE</span></td>
        <td><span id="Blk"><a class="one" href="https://www.ncbi.nlm.nih.gov/pubmed/9824298">Taraxalisin</a></span></td>
        <td class="tcell"><span id="Blk"><i>Taraxacum officinale Webb</i> </span></td>
        <td>This protease, found with a common Central Asia <b>Dandelion</b> plant, is a member of the <strong>Subtilisin</strong> family of serine proteases. This root enzyme shows maximal activity in April at the beginning of plant development.</td>
      </tr>
      <tr>
        <td><span id="Blk">SERINE PEPTIDASE</span></td>
        <td><span id="Blk"><b><a class="one" href="https://www.ncbi.nlm.nih.gov/pubmed/16839575">Milin</a></b></span></td>
        <td class="tcell"><span id="Blk"><i>Euphorbia milii Des.</i></span></td>
        <td>This unique serine protease, found within the "<i>crown of thorns</i>" plant of Madagascar, is glycosylated. Raw latex is used in traditional medicine to treat parasites (i.e. liver fluke, schistosomiasis in sheep, cattle, and humans). </td>
      </tr>
      <tr>
        <td><span id="Blk">CYSTEINE PEPTIDASE</span></td>
        <td><span id="Blk"><b><a class="one" href="https://www.ncbi.nlm.nih.gov/pubmed/32572064/">Papain</a></b></span></td>
        <td class="tcell"><span id="Blk"><i>Carica papaya</i></span></td>
        <td>This well known Papaya enzyme has Factor XIIIa-like and thrombin-like activity (i.e. blood clotting), which makes it an effective agent in the treatment of wounds.</td>
      </tr>
      <tr>
        <td><span id="Blk">ASPARTATE PEPTIDASE</span></td>
        <td><span id="Blk"><b><a class="one" href="https://www.ncbi.nlm.nih.gov/pubmed/28387349/">Ficins</a></b></span></td>
        <td class="tcell"><span id="Blk"><i>Ficus racemosa</i></span></td>
        <td>The latex of the Indian Fig Tree is used to treat boils, diarrhea, dysentery, and hemorrhoids. It is also reportedly used to treat stomach ache, cholera and skeletal fractures.</td>
      </tr>
    </tbody>
</table>

<!------------------------------------------->
<!--------- SECTION 4: Phenolics ------------>
<!------------------------------------------->
<a id="Phenolics"></a>
<span id="BBlk">&thinsp; 4. PHENOLICS &thinsp;</span>**:** are probably the most common group of plant <u>secondary metabolites</u>. Structurally, <span id="Dred">Phenolics</span> contain one or more hydroxyl groups (&ndash;<span id="Red">O</span><span id="Blue">H</span>) covalently bonded to a <u>benzene ring</u> (&ndash;**C**<sub>6</sub><span id="Blue">H</span><sub>6</sub>), with the simplest <span id="Dred">Phenolic</span> being <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/996">phenol</a></b> (**C**<sub>6</sub><span id="Blue">H</span><sub>5</sub>&ndash;<span id="Red">O</span><span id="Blue">H</span>). It should be noted that the <u>benzene ring</u> is a conjugated *pi*-system, that is to say it contains alternating double and single bonds (see: <b><a class="one" href="https://chem.libretexts.org/">sigma-pi model</a></b>). Why is this important? Well, *pi* orbitals are not confined to the space between the two double-bonded carbon atoms. In fact, these electrons are shared by the entire *pi*-bonded system, essentially forming an extended <u>molecular orbital</u>. This arrangement of overlapping electron orbitals (i.e. *sigma*-*pi* double bond) can be conceptualized as a "*hot dog in a bun*", with the shared electrons making up the *sigma* bond (i.e. along the plane of the molecule, corresponding to the "*hot dog*"), and the cloud of <u>delocalized</u> (i.e. "free") electrons making up the *pi* bonds (located above and below the plane of the molecule, corresponding to the "*bun*"). It is the cloud of <b><a class="one" href="https://chem.libretexts.org/">delocalized electrons</a></b> in the *pi* bonds that can move along the entire length of the conjugated *pi*-system, which allows them to capture **photons** of longer wavelengths. The actual *size* of the wavelength of light it captures depends upon the *size* or length of the conjugated *pi*-bond system, similar to how a <u>radio antenna</u> interacts with photons along its length. So, the longer the conjugated *pi*-system, the longer the wavelength (i.e. lower energy) of light it captures. For example, <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/445354">retinol</a></b> (**vitamin A**) has <u>five</u> conjugated double bonds and absorbs the <span id="Purple">violet</span> part of the visible spectrum, thus appearing <span id="Gold">yellow</span> (i.e. reflects <span id="Gr">green</span> and <span id="Red">red</span> light), while the more highly conjugated <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5280489">&beta;-carotene</a></b> (i.e. <u>eleven</u> conjugated double bonds) absorbs lower energy <span id="Blue">blue</span> and <span id="Gr">green</span> light, thus appearing <span id="Or">orange</span> (i.e. reflects <span id="Gold">yellow</span> and <span id="Red">red</span> light). In fact there are many plant compounds that contain these conjugated *pi*-systems (i.e. natural sources of pigments and dyes). More importantly, the production of <span id="Dred">Phenolics</span> was an important evolutionary event for plants.**<sup>198,199</sup>** Approximately 450 million years ago plants moved out of the water and on to land. Prior to this life was restricted to the oceans due to <u>high levels</u> of solar UV radiation (i.e. deadly **ionizing radiation**). Unlike visible light, these shorter wavelengths (180-400 nm) of UV light have enough energy to break chemical bonds and thus destroy biomolecules like <span id="Blue">DNA</span>. Fortunately, with the evolution of photosynthetic cyanobacteria some 3 billion years ago, <span id="Red">O</span><sub>2</sub> began to accumulate within the atmosphere. Although oxygen can absorb UV light it is <u>ozone</u> (<span id="Red">O</span><sub>3</sub>), <b><a class="one" href="https://ozonewatch.gsfc.nasa.gov/education/index.html">a product of oxygen interacting with UV light</a></b>, that is responsible for absorbing most of the harmful UV light from the Sun. Without this <b><a class="one" href="https://www.acs.org/content/acs/en.html">ozone layer</a></b> UV radiation would sterilize the surface of the Earth. Fortunately, by ~450 million years ago enough UV absorbing **ozone** had accumulated within the upper atmosphere to allow plants to safely colonize land. Nevertheless, there are still parts of the UV spectrum (280-380 nm, or **UVB**) that penetrate the upper atmosphere and reach the surface. As a result plants evolved strategies that could deal with this band of ionizing radiation, largely in the form of <span id="Dred">Phenolics</span>.**<sup>200</sup>** As I mentioned above, the conjugated *pi*-systems of phenolics are very good at absorbing UV light, which makes them ideal **UV light screens**.**<sup>201</sup>** In fact, there are a number of phenolic compounds that are common ingredients of suntan lotion, including **para-amino benzoic acid** or <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/978">PABA</a></b> (**Fig. 12**).

<!----------------------------------------------------->
<!--------- PNP SECTION 4.1: PHENOLIC CLASSES --------->
<!----------------------------------------------------->
<a id="Phen_Class"></a>
<span id="BBlk">&thinsp; 4.1 PHENOLICS CLASSES &thinsp;</span>**:** There are several classes of plant <span id="Dred">Phenolics</span> based on the number of phenol groups and bridging carbons that link them together (**Table 4**).**<sup>202</sup>** These compounds are synthesized via two major biochemical pathways: **(i)** the <span id="Dred">Shikimic acid</span> pathway and **(ii)** the <span id="Dred">Polyketide</span> (acetate/malonate) pathway. The <span id="Dred">Shikimic acid</span> pathway produces large numbers of the most common plant <span id="Dred">Phenolics</span>, such as <span id="Dred">benzoic acid</span> derivatives (**C**<sub>6</sub>-**C**<sub>1</sub> carbon skeleton), <span id="Dred">phenylpropanoids</span> (**C**<syb>6</sub>-**C**<sub>3</sub> carbon skeleton) such as <span id="Dred">coumarins</span> (>1300 structures), <span id="Dred">flavonoids</span> (**C**<sub>6</sub>-**C**<sub>3</sub>-**C**<sub>6</sub>, >7000 structures) and <span id="Dred">stilbenoids</span> (**C**<sub>6</sub>-**C**<sub>2</sub>-**C**<sub>6</sub>). The <span id="Dred">Polyketide</span> (acetate/malonate) pathway attaches poly-*ketide* chains (**C=**<span id="Red">O</span>**-C**<span id="Blue">H</span><sub>2</sub>)<sub>n</sub>-**starter**) to a variety of starter compounds, including smaller <span id="Dred">phenolics</span> and <span id="Dred">alkaloids</span> (**Fig. 12**). Both pathways are summarized below. 

<!------------------------------------------>
<!---------- TABLE 4 - PHENOLICS ----------->
<!------------------------------------------>
<a id="PhenTab"></a>

<table class="Table">
    <thead>
      <tr style="text-align:left">
        <td colspan="4"><span id="Blk20"><span id="Blk">TABLE 4.</span> Plant <span id="Dred">Phenolics</span></span></td>
      </tr>
    <thead>
      <tr>
        <th class="f18"><span id="Blk">CLASS</span></th>
        <th style="width:40%" class="f18"><span id="Blk">EXAMPLE STRUCTURE</span></th>
        <th class="f18"><span id="Blk">STRUCTURE DESCRIPTION</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><span id="Blk">SIMPLE PHENOLS</span> <br> (<b>C<sub>6</sub></b>)</td>
        <td><img src="images/C6_catechol.jpg" alt="" width="100px"/></td>
        <td><b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/289">CATECHOL</a></b> - is found in small amounts in many fruits and vegetables. The rapid <em>browning</em> of a cut apple is due to enzymatic oxidation (i.e. polyphenol oxidase) of these compounds. Plants produce it as a defence against herbivory (i.e. <b>allelochemical</b>). It is also a genotoxic organic compound (i.e. can induce DNA damage)</td>  
      </tr>
      <tr>
        <td><span id="Blk">PHENOLIC ACIDS</span> <br> (<b>C<sub>6</sub>-C<sub>1</sub></b>)</td>
        <td><img src="images/C6C1_salicylic_acid.jpg" alt="" width="115px"/></td>
        <td><b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/338">SALICYLIC ACID</a></b> - a well known plant hormone. Commonly extracted from willow bark for its medicinal purposes (e.g. anti-fungal agent). A well known precursor of aspirin (acetylsalicylic acid). Found in many skin care products.</span></td>
      </tr>
      <tr>
        <td><span id="Blk">PHENYLETHANOIDS</span> <br> (<b>C<sub>6</sub>-C<sub>2</sub></b>)</td>
        <td><img src="images/C6C2_tyrosol.jpg" alt="" width="200px"/></td>
        <td><b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/10393">TYROSOL</a></b> - a natural anti-oxidant found in olive oil. Known for its cardio-protective effects (i.e. anti-inflammatory).</td>
      </tr>
      <tr>
        <td><span id="Blk">PHENYLPROPANOIDS</span> <br> (<b>C<sub>6</sub>-C<sub>3</sub></b>)</td>
        <td><img src="images/C6C3_caffeic_acid.jpg" alt="" width="175px"/></td>
        <td><b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/689043">CAFFEIC ACID</a></b> - an intermediate in <span id="Gr">lignin</span> biosynthesis that is found in many plants (e.g. thyme, sunflower seeds, apple sauce). It has anti-oxidant, anti-inflammatory, and anti-cancer properties.</td>
      </tr>
      <tr>
        <td><span id="Blk">NAPHTHOQUINONES</span> <br> (<b>C<sub>6</sub>-C<sub>4</sub></b>)</td>
        <td><img src="images/C6C4_Juglone.jpg" alt="" width="100px"/></td>
        <td><b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/3806">JUGLONE</a></b> - natural dye found in black walnut (<i>Juglans nigra</i>) that is used as a coloring agent (foods, cosmetics). Since it is toxic to many plants it is sometimes used as a natural herbicide.</td>
      </tr>
      <tr>
        <td><span id="Blk">XANTHONES</span> <br> (<b>C<sub>6</sub>-C<sub>1</sub>-C<sub>6</sub></b>)</td>
        <td><img src="images/C5C6C1C6C5_Mangostin.jpg" alt="" width="250px"/></td>
        <td><b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5281650">MANGOSTIN</a></b> - found in the Mangosteen tree (<i>Garcinia mangostana</i>) and known for its anti-oxidant, anti-microbial and anti-neoplastic activities.</td>
      </tr>
      <tr>
        <td><span id="Blk">ANTHRAQUINONES</span> <br> (<b>C<sub>6</sub>-C<sub>2</sub>-C<sub>6</sub></b>)</td>
        <td><img src="images/C6C2C6_resveratrol.jpg" alt="" width="200px"/></td>
        <td><b><span id="Blk"><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/445154">RESVERATROL</a></b> - a well known anti-oxidant (red grapes) and phytoalexin (i.e. plant anti-microbial compound). Also exhibits anti-inflammatory and anti-neoplastic activity.</td>
      </tr>
      <tr>
        <td><span id="Blk">FLAVONOIDS</span> <br> (<b>C<sub>6</sub>-C<sub>3</sub>-C<sub>6</sub></b>)</td>
        <td><img src="images/C6C3C6_Quercetin.jpg" alt="" width="200px"/></td>
        <td><b><span id="Blk"><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5280343">QUERCETIN</a></b> - an abundant plant flavonoid that exhibits anti-bacterial, anti-oxidant, anti-inflammatory and anti-neoplastic activities.</td>
      </tr>
      <tr>
        <td><span id="Blk">POLYPHENOLS</span> <br>(<b>(C<sub>6</sub>)<sub>n</sub></b>)</td>
        <td><img src="images/PolyPhenol_Ellagic_acid.jpg" alt="" width="175px"/></td>
        <td><b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/5281855">ELLAGIC ACID</a></b> - a hetero-tetracyclic compound found in many fruits and vegetables (e.g. chestnuts, walnuts, pecans, raspberries, strawberries, cranberries and grapes, etc.).</td>
      </tr>
    </tbody>
</table>

<!---------------------------------------------------------------->
<!--------- PNP Section 4.2: PHENOLICS - SHIKIMIC ACID  --------->
<!---------------------------------------------------------------->
<a id="Phen_Shik"></a>
<span id="BBlk">&thinsp; 4.2 PHENOLICS BIOSYNTHESIS &thinsp;</span>**:** The synthesis of <span id="Dred">Phenolics</span> links carbohydrate metabolism with the biosynthesis of numerous aromatic compounds, including the three aromatic amino acids <u>phenylalanine</u> (**Phe**), <u>tryptophan</u> (**Trp**) and <u>tyrosine</u> (<span id="Dred">Tyr</span>). However, since most animals do not produce **Phe** and **Trp**, they have to be acquired from their diet (i.e. classified as <u>essential</u> amino acids). Nevertheless, <span id="Dred">Tyr</span> can be derived from **Phe** via a one-step hydroxylation reaction (**Note: Fig. 12** <span id="Dred">arrow</span>). Although most plant <span id="Dred">Phenolics</span> are <u>cell wall</u> components there are many that also play an important role in the survival of plants.  
&nbsp; &nbsp; The majority of plant <span id="Dred">Phenolics</span> are produced via the <u>seven step</u> <span id="Dred">Shikimic acid</span> pathway, which converts <u>phosphoenolpyruvate</u> (**PEP**) and <u>erythrose 4-phosphate</u> (**E4P**) into **chorismate** (**Fig. 12**). Although <span id="Dred">Shikimic acid</span> is an intermediate within this pathway (i.e. step 4 product), its <u>steady-state levels</u> appears to be a good indicator of the overall metabolic status of plants.**<sup>203</sup>** Moreover, many intermediates within this pathway serve as starter material for other metabolic pathways. For example, **3-dehydroshikimate**, the <u>precursor</u> of <span id="Dred">Shikimate</span> (i.e. step 3), is a building block for **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:16918">gallic acid</a>**.**<sup>204,205</sup>** This astringent (i.e. mouth puckering) tri-hydroxylated derivative of **benzoic acid** is not only a common component of many plants (i.e stems, bark, roots, seeds, fruits), but also the building block for more complex **gallotannins**.**<sup>206</sup>** The importance of the <span id="Dred">Shikimic acid</span> pathway to plants and terrestrial ecosystems is perhaps best highlighted by <span id="Gr"><span id="Gr">lignin</span>s</span>, since these <span id="Dred">Phenolic</span> biopolymers account for approximately a third of all the organic carbon within the biosphere.**<sup>207</sup>** It is also interesting to note that the sixth enzyme in this pathway (i.e. 5-enolpyruvyl-3-shikimate phosphate synthase, or **EPSPS**) is inhibited by **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=27744">glyphosate</a>**, the most commonly used herbicide in the world. In fact, many genetically modified crop strains (e.g. soya beans, canola, corn and cotton) have been engineered to tolerate **glyphosate** (i.e. Monsanto's **Roundup Ready crops**).  

<!--------------------------------------------------------->
<!------- FIG 12 - Phenolic Biosynthesis Pathways  -------->
<!--------------------------------------------------------->
<a id="Fig_ShikPath"></a>
<div align=center>
<figure>
<img src="images/Shikimate_Pathway.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 12: <span id="Dred">Shikimate</span> Pathway</u></b>. The seven enzymatic steps of this pathway converts <b>phosphoenolpyruvate</b> (<b>PEP</b>) of the <b>glycolysis pathway</b> and <b>erythrose 4-phosphate</b> of the <b>pentose phosphate pathway</b> into <b>chorismate</b>. This end product is primarily used in plants and microorganisms to synthesize aromatic amino acids (<b>Phe</b>, <b>Trp</b> and <span id="Dred">Tyr</span>). However, <span id="Dred">Chorismate</span> is also used by plants to make a wide variety of aromatic <u>secondary metabolites</u>, particularly <i>para</i>-<b>coumaroyl</b>-<span id="Dred">CoA</span>. Both <span id="Dred">Chorismate</span> and <i>para</i>-<b>coumaroyl</b>-<span id="Dred">CoA</span> are central intermediates in the biosynthesis of numerous plant <b>natural products</b> such as <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:28794">coumarins</a></b>, <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:26776">stilbenoids</a></b>, <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:47916">flavonoids</a></b>, and other <b><a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:26004">phenylpropanoids</a></b>. Many of these compounds serve as <b>phytoalexins</b> (i.e.  anti-microbial compounds produced in response to biotic and abiotic stresses), while others provide protection from UV irradiation (e.g. <span id="Dred">flavonoids</span>, <b>benzoic acid</b> derivatives) or plant–pathogens (e.g. <b>salicylates</b>).<b><sup>199-201,203-207</sup></b>

</figcaption>
</figure>
</div>

&nbsp; &nbsp; As illustrated in **Figure 12** <span id="Dred">phenylpropanoids</span>, like **cinnamic acid**, are the building blocks for a wide variety of important plant <span id="Dred">Phenolics</span>.**<sup>201,203,206,207</sup>** Of the thousands of <span id="Dred">Phenolic</span> compounds perhaps <span id="Gr"><span id="Gr">lignin</span>s</span> are the most intriguing given their biological functions and evolutionary history. Firstly, these abundant <b>biopolymers</b> provide vascular plants with the bio-mechanical support they need to grow upright (i.e. important evolutionary adaptation needed to colonize land). They also provide protection from pests and pathogens since only a select group of species are capable of biochemically degrading them (i.e. some fungi and bacteria). <span id="Gr">Lignins</span> are also hydrophobic and therefore an ideal material to construct vessels dedicated to transporting water (i.e. **xylem**).**<sup>207,208</sup>** Moreover, comparative studies of 31 Fungal genomes suggest that the origin of <span id="Gr">ligninolytic</span> **enzymes** coincided with the end of the great "*carbon sequestration*" period that spanned the late **<a class="one" href="https://stratigraphy.org/timescale/">Carboniferous</a>** and **<a class="one" href="https://stratigraphy.org/timescale/">Permian</a>** periods (323-to-252 **Mya**).**<sup>209</sup>** This was a time when forested wetlands dominated the coastlines of equatorial land masses. According to the fossil record these ancient ecosystems were dominated by four groups of vascular plants: **(i) <a class="one" href="https://samnoblemuseum.ou.edu/common-fossils-of-oklahoma/plant-fossils/fossils-by-plant-group/fossil-lycophytes/">Lycophytes</a>** such as the iconic giant "*Scale trees*" (i.e. primitive **club mosses** that stood 30 meters tall); **(ii)** prop-rooted **<a class="one" href="https://samnoblemuseum.ou.edu/common-fossils-of-oklahoma/plant-fossils/green-plants/land-plants/seed-plants/cordaites/">Cordaites</a>** (early **gymnosperms**, >30 meters tall); **(iii) huge <a class="one" href="https://samnoblemuseum.ou.edu/common-fossils-of-oklahoma/plant-fossils/fossils-by-plant-group/fossil-sphenophytes/">Sphenophytes</a>** (**horsetails**, 20 meters tall); and **(iv)** seed bearing **<a class="one" href="https://samnoblemuseum.ou.edu/common-fossils-of-oklahoma/plant-fossils/fossils-by-plant-group/fossil-medullosans-/">Medullosans</a>** (**conifer**-like plants that resembled **ferns**, 5 meters tall).**<sup>210-213</sup>** The dominant **Lycophytes** were particualrly rich in <span id="Gr">lignins</span> owing to their unusual thick **bark** (i.e. highly <span id="Gr">lignified</span> **periderm**). Although these ancient ecosystems were directing most of their photosynthetically fixed carbon into <span id="Gr">lignin</span>-rich biomass there was likely no species of fungi that could break it down and release it back into the biosphere. The continuous drawing-down of carbon by these palaeotropical forests meant that much of the <span id="Gr">lignified</span> carbon would have been buried in the wetland's anoxic sediments. Trapped and slow to decay this carbon gave rise to peat and slowly transformed into coal over millions of years.**<sup>210-213</sup>**  
&nbsp; &nbsp; Although <span id="Dred">flavonoids</span> (**C**<sub>6</sub>**-C**<sub>3</sub>**-C**<sub>6</sub>) may not have a fabled history like <span id="Gr">lignins</span>, they do provide many important ecological goods and services such as: **(i)** a source of pigments; **(ii)** function as chemical attractants for pollinators; **(iii)** chemical stimulants for *Rhizobium* bacteria that fix nitrogen; **(iv)** chemical defense against herbivores and pathogens; and **(v)** natural UV sun screens.**<sup>201</sup>** For example, **Milkweed** <span id="Dred">flavonoids</span> have been shown to stimulate egg laying (i.e. <u>oviposition</u>) in **Monarch Butterflies**.**<sup>214-216</sup>** 

<!--------------------------------------------->
<!---------- TABLE 5 - Milkweed PNP ----------->
<!--------------------------------------------->
<a id="Mlkwd_PNPquant"></a>

<table class="Table">
    <thead>
      <tr style="text-align:left">
        <td colspan="5"><span id="Blk20"><span id="Blk">TABLE 5.</span> Milkweed <span id="Dred">Cardenolide</span> and <span id="Dred">Phenolic</span> Content</span></td>
      </tr>
    <thead>
      <tr>
        <th class="f18"><span id="Blk">SPECIES</span></th>
        <th class="f18"><span id="Blk">LEAF <span id="Dred">CG</span></span></th>
        <th class="f18"><span id="Blk"><span id="Dred">COUMARIC ACID</span> DERIVATIVES</span></th>
        <th class="f18"><span id="Blk"><span id="Dred">CAFFEIC ACID</span> DERIVATIVES</span></th>
        <th class="f18"><span id="Dred">FLAVONOIDS</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><i>A. exaltata</i></td>
        <td class="tmid">0.125</td>
        <td class="tmid">0.014</td>
        <td class="tmid">0.657</td>
        <td class="tmid">0.079</td>
      </tr>
      <tr>
        <td><i>A. hirtella (Pennell) Woodson</i></td>
        <td class="tmid">0.208</td>
        <td class="tmid">0.054</td>
        <td class="tmid">0.299</td>
        <td class="tmid">0.142</td>
      </tr>
      <tr>
        <td><i>A. incarnata L. incarnata</i></td>
        <td class="tmid">0.126</td>
        <td class="tmid">0.012</td>
        <td class="tmid">0.352</td>
        <td class="tmid">0.106</td>
      </tr>
      <tr>
        <td><i>A. tuberosa L.</i></td>
        <td class="tmid">0.064</td>
        <td class="tmid">0.035</td>
        <td class="tmid">0.475</td>
        <td class="tmid">0.076</td>
      </tr>
      <tr>
        <td><i>A. purpurascens L.</i></td>
        <td class="tmid">0.09</td>
        <td class="tmid">0.09</td>
        <td class="tmid">0.453</td>
        <td class="tmid">0.232</td>
      </tr>
      <tr>
        <td><i>A. verticillata L.</i></td>
        <td class="tmid">0.114</td>
        <td class="tmid">0.046</td>
        <td class="tmid">0.374</td>
        <td class="tmid">0.114</td>
      </tr>
      <tr>
        <td><i>A. viridiflora Raf.</i></td>
        <td class="tmid">0.095</td>
        <td class="tmid">0.153</td>
        <td class="tmid">0.044</td>
        <td class="tmid">0.139</td>
      </tr>
      <tr>
        <td><i>A. sullivantii Torr.</i></td>
        <td class="tmid">0.123</td>
        <td class="tmid">0.08</td>
        <td class="tmid">0.209</td>
        <td class="tmid">0.221</td>
      </tr>
      <tr>
        <td><i>A. syriaca L.</i></td>
        <td class="tmid">0.113</td>
        <td class="tmid">0.039</td>
        <td class="tmid">0.373</td>
        <td class="tmid">0.069</td>
      </tr>
      <tr>
        <td colspan="6"><b>NOTE:</b> Data values taken from the work of <b>Agrawal</b> and colleagues (2009) are mean % dry weight of ~7 <b>Milkweed</b> plants per species.<b><sup>217</sup></b> <span id="Dred">Phenolics</span> found in <b>Milkweeds</b> (across all taxa) were primarily composed of <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/637542">coumaric acid</a></b> (~10%), <b><a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/689043">caffeic acid</a></b> (~54%), and <span id="Dred">Flavonoids</span> (~36%). <span id="Dred">Cardenolides</span>
varied >14-fold across <b>Milkweed</b> species.<b><sup>217</sup></b></td>
      </tr>
    </tbody>
</table>

<!------------------------------------------>
<!--------- Section 5: POLYKETIDES --------->
<!------------------------------------------>
<a id="PKs"></a>
<figure class="FRight150">
<img src="images/Pyrone_Benzene.jpg" alt="" width="165px"/>
</figure>

<span id="BBlk">&thinsp; 5. PLANT POLYKETIDES &thinsp;</span>**:** Plant <span id="Dred">polyketides</span> are a structurally diverse group of compounds that are synthesized by *type III* **Polyketide Synthases** (<span id="Blue">PKS</span>).**<sup>218-220</sup>** Compared to the large "*assembly-line*" like multi-functional **type I** and **type II** <span id="Blue">PKS</span> complexes of bacteria and fungi, plant **type III** <span id="Blue">PKS</span> have a relatively simple architecture (i.e. simple homodimers with a single active site). The most well known plant **type III** <span id="Blue">PKS</span> are the **Chalcone** (<span id="Blue">CHS</span>) and **Stilbene** (<span id="Blue">STS</span>) synthases. This <span id="Blue">CHS</span>/<span id="Blue">STS</span> superfamily of enzymes are responsible for synthesizing many biologically important compounds, such as floral pigments, UV sun screens (i.e. protects against photo-damage) and **phytoalexins** (i.e. anti-microbial compounds).**<sup>218-220</sup>** All of these highly conserved **type III** <span id="Blue">PKS</span> use the same **triad** of amino acid residues (<span id="Gold">Cys</span>, <span id="Purple">His</span>, <span id="Purple">Asn</span>) to catalyze the initial reactions that can be conceptualized as follows: **(i)** the initial "*loading*" step involves the transfer of a <i>starter</i> **acyl group** (&#9398;, **Fig. 13**) from <span id="Red">Acetyl-CoA</span> to a central <span id="Gold">Cys</span>**teine** residue (bound *mono-ketide*, or **MK**) within the active site;**<sup>221-225</sup>** **(ii)** next the "*extension*" step involves the addition of a **C**<sub>2</sub> (acetate) group to the <i>starter</i> molecule courtesy <span id="Red">malonyl-CoA</span> (&#9410;). This is orchestrated by the **histidine** (<span id="Purple">His</span>) and **asparagine** (<span id="Purple">Asn</span>) **dyad** that catalyze the **decarboxylation** of <span id="Red">malonyl-CoA</span>. The resulting chemically reactive <span id="Red">acetyl-CoA</span> **anion** (&#10032; **Fig. 13**) catalyzes the **<a class="one" href="https://chemistrytalk.org/claisen-condensation/">Claisen condensation</a>** reaction that "*extends*" the <span id="Dred">polyketide</span> chain.**<sup>224</sup>** Although the initial *diketide* (**DK**) intermediate can undergo multiple "*extension*" reactions, this iterative process is limited by the physical dimensions and specificity of the active site;**<sup>224,226</sup>** and **(iii)** the final **polyketide** chain undergoes additional chemical modifications via one or more cyclization, aromatization, hydroxylation, glycosylation, acylation, or methylation reactions.**<sup>218-220</sup>** Overall plant <span id="Blue">PKS</span> are capable of generating a wide variety of <span id="Dred">polyketides</span> by simply varying the type of *starter* molecule, the number of  "*extension*" steps, as well as the number and types of post-extension chemical modifications.  

<!----------------------------------------------->
<!------- FIG 13 - Polyketide Synthesis  -------->
<!----------------------------------------------->
<a id="Fig_PKS"></a>
<div align=center>
<figure>
<img src="images/Plant_CHS_mech.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 13: Plant <span id="Dred">Polyketide</span> Biosynthesis</u></b>. <span id="Blue">PKS</span> use <span id="Red">CoA</span> <span id="Gold">thio</span><b>esters</b> for shuttling substrates and <b>poly-ketide</b> intermediates, and carry out all reactions via a <u>single</u> active site.<b><sup>218-220</sup></b> The starter molecule is loaded onto the <span id="Gold">thiol</span> group of a <span id="Gold">Cys</span><b>teine</b> residue located in the active site. <span id="Red">Malonyl-CoA</span>, which donates the <b>C</b><sub>2</sub> units used during the "<i>extension</i>" steps, occupies a large binding pocket adjacent to the central <span id="Gold">Cys</span> residue.<b><sup>221-225</sup></b> An important feature of <b>poly-ketides</b> is the juxtaposition of <b>carbonyl</b> (<b>C</b>=<span id="Red">O</span>) and <b>methylene</b> (&ndash;<b>C</b><span id="Blue">H</span><sub>2</sub>&ndash;) functional groups. This arrangement gives rise to chemically reactive <span id="Red">enol</span><b>ates</b> (<b>NOTE:</b> &#10032; <span id="Gold">thiol</span> <b>esters</b> undergo <b>enolization</b> more rapidly than with ordinary <b>esters</b> due to the nature of their conjugated bonds) that often result in a <b>1,3</b>-<span id="Red">O</span><b>xygenation</b> pattern, as well as <u>cyclic</u> <b>aromatic</b> and <b>pyrone</b> rings. During the "<i>loading</i>" step the positively charged <b>imidazole</b> of <b>histidine</b> (<span id="Purple">His</span>) helps to stabilize the reactive <i>nucleophilic</i> <span id="Gold">thiol</span><b>ate</b> anion of <span id="Gold">Cys</span> that extracts the <b>acyl</b> group (&ndash;[<b>C=</b><span id="Red">O</span>]&ndash;<b>R</b>) from the <span id="Red">CoA</span> carrier molecule.<b><sup>225</sup></b> This "<i>loading</i>" step is also aided by <span id="Blue">H</span>-bonding between a conserved <b>asparagine</b> (<span id="Purple">Asn</span>) residue and the <b>carbonyl</b> <span id="Red">O</span>xygen of the <span id="Gold">thiol</span><b>ester</b> (&ndash;<span id="Gold">S</span>&ndash;<b>C=</b><span id="Red">O</span>&ndash;<b>R</b>).<b><sup>224</sup></b> Bringing the <b>methylene</b> carbon of <span id="Red">malonyl-CoA</span> in close proximity to the <b>carbonyl</b> carbon of the starter <b>ketide</b> sets up the key <b>de-carboxylation</b> reaction of <span id="Red">malonyl-CoA</span> that generates the reactive <span id="Red">acetyl-CoA</span> <b>anion</b> (&#10032;). The liberation of <b>C</b><span id="Red">O</span><sub>2</sub> is assisted in part by <span id="Blue">H</span>-bonding between the conserved basic residues (<span id="Purple">His</span> and <span id="Purple">Asn</span>) and the <span id="Red">malonyl-CoA</span> substrate. These interactions help stabilize the reactive <span id="Red">acetyl-CoA</span> <b>anion</b> (&#10032;, electron "<i>rich</i>" <b>carbanion</b>) that "<i>attacks</i>" the <span id="Gold">thio</span><b>ester</b> bond of the bound starter molecule. This is an ideal pairing of reactive groups, since <span id="Red">enol</span><b>ates</b> are excellent "<i>nucleophiles</i>" (electron rich species) and <b>carbonyl</b> carbons are good "<i>electrophiles</i>" (electron poor species). The resulting <b>di-ketide</b> intermediate is then captured by the central <span id="Gold">Cys</span> that once again anchors the next round of "<i>extension</i>" reactions.<b><sup>220-225</sup></b> Structural and site-directed mutagenesis studies have shown that the volume of the active site cavity places limits on "<i>starter</i>" molecule specificity and the number of possible "<i>extension</i>" reactions (i.e. length of final <b>poly-ketide</b> product).<b><sup>224,226</sup></b>   
</figcaption>
</figure>
</div>

&nbsp; &nbsp; The chemical diversity of <span id="Dred">polyketides</span> underscores the varied roles they play in plants. For example <span id="Glacialb">anthocyanins</span> (**Greek**: *anthos* = flower, and *kyanos* = <span id="Glacialb">cyan blue</span>), a large subgroup of glycosylated <span id="Dred">flavonoids</span> (**Fig. 12**), are natural plant pigments that help attract animals for **pollination** and **seed** dispersal. They, like many other <span id="Dred">flavonoids</span>, are also natural sunscreens that protect against **UV** radiation. <span id="Glacialb">Anthocyanins</span> are well known for their <span id="Glacialb">antioxidant</span> activity (i.e. scavenge *<span id="Rasp">free radical</span>*), and also provide protection against herbivores, pests and pathogens.**<sup>227-232</sup>** All of these functions are made possible in large part by <span id="Blue">CHS</span>, since they play a major role in the biosynthesis of <span id="Dred">flavonoids</span>. Also, the <u>health benefits</u> associated with consuming foods that are rich in <span id="Glacialb">anthocyanins</span> (e.g. most colorful fruits and vegetables) is well known to most health conscious people. Numerous studies have shown that the <span id="Glacialb">antioxidant</span> activity of <span id="Dred">flavonoids</span> and other types of plant <span id="Dred">phenolics</span> can reduce the risk of developing chronic diseases (e.g. cancers, diabetes), as well as provide protection from several common pathogens (bacteria, fungi, viruses).**<sup>227,230-236</sup>**  

<!--------------------------------------------->
<!---------- TABLE 6 - ANTHOCYANINS ----------->
<!--------------------------------------------->
<a id="Tab6_Antho"></a>

<table class="Table">
    <thead>
      <tr style="text-align:left">
        <td colspan="8"><span id="Blk20"><span id="Blk">TABLE 6.</span> COMMON <span id="Glacialb">ANTHOCYANINS</span> IN HIGHER PLANTS</span></td>
      </tr>
    <thead>
      <tr>
        <td colspan="8" class="tmid"><img src="images/Anthocyanidin.jpg" alt="" width="300px"/></td>
      <tr>
        <th colspan="7" class="f18">Position</th>
        <th rowspan="2" class="f18">DESCRIPTION</th>
      </tr>
      <tr>
        <th class="f18">3</th>
        <th class="f18">5</th>
        <th class="f18">6</th>
        <th class="f18">7</th>
        <th class="f18">3'</th>
        <th class="f18">4'</th>
        <th class="f18">5'</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td><span id="OrRed">Cyanidin</span><b>:</b> orange-red pigment (<span id="OrRed">Cy</span>).</td>
      </tr>
      <tr>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td><span id="BRed">Delpinidin</span><b>:</b> a bluish-red pigment (<span id="BRed">Dp</span>).</td>
      </tr>
      <tr>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><b>C</b><span id="Blue">H</span><sub>3</sub></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><b>C</b><span id="Blue">H</span><sub>3</sub></td>
        <td><span id="BRed2">Malvidin</span><b>:</b> another bluish-red pigment.</span>
      </tr>
      <tr>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td><span id="Or">Pelargonidin</span><b>:</b> an orange pigment (<span id="Or">Pg</span>).</td>
      </tr>
      <tr>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><b>C</b><span id="Blue">H</span><sub>3</sub></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td><span id="OrRed2">Peonidin</span><b>:</b> another orange-red pigment.</td>
      </tr>
      <tr>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><b>C</b><span id="Blue">H</span><sub>3</sub></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td class="tmid"><span id="Red">O</span><span id="Blue">H</span></td>
        <td><span id="BRed">Petunidin</span><b>:</b> a bluish-red pigment.</td>
      </tr>
      <tr>
        <td colspan="8"><b>NOTE:</b> The <b>flavylium</b> cation (top structure) forms the backbone of these six common <span id="Glacialb2">anthocyanidins</span>. When one or more of the hydroxyl (&ndash;<span id="Red">O</span><span id="Blue">H</span>) side groups (&ndash;<b>R</b>) becomes glycosylated it is referred to as a <span id="Glacialb">anthocyanin</span>. Three of these <span id="Glacialb">anthocyanins</span> (<span id="OrRed">Cy</span>, <span id="BRed">Dp</span> and <span id="Or">Pg</span>) are the most common pigments (besides chlorophyll) found in nature (~80% of pigmented leaves, ~69% of fruits, ~50% of flowers). Both <span id="OrRed">Cy</span> and <span id="BRed">Dp</span> have been shown to be potent modulators of <b>SIRT6</b>, a <b>histone deacetylase</b> that plays a critical role in regulating genomic stability, glycolysis and aging.<b><sup>237-239</sup></b> Currently there are >9,000 different plant <span id="">flavonoids</span> with ~400 of them being sub-classified as <span id="Glacialb">anthocyanins</span>.<b><sup>227,234,235</sup></b></td>
      </tr>      
    </tbody>
</table>

<div>
<img src="images/Mkwd_icon2.jpg" alt="" style="float:left; width:55px;"/>
<img src="images/Mkwd_icon2.jpg" alt="" style="float:right; width:55px;"/>
<div class="head16">
<i>How do antioxidants like <span id="Dred">flavonoids</span> and <span id="OrRed">vitamin C</span> neutralize <span id="Rasp">free radicals</span></i>?
</div></div>
<br>
<br>

&nbsp; &nbsp; To answer this question we need to look at the chemistry of molecular <span id="Red">O</span>xygen and *<span id="Rasp">free radicals</span>*, that latter being a molecule or atom with at least one "*unpaired*" **valence** <span id="Dred">e</span>lectron. The concept of an "*unpaired*" <span id="Dred">e</span>lectron (<span id="Dred">e</span>**<sup>-</sup>**) speaks to the underlying structure of atoms, specifically the properties of <span id="Dred">e</span>**<sup>-</sup>** that occupy the outer most **energy** level or "*shell*" of an atom (i.e. **valence** <span id="Dred">e</span>**<sup>-</sup>**). Being furthest from the nucleus means that these negatively charged <span id="Dred">e</span>**<sup>-</sup>** are subjected to the least amount of "*pull*" (i.e. electrostatic attraction) by the positively charged nucleus. As a consequence **valence** <span id="Dred">e</span>**<sup>-</sup>** participate more "*freely*" in <u>chemical reactions</u> and <u>chemical bond</u> formation (i.e. explains the chemical "*reactivity*" of atoms and molecules).  
&nbsp; &nbsp; Looking at the <span id="Dred">e</span>**<sup>-</sup>** **configuration** of <span id="Red">O</span><sub>2</sub> (**Fig. 14B** &#10112;) one can see that there are <u>two unpaired</u> **valence** <span id="Dred">e</span>**<sup>-</sup>** occupying <u>two different</u> outer <u>molecular orbitals</u>. Both electrons have the same "*parallel*" **<a class="one" href="http://hyperphysics.phy-astr.gsu.edu/hbase/spin.html#c1">spin state</a>** (+**&frac12;** <u>**&uharl;**</u>), which refers to the **<a class="one" href="http://hyperphysics.phy-astr.gsu.edu/hbase/spin.html#c3">intrinsic angular momentum</a>** of <span id="Dred">e</span>**<sup>-</sup>**. If ground state <span id="Red">O</span><sub>2</sub> extracts a pair of <span id="Dred">e</span>**<sup>-</sup>** from a molecule (i.e. <span id="Red">o</span>xidizes) both <span id="Dred">e</span>**<sup>-</sup>** would have to be in an "*anti-parallel*" **<a class="one" href="http://hyperphysics.phy-astr.gsu.edu/hbase/spin.html#c1">spin state</a>** (-**&frac12;**, <u>**&dharr;**</u>) to fill the two degenerate <u>molecular orbitals</u> (i.e. in accordance with the **<a class="one" href="http://hyperphysics.phy-astr.gsu.edu/hbase/pauli.html#c2">Pauli exclusion principle</a>**). However, since all filled orbitals have **spin-paired** <span id="Dred">e</span>**<sup>-</sup>** (<u>**&uharl;**</u><u>**&dharr;**</u>), only one <span id="Dred">e</span>**<sup>-</sup>** would be in the appropriate "*anti-parallel*" **<a class="one" href="http://hyperphysics.phy-astr.gsu.edu/hbase/spin.html#c1">spin state</a>**. Because of this "*spin-restriction*" on the transfer of <span id="Dred">e</span>**<sup>-</sup>** ground state <span id="Red">O</span><sub>2</sub> is limited to extracting one <span id="Dred">e</span>**<sup>-</sup>** (-**&frac12;**, <u>**&dharr;**</u>) at a time from **spin-paired** molecules. In order to fill both degenerate 2&pi;<sup><span id="Red">&#10043;</span></sup> <u>molecular orbitals</u> would therefore require a two step oxidation process, which helps to explain why <span id="Red">O</span><sub>2</sub> reacts relatively slowly. It is interesting to note that molecular oxygen is a relatively <u>poor</u> **oxidant** compared to other **reactive oxygen species** (<span id="Red">ROS</span>) such as <i><span id="Rasp">Superoxide radical</span></i> (<sup>&#8226;</sup><span id="Red">O</span><sub>2</sub><sup>-</sup>, **Fig. 14** &#10114; &#10102;) or hydrogen peroxide (<span id="Blue">H</span><sub>2</sub><span id="Red">O</span><sub>2</sub>, **Fig. 14** &#10115; &#10105;). This seemingly odd point (since "*oxidation*" on the surface appears to be all about molecular oxygen) comes into focus when one looks at the **thermodynamics** of these reactions, specifically the <span id="Dred">e</span>**<sup>-</sup>** **transfer potentials** (**<i>E</i>**<sup>&#9900;'</sup>) of various **oxidants**.**<sup>240,241</sup>** Substances with more <u>positive</u> **<i>E</i>**<sup>&#9900;'</sup> values are more <u>powerful</u> **oxidants** that can readily extract a single <span id="Dred">e</span>**<sup>-</sup>** from another substance (i.e. **reductant**). The transfer of one <span id="Dred">e</span>**<sup>-</sup>** to <span id="Red">O</span><sub>2</sub> has an **<i>E</i>**<sup>&#9900;'</sup>(<span id="Red">O</span><sub>2</sub>, 1 atm.)/<sup>&#8226;</sup><span id="Red">O</span><sub>2</sub><sup>-</sup>) value of approximately -330 mV (aqueous, pH 7). This means that the product of this **redox** reaction (i.e. <i><span id="Rasp">Superoxide radical</span></i>) is a much stronger **oxidant** than <span id="Red">O</span><sub>2</sub>. However, when normal **ground state** <span id="Red">O</span><sub>2</sub> (&#10112;) transitions to a higher energy (&#8220;*excited*&#8221;) state (**<i>E</i>**<sub>&Delta;</sub> = 94 kcal/mol above ground state) one of the lone <span id="Dred">e</span>**<sup>-</sup>** "*flips*" its "*spin*", which allows the two lone <span id="Dred">e</span>**<sup>-</sup>** to pair up together in one orbital (**Fig. 14B** &#10113;).**<sup>242</sup>** The resulting empty degenerate &pi;<sup><span id="Red">&#10043;</span></sup> <u>molecular orbital</u> makes this "*excited*" <span id="Red">O</span><sub>2</sub><sup><span id="Red">&#10043;</span></sup> species (&#10113;) a very strong and dangerous **oxidant** that rapidly extracts **spin-paired** electrons (<u>**&uharl;**</u><u>**&dharr;**</u>) from biomolecules causing extensive cellular damage and even cell death.**<sup>243-246</sup>** Fortunately there are many different types of <span id="Glacialb">antioxidants</span> (e.g. <span id="Dred">flavonoids</span>, <span id="OrRed">carotenoids</span>, **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:29073">vitamin C</a>** and **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/14985">vitamin E</a>**), **enzymes** (e.g. <span id="Glacialb">SOD</span>, <span id="Glacialb">Catalase</span>, **Fig. 14C** &#10105;) and <span id="Dred">Fe</span> storage proteins (e.g. <span id="Glacialb">Ferritin</span>, **Fig. 14C** &#10106;) that can inhibit the production or damage caused by cellular <span id="Red">ROS</span> (**Fig. 14C**).**<sup>241,247,248</sup>** The great interest in <span id="Red">O</span><sub>2</sub><sup><span id="Red">&#10043;</span></sup> is largely based on the important roles it plays in ionizing radiation induced cell death (e.g. basis of cancer Photodynamic Therapy, or **PDT**), toxicity of **ozone** (<span id="Red">O</span><sub>3</sub>, **Fig. 14C** &#10108;), and metal (e.g. <span id="Dred">Fe</span>, <span id="Lgray">Pt</span>) catalyzed <span id="Red">o</span>xidation reactions (e.g. metal corrosion, catalytic converters, waste treatment, cell metabolism generated oxidative damage).**<sup>241,249-253</sup>**  

<!-------------------------------------------->
<!------- FIG 14 - ROS Anti-Oxidants  -------->
<!-------------------------------------------->
<a id="Fig_Oxygen"></a>
<div align=center>
<figure>
<img src="images/PTable_MO_ROS.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 14: Chemistry of <span id="Red">O</span>xygen</u></b>. <b>(A)</b> Biomolecules (proteins, carbohydrates, nucleic acids, and lipids) found in all cells are mostly (~99%) made up of <u>six chemical elements</u>: <b>hydrogen</b> (<span id="Blue">H</span>), <b>oxygen</b> (<span id="Red">O</span>), <b>carbon</b> (<b>C</b>), <b>nitrogen</b> (<span id="Gr">N</span>), <b>sulfur</b> (<span id="Gold">S</span>) and <b>phosphorus</b> (<span id="Purple">P</span>). Of course the first two elements (<span id="Blue">H</span>, <span id="Red">O</span>) constitute ~70% of the mass of cells (i.e. water), but there are a few other <b>inorganic ions</b> like <b>sodium</b> (<span id="Purple">Na</span>), <b>magnesium</b> (<span id="Dpurp">Mg</span>), <b>chlorine</b> (<span id="GrY">Cl</span>) and <b>calcium</b> (<span id="GrY3">Ca</span>) that are also essential for normal cell function. The position of <span id="Red">O</span> within the <b>Periodic Table</b> (i.e. <b>Group 6A</b>, <b>Period 2</b>) tells us something very important about this element, specifically that it has 6 <b>valence</b> <span id="Dred">e</span><b><sup>-</sup></b> (column 6) all residing within the <b>2<sup>nd</sup></b> energy level (<b>2<sup>nd</sup></b> row). The <b>electronic configuration</b> of these 6 <b>valence</b> <span id="Dred">e</span><b><sup>-</sup></b> (<b>2s</b><sup>2</sup><b>2p</b><sup>4</sup>) also tells us the possible &#8220;states&#8221; (i.e. <b>orbitals</b>) they occupy within the <b>2<sup>nd</sup></b> energy level, as symbolized by the letters <b>s</b> and <b>p</b> (i.e. <b><a class="one" href="http://hyperphysics.phy-astr.gsu.edu/hbase/qunoh.html#c2">principal quantum numbers</a></b>). In accordance with established quantum principles these <b>orbitals</b> are filled one by one per &#8220;shell&#8221; as the number of <span id="Dred">e</span><b><sup>-</sup></b> increases. Each <b>orbital</b>, regardless of its energy level, can only hold a <u>maximum</u> of 2 <span id="Dred">e</span><b><sup>-</sup></b>, each with opposite &#8220;spin states&#8221; (<b><a class="one" href="http://hyperphysics.phy-astr.gsu.edu/hbase/pauli.html#c2">Pauli exclusion principle</a></b>). Stable <span id="Dred">e</span><b><sup>-</sup></b> arrangements arise when a given <b>energy level</b> or &#8220;shell&#8221; is filled. The <b>1<sup>st</sup></b> &#8220;shell&#8221; can accommodate 2 <span id="Dred">e</span><b><sup>-</sup></b> in total, while the <b>2<sup>nd</sup></b> &#8220;shell&#8221; can accommodate up to 8 <span id="Dred">e</span><b><sup>-</sup></b> (i.e. &#8220;octet&#8221; rule). <b>Nobel Gases</b> (<b>Group 8A</b>) like <b>helium</b> (<b>He</b>: <b>1s</b><sup>2</sup>) that have filled energy levels are very stable and are typically chemically inert.<br>
<b>(B, C)</b> The <b>ground state</b> (&#10112;) of <span id="Red">O</span><sub>2</sub> has two unpaired <span id="Dred">e</span><b><sup>-</sup></b> residing in two <u>degenerate</u> (&#8220;anti-bonding&#8221;) 2&pi;<sup><span id="Red">&#10043;</span></sup> orbitals, making it a natural <i><span id="Rasp">di-radical</span></i>.<b><sup>242,249</sup></b> When <span id="Red">O</span><sub>2</sub> transitions to an &#8220;excited&#8221; intermediate state (&#10113;, ~92 kJ/mol above ground state)<b><sup>242</sup></b> the &#8220;spin&#8221; of one <span id="Dred">e</span><b><sup>-</sup></b> becomes &#8220;flipped&#8221; (<b>-&frac12;</b>, <u><b>&dharr;</b></u>), which allows it to pair up with the other lone <span id="Dred">e</span><b><sup>-</sup></b> (<b>+&frac12;</b>, <u><b>&uharl;</b></u>). Although a non-radical this &#8220;<i>excited</i>&#8221; species of oxygen (&#10113; <span id="Red">O</span><sub>2</sub><sup><span id="Red">&#10043;</span></sup>) is very chemically reactive and known to trigger apoptotic cell death.<b><sup>243-246</sup></b> Fortunately photon (i.e. non-ionizing radiation) induced transitions to this higher energy state is highly unlikely unless it is catalyzed by exogenous or endogenous photo-sensitizers.<b><sup>249</sup></b> Regardless, <span id="Red">O</span><sub>2</sub> can undergo a series of single <span id="Dred">e</span><b><sup>-</sup></b> reduction reactions that starts with the production of <i><span id="Rasp">Superoxide radical</span></i> (&#10114;, &#10102; <sup>&#8226;</sup><span id="Red">O</span><sub>2</sub><sup>-</sup>). This short lived <i><span id="Rasp">radical</span></i> is very chemically reactive (<b><i>E</i></b><sup>&#9900;'</sup> = +940 mV),<b><sup>240,241</sup></b> but its negative charge limits its movements (i.e. membrane impermeable) and interactions (i.e. preferentially targets protein [<span id="Dred">Fe</span>&ndash;<span id="Gold">S</span>] clusters).<b><sup>254</sup></b> As a consequence it preferentially undergoes protonation to become a <i><span id="Rasp">hydro-peroxyl radical</span></i> (&#10104; <span id="Blue">H</span>&ndash;<span id="Red">O</span>&ndash;<span id="Red">O</span><sup>&#8226;</sup>). This <i><span id="Rasp">radical</span></i> species is a better <b>oxidizer</b> (<b><i>E</i></b><sup>&#9900;'</sup> = +1060 mV)<b><sup>240,241</sup></b> than <sup>&#8226;</sup><span id="Red">O</span><sub>2</sub><sup>-</sup> and may play an important role in cell membrane <span id="Gold">Lipid</span> <b>peroxidation</b> (&#10103;).<b><sup>255</sup></b> However further protonation (often courtesy <span id="Glacialb">Superoxide dismutase</span>, or <span id="Glacialb">SOD</span>) yields <span id="Blue">H</span><sub>2</sub><span id="Red">O</span><sub>2</sub> (&#10115;, &#10105;). Although a <b>non</b>-<i><span id="Rasp">radical</span></i> this relatively stable molecule can be reduced by <span id="Dred">Fe</span><sup>+2</sup> (<b>Fenton Reaction</b>) to produce a <b>hydroxide ion</b> (<span id="Blue">H</span><span id="Red">O</span><sup>-</sup>) and a <i><span id="Rasp">hydroxyl radical</span></i> (&#10106; <span id="Blue">H</span><span id="Red">O</span><sup>&#8226;</sup>). The latter is the most toxic and powerful <b>oxidant</b> (<b><i>E</i></b><sup>&#9900;'</sup> = +2310 mV)<b><sup>240,241</sup></b> that reacts indiscriminately during its short life span (&#10109;).<b><sup>246,254</sup></b> Its toxicity is in large part due to its ability to produce multiple free radicals from the molecules it reacts with (i.e. chain reaction), much like <sup>&#8226;</sup><span id="Red">O</span><sub>2</sub><sup>-</sup> (&#10103;). Photolysis (i.e. ionizing radiation) of atmospheric (high altitude) water vapour (&#10107;) as well as low atmospheric <b><a class="one" href="https://www.epa.gov/ground-level-ozone-pollution/ground-level-ozone-basics">ozone</a></b> (smog produced <span id="Red">O</span><sub>3</sub>, &#10108;) can also generate toxic <span id="Blue">H</span><span id="Red">O</span><sup>&#8226;</sup>. Recent studies have shown that <span id="Red">O</span><sub>3</sub> can react with <b>squalene</b>, an abundant skin oil and <span id="Dred">triterpenoid</span>, to produce toxic <span id="Blue">H</span><span id="Red">O</span><sup>&#8226;</sup>.<b><sup>251,252</sup></b> Excessive cell damage caused by these <span id="Red">ROS</span> is thought to play an important role in the development of several chronic diseases (e.g. diabetes, arthritis, atherosclerosis, cancers) as well as aging (&#10110;).<b><sup>256-260</sup></b> 

</figcaption>
</figure>
</div>
<br>

&nbsp; &nbsp; Given the basic chemistry of <span id="Red">O</span><sub>2</sub> and <i><span id="Rasp">free radicals</span></i> (**Fig. 14**), one is left with the question of how <span id="Glacialb">antioxidants</span> counteract toxic levels of these chemically reactive molecules. Of course, like most people, when someone mentions <span id="Glacialb">antioxidants</span> I think of **<a class="one" href="https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:29073">vitamin C</a>** and **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/14985">vitamin E</a>** (i.e. **&alpha;-tocopherol**). Arguably **vitamin** <span id="Or">C</span> (i.e. <span id="Or">ascorbic acid</span>) is the more familiar of the two <span id="Glacialb">antioxidants</span>, not only because of its health-promoting virtues often extolled (and profited) by the food and drug industry, but also because of its remarkable medical history. Of course the use of citrus fruits (i.e. limes and lemons) by 18<sup>th</sup> century English sailors to combat the "*Black Death of the sea*", otherwise known as **scurvy** (<b>Latin:</b> *scorbuticus*, "*pertaining to scurvy*") is a familiar tale. However, the story of the Scottish naval surgeon **<a class="one" href="https://www.jameslindlibrary.org/articles/james-lind-and-scurvy-1747-to-1795/">James Lind</a>** (1747) who designed the first clinical trial of this (or any other) disease, as documented in his "*Treatise of the Scurvy*",**<sup>261</sup>** is probably unknown to most of us.**<sup>262,263</sup>** Its a remarkable story for a number of reasons (so forgive me for my meandering), particularly if you consider the great toll that **scurvy** inflicted on sailors between the 16<sup>th</sup> and 19<sup>th</sup> century (i.e. ~2 million scurvy-related sailor deaths have been estimated for this time period).**<sup>264</sup>** For example, during Captain **George Anson's** ill-fated naval expedition (1740–1744) most of the original 1,200 men that crewed his six-ship flotilla succumbed to **scurvy** (e.g. 380 of 510 crewman on one ship died of the disease).**<sup>262,265</sup>** In fact it was this famous naval disaster that apparently inspired **<a class="one" href="https://www.jameslindlibrary.org/articles/james-lind-and-scurvy-1747-to-1795/">James Lind</a>** to investigate **scurvy**. Perhaps even more surprisingly (at least from our biased present day perspective) was the fact that the connection between the disease and diet (e.g. consumption of lemons, **<a class="one" href="https://tinyurl.com/3xbwc7n3">sauerkraut</a>** was known to cure it) was not new. Unfortunately, during that time there were many purported cures for **scurvy** that no doubt distracted and obscured those remedies that actually did work. As **<a class="one" href="https://www.sciencehistory.org/distillations/the-age-of-scurvy">Catherine Price</a>** (2017) aptly wrote:
>"...*history and science are rarely as straightforward as hindsight makes them seem, and the story of vitamins is no exception. The discovery of vitamins was <u>not a moment but a process</u>, a fascinating and often complicated journey*..." **<sup>265</sup>**  

Fortunately by 1795, one year after **Lind's** death, the British Royal Navy finally instituted the use of lemon juice rations (which were later switched to lime juice, hence the term "*limeys*") for all its sailors.**<sup>264</sup>** This change alone is thought to be one of the reasons why Britain succeeded in its long (naval) war against Napoleon, particularly when most other naval military powers did not adapt similar "*anti-scorbutic*" policies.**<sup>264,265</sup>** The identification of this "*anti-scorbutic*" compound occurred much later during the late 1920s, which was the dawn of hormone research. **<a class="one" href="https://www.nobelprize.org/prizes/medicine/1937/szent-gyorgyi/biographical/">Albert Szent-Györgyi</a>** (1928) used a simple but elegant plant root peroxidase system to systematically identify and purify his "*<u>hex</u>uronic acid*" (<u>six</u> carbon oxidized sugar). He went on to show that it was abundant in some fruits and vegetables, and also present within the cortex of animal adrenal glands.**<sup>266</sup>** He not only fully characterize the physical-chemical properties of his purified "*hexuronic acid*", but also showed in two subsequent publications how it (which he renamed "*a-scorbic acid*") could clearly prevent guinea-pigs from developing and dying from **scurvy**.**<sup>267,268</sup>** For his work **<a class="one" href="https://www.nobelprize.org/prizes/medicine/1937/szent-gyorgyi/biographical/">Albert Szent-Györgyi</a>** was awarded the Nobel Prize (Physiology/Medicine) in 1937.  
&nbsp; &nbsp; **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/14985">Vitamin E</a>** (i.e. **&alpha;-tocopherol**) may not have a storied past like <span id="Or">ascorbic acid</span>, but it is regarded as the most important **<a class="one" href="https://www.cancer.gov/publications/dictionaries/cancer-terms/def/lipophilic">lipophilic</a>** <span id="Glacialb">antioxidant</span> within cells. Functionally it prevents the **peroxidation** of membrane <span id="Gold">lipids</span> by scavenging *<span id="Rasp">peroxyl radicals</span>*.**<sup>269-271</sup>** <span id="Glacialb">P</span>**oly**<span id="Glacialb">u</span>**nsaturated** <span id="Glacialb">f</span>**atty** <span id="Glacialb">a</span>**cids** (<span id="Glacialb">PUFA</span>) are particularly prone to chemical attack by *<span id="Rasp">peroxyl radicals</span>* because the double bonds they contain affect the bonding strength of neighbouring <span id="Glacialb">H</span> atoms (**Fig. 15A**).**<sup>241,272,273</sup>** Alterations in the structure of these <span id="Gold">lipids</span> can compromise not only the integrity of cells, but also many cellular functions since <span id="Glacialb">PUFA</span> and their derivatives regulate many cell receptor signaling pathways.**<sup>274,275</sup>** Fortunately, like **vitamin E**, there are many <span id="Dred">flavonoids</span> (e.g. <span id="Glacialb">anthocyanins</span>) that can reduce and neutralize *<span id="Rasp">free radicals</span>*. For <span id="Glacialb">anthocyanins</span> much of this <span id="Glacialb">antioxidant</span> activity stems from the abundance of <b>phenolic</b> <span id="Blue">hydroxyl</span> groups (**Table 6**), since the <span id="Glacialb">H</span> atom belonging to this functional group is easily abstracted by *<span id="Rasp">free radicals</span>* (**Fig. 15B**).

<!---------------------------------------------------------------->
<!------- FIG 15 - Antioxidants & Free Radicals chain rx. -------->
<!---------------------------------------------------------------->
<a id="Fig_VitCE"></a>
<div align=center>
<figure>
<img src="images/FreeRad_ChainRx_VitCE.jpg" alt="" width="800px"/>
<figcaption>
<b><u>Figure 15: <span id="Gold">Lipid</span> Peroxidation and <span="Glacialb"Antioxidant</span> Vitamins E and <span id="Or">C</span></u></b>. <b>(A)</b> <b>Peroxidation</b> of <span id="Gold">lipids</span>, such as <b>polyunsaturated fatty acids</b> (<span id="Glacialb">PUFA</span>) and cholesterol, by <i><span id="Rasp">free radicals</span></i> are associated with a number of human patho-physiological conditions, including (among others) atherosclerosis, acute lung injury, cancer and neuro-degenerative diseases.<b><sup>259,260,276-278</sup></b> The initial step in this chemical process is the abstraction of a hydrogen atom (i.e. <span id="Blue">H</span><sup>+</sup> + <span id="Dred">e</span><sup>-</sup>) from a <span id="Gold">lipid</span> by a <i><span id="Rasp">free radical</span></i> like <sup>&#8226;</sup><span id="Red">O</span><span id="Blue">H</span> (&#10102;). <span id="Glacialb">PUFA</span> are particularly susceptible to <b>peroxidation</b> due to the relative ease of abstracting <u>bis-allylic</u> positioned hydrogen atoms (&#10102;, &ndash;<b>C</b><span id="Blue">H</span><sub>2</sub>&ndash; group positioned between two carbon-carbon double bonds).<b><sup>241,270,272,273</sup></b> Based on carbon-hydrogen bond dissociation energies <u>bis-allylic</u> positioned hydrogens are much weaker (75-80 kcal/mol) than either <u>mono-allylic</u> (88 kcal/mol) or <u>alkyl</u> (101 kcal/mol) hydrogens, which explains why carbons not located between double bonds contribute little (<1%) to <i><span id="Rasp">free radical</span></i> generation.<b><sup>241,272,273</sup></b> The main product, a <span id="Gold">lipid</span> <b>carbonyl</b> <i><span id="Rasp">radical</span></i>, then reacts with <span id="Red">O</span><sub>2</sub> to produce a <span id="Gold">lipid</span> <i><span id="Rasp">peroxyl radical</span></i> (&#10103;). This new <span id="Gold">lipid</span> <i><span id="Rasp">radical</span></i> propagates the <b>peroxidation</b> reaction by abstracting a hydrogen atom from a neighbouring <span id="Gold">lipid</span> molecule (&#10104;). This step creates a new <span id="Gold">lipid</span> <b>carbonyl</b> <i><span id="Rasp">radical</span></i> (&#10105;) that, in turn, powers the same set of reactions that produced it (i.e. &#8220;<i>chain reaction</i>&#8221;) until two such <span id="Gold">lipid</span> <i><span id="Rasp">radicals</span></i> react with one another to terminate the <b>peroxidation</b> process.<b><sup>270</sup></b><br>  
<b>(B)</b> <b>Vitamin E</b>, or &alpha;-tocopherol, is an important cellular lipophilic <i><span id="Rasp">free radical</span></i>-scavenging <span id="Glacialb">antioxidant</span>.<b><sup>269,271</sup></b> It terminates <i><span id="Rasp">free radical</span></i> &#8220;<i>chain reactions</i>&#8221; by donating a hydrogen atom from its <b>phenolic</b> <span id="Blue">hydroxyl</span> group to the attacking <i><span id="Rasp">free radical</span></i> (i.e. <sup>&#8226;</sup><span id="Red">O</span><b>R</b>, &#10106;). Similar to <u>allylic</u> hydrogens, the lone hydrogen on the <b>phenolic</b> <span id="Blue">hydroxyl</span> group has a relatively low bond dissociation energy (89 kcal/mol).<b><sup>279</sup></b> This oxidation step produces a <i><span id="Rasp">radical</span></i> species of <b>vitamin E</b> that is relatively stable owing to the <u>de-localized</u> (spread out over the conjugated ring structure) nature of the unpaired electron.<br>  
<b>(C)</b> <span id="Or">Ascorbic acid</span> (<b>vitamin</b> <span id="Or">C</span>) is an important co-factor for several different enzymes, as well as a &#8220;<i>scavenger</i>&#8221; of chemically reactive <i><span id="Rasp">free-radicals</span></i>.<b><sup>280</sup></b> It is a powerful reducing agent (donates <span id="Blue">H</span><sup>+</sup> and <span id="Dred">e</span><sup>-</sup>) that cycles between a fully reduced <b>mono-anionic</b> species (<span id="Or">A</span><span id="Glacialb">H</span><sup>-</sup>, predominate species at <b>pH 7</b>) and its partially oxidized <b>mono-de</b><span id="Glacialb">hydro</span> species (<sup>&#8226;</sup><span id="Or">A</span><sup>-</sup> &#10107;).<b><sup>280,281</sup></b> An important thermodynamic (energy) barrier prevents oxidation of <sup>&#8226;</sup><span id="Or">A</span><sup>-</sup> to a <b>tri-carbonyl</b> species (i.e. <b>C</b>=<span id="Red">O</span> groups at positions <b>C</b><sub>1</sub>, <b>C</b><sub>2</sub> and <b>C</b><sub>3</sub>), which explains why <span id="Or">ascorbate</span> preferentially cycles between <span id="Or">A</span><span id="Glacialb">H</span><sup>-</sup> and <sup>&#8226;</sup><span id="Or">A</span><sup>-</sup> at neutral <b>pH</b>, and also why <span id="Or">ascorbate</span> functions as a good donor of single <span id="Glacialb">H</span> atoms.<b><sup>281</sup></b> However, <sup>&#8226;</sup><span id="Or">A</span><sup>-</sup> can undergo a reversible oxidation reaction to form a <b>bicyclic hemi-ketal</b> structure (i.e. <b>de</b><span id="Blue">hydro</span> <span id="Or">ascorbate</span>, or <span id="Or">A</span><sup><span id="Blue">H</span><sub>2</sub><span id="Red">O<span></sup> &#10108;). <b>Vitamin</b> <span id="Or">C</span> is a potent <span id="Glacialb">antioxidant</span> due to the unusual stability of its <sup>&#8226;</sup><span id="Or">A</span><sup>-</sup> <i><span id="Rasp">radical</span></i> (i.e. <u>de-localized</u> nature of the unpaired <span id="Dred">e</span><sup>-</sup> within the ring structure) and its preference for reacting with other <i><span id="Rasp">radicals</span></i> like <sup>&#8226;</sup><span id="Red">O</span><span id="Blue">H</span>.<b><sup>280</sup></b> This allows the <sup>&#8226;</sup><span id="Or">A</span><sup>-</sup> <i><span id="Rasp">radical</span></i> to effectively <u>terminate</u> the propagation of <i><span id="Rasp">free radical</span></i> reactions as depicted in panel <b>A</b>. The reducing power <b>Vitamin</b> <span id="Or">C</span> is also used to regenerate many oxidized enzymes, as well as in the recycling of oxidized <b>vitamin E</b>.<b><sup>282-284</sup></b>  

</figcaption>
</figure>
</div>



<a id="Refs"></a>
<span id="BBlk">&thinsp; REFERENCES &thinsp;</span>**:**  

**1.** Akerele O. (1993). Nature’s Medicinal Bounty: Don’t Throw It Away. World Health Forum 14:390–5.  
**2.** World Health Organization. (2009). Report of WHO Interregional Workshop on the Use of Traditional Medicine in Primary Health Care, Ulaanbaatar, Mongolia, 23-26 August 2007.  
**3.** Ljungdahl L. and Wood H.G. (1965). Incorporation of C4 from carbon dioxide into sugar phosphates, carboxylic acids and amino acids by Clostridium Thermoaceticum. Journal of Bacteriology 89:1055–64. https://doi.org/10.1128/JB.89.4.1055-1064.1965.  
**4.** Martin W.F. (2020). Older Than Genes: The Acetyl CoA Pathway and Origins. Frontiers in Microbiology 11:817. https://doi.org/10.3389/fmicb.2020.00817.  
**5.** Berg I.A., Kockelkorn D., Ramos-Vera W.H., Say R.F., Zarzycki J., Hügler M., et al. (2010). Autotrophic carbon fixation in archaea. Nature Reviews Microbiology 8:447–60. https://doi.org/10.1038/nrmicro2365.  
**6.** Fuchs G. (2011). Alternative pathways of carbon dioxide fixation: Insights into the early evolution of life? Annual Review of Microbiology 65:631–58. https://doi.org/10.1146/annurev-micro-090110-102801.  
**7.** Weiss M.C., Sousa F.L., Mrnjavac N., Neukirchen S, Roettger M, Nelson-Sathi S, et al. (2016). The physiology and habitat of the last universal common ancestor. Nature Microbiology 1:1–8. https://doi.org/10.1038/nmicrobiol.2016.116.  
**8.** Weiss M.C., Preiner M., Xavier J.C., Zimorski V., and Martin W.F. (2018). The last universal common ancestor between ancient Earth chemistry and the onset of genetics. PLOS Genetics 14:e1007518. https://doi.org/10.1371/journal.pgen.1007518.  
**9.** Varma S.J., Muchowska K.B., Chatelain P., and Moran J. (2018). Native iron reduces CO<sub>2</sub> to intermediates and end-products of the acetyl-CoA pathway. Nature Ecology & Evolution 2:1019–24. https://doi.org/10.1038/s41559-018-0542-2.  
**10.** Johnson A.P., Cleaves H.J., Dworkin J.P., Glavin D.P., Lazcano A., and Bada J.L. (2008). The Miller Volcanic Spark Discharge Experiment. Science 322:404–4. https://doi.org/10.1126/science.1161527.  
**11.** Haldane J.B.S. (1929). The origin of life. Rationalist Annual 148:3–10.  
**12.** Oparin A.I. The origin of life. 2d ed. New York: Dover Publications; 1953.  
**13.** Miller S.L. (1953). A Production of Amino Acids Under Possible Primitive Earth Conditions. Science 117:528–9. https://doi.org/10.1126/science.117.3046.528.  
**14.** Miller S.L., and Urey H.C. (1959). Organic compound synthesis on the primitive earth. Science 130:245–51. https://doi.org/10.1126/science.130.3370.245.  
**15.** Zahnle K.J. (2006). Earth’s Earliest Atmosphere. Elements 2:217–22.  
**16.** Zahnle K., Schaefer L., and Fegley B. (2010). Earth’s Earliest Atmospheres. Cold Spring Harbor Perspectives in Biology 2: https://doi.org/10.1101/cshperspect.a004895.  
**17.** Catling D.C., Zahnle K.J. (2020). The Archean atmosphere. Science Advances 6:eaax1420. https://doi.org/10.1126/sciadv.aax1420.  
**18.** Martin W., Baross J., Kelley D., Russell M.J. (2008). Hydrothermal vents and the origin of life. Nature Reviews Microbiology 6:805–14. https://doi.org/10.1038/nrmicro1991.  
**19.** Kelley D.S., Karson J.A., Blackman D.K., Früh-Green G.L., Butterfield D.A., Lilley M.D., et al. (2001). An off-axis hydrothermal vent field near the Mid-Atlantic Ridge at 30° N. Nature 412:145–9. https://doi.org/10.1038/35084000.  
**20.** Früh-Green G.L., Kelley D.S., Bernasconi S.M., Karson J.A., Ludwig K.A., Butterfield D.A., et al. (2003). 30,000 Years of Hydrothermal Activity at the Lost City Vent Field. Science 301:495–8. https://doi.org/10.1126/science.1085582.  
**21.** Kelley D.S., Karson J.A., Früh-Green G.L., Yoerger D.R., Shank T.M., Butterfield D.A., et al. (2005). A Serpentinite-Hosted Ecosystem: The Lost City Hydrothermal Field. Science 307:1428–34. https://doi.org/10.1126/science.1102556.  
**22.** Stevenson D.J. (1987). Origin of the Moon-The Collision Hypothesis. Annual Review of Earth and Planetary Sciences 15:271–315. https://doi.org/10.1146/annurev.ea.15.050187.001415.  
**23.** Mojzsis S.J., Harrison T.M., and Pidgeon R.T. (2001). Oxygen-isotope evidence from ancient zircons for liquid water at the Earth’s surface 4,300 Myr ago. Nature 409:178–81. https://doi.org/10.1038/35051557.  
**24.** Wilde S.A., Valley J.W., Peck W.H., and Graham C.M. (2001). Evidence from detrital zircons for the existence of continental crust and oceans on the Earth 4.4 Gyr ago. Nature 409:175–8. https://doi.org/10.1038/35051550.  
**25.** Harrison T.M., Bell E.A., and Boehnke P. (2017). Hadean Zircon Petrochronology. Reviews in Mineralogy and Geochemistry 83:329–63. https://doi.org/10.2138/rmg.2017.83.11.  
**26.** Schopf J.W. (1993). Microfossils of the Early Archean Apex Chert: New Evidence of the Antiquity of Life. Science 260:640–6. https://doi.org/10.1126/science.260.5108.640.  
**27.** Allwood A.C., Walter M.R., Kamber B.S., Marshall C.P., and Burch I.W. (2006). Stromatolite reef from the Early Archaean era of Australia. Nature 441:714–8. https://doi.org/10.1038/nature04764.  
**28.** Djokic T., Van Kranendonk M.J., Campbell K.A., Walter M.R., and Ward C.R. (2017). Earliest signs of life on land preserved in ca. 3.5 Ga hot spring deposits. Nature Communications 2017;8:15263. https://doi.org/10.1038/ncomms15263.  
**29.** Mojzsis S.J., Arrhenius G., McKeegan K.D., Harrison T.M., Nutman A.P., and Friend C.R.L. (1996). Evidence for life on Earth before 3,800 million years ago. Nature 384:55–9. https://doi.org/10.1038/384055a0.  
**30.** Rosing M.T. (1999). <sup>13</sup>C-Depleted Carbon Microparticles in &gt;3700-Ma Sea-Floor Sedimentary Rocks from West Greenland. Science 283:674–6. https://doi.org/10.1126/science.283.5402.674.  
**31.** Ohtomo Y., Kakegawa T., Ishida A., Nagase T., and Rosing M.T. (2014). Evidence for biogenic graphite in early Archaean Isua metasedimentary rocks. Nature Geoscience 7:25–8. https://doi.org/10.1038/ngeo2025.  
**32.** Bell E.A., Boehnke P., Harrison T.M., and Mao W.L. (2015). Potentially biogenic carbon preserved in a 4.1 billion-year-old zircon. Proceedings of the National Academy of Sciences of the United States of America 2015;112:14518–21. https://doi.org/10.1073/pnas.1517557112.  
**33.** Tashiro T, Ishida A, Hori M, Igisu M, Koike M, Méjean P, et al. (2017). Early trace of life from 3.95 Ga sedimentary rocks in Labrador, Canada. Nature 549:516–8. https://doi.org/10.1038/nature24019.  
**34.** Arndt N. and Nisbet E. (2012). Processes on the Young Earth and the Habitats of Early Life. Annual Review of Earth and Planetary Sciences. https://doi.org/10.1146/ANNUREV-EARTH-042711-105316.  
**35.** Sagan C. and Mullen G. (1972). Earth and Mars: Evolution of Atmospheres and Surface Temperatures. Science 177:52–6. https://doi.org/10.1126/science.177.4043.52.  
**36.** Owen T., Cess R.D., and Ramanathan V. (1979). Enhanced CO<sub>2</sub> greenhouse to compensate for reduced solar luminosity on early Earth. Nature 277:640–2. https://doi.org/10.1038/277640a0.  
**37.** Johnson J.E., Webb S.M., Thomas K., Ono S., Kirschvink J.L., and Fischer W.W. (2013). Manganese-oxidizing photosynthesis before the rise of cyanobacteria. Proceedings of the National Academy of Sciences 2013;110:11238–43. https://doi.org/10.1073/pnas.1305530110.  
**38.** Fischer W.W., Hemp J., Johnson J.E. (2016). Evolution of Oxygenic Photosynthesis. Annual Review of Earth and Planetary Sciences 44:647–83. https://doi.org/10.1146/annurev-earth-060313-054810.  
**39.** Preiner M., Igarashi K., Muchowska K.B., Yu M., Varma S.J., Kleinermanns K., et al. (2020). A hydrogen-dependent geochemical analogue of primordial carbon and energy metabolism. Nature Ecology & Evolution 4:534–42. https://doi.org/10.1038/s41559-020-1125-6.  
**40.** Russell M.J. and Martin W. (2004). The rocky roots of the acetyl-CoA pathway. Trends in Biochemical Sciences 29:358–63. https://doi.org/10.1016/j.tibs.2004.05.007.  
**41.** Lane N., Allen J.F., and Martin W. (2010). How did LUCA make a living? Chemiosmosis in the origin of life. BioEssays: News and Reviews in Molecular, Cellular and Developmental Biology 32:271–80. https://doi.org/10.1002/bies.200900131.  
**42.** Christianson D.W. (2007). Chemistry. Roots of biosynthetic diversity. Science 316:60–1. https://doi.org/10.1126/science.1141630.  
**43.** Abbas F., Ke Y., Yu R., Yue Y., Amanullah S., Jahangir M.M., et al. (2017). Volatile Terpenoids: Multiple Functions, Biosynthesis, Modulation and Manipulation by Genetic Engineering. Planta 246:803–16. https://doi.org/10.1007/s00425-017-2749-x.  
**44.** Tetali S.D. (2019). Terpenes and Isoprenoids: A Wealth of Compounds for Global Use. Planta 249:1–8. https://doi.org/10.1007/s00425-018-3056-x.  
**45.** Fäldt J., Arimura G., Gershenzon J., Takabayashi J., and Bohlmann J. (2003). Functional identification of AtTPS03 as (E)-beta-ocimene synthase: A monoterpene synthase catalyzing jasmonate- and wound-induced volatile formation in Arabidopsis thaliana. Planta 216:745–51. https://doi.org/10.1007/s00425-002-0924-0.  
**46.** Zalucki M.P., Brower L.P., and Alonso M.A. (2001). Detrimental Effects of Latex and Cardiac Glycosides on Survival and Growth of First-Instar Monarch Butterfly Larvae Danaus Plexippus Feeding on the Sandhill Milkweed Asclepias Humistrata. Ecological Entomology 26:212–24. https://doi.org/10.1046/j.1365-2311.2001.00313.x.  
**47.** Li X.P., Björkman O., Shih C., Grossman A.R., Rosenquist M., Jansson S., et al. (2000). A pigment-binding protein essential for regulation of photosynthetic light harvesting. Nature 2000;403:391–5. https://doi.org/10.1038/35000131.  
**48.** Grassmann J. (2005). Terpenoids as Plant Antioxidants. Vitamins and Hormones 2005;72:505–35. https://doi.org/10.1016/S0083-6729(05)72015-X.  
**49.** Leverenz R.L., Sutter M., Wilson A., Gupta S., Thurotte A., Bourcier de Carbon C., et al. (2015). A 12 å carotenoid translocation in a photoswitch associated with cyanobacterial photoprotection. Science 348:1463–6. https://doi.org/10.1126/science.aaa7234.  
**50.** Araújo E.C.C., Silveira E.R., Lima M.A.S., Neto M.A., Andrade I.L. de, Lima M.A.A., et al. (2003). Insecticidal Activity and Chemical Composition of Volatile Oils from Hyptis Martiusii Benth. Journal of Agricultural and Food Chemistry 51:3760–2. https://doi.org/10.1021/jf021074s.  
**51.** Regnault-Roger C., Vincent C., and Arnason J.T. (2012). Essential Oils in Insect Control: Low-Risk Products in a High-Stakes World. Annual Review of Entomology 57:405–24. https://doi.org/10.1146/annurev-ento-120710-100554.  
**52.** Tholl D. (2015). Biosynthesis and Biological Functions of Terpenoids in Plants. Advances in Biochemical Engineering/Biotechnology 148:63–106. https://doi.org/10.1007/10_2014_295.  
**53.** Pavela R., and Benelli G. (2016). Essential Oils as Ecofriendly Biopesticides? Challenges and Constraints. Trends in Plant Science 21:1000–7. https://doi.org/10.1016/j.tplants.2016.10.005.  
**54.** Scalerandi E., Flores G.A., Palacio M., Defagó M.T., Carpinella M.C., Valladares G., et al. (2018). Understanding Synergistic Toxicity of Terpenes as Insecticides: Contribution of Metabolic Detoxification in Musca Domestica. Frontiers in Plant Science 9: https://doi.org/10.3389/fpls.2018.01579.  
**55.** Kwok-Keung Fung B. and Stryer L. (1980). Photolyzed rhodopsin catalyzes the exchange of GTP for bound GDP in retinal rod outer segments. Proceedings of the National Academy of Sciences of the United States of America 1980;77:2500–4. https://doi.org/10.1073/pnas.77.5.2500.  
**56.** Liebman P.A. and Pugh E.N.J. (1980). ATP mediates rapid reversal of cyclic GMP phosphodiesterase activation in visual receptor membranes. Nature 287:734–6. https://doi.org/10.1038/287734a0.  
**57.** Kühn H., Bennett N., Michel-Villaz M., and Chabre M. (1981). Interactions between photoexcited rhodopsin and GTP-binding protein: Kinetic and stoichiometric analyses from light-scattering changes. Proceedings of the National Academy of Sciences of the United States of America 78:6873–7. https://doi.org/10.1073/pnas.78.11.6873.  
**58.** Wilden U., Hall S.W., and Kühn H. (1986). Phosphodiesterase activation by photoexcited rhodopsin is quenched when rhodopsin is phosphorylated and binds the intrinsic 48-kDa protein of rod outer segments. Proceedings of the National Academy of Sciences of the United States of America 83:1174–8. https://doi.org/10.1073/pnas.83.5.1174.  
**59.** Palczewski K., Buczyłko J., Kaplan M.W., Polans A.S., and Crabb J.W. (1991). Mechanism of rhodopsin kinase activation. The Journal of Biological Chemistry 266:12949–55.  
**60.** Palczewski K. (2012). Chemistry and biology of vision. The Journal of Biological Chemistry 287:1612–9. https://doi.org/10.1074/jbc.R111.301150.  
**61.** Strickland S. and Mahdavi V. (1978). The induction of differentiation in teratocarcinoma stem cells by retinoic acid. Cell 15:393–403.   https://doi.org/10.1016/0092-8674(78)90008-9.
**62.** Tickle C., Alberts B., Wolpert L., and Lee J. (1982). Local application of retinoic acid to the limb bond mimics the action of the polarizing region. Nature 296:564–6. https://doi.org/10.1038/296564a0.  
**63.** Gudas L.J. and Wagner J.A. (2012). Retinoids regulate stem cell differentiation. Journal of Cellular Physiology 2011;226:322–30. https://doi.org/10.1002/jcp.22417.  
**64.** Rhinn M. and Dollé P. (2012). Retinoic acid signalling during development. Development 139:843–58. https://doi.org/10.1242/dev.065938.  
**65.** Cunningham T.J. and Duester G. (2015) Mechanisms of retinoic acid signalling and its roles in organ and limb development. Nature Reviews Molecular Cell Biology 16:110–23. https://doi.org/10.1038/nrm3932.  
**66.** Ghyselinck N.B. and Duester G. (2019). Retinoic acid signaling pathways. Development 146: https://doi.org/10.1242/dev.167502.  
**67.** Roberts C. (2020). Regulating Retinoic Acid Availability during Development and Regeneration: The Role of the CYP26 Enzymes. Journal of Developmental Biology 8: https://doi.org/10.3390/jdb8010006.  
**68.** Giguere V., Ong E.S., Segui P., and Evans R.M. (1987). Identification of a receptor for the morphogen retinoic acid. Nature 330:624–9.   https://doi.org/10.1038/330624a0.  
**69.** Petkovich M., Brand N.J., Krust A., and Chambon P. (1987). A human retinoic acid receptor which belongs to the family of nuclear receptors. Nature 330:444–50. https://doi.org/10.1038/330444a0.  
**70.** Niederreither K., Subbarayan V., Dollé P., and Chambon P. (1999). Embryonic retinoic acid synthesis is essential for early mouse post-implantation development. Nature Genetics 1999;21:444–8. https://doi.org/10.1038/7788.  
**71.** Duester G. (2008). Retinoic acid synthesis and signaling during early organogenesis. Cell 134:921–31. https://doi.org/10.1016/j.cell.2008.09.002.  
**72.** Hosler D., Burkett S.L., and Tarkanian M.J. (1999) Prehistoric Polymers: Rubber Processing in Ancient Mesoamerica. Science 284:1988. https://doi.org/10.1126/science.284.5422.1988.  
**73.** American Chemical Society National Historic Chemical Landmarks. U.S. Synthetic Rubber Program, 1939-1945. 2019.  
**74.** Pickard W.F. (2008). Laticifers and Secretory Ducts: Two Other Tube Systems in Plants. The New Phytologist 177:877–88. https://doi.org/10.1111/j.1469-8137.2007.02323.x.  
**75.** Castelblanque L., Balaguer B., Martí C., Rodríguez J.J., Orozco M., and Vera P. (2017). Multiple Facets of Laticifer Cells. Plant Signaling & Behavior 12:https://doi.org/10.1080/15592324.2017.1300743.  
**76.** Ramos M.V., Demarco D., Costa Souza I.C. da, and Freitas C.D.T. de. (2019). Laticifers, Latex, and Their Role in Plant Defense. Trends in Plant Science 24:553–67. https://doi.org/10.1016/j.tplants.2019.03.006.  
**77.** Dussourd D.E., and Eisner T. (1987). Vein-Cutting Behavior: Insect Counterploy to the Latex Defense of Plants. Science 237:898–901. https://doi.org/10.1126/science.3616620.  
**78.** Dussourd D.E. (1999). Behavioral Sabotage of Plant Defense: Do Vein Cuts and Trenches Reduce Insect Exposure to Exudate? Journal of Insect Behavior 12:501–15. https://doi.org/10.1023/A:1020966807633.  
**79.** Zalucki M., Brower L.P. (1992). Survival of First Instar Larvae of Danaus Plexippus (Lepidoptera: Danainae) in Relation to Cardiac Glycoside and Latex Content of *Asclepias Humistrata* (Asclepiadaceae). CHEMOECOLOGY 3:81–93. https://doi.org/10.1007/BF01245886.
**80.** Zalucki M.P., Brower L.P., and Alonso‐M.A. (2001). Detrimental effects of latex and cardiac glycosides on survival and growth of first‐instar monarch butterfly larvae Danaus plexippus feeding on the sandhill milkweed *Asclepias humistrata*. Ecological Entomology 26(2):212-224.  
**81** Farmer E.E. and Ryan C.A. (1992). Octadecanoid Precursors of Jasmonic Acid Activate the Synthesis of Wound-Inducible Proteinase Inhibitors. The Plant Cell 4:129–34. https://doi.org/10.1105/tpc.4.2.129.  
**82.** Schittko U., Preston C.A., and Baldwin I.T. (2000). Eating the Evidence? Manduca Sexta Larvae Can Not Disrupt Specific Jasmonate Induction in Nicotiana Attenuata by Rapid Consumption. Planta 210:343–6. https://doi.org/10.1007/PL00008143.  
**83** Turner J.G., Ellis C., and Devoto A. (2002). The Jasmonate Signal Pathway. The Plant Cell 14 Suppl:S153–164. https://doi.org/10.1105/tpc.000679.  
**84.** Rasmann S., Agrawal A.A., Cook S.C., and Erwin A.C. (2009). Cardenolides, induced responses, and interactions between above‐and belowground herbivores of milkweed (*Asclepias spp.*). Ecology 90(9):2393-2404. https://doi.org/10.1890/08-1895.1.  
**85.** Agrawal A.A., Hastings A.P., Patrick E.T., and Knight A.C. (2014). Specificity of Herbivore-Induced Hormonal Signaling and Defensive Traits in Five Closely Related Milkweeds (Asclepias Spp.). Journal of Chemical Ecology 40:717–29. https://doi.org/10.1007/s10886-014-0449-6.  
**86.** Castelblanque L., Balaguer B., Marti C., Orozco M., and Vera P. (2018). LOL2 and LOL5 Loci Control Latex Production by Laticifer Cells in Euphorbia Lathyris. The New Phytologist 219:1467–79. https://doi.org/10.1111/nph.15253.  
**87.** Agrawal A., Petschenka A., Bingham R., Weber M., and Rasmann S. (2012). Toxic Cardenolides: Chemical Ecology and Coevolution of Specialized Plant-Herbivore Interactions. The New Phytologist 194:28–45. https://doi.org/10.1111/j.1469-8137.2011.04049.x.  
**88.** Dobler S., Petschenka G., Wagschal V., and Flacht L. (2015). Convergent Adaptive Evolution – How Insects Master the Challenge of Cardiac Glycoside-Containing Host Plants. Entomologia Experimentalis Et Applicata 157:30–9. https://doi.org/10.1111/eea.12340.  
**89.** Canada H. Summary Safety Review - Lanoxin, Toloxin, Apo-Digoxin, PMS-Digoxin, (Digoxin) - Assessing the Potential Higher Risk of Death Compared to Patients Not Using Digoxin. Aem 2016. https://www.canada.ca/en/health-canada/services/drugs-health-products/medeffect-canada/safety-reviews/summary-safety-review-lanoxin-toloxin-digoxin-digoxin-digoxin-assessing-potential-higher-risk-death-compared-patients-using-digoxin.html  
**90.** Skou, J.C. (1957). The influence of some cations on an adenosine triphosphatase from peripheral nerves. Biochimica et biophysica acta. 23:394-401.  
**91.** Jorgensen P.L., Håkansson K.O., and Karlish S.J. (2003). Structure and mechanism of Na, K-ATPase: functional sites and their interactions. Annual Review of Physiology 65(1):817-849.  
**92.** Kühlbrandt, W. (2004). Biology, structure and mechanism of P-type ATPases. Nature Reviews Molecular Cell Biology 5(4):282-295.  
**93.** Clausen M.V., Hilbers F., and Poulsen H. (2017). The Structure and Function of the Na,K-ATPase Isoforms in Health and Disease. Frontiers in Physiology 8:371 https://doi.org/10.3389/fphys.2017.00371.  
**94.** Gagnon K.B. and Delpire E. (2021). Sodium transporters in human health and disease. Frontiers in Physiology 11:p.588664.  
**95.** Mulkidjanian A.Y., Bychkov A.Y., Dibrova D.V., Galperin M.Y. and Koonin E.V. (2012). Origin of first cells at terrestrial, anoxic geothermal fields. Proceedings of the National Academy of Sciences 109(14):E821-E830.  
**96.** Mulkidjanian A.Y. and Galperin M.Y. (2007). Physico‐chemical and evolutionary constraints for the formation and selection of first biopolymers: towards the consensus paradigm of the abiogenic origin of life. Chemistry & Biodiversity 4(9):2003-2015.  
**97.** Morth J.P., Pedersen B.P., Toustrup-Jensen M.S., Sørensen T.L.M., Petersen J., Andersen J.P., Vilsen B., and Nissen P. (2007). Crystal structure of the sodium–potassium pump. Nature 450(7172):1043-1049.  
**98.** Pettersen E.F., Goddard T.D., Huang C.C., Meng E.C., Couch G.S., Croll T.I., Morris J.H., and Ferrin T.E. (2021). UCSF ChimeraX: Structure visualization for researchers, educators, and developers. Protein Science 30(1):70-82.  
**99.** El Mernissi G. and Doucet A. (1984). Quantitation of [3H]Ouabain Binding and Turnover of Na-K-ATPase along the Rabbit Nephron. The American Journal of Physiology 247:F158–167. https://doi.org/10.1152/ajprenal.1984.247.1.F158.  
**100.** Attwell D. and Laughlin S.B. (2001). An Energy Budget for Signaling in the Grey Matter of the Brain. Journal of Cerebral Blood Flow and Metabolism: Official Journal of the International Society of Cerebral Blood Flow and Metabolism 21:1133–45. https://doi.org/10.1097/00004647-200110000-00001.  
**101.** Sengupta B., Stemmler M., Laughlin S.B. and Niven J.E. (2010). Action potential energy efficiency varies among neuron types in vertebrates and invertebrates. PLoS Computational Biology, 6(7):p.e1000840. doi:10.1371/journal.pcbi.1000840  
**102.** Engl E. and Attwell D. (2015). Non‐signalling energy use in the brain. The Journal of Physiology 593(16):3417-3429. doi:10.1523/JNEUROSCI.3430-11.2012  
**103.** Albers R.W. (1967). Biochemical aspects of active transport. Annual Review of Biochemistry 36(1):727-756.  
**104.** Post R.L., Hegyvary C., and Kume S. (1972). Activation by adenosine triphosphate in the phosphorylation kinetics of sodium and potassium ion transport adenosine triphosphatase. Journal of Biological Chemistry 247(20):6530-6540.  
**105.** Apell H.J. (2019). Finding Na, K-ATPase. II – From Fluxes to Ion Movements. Substantia 3(1):19-41.  
**106.** Wallace, A.R. (1871) Contributions to the Theory of Natural Selection. A Series of Essays. Part III: Mimicry, and Other Protective Resemblances Among Animals. pg. 45-129. 2<sup>nd</sup> edition, London: MacMillan and Co., Printed by Head, Hole & CO., Farringdon Street, and Ivy Lane, E.C. [First published in the "Westminister Review" July 1867. Reprinted with a few corrections and some important additions].  
**107.** Wallace, A.R. (1877). The colors of animals and plants. The American Naturalist, 11(11):641-662.  
**108.** Slater, J.W. (1877). XV. On the Food of Gaily‐coloured Caterpillars. Transactions of the Royal Entomological Society of London 25(3):205-209.  
**109.** Poulton, E.B. (1890). The Colours of Animals, their meaning and use, especially considered in the case of insects. Series: The International Scientific Series, vol. LXVII, New York, D. Appleton and Company, 1890.  
**110.** Parsons, J.A. (1965). A digitalis-like toxin in the monarch butterfly, *Danaus plexippus L*. The Journal of Physiology 178(2):290-304.  
**111.** Repke, K.R.H. and Portius H.J. (1963). Uber die Identitat der Ionenpumpen-ATP-ase in der Zellmembran des Herzmuskels mit einem Digitalis-Rezeptorenzym. Experientia 19:452-458.  
**112.** Reichstein T.V., Von Euw J., Parsons J.A. and Rothschild, M. (1968). Heart Poisons in the Monarch Butterfly: Some aposematic butterflies obtain protection from cardenolides present in their food plants. Science 161(3844):861-866.  
**113.** Schatzmann, H.J. (1953). Herzglykoside als Hemmstoffe fur den activen Kalium und Natrium-Transport durch die Erythrocytemembran. Helv. Physiol. Pharmacol. Acta, 11:34 6-354.  
**114.** Shull G.E., Schwartz A., and Lingrel J.B. (1985). Amino-acid sequence of the catalytic subunit of the (Na<sup>+</sup>+K<sup>+</sup>) ATPase deduced from a complementary DNA. Nature 316(6030):691-695.  
**115.** Price E.M. and Lingrel J.B. (1988). Structure-Function Relationships in the Na,K-ATPase Alpha Subunit: Site-Directed Mutagenesis of Glutamine-111 to Arginine and Asparagine-122 to Aspartic Acid Generates a Ouabain-Resistant Enzyme. Biochemistry 27:8400–8. https://doi.org/10.1021/bi00422a016.  
**116.** Price E.M., Rice D.A., and Lingrel J.B. (1990). Structure-Function Studies of Na,K-ATPase. Site-Directed Mutagenesis of the Border Residues from the H1-H2 Extracellular Domain of the Alpha Subunit. The Journal of Biological Chemistry 265:6638–41.  
**117.** Canfield V., Emanuel J.R., Spickofsky N., Levenson R., and Margolskee R.F. (1990). Ouabain-resistant mutants of the rat Na, K-ATPase alpha 2 isoform identified by using an episomal expression vector. Molecular and Cellular Biology 10(4):1367-1372.  
**118.** Holzinger F., Frick C., and Wink M. (1992). Molecular basis for the insensitivity of the Monarch (Danaus plexippus) to cardiac glycosides. FEBS Letters 314(3):477-480.  
**119.** Zhan S., Merlin C., Boore J.L., and Reppert S.M. (2011). The monarch butterfly genome yields insights into long-distance migration. Cell 147(5):1171-1185.  
**120.** Ogawa H., Shinoda T., Cornelius F. and Toyoshima C. (2009). Crystal structure of the sodium-potassium pump (Na<sup>+</sup>, K<sup>+</sup>-ATPase) with bound potassium and ouabain. Proceedings of the National Academy of Sciences 106(33):13742-13747.  
**121.** Kanai R., Cornelius F., Ogawa H., Motoyama K., Vilsen B., and Toyoshima C. (2021). Binding of cardiotonic steroids to Na<sup>+</sup>, K<sup>+</sup>-ATPase in the E2P state. Proceedings of the National Academy of Sciences 118(1):p.e2020438118.  
**122.** Waterhouse A.M., Procter J.B., Martin D.M.A, Clamp M. and Barton G.J. (2009). Jalview Version 2 - a multiple sequence alignment editor and analysis workbench. Bioinformatics 25(9):1189-1191. doi: 10.1093/bioinformatics/btp033  
**123.** Zhen Y, Aardema ML, Medina EM, Schumer M, Andolfatto P. (2012). Parallel Molecular Evolution in an Herbivore Community. Science 337:1634–1637. https://doi.org/10.1126/science.1226630.  
**124.** Dobler S., Dalla S., Wagschal V., and Agrawal A.A. (2012). Community-Wide Convergent Evolution in Insect Adaptation to Toxic Cardenolides by Substitutions in the Na,K-ATPase. Proceedings of the National Academy of Sciences of the United States of America 109:13040–5. https://doi.org/10.1073/pnas.1202111109.  
**125.** Ujvari B, Casewell NR, Sunagar K, Arbuckle K, Wüster W, Lo N, et al. (2015). Widespread Convergence in Toxin Resistance by Predictable Molecular Evolution. Proceedings of the National Academy of Sciences of the United States of America 112:11911–11916. https://doi.org/10.1073/pnas.1511706112.  
**126.** Al-Robai, A.A. (1993). Different ouabain sensitivities of Na<sup>+</sup>/K<sup>+</sup>-ATPase from *Poekilocerus bufonius* tissues and a possible physiological cost. Comparative Biochemistry and Physiology B, Comparative Biochemistry 106(4):805-812.  
**127.** Sun B., Wang W., and Salvaterra P.M. (1998). Functional analysis and tissue‐specific expression of Drosophila Na<sup>+</sup>, K<sup>+</sup>‐ATPase subunits. Journal of Neurochemistry 71(1):142-151.  
**128.** Dalla S., and Dobler S. (2016). Gene duplications circumvent trade‐offs in enzyme function: Insect adaptation to toxic host plants. Evolution 70(12):2767-2777.  
**129.** Dalla S., Baum M., and Dobler S. (2017). Substitutions in the cardenolide binding site and interaction of subunits affect kinetics besides cardenolide sensitivity of insect Na, K-ATPase. Insect Biochemistry and Molecular Biology 89:43-50.  
**130.** Petschenka G., Wagschal V., von Tschirnhaus M., Donath A., and Dobler S. (2017). Convergently evolved toxic secondary metabolites in plants drive the parallel molecular evolution of insect resistance. The American Naturalist 190(S1):S29-S43.  
**131.** Dobler S., Wagschal V., Pietsch N., Dahdouli N., Meinzer F., Romey-Glüsing R., and Schütte K. (2019). New ways to acquire resistance: imperfect convergence in insect adaptations to a potent plant toxin. Proceedings of the Royal Society B, 286(1908):p.20190883.  
**132.** Yang L., Ravikanthachari N., Mariño-Pérez R., Deshmukh R., Wu M., Rosenstein A., Kunte K., Song H., and Andolfatto P. (2019). Predictability in the evolution of *Orthopteran* cardenolide insensitivity. Philosophical Transactions of the Royal Society B 374(1777):p.20180246.  
**133.** Taverner A.M., Yang L., Barile Z.J., Lin B., Peng J., Pinharanda A.P., Rao A.S., Roland B.P., Talsma A.D., Wei D., and Petschenka G. (2019). Adaptive substitutions underlying cardiac glycoside insensitivity in insects exhibit epistasis in vivo. Elife 8:p.e48224.  
**134.** Odenwald M.A., and Turner, J.R. (2017). The intestinal epithelial barrier: a therapeutic target?. Nature Reviews Gastroenterology and Hepatology 14(1):9-21.  
**135.** Peltonen S., Alanne M., and Peltonen, J. (2013). Barriers of the peripheral nerve. Tissue barriers 1(3):p.e24956.  
**136.** Krieger R.I., Feeny P.P., and Wilkinson C.F. (1971). Detoxication enzymes in the guts of caterpillars: an evolutionary answer to plant defenses?. Science 172(3983):579-581.  
**137.** Brattsten L.B., Wilkinson C.F. and Eisner T. (1977). Herbivore-plant interactions: mixed-function oxidases and secondary plant substances. Science 196(4296):1349-1352.  
**138.** Ahmad S. (1983). Mixed‐function oxidase activity in a generalist herbivore in relation to its biology, food plants, and feeding history. Ecology 64(2):235-243.  
**139.** Li W., Schuler M.A., and Berenbaum M.R. (2003). Diversification of furanocoumarin-metabolizing cytochrome P450 monooxygenases in two papilionids: specificity and substrate encounter rate. Proceedings of the National Academy of Sciences 100(suppl2):14593-14598.  
**140.** Nauen R., Bass C., Feyereisen R., and Vontas J. (2022). The role of cytochrome P450s in insect toxicology and resistance. Annual Review of Entomology 67:105-124.  
**141.** Guengerich F.P. (2018). Mechanisms of cytochrome P450-catalyzed oxidations. ACS catalysis 8(12):10964-10976.  
**142.** Després L., David J.P., and Gallet C. (2007). The evolutionary ecology of insect resistance to plant chemicals. Trends in Ecology and Evolution 22(6):298-307.  
**143.** Enayati A.A., Ranson H., and Hemingway J. (2005). Insect glutathione transferases and insecticide resistance. Insect Molecular Biology 14(1):3-8.  
**144.** Meech R., and Mackenzie P.I. (1997). Structure and function of uridine diphosphate glucuronosyltransferases. Clinical and Experimental Pharmacology and Physiology 24(12):907-915.  
**145.** Luque T., Okano K., and O'Reilly D.R. (2002). Characterization of a novel silkworm (Bombyx mori) phenol UDP‐glucosyltransferase. European journal of biochemistry, 269(3), pp.819-825.  
**146.** Miyauchi Y., Takechi S., and Ishii Y. (2021). Functional Interaction between Cytochrome P450 and UDP-Glucuronosyltransferase on the Endoplasmic Reticulum Membrane: One of Post-translational Factors Which Possibly Contributes to Their Inter-Individual Differences. Biological and Pharmaceutical Bulletin 44(11):1635-1644.  
**147.** Mayer U., Wagenaar E., Beijnen J.H., Smit J.W., Meijer D.K., van Asperen J., Borst P., and Schinkel A.H. (1996). Substantial excretion of digoxin via the intestinal mucosa and prevention of long-term digoxin accumulation in the brain by the mdr1a P-glycoprotein. British Journal of Pharmacology 119(5):1038-1044.  
**148.** Dermauw W., and Van Leeuwen T. (2014). The ABC gene family in arthropods: comparative genomics and role in insecticide transport and resistance. Insect Biochemistry and Molecular Biology 45:89-110.  
**149.** Groen S.C., LaPlante E.R., Alexandre N.M., Agrawal A.A., Dobler S., and Whiteman N.K. (2017). Multidrug transporters and organic anion transporting polypeptides protect insects against the toxic effects of cardenolides. Insect Biochemistry and Molecular Biology 81:51-61.  
**150.** Riordan J.R., Deuchars K., Kartner N., Alon N., Trent J., and Ling, V. (1985). Amplification of P-glycoprotein genes in multidrug-resistant mammalian cell lines. Nature 316(6031):817-819.  
**151.** Abu-Qare A., Elmasry E., and Abou-Donia M. (2003). A role for P-glycoprotein in environmental toxicology. Journal of Toxicology and Environmental Health, Part B 6(3):279-288. 
**152.** Chahine S., and O'Donnell M.J. (2011). Interactions between detoxification mechanisms and excretion in Malpighian tubules of Drosophila melanogaster. Journal of Experimental Biology 214(3):462-468.  
**153.** Hamberger B., and Bak S. (2013). Plant P450s as versatile drivers for evolution of species-specific chemical diversity. Philosophical Transactions of the Royal Society B: Biological Sciences 368(1612):p.20120426.  
**154.** Parvez M., Qhanya L.B., Mthakathi N.T., Kgosiemang I.K.R., Bamal H.D., Pagadala N.S., Xie T., Yang H., Chen H., Theron C.W., Monyaki R., Raselemane S.C., Salewe V., Mongale B.L., Matowane R.G., Abdalla S.M.H., Booi W.I., van Wyk M., Olivier D., Boucher C.E., Nelson D.R., Tuszynski J.A., Blackburn J.M., Yu J.H., Mashele S.S., Chen W., and Khajamohiddin S. (2016). Molecular evolutionary dynamics of cytochrome P450 monooxygenases across kingdoms: Special focus on mycobacterial P450s. Scientific Reports 6(1):p.33099.  
**155.** Dixon R.A., and Barros J. (2019). Lignin biosynthesis: old roads revisited and new roads explored. Open Biology 9(12):p.190215. http://dx.doi.org/10.1098/rsob.190215  
**156.** Tamura K., Stecher G., and Kumar S. (2021). MEGA11: molecular evolutionary genetics analysis version 11. Molecular Biology and Evolution 38(7):3022-3027. https://doi.org/10.1093/molbev/msab120.  
**157.** Jones D.T., Taylor W.R., and Thornton J.M. (1992). The rapid generation of mutation data matrices from protein sequences. Computer Applications in the Biosciences 8:275-282.  
**158.** Felsenstein J. (1985). Confidence limits on phylogenies: An approach using the bootstrap. Evolution 39(4):783-791.  
**159.** Wilkins M.R., Kendall M.J., and Wade O.L. (1985). William Withering and Digitalis, 1785 to 1985. British Medical Journal 290:7–8. https://doi.org/10.1136/bmj.290.6461.7.
**160.** Cattell M, Gold H. The Influence of Digitalis Glucosides on the Force of Contraction of Mammalian Cardiac Muscle. Journal of Pharmacology and Experimental Therapeutics 1938;62:116–125.  
**161.** Blaustein M.P., Zhang J., Chen L., and Hamilton B.P. (2006). How does salt retention raise blood pressure? American Journal of Physiology-Regulatory, Integrative and Comparative Physiology 290(3):R514-R523.  
**162.** Peng M., Huang L., Xie Z., Huang W.H., and Askari A. (1996). Partial Inhibition of Na+/K+-ATPase by Ouabain Induces the Ca<sup>2+</sup>-Dependent Expressions of Early-Response Genes in Cardiac Myocytes. The Journal of Biological Chemistry 271:10372–10378. https://doi.org/10.1074/jbc.271.17.10372.  
**163.** Aizman O., Uhlén P., Lal M., Brismar H., and Aperia A. (2001). Ouabain, a Steroid Hormone That Signals with Slow Calcium Oscillations. Proceedings of the National Academy of Sciences of the United States of America 98:13420–13424. https://doi.org/10.1073/pnas.221315298.  
**164.** Aydemir-Koksoy A., Abramowitz J., and Allen J.C. (2001). Ouabain-induced signaling and vascular smooth muscle cell proliferation. Journal of Biological Chemistry 276(49):46605-46611.  
**165.** Liu X., Spicarova Z., Rydholm S., Li J., Brismar H., and Aperia A. (2008). Ankyrin B modulates the function of Na, K-ATPase/inositol 1,4,5-trisphosphate receptor signaling microdomain. Journal of Biological Chemistry 283(17):11461-11468.  
**166.** Fontana J.M., Burlaka I., Khodus G., Brismar H., and Aperia A. (2013). Calcium oscillations triggered by cardiotonic steroids. The FEBS Journal 280(21):5450-5455.  
**167.** Panizza E., Zhang L., Fontana J.M., Hamada K., Svensson D., Akkuratov E.E., Scott L., Mikoshiba K., Brismar H., Lehtiö J., and Aperia A. (2019). Ouabain-regulated phosphoproteome reveals molecular mechanisms for Na+, K+–ATPase control of cell adhesion, proliferation, and survival. The FASEB Journal 33(9):p.10193.  
**168.** Wang Y., Lonard D.M., Yu Y., Chow D.C., Palzkill T.G., Wang J., Qi R., Matzuk A.J., Song X., Madoux F., and Hodder P. (2014). Bufalin is a Potent Small-Molecule Inhibitor of the Steroid Receptor Coactivators SRC-3 and SRC-1 Bufalin Is a Steroid Receptor Coactivator Inhibitor. Cancer Research 74(5):1506-1517.  
**169.** Shiratori O. (1967). Growth Inhibitory Effect of Cardiac Glycosides and Aglycones on Neoplastic Cells: In Vitro and in Vivo Studies. GANN Japanese Journal of Cancer Research 58:521–528.  
**170.** Stenkvist B., Bengtsson E., Eklund G., Eriksson O., Holmquist J., Nordin B., and Westman-Naeser S. (1980). Evidence of a modifying influence of heart glucosides on the development of breast cancer. Analytical and Quantitative Cytology 2(1):49-54.  
**171.** Stenkvist B. (1999). Is Digitalis a Therapy for Breast Carcinoma? Oncology Reports 6:493–496.  
**172.** Johansson S., Lindholm P., Gullbo J., Larsson R., Bohlin L., and Claeson P. (2001). Cytotoxicity of Digitoxin and Related Cardiac Glycosides in Human Tumor Cells. Anti-Cancer Drugs 12:475–483.  
**173.** Johnson P.H., Walker R.P., Jones S.W., Stephens K., Meurer J., Zajchowski D.A., Luke M.M., Eeckman F., Tan Y., Wong L., and Parry G. (2002). Multiplex gene expression analysis for high-throughput drug discovery: screening and analysis of compounds affecting genes overexpressed in cancer cells. Molecular Cancer Therapeutics 1(14):1293-1304.  
**174.** Newman R.A., Yang P., Pawlus A.D., and Block K.I. (2008). Cardiac Glycosides as Novel Cancer Therapeutic Agents. Molecular Interventions 8:36–49. https://doi.org/10.1124/mi.8.1.8.  
**175.** Botelho A.F.M., Pierezan F., Soto-Blanco B., and Melo M.M. (2019). A Review of Cardiac Glycosides: Structure, Toxicokinetics, Clinical Signs, Diagnosis and Antineoplastic Potential. Toxicon 158:63–68. https://doi.org/10.1016/j.toxicon.2018.11.429  
**176.** Galluzzi L., Buqué A., Kepp O., Zitvogel L., and Kroemer G. (2015). Immunological Effects of Conventional Chemotherapy and Targeted Anticancer Agents. Cancer Cell 28:690–714. https://doi.org/10.1016/j.ccell.2015.10.012.  
**177.** Mijatovic T., Van Quaquebeke E., Delest B., Debeir O., Darro F., and Kiss, R. (2007). Cardiotonic steroids on the road to anti-cancer therapy. Biochimica et Biophysica Acta (BBA)-Reviews on Cancer 1776(1):32-57.  
**178.** Simpson C.D., Mawji I.A., Anyiwe K., Williams M.A., Wang X., Venugopal A.L., Gronda M., Hurren R., Cheng S., Serra S., and Zavareh R.B. (2009). Inhibition of the sodium potassium adenosine triphosphatase pump sensitizes cancer cells to anoikis and prevents distant tumor formation. Cancer Research 69(7):2739-2747.  
**179.** Menger L., Vacchelli E., Adjemian S., Martins I., Ma Y., Shen S., Yamazaki T., Sukkurwala A.Q., Michaud M., Mignot G., and Schlemmer F. (2012). Cardiac glycosides exert anticancer effects by inducing immunogenic cell death. Science Translational Medicine 4(143):pp.143ra99. https://doi.org/10.1126/scitranslmed.3003807.  
**180.** Cerella C., Dicato M., and Diederich M. (2013). Assembling the Puzzle of Anti-Cancer Mechanisms Triggered by Cardiac Glycosides. Mitochondrion 13:225–234. https://doi.org/10.1016/j.mito.2012.06.003.  
**181.** Yuan B., He J., Kisoh K., Hayashi H., Tanaka S., Si N., Zhao H.Y., Hirano T., Bian B., and Takagi N. (2016). Effects of Active Bufadienolide Compounds on Human Cancer Cells and CD4+CD25+Foxp3+ Regulatory T Cells in Mitogen-Activated Human Peripheral Blood Mononuclear Cells. Oncology Reports 36:1377–1384. https://doi.org/10.3892/or.2016.4946.  
**182.** Agrawal A.A., and Konno K. (2009). Latex: A Model for Understanding Mechanisms, Ecology, and Evolution of Plant Defense against Herbivory. Annual Review Ecololgy Evolution Systematics 40:311–31.  
**183.** Rawlings N.D., and Barrett A.J. (1993). Evolutionary families of peptidases. Biochemical Journal 290:205–218. https://doi.org/10.1042/bj2900205.  
**184.** López-Otín C., and Bond J.S. (2008). Proteases: Multifunctional Enzymes in Life and Disease. The Journal of Biological Chemistry 283:30433–30437. https://doi.org/10.1074/jbc.R800035200.  
**185.** Hoorn RAL van der. (2008). Plant Proteases: From Phenotypes to Molecular Mechanisms. Annual Review of Plant Biology 59:191–223. https://doi.org/10.1146/annurev.arplant.59.032607.092835.  
**186.** Blow D.M. (1997). The tortuous story of Asp…His…Ser: Structural analysis of α-chymotrypsin. Trends in Biochemical Sciences 22:405–408. https://doi.org/10.1016/S0968-0004(97)01115-8.  
**187.** Schaller A. (2004). A Cut above the Rest: The Regulatory Function of Plant Proteases. Planta 220:183–197. https://doi.org/10.1007/s00425-004-1407-2.  
**188.** Domsalla A., and Melzig M.F. (2008). Occurrence and Properties of Proteases in Plant Latices. Planta Medica 74:699–711. https://doi.org/10.1055/s-2008-1074530.  
**189.** Berger J., and Asenjo C.F. (1940). ANTHELMINTIC ACTIVITY OF CRYSTALLINE PAPAIN. Science (New York, NY) 91:387–388. https://doi.org/10.1126/science.91.2364.387.  
**190.** Starley I.F., Mohammed P., Schneider G., and Bickler S.W. (1999). The Treatment of Paediatric Burns Using Topical Papaya. Burns: Journal of the International Society for Burn Injuries 25:636–639. https://doi.org/10.1016/s0305-4179(99)00056-x.  
**191.** Maurer H.R. (2001). Bromelain: Biochemistry, Pharmacology and Medical Use. Cellular and Molecular Life Sciences: CMLS 58:1234–1245. https://doi.org/10.1007/PL00000936.  
**192.** Yaakobi T., Cohen-Hadar N., Yaron H., Hirszowicz E., Simantov Y., Bass A., and Freeman A. (2007). Wound Debridement by Continuous Streaming of Proteolytic Enzyme Solutions: Effects on Experimental Chronic Wound Model in Porcin. Wounds: a Compendium of Clinical Research and Practice 19(7):192-200.  
**193.** Rosenberg L., Shoham Y., Krieger Y., Rubin G., Sander F., Koller J., David K., Egosi D., Ahuja R., and Singer A.J. (2015). Minimally invasive burn care: a review of seven clinical studies of rapid and selective debridement using a bromelain-based debriding enzyme (Nexobrid®). Annals of Burns and Fire Disasters, 28(4):264-274.  
**194.** Chobotova K., Vernallis A.B., and Majid F.A.A. (2010). Bromelain’s Activity and Potential as an Anti-Cancer Agent: Current Evidence and Perspectives. Cancer Letters 290:148–156. https://doi.org/10.1016/j.canlet.2009.08.001.  
**195.** Rathnavelu V., Alitheen N.B., Sohila S., Kanagesan S., and Ramesh R. (2016). Potential Role of Bromelain in Clinical and Therapeutic Applications. Biomedical Reports 2016;5:283–8. https://doi.org/10.3892/br.2016.720.  
**196.** Iram S., Zahera M., Wahid I., Baker A., Raish M., Khan A., Ali N., Ahmad S., and Khan M.S. (2019). Cisplatin bioconjugated enzymatic GNPs amplify the effect of cisplatin with acquiescence. Scientific Reports 9(1):p.13826.  
**197.** Winnick T., Davis A.R., and Greenberg D.M. (1940). PHYSICOCHEMICAL PROPERTIES OF THE PROTEOLYTIC ENZYME FROM THE LATEX OF THE MILKWEED, ASCLEPIAS SPECIOSA TORR. SOME COMPARISONS WITH OTHER PROTEASES : I. CHEMICAL PROPERTIES, ACTIVATION-INHIBITION, pH-ACTIVITY, AND TEMPERATURE-ACTIVITY CURVES. The Journal of General Physiology 1940;23:275–88. https://doi.org/10.1085/jgp.23.3.275.  
**198.** Lowry B., Lee D., and Hébant C. (1980). The Origin of Land Plants: A New Look at an Old Problem. Taxon 29:183–197. https://doi.org/10.2307/1220280.  
**199.** Weng J-K., and Chapple C. (2010). The Origin and Evolution of Lignin Biosynthesis. The New Phytologist 187:273–285. https://doi.org/10.1111/j.1469-8137.2010.03327.x.  
**200.** Stafford H.A. (1991) Flavonoid Evolution: An Enzymic Approach. Plant Physiology 96:680–685. https://doi.org/10.1104/pp.96.3.680.  
**201.** Gould K., and Lister C. (2006). Flavonoid Functions in Plants. Flavonoids: Chemistry, Biochemistry and Applications. pp.397-441.  
**202.** Harborne J., and Simmonds N. (1964). Natural Distribution of the Phenolic Aglycones. In: HARBORNE JB(Ed), editor. Biochemistry of Phenolic Compounds. London: Academic Press; 1964. pp.77–128.  
**203.** Tzin V., and Galili G. (2010). The Biosynthetic Pathways for Shikimate and Aromatic Amino Acids in Arabidopsis Thaliana. The Arabidopsis Book / American Society of Plant Biologists 8: https://doi.org/10.1199/tab.0132.  
**204.** Werner R.A., Rossmann A., Schwarz C., Bacher A., Schmidt H-L., and Eisenreich W. (2004). Biosynthesis of Gallic Acid in Rhus Typhina: Discrimination between Alternative Pathways from Natural Oxygen Isotope Abundance. Phytochemistry 65:2809–2813. https://doi.org/10.1016/j.phytochem.2004.08.020.  
**205.** Muir R.M., Ibáñez A.M., Uratsu S.L., Ingham E.S., Leslie C.A., McGranahan G.H., Batra N., Goyal S., Joseph J., Jemmis E.D., and Dandekar A.M. (2011). Mechanism of gallic acid biosynthesis in bacteria (Escherichia coli) and walnut (Juglans regia). Plant molecular biology 75:555-565. https://doi.org/10.1007/s11103-011-9739-3.  
**206.** Daglia M., Di Lorenzo A., Nabavi S.F., Talas Z.S., and Nabavi S.M. (2014). Polyphenols: Well beyond the antioxidant capacity: gallic Acid and related compounds as neuroprotective agents: You are what you eat! Current Pharmaceutical Biotechnology 15:362–372. https://doi.org/10.2174/138920101504140825120737.  
**207.** Boerjan W., Ralph J., and Baucher M. (2003). Lignin Biosynthesis. Annual Review of Plant Biology 54:519–546. https://doi.org/10.1146/annurev.arplant.54.031902.134938.  
**208.** Lattanzio V. (2013). Phenolic Compounds: Introduction, "Natural Products. Phytochemistry, Botany and Metabolism of Alkaloids, Phenolics and Terpenes." Editors: Kishan Gopal Ramawat, Jean-Michel Merillon, Springer-Verlag Berlin Heidelberg. pp1543-1580.  
**209.** Floudas D., Binder M., Riley R., Barry K., Blanchette R.A., Henrissat B., Martínez A.T., Otillar R., Spatafora J.W., Yadav J.Y., Aerts A., Benoit I., Boyd A., Carlson A., Copeland A., Coutinho P.M., de Vries R.P., Ferreira P., Findley K., Foster B., Gaskell J., Glotzer D., Górecki P., Heitman J., Hesse C., Hori C., Igarashi K., Jurgens J.A., Kallen N., Kersten P., Kohler A., Kües U., Arun Kumar T.K., Kuo A., LaButti K., Larrondo L.F., Lindquist E., Ling A., Lombard V., Lucas S., Lundell T., Martin R., McLaughlin D.J., Morgenstern I., Morin E., Murat C., Nagy L.G., Nolan M., Ohm R.A., Patyshakuliyeva A., Rokas A., Ruiz-Dueñas F.J., Sabat G., Salamov A., Samejima M., Schmutz J., Slot J.C., St John F., Stenlid J., Sun H., Sun S., Syed K., Tsang A., Wiebenga A., Young D., Pisabarro A., Eastwood D.C., Martin F., Cullen D., Grigoriev I.V., and Hibbett D.S. (2012). The Paleozoic Origin of Enzymatic Lignin Decomposition Reconstructed from 31 Fungal Genomes. Science 336(6089):1715–1719. https://doi.org/10.1126/science.1221748.  
**210.** Robinson J.M. (1990). Lignin, Land Plants, and Fungi: Biological Evolution Affecting Phanerozoic Oxygen Balance. Geology 18:607–610. https://doi.org/10.1130/0091-7613(1990)018<0607:LLPAFB>2.3.CO;2.  
**211.** Hibbett D., Blanchette R., Kenrick P., and Mills B. (2016). Climate, Decay, and the Death of the Coal Forests. Current Biology 26:R563–7. https://doi.org/10.1016/j.cub.2016.01.014.  
**212.** DiMichele W.A., Gastaldo R.A., and Pfefferkorn H.W. (2005). Plant biodiversity partitioning in the Late Carboniferous and Early Permian and its implications for ecosystem assembly. Proceedings of the California Academy of Sciences. (Vol. 56, Supplement I, No. 4):32-49.  
**213.** Cleal C.J., and Thomas B.A. (2005). Palaeozoic tropical rainforests and their effect on global climates: is the past the key to the present?. Geobiology 3(1):13-31. **214.**  Haribal M., and Renwick J.A. (1996). Oviposition Stimulants for the Monarch Butterfly: Flavonol Glycosides from Asclepias Curassavica. Phytochemistry 41:139–144. https://doi.org/10.1016/0031-9422(95)00511-0.  
**215.** Haribal M., and Renwick J.A. (1998). Identification and Distribution of Oviposition Stimulants for Monarch Butterflies in Hosts and Nonhosts. Journal of Chemical Ecology 24:891–904. https://doi.org/10.1023/A:1022377618562.  
**216.** Baur R., Haribal M., Renwick J.A.A., and Stabler E. (1998). Contact chemoreception related to host selection and oviposition behaviour in the Monarch butterfly, *Danaus plexippus*. Physiological Entomology 23(1):7-19.  
**217.** Agrawal A.A., Salminen J-P., and Fishbein M. (2009). Phylogenetic Trends in Phenolic Metabolism of Milkweeds (Asclepias): Evidence for Escalation. Evolution 63:663–673. https://doi.org/10.1111/j.1558-5646.2008.00573.x.  
**218.** Staunton J., and Weissman K.J. (2001). Polyketide biosynthesis: a millennium review. Natural Product Reports 18(4):380-416.  
**219.** Austin M.B., and Noel J.P. (2003). The chalcone synthase superfamily of type III polyketide synthases. Natural Product Reports 20(1):79-110.  
**220.** Miyanaga A. (2017). Structure and function of polyketide biosynthetic enzymes: various strategies for production of structurally diverse polyketides. Bioscience Biotechnology and Biochemistry 81(12):2227-2236.  
**221.** Lanz T., Tropf S., Marner F.J., Schröder J., and Schröder G. (1991). The role of cysteines in polyketide synthases. Site-directed mutagenesis of resveratrol and chalcone synthases, two key enzymes in different plant-specific pathways. Journal of Biological Chemistry 266(15):9971-9976.  
**222.** Tropf S., Kärcher B., Schröder G., and Schröder J. (1995). Reaction Mechanisms of Homodimeric Plant Polyketide Synthases (Stilbene and Chalcone Synthase): A SINGLE ACTIVE SITE FOR THE CONDENSING REACTION IS SUFFICIENT FOR SYNTHESIS OF STILBENES, CHALCONES, AND 6′-DEOXYCHALCONES (∗). Journal of Biological Chemistry 270(14):7922-7928.  
**223.** Preisig-Müller R., Gehlert R., Melchior F., Stietz U., and Kindl H. (1997). Plant polyketide synthases leading to stilbenoids have a domain catalyzing malonyl-CoA: CO2 exchange, malonyl-CoA decarboxylation, and covalent enzyme modification and a site for chain lengthening. Biochemistry 36(27):8349-8358.  
**224.** Ferrer J.L., Jez J.M., Bowman M.E., Dixon R.A., and Noel J.P. (1999). Structure of chalcone synthase and the molecular basis of plant polyketide biosynthesis. Nature Structural Biology 6(8):775-784.  
**225.** Jez J.M., and Noel J.P. (2000). Mechanism of chalcone synthase: pKa of the catalytic cysteine and the role of the conserved histidine in a plant polyketide synthase. Journal of Biological Chemistry 275(50):39640-39646.  
**226.** Jez J.M., Austin M.B., Ferrer J.L., Bowman M.E., Schröder J., and Noel J.P. (2000). Structural control of polyketide formation in plant-specific polyketide synthases. Chemistry & Biology 7(12):919-930.  
**227.** Kong J.M., Chia L.S., Goh N.K., Chia T.F., and Brouillard R. (2003). Analysis and biological activities of anthocyanins. Phytochemistry 64(5):923-933.  
**228.** Rice-Evans C.A., Miller N.J., and Paganga G. (1996). Structure-antioxidant activity relationships of flavonoids and phenolic acids. Free Radical Biology and Medicine 20(7):933-956.  
**229.** Wang H., Cao G., and Prior R.L. (1997). Oxygen radical absorbing capacity of anthocyanins. Journal of Agricultural and Food Chemistry 45(2):304-309.  
**230.** Delgado-Vargas F., Jiménez A.R., and Paredes-López O. (2000). Natural pigments: carotenoids, anthocyanins, and betalains—characteristics, biosynthesis, processing, and stability. Critical Reviews in Food Science and Nutrition 40(3):173-289.  
**231.** de Pascual-Teresa S., and Sanchez-Ballesta M.T. (2008). Anthocyanins: from plant to health. Phytochemistry Reviews 7:281-299.  
**232.** Khoo H.E., Azlan A., Tang S.T., and Lim S.M. (2017). Anthocyanidins and anthocyanins: Colored pigments as food, pharmaceutical ingredients, and the potential health benefits. Food & Nutrition Research 61(1):p.1361779.  
**233.** Joseph J.A., Shukitt-Hale B., Denisova N.A., Bielinski D., Martin A., McEwen J.J., and Bickford P.C. (1999). Reversals of age-related declines in neuronal signal transduction, cognitive, and motor behavioral deficits with blueberry, spinach, or strawberry dietary supplementation. Journal of Neuroscience 19(18):8114-8121.  
**234.** Dixon R.A., and Pasinetti G.M. (2010). Flavonoids and isoflavonoids: from plant biology to agriculture and neuroscience. Plant Physiology 154(2):453-457.  
**235.** Baerson S.R., and Rimando A.M. (2007). A Plethora of Polyketides: Structures, Biological Activities and Enzymes. American Chemical Society Symposium Series. In Polyketides: Biosynthesis, Biological Activity and Genetic Engineering, A. Rimando and S. Baerson, eds., American Chemical Society, Washington, DC. pp. 2-14.  
**236.** McLaughlin, J.L. (2008). Paw paw and cancer: annonaceous acetogenins from discovery to commercial products. Journal of Natural Products 71(7):1311-1321.  
**237.** Yasuda M., Wilson D.R., Fugmann S.D., and Moaddel R. (2011). Synthesis and characterization of SIRT6 protein coated magnetic beads: identification of a novel inhibitor of SIRT6 deacetylase from medicinal plant extracts. Analytical Chemistry 83(19):7400-7407.  
**238.**  Rahnasto-Rilla M., Tyni J., Huovinen M., Jarho E., Kulikowicz T., Ravichandran S., A Bohr V., Ferrucci L., Lahtela-Kakkonen M., and Moaddel R. (2018). Natural polyphenols as sirtuin 6 modulators. Scientific Reports 8(1):1-11.  
**239.** Klein M.A., and Denu J.M. (2020). Biological and catalytic functions of sirtuin 6 as targets for small-molecule modulators. Journal of Biological Chemistry 295(32):11021-11041.  
**240.** Wardman P. (1989). Reduction potentials of one‐electron couples involving free radicals in aqueous solution. Journal of Physical and Chemical Reference Data 18(4):1637-1755.  
**241.** Buettner G.R. (1993). The pecking order of free radicals and antioxidants: lipid peroxidation, α-tocopherol, and ascorbate. Archives of Biochemistry and Biophysics 300(2):535-543.  
**242.** Petrou A.L., and Terzidaki A. (2017). A meta-analysis and review examining a possible role for oxidative stress and singlet oxygen in diverse diseases. Biochemical Journal 474(16):2713-2731.  
**243.** Agarwal M.L., Clay M.E., Harvey E.J., Evans H.H., Antunez A.R., and Oleinick N.L. (1991). Photodynamic therapy induces rapid cell death by apoptosis in L5178Y mouse lymphoma cells. Cancer Research 51(21):5993-5996.  
**244.** Kochevar I.E., Lynch M.C., Zhuang S., and Lambert C.R. (2000). Singlet oxygen, but not oxidizing radicals, induces apoptosis in HL-60 cells. Photochemistry and Photobiology 72(4):548-553.  
**245.** Dougherty T.J., Gomer C.J., Henderson B.W., Jori G., Kessel D., Korbelik M., Moan J., and Peng Q. (1998). Photodynamic therapy. JNCI: Journal of the National Cancer Institute 90(12):889-905.  
**246.** Skovsen E., Snyder J.W., Lambert J.D., and Ogilby P.R. (2005). Lifetime and diffusion of singlet oxygen in a cell. The Journal of Physical Chemistry B 109(18):8570-8573.  
**247.** Young A.J. and Lowe G.M. (2001). Antioxidant and pro-oxidant properties of carotenoids. Archives of Biochemistry and Biophysics 385(1):20-27.  
**248.** Panche A.N., Diwan A.D., and Chandra S.R. (2016). Flavonoids: an overview. Journal of Nutritional Science 5:p.e47.  
**249.** Kearns D.R. (1971). Physical and chemical properties of singlet molecular oxygen. Chemical Reviews 71(4):395-427.  
**250.** Mustafa M.G. (1990). Biochemical basis of ozone toxicity. Free Radical Biology and Medicine 9(3):245-265.  
**251.** Wisthaler A., and Weschler C.J. (2010). Reactions of ozone with human skin lipids: sources of carbonyls, dicarbonyls, and hydroxycarbonyls in indoor air. Proceedings of the National Academy of Sciences 107(15):6568-6575.  
**252.** Zannoni N., Lakey P.S., Won Y., Shiraiwa M., Rim D., Weschler C.J., Wang N., Ernle L., Li M., Bekö G., and Wargocki P. (2022). The human oxidation field. Science 377(6610):1071-1077.  
**253.** Koltsakis G.C., and Stamatelos A.M. (1997). Catalytic automotive exhaust after treatment. Progress in Energy and Combustion Science 23(1):1-39.  
**254.** D'Autréaux B., and Toledano M.B. (2007). ROS as signalling molecules: mechanisms that generate specificity in ROS homeostasis. Nature Reviews Molecular Cell Biology 8(10):813-824.  
**255.** De Grey A.D. (2002). HO2 the forgotten radical. DNA and cell biology, 21(4), pp.251-257.  
**256.** Harman D. (1981). The aging process. Proceedings of the National Academy of Sciences 78(11):7124-7128.  
**257.** Rosen D.R., Siddique T., Patterson D., Figlewicz D.A., Sapp P., Hentati A., Donaldson D., Goto J., O'Regan J.P., Deng H.X., and Rahmani, Z., Krizus A., McKenna-Yasek D.,Cayabyab A., Gaston S.M., Berger R., Tanzi R.E., Halperin J.J., Herzfeldt B., Van den Bergh R., Hung W.Y., Bird T., Deng G., Mulder D.W., Smyth C., Laing N.G., Soriano E., Pericak–Vance M.A., Haines J., Rouleau G.A., Gusella J.S., Horvitz H.R., and Brown Jr R.H. (1993). Mutations in Cu/Zn superoxide dismutase gene are associated with familial amyotrophic lateral sclerosis. Nature 362(6415):59-62.  
**258.** Balaban R.S., Nemoto S., and Finkel T. (2005). Mitochondria, oxidants, and aging. Cell 120(4):483-495.  
**259.** Dröge W. (2002). Free radicals in the physiological control of cell function. Physiological Reviews. 82(1):47-95.  
**260.** Hileman E.O., Liu J., Albitar M., Keating M.J., and Huang P. (2004). Intrinsic oxidative stress in cancer cells: a biochemical basis for therapeutic selectivity. Cancer Chemotherapy and Pharmacology 53:209-219.  
**261.** Lind J. (1753). A treatise of the scurvy. In three parts. Containing an inquiry into the nature, causes and cure, of that disease. Together with a critical and chronological view of what has been published on the subject. Edinburgh: Printed by Sands, Murray and Cochran, for A. Kincaid and A. Donaldson.  
**262.** Tröhler U. (2005). Lind and scurvy: 1747 to 1795. Journal of the Royal Society of Medicine 98(11):519-522.  
**263.** Tulchinsky T.H., and Varavikova E.A. (2014). A history of public health. The New Public Health pp.1-42.  
**264.** Allan P.K. (2021). "*Finding the Cure for Scurvy*". url:https://www.usni.org/magazines/naval-history-magazine/2021/february/finding-cure-scurvy  
**265.** Price, C. (2017). "*The Age of Scurvy*". The Science History Institute. url:https://www.sciencehistory.org/distillations/the-age-of-scurvy  
**266.** Szent-Györgyi, Albert. (1928). Observations on the function of peroxidase systems and the chemistry of the adrenal cortex: Description of a new carbohydrate derivative. Biochemical Journal 22(6):1387-1409.  
**267.** Svirbely J.L., and Szent-Györgyi A. (1932). The chemical nature of vitamin C. Biochemical Journal 26(3):865-870.  
**268.** Svirbely J.L., and Szent-Györgyi A. (1933). The chemical nature of vitamin C. Biochemical Journal 27(1):279-285.  
**269.** Traber M.G., and Atkinson J. (2007). Vitamin E, antioxidant and nothing more. Free Radical Biology and Medicine 43(1):4-15.  
**270.** Yin H., Xu L., and Porter N.A. (2011). Free radical lipid peroxidation: mechanisms and analysis. Chemical Reviews 111(10):5944-5972.  
**271.** Niki E. (2014). Role of vitamin E as a lipid-soluble peroxyl radical scavenger: *in vitro* and *in vivo* evidence. Free Radical Biology and Medicine 66:3-12.  
**272.** Koppenol W.H. (1990). Oxyradical reactions: from bond-dissociation energies to reduction potentials. FEBS Letters 264(2):165-167.  
**273.** Wagner B.A., Buettner G.R., and Burns C.P. (1994). Free radical-mediated lipid peroxidation in cells: oxidizability is a function of cell lipid bis-allylic hydrogen content. Biochemistry 33(15):4449-4453.  
**274.** Sunshine H., and Iruela-Arispe M.L. (2017). Membrane lipids and cell signaling. Current Opinion in Lipidology 28(5):408-413.  
**275.** Harayama T., and Shimizu T. (2020). Roles of polyunsaturated fatty acids, from mediators to membranes. Journal of Lipid Research 61(8):1150-1160.  
**276.** Cathcart M.K., McNally A.K., Morel D.W., and Chisolm 3rd G.M. (1989). Superoxide anion participation in human monocyte-mediated oxidation of low-density lipoprotein and conversion of low-density lipoprotein to a cytotoxin. Journal of Immunology 142(6):1963-1969.  
**277.** Diaz M.N., Frei B., Vita J.A., and Keaney Jr J.F. (1997). Antioxidants and atherosclerotic heart disease. New England Journal of Medicine 337(6):408-416.  
**278.** Imai Y., Kuba K., Neely G.G., Yaghubian-Malhami R., Perkmann T., van Loo G., Ermolaeva M., Veldhuizen R., Leung Y.C., Wang H., Liu H, Sun Y., Pasparakis M., Kopf M., Mech C. , Bavari S., Malik Peiris J.S., Slutsky A.S., Akira S., Hultqvist M., Holmdahl R,, Nicholls J., Jiang C., Binder C.J., and Penninger J.M. (2008). Identification of oxidative stress and Toll-like receptor 4 signaling as a key pathway of acute lung injury. Cell 133(2):235-249.  
**279.** da Silva G., Chen C.C., and Bozzelli J.W. (2006). Bond dissociation energy of the phenol OH bond from <i>ab initio</i> calculations. Chemical Physics Letters 424(1-3):42-45.  
**280.** Du J., Cullen J.J., and Buettner G.R. (2012). Ascorbic acid: chemistry, biology and the treatment of cancer. Biochimica et Biophysica Acta (BBA)-Reviews on Cancer 1826(2):443-457.  
**281.** Njus D., Kelley P.M., Tu Y.J., and Schlegel H.B. (2020). Ascorbic acid: The chemistry underlying its antioxidant properties. Free Radical Biology and Medicine 159:37-43.  
**282.** Packer J.E., Slater T., and Willson R.L. (1979). Direct observation of a free radical interaction between vitamin E and vitamin C. Nature 278(5706):737-738.  
**283.** May J.M., Qu Z.C., and Mendiratta S. (1998). Protection and recycling of α-tocopherol in human erythrocytes by intracellular ascorbic acid. Archives of Biochemistry and Biophysics 349(2):281-289.  
**284.** Bruno R.S., Leonard S.W., Atkinson J., Montine T.J., Ramakrishnan R., Bray T.M., and Traber M.G. (2006). Faster plasma vitamin E disappearance in smokers is normalized by vitamin C supplementation. Free Radical Biology and Medicine 40(4):689-697.  



<!------------------------------------------------------------------------->
<!------------------------------------------------------------------------->
<div>
<hr style="border:2px solid gray">

&copy; Jeffrey C Howard. The material contained within this website may be copied, distributed and displayed without alterations for noncommercial purposes only provided that it is accompanied by acknowledgements to the author. All commercial and non-commercial rights are reserved to the author.  

<hr style="border:2px solid gray">
</div>
<!------------------------------------------------------------------------->
<!------------------------------------------------------------------------->

<script src='https://storage.ko-fi.com/cdn/scripts/overlay-widget.js'></script>
<script>
  kofiWidgetOverlay.draw('jch274202227', {
    'type': 'floating-chat',
    'floating-chat.donateButton.text': 'Help Support',
    'floating-chat.donateButton.background-color': '#00b9fe',
    'floating-chat.donateButton.text-color': '#fff'
  });
</script>



















