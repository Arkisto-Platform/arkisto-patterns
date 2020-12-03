
# Arkisto Design Patterns

## Audience

This document is for members of the UTS eResearch team and anyone that would like to set up an Arkisto.

## About

This document covers:

- How to generate or get raw Data
- How to generate [Ro-Crates](https://www.researchobject.org/ro-crate/) using a JavaScript implementation [ro-crate-js](https://github.com/UTS-eResearch/ro-crate-js)
- How generate an [OCFL](https://ocfl.io) repository using a JavaScript implementation [ocfl-js](https://github.com/UTS-eResearch/ocfl-js)
- How to spin up an [ONI](https://github.com/UTS-eResearch/oni)
- How to configure dynamic HTML pages
- How to create an RO-Crate export

The instructions on managing the site locally cover Linux and OS X using docker.
Windows users are recommended to use a Linux VM with docker

## How to generate or get raw Data

To get the data either we need to interrogate a database using SQL queries, REST APIs or scraping tools.
There will be cases for which we do not currently have access to raw data. Depending on the use case we would need to generate.

## How to generate Ro-Crates

Using XLRO to define the metadata and use X code to generate Ro-Crates

## How generate an OCFL

Turn your ro-crates into an OCFL repository to be used within ONI.

## How to spin up an ONI

ONI is your main search engine site where the data is going to be accessible by generating a searchable site


## Examples

- See [Seafood Collection](https://github.com/arkisto-platform/seafood-collection) README.md's to find instructions on how to start an Arkisto

The Seafood Collection pattern is about generating data set and then create an Arkisto website

- See [Criminal Characters](https://github.com/arkisto-platform/criminal-characters) README.md's to find instructions on how to start an Arkisto
