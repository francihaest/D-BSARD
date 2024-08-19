# D-BSARD
Belgian Legal Statutory Article Retrieval in Dutch

Advances in AI and natural language processing (NLP) hold great promise for transforming
the legal field by automating complex tasks and providing support for both professionals and
the public. Despite this potential, effective application in legal contexts is hindered by the lack
of high-quality, structured datasets, with a particular absense in the Dutch language. This
thesis presents the development and evaluation of D-BSARD, a Dutch-language statutory article
retrieval dataset designed to support research in natural language processing (NLP) within the
legal domain. Building on the existing French-language BSARD dataset created by Louis and
Spanakis (2022), we translated legal questions and linked them to newly extracted articles from
consolidated legal codes in Dutch. The resulting D-BSARD dataset comprises 20,876 articles
and 1,048 questions.
Using the newly created D-BSARD dataset, we established baseline retrieval models and
evaluated their performance. The results indicated that fine-tuned bi-encoder models achieved
the best performance. Additionally, without task-specific training, the bi-encoder model with a
Word2Vec word embedding encoder and the BM25 lexical model also performed competitively.
However, across all models, the D-BSARD dataset showed slightly lower performance compared
to its French counterpart, indicating a lower data quality. Despite this, the baseline results align
with those from the original BSARD study, validating the effectiveness and reliability of the
dataset. Furthermore, cross-lingual transfer learning did not lead to significant improvements
in model performance.
This work contributes to the growing field of legal NLP by offering a foundational dataset
for statutory article retrieval in Dutch. It also identifies key areas where the dataset may require
further supplementation to enhance its quality and applicability for future research.
