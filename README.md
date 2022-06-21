# C-COMP_DeepDOM
Repo to host code and information generated on behalf of the Center for Chemical Currencies of a Microbial Planet's DeepDOM Data Integration Project

Deep Dissolved Organic Matter (DOM) otherwise known as DeepDOM is the name for a cruise (deployment KN210-04, https://www.bco-dmo.org/deployment/59057) that was conducted across the Western Atlantic Ocean (starting at Montevideo, Uruguay and ending at Bridgetown, Barbados) in 2013. 

<img width="1023" alt="Screen Shot 2022-06-21 at 11 26 11 AM" src="https://user-images.githubusercontent.com/107074556/174838020-4a23bbe6-2144-4bbe-9b5e-a294f810197f.png">


The science objectives of this cruise included:
1. Characterizing deep ocean dissolved organic matter in water masses of western Atlantic Ocean.
2. Characterizing microbial community at selected stations and at selected depths.
3. Characterizing metabolic capabilities of surface, mesopelagic and bathypelagic microbial consortia vis-a-vis the degradation of organic matter from each zone.
4. Examining metabolic and phylogenetic links between microbes in different marine zones (surface, meso-pelagic and bathypelagic depths).

Seawater samples were collected using the following methods to investigate the science objectives shown above:
1. Collecting discrete water samples using Niskin-bottles.
2. Collecting microbial communities from these water samples, by in-situ pumping, or by net-traps and net-tows.
3. Conducting incubation experiments in lab and on deck.
4. Conducting mass spectrometry and flow cytometry underway, using the vessel's seawater intake.

The purpose of this wiki is to provide links to all the relevant metadata and data files in one location to aid training, exploration, and integration efforts during the C-CoMP DeepDOM Workshop. Datasets using various methods are presented below:

## Conductivity-Temperature-Depth (CTD)Sensor Casts

Data description and summary: This data table contains a record of measurements collected by CTD sensors over the course of the cruise. Header fields include relevant fields like: station #, date, lat, lon, depth, pressure, temperature, salinity, O2 concentrations, density, turbidity, par, spar). 74 discrete casts at 23 separate stations (locations). Lead PI: Liz Kujawinski, Co-PI: Krista Longnecker

CTD Data Table Link: http://dmoserv3.bco-dmo.org/jg/serv/BCO-DMO/Deep_Atlantic_DOM/CTD.html0%7Bdir=dmoserv3.whoi.edu/jg/dir/BCO-DMO/Deep_Atlantic_DOM/,info=dmoserv3.bco-dmo.org/jg/info/BCO-DMO/Deep_Atlantic_DOM/CTD%7D

BCO-DMO Dataset Landing Page: https://www.bco-dmo.org/dataset-deployment/481167

## Cruise Event Log

Data description and summary: The cruise event log includes metadata about all sample collections or 'events' that took place during the cruise. Header fields include: instrument, action, station, cast #, lat, lon, seafloor, author, and comment. Lead PI: Liz Kujawinski, Co-PI: Krista Longnecker

Cruise Event Data Table: http://dmoserv3.bco-dmo.org/jg/serv/BCO-DMO/Deep_Atlantic_DOM/event_log.html0%7Bdir=dmoserv3.whoi.edu/jg/dir/BCO-DMO/Deep_Atlantic_DOM/,info=dmoserv3.bco-dmo.org/jg/info/BCO-DMO/Deep_Atlantic_DOM/event_log%7D

BCO-DMO Dataset Landing Page: https://www.bco-dmo.org/dataset-deployment/456062


## DeepDOM Metaproteomes





## Intracellular Metabolites in Marine Microorganisms during an Experiment Evaluating Microbial Mortality

Paper:https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7142611/ (Longnecker and Kujawinski, 2020). 

Study description (from MetaboLights): This project considers the effects of predation and viral lysis on the metabolites found in the surface ocean. Using seawater from the surface ocean, we experimentally manipulated levels of predation and viral lysis. At the beginning and end of the experiment, we sampled the intracellular and extracellular metabolites. The extracts were analyzed using liquid chromatography-based targeted and untargeted metabolomics methods that we have modified for use with marine samples. Lead PI: Liz Kujawinski, Co-PI: Krista Longnecker

Sample Data Table on MetaboLights: https://www.ebi.ac.uk/metabolights/MTBLS461/samples

Metadata ('ISA Metadata') and Targeted and Untargeted metabolomics files (raw): https://www.ebi.ac.uk/metabolights/MTBLS461/files

## Inorganic and organic nutrient data from Niskin bottles

Data description and summary: Inorganic and organic nurient concentrations that were measured in seawater collected from Niskin bottles. Measurements include phosphate, nitrate+nitrite, silicate, nitrite, ammonium, non-purgeable organic carbon, and total nitrogen concentrations. Lead PI: Liz Kujawinski, Co-PI: Krista Longnecker

DeepDOM Nutrient Data Table: [DeepDOM_nutrients.txt](https://github.com/lggray22/C-COMP_DeepDOM/files/8929674/DeepDOM_nutrients.txt)

BCO-DMO Nutrient Dataset Landing Page: https://www.bco-dmo.org/dataset-deployment/473302

## Targeted Metabolite Abundances (Dissolved)

Data description and summary: This dataset contains dissolved metabolite abundances from seawater samples collected during the R/V Knorr cruise KN210-04 between 29 Mar 2013 and 06 May 2013 along the eastern coast of South America. Sample depth, lat, lon, station, time, and cast are from CTD profiles are also included in this dataset. Targeted Metabolites have been corrected for extraction efficiency, but detection limits for the instrument (TSQ) need to be considered during data analysis. Lead PI: Liz Kujawinski, Co-PI: Krista Longnecker

DeepDOM Targeted Metabolite Abundances (Dissolved) Data Table:[DeepDOM_metabolites_dissolved.txt](https://github.com/lggray22/C-COMP_DeepDOM/files/8929731/DeepDOM_metabolites_dissolved.txt)

BCO-DMO DeepDOM Targeted Metabolite Abundances (Dissolved) Data Table Link: http://dmoserv3.bco-dmo.org/jg/serv/BCO-DMO/Deep_Atlantic_DOM/metabolites_dissolved.html0%7Bdir=dmoserv3.whoi.edu/jg/dir/BCO-DMO/Deep_Atlantic_DOM/,info=dmoserv3.bco-dmo.org/jg/info/BCO-DMO/Deep_Atlantic_DOM/metabolites_dissolved%7D

BCO-DMO DeepDOM Targeted Metabolite Abundances (Dissolved) Dataset Landing Page: https://www.bco-dmo.org/dataset-deployment/700032

## Targeted Metabolite Abundances (Particulate)

Data description and summary: This dataset contains particulate metabolite abundances from seawater samples collected during the R/V Knorr cruise KN210-04 between 29 Mar 2013 and 06 May 2013 along the eastern coast of South America. Sample depth, lat, lon, station, time, and cast are from CTD profiles are also included in this dataset. Some of these data are published Kujawinski et al., 2017. Lead PI: Liz Kujawinski, Co-PI: Krista Longnecker

DeepDOM Targeted Metabolite Abundances (Particulate) Data Table: 
[DeepDOMmetabolites_particulate.txt](https://github.com/lggray22/C-COMP_DeepDOM/files/8929774/DeepDOMmetabolites_particulate.txt)

BCO-DMO DeepDOM Targeted Metabolite Abundances (Particulate) Data Table Link: http://dmoserv3.bco-dmo.org/jg/serv/BCO-DMO/Deep_Atlantic_DOM/metabolites_particulate.html0%7Bdir=dmoserv3.whoi.edu/jg/dir/BCO-DMO/Deep_Atlantic_DOM/,info=dmoserv3.bco-dmo.org/jg/info/BCO-DMO/Deep_Atlantic_DOM/metabolites_particulate%7D

BCO-DMO DeepDOM Targeted Metabolite Abundances (Particulate) Dataset Landing Page: https://www.bco-dmo.org/dataset-deployment/700045

## Total Organic Sulfur Concentrations 

Data description and summary: This dataset contains the concentration of total organic sulfur in seawater from samples collected during the R/V Knorr cruise KN210-04 between 29 Mar 2013 and 06 May 2013 along the eastern coast of South America. Lead PI: Liz Kujawinski, Co-PI: Krista Longnecker

DeepDOM Organic Sulfur Concentrations Data Table: 
[DeepDOM_TOS.txt](https://github.com/lggray22/C-COMP_DeepDOM/files/8929784/DeepDOM_TOS.txt)

BCO-DMO DeepDOM Organic Sulfur Concentrations Data Table Link: http://dmoserv3.bco-dmo.org/jg/serv/BCO-DMO/Deep_Atlantic_DOM/TOS.html0%7Bdir=dmoserv3.whoi.edu/jg/dir/BCO-DMO/Deep_Atlantic_DOM/,info=dmoserv3.bco-dmo.org/jg/info/BCO-DMO/Deep_Atlantic_DOM/TOS%7D

BCO-DMO DeepDOM Organic Sulfur Concentrations Dataset Landing Page: https://www.bco-dmo.org/dataset-deployment/745542

## Viral and Bacterial Counts 

Data description and summary: Viral and bacterial counts from filtered water, stained with SYBR Green and counted using epifluorescent microscopy. Duplicates were collected at each depth during the KN210-04 cruise. Lead PI: Ian Hewson, Cornell University

BCO-DMO Viral and Bacterial Counts Data Table: [DeepDOM_viral_bact_counts.txt](https://github.com/lggray22/C-COMP_DeepDOM/files/8929798/DeepDOM_viral_bact_counts.txt)


BCO-DMO Viral and Bacterial Counts Data Table Link: http://dmoserv3.bco-dmo.org/jg/serv/BCO-DMO/Deep_Atlantic_DOM/viral_bact_counts.html0%7Bdir=dmoserv3.whoi.edu/jg/dir/BCO-DMO/Deep_Atlantic_DOM/,info=dmoserv3.bco-dmo.org/jg/info/BCO-DMO/Deep_Atlantic_DOM/viral_and_bacterial_counts%7D

BCO-DMO Viral and Bacterial Counts Dataset Landing Page: https://www.bco-dmo.org/dataset-deployment/528518




