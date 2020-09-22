# dataset_mart

* SCIREX 438

SCIREX: A Challenge Dataset for Document-Level Information Extraction 
[paper](https://www.aclweb.org/anthology/2020.acl-main.670.pdf) 
[source](https://github.com/allenai/SciREX)

[domain]CS

[description]named entity include types of (Matrial, Method, Metric, Task).

* SCIERC 500

Multi-Task Identification of Entities, Relations, and Coreference for Scientific Knowledge Graph Construction
[paper](https://www.aclweb.org/anthology/D18-1360.pdf)
[source](https://github.com/allenai/SciREX)

[domain]CS

[description]named entity include types of (Matrial, Method, Metric, Task, Generic, OtherItem).

* DOCERC (Human-annotated)5,053  (Distantly Supervised)101,873

DocRED: A Large-Scale Document-Level Relation Extraction Dataset
[paper](https://www.aclweb.org/anthology/P19-1074.pdf)
[source](https://github.com/thunlp/DocRED)

[domain] general

[description]DocRED covers a variety of entity types, including person (18.5%), location (30.9%), organization (14.4%), time (15.8%) and number (5.1%). Includes 96 frequent relation types from Wikidata. A notable property of our dataset is that the relation types cover a broad range of categories, including relations relevant to science (33.3%), art (11.5%), time (8.3%), personal life (4.2%), etc.,

* NLPContributionGraph

NLPContributions: An Annotation Scheme for Machine Reading of Scholarly Contributions in Natural Language Processing Literature
[paper](https://arxiv.org/pdf/2006.12870.pdf)
[source](https://ncg-task.github.io/data.html)
[github](https://github.com/jenlindadsouza/NLPContributions)

[domain]

[description]  The pilot annotation exercise was performed on 50 NLP-ML scholarly articles presenting contributions to the five information extraction tasks 1. machine translation, 2. named entity recognition, 3. question answering, 4. relation classification, and 5. text classification.

* SciORC (PDF-parse)8.1M  (LATEX-parse)1.5M

S2orc: The semantic scholar open research corpus
[paper](https://www.aclweb.org/anthology/2020.acl-main.447.pdf)
[source](https://github.com/allenai/s2orc)

[domain] PDF-parse is multi-domain, LATEX-parse is physics, math, CS domain

[description]metadata, full text, inline citations and references, and bibliography entries

* ELSEVIER OA CC-BY CORPUS 2000

ELSEVIER OA CC-BY CORPUS
[paper](https://arxiv.org/pdf/2008.00774)
[source](https://data.mendeley.com/datasets/zm33cdndxs/2)
[github](https://github.com/elsevierlabs-os/AnnotationQuery)

[domain] 2000 documents were sampled from each of the 27 top-level subject

[description] body, abstract, metadata

* CORD-19

CORD-19: The COVID-19 Open Research Dataset
[paper](https://arxiv.org/pdf/2004.10706.pdf)
[source](https://www.semanticscholar.org/cord19/download)
[github](https://github.com/allenai/cord19)

* BC5CDR 

BioCreative V CDR task corpus: a resource for chemical disease relation extraction
[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4860626/pdf/baw068.pdf)
[source](http://www.biocreative.org/tasks/biocreative-v/track-3-cdr/)

[domain] disease named entity recognition (DNER) and chemical-induced disease (CID) relation extraction

[description]The BC5CDR corpus consists of 1500 PubMed articles with 4409 annotated chemicals, 5818 diseases and 3116 chemical-disease interactions.

* AnchorNER

Towards Open-Domain Named Entity Recognition via Neural Correction Models
[paper](https://arxiv.org/pdf/1909.06058.pdf)
[source](https://drive.google.com/file/d/1Qm3WCWLOPRgTJUuXBKrOLPr20V5yOa5i/view?usp=sharing)
[github](https://github.com/zmd971202/OpenNER)

[domain] open-domain, general

[description]We apply the pipeline described hereafter to a dump of abstracts of English Wikipedia from 2017 and obtain AnchorNER. This dataset is built out of 5.2M abstracts of Wikipedia articles, consisting of 268M tokens accounting for 12M sentences. 

* BBN

Bbn pronoun coreference and entity type corpus
[source](https://catalog.ldc.upenn.edu/LDC2005T33)

[description] fine-grained entity type

* OntoNotes

OntoNotes: A Large Training Corpus for Enhanced Processing
[paper](https://www.researchgate.net/publication/230876724_OntoNotes_A_Large_Training_Corpus_for_Enhanced_Processing)
[source](https://catalog.ldc.upenn.edu/LDC2013T19)

* FIGER

Fine-grained entity recognition
[paper](http://xiaoling.github.com/pubs/ling-aaai12.pdf)
[github](https://github.com/xiaoling/figer)
[source](https://drive.google.com/open?id=0B52yRXcdpG6MMnRNV3dTdGdYQ2M)

* KNET

Improving Neural Fine-Grained Entity Typing with Knowledge Attention
[paper](http://nlp.csai.tsinghua.edu.cn/~lzy/publications/aaai2018_entitytyping.pdf)
[github](https://github.com/thunlp/KNET)

[description]

* Open-type

Ultra-Fine Entity Typing
[paper](https://www.aclweb.org/anthology/P18-1009.pdf)
[source](https://homes.cs.washington.edu/~eunsol/open_entity.html)
[github](https://github.com/uwnlp/open_type)

* DialogRE

Dialogue-Based Relation Extraction
[paper](https://arxiv.org/pdf/2004.08056.pdf)
[github](https://github.com/nlpdata/dialogre)
[source](https://dataset.org/dialogre/)

[domain] conversational/Friends

[description]keep 2,100 triples in total, whose two arguments are in “no relation”, and we finally have 10,168 triples for 1,788 dialogues. We randomly split them at the dialogue level, with 60% for training, 20% for development, and 20% for testing.Based on the predefined SF and DialogRE relation types, a subject is expected to be an entity of type PER, ORG, or geo-political entity (GPE). Notably, subjects of most relational triples (96.8%vs. 69.7%intheSFdataset)inDialogRE are person names. The coarse-grained object type is entity, string, or value (i.e., a numerical value or a date). 
相关数据集* DREAM  * C3

* DREAM
[paper](https://arxiv.org/abs/1902.00164)
[github](https://github.com/nlpdata/dream)
[source](https://dataset.org/dream/)

[description]DREAM is a multiple-choice Dialogue-based REAding comprehension exaMination dataset. In contrast to existing reading comprehension datasets, DREAM is the first to focus on in-depth multi-turn multi-party dialogue understanding.

* C3
[paper](https://arxiv.org/abs/1904.09679v3)
[github](https://github.com/nlpdata/c3)
[source](https://dataset.org/c3/)

[description]C3 is the first free-form multiple-Choice Chinese machine reading Comprehension dataset, containing 13,369 documents (dialogues or more formally written mixed-genre texts) and their associated 19,577 multiple-choice free-form questions collected from Chinese-as-a-second language examinations.

* MAVEN (未发布)

MAVEN: A Massive General Domain Event Detection Dataset
[paper](https://arxiv.org/pdf/2004.13590.pdf)
[]

* cfet 中文细粒度entity typing数据集

A Chinese Corpus for Fine-grained Entity Typing
[paper](https://arxiv.org/pdf/2004.08825)
[github](https://github.com/HKUST-KnowComp/cfet)
[source](https://drive.google.com/file/d/1xorWUdTi9r43tTEdwJ4tKa9ErvRjossU/view?usp=sharing)

## 纯关系的数据集

https://github.com/davidsbatista/Annotated-Semantic-Relationships-Datasets

https://lipn.univ-paris13.fr/~gabor/semeval2018task7/



