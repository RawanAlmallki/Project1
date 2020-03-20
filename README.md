# Project1: Traffic accidents & driving licenses in KSA
## Problem statement:
From the data provided by the Traffic Department of the Ministry of Interior to monitor traffic accidents. It was analysed to provide recommendations to help reduce traffic accidents. We analyzed a dataset showing the number of traffic accidents for the regions in 2016-2017 and a dataset showing the number of driver's licenses issued in 1993-2017.
## Summary:
We find two issues in the data that should be the main focus of the General Department of traffic going forward:

- While traffic accidents in most regions are relatively similar, 3 regions with traffic accidents are significantly higher than the average: Mekkah,Riyadh and the Eastern Region.

- Traffic department focus should be on the regions named in the previous point and specifically on Makkah region. Investigation into: traffic policies and road infrastructure spending should be first priority.
##  Dictionary:
Showing overview of the features of two datasets:
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|int|ksa_traff_accid,ksa_driv_lic|The years when driving licenses were issued and traffic accidents recorded. |
|**region**|object|ksa_traff_accid,ksa_driv_lic|The regions where driving licenses have been issued and traffic accidents recorded.|
|**indicator**|object|ksa_traff_accid|Classification of data into accidents, deaths and injuries.|
|**value**|int|ksa_traff_accid|Numbers of accidents, deaths and injuries.|
|**driving_licenses**|int|ksa_driv_lic|Number of licenses issued.|
|**latitude**|float|ksa_traff_accid,ksa_driv_lic|The latitude coordinate of the associated region.|
|**longitude**|float|ksa_traff_accid,ksa_driv_lic|The longitude coordinate of the associated region.|

## Conclusions & Recommendations:
### Conclusions:
- This report was created to help identify the causes of the increase in traffic accidents and how to find solutions to facilitate road traffic in Saudi Arabia. The data analyzed showed that the trend was to reduce the number of traffic accidents.
 During the years (2016-2017), data from the Traffic Department of the Ministry of Interior showed an increase in the main areas of Makkah, Riyadh and the Eastern region above the mean number of accidents. 

### Recommendations:
- You have to be careful and focus when you driving in Makkah. Seems like the accidents is a lot higher than average.

- More scrutiny should be made into traffic violations in Makkah region and made plans to repair or modify existing roads, as well as when made plans to build new roads.

