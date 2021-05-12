## Wellcome Sanger Institute COVID Variants Data

Lineage counts by local authority and week for England

### Syntax

1. **WeekEnding** is the last date of the reported week

2. **Region** is the area of England, (ONS Code RGN19NM) 

3. **LTLA** is the local authority district

4. **Weekly_Cases** is the total number of cases reported by PHE for the LTLA in the reported week

5. **Sequenced** is the total number of reported cases that were sequenced in the LTLA in the reported week

6. **%Sequenced** is the percentage of reported cases that were sequenced in the reported week

7. **Lineage** is the [Pangolin name](https://github.com/cov-lineages/pangolin) for the variant

8. **New_Lineage** is the number of new cases of the Lineage that have been Sequenced in the reported week

9. **%Lineage** is the percentage of Sequenced cases that match the Lineage in the reported week

10. **Total_Lineage** is the total number of cases of the Lineage identified in the LTLA since reporting began 

11. **Population** is the population of the LTLA, as reported by the ONS in 2020

12. **ONS_Code** is the LAD19CD code for the LTLA, which can be used to link to other datasets


### Files:

**England_Variants_Full.csv** contains all reported variant data since September 5th 2020

**England_Variants_Week.csv** contains the most recent week of data

**Local Authorities/<LTLA>.csv** contains all reported data for the named Local Authority

### Data Sources:

**Wellcome Sanger Institute:** https://covid19.sanger.ac.uk/downloads

**PHE Case Data:** https://coronavirus.data.gov.uk/

**ONS PopulationDdata 2020:** https://www.ons.gov.uk/file?uri=/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/populationestimatesforukenglandandwalesscotlandandnorthernireland/mid2019april2020localauthoritydistrictcodes/ukmidyearestimates20192020ladcodes.xls


_The dataset will be updated daily by an automated process, (exact update time to be confirmed)_