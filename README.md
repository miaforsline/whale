# EDS 223 Assignment 3: Protecting Whales from Ships
### Student authors: Mia Forsline & Alexandra Yousefivand
### Due 2021-11-16 

## Motivation and project goal
This assignment draws from the "Worthwhale" MESM group project (UCSB Bren School class of 2020), which includes an economic valuation of whale watching tourism for the Caribbean island nation Dominica. Whale watching tourism contributes significantly to the economy of Dominica; however, it was also determined that fast-moving ships pose a threat to whale safety. The **project goal** is to determine an appropriate speed reduction zone for ships off the coast of Dominica and the potential effect on local marine traffic. Whale siting data from 2005-2018 were examined, in conjunction with Automatic Identification System (AIS) transmitter locational data, to create a map of a proposed speed reduction zone. The original ship speed was compared to a ship speed of 10 knots in order to determine the impact of the speed reduction zone on ship travel times.

## Intended purpose and important concepts
As this project is intended for educational purposes, the student authors practiced the following:
- assigning geometries
- setting (and resetting) coordinate reference systems
- spatial joins
- creating a convex hull
- plotting grids and maps
- calculating distances and speeds
- unit conversions

## Future research
Future research aims to validate the preliminary parameters used in this analysis, such as minimum critical number of whale sitings per spatial cell and the duration of such sitings. This analysis seeks to inform future policy regarding whale watching ecotourism and ship speeds in whale habitats.

## Installation
The following **packages** were utilized during this analysis:
- `geopandas`
- `pandas`
- `numpy`
- `matplotlib`
- `shapely`

## Data
Due to large file sizes, data for this analysis is **NOT** hosted in the repository. Data should be downloaded **locally** into the following file structure.
    
- protecting-whales-from-ships-21
    - README.md
    - HW3.ipynb
    - data (_directory_)
        - sightings2005_2018
        - station1249
        - dominica (_directory_)
            - dma_admn_adm0_py_s1_dominode_v2.cpg
            - dma_admn_adm0_py_s1_dominode_v2.dbf
            - dma_admn_adm0_py_s1_dominode_v2.prj
            - dma_admn_adm0_py_s1_dominode_v2.sbn
            - dma_admn_adm0_py_s1_dominode_v2.sbx
            - dma_admn_adm0_py_s1_dominode_v2.shp
            - dma_admn_adm0_py_s1_dominode_v2.shp
            - dma_admn_adm0_py_s1_dominode_v2.shx
