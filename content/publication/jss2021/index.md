---
title: "On the practice of semantic versioning for Ansible galaxy roles: An empirical study and a change classification model"

authors:
- Ruben Opdebeeck
- Ahmed Zerouali
- cvelazquezr
- Coen De Roover

date: "2021-07-15T00:00:00Z"
doi: "10.1016/j.jss.2021.111059"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference Paper; 2 = Workshop Paper;
# 3 = Journal Article; 4 = Preprint / Working Paper; 5 = Report; 6 = Book; 
# 7 = Book section; 8 = Thesis; 9 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In the *Journal of Systems and Software*, JSS 2021
publication_short: In *JSS* 2021

abstract: Ansible, a popular Infrastructure-as-Code platform, provides reusable collections of tasks called roles. Roles are often contributed by third parties, and like general-purpose libraries, they evolve. Therefore, new releases of roles need to be tagged with version numbers, for which Ansible recommends adhering to the semantic versioning format. However, roles significantly differ from generalpurpose libraries, and it is not yet known what constitutes a breaking change or the addition of a feature to a role. Consequently, this can cause confusion for clients of a role and new role contributors. To alleviate this issue, we perform an empirical study on semantic versioning in Ansible roles to uncover the types of changes that trigger certain types of version bumps. Our dataset consists of over 81 000 version increments spanning upwards of 8 500 Ansible roles. We design a novel structural model for these roles, and implement a domain-specific structural change extraction algorithm to calculate structural difference metrics. Afterwards, we quantitatively investigate the state of semantic versioning in Ansible roles and identify the most commonly changed elements. Then, using the structural difference metrics, we train a Random Forest classifier to predict applicable version bumps for Ansible role releases. Finally, we confirm our empirical findings with a developer survey. Our observations show that although most Ansible role developers follow the semantic versioning format, it appears that they do not always consistently follow the same rules when selecting the version bump to apply. Moreover, we find that the distinction between patch and minor increments is often unclear. Therefore, we use the gained insights to formulate a number of guidelines to apply semantic versioning on Ansible roles. These guidelines can be used by role developers to ensure a clear interpretation of the version increments.

tags: [ansible, infrastructure as code, semantic versioning, empirical study, mining software repositories]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://soft.vub.ac.be/Publications/2021/vub-tr-soft-21-08.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
