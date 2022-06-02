# Heat Transfer Final Project - Roof Ventilation
[TOC]
###### tags: `Coursework` `Heat Transfer`

## Links
[GitHub](https://github.com/WildfootW/NTU-BIME_Heat-Transfer)
[Final Presentation - Google Slide](https://docs.google.com/presentation/d/10e4b4Bxr102GnMjUtFFRuPeiefu8AC84Gmr4oDF9beA/edit?usp=sharing)

### Online Resource
* [How Roof Ventilation Works](https://youtu.be/DoxcJp_A7gU)
* [Example - Heat Transfer Simulation of Soldering a SMD Microcontroller](https://bencer3283.github.io/docs/heattransfer.pdf)
* [SOLIDWORKS Flow Simulation Add-on Module Benefits - HVAC Part 1](https://www.cati.com/blog/solidworks-flow-simulation-add-on-module-benefits-hvac-part-1/)

## 通風球 Whirlybird

## 冬瓜散熱器
* [運作原理](https://yxnumber0.weebly.com/36939299922140729702.html)
* 冬瓜系列產品有多項專利字號：I570310、I612255、M534210、M538058、M550321、M550385、M544538、M544539、M544540、M551635
    * [專利檢索](https://twpat3.tipo.gov.tw/twpatc/twpatkm)
![](https://i.imgur.com/NYL6mK3.png)
![](https://i.imgur.com/4ekGCpw.png)

## Corrugated Iron House
[這兩天頂樓或鐵皮屋室內溫度?? - Mobile01](https://www.mobile01.com/topicdetail.php?f=335&t=1086084)
| 室內溫度 | 室外溫度 | 鐵皮屋表面溫度 | 有隔熱漆鐵皮屋 |
| ---- | ---- | ------- | ------- |
| 32   | 30   | 50      | 29.6    |
| 35   | 37   |         |         |
| 36.5 | 38   |         |         |
| 36   | 37   |         |         |

![](https://i.imgur.com/InISFe8.png)


## Simulation
### Flow
<iframe width="560" height="315" src="https://www.youtube.com/embed/KfzYUmoMM8o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vr9A2oVy570" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/F-u9n6pPd78" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/TTA0Dd5EYAs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Convection
<iframe width="560" height="315" src="https://www.youtube.com/embed/p9-coiUAJ6M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Radiation
<iframe width="560" height="315" src="https://www.youtube.com/embed/SHswx8BVqYA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

(& Natural Convection)

### Result
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DbNsZPg2mA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Mesh
<iframe width="560" height="315" src="https://www.youtube.com/embed/Gzp4u5S5vo4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Proposal
* [Google Slides Link](https://docs.google.com/document/d/1OJX1ZAdlGaIlymyGFckiPrdlxcDVMiLZkscwnZ3FFMw/edit?usp=sharing)

候選題目
* 懷爐
* 電動車電池散熱
    * http://www.heattransfertechnologies.com/projects/batterycooling.html
    * https://www.youtube.com/watch?v=D_y46bSlZRU&ab_channel=ValeoGroup
* 鐵皮屋散熱
* 紙包雞
* 除濕機
* 壽喜燒
* 全家厚紙板
* 潛水衣論文
* 清邁炸雞
    * https://www.masters.tw/36671/ironhands
* 艾灸
    * https://pubmed.ncbi.nlm.nih.gov/31254681/
* 咖啡濾杯
    * https://www.youtube.com/watch?v=jGpAKTuer-w
    * 不是穩態
   
## Troubleshoot
### Geometry
![](https://i.imgur.com/2A0cRlD.png)
https://hawkridgesys.com/blog/flow-simulation-4-starting-flow-simulation-analysis
<iframe width="560" height="315" src="https://www.youtube.com/embed/BeNu4-VUv48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Step
### Before Adjust
![](https://i.imgur.com/MAr6jUc.jpg)
Temperature too high
due to Computation Domain is too small

![](https://i.imgur.com/iAXR6lx.jpg)

### General Setting (No Vent)
* 6 Windows
* Winds 3 m/s (x direction)
* G = -9.81 (y direction)
* Default Tempature = 30(c)
![](https://i.imgur.com/UHmp0q0.png)
![](https://i.imgur.com/585rcnh.png)

### Whirlybird
![](https://i.imgur.com/KiKoMHC.png)
![](https://i.imgur.com/Hgsg56Q.png)
![](https://i.imgur.com/5mTB9wD.png)
(單獨模擬的 mesh)
![](https://i.imgur.com/dBb3gcB.png)
(compare to the default mesh on the house)

#### Local Mesh (6, 6, 6) 1 Vent
![](https://i.imgur.com/GXj7iEB.png)
![](https://i.imgur.com/i55n5yg.jpg)
![](https://i.imgur.com/Qj6lmAo.png)
(Only Right Top Vent Working)
![](https://i.imgur.com/4j46uog.jpg)
![](https://i.imgur.com/zljvt48.png)
![](https://i.imgur.com/NATakPE.png)

#### Local Mesh (5, 5, 5) 1 Vent
CPU time 	256 s
Total cells 	21582
Fluid cells 	16802
Solid cells 	4780
Fluid cells contacting solids 	4299
![](https://i.imgur.com/1GMOeOi.png)

#### Local Mesh (4, 4, 5) 8 Vent
Create Mesh 9 min
CPU time 	2162 s
Total cells 	111540
Fluid cells 	81604
Solid cells 	29936
Fluid cells contacting solids 	26640
Irregular Cells 	6
Trimmed cells 	36
![](https://i.imgur.com/DvffR9F.png)
![](https://i.imgur.com/tVcg3ht.png)
![](https://i.imgur.com/yU0vhku.jpg)
Don't know why temperature is not symmetry
![](https://i.imgur.com/VSM7Ask.png)
Temperature of wall still too high

#### Local Mesh (4, 4, 5) 1 Vent
![](https://i.imgur.com/UzsCvtw.png)
![](https://i.imgur.com/Y0m8IvU.png)

#### (4, 4, 5) 1 Vent 20m/s wind
![](https://i.imgur.com/BEtYNGO.png)

#### (4, 4, 5) 1 Vent 10m/s wind
![](https://i.imgur.com/sBKdUuB.png)


### 冬瓜
#### Local Mesh (4, 4, 5) 1 Vent
![](https://i.imgur.com/TfeOqaz.png)
![](https://i.imgur.com/8WMtZW0.png)

#### Local Mesh (4, 4, 5) 8 Vent
![](https://i.imgur.com/SCYB4NH.png)


### No Vent (4, 4, 5)
![](https://i.imgur.com/gglZvXX.png)
