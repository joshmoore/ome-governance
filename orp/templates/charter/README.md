# Charter for an OME Registered Project (ORP)

## **Overview**

This document formalizes the default governance for an individual OME
Registered Project (ORP). It is a meritocratic, consensus-based, and
self-governing process, akin to the Apache model. The primary goal is to
empower developers, streamline the development process, and maintain the
project's stability and continuity while adhering to the overarching principles
of the overall OME Project.

Projects are encouraged to start with this template and adapt it to their
needs. Projects may deviate from this template for good reasons; we suggest
starting here and evolving as the project matures.

## **Roles and Responsibilities**

### **Users**

Users are members of the community who utilize the project. Their
contributions, such as providing feedback, reporting bugs, and general
evangelism, are essential for the project's purpose and direction.

### **Contributors**

Contributors are community members who engage directly with the project in concrete ways, such as:

- Proposing, discussing, or reviewing a change to the code, documentation, or specification via a pull request.
- Reporting issues through public channels.
- Assisting with documentation or project infrastructure.
- Supporting new users.

All community members are encouraged to contribute. Contributions should be
made in compliance with the OME Project's
[Code of Conduct](https://github.com/ome/governance/blob/master/code-of-conduct/README.md).

### **Project Steering Committee (PSC)**

The Project Steering Committee (PSC) serves as the governing and administrative
body for the individual Registered Project. It is equivalent to the Project
Management Committee (PMC) in an Apache-governed project.

- Function: The PSC have administrative rights and make decisions, such as
  accepting or rejecting pull requests, and managing administrative actions
  within the project's repositories (e.g. adding/removing members). A group of
  one is acceptable for small projects.
- Authority: The PSC is self-governing and its membership is not overseen by
  the OME Management Group (OMG). The membership of this group, its processes,
  meeting minutes and any other material should be clearly findable by the
  community.
- Membership is Merit-Based: Any contributor is eligible to join the PSC.
  - Nomination: Existing PSC members can nominate new members. Nominations must
    be based on clear evidence of sustained, quality contribution to the
    project. Approval is subject to vote by the existing PSC (ideally
    consensus, but at minimum majority approval).
  - Removal: PSC members who become inactive can and should be removed via a
    majority vote of the existing PSC.

### **PSC Chair**

Larger projects should have a Chair. The Chair's role is to act as a
coordinator and facilitator for the group's activities and discussions. The
Chair holds no additional authority over other PSC members. The Chair is
optional for smaller projects.

## **Decision Making Process**

Decisions should be made in accordance with the mission and values of the OME
Project.

### **Consensus-Seeking and Voting**

The project aims for consensus among PSC members for all decisions. If
consensus cannot be reached after discussion, decisions will be resolved by
falling back on a majority vote of the PSC.

### **Lazy Consensus for Day-to-Day Operations**

Lazy Consensus is used for most day-to-day decisions, allowing the majority of
contributions to proceed efficiently.

- Minor Documentation Changes (e.g. typo fixes): Require approval by a Core
  Developer and no disagreement or requested changes from any Core Developer
  within a reasonable time (e.g. one working day).
- Code Changes and Major Documentation Changes: Require agreement by one Core
  Developer and no disagreement or requested changes from any Core Developer
  within a reasonable time (e.g. a few working days).
- Objections: If a Core Developer raises an objection to a proposal under lazy
  consensus, the proposal is escalated to the full group for a
  consensus-seeking discussion or a majority vote.

## **Code of Conduct**

All Registered Projects must adhere to the OME Project's
[Code of Conduct](https://github.com/ome/.github/blob/master/CODE_OF_CONDUCT.md).

## **License and Attribution**

This governance document is adapted from the original Zarr governance document
and the [Meritocratic governance model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel)
by Ross Gardler and Gabriel Hanganu (licensed under a Creative Commons
Attribution-ShareAlike 4.0 International License).
