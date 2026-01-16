---
title: "Does Infrastructure as Code Adhere to Semantic Versioning? An Analysis of Ansible Role Evolution"

authors:
- Ruben Opdebeeck
- Ahmed Zerouali
- cvelazquezr
- Coen De Roover

date: "2020-10-27T00:00:00Z"
doi: "10.1109/SCAM51674.2020.00032"

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

abstract: Ansible, a popular Infrastructure-as-Code platform, provides reusable collections of tasks called roles. Roles are often contributed by third parties, and like general-purpose libraries, they evolve. As such, new releases of roles need to be tagged with version numbers, for which Ansible recommends adhering to the semantic versioning format. However, roles significantly differ from general-purpose libraries, and it is not yet known what constitutes a breaking change or the addition of a feature to a role. Consequently, this can cause confusion for clients of a role and new role contributors. To alleviate this issue, we perform an empirical study on semantic versioning in Ansible roles to uncover the types of changes that trigger certain types of version bumps. We collect a dataset of over 70000 version increments spanning upwards of 7800 Ansible roles. Moreover, we design a novel structural model for these roles, and implement a domainspecific structural change extraction algorithm to calculate structural difference metrics. Afterwards, we quantitatively investigate the state of semantic versioning in Ansible roles and identify the most commonly changed components. Then, using the structural difference metrics, we train a Random Forest classifier to predict applicable version bumps for Ansible role releases. Lastly, we confirm our empirical findings with a developer survey. Our observations show that although most Ansible role developers follow the semantic versioning format, it appears that they do not always consistently follow the same rules when selecting the version bump to apply.

tags: [ansible, infrastructure as code, semantic versioning, empirical study, mining software repositories]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://soft.vub.ac.be/Publications/2020/vub-tr-soft-20-08.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
