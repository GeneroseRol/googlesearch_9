Google Search Clone

Live Demo: https://github.com/GeneroseRol/googlesearch_9.git

Project Overview

This project is a functional front-end clone of Google Search, Google Image Search, and Google Advanced Search. It demonstrates the ability to map HTML forms to external server endpoints using HTTP GET parameters, all styled with CSS to match Google's core aesthetics.

Team Members & Responsibilities

This project was developed collaboratively using a strict Git Feature Branch Workflow.

[Generose Rol]: Google Standard Search & 'I'm Feeling Lucky' Button

[Mark Lee Olino]:  Image Search & Navigation

[Juan Cedrick Lopez]: Advanced Search 

Technical Architecture (URL Parameters)

This application successfully routes search queries to Google's servers by passing the following GET parameters through HTML <form> tags:

q: The primary search query input.

btnI: Triggers the "I'm Feeling Lucky" redirect bypass.

tbm=isch: Hidden parameter used to route directly to Google Images.

as_q: Advanced Search - "all these words".

as_epq: Advanced Search - "this exact word or phrase".

as_oq: Advanced Search - "any of these words".

as_eq: Advanced Search - "none of these words".

Collaboration Workflow

Briefly describe how your team managed the codebase. Did you encounter any merge conflicts? How did you resolve them?

Our team used Git to work on separate branches and submitted pull requests to review each other's code before merging. When a technical glitch caused a pull request to only show up for Generose, we create new repo and resolved any future code conflicts by discussing the changes together.
