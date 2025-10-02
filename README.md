Mafoko: South African Terminology, Lexicon and Glossary Project
==============================

Give Feedback 📑: [DSFSI Resource Feedback Form](https://docs.google.com/forms/d/e/1FAIpQLSf7S36dyAUPx2egmXbFpnTBuzoRulhL5Elu-N1eoMhaO7v10w/formResponse)


## Table of contents 

1. [Project Description](#project-description) 
2. [Getting Started](#getting-started)
3. [Authors](#authors)
4. [Attribution](#attribution)

## Project Description 
-----------

The "Mafoko: South African Terminology, Lexicon, and Glossary Project" is dedicated to the comprehensive collection, meticulous cleaning, and transformative processing of South African language terminology lists, lexicons, and glossaries. This initiative is an integral part of the broader mission of the Data Science for Social Impact (DSFSI) lab/group, which aims to liberate and openly share as many language resources as possible.

The quality and accuracy of each resource are maintained by the original authors, ensuring the integrity and authenticity of the linguistic data. For any questions or clarifications regarding the content, users are encouraged to directly contact the original authors. By making these linguistic assets readily accessible, the project seeks to enhance language preservation, support linguistic research, and foster educational opportunities across South Africa's diverse linguistic landscape.

### Disclaimer

Each resource is provided on an “as is” basis, without representations, warranties or conditions of any kind, either express or implied including, without limitation, any warranties or conditions of title, non-infringement, merchantability or fitness for a particular purpose. We shall not have any liability for any form or type of damages (including without limitation lost profits), however caused and on any theory of liability, whether in contract, strict liability, or delict (including negligence or otherwise) arising in any way out of any of the resources, even if advised of the possibility of such damages. Likewise, to the full extent permitted by law, we shall not have any liability whatsoever for any mistakes in the source data or for any disputed translations.

Where any user finds technical mistakes or errors in the files, they may submit a request for fixes via Github. 

### Databases

| Database | Description | Documentation | CSV | JSON | TBX | xlsx |
|----------|-------------|---------------|-----|------|-----|------|
| OERTB | Open Resource Term Bank (OERTB) project is to support the collaborative development and dissemination of terminological resources, and thereby promoting the use of African languages in teaching and learning at higher education institutions. | TBD | [data/oertb/oertb-full.csv](https://github.com/dsfsi/za-mafoko/blob/master/data/oertb/oertb-full.csv), view on [datasette](https://lite.datasette.io/?csv=https://github.com/dsfsi/za-mafoko/blob/master/data/oertb/oertb-full.csv) | [data/oertb/oertb-termbank-IATE.json](https://github.com/dsfsi/za-mafoko/blob/master/data/oertb/oertb-termbank-IATE.json), view on [datasette](https://lite.datasette.io/?json=https://github.com/dsfsi/za-mafoko/blob/master/data/oertb/oertb-termbank-IATE.json) | [data/oertb/oertb-termbank-IATE.tbx](https://github.com/dsfsi/za-mafoko/blob/master/data/oertb/oertb-termbank-IATE) ||
| StatsSA | The Multilingual Statistical Terminology Project by Stats SA develops statistical terminology in South Africa's 11 official languages to enhance access to vital data for all citizens, ensuring a deeper understanding and connection to the information that affects their lives. | TBD | [data/stassa/multilingual_statistical_terminology_clean.csv](https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/multilingual_statistical_terminology_clean.csv), view on [datasette](https://lite.datasette.io/?csv=https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/multilingual_statistical_terminology_clean.csv) | [data/statssa/multilingual_statistical_terminology_clean.json](https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/multilingual_statistical_terminology_clean.json), view on [datasette](https://lite.datasette.io/?json=https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/multilingual_statistical_terminology_clean.json) ||[data/statssa/multilingual_statistical_terminology_clean.xlsx](https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/multilingual_statistical_terminology_clean.xlsx) |


## Licence

* All datasets, unless stated, are licensed under [Nwulite Obodo Open Data License - Version 1.0](https://licensingafricandatasets.com/nwulite-obodo-license)


## Getting Started
-----------
_This section provides the necessary information for a user to be able to run the code locally._


### Usage 


## Authors 
-----------

This repository is authored by the below team members. 

_Outside the PI and team lead, all other members are listed alphabetically by surname._

* Written by : Vukosi Marivate (PI)*, Fiskani Banda, Richard Lastrucci, Mohlatlego Nakeng, Kayode Olalaye, Thapelo Sindane
* Contact details : vukosi.marivate@cs.up.ac.za

### Contributions  

This is optional and provides information about which  and how each of the developers contributed. 

## Attribution

1. We ask you reference individual datasets you are using as well as this project.
2. For individual datasets, please refer to their READMEs in their  dataset folders. 

For the overall project the citation should be

```
@dataset{dsfsi-mafoko,
	date = {2023},
	title = {Mafoko: South African Terminology, Lexicon and Glossary Project},
	url = {https://github.com/dsfsi/za-mafoko/},
  author = {Vukosi Marivate and Fiskani Banda and Richard Lastrucci and Matome Ledwaba and Keabetswe Madumo and Mohlatlego Nakeng and Kayode Olalaye and Thapelo Sindane and DSFSI}
}
```

### DSAC Attribution

| Attribution Name                                                                                              | Dataset Link                                                                                          |
|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| [DSAC Election Terminology Attribution](./data/dsac/attribution-dsac-election-terminology-dictionary.md)                         | [Dataset](./data/dsac/dsac_election_terminology_dictionary.csv)                             |
| [DSAC Life Orientation Terminology Attribution](./data/dsac/attribution-dsac-life-orientation-terminology-term-list.md)          | [Dataset](./data/dsac/dsac_life_orientation_terminology_term_list.csv)                      |
| [DSAC Arts & Culture Terminology – Intermediate Phase Attribution](./data/dsac/attribution-dsac-multilingual-arts-&-culture-intermediate-phase-terminology-list.md) | [Dataset](./data/dsac/dsac_multilingual_arts_&_culture_intermediate_phase_terminology_list.csv) |
| [DSAC Engineering & Construction Terminology Attribution](./data/dsac/attribution-dsac-multilingual-engineering-and-construction-terminology.md) | [Dataset](./data/dsac/dsac_multilingual_engineering_and_construction_terminology.csv)       |
| [DSAC Financial Terminology Attribution](./data/dsac/attribution-dsac-multilingual-financial-terminology.md)                     | [Dataset](./data/dsac/dsac_multilingual_financial_terminology.csv)                          |
| [DSAC HIV and AIDS Terminology Attribution](./data/dsac/attribution-dsac-multilingual-hiv-and-aids-terminology.md)               | [Dataset](./data/dsac/dsac_multilingual_hiv_and_aids_terminology.csv)                       |
| [DSAC Human, Social, Economic & Management Sciences Terminology Attribution](./data/dsac/attribution-dsac-multilingual-human-social-economic-and-management-sciences-terminology.md) | [Dataset](./data/dsac/dsac_multilingual_human_social_economic_and_management_sciences_terminology.csv) |
| [DSAC ICT Dictionary Attribution](./data/dsac/attribution-dsac-multilingual-ict-dictionary.md)                                     | [Dataset](./data/dsac/dsac_multilingual_ict_dictionary.csv)                                 |
| [DSAC Mathematics Dictionary (Grades R–6) Attribution](./data/dsac/attribution-dsac-multilingual-mathematics-dictionary-r-to-6.md) | [Dataset](./data/dsac/dsac_multilingual_mathematics_dictionary_r_to_6.csv)                  |
| [DSAC Parliamentary Dictionary Attribution](./data/dsac/attribution-dsac-multilingual-parliamentary-dictionary.md)               | [Dataset](./data/dsac/dsac_multilingual_parliamentary_dictionary.csv)                       |
| [DSAC Soccer Terminology Attribution](./data/dsac/attribution-dsac-multilingual-soccer-terminology.md)                           | [Dataset](./data/dsac/dsac_multilingual_soccer_terminology.csv)                             |
| [DSAC Natural Science & Technology Term List – Nguni Languages Attribution](./data/dsac/attribution-dsac-natural-science-and-technology-term-list-nguni-languages.md) | [Dataset](./data/dsac/dsac_natural_science_and_technology_term_list_nguni_languages.csv)    |
| [DSAC Natural Sciences & Technology Dictionary – Sotho Attribution](./data/dsac/attribution-dsac-natural-sciences-and-technology-dictionary-sotho.md) | [Dataset](./data/dsac/dsac_natural_sciences_and_technology_dictionary_sotho.csv)            |
| [DSAC Natural Sciences & Technology (Grades 4–6) Attribution](./data/dsac/attribution-dsac-natural-sciences-and-technology-for-grade-4-to-6.md) | [Dataset](./data/dsac/dsac_natural_sciences_and_technology_for_grade_4_to_6.csv)            |
| [DSAC Pharmacy Terminology – First Edition Attribution](./data/dsac/attribution-dsac-pharmacy-first-edition.md)                  | [Dataset](./data/dsac/dsac_pharmacy_first_edition.csv)                                      |
| [DSAC Pharmacy Terminology – Second Edition Attribution](./data/dsac/attribution-dsac-pharmarcy-second-edition.md)               | [Dataset](./data/dsac/dsac_pharmarcy_second_edition.csv)                                    |

