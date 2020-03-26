# ICD9-to-ICD10-Mapping
This specific program is used to map ICD 9 CM codes to ICD 10 CM codes using GEM (General Equivalence Mapping). 
The mapping has been done for the columns Diagnosis1, Diagnosis2, Diagnosis3, Diagnosis4 and Diagnosis5.
In the code, the GEM file has been read from the folder, thus the path has the folder name at first. Whereas the GEM file has been directly uploaded, so while executing please change the path. 
These ICD9 codes donot have decimal imputations like in GEM file. Thus, there was no need to impute the decimals for ICD9 codes. 
After obtaining the ICD10 codes for the respective ICD9 codes, the decimals have been imputed at approrpiate positions. 
Since FLAGS would not affect the process of mapping, eventually they have not been considered. 
