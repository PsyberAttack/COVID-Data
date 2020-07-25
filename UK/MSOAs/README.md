## England COVID-19 Cases / Deaths MSOA

A Middle Layer Super Output Area (MSOA) is a geospatial area used by the Office for National Statistics, (ONS), to report small area statistics. They are referred to locally by their House of Commons Library names, usually forming a local neighbourhood or cluster of villages.

This dataset gives the clearest insights yet into the amplitude of England's COVID-19 epidemic. Cases date back to Week 10, (March 1st 2020), and are recorded weekly. Deaths date back to March 1st. They're updated in monthly format.

### Syntax

1. **MSOA Name** is the House of Commons Library name for the MSOA

1. **Local Authority** is the LTA authority for the MSOA

1. **Cases** is the sum total number of cases ever reported by UK Government for the MSOA

2. **Deaths** is the sum total number of deaths ever recorded by the ONS in the MSOA

3. **Population** is from the latest ONS population survey, accurate as of July 2018.

4. **Cases_100K** is a per capita calculation of Cases per 100K Population:  ((Population / 100,000)  \*  Cases)

5. **Deaths_100K** is a per capita calculation of Deaths per 100K Population: ((Population / 100,000)  \*  Deaths)

6. **Infected%** is the percentage of the population who've tested posistive: ( Cases  / Population)

7. **Dead%** is the percentage of the population who've died: (100 / (Deaths / Population))

8. **CFR%** is the percentage of the Cases reported by UK Government and deaths reported by ONS: (100 / (Deaths / Population))

9. **MSOA11CD/LAD19CD** are unique codes for each area, which can be used to connect this data to others using ONS codes.



** Note:** The UK completely lost control of their epidemic at the start of the pandemic. The early government testing data was limited so the early numbers of reported cases are deceptive. Deaths have been determined by what is written on the death certificate. The ONS has no way of confirming if the deceased was tested, but COVID-19 will have been mentioned as a cause of death.

The deaths data is a more reliable source for the periods March-April, (Weeks 10-18), and they point to an epidemic as bad as anything seen globally.



### Regional Data

The dataset is tagged with Region, Local Authority and MSOA names and codes. Population data by MSOA comes from the latest December 2019 reprot, accurate as of 2018: https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/middlesuperoutputareamidyearpopulationestimates



### Deaths Data

The Office for National Statistics releases a monthly count of COVID-19 deaths by MSOA, based on place of residence of the deceased and cause of death on their death certificate. As death certificates are certified by a medical practitioner, ONS is considered to provide the most reliable indicator of the UK's COVID-19 death toll: https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/bulletins/deathsinvolvingcovid19bylocalareasanddeprivation/deathsoccurringbetween1marchand30june2020




### Case Data

The UK Government now provides Case data by MSOA and Week number on their new dashboard, from the 'Weekly cases by local area in England' map. This dataset has been joined to the ONS Deaths data by merging them on the MSOA19CD codes in each dataset: https://coronavirus-staging.data.gov.uk/cases



### Files:

The data is provided in both timeseries and total form.

**England-MSOA-Cases-Deaths.csv** contains the latest total cases and deaths data.

**England-MSOA-Cases-Deaths_TIME.csv** contains a timeseries of deaths by month and case by week.




### Data Sources:

**UK Government Coronavirus Dashboard:** https://coronavirus-staging.data.gov.uk/cases

**ONS COVID Deaths by MSOA Map:** https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/causesofdeath/articles/deathsinvolvingcovid19interactivemap/2020-06-12 

_The dataset will be updated daily by an automated process, (exact update time to be confirmed)_
