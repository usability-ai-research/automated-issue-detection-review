# Advances in Automation and AI for Usability Issue Detection: Systematic Literature Review

## About

This repository contains the official materials for the research paper *"Advances in Automation and AI for Usability Issue Detection: Systematic Literature Review"*. The paper explores automated methods for detecting usability issues, offering a systematic literature review of 215 studies published between 2014 and 2026. It highlights research objectives, technologies, devices, data sources, technological maturity, the use of artificial intelligence, and the involvement of real participants across the publications.

### Paper citation

Not published yet.

### Contents

* [Data](#data)
* [Extended results](#extended-results)
* [Codes](#codes)
* [Authors](#authors)
* [License](#license)

## Data

The final [dataset](./data/publications.csv) contains 215 research publications with their bibliographic data and the fields extracted during the review. Multi-valued fields are separated by a semicolon (;):
| Column | Description |
| --- | --- |
| `title` | The full title of the publication. |
| `author` | The names of the authors who contributed to the publication. |
| `year` | The year the publication was released. |
| `type` | The category of the publication: `article` (journal article) or `inproceedings` (conference paper). |
| `volume` | The volume number in which the publication appears, if available. |
| `number` | The issue number within the journal or proceedings, if available. |
| `pages` | The page range of the publication, if available. |
| `venue` | The name of the journal or conference where the publication was published. |
| `venueShort` | The abbreviation of the conference name, if available. |
| `publisher` | The name of the publisher, unified as it appears in the Journal Citation Reports. |
| `doi` | The Digital Object Identifier (DOI) of the publication. |
| `url` | The URL of the publication or the publisher's webpage. |
| `abstract` | The abstract of the publication. |
| `keywords` | The key terms that describe the main topics of the publication. |
| `citedBy` | The number of citations on Google Scholar (retrieved 2026-10-12). |
| `citedByPerYear` | The number of citations divided by the years since publication. |
| `quality` | The best journal quartile (`Q1`–`Q3`) or conference rank (`A*`, `A`, `B`) of the venue in the publication year. |
| `objective` | The research objective of the publication (single value, see [Codebook](#codebook)). |
| `technology` | The technologies utilized in the publication (multiple values). |
| `data` | The data sources used in the publication (multiple values). |
| `device` | The device types for which the approach was examined (multiple values). |
| `maturity` | The technological maturity of the approach (single value). |
| `participants` | Whether the approach relies on real participants. |


## Codes
 
Objectives, maturity and participant involvement were coded as single values. Technology, data sources and devices were coded as multiple values.
 
| Field | Codes |
| --- | --- |
| `objective` | Aesthetics evaluation, Affective state detection, Automated feedback generation, Automatic guideline evaluation, Feedback evaluation, Perceived affordance evaluation, Research assistants, Usability attribute evaluation, Usability issue encounter detection, Visual complexity evaluation |
| `technology` | Machine learning, Deep learning, LLM, Rule-based systems, Computer vision, Descriptive metrics, NLP, Chatbots, Log-based sequence & pattern mining |
| `data` | User interactions, Source code, Images, Video, Text, Physiological signals, Audio, User movements, Gaze data, None |
| `device` | Desktop, Mobile, Consumer electronics, Wearables, VR, Device independent |
| `maturity` | Concept, Prototype, Tool, Existing tools |
| `participants` | dependent, independent |



## Authors

### General contact 

Email: 
**usability.ai.research@gmail.com**


**Eduard Kuric**\
He is a researcher and lecturer at [Faculty of Informatics and Information Technologies](https://www.fiit.stuba.sk/), [Slovak University of Technology in Bratislava](https://www.stuba.sk/). His research interests include human-computer interaction analysis, user modeling, personalized web-based systems, and machine learning. Eduard is also the head of the UX Research Department and the founder of [UXtweak](https://www.uxtweak.com/).
- [LinkedIn](https://www.linkedin.com/in/eduard-kuric-b7141280/)
- [Google Scholar](https://scholar.google.com/citations?user=MwjpNoAAAAAJ&hl=en&oi=ao)
- Email: eduard.kuric([AT])stuba.sk

**Peter Demcak**\
Researcher with background in software engineering, whose current topics of interest involve user behavior, human-computer interaction, UX research methods and design practices, and machine learning. Currently occupies the position of a scientific and user experience researcher at [UXtweak](https://www.uxtweak.com/), with focus on research that supports work of UX professionals.

- Email: peter.demcak([AT])uxtweak.com

**Matus Krajcovic**\
User experience researcher at [UXtweak](https://www.uxtweak.com/) and PhD student in computer science at [Faculty of Informatics and Information Technologies](https://www.fiit.stuba.sk/), [Slovak University of Technology in Bratislava](https://www.stuba.sk/). Currently focuses on data analysis and research in machine learning use in the field of human-computer interaction.
- Email: matus.krajcovic([AT])uxtweak.com

**Jan Lang**\
He is an associate professor, teacher and researcher at I[Faculty of Informatics and Information Technologies](https://www.fiit.stuba.sk/), [Slovak University of Technology in Bratislava](https://www.stuba.sk/). His research interests involve object-oriented analysis and design, software engineering, complex event processing, educational content specification and modelling, learning management and content management.

- Email: jan.lang([AT])stuba.sk

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

[![Creative Commons License](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)