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

#### Layer use for mtORF   
![QuickLoadpurple_mtORF.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/QuickLoadpurple_mtORF.JPG)  

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
The protocol used comes from Hollie Putnam's LabNotebook and is available [here](https://hputnam.github.io/Putnam_Lab_Notebook/Pocillopora_PocHistone_PCR_RFLP/)

#### Layer use for RFLP incubation   
![QuickLoadpurple_RFLP.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/QuickLoadpurple_RFLP.JPG) 

#### Gel pictures     
#### *20240303* PocHistone RFLP 001 gel 1:  
![pocHistone001g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone001g1.JPG)

#### *20240303* PocHistone RFLP 001 gel 2:  
![pocHistone001g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone001g2.JPG)

#### *20240303* PocHistone RFLP 001 gel 3:  
![pocHistone001g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone001g3.JPG)

#### *2024xxxx* PocHistone RFLP 002 gel 1:  
![pocHistone002g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone002g1.JPG)

#### *2024xxxx* PocHistone RFLP 002 gel 2:  
![pocHistone002g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone002g2.JPG)

#### *2024xxxx* PocHistone RFLP 003 gel 1:  
![pocHistone003g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone003g1.JPG)

#### *2024xxxx* PocHistone RFLP 003 gel 2:  
![pocHistone003g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone003g2.JPG)

#### *2024xxxx* PocHistone RFLP 003 gel 3:  
![pocHistone003g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone003g3.JPG)

#### *20250804* PocHistone RFLP 005 gel 1:
![pocHistone005g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone005g1.JPG)

#### *20250804* PocHistone RFLP 005 gel 2:
![pocHistone005g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone005g2.JPG)

#### *20250804* PocHistone RFLP 005 gel 3:
![pocHistone005g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone005g3.JPG)

#### *20250817* PocHistone 007 gel 1:
![PocHistone_007_g1_20250817.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_007_g1_20250817.JPG)

#### *20250817* PocHistone 007 gel 2:
![PocHistone_007_g2_20250817.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_007_g2_20250817.JPG)

#### *20250817* PocHistone 007 gel 3:
![PocHistone_007_g3_20250817.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_007_g3_20250817.JPG)

#### *20250817* PocHistone RFLP 007 gel 1:
![pocHistone007g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone007g1.JPG)

#### *20250817* PocHistone RFLP 007 gel 2:
![pocHistone007g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone007g2.JPG)

#### *20250817* PocHistone RFLP 007 gel 3:
![pocHistone007g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone007g3.JPG)

#### *20250819* PocHistone 006 gel 1:
![PocHistone_006_g1_20250819.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_006_g1_20250819.JPG)

#### *20250819* PocHistone 006 gel 2:
![PocHistone_006_g2_20250819.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_006_g2_20250819.JPG)

#### *20250819* PocHistone 006 gel 3:
![PocHistone_006_g3_20250819.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_006_g3_20250819.JPG)

#### *20250820* PocHistone RFLP 006 gel 1:
![pocHistone007g1.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone006g1_20250820.JPG)

#### *20250820* PocHistone RFLP 006 gel 2:
![pocHistone007g2.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone006g2_20250820.JPG)

#### *20250820* PocHistone RFLP 006 gel 3:
![pocHistone007g3.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/pocHistone006g3_20250820.JPG)

#### *20250820* PocHistone 005 gel 1:
![PocHistone_005_g1_20250820.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_005_g1_20250820.JPG)

#### *20250820* PocHistone 005 gel 2:
![PocHistone_005_g2_20250820.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_005_g2_20250820.JPG)

#### *20250820* PocHistone 005 gel 3:
![PocHistone_005_g3_20250820.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_005_g3_20250820.JPG)

#### *20250821* PocHistone RFLP 005 gel 1:
![PocHistone_RFLP_005_g1_20250821.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_005_g1_20250821.JPG)

#### *20250821* PocHistone RFLP 005 gel 2:
![PocHistone_RFLP_005_g2_20250821.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_005_g2_20250821.JPG)

#### *20250821* PocHistone RFLP 005 gel 3:
![PocHistone_RFLP_005_g3_20250821.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_005_g3_20250821.JPG)

