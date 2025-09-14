---
title: "TELESAFE: Detecting Private/Work Boundary Crossings in Energy Consumption Trails in Telework"
collection: publications
category: manuscripts
permalink: /publication/2025-08-29-telesafe
excerpt: ''
date: 2025-08-29
venue: 'VLDB'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://dl.acm.org/doi/10.14778/3725688.3725690'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Haoying Zhang, Mariem Brahem, Nicolas Anciaux, Benjamin Nguyen, and Jose Maria de Fuentes. 2025. TELESAFE: Detecting Private/Work Boundary Crossings in Energy Consumption Trails in Telework. Proc. VLDB Endow. 18, 6 (February 2025), 1565–1578. https://doi.org/10.14778/3725688.3725690'
---
Teleworking has become a social gain following the COVID-19 lock-downs. In many professions, remote work is becoming a common practice, either at the employee's home or in a shared space nearby. However, this creates an implicit private/work-life tension as private activities may be carried out during work time and vice versa. Detecting boundary crossings is of outmost relevance - they serve as evidence of the workers' breaks and right to rest. However, this must be achieved without excessive surveillance. Existing activity recognition techniques either do not address the border crossing problem or require a priori training.
To address this issue, this article proposes TELESAFE, a boundary crossing detector solution for teleworking. TELESAFE does not require any training nor instrumentation of the teleworker home and can be run locally in resource-constrained devices. To illustrate its suitability, it is applied on electric consumption trails so as to enable self and third-party assessment (e.g., work inspectors) on working conditions. Results on real-world datasets show a Fscore over 90% for identifying private activities involving one or more devices with usage patterns of varying lengths. Interestingly, TELESAFE outperforms Machine and Deep-Learning approaches in the most complex settings, without the burden of training.
