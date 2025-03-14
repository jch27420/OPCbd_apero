---
title: "OPC Milkweeds"
subtitle: " "
excerpt: "Milkweeds are remarkable plants! Some are important indicator species of healthy Tallgrass Communities (TGC), while many others serve as important sources of food, fibre and medicine."
date: 2022-10-11
author: "JCH"
draft: false
bibliography: OPCmkwd.bib
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
  name:  iNaturalist
  url: https://www.inaturalist.org/
- icon: door-open
  icon_pack: fas
  name: OPC
  url: http://www.ojibway.ca/index.htm
- icon: door-open
  icon_pack: fas
  name: NatureServe Explorer
  url: https://explorer.natureserve.org/
- icon: door-open
  icon_pack: fas
  name: Cornell Bird Lab
  url: https://www.allaboutbirds.org/
- icon: door-open
  icon_pack: fas
  name: Audubon
  url: https://www.audubon.org/
- icon: door-open
  icon_pack: fas
  name: USDA - Plants
  url: https://plants.usda.gov/home
- icon: door-open
  icon_pack: fas
  name: ITIS
  url: https://www.itis.gov/
- icon: door-open
  icon_pack: fas
  name: US Forest Service - Pollinators
  url: https://www.fs.usda.gov/managing-land/wildflowers/pollinators

---

<style type="text/css">
/* ================== */
/*  Photo/Figures CSS */
/* ================== */
#myDiv44 {
  border: 4px outset red;
  width: 50%;
  padding: 4px;
  margin: auto;
  border-style: groove;
  background-color: ivory1;    
  text-align: center;
}
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 90%;
  }
