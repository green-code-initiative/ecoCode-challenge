# Hello! Welcome to the spotter team 👋

As a spotter, you are here to improve ecoCode by finding new rules to implement on one of our static analysers.

## Prerequisites

Here are the things you need to succeed in this challenge:

- Your experience and your brain 😤
- A computer with an internet connection should help you ask your favourite search engine or AI for help.
- A [GitHub account](https://github.com/signup) to share your hard work with the community

## 📜 Identify new ecodesign rules

### Does my rule already exist in ecoCode?

For Android and iOS rules, here are the rules already found: [best pratices mobile](https://github.com/cnumr/best-practices-mobile)

For other plugin rules, there is no centralised place to list all the rules that have been implemented or are in progress. To check if your
rule already exists or has been proposed, please check the following sources:

- [ecoCode implemented rule specification folder](https://github.com/green-code-initiative/ecoCode/tree/main/ecocode-rules-specifications/src/main/rules): contains all the description of the implemented rules
- [ecoCode Rules.md](https://github.com/green-code-initiative/ecoCode/blob/main/RULES.md): a partial list of accepted and not accepted
   rules. Your new rule should not be here!
- [ecoCode canditate rules kanban](https://github.com/orgs/green-code-initiative/projects/1/views/1): a list of work in progress rules.
- check the issues in the plugin project of the language of your rule. For example, for Java check [the Java ecoCode plugin issues](https://github.com/green-code-initiative/ecoCode-java/issues). Some rules there are not complete. If you found a duplication of your rule but you think that you have the missing justification (for example), ask a coach if you can complete the rule!

### What is a good rule definition?

Now you have an idea. Have you checked that it has not already been submitted? Great, you have a baby rule. Here are the things you need to do to turn it into a nice, mature rule:

- A short but explicit title
- The language / platform your rule applies
- A description of what your rule does (and does not do) **with code example**: what is the code my static analyzer must detect and why?
- **The justification of the rule**: documentation reference or measure (or at least an approach to perform the measure) that explains
  why your rule is relevant

Good examples of rule definitions can be found here:

- [Example of rule definition with measure validation](https://github.com/green-code-initiative/ecoCode-challenge/issues/92)
- [Example of rule definition with documentation validation](https://github.com/green-code-initiative/ecoCode-challenge/issues/91)

### What is the submission process for my work?

Your rule is ready and you want to submit it? Connect to the [Green Code Initiative GitHub - ecoCode Challenge project](https://github.com/green-code-initiative/ecoCode-challenge) and perform the following steps:

1- Go to the `Issues` tab and click on the `New Issue` button

![Screen New Issue](/assets/images/spotter_enter_issue1.png)

2- Select the `[Hachaton 2024] Spotter rule description template` and click on `Get Started`

![Screen Get Started](/assets/images/spotter_enter_issue2.png)

3- Fill in the template with your rule and click on `Submit new issue`

![Screen Fill template](/assets/images/spotter_enter_issue3.png)

And that's it!
