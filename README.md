# Node.js Examples

⚠️⚠️⚠️  

The contents of this repository are not up to date.  
The opinions and information expressed here do not necessarily reflect the up-to-date opinions of the Node.js project.  
It is kept here as a public archive.  

⚠️⚠️⚠️  

-----

## Overview

This repository is a collective of opinionated and real-world examples of how you can use Node.js to build things.

## How This Repository is Structured

This repository is structured in a specific way:

- **Top-level directories** are **category directories** of applications - for example, `CLI`, `server`, and `utility` - that enable you to find the specific _kind_ of example you're looking for.
- **Second-level directories** are **project directories** named after specific modules, frameworks, platforms, or tools - for example, `yargs` is a CLI framework, both `express` and `fastify` are web frameworks, and `moment` is a utility.
- **Third-level directories** are **example directories**, where specific examples live. You can find a full list of these examples in the [Examples](#examples) section below.

Here is an example of the structure in general terms:

```text
- examples (root)
  - category
    - project
      - example
  - category
    - project
      - example
      - example
      - example
    - project
      - example
      - example
  - category
    - project
      - example
    - project
      - example
      - example
