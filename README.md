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

| Database | Description | Documentation | CSV | JSONL |
|----------|-------------|---------------|-----|-------|
| DSAC | Department of Sports, Arts and Culture (DSAC) project is to support the collaborative development and dissemination of terminological resources, and thereby promoting the use of African languages in teaching and learning at higher education institutions. | [README](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/README.md) | [data/dsac/combined_dsac.csv](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/combined/combined_dsac.csv),<br>view on [datasette](https://lite.datasette.io/?csv=https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/combined/combined_dsac.csv) | [data/dsac/combined_dsac.jsonl](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/combined/combined_dsac.jsonl),<br>view on [datasette](https://lite.datasette.io/?json=https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/combined/combined_dsac.jsonl) | 
| StatsSA | The Multilingual Statistical Terminology Project by Stats SA develops statistical terminology in South Africa's 11 official languages to enhance access to vital data for all citizens, ensuring a deeper understanding and connection to the information that affects their lives. | [README](https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/README.md) | [data/statssa/statssa_multilingual_statistical_terminology.csv](https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/statssa_multilingual_statistical_terminology.csv), view on [datasette](https://lite.datasette.io/?csv=https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/statssa_multilingual_statistical_terminology.csv) | [data/statssa/statssa_multilingual_statistical_terminology.jsonl](https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/statssa_multilingual_statistical_terminology.jsonl), view on [datasette](https://lite.datasette.io/?json=https://github.com/dsfsi/za-mafoko/blob/master/data/statssa/statssa_multilingual_statistical_terminology.jsonl) |
| UNISA Multilingual | The South African Multilingual Linguistic Terminology (SAMLT) Project is a comprehensive multilingual termbank containing 500 linguistic terms translated across nine South African languages. Each term includes translations by field experts, accompanied by concise definitions and usage examples to clarify technical linguistic concepts for classroom and academic use. This resource addresses the critical need for standardized linguistic terminology in African languages, supporting linguistics education and research across South Africa's diverse linguistic landscape. | [README](https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_multilingual/README.md) | [data/unisa_multilingual/unisa_multilingual_linguistic_terminology.csv](https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_multilingual/unisa_multilingual_linguistic_terminology.csv), view on [datasette](https://lite.datasette.io/?csv=https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_multilingual/unisa_multilingual_linguistic_terminology.csv)   | [data/unisa_multilingual/unisa_multilingual_linguistic_terminology.jsonl](https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_multilingual/unisa_multilingual_linguistic_terminology.jsonl), view on [datasette](https://lite.datasette.io/?json=https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_multilingual/unisa_multilingual_linguistic_terminology.jsonl) |
| UNISA Robotics  | The UNISA Multilingual Robotics Glossary is a comprehensive collection of approximately 100 robotics and engineering terminology entries translated across South Africa's 11 official languages. This glossary was developed by the University of South Africa (UNISA) through its Inspired towards Science, Engineering and Technology (I-SET) program, in collaboration with the Department of Linguistics and Modern Languages and the Department of African Languages. This resource aims to make robotics education accessible in mother-tongue languages throughout South Africa, supporting STEM education and bridging the gap between technical terminology and linguistic diversity. | [README](https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_robotics/README.md) | [data/unisa_robotics/unisa_robotics_multilingual_glossary.csv](https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_robotics/unisa_robotics_multilingual_glossary.csv), view on [datasette](https://lite.datasette.io/?csv=https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_robotics/unisa_robotics_multilingual_glossary.csv) | [data/unisa_robotics/unisa_robotics_multilingual_glossary.jsonl](https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_robotics/unisa_robotics_multilingual_glossary.jsonl), view on [datasette](https://lite.datasette.io/?json=https://github.com/dsfsi/za-mafoko/blob/master/data/unisa_robotics/unisa_robotics_multilingual_glossary.jsonl) |
| UP Glossary | The University of Pretoria Multilingual Academic Glossaries project promotes access to academic terminology in Afrikaans, English, and Northern Sotho to support multilingual teaching and learning, fostering inclusivity and linguistic diversity in higher education. | [README](https://github.com/dsfsi/za-mafoko/blob/master/data/up_glossary/README.md) | [data/up_glossary/combined/combined_up_glossary.csv](https://github.com/dsfsi/za-mafoko/blob/master/data/up_glossary/combined/combined_up_glossary.csv), view on [datasette](https://lite.datasette.io/?csv=https://github.com/dsfsi/za-mafoko/blob/master/data/up_glossary/combined/combined_up_glossary.csv) | [data/up_glossary/combined/combined_up_glossary.jsonl](https://github.com/dsfsi/za-mafoko/blob/master/data/up_glossary/combined/combined_up_glossary.jsonl), view on [datasette](https://lite.datasette.io/?json=https://github.com/dsfsi/za-mafoko/blob/master/data/up_glossary/combined/combined_up_glossary.jsonl) |
| OERTB | Open Resource Term Bank (OERTB) project is to support the collaborative development and dissemination of terminological resources, and thereby promoting the use of African languages in teaching and learning at higher education institutions. | TBA | TBA |TBA |

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

```
@article{marivate2025mafokostructuringbuildingopen,
title={Mafoko: Structuring and Building Open Multilingual Terminologies for South African NLP}, 
author={Vukosi Marivate and Isheanesu Dzingirai and Fiskani Banda and Richard Lastrucci and Thapelo Sindane and Keabetswe Madumo and Kayode Olaleye and Abiodun Modupe and Unarine Netshifhefhe and Herkulaas Combrink and Mohlatlego Nakeng and Matome Ledwaba},
year={2025},
eprint={2508.03529},
archivePrefix={arXiv},
primaryClass={cs.CL},
url={https://arxiv.org/abs/2508.03529}, 
}
```

### DSAC Attribution

| Attribution Name                                                                                              | Dataset Link                                                                                          |
|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| [DSAC Election Terminology Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-election-terminology-dictionary.md)                         | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_election_terminology_dictionary.csv)                             |
| [DSAC Life Orientation Terminology Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-life-orientation-terminology-term-list.md)          | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_life_orientation_terminology_term_list.csv)                      |
| [DSAC Arts & Culture Terminology – Intermediate Phase Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-arts-&-culture-intermediate-phase-terminology-list.md) | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_arts_&_culture_intermediate_phase_terminology_list.csv) |
| [DSAC Engineering & Construction Terminology Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-engineering-and-construction-terminology.md) | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_engineering_and_construction_terminology.csv)       |
| [DSAC Financial Terminology Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-financial-terminology.md)                     | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_financial_terminology.csv)                          |
| [DSAC HIV and AIDS Terminology Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-hiv-and-aids-terminology.md)               | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_hiv_and_aids_terminology.csv)                       |
| [DSAC Human, Social, Economic & Management Sciences Terminology Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-human-social-economic-and-management-sciences-terminology.md) | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_human_social_economic_and_management_sciences_terminology.csv) |
| [DSAC ICT Dictionary Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-ict-dictionary.md)                                     | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_ict_dictionary.csv)                                 |
| [DSAC Mathematics Dictionary (Grades R–6) Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-mathematics-dictionary-r-to-6.md) | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_mathematics_dictionary_r_to_6.csv)                  |
| [DSAC Parliamentary Dictionary Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-parliamentary-dictionary.md)               | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_parliamentary_dictionary.csv)                       |
| [DSAC Soccer Terminology Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-multilingual-soccer-terminology.md)                           | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_multilingual_soccer_terminology.csv)                             |
| [DSAC Natural Science & Technology Term List – Nguni Languages Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-natural-science-and-technology-term-list-nguni-languages.md) | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_natural_science_and_technology_term_list_nguni_languages.csv)    |
| [DSAC Natural Sciences & Technology Dictionary – Sotho Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-natural-sciences-and-technology-dictionary-sotho.md) | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_natural_sciences_and_technology_dictionary_sotho.csv)            |
| [DSAC Natural Sciences & Technology (Grades 4–6) Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-natural-sciences-and-technology-for-grade-4-to-6.md) | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_natural_sciences_and_technology_for_grade_4_to_6.csv)            |
| [DSAC Pharmacy Terminology – First Edition Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-pharmacy-first-edition.md)                  | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_pharmacy_first_edition.csv)                                      |
| [DSAC Pharmacy Terminology – Second Edition Attribution](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/attribution-dsac-pharmarcy-second-edition.md)               | [CSV Dataset](https://github.com/dsfsi/za-mafoko/blob/master/data/dsac/dsac_pharmarcy_second_edition.csv)                                    |

