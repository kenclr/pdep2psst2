# Updating Supersense Field in PDEP
The Pattern Dictionary of English Prepositions (PDEP, <http://www.clres.com/db/TPPEditor.html>) contains a field that holds supersenses (version 1 as described in [1]). A second version is described in [2], [3], and [4]. Procedures for mapping from version 1 to version 2 are described in [5]. This repository contains a description of the analysis [5] and provides the files supporting the analysis. This is a __working paper__ that presents initial steps toward this mapping and provides several files for use in this process. Several further efforts are underway. Any comments, criticisms, and suggestions are __welcome__.

Files
-----
- ACKNOWLEDGMENTS.md: Contributors

Initial Data
------------
- prepwiki.json: Data used to fill the PDEP supersense field, using the TPP_PSST element identifying TPP senses and their supersenses, to synchonize PDEP and prepwiki (<http://www.clres.com/db/syncpsst.php> and <http://www.clres.com/db/syncpsst%20-%20Copy.php>). Also used PSST_SHORT_DEFS as the 75 supersense definitions in psst-v1-defs.txt.
- psst-v1-pdep-all.tsv: 581 PDEP senses for which supersense field was entered, with (1) the supersense, (2) the preposition, (3) the sense, and (4) the definition of the preposition's sense; created from pdeppsst-v1.tsv deleting senses without a supersense and then sorted by the supersenses (e.g., 28 senses with supersense __1DTrajectory__ and one sense with supersense __1DTrajectory,2DArea__
- psst-v1-pdep.txt: 143 distinct supersenses in PDEP (some with single supersense names and some with multiple "conflation" supersenses)
- pdep-no-psst.tsv: 458 PDEP senses not having a supersense, with (1) a tab, (2) the preposition, (3) the sense, and (4) the definition of the preposition's sense
- pdeppsst-v1.tsv: All 1075 PDEP senses in alphabetic order, with (1) the supersense, (2) the preposition, (3) the sense, and (4) the definition of the preposition's sense

Data for Mapping v1 to v2 Supersenses
-------------------------------------
- psst-v1-wiki.txt: Original 75 supersenses from the PrepWiki
- psst-v1-pdep-pure.txt: PDEP v1 supersense fields containing a single (pure) supersense
- psst-v1-pdep-conf.txt: PDEP v1 supersense fields containing a conflated supersense (containing two or more supersenses)
- psst-v1-defs.txt: Short definitions for the 75 v1 supersenses
- psst-v2.txt: The v2 supersenses (from [3])
- psst-v2-defs.tsv: Short definitions for the 50 v2 supersenses (from [3]), with (1) the hierarchical position for the supersense, (2) the supersense name, and (3) the definition from the supersense box

Mapping Analyses
----------------
- psst-v1-same.txt: The 36 supersenses having the same name in v1 and v2, with an assessment of their equality
- psst-v1-merged.txt: The 39 supersenses in v1 not in v2 and that need to be merged into v2, with an initial map from v1 to v2
- psst-v2-new.tsv: The 143 distinct PDEP v1 supersenses mapped into v2, characterizing the type of mapping, with (1) the type, (2) the number of PDEP senses with the v1 supersenses, (3) the original PDEP supersense, and (4) the potential v2 supersense
- psst-v2-refined.txt: The 127 distinct v2 supersenses mapped from the v1 supersenses
- psst-v2-final.txt: The 89 unique v2 supersenses (removing duplicates), with 37 pure supersenses and 52 conflated supersenses

Reference
---------
- [1] Nathan Schneider, Jena D. Hwang, Vivek Srikumar, Meredith Green, Abhijit Suresh, Kathryn Conger, Tim O'Gorman, and Martha Palmer. A corpus of preposition supersenses. _Proceedings of the 10th Linguistic Annotation Workshop_, Berlin, Germany, August 11, 2016. <http://people.cs.georgetown.edu/nschneid/p/psstcorpus.pdf>

- [2] Jena D. Hwang, Archna Bhatia, Na-Rae Han, Tim O’Gorman, Vivek Srikumar, and Nathan Schneider. Double trouble: the problem of construal in semantic annotation of adpositions. _Proceedings of the Sixth Joint Conference on Lexical and Computational Semantics_, Vancouver, British Columbia, Canada, August 3–4, 2017. <http://people.cs.georgetown.edu/nschneid/p/prepconstrual2.pdf>

- [3] Nathan Schneider, Jena D. Hwang, Archna Bhatia, Na-Rae Han, Vivek Srikumar, Tim O’Gorman, Sarah R. Moeller, Omri Abend, Austin Blodgett, and Jakob Prange (January 2, 2020). Adposition and Case Supersenses v2: Guidelines for English. arXiv preprint. <https://arxiv.org/abs/1704.02134>

- [4] Nathan Schneider, Jena D. Hwang, Vivek Srikumar, Jakob Prange, Austin Blodgett, Sarah R. Moeller, Aviram Stern, Adi Bitan, and Omri Abend. (2018). Comprehensive Supersense Disambiguation of English Prepositions and Possessives. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)_ Association for Computational Linguistics, Melbourne, Australia <http://aclweb.org/anthology/P18-1018>

- [5] Ken Litkowski. (2018) Updating Supersenses in the Preposition Pattern Dictionary. Working Paper 18-02. Damascus, MD: CL Research <http://www.clres.com/online-papers/PSST2.pdf> or <https://www.overleaf.com/read/xfdyswpwysjq> or <https://github.com/kenclr/pdep2psst2>

Contact
-------

Questions should be directed to:

Ken Litkowski
[ken@clres.com]()  
