---
layout: post
title: Reconstruction_Charite_Flow_no_flow
date: '2024-07-30'
categories: Processing, Protocol, data analysis
tags: Flow no flow project
---
# Charite 
### ***Resume of the project.***

In the island of Mo'orea located in French Polynesia, *Pocillopora spp.* are present and conciderate as dominante species around the island (back reef - fore reef) following many event as Crown of Throne, bleaching event (Gonzalo Pérez-Rosales et al. 2021). *Pocillopora spp.* show lot of plasticity depending of the depth, light and courant (Johnston et al. 2017). Identified *Pocillopora spp.* at species level are complicated only by morphology. Molecular work need to be done to detect and identified the species level using mtORF (Johnston et al. 2022). In this experiment we identify 4 differents species *P.verrucosa* (Haplotype 3), *P. meandrina* (Haplotype 1a - 8a), *P. tuahiniensis* (Haplotype 10)(new specie describe by Johnston and Burgess 2023), *P. grandis* (Haplotype 1a) sampled at 2 differents sites conditions; Haapiti **Flow site** (W 149.883782438236 - S 17.5650093638768)and Manava **No flow site** (W 149.807646130636 - S 17.4756927846393). 
Our goal it's to identified the difference and the plasticity the coral make between a site with a hight flow regime compare to a low flow regime condition. For doing that we ran tomography scanning (Scucchia et al. 2023) on our samples at the BeamLine of SESAME in Jordan and BESSY in Germany.    

### Preparation for doing the reconstruction
### Software
- Fiji 
- ImageJ
- NRecon
- Dragonfly 

### Folder preparation   
- Create a new Folder with the name of the samples
- Create a folder for each windows scan we need 
- Create a folder call "FF Before" / "FF_After" and "Radio". FF means "Flat Field". 

### Changing H5 file to Tiff file   
For doing this step is necessary to use Fiji software. 
- Search and select N5 in research bar (in the bottum right).  
- Find and select the raw data file in .h5.  
- After selecting the correct file, clic on it and go to.   
- The next step is to change the file form H5 to TIFF, for that select file -> exchange -> data    
- when this computer as finish to process and show a new window with the scan, go to Fiji panel control -> File -> Save As -> Image Sequence ...    
- Pick the correct direction (clic on Browse).  
- Change the name of the sample and add "_" at the end of the name    
- Save the file in the correct folder.   
- Do the same process for "Data", "Data_dark" and "Data_white"      

### ANKAphase   
For doing this step is necessary to use ImageJ software.
- Go to Plugins -> ANKAphase -> ANKAphase   
- The ANKAphase window will showing up with General settings      
- In general settings, change the *projection images directory* <- it will be the radio data (with the object scan in our case "Pocillopora scan". Change the browse of *flat-field 1 images directory* with the FF beofre, change the browse of *flat-fild 2 images directory* with FF after.  
- After to have clic on *run* check the data result and see if everything looks ok.  

**Now we need to prepare the file for the reconstruction**  ***If needed***   
For doing this step is necessary to use ImageJ software.   
- Select the area we choose to keep.  
- After to have selected the square go to image -> crop 
- Create a folder call *ankaphase crop* to you principal folder.  
- Save the folder of the new crop images in *ankaphase corp* folder   

### Reconstruction phase  
For doing this step is necessary to use NRecon software. 
