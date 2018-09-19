# impact of children

Data for our paper "The impact of caring for children on women’s research output: a retrospective cohort study". Currently under review with _PLOS ONE_.

The file `individual.papers.csv` contains one row per paper per researcher and is used to examine the collaboration data. The variables are:
* num: researcher ID number
* career.year: years since first paper
* year: calendar year
* first.author: researcher was first author (TRUE/FALSE)
* last.author: researcher was last author (TRUE/FALSE)
* n_affils: number of affliations on the paper
* n_not.australia: number of affliations outside Australia
* baby.flag: flag for first baby (0 = no baby at this time, 1 = baby at this time)
* years.since: years since first baby
* baby.flag2: flag for second baby
* years.since2: years since second baby (0 = no baby at this time, 1 = baby at this time)

The file `individual.papers.csv` contains one row per year per researcher and is used to examine the research output data. The variables are:
* num: researcher ID number
* career.year: years since first paper
* year: calendar year
* papers: yearly number of papers
* citations: yearly number of Scopus citations
* baby.flag: flag for first baby (0 = no baby at this time, 1 = baby at this time)
* years.since: years since first baby
* baby.flag2: flag for second baby
* years.since2: years since second baby (0 = no baby at this time, 1 = baby at this time)
