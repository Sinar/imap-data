iMAP State of Internet Censorship data prepared for the reports available on https://imap.sinarproject.org/.


# 2023 reports

The 2023 report covers OONI data, for a period of 1 year from 1 July 2022 to 30 June 2023, as well as 10 countries: Cambodia, Hong Kong (China), India, Indonesia, Malaysia, Myanmar, Philippines, Thailand, Timor-Leste and Vietnam. 

**Files**
- *2023-iMAP-ASN-lookup*
- *2023-iMAP-Confirmed-blockings*
- *2023-iMAP-Instant-messaging-and-circumvention-tools*
- *2023-iMAP-Web-connectivity*


# 2022 reports

The 2022 report covers OONI data for a period of 6 months, from 1 January 2022 to 30 June 2022, as well as 8 countries: Cambodia, Hong Kong (China), Indonesia, Malaysia, Myanmar, Philippines, Thailand, and Vietnam. India is also part of the project but the report will only be available in the next round of reporting (2023). In the case of Hong Kong, the results of the heuristics showed external censorship from outside of the country instead of local censorship. Thus, the local researchers had analysed the OONI measurements manually to identify confirmed blockings. The domains identified were based on the timed-out instances. 

**Files**
- *recalculated_blockings*: Folder containing metadata of measurements recalculated based on heuristics. Full datasets are available on https://data.sinarproject.org/dataset/?_tags_limit=0&tags=OONI. 
- *jupyter_notebook*: Jupyter notebook used in running heuristics based on https://ooni.org/notebooks/tutorial-russia-data-analysis-case-study.html
- *heuristics_check.xlsx*: Sheet used in the heuristics i.e. identifying which IP address is true/false positive, which http title indicate a blockpage
- *confirmed_blockings*: Contain all domains which are confirmed blockings based on the heuristics
- *ASN_LOOKUP.xlsx*: Network name based on AS numbers 


