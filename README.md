# ADR Structure

A simple ADR (Arhitecture Decision Record) file structure that we use in our projects and VSCode Snippets for ADRs. 

Contents:

  - [What is an architecture decision record?](#what-is-an-architecture-decision-record)
  - [Why and when should you use ADRs?](#why-and-when-should-you-use-adrs)
  - [ADR template](#adr-template)
  - [List ADRs in your documentation](#list-adrs-in-your-documentation)
  - [VSCode Snippets for ADRs](#vscode-snippets-for-adrs)

## What is an architecture decision record?
Think of architecture decision record (ADR) as a document that will capture an important architectural decision in your project. 

It's a record in time to which you can point and see what decision was made, why it was made and what are the consequences. 

ADRs are like a note to your future self explainig why you did a thing in a certain way. (or to a future teammate/owner)


## Why and when should you use ADRs?

### Why
We needed a better overview of what changes/decisions were made in the past and why. 

In most projects you use a git repository and you might have a project management tool like Clubhouse. 

Git is great to log changes to multiple files and provide an overview on a pull/merge request, but it doesn't give you the whole story around those changes and it's hard to track a specific architectural decision. 

Clubhouse or other management tools are focused around stories/tasks/iterations, but it's not linked to the actual project files and it gets tricky to track down certain things in a sea of tasks. 

ADR is the best solution to have a complete overview of an important architectural decision:
- Why it was needed? (context)
- When it was made? (date)
- Is it live? (status)
- What were the options? (options)
- How was it implemented? (decision)
- What changed or what was affected? (consequences)
- Who was part of the decision? (people involved)

### When
I'll use this TL;DR from Spotify:
> TL;DR Have you made a significant decision that impacts how engineers write software? Write an ADR!

[When Should I Write an Architecture Decision Record](https://engineering.atspotify.com/2020/04/14/when-should-i-write-an-architecture-decision-record/)

## ADR template
The ADR template should include:
- Name that is descriptive (*)
- Date (*)
- Status (*)
- Context (*)
- Options
- Decision (*)
- Consequences (*)
- People involved

(*) - mandatory

See our [ADR template](docs/adr/0001-ADRNameDescriptive.md).

## List ADRs in your documentation
Add your ADRs to the main ReadMe of your project/repository. 

Have a content table for ADRs, this way you can quickly refresh your memory on some changes and find what you're looking for. 

[Example](README-example.md)

See the [VSCode Snippets](#vscode-snippets-for-adrs) 


## VSCode Snippets for ADRs
We have 2 VSCode snippets to easy add ADR files or create a content table of ADRs. 

- **adr-index**
  
  It will allow you to start create the [ADR list](#list-adrs-in-your-documentation) for your documentation.

- **adr-content**
  
  It will allow you to generate a default [ADR template](#adr-template).

Find them [here](VSCode-Snippets.md)

## Other resources

- [Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)
- [Markdown Architectural Decision Records](https://github.com/adr/madr)
- [Architecture decision record](https://github.com/joelparkerhenderson/architecture_decision_record)
- [Wiki](https://en.wikipedia.org/wiki/Architectural_decision)