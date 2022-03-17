---
title: "MUTAMA: An Automated Multi-label Tagging Approach for Software Libraries on Maven"

authors:
- cvelazquezr
- Coen De Roover

date: "2020-10-28T00:00:00Z"
doi: "10.1109/SCAM51674.2020.00034"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference Paper; 2 = Workshop Paper;
# 3 = Journal Article; 4 = Preprint / Working Paper; 5 = Report; 6 = Book; 
# 7 = Book section; 8 = Thesis; 9 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the 20th IEEE *International Working Conference on Source Code Analysis and Manipulation*, SCAM 2020, Adelaide, Australia
publication_short: In *SCAM* 2020

abstract: Recent studies show that the Maven ecosystem alone already contains over 2 million library artefacts including their source code, byte code, and documentation. To help developers cope with this information, several websites overlay configurable views on the ecosystem. For instance, views in which similar libraries are grouped into categories or views showing all libraries that have been tagged with tags corresponding to coarse-grained library features. The MVNRepository overlay website offers both category-based and tag-based views. Unfortunately, several libraries have not been categorised or are missing relevant tags. Some initial approaches to the automated categorisation of Maven libraries have already been proposed. However, no such approach exists for the problem of tagging of libraries in a multi-label setting. This paper proposes MUTAMA, a multi-label classification approach to the Maven library tagging problem based on information extracted from the byte code of each library. We analysed 4 088 randomly selected libraries from the Maven software ecosystem. MUTAMA trains and deploys five multi-label classifiers using feature vectors obtained from class and method names of the tagged libraries. Our results indicate that classifiers based on ensemble methods achieve the best performances. Finally, we propose directions to follow in this area.

tags: [multi-label, libraries, software ecosystem, classification]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://soft.vub.ac.be/Publications/2020/vub-tr-soft-20-09.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
