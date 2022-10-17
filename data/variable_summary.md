# Variable summary

## Id var

note: column index [1:7] for each file

statecode  
countycode  
fipscode  
state  
county  
year  
county_ranked -- *County Ranked (Yes=1/No=0); missing if national or state level*  


## Dependent var

note: 2018 and 2019 data seem to use same underlying source data for dependent var (from 2016); 2020 uses 2017 data; 2021 uses 2018 data

**Poor mental health days**  
v042_rawvalue  
v042_cilow  
v042_cihigh  

**Frequent mental distress rate** -- *starts in 2016*  
v145_rawvalue  
x v145_numerator  
x v145_denominator  
v145_cilow  
v145_cihigh  


## Explanatory var

**Income inequality** (ratio) -- *starts in 2015*  
v044_rawvalue  
v044_numerator  
v044_denominator  
v044_cilow  
v044_cihigh  


## Control var

**Median household income**  
v063_rawvalue  
v063_cilow  
v063_cihigh  

**High school graduation rate**  
v021_rawvalue  
v021_numerator  
v021_denominator  

**Some college rate**  
v069_rawvalue  
v069_numerator  
v069_denominator  
v069_cilow  
v069_cihigh  

**Unemployment rate**  
v023_rawvalue  
v023_numerator  
v023_denominator  

**Children in poverty rate**  
v024_rawvalue  
v024_numerator  
*x* v024_denominator -- *== population < 18*  
v024_cilow  
v024_cihigh  

**Children in single-parent households rate**  
v082_rawvalue  
v082_numerator  
v082_denominator  
v082_cilow  
v082_cihigh  

**Severe housing problems rate**  
v136_rawvalue  
v136_numerator  
v136_denominator  
v136_cilow  
v136_cihigh  

**Food environment index** -- *starts in 2014*  
v133_rawvalue  
v133_numerator  
v133_denominator  

**Mental health providers** -- *missing in 2014*
v062_rawvalue  
v062_numerator  
v062_denominator  
*x* v062_cilow  
*x* v062_cihigh  
v062_other_data_1 -- *Ratio of population to mental health providers; this var contains negatives in older years; remove those obs?*  


## Demographic var

note: numerator and denominator for following var available starting 2015

**Population count**  
v051_rawvalue  

**% below 18 years of age** -- *multiply by population to get denominator for children in poverty rate?*  
v052_rawvalue  

**% Non-Hispanic African American**  
v054_rawvalue  

**% American Indian and Alaskan Native**
v055_rawvalue  

**% Asian**  
v081_rawvalue  

**% Native Hawaiian/Other Pacific Islander**  
v080_rawvalue  

**% Hispanic**  
v056_rawvalue  

**% Non-Hispanic white**  
v126_rawvalue  

**% Females**  
v057_rawvalue  

**% Rural**  
v058_rawvalue  
v058_numerator  
v058_denominator  
