On the need for configurable travel recommender systems:  
A systematic mapping study
=====================================================================================

Introduction
------------

This page provides the replication package for the paper titled "**On the need for configurable travel recommender systems: A systematic mapping study**". The replication package includes all the necessary resources and instructions to reproduce the mapping study presented in the paper. This paper aims to map studies under the travel recommender systems (TRS) field, with a focus on the configurability these systems offer to providers. It assists in identifying relevant works in the literature and analyzes challenges that are worth to be investigated by researchers and practitioners. Eventually, future work directions are proposed, aiming to provide more support to TRSs providers.

Research queries
----------------

For this paper, we searched for terms related to the work in the domain of travel recommender systems, narrowing it down to configurable (and similar terms) recommender (and similar terms) systems for tourism (and similar terms). The search includes the titles of works, their abstracts, and keywords, to support our analysis effectively. Moreover, we limit our query to works published within the past 10 years considering journal and conference papers. We execute our final query on three digital libraries: Scopus, IEEE, and DBLP. It is possible to visualize the queries for the respective libraries below:

**SCOPUS**

*TITLE-ABS-KEY ( configurable OR personali\* OR customi\* ) AND (TITLE-ABS-KEY (recommender OR advis\* OR assist\* OR suggest\*)) AND TITLE-ABS-KEY-AUTH((tourism OR eTourism) AND travel) AND ( LIMIT-TO ( SUBJAREA,"COMP" ) ) AND ( LIMIT-TO ( PUBYEAR,2013) OR LIMIT-TO ( PUBYEAR,2014) OR LIMIT-TO ( PUBYEAR,2015) OR LIMIT-TO ( PUBYEAR,2016) OR LIMIT-TO ( PUBYEAR,2017) OR LIMIT-TO ( PUBYEAR,2018) OR LIMIT-TO ( PUBYEAR,2019) OR LIMIT-TO ( PUBYEAR,2020) OR LIMIT-TO ( PUBYEAR,2021) OR LIMIT-TO ( PUBYEAR,2022) OR LIMIT-TO ( PUBYEAR,2023) ) AND ( LIMIT-TO ( LANGUAGE,"English" ) ) AND ( LIMIT-TO ( EXACTKEYWORD,"Recommender Systems" ) OR LIMIT-TO ( EXACTKEYWORD,"Advis\*" ) OR LIMIT-TO ( EXACTKEYWORD,"Tourism" ) OR LIMIT-TO ( EXACTKEYWORD,"Assist\*" ) OR LIMIT-TO ( EXACTKEYWORD,"Suggesti\*" ) )*

**IEEE**

*(("All Metadata": configurable OR personali\* OR customi\*) AND ("All Metadata": recommender OR advis\* OR assist\* OR suggest\*) AND (("All Metadata": tourism OR eTourism) AND travel))*
> In the IEEE library, the time range filter must be applied right after fetching all the results since the library does not contain a command to do so directly through the query.

**DBLP**

*configurable | personali | customi recommender | advis | assist | suggest tourism | eTourism*
> In the DBLP library, the time range filter must be applied right after fetching all the results since the library does not contain a command to do so directly through the query.

Replication package
-------------------

The list of all the papers retrieved from the queries is available for download <a href="https://file.io/AF1NJid5Z2I7" title="Download" download>here</a> and in this repository in the file named _papers_list.xlxs_. The spreadsheet is divided into three tabs:

- All retrieved papers
  > This list contains the raw data retrieval with all the papers fetched using the available queries above.
- Retrieved papers without duplicated ones
  > This list contains the works after the removal of duplicated ones across digital libraries.
- Final selection
  > This list contains the final works selected based on the inclusion and exclusion criteria explained in the paper.
