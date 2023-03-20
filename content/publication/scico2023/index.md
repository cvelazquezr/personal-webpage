---
title: "A Text Classification Approach to API Type Resolution for Incomplete Code Snippets"

authors:
- cvelazquezr
- Dario Di Nucci
- Coen De Roover

date: "2023-03-17T00:00:00Z"
doi: "10.1016/j.scico.2023.102941"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference Paper; 2 = Workshop Paper;
# 3 = Journal Article; 4 = Preprint / Working Paper; 5 = Report; 6 = Book; 
# 7 = Book section; 8 = Thesis; 9 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In the *Science of Computer Programming* Journal, SCICO 2023
publication_short: In *SCICO* 2023

abstract: The Stack Overflow Q&A platform boasts an active community of users who often include code snippets in their questions and answers. Several development tools rely on these code snippets as a source of information. Although code snippets are intended as examples for humans, they may not form compilation units. For instance, snippets illustrating how to use an API might lack the import statements for the corresponding API types. Thus, it becomes essential to determine the fully-qualified name of API types in incomplete snippets. We present RESICO, a machine learning-based text classification approach to resolving the simple name of API types to their fully-qualified names. RESICO is trained on a corpus of Java programs for which a compiler can determine the fully-qualified names. For four machine learning classifiers, we evaluate the type resolution accuracy of the resulting models on the original and an extended version of datasets of snippets previously used to evaluate the current state-of-the-art approach based on information retrieval. Results show that our approach outperforms the state-of-the-art one, although the training phase is slightly slower. We observe that most of the incorrect type resolutions are not due to ambiguities among the simple names for API types but due to similarities among the contexts in which these types are used, representing a future research challenge.

tags: [fully qualified name resolution, machine learning, text classification, stack overflow]

# Display this page in the Featured widget?
featured: true

url_pdf: 'http://soft.vub.ac.be/Publications/2023/vub-tr-soft-23-07.pdf'
url_code: 'https://github.com/softwarelanguageslab/resico-paper'
url_dataset: 'https://zenodo.org/record/7276757'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
