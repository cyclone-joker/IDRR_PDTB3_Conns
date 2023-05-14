# IDRR_PDTB3_Conns
PDTB 3.0 Selected Connectives for IDRR Connective Classification.

**Paper**: ACL 2023-Infusing Hierarchical Guidance into Prompt Tuning: A Parameter-Efficient Framework for Multi-level Implicit Discourse Relation Recognition

**Introduction**: In order to analyse the effectiveness of our PEMI model on PDTB 3.0 database, we select 185 connectives from PDTB 3.0 "Implicit" instances. However, the annotation of connectives for PDTB3.0 is really different from that of PDTB 2.0, which results in a lack of samples for many categories and even exists no sample on the dev and test sets. Therefore, we simply merge some of them according to the semantics and obtain 150 connectives. (We have only merged the connectives that are determined to be in the same category. And this does not represent the final version of a complete merger.)

In `pdtb3_implicit_connectives.xlsx`, the column `raw_connective` means the raw connectives that we extract from PDTB 3.0 "Implicit" instances. And the column `connective` is the corresponding connectives we merged.
