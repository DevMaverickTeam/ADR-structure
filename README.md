# ADR Structure

A simple ADR (Arhitecture Decision Record) file structure that we use in our projects. 

Contents:

  - [What is an architecture decision record?](#what-is-an-architecture-decision-record)
  - [How, when and why should you use ADRs?](#how-when-and-why-should-you-use-adrs)
  - [ADR template](#adr-template)
  - [List ADRs in your documentation](#list-adrs-in-your-documentation)
  - [VSCode Snippets for ADRs](#vscode-snippets-for-adrs)

## What is an architecture decision record?
Think of architecture decision record as a document or record that will capture and important architectural change/decision in your project. 

It's a record in time to which you can point and see what decision was made, why it was made and what are the consequences of that decision. 

## How, when and why should you use ADRs?


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

