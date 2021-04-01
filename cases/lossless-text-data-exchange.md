# Information lossless text data exchange

## Metadata

* **Status:**  In Progress
* **Type:** Generic
* **Work Package**: WP6
* **Research Coordinators:**  Dirk Roorda (DANS)
* **Coordinators for CLARIAH:**  Joris van Zundert (Huygens ING)
* **Participating Institutes:** DANS, HuC-DI, INT
* **End-users**: 
* **Developers**: Dirk Roorda (DANS)
* **Interest Groups**: Ann, TP
* **Task IDs**:

## Description

A long standing problem is the lack of a academically wide accepted standard to address arbitrary parts of “a text”. This is a thorny problem as perspectives on what “the text” is, vary from researcher to researcher and from context to context. The problem is aggravated by the fact that it is common research practice and pragmatism to remove existing annotation data from digital texts and to add new annotation layers without concern for annotation and text legacy. Also many domain specific communities and projects (e.g. W3C web annotation, TEI, LAF, FOLIA, The Codex, TAG-ML to name but a few) have proposed pragmatic but very different standards to link annotations to parts of texts. 
These practices are defendable on the basis of specific research aims, but questionable with regard to uniquely identifiable and addressable text data, information, and annotation. Ideally we would have a common text coordinate system that is community standard agnostic and that may thus allow seamless transformation from one community specific standard to another. Or there might be a Pandoc (https://pandoc.org/) like solution, but one that guarantees information-losslessness. Alternatively a blockchain like solution might turn out to be the most practical and pragmatic solution.
In Work Package 6 “Text” of the CLARIAH-PLUS project one goal is to investigate different solutions for this problem and to what extent they could be integrated and advocated through CLARIAH-PLUS infrastructure. Solutions (non-exhaustively listed here) that may be explored are “turntable”, “blockchain”, and “common coordinates” solutions.

### What is the research about?

The objective of this Use Case is not to come up with a begin-all end-all solution for this problem, as the problem transcends CLARIAH+ to a large extent. However, with TextFabric Dirk Roorda has created an effective way of tending to the “coordinate needs” of smaller communities and individual researchers that face very particular ancient, fossilized, or small languages and text collections. Dirk’s approach (and TextFabric’s technology) make the needs and requirements of such users clearly and urgently visible at the level of community standard development.

### What is needed to do the research?

There are a dozen corpora in Text-Fabric, some of which are “canonical” texts, e.g. Dead Sea Scrolls, Quran, Old Babylonian Cuneiform Tablets. (See the CLARIAH tool/data list compiled by Jan Odijk)
Having these corpora in Text-Fabric means that we can produce multiple exports while preserving the capacity of addressing all items in the text, down to the word/character level.
We can use that to produce derived datasets of these corpora that can be handled by other tools.
One of those tools is Blacklab, developed at INT, which leverages the power of full-text search to not only text but also their annotations. We plan to make several Text-Fabric corpora available in Blacklab.

#### Data

1. The General Missives (for which Dirk already has produced much cleaner data than existed, which is already in Text-Fabric). The General Missives are the subject of WP6-Use Case 1
2. The NENA corpus (https://github.com/CambridgeSemiticsLab/nena ), a native speaker corpus of Neo-Aramaic, phonologically marked up. It is already in Text-Fabric, it is a growing corpus under development, and Dirk is paid by Cambridge to provide it with a search interface. Blacklab seems to be a good first shot, but probably we do need add-ons.
3. The Fusus corpus (https://github.com/among/fusus). An Arabic corpus which is being developed by Dirk and Cornelis van Lit (https://github.com/among/digitized-manuscripts Univ. Utrecht). It consists of commentary texts on a classic mystico-philosophical work by Ibn Arabi. We are working from printed pages, do OCR, and preserve the outcome in Text-Fabric. Cornelis will do data oriented research on it, but in order to cater for a wider public, a blacklab like interface is desirable. Dirk is paid by Utrecht to produce this corpus.
4. The Hebrew Bible. The BHSA (https://github.com/ETCBC/bhsa) is a mature text-fabric representation of the Biblia Hebraica Stuttgartensia and is used in Biblical research. Recently Martijn Naaijer got his Ph.D. cum laude for his thesis in which he applies machine learning to rank the books of the bible in time. The BHSA is online through SHEBANQ, a DANS service built for CLARIN, which is in continued use for research and education. In order to explore alternative interfaces, it would be welcome to have the BHSA available in a Blacklab interface. Even better, the Dead Sea Scrolls (https://github.com/ETCBC/dss), which overlap with the BHSA but date from much earlier, are a case in point where focused linguistic annotations on one source are being transferred to another source.

### What software and services are involved?

Amongst others:

- TextFabric
- Blacklab

This use case is related in interesting ways to the use case "Annotatable collections". It starts with TextFabric collections that are already separated in text plus text coordinates plus annotations that refer to these coordinates, and feeds this collection data to existing CLARIAH tooling and infrastructure. The "Annotatable collections" use case intends to do the reverse: start with existing online collections and present them online as text plus text coordinates that can subsequently be used for online annotation scenarios.

## References

References to related resources and publications and especially links to related use-cases:

* [CLARIAH](https://clariah.nl)

