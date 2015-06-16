Agile Working Agreement
=======================

The Simpler's agile teams working agreement outlines our Agile process,
each role's responsibilities, and any other agreements around working
times, locations, etc. This is an evolving document, PRs are encouraged :)

Agile Process & Schedule
--------------------

Iterations: Weekly

Mondays:

- 10:00 (20 minute timebox) Demos
- 10:20 (20 minute timebox) Retro - Pros/Deltas
- 10:40 (40 minute timebox) Retro - Action Items
- 11:20 (10 minute timebox) Iteration Kickoff

Tuesdays:

- 1:00 (25 minute timebox) Story Grooming

#### Demo

Each developer demos their stories that have been deployed to staging for
the iteration.

#### Retro - Pros/Deltas

As a team, we'll discuss the pros and deltas of our experiences during
the iteration. Pros are the experiences that made our job easy and
effective. Deltas are the experiences that made our job difficult.
We'll reflect on the pros to see if there's an opportunity to further grow in
that direction, and we'll reflect on the deltas to see what we can do to
improve any pain points or inefficiencies. 

#### Retro - Action Items

The net result of the retrospective will be an action item list to promote the
pros and address the deltas. Each action item should assigned to an individual
and acted on immediately or prioritized in our backlog. We will also
review the prior action items as a follow-up.

#### Iteration Kickoff

Assuming the stories are well groomed over the past two weeks, the team
reviews the plan for the week, reviews any recent story updates, and
agrees on the plan.

#### Story Grooming

Story grooming is an exercise between the Product Owner and the
development team.

The **Product Owner's responsibility** is to set/communicate goals, and curate a 
prioritized list of stories to meet those goals for the following 2 iterations
(e.g. the story grooming meeting held Tuesday June 2nd would
include stories in Tracker through Friday June 19th).
The Product Owner presents to the development team each story with and idea of
acceptance criteria. Acceptance criteria outlines details necessary to
ensure that the feature successfully fulfills it's business requirements.

The **development team's responsibility** is to ask for any clarification and
details that they need in order to properly weight and complete the story.

Pivotal Tracker Story States
------------------------------

- **Started** - Developer is actively working on the story.
- **Finished** - Developer submits a pull request.
- **Delivered** - Developer merges in the pull request to the main branch
(CircleCI will automatically deploy to staging if the build passes).

Definition of Ready
-------------------

The "definition of ready" outlines what the user story should contain in
order for the user story to be ready for the developer to start.

- User story titles and descriptions using **accurate domain terminology**.
- Attach **screenshots of mockups** outlining the user work flow and general
  layout of what's to be built. This doesn't have to be overly detailed. Its
  purpose is to eliminate high-level design questions so the developer
  can focus on executing without having to worry about making high-level
  design decisions.
