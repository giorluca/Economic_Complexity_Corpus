# Economic_Complexity_Corpus
<p align="justify">
‘Economic Complexity Corpus’ (ECC) is a collection of 83 English research papers on the concept of economic complexity published between 2019 and July 2024, written by 82 authors. The textual genre distribution is 100% academic, thus the communication typology is expert-to-expert. The data source for our corpus is CORE (Knoth et al., 2023), a comprehensive bibliographic database of the world’s scholarly literature and the world’s largest collection of full text open access research papers. Each entry in the corpus contains a unique numerical identifier, the COREid, the title, the full text, the author(s), the year of publication, the abstract, the DOI (Digital Object Identifier), the language, the publisher and the title-text pair together.
</p>

![image](https://github.com/user-attachments/assets/be053999-d8fe-4ded-a699-e5aa2e898aba)

![image](https://github.com/user-attachments/assets/aa97c970-081a-4414-a925-7e9c95f3f4c9)

_Data Preprocessing_
<p align="justify">
First, we make sure that the corpus contains no missing entries in both the title and text field. Then we drop 1 duplicate entry by title. We also append the titles to the beginning of the texts, separating them by two newline characters (‘\n’) in order to have all relevant textual data in the same string. Furthermore, before computing the bigram, trigram and keyword lists, we remove stopwords (e.g., ‘and’, ‘or’, ‘of’), as non-informative, functional and very common words which carry minimal semantic relevance can obscure potential interesting and meaningful patterns in content analysis3 (Raulji & Saini, 2017; Kaur & Buttar, 2018). We keep the texts with stopwords for the collocation analysis and the analysis of concordance lines. Finally, for enhanced compatibility with the textual analysis toolkit, we export each preprocessed title-text pair in separate plain text format (.txt) files.
</p>

To cite our work:
[TBA]
