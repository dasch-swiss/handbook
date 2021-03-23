# YouTrack Issue Organization

## Overview

The Research and Development team can visualize and manage their work issues inside the DaSCH Service Platform project on [YouTrack](https://dasch.myjetbrains.com/youtrack/issues/DSP).

## Issue Types

For the project, the following issue types are defined.

### Theme / Initiative

Describe categories in which issues are classified by relevant topic.

### Epic

Describe a feature or a part of a feature that will be implemented over one or several iterations of work. An epic must deliver a workable piece of code (from backend to frontend).
It is broken down and detailed by 2 types of issues: user stories and tasks. They are both complementary, at the same level in the issue hierarchy.

### User Story

Describe a feature in an informal, non-technical language  from the perspective of an end user. It contains a short but explicit description, the context, the contact person for questioning and mockups or prototypes. After reading a user story, the team knows what they are building, why they're building, and what value it creates.

User stories are written by the product management team.

### Task

Describe a part of a feature in a technical language. A task can be a new feature, an improvement or a bug fix.

Tasks are written by developers based on the user story requirements.

## Workflow

The Product Management (PM) team creates themes and epics based on the current roadmap and priorities. For each epic, one or several user stories are written following the defined template and added to the Youtrack board.

For each epic, the relevant developers participate in a meeting with one of the PM members who explains the epic and the user stories.

The developers then create one or several tasks with technical specifications based on the user story requirements. A task should be created for each subsystem involved. The workflow and the estimation of time are also defined.

## Templates

### User Story template

Describe an iteration to achieve a working feature or a working part of it.

It is written by the Product Management team, in an informal language, following this template:

Who: “As a [persona*], --> [Persona definition](https://docs.google.com/document/d/1fTPaEq9Ks6tn5R1T1ZMEvynb7GpNPNX5buvVtklk0eo/edit)

What: I want to [do something],

Why: so that I can [solve a problem]”

Definition of done OR Expected behaviour

Background information

Contact person for questioning

Additional information

Corresponding Mockup and/or Prototype

Once the user stories are clearly defined, they are visible for the entire team on [Youtrack](https://dasch.myjetbrains.com).

### Task template

Describe any kind of work that needs to be done to implement a User Story or fix a Bug.

The user story is broken down in a technical way into tasks which become part of the sprint backlog.

Typically there is at least one task per involved subsystem and/or group of developers.

A task, in contrast to a user story, is typically something like code this, design that, create test data for such-and-such, automate that, and so on.

In general, tasks should have a time estimate and the effective time spent attached to it.

Examples:

- Add route to `DSP-API`
- Add project members component to DSP-APP
- Add members list component to DSP-UI-LIB
- Add route to DSP-JS-LIB
- Add methods to DSP-PY-LIB
- Add unit tests to DSP-APP and DSP-UI-LIB
- Add feature documentation to DSP-DOCS
- Clean-up xy
- Add tests
- Bump version of library xyz

### Bug template

[Bug Template for YouTrack issues](https://dasch.myjetbrains.com/youtrack/newIssue?project=DSP&summary=Bug&description=**Describe%20the%20bug**%0AA%20clear%20and%20concise%20description%20of%20what%20the%20bug%20is.%0A%0A**To%20Reproduce**%0ASteps%20to%20reproduce%20the%20behavior%3A%0A1.%20Go%20to%20'...'%0A2.%20Click%20on%20'....'%0A3.%20Scroll%20down%20to%20'....'%0A4.%20See%20error%0A%0A**Expected%20behavior**%0AA%20clear%20and%20concise%20description%20of%20what%20you%20expected%20to%20happen.%0A%0A**Screenshots**%0AIf%20applicable%2C%20add%20screenshots%20to%20help%20explain%20your%20problem.%0A%0A**Desktop%20(please%20complete%20the%20following%20information)%3A**%0A%20-%20OS%3A%20%5Be.g.%20iOS%5D%0A%20-%20Browser%20%5Be.g.%20chrome%2C%20safari%5D%0A%20-%20Version%20%5Be.g.%2022%5D%0A%0A**Smartphone%20(please%20complete%20the%20following%20information)%3A**%0A%20-%20Device%3A%20%5Be.g.%20iPhone6%5D%0A%20-%20OS%3A%20%5Be.g.%20iOS8.1%5D%0A%20-%20Browser%20%5Be.g.%20stock%20browser%2C%20safari%5D%0A%20-%20Version%20%5Be.g.%2022%5D%0A%0A**Additional%20context**%0AAdd%20any%20other%20context%20about%20the%20problem%20here.&c=Type%20Bug)

Describes a user facing defect.

Bugs are prioritized (e.g., high, normal, low) issues which describe a defect in the DaSCH Service Platform. These defects can affect either the current released version or the next major version in development.

If a bug affects the current released (deployed) version of the platform, then it is immediately put on the board of the running sprint. Bugs with a high priority should be solved during the running sprint, while normal and low priority bugs can be moved to the next sprint if necessary. Any bugs moved to the next sprint should be re-prioritized to “high” if they are not already, thus making sure that they are not pushed back again.

With two weeks per sprint, a high priority bug should thus be solved in those two weeks. A normal or low priority bug moved to the next sprint will thus be solved at the latest in 4 weeks. A bugfix release can then be planned, which will incorporate only the bug fixes.

If a bug affects the current development version, i.e., the next major version in development, then it should be put on the board by the team during regular Sprint Planning and solved before the next major version of the platform is released.

## Subsystems

The DaSCH Service Platform (DSP) consists of multiple subsystems. The subsystems usually live in their own Github repository. These are:

- `DSP-API`: https://github.com/dasch-swiss/dsp-api
- `DSP-APP`: https://github.com/dasch-swiss/dsp-app
- `DSP-UI-LIB`: https://github.com/dasch-swiss/dsp-ui-lib 
- `DSP-JS-LIB`: https://github.com/dasch-swiss/dsp-js-lib
- `DSP-TOOLS`: https://github.com/dasch-swiss/dsp-tools
- `DSP-DOCS`: https://github.com/dasch-swiss/dsp-docs

The DaSCH Service Platform has a global release schedule, for which then the individual subsystems need to be released. A user story consisting of tasks with hard dependencies (aka “breaking changes”) can only be released as a whole. Tasks with soft dependencies (aka “non-breaking changes) can be released independently.

## Example

- Theme: Permissions
  - Epic: Get and display permissions for a project (DSP-123)
    - User Story: Display existing group permissions (incl. mockups)
    - Task: Refactor hasPermissions object structure (Backend)
    - Task: Get permissions from the API (Frontend)
    - Task: Table view with groups and given permissions (Frontend)

1. The organization between subsystems is done at the level of tasks as well as the dependencies.
1. User Stories should be tagged with a future release, reflecting the global priorization.
