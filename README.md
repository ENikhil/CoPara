#CoPara 🥥: The First Dravidian Paragraph-level n-way Aligned Corpus

This repository presents CoPara 🥥, the first publicly available paragraph-level (n-way aligned) multilingual parallel corpora for Dravidian languages. The collection contains 2856 paragraph/passage pairs between English and four Dravidian languages. We source the parallel paragraphs from the New India Samachar magazine and align them with English as a pivot language. We do human and artificial evaluations to validate the high-quality alignment and richness of the parallel paragraphs of a range of lengths. We hope to help advance research in Dravidian NLP, parallel multilingual, and beyond sentence-level tasks like NMT, etc.

The data folder has our dataset on a paragraph aligned level (Paragraphs.csv that we present in the paper) as well as just articles aligned to each other (Articles.csv). The following additional metadata can be of use in various tasks:

- Index: a 0 based index of all data
- Text: The main text of the paragraph
- Tokens: Number of tokens in the paragraph
- Sentences: Number of sentences in the paragraph
- Words: Number of words in the paragraph 

We also make the best finetuned NMT model checkpoints here: 
https://drive.google.com/drive/folders/1WtilqTLflkgxdz5hHAVae1RHQQN-vfty?usp=sharing