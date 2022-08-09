---
title: "Uncovering Library Features from API Usage on Stack Overflow"

authors:
- cvelazquezr
- Eleni Constantinou
- Coen De Roover

date: "2022-03-15T00:00:00Z"
doi: "10.1109/SANER53432.2022.00035"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference Paper; 2 = Workshop Paper;
# 3 = Journal Article; 4 = Preprint / Working Paper; 5 = Report; 6 = Book; 
# 7 = Book section; 8 = Thesis; 9 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the 29th IEEE International Conference on *Software Analysis, Evolution and Reengineering*, SANER 2022, Hawaii, United States of America
publication_short: In *SANER* 2022

abstract: Selecting an appropriate library for reuse within a vast software ecosystem can be a daunting task. A list of features for each library, i.e., a short description of the functionality that can be reused with code examples that illustrate its usage, may alleviate this problem. In this paper, we propose a data-driven approach that uses both the code snippets and the accompanying natural language descriptions from Stack Overflow posts to produce a list of features of a given library. Each extracted feature corresponds to a cluster of API classes and methods considered related based on attributes of the Stack Overflow posts in which they appear. We evaluated the approach considering seven Maven libraries and compared the resulting features against library descriptions from cookbook-like tutorials. The approach achieves an average accuracy of 67% across the seven libraries for the tutorial-like features. For at least 73% of the features extracted by the approach but missing from the documentation, we found a matching library usage in a corpus of GitHub projects. These results suggest that our clusters represent library features, which paves the way to better tool support for documenting software libraries and for selecting a library in an ecosystem.

tags: [features, libraries, stack overflow]
featured: true

url_pdf: 'https://soft.vub.ac.be/Publications/2022/vub-tr-soft-22-01.pdf'
url_code: 'https://github.com/cvelazquezr/saner-2022'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.slideshare.net/CamiloErnestoVelzque/uncovering-library-features-from-api-usage-on-stack-overflow/CamiloErnestoVelzque/uncovering-library-features-from-api-usage-on-stack-overflow'
url_source: ''
url_video: 'https://youtu.be/OgfCeaLsauE?t=2666'
url_video_backup: 'https://youtu.be/iP-gKOFDL-A'

---
