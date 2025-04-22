---
layout: post
title: PocID Relative abundance molecular species ID.
date: '2024-10-09'
categories: Processing, Pocillopora, Gel, PCR
tags: PocID RA
---
# Relative abundance *Pocillopora spp.* around the island of Mo'orea. Species identification via mtORF-PocHistone and RFLP.

## Context:
Our study is based on population genetics of *Pocillopora sp.* on the Polynesian islands based on their often misleading and incorrect morphology. We are therefore trying to understand population dynamics by **Haplotype** so that we can correlate our transect data with our term tolerance data from the laboratory (see NoteBook TPC Haplotype).

### **gDNA** extraction with "Quick-DNA 96 Kit / Cat No: [D3012](https://zymoresearch.eu/products/quick-dna-96-kit)  
#### Protocol:   

1. Reagent preparation:
	Add 260ul or 1,040ul **Proteinase K storage Buffer** to reconstitute the lyophilized **Proteinase K**, 5mg (D3001-2-5) or 20mg (D3001-2-20), respectively (final concentration of 20mg/ml). Vortex to dissolve. 

2. gDNA extraction in DNA/RNA shield

	- Add 10ul PK Digestion buffer + 5ul of Proteinase K.   
		For 2 plate in a time --> 2.0ml of PK Digestion Buffer + 1.0ml ProtK 
		
	- Add 400ul og Genomic Lysis Buffer to 100ul of teh sample/shield mixture.   
		For 2 plate in a time --> 400ul x 192 samples = 76.8ml 
	
	- Mix completely by vortexing (with pipette in the plate) 4-5 times then let stand 10 minutes 

	- Transfer the mixture to the wells of a **Silicon-A Plate** on a **Collection Plate**. Centrifuge at 2.500xg for 5 minutes.   

	- Remove the waste in the colelction plate and move to the next step.  

	- Add 200ul of **DNA Pre-Wash Buffer** to each well and. centrifuge at 2,500xg for 5 nminutes,  
		For 2 plate in a time --> 200ul x 192 samples = 38.4ml.   
		
	- Remove the waste in the colelction plate and move to the next step.   

	- Add 300ul **g-DNA Wash Buffer** to each well and centrifuge at 2,500xg for 5 minutes.  
		For 2 plate in a time --> 300ul x 192 samples = 57.6ml.   
		
	- Transfer the **Silicon-A Plate** onto an **Elution plate**. Add 50ul **DNA Elution Buffer** (need to be heat at 70˚C) to each well and incubate during 2 minutes then centrifuge at 2,500xg for 5 minutes. 
		For 2 plate in a time --> 50ul x 192 samples = 9.6ml.  
		
	- Keep the **Silicon-A Plate** in the fridge (4˚C). 

	- Cover the **Elution Plate** and keep it at -20˚C. 

	- Nano drop 3-4 samples on each plate to control de DNA concentration. 

#### **Nano drop** result : 

*20240919* **Plate 16 and 17**. 

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv). 

| Plate  | Sample | Well | ng/ul  | A260/280 | A260/230 |
|--------|--------|------|--------|----------|----------|
| 17     | 1398   | A1   | 17     | 1.72     | 0.85     |
| 17     | 1390   | B1   | 1.1    | 1.6      | 0.16     |
| 16     | 1407   | H12  | 1.5    | 2.75     | 0.56     |
| 16     | 2220   | A1   | .- 0,8 | 0.84     | .-0.06   |
| 16     | 2194   | B1   | .-0.9  | 1.16     | .-0.25   |

After checking we figure it out that we didin't add Elution Buffer but g-DNA Wash buffer. 
Following that we tooked plates out of the freezer and added 50ul of Elution Buffer
Eluted in 50ul of Elution Buffer and mesured on nanodrop. 

| Plate  | Sample | Well | ng/ul  | A260/280 | A260/230 |
|--------|--------|------|--------|----------|----------|
| 16     | 2220   | A1   | 3.4    | 1.97     | 0.89     |
| 16     | 2194   | B1   | 20.8   | 1.88     | 1.83     |
| 16     | 2189   | C1   | 13.6   | 1.9      | 1.96     |
| 17     | 1398   | A1   | 10     | 1.82     | 1.01     |
| 17     | 1390   | B1   | 14.9   | 1.86     | 2.32     |
| 17     | 2163   | C1   | 12.1   | 1.91     | 1.31     |

