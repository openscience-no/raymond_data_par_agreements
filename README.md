# raymond_data_par_agreements
Public data about the Norwegian journal agreements. Journal and participant lists, etc.

This repository contains information about the journal license agreements listed on
https://www.openscience.no/en/publisering/apen-publisering

## Content
The data is provided in two ways, both containing the same information (duplicates). 
  - `/all`  
    All agreements listed in one single file. A `.csv` using ";" for the field separator and "," for the decimal point.
  - `/agreement_name01`  
    Separat folders for each agreement, with an Excel (`.xlsx`) file.

## Structure
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

