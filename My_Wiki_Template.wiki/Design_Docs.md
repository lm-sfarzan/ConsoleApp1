This folder is for storing any design document that you will create while developing the project.

> A technical specification document outlines how you’re going to address a technical problem by designing and building a solution for it. It’s sometimes also referred to as a technical design document, a software design document, or an engineering design document. It’s often written by the engineer who will build the solution or be the point person during implementation, but for larger projects, it can be written by technical leads, project leads, or senior engineers. These documents show the engineer’s team and other stakeholders what the design, work involved, impact, and timeline of a feature, project, program, or service will be.

| Document                                  | Details                                                   | Status                     |
| ----------------------------------------- | --------------------------------------------------------- | -------------------------- |
| [Design Document Template](https://github.com/sinafarzan/My_Wiki_Template/wiki/Design_Docs#design-document) | A template for documenting design for a technical problem | <WIP/Implemented/Archived> |



# [Title] Design Document

Author: [Your Name]

## Introduction

### Rationale

What are you trying to accomplish? What’s wrong with things the way they are now?

### Background

Describe any historical context that would be needed to understand the document, including legacy considerations.

### Terminology

If the document uses any special words or terms, list them here.

### Non-Goals

If there are related problems that you have decided not to address with this design, but which someone might conceivably expect you to solve, then list them here.

## Proposed Design

Start with a brief, high-level description of the solution. The following sections will go into more detail.

### System Architecture

If the design consists of a collaboration between multiple large-scale components, list those components here — or better, include a diagram.

### Data Model

Describe how the data is stored. This could include a description of the database schema.

### Interface/API Definitions

Describe how the various components talk to each other. For example, if there are REST endpoints, describe the endpoint URL and the format of the data and parameters used.

### Business Logic

If the design requires any non-trivial algorithms or logic, describe them.

### Migration Strategy

If the design incurs non-backwards-compatible changes to an existing system, describe the process whereby entities that depend on the system are going to migrate to the new design.

## Impact

Describe the potential impacts of the design on overall performance, security, and other aspects of the system.

## Risks

If there are any risks or unknowns, list them here. Also if there is additional research to be done, mention that as well.

## Alternatives

If there are other potential solutions which were considered and rejected, list them here, as well as the reason why they were not chosen.