*20240920* **Plate 18 and 19**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv). 

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0.1    | .-0.14   | 0.18     |
| 18             | 2418   | A1   | 15.6   | 2.11     | 2.3      |
| 18             | 2350   | B1   | 23.8   | 2.05     | 0.33     |
| 18             | 2421   | C1   | 31.2   | 2.03     | 1.64     |
| 19             | 1448   | A1   | 16.9   | 2.1      | 2.16     |
| 19             | 1442   | B1   | 12     | 2.14     | 2.22     |
| 19             | 1418   | C1   | 4.1    | 2.83     | 0.56     |

*20240920* **Plate 20 and 21**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv). 

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0.1    | .-1.64   | 0.58     |
| 20             | 1424   | A1   | 14.3   | 2.08     | 2.05     |
| 20             | 2463   | B1   | 33.2   | 1.97     | 1.46     |
| 20             | 3314   | C1   | 28.1   | 1.94     | 1.58     |
| 21             | 2137   | A1   | 5.6    | 2.11     | 1.04     |
| 21             | 2152   | B1   | 10.4   | 1.97     | 2.22     |
| 21             | 3113   | C1   | 24.4   | 1.97     | 2.02     |

Probability of mixing buble surface between 12C and 12D on plate 20. 

*20240920* **Plate 22 and 23**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv). 

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0.8    | .-12.88  | 2.26     |
| 22             | 2136   | A1   | 18.1   | 1.94     | 1.48     |
| 22             | 3231   | B1   | 39     | 1.95     | 1.89     |
| 22             | 3291   | C1   | 22.8   | 1.98     | 1.64     |
| 23             | 3496   | A1   | 25.8   | 2        | 2.46     |
| 23             | 3620   | B1   | 19     | 1.98     | 1.65     |
| 23             | 2916   | C1   | 37.6   | 1.93     | 2.42     |

*20240921* **Plate 24 and 25**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv). 

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0      | .-0.01   | 0.12     |
| 24             | 3513   | A12  | 61.8   | 1.96     | 2.33     |
| 24             | 3501   | B12  | 34     | 2.02     | 1.75     |
| 24             | 3674   | C12  | 30.8   | 2.01     | 1.76     |
| 25             | 2752   | F12  | 21.8   | 2.05     | 2.45     |
| 25             | 2781   | G12  | 20.1   | 2.07     | 2.26     |
| 25             | 2768   | H12  | 43.4   | 2.01     | 2.27     |

*20240922* **Plate 26 and 27**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv). 

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0.2    | 2.78     | 0.43     |
| 26             | 2715   | A1   | 39     | 1.93     | 1.72     |
| 26             | 2708   | B1   | 35.4   | 1.9      | 0.93     |
| 26             | 2845   | C1   | 32     | 1.95     | 1.55     |
| 27             | 3445   | A12  | 42.9   | 1.92     | 0.84     |
| 27             | 3679   | B12  | 8.9    | 2.11     | 1.83     |
| 27             | 2694   | C12  | 15.9   | 1.98     | 1.4      |

*20240922* **Plate 28 and 29**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv). 

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | .-0.4  | 1.3      | .-5.44   |
| 28             | 2386   | F1   | 33.5   | 1.91     | 1.94     |
| 28             | 2382   | G1   | 38     | 1.93     | 1.9      |
| 28             | 2361   | H1   | 35.9   | 1.92     | 1.88     |
| 29             | 2996   | A1   | 34.1   | 1.95     | 1.6      |
| 29             | 2855   | B1   | 42.1   | 1.9      | 1.09     |
| 29             | 2605   | C1   | 35.2   | 1.95     | 2.14     |

*20240922* **Plate 30 and 31**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv).

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | .-0.1  | 0.27     | .-0.95   |
| 31             | 3385   | A12  | 31.9   | 1.93     | 2.05     |
| 31             | 3364   | B12  | 29.1   | 1.94     | 2.02     |
| 31             | 3431   | C12  | 10.5   | 1.83     | 0.53     |
| 30             | 2665   | F12  | 35.8   | 1.91     | 2.18     |
| 30             | 2991   | G12  | 28.5   | 1.94     | 1.63     |
| 30             | 2500   | H12  | 47.9   | 1.9      | 1.81     |

*20240923* **Plate 32 and 33**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv).

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | .-0.1  | 0.18     | .-0.18   |
| 32             | 430    | A1   | 35.6   | 1.96     | 2.1      |
| 32             | 2085   | B1   | 12.6   | 2.1      | 1.62     |
| 32             | 1975   | C1   | 36.8   | 1.99     | 1.87     |
| 33             | 2004   | A12  | 34.4   | 1.95     | 1.38     |
| 33             | 1914   | B12  | 29.6   | 2        | 1.71     |
| 33             | 1779   | C12  | 19.9   | 2.04     | 2.08     |