#### *20250821* PocHistone 009 gel 1:
![PocHistone_009_g1_20250821.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_009_g1_20250821.JPG)

#### *20250821* PocHistone 009 gel 2:
![PocHistone_009_g2_20250821.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_009_g2_20250821.JPG)

#### *20250821* PocHistone 009 gel 3:
![PocHistone_009_g3_20250821.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_009_g3_20250821.JPG)

#### *20250822* PocHistone RFLP 009 gel 1:
![PocHistone_RFLP_009_g1_20250822.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_009_g1_20250822.JPG)

#### *20250822* PocHistone RFLP 009 gel 2:
![PocHistone_RFLP_009_g2_20250822.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_009_g2_20250822.JPG)

#### *20250822* PocHistone RFLP 009 gel 3:
![PocHistone_RFLP_009_g3_20250822.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_009_g3_20250822.JPG)

#### *20250823* PocHistone 010 gel 1:
![PocHistone_010_g1_20250823.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_010_g1_20250823.JPG)

#### *20250823* PocHistone 010 gel 2:
![PocHistone_010_g2_20250823.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_010_g2_20250823.JPG)

#### *20250823* PocHistone 010 gel 3:
![PocHistone_010_g3_20250823.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_010_g3_20250823.JPG)

#### *20250823* PocHistone RFLP 010 gel 1:
![PocHistone_RFLP_010_g1_20250823.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_010_g1_20250823.JPG)

#### *20250823* PocHistone RFLP 010 gel 2:
![PocHistone_RFLP_010_g2_20250823.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_010_g2_20250823.JPG)

#### *20250823* PocHistone RFLP 010 gel 3:
![PocHistone_RFLP_010_g3_20250823.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_RFLP_010_g3_20250823.JPG)

#### *20250827* PocHistone 004 gel 1:
![PocHistone_004_g1_20250827.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_004_g1_20250827.JPG)

#### *20250827* PocHistone 004 gel 2:
![PocHistone_004_g2_20250827.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_004_g2_20250827.JPG)

#### *20250827* PocHistone 004 gel 3:
![PocHistone_004_g3_20250827.JPG](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/PocHistone_004_g3_20250827.JPG)

#### *20250827* PocHistone RFLP 004 gel 1:
![](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/)

#### *20250827* PocHistone RFLP 004 gel 2:
![](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/)

#### *20250827* PocHistone RFLP 004 gel 3:
![](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/)   

### Resume of PocHistone RFLP *Haplotype 1a* gel:   
  
