# Contributing to DigitRubber Ontology

:+1: First of all: Thank you for taking the time to contribute!

The following is a set of guidelines for contributing to DIGITRUBBER. 
These guidelines are not strict rules. Use your best judgment, and feel free to propose 
changes to this document in a pull request.

## Table Of Contents

- [Contributing to DigitRubber Ontology](#contributing-to-digitrubber-ontology)
  - [Table Of Contents](#table-of-contents)
  - [Code of Conduct](#code-of-conduct)
  - [Guidelines for Contributions and Requests](#guidelines-for-contributions-and-requests)
    - [Reporting problems with the ontology](#reporting-problems-with-the-ontology)
    - [Requesting new terms](#requesting-new-terms)
      - [Who can request a term?](#who-can-request-a-term)
      - [How to write a new term request](#how-to-write-a-new-term-request)
    - [How to add a new term](#how-to-add-a-new-term)
  - [Best Practices](#best-practices)
    - [How to write great issues?](#how-to-write-great-issues)
    - [How to create a great pull/merge request?](#how-to-create-a-great-pullmerge-request)

<a id="code-of-conduct"></a>

## Code of Conduct

The DigitRubber Ontology team strives to create a
welcoming environment for editors, users and other contributors.
Please carefully read our [Code of Conduct](CODE_OF_CONDUCT.md).

<a id="contributions"></a>

## Guidelines for Contributions and Requests

<a id="reporting-bugs"></a>

### Reporting problems with the ontology

Please use our [Issue Tracker](https://github.com/TIBHannover/DIGIT-RUBBER/issues/) for reporting problems with the ontology. 
To learn how to write a good issue [see here](#great-issues).

<a id="requesting-terms"></a>

### Requesting new terms

Before you write a new request, please consider the following: 

- **Does the term already exist?** Before submitting suggestions for new ontology terms, check whether the term exist, 
either as a primary term or a synonym term. You can search for your term using [OLS](http://www.ebi.ac.uk/ols/ontologies/digitrubber).
- **Can you provide a definition for the term?** It should be very clear what the term means, and you should be
able to provide a concise definition, ideally with a scientific reference.
- **Is the ontology in scope for the term?** Sometimes, it is hard to tell whether a term "belongs" in
and ontology. A rule of thumb is "if a similar term already exists, the new term is probably in scope."
It can be very helpful to mention a very similar concept as part of the term request!

#### Who can request a term?

Anyone can request new terms. However, there is not guarantee that your term will be added automatically. Since this is a 
community resource, it is often necessary to do at least some of the work of adding the term yourself, see below.

#### How to write a new term request

Request a new term _via_ the GitHub [Issue Tracker](https://github.com/TIBHannover/DIGIT-RUBBER/issues/).

It is important to remember that it takes a lot of time for curators to process issues submitted to the tracker.
To make this work easier, please always use issue templates if they are available (https://github.com/TIBHannover/DIGIT-RUBBER/issues/new/choose).

For how to write a good term request, please read the [best practices carefully](#great-issues).

<a id="adding-terms"></a>

### How to add a new term

If you have never editted this ontology before, first follow a [general tutorial](https://oboacademy.github.io/obook/lesson/contributing-to-obo-ontologies)

**Process**:

1. Clone the repository (In case you are not an offical team member, create a fork first)
1. Create new branch in git, for example `git checkout -b issue123`
1. Open src/ontology/digitrubber-edit.owl in your favourite editor, i.e. [Protege](https://protege.stanford.edu/). **Careful:** double check you are editing the correct file. There are many ontology files in this repository, but only one _editors file_!
1. Perform your edit and save your changes
1. Commit changes to branch
1. Push changes upstream
1. Create pull request

## Best Practices

<a id="great-issues"></a>

### How to write great issues?

Please refer to the [OBO Academy best practices](https://oboacademy.github.io/obook/lesson/term-request/).

<a id="great-pulls"></a>

### How to create a great pull/merge request?

Please refer to the [OBO Academy best practices](https://oboacademy.github.io/obook/howto/github-create-pull-request/)