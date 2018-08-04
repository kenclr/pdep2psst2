# Updating Supersense Field in PDEP
Updating supersenses from Schneider et al.

Each PP idiom consists of a multiple word expression (MWE), i.e., containing at least two words. Idioms were obtained from ODE entries either beginning or ending with a preposition from the Pattern Dictionary of English Prepositions (PDEP, <http://www.clres.com/db/TPPEditor.html>). This repository contains a description of the analysis [1] and provides the files supporting the analysis.

This paper characterizes PP idioms, identifies the idiom inventories, discusses their occurrence in the PDEP corpora, identifies entries and senses missing from PDEP, describes how to incorporate new data into PDEP, and considers potential expansion of PDEP corpora. The paper examines the PP idioms in the supersense reviews corpus (<https://github.com/nert-gu/streusle>) in the light of these results.

This paper is a __working paper__. It describes several steps that have been taken in mapping from  not the ultimate consideration of PP idioms, but rather liberally identifies further work that is intended. Any comments, criticisms, and suggestions are __welcome__.

Files
-----
- ACKNOWLEDGMENTS.md: Contributors

Initial Data
------------
- prepwiki.json: Data used to fill the PDEP supersense field, using the TPP_PSST element identifying TPP senses and their supersenses, to synchonize PDEP and prepwiki (<http://www.clres.com/db/syncpsst.php> and <http://www.clres.com/db/syncpsst%20-%20Copy.php>). Also used PSST_SHORT_DEFS as the 75 supersense definitions in psst-v1-defs.txt.
- pp-final.txt: 2785 entries ending with a PDEP preposition (potentially idiomatic), with senses, a part of speech, and a definition

Data for Mapping v1 to v2 Supersenses
-------------------------------------
- psst-v1-defs.txt: Short definitions for the 75 v1 supersenses


Reference
---------
- [1] Ken Litkowski. (2018) Updating Supersenses in the Preposition Pattern Dictionary. Working Paper 18-02. Damascus, MD: CL Research <http://www.clres.com/online-papers/PSST2.pdf> or <https://www.overleaf.com/read/xfdyswpwysjq> or <https://github.com/kenclr/pdep2psst2>

- [4] Jena D. Hwang, Archna Bhatia, Na-Rae Han, Tim O’Gorman, Vivek Srikumar, and Nathan Schneider. Double trouble: the problem of construal in semantic annotation of adpositions. _Proceedings of the Sixth Joint Conference on Lexical and Computational Semantics_, Vancouver, British Columbia, Canada, August 3–4, 2017. <http://people.cs.georgetown.edu/nschneid/p/prepconstrual2.pdf>

- [5] Nathan Schneider, Jena D. Hwang, Archna Bhatia, Na-Rae Han, Vivek Srikumar, Tim O’Gorman, Sarah R. Moeller, Omri Abend, Austin Blodgett, and Jakob Prange (July 2, 2018). Adposition and Case Supersenses v2: Guidelines for English. arXiv preprint. <https://arxiv.org/abs/1704.02134>

- __[7] Nathan Schneider, Jena D. Hwang, Vivek Srikumar, Jakob Prange, Austin Blodgett, Sarah R. Moeller, Aviram Stern, Adi Bitan, and Omri Abend. Comprehensive supersense disambiguation of English prepositions and possessives. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics_, Melbourne, Australia, July 15–20, 2018. <http://people.cs.georgetown.edu/nschneid/p/pssdisambig.pdf>__

Contact
-------

Questions should be directed to:

Ken Litkowski
[ken@clres.com]()  
