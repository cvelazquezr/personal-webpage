---
title: "Extracting Library Features from Incomplete Code on Stack Overflow"

authors:
- cvelazquezr

date: "2024-03-29T00:00:00Z"
# doi: "10.1016/j.scico.2023.102941"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference Paper; 2 = Workshop Paper;
# 3 = Journal Article; 4 = Preprint / Working Paper; 5 = Report; 6 = Book; 
# 7 = Book section; 8 = Thesis; 9 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
# publication: In the *Science of Computer Programming* Journal, SCICO 2023
# publication_short: In *SCICO* 2023

abstract: It is common in contemporary software development to reuse features provided by third-party libraries. Reusing features instead of re-implementing them from scratch can reduce development time and may improve the overall system quality. However, selecting an appropriate library to reuse features from can be difficult for developers due to the lack of automated tool support. Some library indices propose rankings of libraries, but these are biased towards the number of library downloads, attributed stars, etc. This may lead developers to select the most popular library instead of the library with the feature they were hoping to reuse. This thesis makes three contributions. The first, called LiFUSO, is an automated approach to enumerating and describing the features provided by a library based on publicly available information on social coding platforms such as Stack Overflow (SO) and GitHub. LiFUSO analyses library usages within SO posts and extracts usage patterns indicative of library features. To this end, it considers both the code snippets and the surrounding natural language within each SO post that discusses the library. RESICO, the second contribution of the thesis, is an automated approach to resolving API type references within a code snippet to their corresponding fully-qualified name. As a learning-based text classification approach, RESICO needs to be trained on a corpus of programs for which a compiler has determined the correct type information. Once trained, it can take syntactically incorrect code snippets as input. The final contribution combines LiFUSO and RESICO so the former is no longer limited in scope to SO posts that have been tagged with a library’s name but can also extract information from posts in which it has recognised many library types. We evaluate the impact of broadening the scope of the analysis on the quantity and quality of the uncovered library features. The contributions are relevant to the software engineering community at large. RESICO’s type resolution can be adopted by tools that need to analyse potentially incomplete code snippets, or by tools that need to determine the libraries used within a code snippet —just like in our third contribution. LiFUSO paves the way for tool support for selecting a library from many alternatives. Finally, these contributions help understand the benefits and drawbacks of data-centric over algorithmic-centric solutions to software engineering problems.

tags: [fully qualified name resolution, machine learning, text classification, stack overflow, features]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://soft.vub.ac.be/Publications/2024/vub-soft-phd-29-03.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
