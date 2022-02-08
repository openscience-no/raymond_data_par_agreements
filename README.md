# raymond_data_par_agreements
Public data about the Norwegian journal agreements. Journal and participant lists, etc.

This repository contains information about the journal license agreements listed on
https://www.openscience.no/en/publisering/apen-publisering

## Content
There are currently two main folders, one with data on agreement journals and one with data on agreement participant institutions.  
Journal lists are based on data received directly from the publisher and may be enriched with additional information found on the publishers website. Participant lists are based on data from the consortium administration system Edvarda. 

## Structure  
Data are availiable in two equal formats, both containing the same information (duplicates):
   - `/all`  
     All agreements aggregated into one single file. A `.csv` using ";" for the field separator and "," for the decimal point.
   - `/agreement_name01`  
     Separat folders for each agreement, with an Excel (`.xlsx`) file.  
  
The `*_current.*` file will always containt the most recent version of the data. Additionally, historic versions are also provided on a year by year basis.

Example:
```
raymond_data_par_agreements
    agreement_journals
        all 
            agr_journals_all_current.csv 
            agr_journals_all_year_2022.csv 
        agreement_name01 
            agr_journals_agreement_name01_current.xlsx
            agr_journals_agreement_name01_year_2022.xlsx
    agreement_participants
        all 
            agr_participants_all_current.csv
            agr_participants_all_year_2022.csv
        agreement_name01 
            agr_participants_agreement_name01_current.xlsx
            agr_participants_agreement_name01_year_2022.xlsx
```

