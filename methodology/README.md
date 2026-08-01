# Systematic Review Summary

## Files

- [SrMeth&Coding](SrMeth&Coding.xlsx): Excel file containing the methodology employed in the systematic review (SR), together with the procedures used to extract and code the results for the proposed research questions (RQs).

## Description

This repository contains a systematic review of publications indexed in the **Scopus** and **Web of Science Core Collection** bibliographic databases. The review covers studies published from **January 1, 2014, to June 30, 2026**, and follows an adapted **PRISMA 2020** reporting and study-selection process.

The review focuses on publications whose main contribution is a taxonomy, classification, broad list, or synthesis of **cyber threats affecting end users of online social networks (OSNs)**. After identification, duplicate removal, title-and-abstract screening, and full-text screening, **48 studies** were included in the final review.

## Search Strategy

The searches were restricted to publication **titles**. A broader search across titles, abstracts, and keywords produced more than 59,000 records across all research areas and approximately 30,000 records after restricting the results to Computer Science and Engineering. The title-based strategy was therefore adopted as a trade-off between sensitivity, relevance, and screening feasibility, and to retrieve publications whose central focus was explicitly related to OSN cyber-threat taxonomies, classifications, or broad threat analyses.

The search strategy combined two sets of terms:

- **Set 1 — Online social networks and social media**
  - `social media`
  - `social network*`
  - `OSN*`
  - `SNS`
  - `MSN*`

- **Set 2 — Cyber threats and security**
  - `threat*`
  - `security`
  - `attack*`

The searches were limited to:

- Publications written in **English**.
- The subject areas **Computer Science** and **Engineering**.
- Publications dated from **2014 to June 30, 2026**.

### Scopus query

```text
TITLE(( *social AND (media OR network*) ) OR osn* OR sns OR msn*)
AND TITLE(*threat OR threat* OR *security OR *attack OR attack*)
AND PUBYEAR > 2013
AND (LIMIT-TO(SUBJAREA, "COMP") OR LIMIT-TO(SUBJAREA, "ENGI"))
```

### Web of Science Core Collection query

```text
TI=(((*social AND (media OR network*)) OR osn* OR sns OR msn*))
AND TI=(*threat OR threat* OR *security OR *attack OR attack*)
AND PY=(2014-2026)
AND SU=(Computer Science OR Engineering)
```

## Identification and Duplicate Removal

The database searches identified the following records:

| Database | Records identified |
|---|---:|
| Scopus | 1,094 |
| Web of Science Core Collection | 633 |
| **Combined records** | **1,727** |

A total of **527 duplicate records** were removed. After duplicate removal and initial data cleaning, **1,200 unique records** remained for screening.

Some residual duplicates caused by differences in titles, author names, publication years, or missing identifiers were identified and removed during the subsequent screening phases.

## Screening Phases

Percentages in the first screening phase are calculated using the **1,200 unique records** as the denominator. In the second phase, percentages are reported both in relation to the **1,200 screened records** and to the **216 records assessed at full text**.

### Phase 1 — Title and Abstract Screening

The title and abstract of each record were assessed against the eligibility criteria.

| Exclusion reason | Records excluded | Percentage of screened records (`n = 1,200`) |
|---|---:|---:|
| Not written in English | 8 | 0.67% |
| Abstract not accessible | 4 | 0.33% |
| Duplicate record | 7 | 0.58% |
| Irrelevant publication type, such as conference reviews, editorials, errata, retracted publications, or notes | 52 | 4.33% |
| Does not address cyber threats in OSNs | 251 | 20.90% |
| Addresses OSN cyber-threat statistics, case studies, or surveys focused on specific areas or groups | 150 | 12.50% |
| Addresses threat detection, alerting, or analysis through OSN platforms, data mining, AI, ML, CTI platforms, or other technologies | 168 | 14.00% |
| Addresses individual cyber threats, attacks, or solutions at a very fine level of granularity | 344 | 28.67% |
| **Total excluded in Phase 1** | **984** | **82.00%** |
| **Remaining for full-text screening** | **216** | **18.00%** |

### Phase 2 — Full-Text Screening

The full texts of the remaining 216 records were assessed against the eligibility criteria.

| Exclusion reason | Records excluded | Percentage of screened records (`n = 1,200`) | Percentage of full-text records (`n = 216`) |
|---|---:|---:|---:|
| Full text not accessible or not retrieved | 43 | 3.58% | 19.90% |
| Does not address cyber threats in OSNs | 47 | 3.92% | 21.76% |
| A more complete or updated version was already included | 6 | 0.50% | 2.78% |
| Does not provide a clear OSN cyber-threat taxonomy, list, or classification | 38 | 3.17% | 17.59% |
| Addresses OSN cyber-threat statistics, case studies, or surveys focused on specific areas or groups | 6 | 0.50% | 2.78% |
| Addresses threat detection, alerting, or analysis through OSN platforms, data mining, AI, ML, CTI platforms, or other technologies | 1 | 0.083% | 0.46% |
| Addresses individual cyber threats, attacks, or solutions at a very fine level of granularity | 27 | 2.25% | 12.50% |
| **Total excluded in Phase 2** | **168** | **14.00%** | **77.78%** |
| **Included in the final review** | **48** | **4.00%** | **22.22%** |

## Results Overview

| Review stage | Records | Percentage |
|---|---:|---:|
| Records identified across both databases | 1,727 | — |
| Duplicate records removed before screening | 527 | — |
| Unique records screened | 1,200 | 100.00% |
| Excluded during title-and-abstract screening | 984 | 82.00% |
| Assessed through full-text screening | 216 | 18.00% |
| Excluded during full-text screening | 168 | 14.00% of screened records; 77.78% of full-text records |
| **Total excluded during screening** | **1,152** | **96.00% of screened records** |
| **Studies included in the systematic review** | **48** | **4.00% of screened records; 22.22% of full-text records** |

### Summary

The systematic review initially identified **1,727 records** across Scopus and Web of Science Core Collection. After removing **527 duplicates**, **1,200 unique records** were screened.

During the first phase, **984 records were excluded (82.00%)**, leaving **216 records (18.00%)** for full-text assessment. During the second phase, **168 records were excluded**, representing **14.00% of all screened records** and **77.78% of the records assessed at full text**.

In total, **1,152 of the 1,200 screened records were excluded (96.00%)**, and **48 studies were included in the final systematic review (4.00%)**. These studies cover publications from **2014 to June 30, 2026** and support the analysis of terminology, classification criteria, and cyber threats affecting OSN end users.