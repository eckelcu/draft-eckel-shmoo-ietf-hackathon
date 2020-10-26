---
title: "Finding code associated with IETF Internet-Drafts"
abbrev: "finding-code"
docname: draft-eckel-finding-code
category: info

ipr: trust200902
area: General
workgroup: edm
keyword: Internet-Draft

stand_alone: yes
pi: [toc, sortrefs, symrefs]

author:
 -
    ins: C. Eckel
    name: Charles Eckel
    organization: Cisco Systems
    email: eckelcu@cisco.com

normative:
  RFC2119:

informative:



--- abstract

IETF Hackathons encourage developers to collaborate and develop utilities, ideas, sample code and solutions that show practical implementations of IETF standards. 
This document provides a set of best practices for running IETF Hackathons.

--- middle

# Introduction

Code can exist and be publicly accessible in many places. One common place is GitHub. The IETF chartered the GitHub Integration and Tooling (GIT) working group to establish and document practices and policies for use of GitHub by working groups for managing their work. This resulted in RFC 8874, which provides a set of guidelines for working groups that choose to use GitHub for their work, and RFC 8875, which specifies a set of administrative processes and
conventions for such working groups. Within the working group, the concept of work is limited to the development of Internet-Drafts. Any concept of code is limited to that which appears as text within an Internet-Draft. In many cases, there is additional code that is closely associated with the Internet-Draft but not contained within it. This code may be of interest to the community of people contributing to the development of the Internet-Draft or to its implementation or deployment. This Internet-Draft provides a set of practices aimed at making it easier to share and find such code. Note, it is expected that a subset this code may continue to be of interest after the Internet-Draft that becomes an RFC. This topic is outside the current scope of this Internet-Draft.

# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.

# GitHub Orgs and GitHub Repositories

# RFC 7942 – Implementation Status, 
Vijay wrote, “The proposal we are considering --- i.e., putting some text in RFCs to guide legions of implementers not familiar with "IETF arcana" --- is already being used loosely as I pointed out above for QUIC.  It seems to me that we can do better by institutionalising it in some manner that RFC 7942 did not. Perhaps as you suggest, the answer is to simply write a RFC 7942-bis draft.  If you think this is an avenue we should explore, I am happy to spin up a rfc7942-bis  so to provide more structure to the conversation.”
Mirja wrote, “Just very quickly some points. Having read all RFCs that we have published in the four years of my AD time I can tell you that RFC7942 is used form time to time. However, it also addresses a different problem then what you ask for, namely how do people in the wg know about existing implementations. QUIC decides to use another tool for this purpose; I guess for several reason, one being that many implementors in QUIC who have been new to the IETF are actually more familiar with GitHub than any IETF procedures. My expectation is that note you mentioned for QUIC will be removed before publication as RFC.”

# Proposal from Tommy and Mark
How about a link in data tracker to take you to said COTS service? (With a standard template, etc).
My .02 -- I'd very much rather track this sort of thing in COTS services (e.g., GitHub) rather than commissioning yet another expensive, one-off, badly-maintained datatracker feature.

# Datatracker Mechanisms
A few releases ago, we changed the way the datatracker allows you to 
make references to external resources (see the section labelled 
Additional Resources on a document's main page or on a groups /about page).

If you are using github for your working group or a set of drafts, 
please consider pointing to the repository or organization using the 
github_repo and github_org tags respectively. The datatracker will use 
the urls you provide with those tags to backup the repositories.

(You'll see github and gitlab username tags in the hint for the edit 
form - those are not used by the backup mechanism - there is no need to 
enter any such thing for this purpose).

RjS

# Security Considerations

Participant email addresses.


# IANA Considerations

This document has no IANA actions.



--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
