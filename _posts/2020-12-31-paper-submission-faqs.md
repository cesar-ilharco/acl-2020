---
title: "Paper Submission FAQs"
author: program-chairs
author_profile: true
excerpt: ""
tags:
  paper-submission
  faqs
categories:
    blog
---
**If you need to contact PCs, please use English. PCs have received several emails in non-English.
And also, when you discuss your submissions with your co-authors, please do NOT cc PCs.**

## Double Submissions and Anonymity Issues

### Q1: My paper recently gets rejected from ICLR 2021. The paper is automatically de-anonymized on January 15, 2021. Can I submit my paper to ACL-IJCNLP 2021?

A1: The anonymity period starts on January 1, 2021. In general, the papers rejected by ICLR 2021 should not be submitted to ACL-IJCNLP 2021. On the other hand, if you have a non-anonymized version of the paper posted on or before January 1, 2021, please see Q2.

### Q2: We have submitted our paper to ICLR 2021 and we also have a non-anonymized version on arXiv now. ICLR 2021 notifies us of the final result and de-anonymizes the submission on January 12, 2021 which is in the anonymity period of ACL-IJCNLP 2021, we wonder if it would be against the anonymous policy if we submit that paper to ACL-IJCNLP 2021 at that time. 

A2: If your non-anonymized paper is posted on or before January 1, 2021, you can submit your paper to ACL-IJCNLP 2021.

### Q3: Our paper has already been accepted at a workshop. There are no formal proceedings for this workshop. We want to submit our work to ACL-IJCNLP 2021. Do we need to take any special steps to ensure its eligibility for ACL-IJCNLP 2021, for example, to ensure that the workshop does not post the paper online during the anonymity period?

A3: The goal of the anonymity period is to ensure double blind review. Thus, the workshop should not post the paper online during the anonymity period. It would be good that you contact the workshop organizers about this.

### Q4: Does the anonymity deadline of January 1, 2021 refer to the submission deadline or publication deadline for an arXiv submission?

A4: For arXiv submissions, January 1, 2021 11:59pm UTC-12h (anywhere on earth) is the submission deadline. The date stamp associated with the submission is the time that the final "Submit Article" step is completed. For other non-anonymized versions, it is the deadline when such a version becomes public.

### Q5: We post an arXiv preprint prior to the anonymity period, and we will not update/advertise it after anonymity begins. May we introduce upgrades to the associated web demo and the related GitHub repo during the anonymity period if we do not announce these upgrades in any way?
A5: As long as you don't update your arXiv preprint during the anonymity period, you won't be considered as violating the anonymity policy. That is, you can still update your web demo and a GitHub repo after anonymity begins.

### Q6: Can we submit a paper based on work reported previously in a talk?
A6: You are most welcome to submit your work to ACL-IJCNLP 2021 as long as the talk or the previous venue you submit work to does not have a formal proceeding, with an ISBN/ISSN/DOI or similar.

### Q7: Can we submit ACL-IJCNLP 2021 main conference papers to ACL-IJCNLP workshops?
A7: We allow papers dual-submitted to both ACL-IJCNLP 2021 main conference and its workshops.

### Q8: Can we submit ACL-IJCNLP 2021 papers to a non-archival workshop? The workshop will not have formal published proceedings, but will provide links to accepted papers.
A8: If your workshop paper is published online between January 1, 2021 and May 5, 2021, then you should not submit to ACL-IJCNLP 2021 due to its anonymity policy.

### Q9: In my paper submission, can I include a link to my source code at github?
A9: Please do not include github links that reveal the authors' identities in your submission. If you feel it is important to include your source code, you can zip the code and submit it to softconf. If your paper is accepted, you can include the github link in the camera-ready version.

## Page Limit

### Q1: What is the page limit of theme papers? 
A1: Submission requirements for theme papers are the same as long papers.

### Q2: The call for papers says "Authors will be allowed extra space after the 8th page (4th for short papers) for a broader impact statement or other discussion of ethics." Does this mean that the impact statement will be not counted in the total page limit?
A2: The ethics/broader impact statement is not counted in the total page limit. You need to put the impact statement right before the references. Thus, the paper excluding the impact statement and references should not be over the page limit. 

### Q3: What is the page limit of the appendix?
A3: The page limit of the appendix is 4 pages.

### Q4: Should the appendix be submitted as a separate document?
A4: Yes. It should be submitted as a separate pdf file. It should not be included in the main paper.

## Abstract and Full Paper Submissions

### Q1: Why does the conference require abstracts to be submitted by January 25, 2021?
A1: The review period of ACL-IJCNLP 2021 is a couple of weeks shorter than that of ACL 2020, mainly due to the coordination with NAACL 2021. To deal with the shortened review cycle, we require authors to submit an abstract one week before the full-paper deadline in order to prepare for the review cycle.

### Q2: Do I need to submit an abstract by January 25, 2021?
A2: Yes. If you don't submit an abstract by that date, you will not be able to submit the full paper by the February 1 deadline.

### Q3: Will I be able to change author names and subject areas after the abstract deadline? What can we change in the full-paper submission?
A3:  You should not change the author names and the subject area after the January 25 deadline because we are going to use that information to assign submissions to tracks and run conflict-of-interest checks. But you can change the order of authors, the paper type, and make minor changes to the title and the abstract. 

### Q4: Do all authors have to have user profiles and global profiles?
A4:  We prefer all authors to have those profiles, but if it is impossible for some authors to have those profiles, it is ok (albeit not desirable).

## Impact Statement

### Q1: What kind of submissions should include an impact statement? How will the impact statement be used during the review process?
A1: We are drafting a separate FAQ on impact statement. It will be posted to the conference website around January 15, 2021.  The FAQ will be similar to the ones used by [NAACL 2021](https://2021.naacl.org/ethics/review-questions/). 

## Reproducibility Issues

### Q1: Is there a reproducibility checklist?
A1: The checklist is [here](https://2021.aclweb.org/calls/reproducibility-checklist/), which is very similar to the one used by NAACL 2021. The checklist is intended as a reminder to help authors improve reproducibility of their papers and to help reviewers to assess the papers.

### Q2: What do I need to do about the checklist during the submission process?
A2: The checklist is part of the submission form. We require all submissions to mark "Yes", "No", or "N/A" for each item (we will have a mandatory selector for each item). As an example, a paper which introduces a new dataset might not do a hyperparameter search, and so the authors can mark "N/A" for the hyperparameter search items. 

### Q3: Should we address the relevant questions in the checklist in the main paper or in the appendix?
A3: Authors can choose the best places to address those questions. Below are some recommendations: 
- The items in the first group "For all reported experimental results" should be included in the main paper. 
- The items in the second group "For all results involving multiple experiments, such as hyperparameter search" can be in the appendix, although "the exact number of training and evaluation runs" should likely be in the main paper. 
- The items in the third group "For all datasets used" are mixed. The first and second items should be in the main paper (to understand experimental results we need to know the number of examples, and data splits), while the rest of the items can be in the appendix. 
