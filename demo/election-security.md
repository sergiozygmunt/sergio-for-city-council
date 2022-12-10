---
title: Election Security
description: 
permalink: /election-security/

layout: page

---

## Ensuring a secure election
There are a lot of moving pieces in the election system to ensure that an election is secure and fair. For starters, the federal government has its own standards for election security and accessability with the Help Americans Vote Act and other laws.

Next, the State of California has its own security policies, such as requiring paper ballots or Voter Verified Paper Audit Trails when using electronic voting machines.

Finally, the County of San Mateo has its own policies to ensure secure and fair elections. 

While these dedicated teams all do an excellent job at ensuring that elections are safe and fair, individual candidates and campaigns also play a role in ensuring secure elections.

## Doing our part
A lot of people don't recognize the role individual candidates (and their committees) play in ensure a secure and fair election. Throughout the normal corse of an election cycle, candidates receive and process a lot of personal information about voters. Candidates receive the full voter registration database which contains voters' names, home/mailing addresses, dates of birth, location of birth, voting history, and party affiliation, to name a few. 

### Some of the things our campaign is doing 
+ Encrypting persistent storage where voter data is stored.
+ Requiring hardware-based (FIDO 2) multi factor authentication into all systems that contain voter or campaign information. We require security keys (Yubikeys) because they make it next to impossible to phish campaign team members.
+ Use branch protection on all Git repositories (including the build repository for this site) to ensure that all Git commits are signed.
+ Proactively archive this website (and documents posted on it) in the WayBack Machine to ensure the integrity of the site isn't compromised if it goes offline in the future.

### What information do we store?
We publish a [list of what data we store and where we process it](/voter-data).