| *P.   meandrina* | *P. grandis* | *Did not work* |
|----------------|------------|--------------|
| 433            | 456        | 549          |
| 675            | 601        |          |
| 451            | 607        | 3872         |
| 431            | 550        | 3919         |
| 652            | 458        | 3729         |
| 602            | 410        | 3751         |
| 442            | 559        | 3789         |
| 461            | 422        | 1836         |
| 441            | 557        | 1840         |
| 418            | 726        |       -      |
| 597            | 559        |       -      |
| 440            | 683        |       -      |
| 429            | 689        |       -      |
| 603            | 670        |       -      |
| 605            | 3559       |       -      |
| 439            | 3549       |       -      |
| 400            | 667        |       -      |
| 427            | 3735       |       -      |
| 573            | 3613       |       -      |
| 575            | 3536       |       -      |
| 426            | 1447       |       -      |
| 606            | 3531       |       -      |
| 556            | 3621       |       -      |
| 528            | 3732       |       -      |
| 479            | 3535       |       -      |
| 448            | 3549       |       -      |
| 412            | 3559       |       -      |
| 424            | 3613       |       -      |
| 411            | 3709       |       -      |
| 449            | 3787       |       -      |
| 434            | 3793       |       -      |
| 592            | 3949       |       -      |
| 445            | 3680       |       -      |
| 604            | 3641       |       -      |
| 614            | 3692       |       -      |
| 726            | 3735       |       -      |
| 3617           | 3736       |       -      |
| 2550           | 3879       |       -      |
| 676            | 3757       |       -      |
| 3724           | 3777       |       -      |
| 3707           | 3782       |       -      |
| 668            | 3807       |       -      |
| 3532           | 3812       |       -      |
| 596            | 3895       |       -      |
| 685            | 1693       |       -      |
| 680            | 1704       |       -      |
| 725            | 1705       |       -      |
| 3723           | 1706       |       -      |
| 723            | 1709       |       -      |
| 3615           | 1710       |       -      |
| 3726           | 1656       |       -      |
| 721            | 1657       |       -      |
| 3710           | 1660       |       -      |
| 3686           | 1668       |       -      |
| 3592           | 1672       |       -      |
| 3629           | 1684       |       -      |
| 535            | 1590       |       -      |
| 703            | 1592       |       -      |
| 3552           | 1629       |       -      |
| 3627           | 1648       |       -      |
| 3602           | 1358     |       -      |
| 702            | 1355     |       -      |
| 666            | 1399     |       -      |
| 3610           | 1404     |       -      |
| 684            | 1435     |       -      |
| 2189           | 1436     |       -      |
| 2185           | 1440     |       -      |
| 2205           | 1446     |       -      |
| 2186           | 1489     |       -      |
| 2213           | 1510     |       -      |
| 2192           | 1511     |       -      |
| 2184           | 1521     |       -      |
| 1423           | 1534     |       -      |
| 3537           | 1535     |       -      |
| 3553           | 1557     |       -      |
| 3558           | 988     |       -      |
| 3622           | 994     |       -      |
| 3626           | 1034     |       -      |
| 3628           | 1051     |       -      |
| 3706           | 1057     |       -      |
| 3713           | 1067     |       -      |
| 3719           | 1078     |       -      |
| 3728           | 1084     |       -      |
| 3732           | 1109     |       -      |
| 3685           | 1115     |       -      |
| 3703           | 1163     |       -      |
| 3759           | 1165     |       -      |
| 3769           | 1214     |       -      |
| 3843           | 1223     |       -      |
| 3871           | 1297     |       -      |
| 3881           | 1318     |       -      |
| 3522           | 1079     |       -      |
| 3550           | 1355     |       -      |
| 3552           | 1358     |       -      |
| 3592           | 1399     |       -      |
| 3602           | 1404     |       -      |
| 3610           | 1435     |       -      |
| 3615           | 1436     |       -      |
| 3617           | 1440     |       -      |
| 3627           | 1446     |       -      |
| 3629           | 1489     |       -      |
| 3707           | 1510     |       -      |
| 3710           | 1511     |       -      |
| 3724           | 1521     |       -      |
| 3726           | 1534     |       -      |
| 3544           | 1535     |       -      |
| 3545           | 1557     |       -      |
| 3548           | 1727     |       -      |
| 3595           | 1728     |       -      |
| 3600           | 1755     |       -      |
| 3624           | 1757     |       -      |
| 3633           | 1758     |       -      |
| 3635           | 1781     |       -      |
| 3643           | 1791     |       -      |
| 3711           | 1812     |       -      |
| 3720           | 1818     |       -      |
| 3691           | 1832     |       -      |
| 3696           | 1851     |       -      |
| 3699           | 1862     |       -      |
| 3733           | 1864 P32 D11     |       -      |
| 3734           | 1865     |       -      |
| 3742           | 1902     |       -      |
| 3747           | 1937     |       -      |
| 3751           | 1976     |       -      |
| 3755           | 1991     |       -      |
| 3758           | 1995     |       -      |
| 3764           | 1999     |       -      |
| 3770           | 2001     |       -      |
| 3818           | 2073     |       -      |
| 3839           | 2101     |       -      |
| 3850           | 2120     |       -      |
| 3856           |      -     |       -      |
| 3860           |      -     |       -      |
| 3862           |      -     |       -      |
| 3874           |      -     |       -      |
| 3884           |      -     |       -      |
| 3808           |      -     |       -      |
| 3809           |      -     |       -      |
| 3818           |      -     |       -      |
| 3827           |      -     |       -      |
| 3890           |      -     |       -      |
| 3903           |      -     |       -      |
| 3904           |      -     |       -      |
| 3908           |      -     |       -      |
| 3914           |      -     |       -      |
| 3915           |      -     |       -      |
| 3918           |      -     |       -      |
| 3942           |      -     |       -      |
| 3591           |      -     |       -      |
| 3601           |      -     |       -      |
| 3609           |      -     |       -      |
| 3715           |      -     |       -      |
| 3686           |      -     |       -      |
| 3688           |      -     |       -      |
| 3698           |      -     |       -      |
| 3700           |      -     |       -      |
| 3701           |      -     |       -      |
| 3737           |      -     |       -      |
| 3744           |      -     |       -      |
| 3745           |      -     |       -      |
| 3746           |      -     |       -      |
| 3750           |      -     |       -      |
| 3761           |      -     |       -      |
| 3765           |      -     |       -      |
| 3767           |      -     |       -      |
| 3772           |      -     |       -      |
| 3833           |      -     |       -      |
| 3836           |      -     |       -      |
| 3846           |      -     |       -      |
| 3848           |      -     |       -      |
| 3852           |      -     |       -      |
| 3863           |      -     |       -      |
| 3864           |      -     |       -      |
| 3865           |      -     |       -      |
| 3869           |      -     |       -      |
| 3873           |      -     |       -      |
| 3877           |      -     |       -      |
| 3885           |      -     |       -      |
| 3739           |      -     |       -      |
| 3741           |      -     |       -      |
| 3743           |      -     |       -      |
| 3766           |      -     |       -      |
| 3771           |      -     |       -      |
| 3834           |      -     |       -      |
| 3835           |      -     |       -      |
| 3837           |      -     |       -      |
| 3841           |      -     |       -      |
| 3847           |      -     |       -      |
| 3854           |      -     |       -      |
| 3855           |      -     |       -      |
| 3859           |      -     |       -      |
| 3866           |      -     |       -      |
| 3887           |      -     |       -      |
| 3889           |      -     |       -      |
| 3774           |      -     |       -      |
| 3776           |      -     |       -      |
| 3783           |      -     |       -      |
| 3784           |      -     |       -      |
| 3785           |      -     |       -      |
| 3786           |      -     |       -      |
| 3788           |      -     |       -      |
| 3795           |      -     |       -      |
| 3797           |      -     |       -      |
| 3798           |      -     |       -      |
| 3800           |      -     |       -      |
| 3803           |      -     |       -      |
| 3806           |      -     |       -      |
| 3811           |      -     |       -      |
| 3816           |      -     |       -      |
| 3817           |      -     |       -      |
| 3823           |      -     |       -      |
| 3824           |      -     |       -      |
| 3829           |      -     |       -      |
| 3830           |      -     |       -      |
| 3897           |      -     |       -      |
| 3912           |      -     |       -      |
| 3913           |      -     |       -      |
| 3917           |      -     |       -      |
| 3934           |      -     |       -      |
| 3935           |      -     |       -      |
| 3937           |      -     |       -      |
| 3934           |      -     |       -      |
| 3935           |      -     |       -      |
| 3937           |      -     |       -      |
| 3938           |      -     |       -      |
| 3943           |      -     |       -      |
| 3945           |      -     |       -      |
| 3789           |      -     |       -      |
| 3804           |      -     |       -      |
| 1561           |      -     |       -      |
| 1563           |      -     |       -      |
| 1565           |      -     |       -      |
| 1567           |      -     |       -      |
| 1569           |      -     |       -      |
| 1570           |      -     |       -      |
| 1572           |      -     |       -      |
| 1573           |      -     |       -      |
| 1575           |      -     |       -      |
| 1577           |      -     |       -      |
| 1580           |      -     |       -      |
| 1581           |      -     |       -      |
| 1583           |      -     |       -      |
| 1584           |      -     |       -      |
| 1587           |      -     |       -      |
| 1593           |      -     |       -      |
| 1598           |      -     |       -      |
| 1599           |      -     |       -      |
| 1606           |      -     |       -      |
| 1607           |      -     |       -      |
| 1608           |      -     |       -      |
| 1610           |      -     |       -      |
| 1612           |      -     |       -      |
| 1618           |      -     |       -      |
| 1620           |      -     |       -      |
| 1621           |      -     |       -      |
| 1624           |      -     |       -      |
| 1626           |      -     |       -      |
| 1627           |      -     |       -      |
| 1628           |      -     |       -      |
| 1635           |      -     |       -      |
| 1636           |      -     |       -      |
| 1638           |      -     |       -      |
| 1641           |      -     |       -      |
| 1643           |      -     |       -      |
| 1644           |      -     |       -      |
| 1645           |      -     |       -      |
| 1647           |      -     |       -      |
| 1648 S2T1           |      -     |       -      |
| 1649           |      -     |       -      |
| 1650           |      -     |       -      |
| 1651           |      -     |       -      |
| 1653           |      -     |       -      |
| 1654           |      -     |       -      |
| 1655           |      -     |       -      |
| 1658           |      -     |       -      |
| 1659           |      -     |       -      |
| 1661           |      -     |       -      |
| 1662           |      -     |       -      |
| 1663           |      -     |       -      |
| 1666           |      -     |       -      |
| 1671           |      -     |       -      |
| 1673           |      -     |       -      |
| 1675           |      -     |       -      |
| 1680           |      -     |       -      |
| 1685           |      -     |       -      |
| 1686           |      -     |       -      |
| 1689           |      -     |       -      |
| 1691           |      -     |       -      |
| 1700           |      -     |       -      |
| 1704           |      -     |       -      |
| 1705           |      -     |       -      |
| 1711           |      -     |       -      |
| 1348           |      -     |       -      |
| 1353           |      -     |       -      |
| 1356               |      -     |       -      |
| 1379               |      -     |       -      |
| 1372               |      -     |       -      |
| 1379               |      -     |       -      |
| 1380               |      -     |       -      |
| 1385               |      -     |       -      |
| 1386               |      -     |       -      |
| 1391               |      -     |       -      |
| 1394               |      -     |       -      |
| 1396               |      -     |       -      |
| 1397               |      -     |       -      |
| 1398               |      -     |       -      |
| 1401               |      -     |       -      |
| 1402               |      -     |       -      |
| 1405               |      -     |       -      |
| 1406               |      -     |       -      |
| 1411               |      -     |       -      |
| 1419               |      -     |       -      |
| 1420               |      -     |       -      |
| 1421               |      -     |       -      |
| 1424               |      -     |       -      |
| 1425               |      -     |       -      |
| 1426               |      -     |       -      |
| 1427               |      -     |       -      |
| 1428               |      -     |       -      |
| 1430               |      -     |       -      |
| 1432               |      -     |       -      |
| 1442               |      -     |       -      |
| 1443               |      -     |       -      |
| 1445               |      -     |       -      |
| 1446               |      -     |       -      |
| 1453               |      -     |       -      |
| 1457               |      -     |       -      |
| 1458               |      -     |       -      |
| 1460               |      -     |       -      |
| 1464               |      -     |       -      |
| 1465               |      -     |       -      |
| 1468               |      -     |       -      |
| 1469               |      -     |       -      |
| 1470               |      -     |       -      |
| 1471               |      -     |       -      |
| 1472               |      -     |       -      |
| 1473               |      -     |       -      |
| 1475               |      -     |       -      |
| 1478               |      -     |       -      |
| 1479               |      -     |       -      |
| 1480               |      -     |       -      |
| 1481               |      -     |       -      |
| 1486               |      -     |       -      |
| 1490               |      -     |       -      |
| 1492               |      -     |       -      |
| 1495               |      -     |       -      |
| 1496               |      -     |       -      |
| 1497               |      -     |       -      |
| 1498               |      -     |       -      |
| 1499               |      -     |       -      |
| 1501               |      -     |       -      |
| 1502               |      -     |       -      |
| 1504               |      -     |       -      |
| 1506               |      -     |       -      |
| 1507               |      -     |       -      |
| 1508               |      -     |       -      |
| 1515               |      -     |       -      |
| 1522               |      -     |       -      |
| 1526               |      -     |       -      |
| 1528               |      -     |       -      |
| 1529               |      -     |       -      |
| 1530               |      -     |       -      |
| 1532               |      -     |       -      |
| 1533               |      -     |       -      |
| 1534               |      -     |       -      |
| 1537               |      -     |       -      |
| 1539               |      -     |       -      |
| 1540               |      -     |       -      |
| 1542               |      -     |       -      |
| 1545               |      -     |       -      |
| 1549               |      -     |       -      |
| 1551               |      -     |       -      |
| 1553               |      -     |       -      |
| 1556               |      -     |       -      |
| 977                |      -     |       -      |
| 978                |      -     |       -      |
| 984                |      -     |       -      |
| 987                |      -     |       -      |
| 991                |      -     |       -      |
| 995                |      -     |       -      |
| 996                |      -     |       -      |
| 997                |      -     |       -      |
| 1000               |      -     |       -      |
| 1002               |      -     |       -      |
| 1003               |      -     |       -      |
| 1004               |      -     |       -      |
| 1006               |      -     |       -      |
| 1008               |      -     |       -      |
| 1010               |      -     |       -      |
| 1012               |      -     |       -      |
| 1015               |      -     |       -      |
| 1016               |      -     |       -      |
| 1022               |      -     |       -      |
| 1025               |      -     |       -      |
| 1026               |      -     |       -      |
| 1029               |      -     |       -      |
| 1030               |      -     |       -      |
| 1037               |      -     |       -      |
| 1039               |      -     |       -      |
| 1044               |      -     |       -      |
| 1047               |      -     |       -      |
| 1052               |      -     |       -      |
| 1054               |      -     |       -      |
| 1060               |      -     |       -      |
| 1061               |      -     |       -      |
| 1062               |      -     |       -      |
| 1063               |      -     |       -      |
| 1064               |      -     |       -      |
| 1065               |      -     |       -      |
| 1071               |      -     |       -      |
| 1074               |      -     |       -      |
| 1075               |      -     |       -      |
| 1076               |      -     |       -      |
| 1083               |      -     |       -      |
| 1087               |      -     |       -      |
| 1089               |      -     |       -      |
| 1090               |      -     |       -      |
| 1428               |      -     |       -      |
| 1102               |      -     |       -      |
| 1103               |      -     |       -      |
| 1105               |      -     |       -      |
| 1111               |      -     |       -      |
| 1113               |      -     |       -      |
| 1114               |      -     |       -      |
| 1116               |      -     |       -      |
| 1118               |      -     |       -      |
| 1123               |      -     |       -      |
| 1124               |      -     |       -      |
| 1125               |      -     |       -      |
| 1128               |      -     |       -      |
| 1136               |      -     |       -      |
| 1137               |      -     |       -      |
| 1139               |      -     |       -      |
| 1146               |      -     |       -      |
| 1153               |      -     |       -      |
| 1415               |      -     |       -      |
| 1162               |      -     |       -      |
| 1171               |      -     |       -      |
| 1177               |      -     |       -      |
| 1179               |      -     |       -      |
| 1180               |      -     |       -      |
| 1197               |      -     |       -      |
| 1218               |      -     |       -      |
| 1221               |      -     |       -      |
| 1222               |      -     |       -      |
| 1225               |      -     |       -      |
| 1424               |      -     |       -      |
| 1325               |      -     |       -      |
| 1335               |      -     |       -      |
| 1081               |      -     |       -      |
| 1348               |      -     |       -      |
| 1353               |      -     |       -      |
| 1356               |      -     |       -      |
| 1372               |      -     |       -      |
| 1379               |      -     |       -      |
| 1380               |      -     |       -      |
| 1385               |      -     |       -      |
| 1386               |      -     |       -      |
| 1391               |      -     |       -      |
| 1394               |      -     |       -      |
| 1396               |      -     |       -      |
| 1397               |      -     |       -      |
| 1398               |      -     |       -      |
| 1401               |      -     |       -      |
| 1402               |      -     |       -      |
| 1405               |      -     |       -      |
| 1406               |      -     |       -      |
| 1411               |      -     |       -      |
| 1419               |      -     |       -      |
| 1420               |      -     |       -      |
| 1421               |      -     |       -      |
| 1424               |      -     |       -      |
| 1425               |      -     |       -      |
| 1426               |      -     |       -      |
| 1427               |      -     |       -      |
| 1428               |      -     |       -      |
| 1430               |      -     |       -      |
| 1432               |      -     |       -      |
| 1442               |      -     |       -      |
| 1443               |      -     |       -      |
| 1445               |      -     |       -      |
| 1453               |      -     |       -      |
| 1457               |      -     |       -      |
| 1458               |      -     |       -      |
| 1460               |      -     |       -      |
| 1464               |      -     |       -      |
| 1465               |      -     |       -      |
| 1468               |      -     |       -      |
| 1469               |      -     |       -      |
| 1470               |      -     |       -      |
| 1471               |      -     |       -      |
| 1472               |      -     |       -      |
| 1473               |      -     |       -      |
| 1475               |      -     |       -      |
| 1478               |      -     |       -      |
| 1479               |      -     |       -      |
| 1480               |      -     |       -      |
| 1481               |      -     |       -      |
| 1486               |      -     |       -      |
| 1490               |      -     |       -      |
| 1492               |      -     |       -      |
| 1495               |      -     |       -      |
| 1496               |      -     |       -      |
| 1497               |      -     |       -      |
| 1498               |      -     |       -      |
| 1499               |      -     |       -      |
| 1501               |      -     |       -      |
| 1502               |      -     |       -      |
| 1504               |      -     |       -      |
| 1506               |      -     |       -      |
| 1507               |      -     |       -      |
| 1508               |      -     |       -      |
| 1515               |      -     |       -      |
| 1522               |      -     |       -      |
| 1526               |      -     |       -      |
| 1528               |      -     |       -      |
| 1529               |      -     |       -      |
| 1530               |      -     |       -      |
| 1532               |      -     |       -      |
| 1533               |      -     |       -      |
| 1537               |      -     |       -      |
| 1539               |      -     |       -      |
| 1540               |      -     |       -      |
| 1542               |      -     |       -      |
| 1545               |      -     |       -      |
| 1549               |      -     |       -      |
| 1551               |      -     |       -      |
| 1553               |      -     |       -      |
| 1556               |      -     |       -      |
| 1714               |      -     |       -      |
| 1715               |      -     |       -      |
| 1716               |      -     |       -      |
| 1717               |      -     |       -      |
| 1718               |      -     |       -      |
| 1724               |      -     |       -      |
| 1729               |      -     |       -      |
| 1730               |      -     |       -      |
| 1731               |      -     |       -      |
| 1732               |      -     |       -      |
| 1733               |      -     |       -      |
| 1734               |      -     |       -      |
| 1735               |      -     |       -      |
| 1736               |      -     |       -      |
| 1737               |      -     |       -      |
| 1738               |      -     |       -      |
| 1739               |      -     |       -      |
| 1741               |      -     |       -      |
| 1742               |      -     |       -      |
| 1746               |      -     |       -      |
| 1747               |      -     |       -      |
| 1752               |      -     |       -      |
| 1762               |      -     |       -      |
| 1765               |      -     |       -      |
| 1767               |      -     |       -      |
| 1769               |      -     |       -      |
| 1779               |      -     |       -      |
| 1784               |      -     |       -      |
| 1785               |      -     |       -      |
| 1788               |      -     |       -      |
| 1789               |      -     |       -      |
| 1790               |      -     |       -      |
| 1796               |      -     |       -      |
| 1806               |      -     |       -      |
| 1807               |      -     |       -      |
| 1808               |      -     |       -      |
| 1809               |      -     |       -      |
| 1811               |      -     |       -      |
| 1815               |      -     |       -      |
| 1816               |      -     |       -      |
| 1817               |      -     |       -      |
| 1820               |      -     |       -      |
| 1823               |      -     |       -      |
| 1824               |      -     |       -      |
| 1828               |      -     |       -      |
| 1830               |      -     |       -      |
| 1833               |      -     |       -      |
| 1834               |      -     |       -      |
| 1837               |      -     |       -      |
| 1839               |      -     |       -      |
| 1844               |      -     |       -      |
| 1846               |      -     |       -      |
| 1857               |      -     |       -      |
| 1863               |      -     |       -      |
| 1864 P32 H6               |      -     |       -      |
| 1874               |      -     |       -      |
| 1875               |      -     |       -      |
| 1876               |      -     |       -      |
| 1877               |      -     |       -      |
| 1883               |      -     |       -      |
| 1884               |      -     |       -      |
| 1886               |      -     |       -      |
| 1891               |      -     |       -      |
| 1896               |      -     |       -      |
| 1900               |      -     |       -      |
| 1901               |      -     |       -      |
| 1906               |      -     |       -      |
| 1907               |      -     |       -      |
| 1915               |      -     |       -      |
| 1917               |      -     |       -      |
| 1918               |      -     |       -      |
| 1919               |      -     |       -      |
| 1922               |      -     |       -      |
| 1926               |      -     |       -      |
| 1927               |      -     |       -      |
| 1930               |      -     |       -      |
| 1931               |      -     |       -      |
| 1933               |      -     |       -      |
| 1934               |      -     |       -      |
| 1939               |      -     |       -      |
| 1940               |      -     |       -      |
| 1942               |      -     |       -      |
| 1944               |      -     |       -      |
| 1945               |      -     |       -      |
| 1949               |      -     |       -      |
| 1953               |      -     |       -      |
| 1954               |      -     |       -      |
| 1955               |      -     |       -      |
| 1958 P33 B11               |      -     |       -      |
| 1958 P33 D11               |      -     |       -      |
| 1960               |      -     |       -      |
| 1965               |      -     |       -      |
| 1969               |      -     |       -      |
| 1970               |      -     |       -      |
| 1971               |      -     |       -      |
| 1973               |      -     |       -      |
| 1975               |      -     |       -      |
| 1980               |      -     |       -      |
| 1986               |      -     |       -      |
| 1987               |      -     |       -      |
| 1989               |      -     |       -      |
| 1990               |      -     |       -      |
| 1992               |      -     |       -      |
| 1993               |      -     |       -      |
| 1998               |      -     |       -      |
| 2000               |      -     |       -      |
| 2003               |      -     |       -      |
| 2004               |      -     |       -      |
| 2007               |      -     |       -      |
| 2008               |      -     |       -      |
| 2009               |      -     |       -      |
| 2010               |      -     |       -      |
| 2015               |      -     |       -      |
| 2017               |      -     |       -      |
| 2019               |      -     |       -      |
| 2022               |      -     |       -      |
| 2023               |      -     |       -      |
| 2024               |      -     |       -      |
| 2026               |      -     |       -      |
| 2029               |      -     |       -      |
| 2030               |      -     |       -      |
| 2032               |      -     |       -      |
| 2033               |      -     |       -      |
| 2035               |      -     |       -      |
| 2036               |      -     |       -      |
| 2038               |      -     |       -      |
| 2039               |      -     |       -      |
| 2041               |      -     |       -      |
| 2043               |      -     |       -      |
| 2048               |      -     |       -      |
| 2050               |      -     |       -      |
| 2053               |      -     |       -      |
| 2054               |      -     |       -      |
| 2055               |      -     |       -      |
| 2056               |      -     |       -      |
| 2060               |      -     |       -      |
| 2061               |      -     |       -      |
| 2064               |      -     |       -      |
| 2070               |      -     |       -      |
| 2071               |      -     |       -      |
| 2072               |      -     |       -      |
| 2077               |      -     |       -      |
| 2081               |      -     |       -      |
| 2082               |      -     |       -      |
| 2085               |      -     |       -      |
| 2086               |      -     |       -      |
| 2087               |      -     |       -      |
| 2092               |      -     |       -      |
| 2094               |      -     |       -      |
| 2098               |      -     |       -      |
| 2099               |      -     |       -      |
| 2102               |      -     |       -      |
| 2105               |      -     |       -      |
| 2111               |      -     |       -      |
| 2115               |      -     |       -      |
| 2116               |      -     |       -      |
| 2118               |      -     |       -      |
| 2119               |      -     |       -      |
| 2121               |      -     |       -      |
| 2129               |      -     |       -      |
| 2130               |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |
|                |      -     |       -      |