/* ========================== */
/*         TABLE CSS          */
/* ========================== */
.Table {
  border-collapse: collapse;
  overflow: auto;
  width: 100%;
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
  text-align: center;
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
td:first-child + td {text-align: center;}
td:first-child + td + td.tcell {text-align: center;}
.Table tbody tr {border-bottom: 2px solid #dddddd;}
.Table tbody tr:last-of-type {border-bottom: 2px solid #009879;}

/* =============================== */
/*          CSS for Links          */
/* =============================== */
a.one:link {color: rgb(0, 0, 200);}
a.one:visited {color: rgb(192, 20, 172);}
a.one:hover {color: rgb(255, 20, 100);}

/* ============================== */
/*     CSS for stylizing text     */
/* ============================== */
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
#Blk { font-weight: bold; color: rgb(0, 0, 0); }
#Red { font-weight: bold; color: rgb(255, 10, 20); }
#Red2 { font-weight: bold; color: rgb(255, 50, 50); }
#Dred { font-weight: bold; color: rgb(175, 0, 0); }
#Or { font-weight: bold; color: rgb(255, 140, 0); }
#Or2 { font-weight: bold; color: rgb(245, 180, 0); }
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
#BGr { font-weight: bold; color: rgb(67, 205, 170); }
#Teal { font-weight: bold; color: rgb(60, 180, 180); }
#Teal2 { font-weight: bold; color: rgb(60, 100, 200); }
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
<!--------------------------------------------->
<!------------ FIG 1 - MILKWEEDS  ------------->
<!--------------------------------------------->

<div align="center">

<figure>
<img src="images/OPCMkwd_header_pic.jpg" alt="" width="600px"/>
</figure>

</div>

<!---------------------------------------------->
<!-------- END - FIG 1 - OPC SOIL MAP  --------->
<!---------------------------------------------->
<!-- this is a subheadline -->
<details>
<summary>
<b>TABLE OF CONTENTS</b>
</summary>

1.  <a href="#Mkw">The Allure of Milkweeds</a>
2.  <a href="#Mkw_Pop">OPC Milkweed Population</a>
    - <a href="#MkwdsOnt">Table 1. Milkweeds of Ontario</a>
3.  <a href="#Mkw_Hab">Milkweed Habitat</a>
4.  <a href="#Mkw_Morph">Milkweed Morphology</a>
    - <a href="#Fig_MkwFlower">Fig.1 Milkweed Flower Structure</a>
5.  OPC Milkweeds
    - <a href="#Photo_BM">Butterfly Milkweed</a>
    - <a href="#Photo_PM">Purple Milkweed</a>
    - <a href="#Photo_SwM">Swamp Milkweed</a>
    - <a href="#Photo_CM">Common Milkweed</a>
6.  <a href="#GSrank">Floral Abundance: Global & Regional Rankings</a>
7.  <a href="#Refs">References</a>

</details>
<!---------------------------------------------------->
<!--------- SECTION 1 - ALLURE OF MILKWEEDS  --------->
<!---------------------------------------------------->
<a id="Mkw"></a>

<div align="center">

<h3>
THE ALLURE OF MILKWEEDS
</h3>

</div>

    We have been taught from a very young age to despise weeds, in large part because they compete with more desirable plants for precious nutrients. So it is perhaps no surprise that Milk*weed*, the common name given to plants belonging to the genus *Asclepias*, are also demonized by most people. The so called *weediness* of these plants is due, in large part, to the ability of some **Milkweed** species to colonize road sides and other disturbed areas. However, this characterization is misleading due to the fact that many species of *Asclepias* are important sources of food, fibre and medicine.  
    **First Nations** people have long known that different parts of the **Milkweed** plant can be used for many purposes. For example, the tough inner stem fibres can be simply rubbed together between the hands to make twine or thicker cords. Although most **Milkweeds** are suitable for making cordage, **<a class="one" href="https://explorer.natureserve.org/Taxon/ELEMENT_GLOBAL.2.129944/Asclepias_incarnata" target="_blank" title="Go to NatureServe">Swamp Milkweed</a>** (*Asclepias incarnata*) is apparently preferred due to its very tough fibers. **Milkweeds** are also edible. The young leaves, shoots and stems of **<a class="one" href="https://explorer.natureserve.org/Taxon/ELEMENT_GLOBAL.2.131135/Asclepias_syriaca" target="_blank" title="Go to NatureServe">Common Milkweed</a>** (*Asclepias syriaca*), as well as its flower buds, roots and young pods are all considered quite delicious and nutritious greens when properly prepared. **First Nations** people also knew of the healing properties of **Milkweeds**. For example, many parts of the plant, including its **latex**, were used to treat among other things: **(i)** body aches (e.g. back, chest, stomach); **(ii)** venereal diseases and fungal infections (e.g. *ringworm*); and **(iii)** *dropsy* (i.e. a build up of body fluid, aka *edema*) commonly associated with congestive heart failure.**<sup>[1](#ref-kindscher_medicinal_1992),[2](#ref-moerman_medicinal_1986)</sup>** Today, we now know that steroidal compounds known as <span id="Blue">C</span>ardiac <span id="Blue">G</span>lycosides (<span id="Blue">CG</span>) are the **latex** components responsible for its toxic and medicinal affects on cardiac muscle.**<sup>[3](#ref-cattell_influence_1938),[4](#ref-withering_account_1785)</sup>** Although it is perhaps not too surprising that humans realized long ago the usefulness of these toxins (i.e. poison-tipped arrows, medicine), what is surprising is that insects beat us to it! Recent studies have shown that **Monarch** butterflies can discriminate between *Asclepias* species that produce high and low levels of <span id="Blue">CG</span> apparently as a way to help their offspring deal with deadly (toxin-sensitive) parasites, what scientists have termed *trans-generational* medication.**<sup>[5](#ref-lefevre_evidence_2010)</sup>**  
    **Milkweeds** also provide many other valuable *ecosystem goods* and *services*.**<sup>[6](#ref-daily_introduction_1997)</sup>** For example, the hollow filament-like hairs attached to the seeds, commonly referred to as *coma*, *floss* or simply *silk*, are not only hypoallergenic but apparently warmer than wool and as buoyant as cork. This latter property of the *silk* was put to good use by the Allies during World War II to make life jackets, since the usual material *kapok* (aka: *Java cotton*, from the Kapok tree *Ceiba pentandra*) was in short supply. Today, the warm and hypo-allergenic properties of this *silk* have motivated a few garment manufacturers to use them in the production of linen and to insulate clothing.**<sup>[7](#ref-knudsen_milkweed_1992)</sup>** Ecologically, *Asclepias spp.* serve as important hosts to many types of insects (e.g. **Monarch butterfly**) and produce relatively large volumes of nectar that many pollinating insects and hummingbirds rely on for food.**<sup>[8](#ref-wyatt_ecology_1994)</sup>** Lastly, quite a few passerines like the **<a class="one" href="https://www.allaboutbirds.org/guide/Baltimore_Oriole" target="_blank" title="Go to Cornell Lab">Baltimore Oriole</a>** (*Icterus galbula*), **<a class="one" href="https://www.allaboutbirds.org/guide/American_Goldfinch/" target="_blank" title="Go to Cornell Lab">American Goldfinch</a>** (*Spinus tristis*) and **<a class="one" href="https://www.allaboutbirds.org/guide/Yellow_Warbler" target="_blank" title="Go to Cornell Lab">Yellow Warbler</a>** use the *silk* and fibre to help build their nests.**<sup>[9](#ref-langas_what_2019)</sup>** So, given the wealth of *goods* and *services* **Milkweeds** do provide why not cultivate them?

<div align="center">

<h3>
MILKWEED FAMILY
</h3>

</div>

<!----------------------------------------------------------------------->
<!----------------- SECTION 1 - OPC MILKWEED POPULATION ----------------->
<!----------------------------------------------------------------------->

<a id="Mkw_Pop"></a>**1. <u>MILKWEED POPULATION</u>:** *Asclepias spp.* are a large family (\>70 species) of North American forbs (see **<a class="one" href="https://plants.sc.egov.usda.gov/core/profile?symbol=ASCLE" target="_blank" title="Go to USDA">USDA</a>**). However, only 12 species are native to Ontario (**Table 1.**), and of these only seven have historically been found at <span id="Dred">OPC</span>. Unfortunately one species known as **White Milkweed** is now believed to be provincially <u>extinct</u> (**<a class="one" href="#GSrank">see Species/Ecosystem Rankings</a>**).

<!---------------------------------------------------------------->
<!------------------------- TABLE 1: Milkweed sp.----------------->
<!---------------------------------------------------------------->
<a class="OntMkwd"></a>
<table class="Table">
<thead>
<tr>
<th class="f18">
<span id="Blk">Genus Species</span>
</th>
<th class="f18">
<span id="Blk">Common Name</span>
</th>
<th class="f18">
<span id="Blk">S,G RANKS</span>
</th>
<th class="f18">
<span id="Blk">MEDICAL</span>
</th>
</tr>
</thead>
<tbody>
<tr>
<td>
<i>Asclepias exaltata</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/125386-Asclepias-exaltata" target="_blank" title="Go to iNaturalist">Poke milkweed</a></b>
</td>
<td>
S4,G5
</td>
<td>
yes
</td>
</tr>
<tr>
<td>
<i>Asclepias hirtella</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/127690-Asclepias-hirtella" target="_blank" title="Go to iNaturalist">Tall green milkweed</a></b>
</td>
<td>
<span id="Red">S1</span>,G5
</td>
<td>
</td>
</tr>
<tr>
<td>
<i>Asclepias incarnata</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/125381-Asclepias-incarnata" target="_blank" title="Go to iNaturalist">Swamp Milkweed</a></b>
</td>
<td>
S5,G5T5
</td>
<td>
yes
</td>
</tr>
<tr>
<td>
<i>Asclepias purpurascens</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/125380-Asclepias-purpurascens" target="_blank" title="Go to iNaturalist">Purple Milkweed</a></b>
</td>
<td>
<span id="Red">S1</span>,G4G5
</td>
<td>
</td>
</tr>
<tr>
<td>
<i>Asclepias quadrifolia</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/129548-Asclepias-quadrifolia" target="_blank" title="Go to iNaturalist">Fourleaf Milkweed</a></b>
</td>
<td>
<span id="Red">S1</span>,G5
</td>
<td>
yes
</td>
</tr>
<tr>
<td>
<i>Asclepias sullivantii</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/158761-Asclepias-sullivantii" target="_blank" title="Go to iNaturalist">Prairie Milkweed</a></b>
</td>
<td>
<span id="Dred">S2</span>,G5
</td>
<td>
</td>
</tr>
<tr>
<td>
<i>Asclepias syriaca</i>
</td>
<td>
<b><a class="one" href="https://www.inaturalist.org/taxa/47911-Asclepias-syriaca" target="_blank" title="Go to iNaturalist">Common Milkweed</a></b>
</td>
<td>
S5,G5
</td>
<td>
yes
</td>
</tr>
<tr>
<td>
<i>Asclepias tuberosa</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/47912-Asclepias-tuberosa" target="_blank" title="Go to iNaturalist">Butterfly Milkweed</a></b>
</td>
<td>
S4,G5
</td>
<td>
yes
</td>
</tr>
<tr>
<td>
<i>Asclepias verticillata</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/125379-Asclepias-verticillata" target="_blank" title="Go to iNaturalist">Whorled Milkweed</a></b>
</td>
<td>
S4,G5
</td>
<td>
yes
</td>
</tr>
<tr>
<td>
<i>Asclepias variegata</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/127691-Asclepias-variegata" target="_blank" title="Go to iNaturalist">White Milkweed</a></b>
</td>
<td>
<span id="Red">SX</span>,G5
</td>
<td>
</td>
</tr>
<tr>
<td>
<i>Asclepias viridiflora</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/158763-Asclepias-viridiflora" target="_blank" title="Go to iNaturalist">Green Milkweed</a></b>
</td>
<td>
<span id="Dred">S2</span>,G5
</td>
<td>
</td>
</tr>
<tr>
<td>
<i>Asclepias ovalifolia</i>
</td>
<td>
<b><a class="one" href="https://inaturalist.ca/taxa/47905-Asclepias-ovalifolia" target="_blank" title="Go to iNaturalist">Oval Leaf Milkweed</a></b>
</td>
<td>
<span id="Dred">S2</span>,<span id="Blue">G3</span>G5
</td>
<td>
</td>
</tr>
</tbody>
</table>
<!---------------------------------------------------------------->
<!------------------- SECTION 2: MILKWEED HABITAT----------------->
<!---------------------------------------------------------------->

<a id="Mkw_Hab"></a>**2. <u>HABITAT</u>:** **Milkweeds** are herbaceous perennial plants that can be found in a wide variety of habitats, ranging from roadside ditches and swamps to deserts, prairies and forests. Some species, notably *A. syriaca*, readily colonize disturbed areas such as abandoned fields and roadsides. (Consult **<a class="one" href="https://plants.sc.egov.usda.gov/core/profile?symbol=ASCLE)" target="_blank" title="Go to USDA">USDA</a>**, or **<a class="one" href="https://www.itis.gov/" target="_blank" title="Go to ITIS">ITIS</a>** for species specific habitats).

<!------------------------------------------------------------->
<!---------- MILKWEED FAMILY SECTION 3: PLANT MORPH ----------->
<!------------------------------------------------------------->

<a id="Mkw_Morph"></a>**3. <u>MILKWEED MORPHOLOGY</u>:** As their name suggests **Milkweeds** are known for their sticky, often *creamy white* (but can be yellow, orange or clear) **latex** that is exuded in response to tissue damage. Closer examination of **latex** shows that it is unlike plant **sap** or **resin** in a number of ways. Firstly, **sap** is an aqueous solution that is transported by the vasculature (xylem and phloem) of the plant, while **resins** are a fat-soluble mixture of largely volatile <span id="Dred">Terpenoids</span> and <span id="Dred">Phenolics</span> found within *inter*cellular spaces, or ducts.**<sup>[10](#ref-langenheim_plant_2003)</sup>** By contrast, **latex** is produced and stored (under pressure) in *living cells* known as **lactifers**.**<sup>[11](#ref-pickard_laticifers_2008),[12](#ref-castelblanque_multiple_2017)</sup>** These elongated and branching cells form *unique* tubular networks throughout most of the plant (i.e. independent of the vascular bundles). The **latex** stored in these **lactifers** is an <u>emulsion</u> that contains microscopic particles of **<a class="one" href="https://pubchem.ncbi.nlm.nih.gov/compound/6557" target="_blank" title="Go to PubChem">polyisoprene</a>**, which is commonly known as natural rubber.**<sup>[11](#ref-pickard_laticifers_2008)–[13](#ref-ramos_laticifers_2019)</sup>**

There are other **latex** compounds, besides *natural rubber*, that make the plant inedible to most animals.**<sup>[13](#ref-ramos_laticifers_2019)–[15](#ref-dobler_convergent_2015)</sup>** Some of the more well known components of **latex** include <span id="Blue">C</span>ardiac <span id="Blue">G</span>lycosides (<span id="Blue">CG</span>), digestive <span id="Dred">Proteases</span> and <span id="Dred">Phenolics</span>. Many herbivores like the larval stage of the Monarch butterfly (*Danaus plexoppus*) are *obligate* feeders of **Milkweeds**. In fact, there are over 100 insect species that feed exclusively on **Milkweed** as a form of chemical defence against predators.**<sup>[15](#ref-dobler_convergent_2015)</sup>** In addition to the characteristic sticky **latex**, *Asclepias spp.* have unique flowers and *pod* like fruits.**<sup>[7](#ref-knudsen_milkweed_1992)</sup>** The former have very complex structures that are in someways comparable to orchids (i.e. pollen), while the latter are packed with *silky* haired seeds that are both buoyant in water and adapted for wind dispersal (**Fig. 1**).

<!---------------------------------------------------------------------------->
<!-------------------- FIG 1 - MILKWEED FLOWER STRUCTURE --------------------->
<!---------------------------------------------------------------------------->

<a id="Fig_MkwFlower"></a>

<div align="center">

<figure>

<img src="images/Fig1_MlkwdFlower.jpg" alt="" width="800px"/>

</figure>

</div>

**Figure 1: Milkweed Flower Structure**. **(A)** The **pollinarium** is a *winged* or “*wishbone*” shaped structure that contains two discrete sacs of pollen, or **pollinium**, that are joined to a central disc-like **corpusculum** via the <u>arms</u> of the **translator**. **(B)** This cartoon shows an overhead view of the shape and position of the flower elements, including the <i>coronal</i> **hood** and **horn** (nectar reservoir) and the position of the **corpusculum** in relation to the much larger **gynostegium** (<sup>☆</sup>fused female **stigma** and male **anther**). **(C)** This picture of Purple Milkweed flowers shows some of its floral elements, including 5 backward pointing (reflected) petals that make up the **corolla**.
<br>

**Milkweed** flowers are arranged in either <u>flat topped</u> or round clusters called *umbels* (i.e. latin “*umbella*”: *a sunshade, parasol or umbrella*). Individual flowers have two distinct parts, a lower <u>*corolla*</u> and upper <u>*corona*</u> (**Fig. 1**). The lower *corolla* is made up of 5 backward-pointing (usually) petals, while the upper nectar containing *corona* is composed (usually) of 5 pairs of <u>*hoods*</u> and <u>*horns*</u>. The *hoods* extend from the base of the *stamens* and house a horn like appendage (nectar reservoir) that arches over top of a central *gem* like *gynostegium* (fused female *stigma* and male *anthers*). This unusual flower structure results in an equally unusual pollination mechanism. Like orchids, the pollen of **Milkweed** is packaged into discrete units called <u>*pollinia*</u>. They are part of *wishbone* like structure called a <u>*pollinarium*</u> that contains a pair of *pollinium*, a <u>*translator*</u> and <u>*corpusculum*</u>.**<sup>[8](#ref-wyatt_ecology_1994)</sup>** The *pollinia* are connected to the *corpusculum*, a small disc-like gland at the base of the *wishbone*, via the forking *arms* of the *translator*. Visually, the *corpusculum* (apex of the *pollinarium*) sits atop a narrow opening (<u>*alar fissure*</u>) into the <u>*stigmatic chamber*</u>, which houses the *pollinarium* (**Fig. 1**). When the leg of a feeding insect slips between the *hoods* and comes into contact with the *corpusculum* it can free the *pollinia* and carry it to other **Milkweed** plants. Given the arduous nature of the **<a class="one" href="https://www.fs.usda.gov/wildflowers/pollinators/importance.shtml" target="_blank" title="Go to USDA">pollination</a>** process, only relatively large insects are capable of carrying out this task.

<hr style="border:2px solid gray">
<!----------------------------------------------------------------->
<!-------------------- PHOTOS OF MILKWEED sp. --------------------->
<!----------------------------------------------------------------->

    The following Milkweed photos currently do not include two other resident species (i.e. Prairie<sup><span id="Dred">S2</span></sup>, Tall Green<sup><span id="Red">S1</span></sup>). These plants are difficult to find owing to their imperilled status (i.e. work in progress). Nevertheless, these four species are some of the most interesting, beautiful and ecologically important forbs found at <span id="Dred">OPC</span>.

<a id="Photo_BM"></a>
**1. BUTTERFLY MILKWEED (**<i>Asclepias tuberosa L.</i>**):** **S4**, **G5**

<figure>

<img src="images/OrMkwd_v2pics.jpg" alt="" width="800px"/>

</figure>

**Figure 2.** This beautiful **Milkweed** is noted for its flat-top umbels of small orange flowers, typical <i>hood</i> and <i>horn</i> corona structure, hairy stems and alternatively arranged leaves. As the name of this plant implies it attracts many types of butterflies, such as Hairstreaks, Monarchs and Great Spangled Fritillaries.<br>

**POPULATION & HABITAT:** **<a class="one" href="https://explorer.natureserve.org/Taxon/ELEMENT_GLOBAL.2.129775/Asclepias_tuberosa">Butterfly Milkweed</a>** (*aka* **Orange Milkweed**) is one of the few native orange wildflowers, making it relatively easy to spot when it blooms (mid to late June) in areas containing open sandy soils. Its a relatively common plant at **<span id="Dred">OPC</span>** where it grows singly or in small clusters. This forb is only found in Ontario and Quebec (rare) within Canada. Unfortunately in Ontario populations of *A. tuberosa* are under threat by the loss and fragmentation of habitat (i.e. prairie and savannas) and the suppression of regenerative surface fires. It is also found in many other parts of eastern North America, but its status varies from region to region. In fact in many American states its status appears to be largely unknown.**<sup>[16](#ref-stevens_plant_2006)–[18](#ref-usda_plants_2024)</sup>**

**ECOLOGICAL & MEDICINAL PROPERTIES:** *A. tuberosa* is an important <u>indicator species</u> of healthy prairie habitats with reported medicinal properties (**Note:** the genus, *Asclepias*, refers to the Greek god of medicine *Asklepios*). **First Nations People** were known to chew the plant root as a cure for pleurisy and other pulmonary ailments, as well as make tea to treat diarrhea and stomach ailments. From an evolutionary perspective, the flat top *umbel* arrangement of the flowers provides a convenient resting platform for pollinating insects to feed on its nectar. This is just one co-evolutionary strategy that plants have adapted to promote insect pollination.**<sup>[16](#ref-stevens_plant_2006)–[18](#ref-usda_plants_2024)</sup>**

<hr style="border:2px solid gray">

<a id="Photo_PM"></a>
**2. PURPLE MILKWEED (**<i>Asclepias purpurascens L.</i>**):** <span id="Red">S1</span>, **G4G5**

<figure>

<img src="images/PurMkwd_v2pics.jpg" alt="" width="800px"/>

</figure>

**Figure 3.** As the flowers of the **Purple Milkweed** mature they develop a deeper purple colour. Note how the difference in colour and shape of the two umbels in the right picture (i.e. one on the right has more loosely arranged, deeper coloured flowers).<br>

**POPULATION & HABITAT:** **<a class="one" href="https://explorer.natureserve.org/Taxon/ELEMENT_GLOBAL.2.145205/Asclepias_purpurascens">Purple Milkweed</a>** is a native perennial forb of eastern North America and considered a key <u>indicator species</u> for healthy Oak savannas. Although its habitat requirements are not particularly restrictive they seem to prefer the partly shaded areas of Oak savannas at **<span id="Dred">OPC</span>** where it grows singly or in very low numbers. In Ontario its status is critically imperiled (<span id="Red">S1</span>). In many other parts of its range its status is either vulnerable (<span id="Blue">S3</span>), imperiled (<span id="Dred">S2</span>), critically imperiled (<span id="Red">S1</span>) or simply unknown. There are only a few eastern states where its population appears to be secure. Obviously it would benefit greatly from further protective measures (i.e. habitat restoration).**<sup>[17](#ref-natureserve_natureserve_2024),[18](#ref-usda_plants_2024)</sup>**

**ECOLOGICAL & MEDICINAL PROPERTIES:** Similar to other **Milkweeds**, *A. purpurascens* attracts many type of pollinator species, including (among others) bees, butterflies and hummingbirds. They have a common flower structure (i.e. *corolla* - 5 reflected petals, *corona* - 5 pairs of hoods and curved horns) and like many other *Asclepias spp.* produce a white latex that contains toxic **<span id="Blue">CG</span>**.**<sup>[17](#ref-natureserve_natureserve_2024),[18](#ref-usda_plants_2024)</sup>**

<hr style="border:2px solid gray">

<a id="Photo_SwM"></a>
**3. SWAMP MILKWEED (**<i>Asclepias incarnata</i>**):** **S5**, **G5T5**

<figure>

<img src="images/SwMkwd_v2pics.jpg" alt="" width="800px"/>

</figure>

**Figure 4.** This cluster of <i>A. incarnata</i> plants were found (as one would expect from its name) growing next to a creek flowing into a small pond at Ojibway Park.<br>

**POPULATION & HABITAT:** **<a class="one" href="https://explorer.natureserve.org/Taxon/ELEMENT_GLOBAL.2.129944/Asclepias_incarnata">Swamp Milkweed</a>** (*aka* Pleurisy Root) like other species in this family, is a native perennial forb that is found in may parts of North America. As its name implies this *Ascelpias* species prefers moist habitats (e.g. wet meadows, marshes, the banks of rivers and streams).**<sup>[17](#ref-natureserve_natureserve_2024)–[19](#ref-kirk_plant_2006)</sup>**

**ECOLOGICAL & MEDICINAL PROPERTIES:** *A. incarnata* is thought to be the preferred food of the Monarch butterfly (*Danaus plexippus*) caterpillar. It is also an important source of nectar for many pollinators, including hummingbirds. The young shoots and seed pods, as well as the flower buds are all edible. Extracts of the root and other plant parts have been used as an emetic (i.e. induce vomiting), diuretic (i.e. promote urination) and a anti-helminth (i.e. purge parasitic worms). It is also commonly referred to as Pleurisy Root for its use in the treatment of lung problems. As mentioned previously, it is the preferred *Asclepias* species for making cordage due to its very tough stem fibres.**<sup>[17](#ref-natureserve_natureserve_2024)–[19](#ref-kirk_plant_2006)</sup>**

<hr style="border:2px solid gray">

<a id="Photo_CM"></a>
**4. COMMON MILKWEED (**<i>Asclepias syriaca</i>**):** **S5**, **G5**

<figure>

<img src="images/ComMkwd_v2pics.jpg" alt="" width="800px"/>

</figure>

**Figure 5.** The red and black colour pattern of the **Milkweed beetle** (<i>Tetraopes tetrophthalmus</i>) seen on the right advertises to potential predators that it is not good to eat (i.e. <i>aposematic</i> coloration). These insects dine on the leaves and roots of this specific **Milkweeds** species and store the toxic <span id="Blue">CG</span> in their tissues to ward off predators.<br>

**POPULATION & HABITAT:** *Asclepias syriaca* is a native perennial forb that is common to eastern North America, but a rare inhabitant of the Midwest. It is known to colonize disturbed areas, like roadsides, but can also be found in open fields and pastures.**<sup>[17](#ref-natureserve_natureserve_2024),[18](#ref-usda_plants_2024),[20](#ref-stevens_plant_2006-1)</sup>**

**ECOLOGICAL & MEDICINAL PROPERTIES:** This **Milkweed** species is a food source for many insects and animals. Like other *Asclepias spp.* its nectar attracts many insect species, as well as hummingbirds. Moreover, many insects such as **Monarch butterfly** caterpillars and the **Red Milkweed beetle** (*Tetraopes tetrophthalmus*) are *Asclepias spp.* specialists. As mentioned previously the young stems, flower buds and seed pods of **Milkweeds** are all edible when properly prepared.**<sup>[17](#ref-natureserve_natureserve_2024),[18](#ref-usda_plants_2024),[20](#ref-stevens_plant_2006-1)</sup>**

<hr style="border:2px solid gray">
<a id="GSrank"></a>

<div align="center">

<h3>
GLOBAL & REGIONAL RANKINGS
</h3>

</div>

**GRANKS** (**G**, global rankings) and **SRANKS** (**S**, State/Province rankings) provide designations for floral and ecosystem abundance. They are assigned and maintained by several conservation agencies. The following general rankings are from **<a class="one" href="https://explorer.natureserve.org/AboutTheData/DataTypes/ConservationStatusCategories">NatureServe</a>**:  
<span id="Red">GX: Presumed Extinct/Collapsed</span>: **Species** <u>presumed extinct</u>, not located despite intensive searches and virtually no likelihood of rediscovery. **Ecosystem** <u>presumed collapsed</u> throughout its range, due to loss of key dominant and characteristic taxa and/or elimination of the sites and ecological processes on which the type depends.  
<span id="Red">GH - Possibly Extinct/Collapsed</span>: **Species** or **Ecosystem** is known from only historical occurrences, but still some hope of rediscovery. Examples of evidence include (1) that a species has not been documented in approximately 20-40 years in human-dominated landscapes despite some searching and/or some evidence of significant habitat loss or degradation; (2) that a species or ecosystem has been searched for unsuccessfully, but not thoroughly enough to presume that it is extinct or collapsed throughout its range.  
<span id="Red">G1 - Critically Imperiled</span>: At very high risk of extinction or collapse due to very restricted range, very few populations or occurrences, very steep declines, very severe threats, or other factors.  
<span id="Dred">G2 - Imperilled</span>: At high risk of extinction or collapse due to restricted range, few populations or occurrences, steep declines, severe threats, or other factors.  
<span id="Blue">G3 - Vulnerable</span>: At moderate risk of extinction or collapse due to a fairly restricted range, relatively few populations or occurrences, recent and widespread declines, threats, or other factors.  
**G4 - Apparently Secure**: At fairly low risk of extinction or collapse due to an extensive range and or many populations or occurrences, but with possible cause for some concern as a result of local recent declines, threats, or other factors.  
**G5 - Secure**: At very low risk or extinction or collapse due to a very extensive range, abundant populations or occurrences, and little to no concern from declines or threats.

**GRANK**s and **SRANK**s may also include other designations, notably: **GU** (uncertain global ranking); **G?** (tentative ranking); **Q** (questionable taxonomic status of the species, subspecies, or variety); **T** (rank applies to a subspecies or variety); and **HYB** (hybrid of 2 species); **SH** (plant historically occurred in Ontario, but has not been recorded in the last 20 years); **SR** (plant has been reported without persuasive documentation); **SU** (species has no SRANK value and therefore of uncertain status); **SX** (species apparently extirpated from Ontario with little likelihood of rediscovery); **SE** (species is exotic, not native to Ontario); **?** (some uncertainty about an assigned rank). Rank ranges (e.g. **S1S2**) indicate the uncertain nature of the species rank (i.e. either **S1** or **S2**).

**MNR RISK STATUS:** This code is assigned by the Ontario Ministry of Natural Resources (**OMNR**) and is based on recommendations by the Committee on the Status of Species at Risk in Ontario. The designated categories are as follows:  
<span id="Red">END</span>**:** Any indigenous species that is threatened with immediate extinction throughout all or a significant portion of its Ontario range.  
<span id="Red">THR</span>**:** Any indigenous species that is experiencing a definite non-cyclical decline throughout all or a major portion of its Ontario range.  
<span id="Red">VUL</span>**:** Any indigenous species that has relatively stable populations, and/or that occurs sporadically, or in a very restricted area of Ontario, or is at the fringe of its range.

**COSEWIC:** Risk codes developed by the Committee on the Status of Endangered Wildlife in Canada include:  
<span id="Red">END</span>**:** Any indigenous flora that is threatened with imminent extinction throughout all or a significant portion of its Canadian range.  
<span id="Red">EXP</span>**:** Any indigenous flora that no longer exists in the wild in Canada but can occur elsewhere.  
<span id="Red">THR</span>**:** Any indigenous flora that is likely to become endangered in Canada if the factors affecting its vulnerability are not reversed.  
<span id="Red">VUL</span>**:** Any indigenous flora that is particularly at risk because of low or declining numbers, occurrence at the fringe of its range or in restricted areas, or for some other reason, but is not yet threatened.

------------------------------------------------------------------------

<hr style="border:2px solid gray">
<!--------------------------------------------------------------------->

© Jeffrey C Howard. The material contained within this website may be copied, distributed and displayed without alterations for noncommercial purposes only provided that it is accompanied by acknowledgements to the author. All commercial and non-commercial rights are reserved to the author.  
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

<div id="ref-kindscher_medicinal_1992" class="csl-entry">

<span class="csl-left-margin">1 </span><span class="csl-right-inline">Kindscher Kelly. *[Medicinal Wild Plants of the Prairie: An Ethnobotanical Guide](https:////catalog.hathitrust.org/Record/002604100)*. Lawrence: University Press of Kansas; 1992.</span>

</div>

<div id="ref-moerman_medicinal_1986" class="csl-entry">

<span class="csl-left-margin">2 </span><span class="csl-right-inline">Moerman DE. *[Medicinal Plants of Native America](https://trove.nla.gov.au/version/14948128)*. Ann Arbor : Museum of Anthropology, University of Michigan; 1986.</span>

</div>

<div id="ref-cattell_influence_1938" class="csl-entry">

<span class="csl-left-margin">3 </span><span class="csl-right-inline">Cattell M, Gold H. [The Influence of Digitalis Glucosides on the Force of Contraction of Mammalian Cardiac Muscle](http://jpet.aspetjournals.org/content/62/1/116). *Journal of Pharmacology and Experimental Therapeutics* 1938;**62**:116–25.</span>

</div>

<div id="ref-withering_account_1785" class="csl-entry">

<span class="csl-left-margin">4 </span><span class="csl-right-inline">Withering W. *[An Account of the Foxglove and some of its Medical UsesWith Practical Remarks on Dropsy and Other Diseases](http://www.gutenberg.org/ebooks/24886)*. 1785.</span>

</div>

<div id="ref-lefevre_evidence_2010" class="csl-entry">

<span class="csl-left-margin">5 </span><span class="csl-right-inline">Lefèvre T, Oliver L, Hunter MD, De Roode JC. Evidence for trans-generational medication in nature. *Ecology Letters* 2010;**13**:1485–93. <https://doi.org/10.1111/j.1461-0248.2010.01537.x>.</span>

</div>

<div id="ref-daily_introduction_1997" class="csl-entry">

<span class="csl-left-margin">6 </span><span class="csl-right-inline">Daily GC. Introduction: What are ecosystem services. *Nature’s services: Societal dependence on natural ecosystems*. 1997.</span>

</div>

<div id="ref-knudsen_milkweed_1992" class="csl-entry">

<span class="csl-left-margin">7 </span><span class="csl-right-inline">Knudsen HD, Sayler RY. Milkweed: The worth of a weed. *The Yearbook of Agriculture (USA) New Crops, New Uses, New Markets: Industrial and Commercial Products from US Agriculture Office of Publishing and Visual Communication* 1992:118–23.</span>

</div>

<div id="ref-wyatt_ecology_1994" class="csl-entry">

<span class="csl-left-margin">8 </span><span class="csl-right-inline">Wyatt R, Broyles SB. Ecology and Evolution of Reproduction in Milkweeds. *Annual Review of Ecology and Systematics* 1994;**25**:423–41. <https://doi.org/10.1146/annurev.es.25.110194.002231>.</span>

</div>

<div id="ref-langas_what_2019" class="csl-entry">

<span class="csl-left-margin">9 </span><span class="csl-right-inline">Langas A. [What Nesting Materials Are Safe for Birds?](https://www.audubon.org/news/what-nesting-materials-are-safe-birds) *Audubon Magazine* 2019.</span>

</div>

<div id="ref-langenheim_plant_2003" class="csl-entry">

<span class="csl-left-margin">10 </span><span class="csl-right-inline">Langenheim J. *Plant Resins: Chemistry, Evolution, Ecology and Ethnobotany.* Portland, Oregon: Timber Press; 2003.</span>

</div>

<div id="ref-pickard_laticifers_2008" class="csl-entry">

<span class="csl-left-margin">11 </span><span class="csl-right-inline">Pickard WF. Laticifers and Secretory Ducts: Two Other Tube Systems in Plants. *The New Phytologist* 2008;**177**:877–88. <https://doi.org/10.1111/j.1469-8137.2007.02323.x>.</span>

</div>

<div id="ref-castelblanque_multiple_2017" class="csl-entry">

<span class="csl-left-margin">12 </span><span class="csl-right-inline">Castelblanque L, Balaguer B, Martí C, Rodríguez JJ, Orozco M, Vera P. Multiple Facets of Laticifer Cells. *Plant Signaling & Behavior* 2017;**12**: <https://doi.org/10.1080/15592324.2017.1300743>.</span>

</div>

<div id="ref-ramos_laticifers_2019" class="csl-entry">

<span class="csl-left-margin">13 </span><span class="csl-right-inline">Ramos MV, Demarco D, Costa Souza IC da, Freitas CDT de. Laticifers, Latex, and Their Role in Plant Defense. *Trends in Plant Science* 2019;**24**:553–67. <https://doi.org/10.1016/j.tplants.2019.03.006>.</span>

</div>

<div id="ref-agrawal_latex_2009" class="csl-entry">

<span class="csl-left-margin">14 </span><span class="csl-right-inline">Agrawal AA, Konno K. Latex: A Model for Understanding Mechanisms, Ecology, and Evolution of Plant Defense against Herbivory. *Annu Rev Ecol Evol Syst* 2009;**40**:311–31.</span>

</div>

<div id="ref-dobler_convergent_2015" class="csl-entry">

<span class="csl-left-margin">15 </span><span class="csl-right-inline">Dobler S, Petschenka G, Wagschal V, Flacht L. Convergent Adaptive Evolution – How Insects Master the Challenge of Cardiac Glycoside-Containing Host Plants. *Entomologia Experimentalis Et Applicata* 2015;**157**:30–9. <https://doi.org/10.1111/eea.12340>.</span>

</div>

<div id="ref-stevens_plant_2006" class="csl-entry">

<span class="csl-left-margin">16 </span><span class="csl-right-inline">Stevens M. Plant fact sheet for Butterfly Milkweed (Asclepias tuberosa). 2006.</span>

</div>

<div id="ref-natureserve_natureserve_2024" class="csl-entry">

<span class="csl-left-margin">17 </span><span class="csl-right-inline">NatureServe. [NatureServe Network Biodiversity Location Data accessed through NatureServe Explorer \[web application\]. NatureServe, Arlington, Virginia.](https://explorer.natureserve.org/) *NatureServe* 2024.</span>

</div>

<div id="ref-usda_plants_2024" class="csl-entry">

<span class="csl-left-margin">18 </span><span class="csl-right-inline">USDA. [The PLANTS Database](http://plants.usda.gov). *The PLANTS Database* 2024.</span>

</div>

<div id="ref-kirk_plant_2006" class="csl-entry">

<span class="csl-left-margin">19 </span><span class="csl-right-inline">Kirk S, Belt S. Plant fact sheet for Swamp Milkweed (Asclepias incarnata). 2006.</span>

</div>

<div id="ref-stevens_plant_2006-1" class="csl-entry">

<span class="csl-left-margin">20 </span><span class="csl-right-inline">Stevens M. Plant fact sheet for Common Milkweed (Asclepias syriaca). 2006.</span>

</div>

</div>
