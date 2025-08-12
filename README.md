# WBP

-------------------
GENERAL INFORMATION
-------------------


1. Tetons Whitebark and Limber Pine Spectra + Physiology

Pine physiology metrics and spectra collected at Mt. Glory in Wilson, WY in 2025

3. Author Information

  Principal Investigator Contact Information
        Name: Danielle Ulrich
           Institution: Montana State University
           Address: 310 Lewis Hall, Bozeman, MT 59717
           Email: danielle.ulrich@montana.edu
	   ORCID: 0000-0002-2367-4193

  Associate or Co-investigator Contact Information
           Name: Anna Schweiger
           Institution: Montana State University
           Address: Leon Johnson Hall, Bozeman, MT 59717
           Email: anna.schweiger@montana.edu
	   ORCID: 0000-0002-5567-4200

  Associate or Co-investigator Contact Information
        Name: Lou Duloisy
           Institution: Montana State University
           Address: 310 Lewis Hall, Bozeman, MT 59717
           Email: 

  Associate or Co-investigator Contact Information
           Name: Madelyn Zack
           Institution: Montana State University
           Address: Leon Johnson Hall, Bozeman, MT 59717
           Email: n49p778@montana.edu



3. Date of data collection: 2025-06-12 to 2025-06-15	2025-09-01 to 2025-09-04

4. Geographic location of data collection (where was data collected?): Mt. Glory Teton Dr, Wilson, WY 83014

5. Information about funding sources that supported the collection of the data: 

Sponsorship: 

--------------------------
SHARING/ACCESS INFORMATION
-------------------------- 


1. Licenses/restrictions placed on the data:
Creative Commons Attribution-NonCommercial-NoDerivs 3.0 United States, http://creativecommons.org/licenses/by-nc-nd/3.0/us/ 

2. Links to publications that cite or use the data:

3. Links to other publicly accessible locations of the data:

4. Links/relationships to ancillary data sets:

5. Was data derived from another source?
           If yes, list source(s):No

6. Recommended citation for the data:



--------------------------
METHODOLOGICAL INFORMATION
--------------------------

1. Description of methods used for collection/generation of data:

	a. Leaf-level spectra were taken on intact fasicles opposite to fasicles tapped for gas exchange measurements. One to three fasicles were arranged on a black nonreflective background and held in place with rubber bands. Two averaged spectral readings were taken per fasicle, avoiding gaps between needles with the handheld contact probe.

	b. Fresh leaf-tissue samples for NSC quantification were collected in the field, stored on dry ice, microwaved for 3 minutes to stop enzymatic activity, and dried.

	c. Gas exchange parameters including net photosynthesis rate (A) and stomatal conductance (gs) were measured using the LI-6800 Portable Photosynthesis System (LI-COR Biosciences, Lincoln, NE, USA). Measurements were conducted on mature, healthy leaf fasicles under controlled environmental conditions within the leaf chamber. Data were recorded once steady-state values were achieved after 2–3 minutes of stabilization.

	d. Leaf water potential was determined using a pressure chamber (Water Potential Pressure Chamber – Standard, Edaphic Scientific, Moorabbin, VIC, Australia). Immediately after gas exchange measurements, similar paired fasicles were removed removed and placed in a dark cooler until the chamber could be reached (seasonal) OR immediately placed in the chamber to measure diurnal water potential (diurnals).

2. Methods for processing the data:

	a. Leaf reflectance spectra were collected over the range 350–2500 nm. Raw spectral data were first corrected for dark current and calibrated using a white reference panel. Regions affected by atmospheric water absorption (e.g., 1350–1450 nm, 1800–1950 nm) were removed or corrected*

	b. Dried fasicles collected for NSC contents were processed following the double digestion protocol described by Landhäusser et al. (2018). Briefly, dried and finely ground plant tissue samples were first extracted with ethanol to remove soluble sugars. The ethanol extracts were then analyzed for soluble sugar content using enzymatic assays. The remaining pellet was subjected to double enzymatic digestion using amyloglucosidase and α-amylase to hydrolyze starch into glucose. The glucose released was quantified enzymatically and used to calculate starch content.

	c. Gas exchange raw data were checked, unstable or flagged data points removed. For each fasicle, steady-state values were averaged over the measurement period. Environmental conditions inside the chamber (temperature, light, CO₂, humidity) were monitored and kept consistent across samples.

	d. Water potential pressure readings indicating xylem sap emergence at the petiole cut were recorded as leaf water potential.


References
Landhäusser, S. M. Standardized protocols and procedures can precisely and accurately quantify non-structural carbohydrates. Tree Physiology, 38(4), 514–529 (2018)


3. Instrument- or software-specific: 
LI-6800 Portable Photosynthesis System, LI-COR Biosciences, Lincoln, NE, USA
FieldSpec 4 Spectroradiometer, ASD Inc., Longmont, CO, USA
Water Potential Pressure Chamber – Standard, Edaphic Scientific, Moorabbin, VIC, Australia

5. Standards and calibration information, if appropriate: 
White reference panel (internal to leaf clip), ASD Inc., Longmont, CO, USA
Spectralon Reflectance Standard, Labsphere Inc., North Sutton, NH, USA

6. Environmental/experimental conditions: 
Fairly dry field conditions, evening rainfall.

7. Describe any quality-assurance procedures performed on the data:
White reference spectra collected in-between each sample spectra.

8. People involved with sample collection, processing, analysis and/or submission:
Lou Duloisy (collection, processing, analysis, submission)
Danielle Ulrich
Anna K. Schweiger
Madelyn Zack (collection, analysis)
High schooler

---------------------
DATA & FILE OVERVIEW
---------------------
This data set contains diurnal gas exchange, water potential, [NSC], and spectral data from 10 Whitebark (PIAL) & Limber pine (PIFL) individuals sampled along the Mt. Glory trail in Wilson, WY. Physiological data was used to build partial least squares regression (PLSR) models for predicting leaf nutrient contents from spectra.

1. File List
   A. Filename: WBP_diurnals.csv	
	Short Description: Leaf gas exchange and water potential measurements
	Size: 
	Type: CSV file

   B. Filename: DOB_pigments.csv	
	Short Description: Leaf-level spectra
	Size: 
	Type: CSV file  

-----------------------------------------
DATA-SPECIFIC INFORMATION FOR: DOB_pigments.csv 
-----------------------------------------

1. Number of variables: 6

2. Number of cases/rows: 60

3. Missing data codes: NA      

4. Variable List
   
    A. ID: individual ID
	B. species: species abbreviation (PIAL or PIFL)
	C. timepoint: time of measurement (six per day)
	D. water_potential: water potential (MPa)    
	E. A: net photosynthesis (µmol CO2 m-2 s-1)
	F. GSW: stomatal conductance (mol m-2 s-1) 
