---
title: "Running an IETF Hackathon"
abbrev: "ietf-hackathon"
docname: draft-eckel-shmoo-ietf-hackathon
category: info

ipr: trust200902
area: General
workgroup: shmoo
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
This document provides a set of practices for running IETF Hackathons.

--- middle

# Introduction

IETF Hackathons encourage developers to collaborate and develop utilities, ideas, sample code and solutions that show practical implementations of IETF standards. 
IETF Hackathons aim to:

* Advance the pace and relevance of IETF standards activities by bringing the speed and collaborative spirit of open source development into the IETF
* Bring developers and young people into IETF and get them exposed to and interested in IETF

IETF Hackathons are free to attend and open to everyone. They are collaborative events, not competitions. Any competitiveness among participants is friendly, and in the spirit of advancing the pace and relevance of new and evolving internet standards. 

This document provides a set of practices for running IETF Hackathons.

# Conventions and Definitions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this
document are to be interpreted as described in BCP 14 {{RFC2119}} {{!RFC8174}}
when, and only when, they appear in all capitals, as shown here.

# Roles and Responsibilities

## Hackathon Chair(s)

The role of a hackathon chair is similar to that of a working group chair. As with working groups, it is typically best to have co-chairs share responsibilities and workload. Key responsibilities include:

* Organize and deliver a hackathon at each IETF meeting, soliliciting help from all other roles to do much of the heavy lifting
* Encourage and provide guidance to champions who volunteer to lead projects
* Maintain the hackathon wiki (e.g. https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon) and all of its child pages.
* Moderate hackathon@ietf.org email list
* Request sessions for hackathon opening and closing at IETF meeting (i.e. https://datatracker.ietf.org/secr/sreq/)
* Emcee the hackathon, including the opening and closing sessions and announcements in between
* Create and manage the GitHub repo used for each Hackathon (e.g. [https://github.com/IETF-Hackathon/ietf108-project-presentations](https://github.com/IETF-Hackathon/ietf108-project-presentations)
* Main point of contact for all Hackathon questions and concerns


## Secretariat

* Configure and manage Hackathon registration system
* Maintain web page for Hackathons https://www.ietf.org/how/runningcode/hackathons/
* Create web page for each Hackathon (e.g. https://www.ietf.org/how/runningcode/hackathons/109-hackathon/)
* Create wiki page for each Hackathon (e.g. https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon). This is initialized and updated at times by the Secretariat, but the Chair(s) are ultimately responsible for maintaining it.
* Handle venue logistics for Hackathon (e.g. reserve room, food and beverages, AV, etc.)
* Internal IETF promotion (e.g. email messages to community)
* Assist with external outreach, as needed

## Hackathon Sponsor

* Sponsor cost of Hackathon (either per meeting or per year, depending on model)
* If desired, provide t-shirts or other giveaways
* May provide support staff to assist with Hackathon (not required)

## Champions of Projects

Champions of projects are the key to a successful Hackathon. Key responsibilities for champions include:

* Volunteer to lead a project at the Hackathon
* Serve as primary contact for the project
* Add and manage information on the Hackathon wiki for the project
* Promote the project to appropriate groups inside IETF and outside as well
* Welcome and organize members of the team
* Provide focus, guidance, and leadership for the project

## IETF LLC, Director of Communications and Operations (was ISOC)

* External (outside world) promotion
* Outreach to local universities
* Provide photographer

## Judges

The first several hackathon involved judges who listened to summary presentations by teams at the closing of each hackathon and identified winning teams for an arbitrary number of project categories. Prizes were made available to members of winning teams. This was done as an incentive to participate in the Hackathon and present results, and  to provide a fun yet informative end to the Hackathon that could be appreciated by the entire IETF community. Judging and awarding of prizes led to confusion regarding the nature of the Hackathon, making it appear to some overly competitive. Procurement of appropriate prizes was financially and logistically challenging. Arrangement of judges, determination of winners, and awarding of prizes all became more time consuming, especially as the number of projects and participants grew. Ultimately, it was deemed best to eliminate judging, awards, and prizes entirely. Apparently the IETF community has an innate incentive to participate and present results in the Hackathon. 

# Timing

The first IETF Hackathon was held the weekend before the start of the IETF 92 meeting. The rationale was to avoid conflicts yet make it relatively convenient for those attending the IETF meeting to participate in the hackathon as well. Holding the hackathon on the weekend was also viewed as making it more accessible to non IETF meeting attendees, including students and working professionals who would have other commitments during the week. The weekend before was viewed as better than the weekend after such that things learned during the hackathon could be shared and discussed with the rest of the IETF community during working group sessions and the like. This worked well at IETF 92, was repeated at IETF 93, and quickly became an established norm with the IETF meeting being officially extended to include the hackathon at the start.


## Online Timing

See Online Only section.



# Technology

The IETF Hackathon makes use of the same tooling used by the IETF community for its work and meetings. This includes a combination of the [Datatracker](https://datatracker.ietf.org/), [IETF Website](https://www.ietf.org/how/runningcode/), the [Meeting Wiki](https://trac.ietf.org/trac/ietf/meeting/wiki), [GitHub](https://github.com/ietf-hackathon), [Meetecho](https://www.meetecho.com/), [Webex](https://ietf.webex.com/webappng/sites/ietf/dashboard?siteurl=ietf), and [Gather](https://gather.town/).

## Datatracker

Hackathon “Team” in the Datatracker
The Datatracker now supports the notion of teams that are not a part of the standards development process (e.g. EDU team). This means that we could create rolls in the Datatracker for the Hackathon Chair, Technology Champion, etc. and manage content, work, etc. within the Datatracker. Would you like to explore this?
* Yes

# Statistics and Metrics

# Aux Events

## Hackdemo Happy Hour

Hackdemo Happy Hour provides an opportunity for more in depth sharing and discussion than is possible within the time constraints of the result presentation that occur at the end of the hackathon. This opportunity is made available to all teams. As with the results presentation, participation is optional. 

Initially, we did something similar as part of Bits and Bites. This worked well for the hackathon but the Bits and Bites event was eventually abandoned for other reasons. Hackademo Happy Hour was created as a low cost, informal event to provide a venue for the IETF community to engage with the Hackathon teams in more in depth discussions related to their projects. 

Hackdemo Happy Hour is typically Monday evening, roughly from 18:00 - 19:30, often overlapping a bit with the last working group session of the day but continuing long enough to allow everyone an opportunity to join. The goal is to make it convenient to attend by not conflicting with other meetings but also no running too late into the night. 

Light snacks and non alcoholic beverages are provided, and a cash bar is available to align with the spirit of a happy hour.

## Code Sprint 

How can the Hackathon and the Code Sprint work together or potentially be combined (a single two-day event focusing on the development of IETF protocols AND IETF internal tools)? There is some concern that the events currently compete for resources, but I see a lot of synergistic potential and would like to help realize that potential. 
* I proposed combining for Prague, but Henrik and Robert were very against it.
* I still think it is a good idea.
* We had projects creating IETF tools in Hackathon in Dallas and again in Prague  

# Online Only

IETF 107 Hackathon was originally scheduled to be the weekend at the start of the IETF meeting in Vancouver. When COVID-19 hit and it became clear the IETF meeting could not occur in person, the hackathon already had 23 projects and 176 registrations. With only 10 days until the anticipated start of the hackathon, a survey went out to the hackathon community, including all project champions and registered participants, to see if they wanted to participate in the hackathon exactly as planned except with everyone participating remotely rather than in person. A relatively small number of people expressed interest in participating, with even fewer wanting to continue to champion their projects. The fact that the hackathon was planned for the weekend before the IETF meeting and in the local time zone, both of which were historically very convenient and attractive to hackathon participants, suddenly became huge obstacles. Consequently, the IETF 107 Hackathon was cancelled.

We knew more advance that IETF 108 would be an online only meeting. We moved and expanded the schedule to run the entire work week before the rest of the IETF meeting. The hackathon kickoff was set for Monday, the closing for Friday, with all the time in between left for individual project teams to arrange to meet how and when was most convenient for them. The kickoff and closing sessions were schedule to align with the time frame established for the IETF 108 meeting. All of this was, of course, not ideal, and it worked much better for some people than for others, but at least everyone knew the plan and corresponding time commitment well in advance and had the ability to plan accordingly.

The response was great. We ultimately had 19 projects and almost 300 registrations. It is hard to say how many people actually participated and for how long, but many projects were able to get substantial work done. For the closing, 10 teams produced and shared presentations summarizing their findings and achievements. All presentations as well as the agenda and a recording of the closing session are available via the IETF 108 Hackathon [wiki]((https://trac.ietf.org/trac/ietf/meeting/wiki/109hackathon).

# Project Presentations

Project presentations are an important mechanism for capturing what each team accomplished and sharing this with the IETF community.

For the first few Hackathons, we had two very distinct types of presentations,

1. Presentation that served as project pitches at the start of the Hackathon
2. Presentations that summarizes results at the end of the Hackathon. 

## Project Pitches

The project pitches were 5-10 minute presentations by a champion of a project describing what they wanted to do and how they proposed to accomplish it. This gave everyone in the room a better understanding of all the projects and helped participants match themselves with appropriate projects. This was fantastic when we had a small number of projects, but it became unwieldy as the number of projects increased. As knowledge of the hackathon grew and advanced planning became more common, many participants knew exactly which team they planned to join and wanted to get to work as quickly as possible rather than spend a couple hours listening to presentations. Project pitches were dropped from the Hackathon. Champions are encouraged to share this type of information in advance via the Meeting Wiki instead.

## Results Summaries

The project presentations are brief summaries by each team of what problem they tried to solve, what they achieved, and highlights that include lessons learned, feedback to associated working groups, and collaboration with open source communities and other standards organizations. We also highlight individuals who are participating in their first IETF Hackathon or first IETF event to facilitate their introduction into the IETF community. The production and presentation of results summaries is optional. Fortunately, despite the lack of awards and prizes, most teams participate. 

As with the project pitches, results presentations can become unwieldy as the number of projects increases. The formula used is to limit the total time for all presentations to 2 hours and allocate time slots based on that. Time slots of minutes are typical.

All presentation are uploaded to a GitHub repo created specifically for each IETF Hackathon (e.g., [https://github.com/IETF-Hackathon/ietf108-project-presentations](https://github.com/IETF-Hackathon/ietf108-project-presentations).

The contents of this repo are used as the source for all project presentations at the end of the hackathon and remain as a reference after the hackathon. For portability, presentations are requested to be in PDF format.

One must be a member of the IETF-Hackathon GitHub org to upload a new presentation or update/replace an existing presentation.

To be added as a member, presenters are asked to

* include the name by which they are known in their GitHub profile
* enable two factor authentication (2FA)
* send your GitHub user name to the Chair(s)

Presenters are asked to do this at their earliest convenience as the Chair(s) typically get very busy as the start of presentations approaches.

### Presenting in person

Presentations are run from a shared ChromeBook at the front of the hackathon room. This Chromebook is provided by the Secretariat.

### Presenting Remotely 

Remote presenters are welcome to run their own presentations using the screen sharing functionality in Meetecho. Alternatively, the hackathon chairs can share the presentation and advance slides for the presenter. 

## IETF Survey Results

https://www.ietf.org/media/documents/survey-planning-possible-online-meetings-responses.pdf

(From L-R: Very important, Important, Neutral, Not important, Not at all important, Score (lower score is more important))
- Hackathon 6.73% 20.20% 40.65% 19.70% 12.72% 3.11

# Hackathon Survey results

tbd


# Security Considerations

Participant email addresses.


# IANA Considerations

This document has no IANA actions.



--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledgements.