*20240923* **Plate 34 and 35**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv).

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0.2    | .-0.45   | 0.88     |
| 34             | 1530   | A1   | 19.7   | 1.97     | 1.68     |
| 34             | 1659   | B1   | 24.7   | 2.02     | 1.87     |
| 34             | 1567   | C1   | 22.6   | 2.02     | 2.07     |
| 35             | 1527   | F12  | 46.5   | 1.92     | 2.11     |
| 35             | 1928   | G12  | 31.1   | 1.94     | 1.63     |
| 35             | 1985   | H12  | 38.9   | 1.95     | 2.19     |

*20240924* **Plate 36 and 37**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv).

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0.1    | .-0.09   | .-0.32   |
| 36             | 1959   | A1   | 62.1   | 1.93     | 2.37     |
| 36             | 1963   | B1   | 16.5   | 2.03     | 2.28     |
| 36             | 2025   | C1   | 23.5   | 1.99     | 2.64     |
| 37             | 931    | A10  | 54.4   | 1.96     | 2.13     |
| 37             | 1218   | A11  | 32.7   | 1.93     | 2.7      |
| 37             | 1075   | A12  | 47.8   | 1.93     | 1.81     |

*20240925* **Plate 38 and 39**.

See plate number for each samples [here](https://github.com/PierrickHarnay/Pocillopora-Lagoon-Abundance/blob/main/Data/POC_ID_RA_list.csv).

| Plate          | Sample | Well | ng/ul  | A260/280 | A260/230 |
|----------------|--------|------|--------|----------|----------|
| Elution buffer | x      | x    | 0.3    | .-0.30   | .-1.36   |
| 38             | 814    | A1   | 31     | 1.99     | 2.13     |
| 38             | 892    | A2   | 45.1   | 1.97     | 1.8      |
| 38             | 799    | A3   | 24.4   | 2.04     | 1.16     |


### **Gel process control of DNA quality**
#### Protocol:

During the process we used differentes size of gel. For this raison we have list bellow all the different way to make the gel at **1.5%**. 

##### Small size of gel: 
-  1.12g of **Agarose** 
-  75ml of **1x TAE Buffer**
-  1µl of **gelgreen**. 

##### Medium size of gel:
-  1.50g of **Agarose** 
-  100ml of **1x TAE Buffer**
-  1µl of **gelgreen**. 

##### Large size of gel:
-  2.25 of **Agarose** 
-  150ml of **1x TAE Buffer**
-  1µl of **gelgreen**. 

On each gel add 4µl of **lader** on one side of the gel. On each gel add 4µl of samples in each well. Run the gel at 100V during 35 minutes.   

#### Gel pictures   
#### *20240411* plate002 gel 001 mtORF after extraction:   
![P02g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P02g1.JPG)  

#### *20240411* plate002 gel 002 mtORF after extraction:  
![P02g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P02g2.JPG)

#### *20240411* plate002 gel 003 mtORF after extraction:  
![P02g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P02g3.JPG)

#### *20250226* plate003 gel 001 mtORF after extraction:  
![P03g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P03g1.JPG)

#### *20250226* plate003 gel 003 mtORF after extraction:  
![P03g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P03g3.JPG)

#### *20250226* plate004 gel 001 mtORF after extraction:  
![P04g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P04g1.JPG)

#### *20250226* plate004 gel 002 mtORF after extraction:  
![P04g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P04g2.JPG)

#### *20250226* plate004 gel 003 mtORF after extraction:  
![P04g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P04g3.JPG)

#### *20250226* plate005 gel 001 mtORF after extraction:  
![P05g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P05g1.JPG)

#### *20250226* plate005 gel 002 mtORF after extraction:  
![P05g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P05g2.JPG)

#### *20250226* plate005 gel 003 mtORF after extraction:  
![P05g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P05g3.JPG)

#### *20250226* plate006 gel 001 mtORF after extraction:  
![P06g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P06g1.JPG)

#### *20250226* plate006 gel 002 mtORF after extraction:  
![P06g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P06g2.JPG)

#### *20250226* plate006 gel 003 mtORF after extraction:  
![P06g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P06g3.JPG)

#### *20250226* plate007 gel 001 mtORF after extraction:  
![P07g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P07g1.JPG)

#### *20250226* plate007 gel 002 mtORF after extraction:  
![P07g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P07g2.JPG)

#### *20250226* plate007 gel 003 mtORF after extraction:  
![P07g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P07g3.JPG)

#### *20250227* plate008 gel 001 mtORF after extraction:  
![P08g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P08g1.JPG)

#### *20250227* plate008 gel 002 mtORF after extraction:  
![P08g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P08g2.JPG)

#### *20250227* plate008 gel 003 mtORF after extraction:  
![P08g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P08g3.JPG)

#### *20250227* plate009 gel 001 mtORF after extraction:  
![P09g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P09g1.JPG)

#### *20250227* plate009 gel 002 mtORF after extraction:  
![P09g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P09g2.JPG)

#### *20250227* plate009 gel 003 mtORF after extraction:  
![P09g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P09g3.JPG)

#### *20241005* plate012 mtORF after extraction:  
![P12.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P12.JPG)

#### *20241005* plate013 mtORF after extraction:  
![P13.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P13.JPG)

#### *20241005* plate014 mtORF after extraction:  
![P14.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P14.JPG)

#### *20241005* plate015 mtORF after extraction:   
![P15.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P15.JPG)

#### *20241005* plate016 mtORF after extraction:  
![P16.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P16.JPG)

#### *2024xxxx* plate017 mtORF after extraction:  
![P17.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P17.JPG)

#### *20241005* plate018 mtORF after extraction:  
![P18.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P18.JPG)

#### *2024xxxx* plate019 mtORF after extraction:  
![P19.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P19.JPG)

#### *2024xxxx* plate020 gel 001 mtORF after extraction:  
![P20g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P20g1.JPG)

#### *2024xxxx* plate020 gel 002 mtORF after extraction:  
![P20g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P20g2.JPG)

#### *2024xxxx* plate020 gel 003 mtORF after extraction:  
![P20g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P20g3.JPG)

#### *2024xxxx* plate021 gel 001 mtORF after extraction:  
![P21g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P21g1.JPG)

#### *2024xxxx* plate021 gel 002 mtORF after extraction:  
![P21g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P21g2.JPG)

#### *2024xxxx* plate021 gel 003 mtORF after extraction:  
![P21g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P21g3.JPG)

#### *20240928* plate022 gel 001 mtORF after extraction:  
![P22g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P22g1.JPG)

#### *20240928* plate022 gel 002 mtORF after extraction:  
![P22g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P22g2.JPG)

#### *20240928* plate022 gel 003 mtORF after extraction:  
![P22g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P22g3.JPG)

#### *20240928* plate023 gel 001 mtORF after extraction:  
![P23g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P23g1.JPG)

#### *20240928* plate023 gel 002 mtORF after extraction:  
![P23g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P23g2.JPG)

#### *20240928* plate023 gel 003 mtORF after extraction:  
![P23g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P23g3.JPG)

#### *20240930* plate024 gel 001 mtORF after extraction:  
![P24g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P24g1.JPG)

#### *20240930* plate024 gel 002 mtORF after extraction:  
![P24g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P24g2.JPG)

#### *20240930* plate024 gel 003 mtORF after extraction:  
![P24g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P24g3.JPG)

#### *20240930* plate025 gel 001 mtORF after extraction:  
![P25g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P25g1.JPG)

#### *20240930* plate025 gel 002 mtORF after extraction:  
![P25g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P25g2.JPG)

#### *20240930* plate025 gel 003 mtORF after extraction:  
![P25g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P25g3.JPG)

#### *20240930* plate026 gel 001 mtORF after extraction:  
![P26g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P26g1.JPG)

#### *20240930* plate026 gel 002 mtORF after extraction:  
![P26g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P26g2.JPG)

#### *20240930* plate026 gel 003 mtORF after extraction:  
![P26g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P26g3.JPG)

#### *20240930* plate027 gel 001 mtORF after extraction:  
![P27g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P27g1.JPG)

#### *20240930* plate027 gel 002 mtORF after extraction:  
![P27g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P27g2.JPG)

#### *20240930* plate027 gel 003 mtORF after extraction:  
![P27g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P27g3.JPG)

#### *20241001* plate028 gel 001 mtORF after extraction:  
![P28g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P28g1.JPG)

#### *20241001* plate028 gel 002 mtORF after extraction:  
![P28g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P28g2.JPG)

#### *20241001* plate028 gel 003 mtORF after extraction:  
![P28g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P28g3.JPG)

#### *20241001* plate029 gel 001 mtORF after extraction:  
![P29g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P29g1.JPG)

#### *20241001* plate029 gel 002 mtORF after extraction:  
![P29g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P29g2.JPG)

#### *20241001* plate029 gel 003 mtORF after extraction:  
![P29g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P29g3.JPG)

#### *20241001* plate030 gel 001 mtORF after extraction:  
![P30g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P30g1.JPG)

#### *20241001* plate030 gel 002 mtORF after extraction:  
![P30g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P30g2.JPG)

#### *20241001* plate030 gel 003 mtORF after extraction:  
![P30g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P30g3.JPG)

#### *20241001* plate031 gel 001 mtORF after extraction:  
![P31g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P31g1.JPG)

#### *20241001* plate031 gel 002 mtORF after extraction:  
![P31g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P31g2.JPG)

#### *20241001* plate032 gel 001 mtORF after extraction:  
![P32g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P32g1.JPG)

#### *20241001* plate032 gel 002 mtORF after extraction:  
![P32g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P32g2.JPG)

#### *20241002* plate033 gel 001 mtORF after extraction:  
![P33g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P33g1.JPG)

#### *20241002* plate033 gel 002 mtORF after extraction:  
![P33g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P33g2.JPG)

#### *20241002* plate033 gel 003 mtORF after extraction:  
![P33g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P33g3.JPG)

#### *20241002* plate034 gel 001 mtORF after extraction:  
![P34g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P34g1.JPG)

#### *20241002* plate034 gel 002 mtORF after extraction:  
![P34g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P34g2.JPG)

#### *20241002* plate034 gel 003 mtORF after extraction:  
![P34g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P34g3.JPG)

#### *20241002* plate035 gel 001 mtORF after extraction:  
![P35g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P35g1.JPG)

#### *20241002* plate035 gel 002 mtORF after extraction:  
![P35g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P35g2.JPG)

#### *20241002* plate036 gel 001 mtORF after extraction:  
![P36g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P36g1.JPG)

#### *20241002* plate036 gel 002 mtORF after extraction:  
![P36g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P36g2.JPG)

#### *20241002* plate036 gel 003 mtORF after extraction:  
![P36g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P36g3.JPG)

#### *20241002* plate037 gel 001 mtORF after extraction:  
![P37g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P37g1.JPG)

#### *20241002* plate037 gel 002 mtORF after extraction:  
![P37g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P37g2.JPG)

#### *20241002* plate037 gel 003 mtORF after extraction:  
![P37g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P37g3.JPG)

#### *20241002* plate038 gel 001 mtORF after extraction:  
![P38g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P38g1.JPG)

#### *20241002* plate038 gel 002 mtORF after extraction:  
![P38g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P38g2.JPG)

#### *20241002* plate038 gel 003 mtORF after extraction:  
![P38g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P38g3.JPG)

#### *20241002* plate039 gel 001 mtORF after extraction:  
![P39g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P39g1.JPG)

#### *20241002* plate039 gel 002 mtORF after extraction:  
![P39g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/P39g2.JPG)

### ZR 96 DNA Clean-up Kit Cat No [D4017 D4018](https://zymoresearch.eu/products/zr-96-dna-clean-up-kit)
#### Protocol:   

1. Reagent preparation: Add 96 ml 100% ethanol (104 ml 95% ethanol) to the 24 ml **DNA Wash Buffer** concentrate. Add 192 ml 100% ethanol (208 ml 95% ethanol) to the 48ml **DNA Wash Buffer** concentrate. 

2. Sample processing: 

- Add 100 µl **DNA Binding Buffer** to PCR sample, Mix, transfer to cullum plate, then add any remaning sample (20µl). 
    
- Centrifuge at **3000g** for **5 minutes**   

- Add 300 µl **Wash buffer** to each well   

- Centrifuge at **3000g** for **5 minutes**    

- Add 300 µl at **Wash buffer**   

- Centrifuge at **3000g** for **5 minutes**    

- Add 40µl nuc free water to each well   

- Transfer silicon plate into an evolution plate   

- Centrifuge **3000g** for **3 minutes**

- Done! Store in freezer   

### Sequence process at URI   

------------------------------------------

### PocHistone and RFLP for species identify as Haplotype 1a (*P. grandis - P. meandrina*): 
#### Protocol:

#### Gel pictures     
#### *20240303* RFLP 001 gel 1:  
![pocHistone001g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone001g1.JPG)

#### *20240303* RFLP 001 gel 2:  
![pocHistone001g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone001g2.JPG)

#### *20240303* RFLP 001 gel 3:  
![pocHistone001g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone001g3.JPG)

#### *2024xxxx* RFLP 002 gel 1:  
![pocHistone002g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone002g1.JPG)

#### *2024xxxx* RFLP 002 gel 2:  
![pocHistone002g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone002g2.JPG)

#### *2024xxxx* RFLP 003 gel 1:  
![pocHistone003g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone003g1.JPG)

#### *2024xxxx* RFLP 003 gel 2:  
![pocHistone003g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone003g2.JPG)

#### *2024xxxx* RFLP 003 gel 3:  
![pocHistone003g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone003g3.JPG)