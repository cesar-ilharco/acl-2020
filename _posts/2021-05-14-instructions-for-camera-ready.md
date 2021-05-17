---
title: "Instruction for Camera-Ready Submission"
author: Antoine Bosselut, Christophe Gravier, Jing Huang
author_profile: true
excerpt: ""
tags:
  Camera-Ready
  Submission
categories:
    blog
toc: true
toc_sticky: true
toc_icon: "cog"
---
May 14, 2020
These instructions are adapted from the ones for ACL 2020, EMNLP 2020, and NAACL 2021.

To submit your camera-ready version, please go to the softconf site, click the submission id, and then click "Final Camera Ready Submission". This document is organized based on the sections in the Final Submission Page. Please note that the following applies to the ACL-IJCNLP main conference papers and Findings of ACL papers. It will also apply to ACL-IJCNLP workshop papers unless the workshops have their own instructions.

Please remember to use the template files for the conference and follow the instructions in this document. In addition, you need to run a tool called aclpub_check developed by the NAACL2021 publication chairs to automate the checking for some frequently encountered formatting issues. For details of the tool, see Section 3 and the Appendix. Camera-ready copies that fail to meet these instructions will be returned for re-submission. 

## 1. Metadata (Part A in the final submission form)
### Can I make changes to the author list in the camera-ready version?
No, you cannot change the author list, as explained in the FAQ at https://2021.aclweb.org/blog/faq-decision/ 
In fact, the authors' field will not be editable in the final submission form.

### How should I enter metadata on the START system?
The metadata (title, author, abstract) that you enter into START is very important, because it is used on the conference website, proceedings, handbook, mobile app, and the ACL Anthology (and propagates to Google Scholar, etc.).

Before the metadata is entered, please have all authors ensure that the name in their START profile (User Console, Update Profile) appears exactly the way that they want it to appear. 
- Unicode (UTF-8) can be used for accented or special characters.
- Ordinarily, names are NOT written in all caps or all lowercase.
- The "Last Name" is the name(s) by which your paper is to be cited. It is usually a family name, even for authors from cultures where the family name is written first.
- The "First Name" is usually a given name or names, including middle names/initials.

The metadata should be written using Unicode (UTF-8) with LaTeX commands. Please try to follow these guidelines: 
- In titles, please capitalize the first word, the first word after a colon (:), and all other words (including hyphenated words like Mixed-Case), except the function words: **articles, pronouns, conjunctions, prepositions, particles, subordinating conjunctions, and the infinitive marker "to".** 
- BibTeX (in many bibliography styles, including ACL's) lowercases the titles of conference papers, and needs to be told which letters not to lowercase. So if your title has letters that should always be capitals, please protect them with curly braces, like this: {E}nglish, {C}homsky, {IBM}, {CFG}s, {HMM}s. Please also protect the first letter after a sentence-final punctuation mark. For example: 

*Can {LSTM} Learn to Capture Agreement? {T}he Case of {B}asque 
Named Entity Extraction from Noisy Input: {S}peech and {OCR}.*

It is important to only protect those first letters that belong to the categories exhibited above, i.e., proper names (including language names), acronyms, abbreviations, the first letter after punctuation (such as a colon) and the first letter in a sentence. These curly braces will not appear in the online conference program or proceedings. They will only appear in the BibTeX file that others will use to cite your paper.
- If you need literal curly braces, please escape them like this: \{ \}
- Please don't use any nonstandard LaTeX commands, and there should be no \footnote or citations using \cite or related commands.
- You can use LaTeX math mode where appropriate: An $O(n^2)$ Algorithm for $n$-gram Smoothing.
- You can use Unicode (UTF-8) for accented or special characters.
- If you copy-and-paste from your PDF file, please be sure to rejoin words broken by hyphenation.

## 2. Copyright (Part B in the form)

### What about copyright?
When you submit the paper, you will be asked to sign the ACL Copyright Transfer Agreement on behalf of all authors, electronically (via the START Conference Manager). Authors retain many rights under this agreement and it is appropriate in the vast majority of cases. Please contact the publication chairs at acl2021publicationchairs@googlegroups.com, with any concerns regarding copyright.

### Who should sign the copyright form?
Before signing this form, please confirm with your co-authors (and, if applicable, your and their employers) that they authorize you to sign on their behalf. Only the authorized representative needs to sign the copyright form. Please sign your full name (not just your first or last initials). 






