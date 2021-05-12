## Wellcome Sanger Institute COVID Variants Data

Lineage counts by local authority and week for England

### Syntax

**WeekEnding** is the last date of the reported week

**Region** is the area of England, (ONS Code RGN19NM) 

**LTLA** is the local authority district

**Cases_100K** is the number of cases reported by PHE per 100,000 people in the LTLA across the reported week

**Weekly_Cases** is the total number of cases reported by PHE for the LTLA in the reported week

**Sequenced** is the total number of reported cases that were sequenced in the LTLA in the reported week

**%Sequenced** is the percentage of reported cases that were sequenced in the reported week

**Lineage** is the [Pangolin name](https://github.com/cov-lineages/pangolin) for the variant

**New_Lineage** is the number of new cases of the Lineage that have been Sequenced in the reported week

**%Lineage** is the percentage of Sequenced cases that match the Lineage in the reported week

 **Total_Lineage** is the total number of cases of the Lineage identified in the LTLA since reporting began 

 **Population** is the population of the LTLA, as reported by the ONS in 2020

 **ONS_Code** is the LAD19CD code for the LTLA, which can be used to link to other datasets

### Files:

**England_Variants_Full.csv** contains all reported variant data since September 5th 2020

**England_Variants_Week.csv** contains the most recent week of data

**Local Authorities/<LTLA>.csv** contains all reported data for the named Local Authority

### Data Sources:

**Wellcome Sanger Institute:** https://covid19.sanger.ac.uk/downloads

**PHE Case Data:** https://coronavirus.data.gov.uk/

**ONS PopulationDdata 2020:** https://www.ons.gov.uk/file?uri=/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/populationestimatesforukenglandandwalesscotlandandnorthernireland/mid2019april2020localauthoritydistrictcodes/ukmidyearestimates20192020ladcodes.xls


_The dataset will be updated daily by an automated process, (exact update time to be confirmed)_