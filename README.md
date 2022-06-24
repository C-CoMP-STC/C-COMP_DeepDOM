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

## Genomics (16S rRNA gene sequencing, metatranscriptomics, metagenomics\

Data description and summary:

Data can be accessed under the NCBI Umbrella BioProject PRJNA805279: https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA805279


## Publications with data from the 2013 DeepDOM cruise
### Primary datasets
(Cavaco et al. 2022): 16S rRNA gene sequencing, metatranscriptomics, and metagenomics\
Cavaco, M. A., M. P. Bhatia, A. K. Hawley, M. Torres-Beltrán, W. M. Johnson, K. Longnecker, K. Konwar, E. B. Kujawinski and S. J. Hallam (2022). Pathway-centric analysis of microbial metabolic potential and expression along nutrient and energy gradients in the western Atlantic Ocean Front Mar Sci 9.

Durkin, C. A., M. L. Estapa and K. O. Buesseler (2015). Observations of carbon export by small sinking particles in the upper mesopelagic. Mar Chem 175: 72-81.
Durkin, C. A., B. A. S. Van Mooy, S. T. Dyhrman and K. O. Buesseler (2016). Sinking phytoplankton associated with carbon flux in the Atlantic Ocean. Limnol Oceanogr 61: 1172-1187.

(Eggleston and Hewson 2016): Pelagibacter along a latitudinal transect\
Eggleston, E. M. and I. Hewson (2016). Abundance of Two Pelagibacter ubique Bacteriophage Genotypes along a Latitudinal Transect in the North and South Atlantic Oceans. Front Microbiol 7.

(Hoarfrost and Arnosti 2017): extracellular enzyme activities\
Hoarfrost, A. and C. Arnosti (2017). Heterotrophic Extracellular Enzymatic Activities in the Atlantic Ocean Follow Patterns Across Spatial and Depth Regimes. Front Mar Sci 4(200).

(Holm et al. 2022): Lipids (DeepDOM is one of multiple datasets)\
Holm, H. C., H. F. Fredricks, S. M. Bent, D. P. Lowenstein, J. E. Ossolinski, K. W. Becker, W. M. Johnson, K. Schrage and B. A. S. V. Mooy (2022). Global ocean lipidomes show a universal relationship between temperature and lipid unsaturation. Science 376(6600): 1487-1491.

(Howard et al. 2017): Biological production, export efficiency, and phytoplankton communities\
Howard, E. M., C. A. Durkin, G. M. M. Hennon, F. Ribalet and R. H. R. Stanley (2017). Biological production, export efficiency, and phytoplankton communities across 8000 km of the South Atlantic. Glob Biogeochem Cycle 31(7): 1066-1088.

Hurley, S. J., F. J. Elling, M. Könneke, C. Buchwald, S. D. Wankel, A. E. Santoro, J. S. Lipp, K.-U. Hinrichs and A. Pearson (2016). Influence of ammonia oxidation rate on thaumarchaeal lipid composition and the TEX86 temperature proxy. Proc Natl Acad Sci USA 113(28): 7762-7767.

Hurley, S. J., J. S. Lipp, H. G. Close, K.-U. Hinrichs and A. Pearson (2018). Distribution and export of isoprenoid tetraether lipids in suspended particulate matter from the water column of the Western Atlantic Ocean. Organic Geochemistry 116: 90-102.

(Johnson et al. 2020): metabolites on particles \
Johnson, W. M., K. Longnecker, M. C. Kido Soule, W. A. Arnold, M. P. Bhatia, S. J. Hallam, B. A. S. Van Mooy and E. B. Kujawinski (2020). Metabolite composition of sinking particles differs from surface suspended particles across a latitudinal transect in the South Atlantic. Limnol Oceanogr 65: 111-127.

(Johnson et al. in revision): Dissolved, known, metabolites\
Johnson, W. M., M. C. Kido Soule, K. Longnecker, M. P. Bhatia, S. J. Hallam, M. W. Lomas and E. B. Kujawinski (in revision). Insights into the controls on metabolite distributions along a latitudinal transect of the western Atlantic Ocean. Limnology and Oceanography 

(Lohmann et al. 2021): particulate organic pollutants\
Lohmann, R., E. Markham, J. Klanova, P. Kukucka, P. Pribylova, X. Gong, R. Pockalny, T. Yanishevsky, C. C. Wagner and E. M. Sunderland (2021). Trends of Diverse POPs in Air and Water Across the Western Atlantic Ocean: Strong Gradients in the Ocean but Not in the Air. Environ Sci Technol 55(14): 9498-9507.

(Longnecker et al. 2020): Organic sulfur concentrations and direct infusion mass spectrometry data\
Longnecker, K., L. Oswald, M. C. K. Soule, G. A. Cutter and E. B. Kujawinski (2020). Organic sulfur: a spatially variable and understudied component of marine organic matter. Limnol Oceanogr Lett 5: 305-312.

(Longnecker and Kujawinski 2020): Intracellular metabolites during grazing experiments\
Longnecker, K. and E. B. Kujawinski (2020). Intracellular metabolites in marine microorganisms during an experiment evaluating microbial mortality. Metabolites 10(3): 105.

Motta, L. C., J. D. Blum, B. N. Popp, J. C. Drazen and H. G. Close (2020). Mercury stable isotopes in flying fish as a monitor of photochemical degradation of methylmercury in the Atlantic and Pacific Oceans. Mar Chem 223: 103790.

Rocke, E., M. G. Pachiadaki, A. Cobban, E. B. Kujawinski and V. P. Edgcomb (2015). Protist community grazing on prokaryotic prey in deep ocean water masses. PLoS One 10(4): e0124505.

### Additional publications using a portion of DeepDOM data
- Kido Soule, M. C., K. Longnecker, W. M. Johnson and E. B. Kujawinski (2015). Environmental metabolomics: analytical strategies. Mar Chem 177, Part 2: 374-387.\
- Kujawinski, E. B., K. Longnecker, H. Alexander, S. T. Dyhrman, C. L. Fiore, S. T. Haley and W. M. Johnson (2017). Phosphorus availability regulates intracellular nucleotide pools in marine eukaryotic phytoplankton. Limnol Oceanogr Lett 2: 119-129.\
- Longnecker, K., J. Futrelle, E. Coburn, M. C. Kido Soule and E. B. Kujawinski (2015). Environmental metabolomics: databases and tools for data analysis. Mar Chem 177, Part 2: 366-373.\
- Longnecker, K. and E. B. Kujawinski (2017). Mining mass spectrometry data: Using new computational tools to find novel organic compounds in complex environmental mixtures. Organic Geochemistry 110: 92-99.\
- Saw, J. H. W., T. Nunoura, M. Hirai, Y. Takaki, R. Parsons, M. Michelsen, K. Longnecker, E. B. Kujawinski, R. Stepanauskas, Z. Landry, C. A. Carlson and S. J. Giovannoni (2020). Pangenomics analysis reveals diversification of enzyme families and niche specification in globally abundant SAR202 bacteria. mBio 11(1): e02975-02919.


