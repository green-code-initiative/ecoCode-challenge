---
name: "[Hackaton 2024] Spotter rule description template"
about: 'Spotters: use this template to describe your new rule.'
title: "[Hackaton 2024][Your team here][The platform here] Your rule title here"
labels: Hackaton 2024, spotter
assignees: jhertout

---

**Rule title**

The title of your rule.

**Language and platform**

The language and platform for your rule. For example: Java (11+ JEE), Java (Android 14+), Python 2.7+...

**Rule description**

What does your rule do? Why is this a green coding issue? 
This section should have a bad code versus good code example.

**Rule short description**

A summary of the rule in a single short sentence.

**Rule justification**

**Very important**: give us elements that justify that your rule has an environmental impact. Without a good justification, your rule will not be accepted by Green Code Initiative.

Here are some elements that can help to justify your rule:
- a publication or documentation that explain the impact of the rule (provide the link to the documentation or at least a reference if the documentation is not available online). Please indicate us where to find the information in the document (page, paragraph) and perform a summary if possible.
- comparison measurement in term of energy of the bad practice versus the good practice. If you cannot perform the measure yourself, please indicate us what to measure, with which tools...

**Severity / Remediation Cost**

Estimate the severity and remediation cost of your issue.

Severity must be one of blocker, critical, major, minor (see https://docs.sonarsource.com/sonarqube/latest/extension-guide/adding-coding-rules/#default-severities). Add the justification for your choice.

Remediation cost must be one of trivial, easy, medium, major, high, complex (see https://docs.sonarsource.com/sonarqube/latest/extension-guide/adding-coding-rules/#evaluation-of-the-remediation-cost to choose the must adapted to your rule). Add the justification for your choice.

**Implementation principle**

Indicate here what we will have to detect during the static analysis of the source code with the issue.
