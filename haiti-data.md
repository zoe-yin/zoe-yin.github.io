---
layout: default
title: Haiti Data
permalink: /haiti-data/
---

# Mw7.2 Nippes, Haiti Earthquake: Sentinel-1 and ALOS-2 Interferometry
## H. Zoe Yin <sup>1</sup>, Xioahua Xu <sup>2</sup>, Jennifer S. Haase <sup>1</sup>, Roby Douilly <sup>3</sup>, David T. Sandwell1 <sup>1</sup>, Bernard Mercier de Lépinay <sup>4</sup>

<sup>1</sup> *Institute for Geophysics and Planetary Physics, University of California, San Diego, CA, USA* <br />
<sup>2</sup> *University of Texas Institute for Geophysics, Austin, TX, USA* <br />
<sup>3</sup> *University of California, Riverside, CA, USA* <br />
<sup>4</sup> *CNRS Université Côte d'Azur, Valbonne, France* <br />

---
[Background](#background)<br />
[Data](#data)<br />

---

The [Mw7.2 Nippes, Haiti](https://earthquake.usgs.gov/earthquakes/eventpage/us6000f65h/executive) earthquake struck on August 14, 2021 (8:29 am local time) on Haiti's southwest peninsula. The earthquake occurred 125 km west of Port-au-Prince at a depth of 10 km with an oblique thrust faulting mechanism. The earthquake occurred along the Enriquillo-Plantain Garden fault (EPGF) zone, about 100 km west of the [Mw7.0 2010 Haiti](https://earthquake.usgs.gov/earthquakes/eventpage/usp000h60h/executive) earthquake. This page provides line-of-sight deformation data from Sentinel-1 and ALOS-2. The InSAR data are processed with open source software [GMTSAR](https://topex.ucsd.edu/gmtsar/) and mapped using Generic Mapping Tools [(GMT)](http://gmt.soest.hawaii.edu). The InSAR phase are filtered with a 300 m Gaussian filter. The line-of-sight data are acquired by merging different swaths' phase and then unwrapped using snaphu. We also include KMZ files for viewing with Google Earth. 

## Data
Two InSAR satellites were operational before the earthquake and continue to collect measurements of line-of-sight (LOS) deformation. The C-band Sentinel-1 satellites, operated by the European Space Agency [(ESA)](http://www.esa.int/ESA), provide a 6-day coverage (ascending and descending tracks) of the earthquake sequence. These data are available on the [Sentinel Data Hub](https://scihub.copernicus.eu/dhus/). The L-band ALOS-2 satellite, operated by the Japanese Aerospace Exploration Agency [(JAXA)](http://global.jaxa.jp/), collected ascending ScanSAR data can be found on the [ALOS-2 User Interface Gateway](https://auig2.jaxa.jp/openam/UI/Login?goto=http%3A%2F%2Fal2mwb01%3A80%2Fips%2Fhome).

This page provides line-of-sight deformation data from Sentinel-1 and ALOS-2. The InSAR data are processed with open source software [GMTSAR](https://topex.ucsd.edu/gmtsar/) and mapped using Generic Mapping Tools [(GMT)](http://gmt.soest.hawaii.edu). The InSAR phase are filtered with a 300 m Gaussian filter. The line-of-sight data are acquired by merging different swaths' phase and then unwrapped using snaphu. We also include KMZ files for viewing with Google Earth. 

<img src="{{site.baseurl}}/assets/img/figures/timeline-fig.png">

*Timeline of all SAR scene acquisitions used in this work with the vertical red dashed line marking the Aug 14 earthquake. Sentinel-1 acquisitions are frequent, with ascending and descending acquisitions less than two weeks before the 2021 earthquake. In contrast, ALOS-2 acquisitions are infrequent with the closest usable ALOS-2 acquisitions prior to the earthquake are more than 6 months before the earthquake. Note the breaks in the horizontal axis in grey which represent large time periods between ALOS-2 acquisitions.*


## Background
The earthquake ruptured ~80 km from Nippes towards the west, in two main slip patches with primarily dip-slip in the east and strike slip in the west (USGS) ([https://earthquake.usgs.gov/earthquakes/eventpage/us6000f65h/finite-fault](https://urldefense.proofpoint.com/v2/url?u=https-3A__earthquake.usgs.gov_earthquakes_eventpage_us6000f65h_finite-2Dfault&d=DwMFaQ&c=-35OiAkTchMrZOngvJPOeA&r=aqhWRwcp7Zur2Pe5RZ58oA&m=ga5VGU7D1xmnLkwLBToQea4rNatv-czby_Ywl-lRCRc&s=a1Xzf_3cWhE1tM_fe-AeWBDfFB0GCCbixIW67GX6lw0&e=)). This pattern is clearly seen in the second interferogram with a large region of uplift in the east (towards the satellite in the LoS) and dominantly strike slip in the west (away from the satellite in the LoS.

The EPGF is part of the system of strike slip and thurst faults that constitute the northeast boundary of the Caribbean tectonic plate. The plate boundary transitions from pure strike slip south of Cuba to subduction in the Antilles. The slip rate along the EPGF fault zone determined from GPS data is 10-11.4 mm/yr of oblique motion (Symithe et al., 2016). The rupture leaves a ~60 km segment of the EPGF unruptured between this and the 2010 Haiti M7.0 earthquake rupture on the Leogane fault (Symithe et al, 2015). Given the time since the historic earthquakes in 1701, 1751 and 1770 on this plate boundary (Manaker et al., 2008), there remains accumulated strain on the unruptured Mirogoane segment to the east of the August 14 event.

<img src="{{site.baseurl}}/assets/img/figures/overview-results-fig.jpg">
*Overview of the southern peninsula of Haiti, highlighting the epicenters of the 2021 M7.2 and 2010 M7.0 earthquakes and major historic earthquakes (red stars). Aftershocks from 2010 on the Léogane -- Trois Baies fault are from [Douilly et al. (2013)](https://pubs.geoscienceworld.org/ssa/bssa/article/103/4/2305/349821/Crustal-Structure-and-Fault-Geometry-of-the-2010). Aftershocks from 2021 are from the [Ayiti-Séismes network](https://ayiti.unice.fr/ayiti-seismes/). Mapped EPGFZ faults (black lines) are from [Saint Fleur et al. (2020)](https://www.sciencedirect.com/science/article/pii/S0040195120300512). The rupture zones do not align with the previously understood segmentation of the Enriquillo Plantain Garden Fault Zone. Instead, the rupture zones highlight a broad zone of strike-slip and secondary thrust features comprising the transpressional plate boundary. Original segmentation into the Macaya-Tiburon Segment (MTS), Clonard-Macaya Segment (CMS), Miragoâne-Clonard Segment (MCS) and Pietonville-Léogane Segment (PVLS) is taken from* [Saint Fleur et al. (2020)](https://www.sciencedirect.com/science/article/pii/S0040195120300512)*. The range of event depths is indicated for 0 km (blue) to 18 km (yellow)*

### Google Earth Project Download

Download a Google Earth project file containing all InSAR pairs included below as layers. Also includes features picked from these pairs and other published resources to contextualize the InSAR data.

[Google Earth project KMZ file](https://drive.google.com/drive/folders/1x2wfHi3W-KjhjVEkIpDQhcUqulbi9Vtm?usp=sharing)


## InSAR Data

|

|

### ALOS-2 Ascending Track 042 (Stripmap): Pair 2021/01/01 - 2021/08/27

*Co & postseismic & secondary fault structures*

 |
|

| *PHASE: [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-08-27/intf_200m-unwrap/phasefilt_ll.grd)

*[![phasefilt_ll](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-08-27/intf_200m-unwrap/ALOS-2_A042_20210101_20210827_phasefilt.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-08-27/intf_200m-unwrap/ALOS-2_A042_20210101_20210827_phasefilt.jpg)\
 | **PHASE GRADIENT: [yphase_mask_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-08-27/intf_200m-unwrap/yphase_mask_ll.grd)

*[![phase-gradient](https://topex.ucsd.edu/haiti_7.2/web/figures/A042-20210101_20210827_yphasegradient.jpg "web/figures/A042-20210101_20210827_yphasegradient.jpg")](https://topex.ucsd.edu/haiti_7.2/web/figures/A042-20210101_20210827_yphasegradient.jpg)*  | **LINE OF SIGHT: [los_ll.grd](https://topex.ucsd.edu/web/swot/ALOS2_A042/2021-01-01_2021-08-27/intf_200m-unwrap/los_ll.grd)**

[![line-of-sight](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-08-27/intf_200m-unwrap/A042-2021-01-01_2021-08-27_LOS.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-08-27/intf_200m-unwrap/A042-2021-01-01_2021-08-27_LOS.jpg)\
** |

 |
|

* * * * *

 |
|

### ALOS-2 Ascending Track 042 (Stripmap): Pair 2021/08/27 - 2021/12/31   

*Postsesismic & secondary fault structures*\
 |
|

| *PHASE: phasefilt_ll.grd

*[![phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-08-27_2021-12-31/intf_200m-unwrap/A042-20210827_20211231_phasefilt_zoom.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-08-27_2021-12-31/intf_200m-unwrap/A042-20210827_20211231_phasefilt_zoom.jpg)\
 | ***PHASE GRADIENT: yphase_mask_ll.grd

*[![phase-gradient](https://topex.ucsd.edu/haiti_7.2/web/figures/A042-20210827_2021231_yphasegradient.jpg "web/swot/ALOS2_A042/2021-08-27_2021-12-31/intf_200m-unwrap/")](https://topex.ucsd.edu/haiti_7.2/web/figures/A042-20210827_2021231_yphasegradient.jpg)**  | **LINE OF SIGHT: [los_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-08-27_2021-12-31/intf_200m-unwrap/los_ll_dtr.grd)**\
**\
![line-of-sight](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-08-27_2021-12-31/intf_200m-unwrap/A042-20210827_20211231_los.jpg)\
** |

 |
|

* * * * *

 |
|

### ALOS-2 Ascending Track 042 (Stripmap): Pair 2021/01/01 - 2021/12/31

*All Co & postseismic (Jan 1 - Dec 31)* |
|

| *PHASE: [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-08-27_2021-12-31/intf_200m-unwrap/phasefilt_ll.grd)

*![phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-12-31/intf_200m-unwrap/ALOS-2_A042_20210101_20211231_phasefilt.jpg)\
 | ***PHASE GRADIENT: [yphase_mask_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/phasegrad/yphase_mask_ll_2021-01-01_2021-12-31.grd)

![phase
                                                          gradient
                                                          (azimuth)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/phasegrad/2021-01-01_2021-12-31.grd_phasegrad.jpg)\
*** | **LINE OF SIGHT: [los_ll_dtr.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-08-27_2021-12-31/intf_200m-unwrap/los_ll_dtr.grd)**\
**\
![line-of-sight](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/2021-01-01_2021-12-31/intf_200m-unwrap/A042-2021-01-01_2021-12-31_los.jpg)\
** |

 |
|\
 |
|

* * * * *

 |
|

### ALOS-2 Ascending Track 042 (Stripmap): Phase gradient stack

The gradient of the phase taken in the azimuth (flight) direction and stacked using all ALOS-2 ascending track pairs between Dec 23, 2020 and Dec 31, 2021 (3 pairs for A042 and 5 pairs for A043)\
 |
|

| *PHASE GRADIENT STACK:* **yphase_mask_ll_stack.grd***

*[![Phase gradient stack](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/phasegrad/ALOS2-A042-A043_yphasegradient.png)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/phasegrad/ALOS2-A042-A043_yphasegradient.png)\
 | *

* |\
**

** |

 |
|

* * * * *

 |
|

### ALOS-2 Ascending Track 043 (Stripmap): 2020/12/23 - 2021/08/18

*Coseismic & surface rupture*\
 |
|

| *PHASE:* [phasefilt_ll.grd ](https://topex.ucsd.edu/haiti_7.2/swot/ALOS2_A043/2020-12-23_2021-08-18/intf_200m-unwrap-v02/phasefilt_ll.grd)

[![phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A043/2020-12-23_2021-08-18/intf_200m-unwrap-v02/A043-2020-12-23_2021-08-18_phasefilt.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A043/2020-12-23_2021-08-18/intf_200m-unwrap-v02/A043-2020-12-23_2021-08-18_phasefilt.jpg)\
 | *PHASE GRADIENT:* *[yphase_mask_ll_2020-12-23_2021-08-18.grd](https://topex.ucsd.edu/haiti_7.2/swot/ALOS2_A043/2020-12-23_2021-08-18/intf_200m-unwrap-v02/yphase_mask_ll_2020-12-23_2021-08-18)

[![phase grad](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A043/phasegrad/2020-12-23_2021-08-18.grd_phasegrad.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A043/phasegrad/2020-12-23_2021-08-18.grd_phasegrad.jpg)\
* | **LINE OF SIGHT:* ***[los_ll.grd](https://topex.ucsd.edu/haiti_7.2/swot/ALOS2_A043/2020-12-23_2021-08-18/intf_200m-unwrap-v02/los_ll.grd)**

[![LOS](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A043/2020-12-23_2021-08-18/intf_200m-unwrap-v02/A043-2020-12-23_2021-08-18_LOS.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A043/2020-12-23_2021-08-18/intf_200m-unwrap-v02/A043-2020-12-23_2021-08-18_LOS.jpg)\
** |

 |
|

* * * * *

 |
|

### ALOS-2 Ascending Track 043 (Stripmap): Phase gradient stack

*The gradient of the phase taken in the azimuth (flight) direction and stacked using all ALOS-2 ascending track pairs between Dec 23, 2020 and Dec 31, 2021 (3 pairs for A042 and 5 pairs for A043)

* |
|

|

*PHASE GRADIENT STACK:* **yphase_mask_ll_stack.grd*

*[![Phase
                                                          gradient
                                                          stack](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/phasegrad/ALOS2-A042-A043_yphasegradient.png)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_A042/phasegrad/ALOS2-A042-A043_yphasegradient.png)\


### ALOS-2 Descending Track 138 (ScanSAR): 2019/12/10 - 2021/08/17

*Coseismic Deformation.*\

| *PHASE:* [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_D138/2019-12-10_2021-08-17/phasefilt_ll.grd)

[![Phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_D138/2019-12-10_2021-08-17/ALOS2-D138_20191210_20210817_phasefilt.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_D138/2019-12-10_2021-08-17/ALOS2-D138_20191210_20210817_phasefilt.jpg)\

**                       PHASE GRADIENT: N/A                                ** | ****LINE OF SIGHT:* ***[los_ll_dtr.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_D138/2019-12-10_2021-08-17/los_ll_dtr.grd)****

[![LOS](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_D138/2019-12-10_2021-08-17/ALOS2-D138_2019-12-10_2021-08-17_los.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS2_D138/2019-12-10_2021-08-17/ALOS2-D138_2019-12-10_2021-08-17_los.jpg)\


### ALOS-1 Ascending Track 138 (FBD): 2010/01/16 - 2010/06/23

*2010 Postseismic Deformation*

| *PHASE:* [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS1_A138/20100116_20100603/phasefilt_ll.grd)

[![phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS1_A138/20100116_20100603/postseismic-ALOS1-2010016_2010154_phasefilt-zoom.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS1_A138/20100116_20100603/postseismic-ALOS1-2010016_2010154_phasefilt-zoom.jpg)

 | ***PHASE GRADIENT:* **[yphase_mask_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS1_A138/20100116_20100603/yphase_mask_ll.grd)

[![Phase gradient](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS1_A138/20100116_20100603/postseismic-ALOS1-2010016_2010154_phasegradient-zoom.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/ALOS1_A138/20100116_20100603/postseismic-ALOS1-2010016_2010154_phasegradient-zoom.jpg)\


### Sentinel-1 Descending track D142: 2021/08/03 - 2021/08/15

*Descending coseismic interferogram*


| *PHASE:* [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210803-20210815/phasefilt_ll.grd)

[![Phase](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210803-20210815/S1-D142_20210803-20210815_phasefilt.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210803-20210815/S1-D142_20210803-20210815_phasefilt.jpg)\


### Sentinel-1 Descending track D142: 2021/08/15 - 2021/08/21

*Post-seismic Interferogram*
**PHASE:* [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210815-20210821/phasefilt_ll.grd)*

*[![Phase](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210815-20210821/S1-D142_20210815-20210821_phasefilt.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210815-20210821/S1-D142_20210815-20210821_phasefilt.jpg)*

### Sentinel-1 Descending track D142: 2021/08/21 - 2021/08/27

*Post-seismic Interferogram*\

**PHASE:* [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210821-20210827/phasefilt_ll.grd)*

*[![Phase](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210821-20210827/S1-D142_20210821-20210827_phasefilt.jpg)](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_D142/20210821-20210827/S1-D142_20210821-20210827_phasefilt.jpg)*

### Sentinel-1 Ascending track A004: 2021/08/05 - 2021/08/17

*Ascending coseismic interferogram*

**PHASE: [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210805-20210817/phasefilt_ll.grd)

**[**![phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210805-20210817/Sentinel-1_A004_20210805_20210817_phasefilt.jpg)**](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210805-20210817/Sentinel-1_A004_20210805_20210817_phasefilt.jpg)

### Sentinel-1 Ascending track A004: 2021/08/17 - 2021/08/23

*Post-seismic Interferogram***\
***PHASE: [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210817-20210823/phasefilt_ll.grd)

**[**![phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210817-20210823/Sentinel-1_A004_20210817_20210823_phasefilt.jpg)**](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210817-20210823/Sentinel-1_A004_20210817_20210823_phasefilt.jpg)*  | *

### Sentinel-1 Ascending track A004: 2021/08/23 - 2021/08/29

*Post-seismic Interferogram*\

****PHASE: [phasefilt_ll.grd](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210823-20210829/phasefilt_ll.grd)****

**[**![phasefilt](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210823-20210829/Sentinel-1_A004_20210823_20210829_phasefilt.jpg)**](https://topex.ucsd.edu/haiti_7.2/web/swot/S1_A004/20210823-20210829/Sentinel-1_A004_20210823_20210829_phasefilt.jpg)* *

## Acknowledgements:
*Rapid InSAR data processing was supported by a National Science Foundation RAPID grant (Grant #2150704). We thank the operators of the Ayiti-Séismes earthquake monitoring network at Bureau des Mines, Faculté des Sciences, Laboratoire URGéo, Université d'état d'Haïti, Ecole Normale Supérieur, and Laboratoire Géoazur for making aftershock locations free and openly available. We thank Sylvert Paul and Francoise Courboulex at GéoAzur, Eric Calais at ENS, and Jeremy Maurer at Missouri University of Science and Technology for helpful discussions related to the earthquake. We thank ESA for the rapid acquisition and distribution of Sentinel-1 data. We thank JAXA for access to ALOS-1 and ALOS-2 data. The development of the GMTSAR software, and specifically the processing chain for Sentinel-1 and ALOS-2, was supported by the National Aeronautics and Space Administration (NASA) and the National Science Foundation through the NASA Earth Surface and Interior program (NNX16AK93G and 80NSSC19K1043), the NSF Office of Advanced Cyberinfrastructure program (OAC-1834807), and the NSF EarthScope program (EAR-1147435, EAR-1424374, EAR-1614875).*