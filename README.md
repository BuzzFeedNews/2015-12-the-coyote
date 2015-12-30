# Data and Analysis for "The Coyote"

This repository contains data and analysis associated with the [BuzzFeed News article, "The Coyote,"](http://www.buzzfeed.com/kenbensinger/the-coyote) published December 29, 2015.

- [Data](#data)
- [Analyses](#analyses)
- [Reproducing These Analyses](#reproducing-these-analyses)

## Data

The analyses in this repository use visa-certification data published by the [Department of Labor's Office of Foreign Labor Certification (OFLC)](https://www.foreignlaborcert.doleta.gov/performancedata.cfm). The OFLC publishes spreadsheets detailing its decisions about whether to approve ("certify") employers to bring H-2 guest workers to the United States. H-2 visas come in two types: H-2A for agricultural workers and H-2B for non-agricultural unskilled workers. The Department of Labor's data covers __H-2A decisions since FY 2006__ and __H-2B decisions since FY 2000__. The most recent data, for both visa types, includes data  __through FY 2015__, which concluded on Sept. 30, 2015.

The raw data were collected from two sites — [doleta.gov](http://www.foreignlaborcert.doleta.gov/performancedata.cfm) and [fldatacenter.com](http://www.flcdatacenter.com/) — and were then processed into a standardized format. You can find that raw data, the processing scripts, and additional details [here](https://github.com/buzzfeednews/H-2-certification-data).

## Analyses

- __Passage__: "[...] over more than a quarter of a century, [Eury] has been responsible for procuring hundreds of thousands of Mexican workers on H-2 visas [...]"
- __Analysis__: In just the 10 years since fiscal year 2006 — the earliest fiscal year for which both H-2A and H-2B certification data is available — Eury-controlled businesses have received approval for at least 213,000 H-2 visas. [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "Last year, Eury’s companies were approved for more than 20,000 visas [...]"
- __Analysis__: [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "Soon [ILMC] was helping clients gain approval for thousands of visas every year."
- __Analysis__: In each fiscal year between FY 2000 and FY 2009, ILMC's H-2 applications were certified for more than 4,000 workers. [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "[...] the North Carolina Growers Association often requested more than 80% of all agricultural guest worker visas in North Carolina."
- __Analysis__: For example, approximately 90% in FY 2007 and 86% in FY 2011. [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "For years, employers in North Carolina obtained approvals for more such guest worker visas than employers in any other state."
- __Analysis__: For each fiscal year between FY 2007 and FY 2014, worksites listed in North Carolina accounted for more H-2A certifications than any other state. [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "In the 12-month period starting July 2014, the growers association got permission to import more than 12,000 guest workers for jobs in North Carolina."
- __Analysis__: [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "Even with more competition, in 2011, [Eury] was still responsible for securing one in eight of all H-2 guest worker visa certifications."
- __Analysis__: In 2011, Eury's businesses accounted for approximately 18,085 of 144,602 H-2 certifications, or 12.5%. [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "In a typical year [Eury's] companies meet the labor needs of clients across more than 20 states."
- __Analysis__: E.g., according to OFLC data: 31 worksite states in FY 2011, 31 in FY 2012: 31 states; 23 in FY 2013; 30 in FY 2014; 20 in FY 2015. [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "The North Carolina Growers Association has continued to get visas approved for Walker Farms, more than 90 since Ordaz died, including 13 this year."
- __Analysis__: [A list of those certifications can be found here.](notebooks/analysis.ipynb)

---

- __Passage__: "International Labor Management was a major player, helping clients get approval for as many as 5,000 visas a year."
- __Analysis__: In both FY 2005 and FY 2006, ILMC helped clients get approval for more than 5,000 H-2 visas. [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "But it took the Labor Department 10 days [after ILMC pleaded guilty on July 22nd] to follow through — and in that time the agency approved at least 12 of the company’s visa applications for a total of more than 400 workers."
- __Analysis__: [A list of those certifications can be found here.](notebooks/analysis.ipynb)

---

- __Passage__: "And [Wicker] kept submitting the association’s visa applications for more than four months — 20 applications in all, for a total of 3,887 workers."
- __Analysis__: [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "Since [August 3, 2014, National Agricultural Consultants] has won approval for 5,100 H-2 visas, federal data show [...]"
- __Analysis__: [Details here.](notebooks/analysis.ipynb)

---

- __Passage__: "[...] its 10 largest clients had all previously gotten visas through International Labor Management."
- __Analysis__: [A list of those companies, and their previous ILMC certifications can be found here.](notebooks/analysis.ipynb)

---

- __Passage__: "Since Eury was first indicted [on Jan. 31, 2014], the [NCGA] has won approval for at least 22,000 visas."
- __Analysis__: [Details here.](notebooks/analysis.ipynb)


## Reproducing These Analyses

This repository contains all the data and code necessary to reproduce the analyses above. In theory, it should be possible to perform the analysis in any computer language or statistical program. We performed our analysis in Python. To re-run it you'll need Python 3 and the libraries listed in [`requirements.txt`](requirements.txt).

## Other Analyses From BuzzFeed News

You can find a regularly-updated index of our open-source data and analyses here: [github.com/BuzzFeedNews/everything](https://github.com/BuzzFeedNews/everything)

## Questions / Feedback?

Email Jeremy Singer-Vine at jeremy.singer-vine@buzzfeed.com
