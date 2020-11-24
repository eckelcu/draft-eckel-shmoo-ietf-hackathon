# draft-eckelcu-shmoo-ietf-hackathon

This repository contains a personal [IETF Internet-Drafts](https://www.ietf.org/standards/ids/) that has not yet been adopted by an IETF working group. The draft is in Markdown format. XML and text versions of the draft, as required for [draft submission](https://datatracker.ietf.org/submit/) are generated using:

* [kramdown-rfc2629](https://github.com/cabo/kramdown-rfc2629/blob/master/README.md) to convert from Markdown to XML
* [xml2rfc](https://xml2rfc.tools.ietf.org/) to convert from XML to to text and other formats

A branch is created to track each version of the draft, i.e. 00, 01, 02, etc. Whenever a branch is ready for submission to the IETF, the following tools are used to verify and submit the draft:

* [IDNITS](https://tools.ietf.org/tools/idnits/) to verify the readiness of the resulting text version of the file for submission
* [Internet-draft submission](https://datatracker.ietf.org/submit/) to submit updated version

After a draft has been submitted, the branch in which is exists is merged with the "main" branch and a new branch is created for the next version.
