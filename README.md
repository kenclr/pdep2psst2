# Updating Supersense Field in PDEP
Updating supersenses from Schneider et al.

Each PP idiom consists of a multiple word expression (MWE), i.e., containing at least two words. Idioms were obtained from ODE entries either beginning or ending with a preposition from the Pattern Dictionary of English Prepositions (PDEP, <http://www.clres.com/db/TPPEditor.html>). This repository contains a description of the analysis [1] and provides the files supporting the analysis.

This paper characterizes PP idioms, identifies the idiom inventories, discusses their occurrence in the PDEP corpora, identifies entries and senses missing from PDEP, describes how to incorporate new data into PDEP, and considers potential expansion of PDEP corpora. The paper examines the PP idioms in the supersense reviews corpus (<https://github.com/nert-gu/streusle>) in the light of these results.

This paper is a __working paper__. It describes several steps that have been taken in mapping from  not the ultimate consideration of PP idioms, but rather liberally identifies further work that is intended. Any comments, criticisms, and suggestions are __welcome__.

Files
-----
- ACKNOWLEDGMENTS.md: Contributors inspiring this research

Initial Data
------------
- pp-begin.txt: 2484 entries beginning with a PDEP preposition (potentially idiomatic), with senses, a part of speech, and a definition
- pp-final.txt: 2785 entries ending with a PDEP preposition (potentially idiomatic), with senses, a part of speech, and a definition

Data for Beginning PP Idioms
----------------------------

Data for Ending PP Idioms
-------------------------

Data for PP Idioms in Streusle Corpus
-------------------------------------
- Streusle-4.0.PPIdioms.parse: The 170 lines from the Streusle parses that have a LEXLEMMA PP (13th column), indicating that the annotators felt the presence of PP idiom
- Streusle-4.0.PPIdioms-sorted.tsv: Parsed lines from above sorting the PP idioms
- Streusle-4.0.PPIdioms-unique.tsv: List of the 95 unique idioms in these lines
- Streusle-4.0.PPIdioms-stats.tsv: Statistics about the 95 idioms: a count of their frequency, whether having different role and function supersenses, whether found in a dictionary, and comments about the idiom if not found in the dictionary
- Streusle-4.0.PPIdioms-analysis.tsv: Summary analysis for each idiom whether found and analysis in two dictionaries
- Streusle-4.0.PPIdioms-construal.tsv: Role and function supersenses for each idiom (highlighting differences)

Reference
---------
- [1] Ken Litkowski. (2018) Updating Supersenses in the Preposition Pattern Dictionary. Working Paper 18-02. Damascus, MD: CL Research <http://www.clres.com/online-papers/PSST2.pdf> or <https://www.overleaf.com/read/xfdyswpwysjq> or <https://github.com/kenclr/pdep2psst2>

- [5] Nathan Schneider, Jena D. Hwang, Archna Bhatia, Na-Rae Han, Vivek Srikumar, Tim O’Gorman, Sarah R. Moeller, Omri Abend, Austin Blodgett, and Jakob Prange (July 2, 2018). Adposition and Case Supersenses v2: Guidelines for English. arXiv preprint. <https://arxiv.org/abs/1704.02134>

- __[7] Nathan Schneider, Jena D. Hwang, Vivek Srikumar, Jakob Prange, Austin Blodgett, Sarah R. Moeller, Aviram Stern, Adi Bitan, and Omri Abend. Comprehensive supersense disambiguation of English prepositions and possessives. _Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics_, Melbourne, Australia, July 15–20, 2018. <http://people.cs.georgetown.edu/nschneid/p/pssdisambig.pdf>__

Contact
-------

Questions should be directed to:

Ken Litkowski
[ken@clres.com]()  
