## England COVID-19 Cases / Deaths MSOA

Each week the UK government publishes a list of cases by MSOA in England, and each month the Office for National Statistics, (ONS), publishes statistics for deaths by MSOA.

An MSOA, (Middle Layer Super Output Area), is a geospatial area used by the Office for National Statistics, (ONS), to report small area statistics. There are 6,971 MSOAs in England, with an average population of 8,242 residents. They are referred to locally by their House of Commons Library names, usually forming a local neighbourhood or cluster of villages, so that is the naming convention used here.

This dataset gives the clearest insights yet into the amplitude of England's COVID-19 epidemic. Cases date back to Week 10, (March 1st 2020), and are updated weekly. Deaths date back to March 1st, and are updated monthly with each new ONS report.

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


**Note:** The UK completely lost control of their epidemic at the start of the pandemic. The early government testing capacity limited detection rates, so the deaths data is a more reliable indicator for the periods March-April, (Weeks 10-18).

Due to an early shortage of testing, there are some MSOAS where more deaths have been reported than cases. These MSOAs will all have a CFR% above 100. This happens because Deaths are reported by the cause of death listed on the death certificate, so the deceased may have had a clinical diagnosis of COVID without a positive test. The ONS cannot confirm if the deceased was tested or not, so it isn't possible to separate confirmed cases with clinically diagnosed fatalities. For this reason, individual cases from government data may not always directly correlate with deaths from the ONS data.

### Sheets

The smaller sheets can all be rendered in the browser, but larger sheets will need to be downloaded and opened in Excel or LibreOffice.

**England-Cases-Deaths_TOTALS.csv** contains the latest total cases, deaths and calculated rates for each MSOA in England.

**England-Cases-Deaths_TIME.csv** contains a timeseries of deaths by month and cases by week for each MSOA in England.

**England-Cases-Deaths_WORST.csv** contains the latest total cases, deaths and calculated rates for the worst affected MSOAs in England.

**England-Cases-Deaths_LEAST.csv** contains the latest total cases, deaths and calculated rates for the least affected MSOAs in England.

**<REGION\>-Cases-Deaths_TOTALS.csv** contains the latest total cases, deaths and calculated rates for each MSOA in the Region.

**<REGION\>-Cases-Deaths_TIME.csv** contains a timeseries of deaths by month and cases by week for each MSOA in the Region.

**<REGION\>-Cases-Deaths_WORST.csv** contains the latest total cases, deaths and calculated rates for the worst affected MSOAs in the Region.

**<REGION\>-Cases-Deaths_LEAST.csv** contains the latest total cases, deaths and calculated rates for the least affected MSOAs in the Region.


### Regional/Population Data

The dataset is tagged with Region, Local Authority and MSOA names and codes. Population data by MSOA comes from the latest December 2019 reprot, accurate as of 2018: https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/middlesuperoutputareamidyearpopulationestimates



### Deaths Data

The Office for National Statistics releases a monthly count of COVID-19 deaths by MSOA, based on place of residence of the deceased and cause of death on their death certificate. As death certificates are certified by a medical practitioner, the ONS is considered to provide the most reliable indicator of the UK's COVID-19 death toll: https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/bulletins/deathsinvolvingcovid19bylocalareasanddeprivation/deathsoccurringbetween1marchand30june2020




### Case Data

The UK Government now provides Case data by MSOA and Week number on their new dashboard, from the 'Weekly cases by local area in England' map. This dataset has been joined to the ONS Deaths data by merging them on the MSOA19CD codes in each dataset: https://coronavirus-staging.data.gov.uk/cases
