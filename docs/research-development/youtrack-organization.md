# YouTrack Issue Organization

## Overview

The Research and Development team coordinates their work inside the DaSCH Service Platform project on [YouTrack](https://dasch.myjetbrains.com/youtrack/issues/DSP).

## Issue Types
For the project, the following issue types are defined.

### Theme
Describes an overal theme that the issues organized under it share.

### Epic
Describes a larger User Story, which typically can be broken down in smaller ones
(User Stories).

### User Story
It's tempting to think that user stories are, simply put, software system requirements. But they're not.

A key component of Agile software development is putting people first, and user-stories put actual end users at the center of the conversation. Stories use non-technical language to provide context for the development team and their efforts. After reading a user story, the team knows what they are building, why they're building, and what value it creates. 

User stories are one of the core components of an Agile program. They help provide a user-focused framework for daily work — which drives collaboration, creativity, and a better product overall.

#### What are User Stories?
A user story is the smallest unit of work in an Agile framework. It’s an end goal, not a feature, expressed from the software user’s perspective.

The purpose of a user story is to articulate how a piece of work will deliver a particular value back to the customer. Note that "customers" don't have to be external end users in the traditional sense, they can also be internal customers or colleagues within your organization who depend on your team.

User stories are a few sentences in simple language that outline the desired outcome. They don't go into detail. Requirements are added later, once agreed upon by the team.

Stories fit neatly into Agile frameworks like Scrum. In Scrum, user stories are added to sprints and “burned down” over the duration of the sprint. It’s this work on user stories that helps Scrum teams get better at estimation and sprint planning, leading to more accurate forecasting and greater agility.

User stories are also the building blocks of larger agile frameworks like epics and themes. Epics are large work items broken down into a set of stories, and multiple epics comprise an theme. These larger structures ensure that the day to day work of the development team (on stories) contributes to the organizational goals built into epics and themes.

#### Why create User Stories?
For development teams new to Agile, user stories sometimes seem like an added step. Why not just break the big project (the epic) into a series of steps and get on with it? Because stories give the team important context and associate tasks with the value those tasks bring.

User stories serve a number of key benefits:
- Stories keep the focus on the user. A To-Do list keeps the team focused on tasks that need checked off, but a collection of stories keeps the team focused on solving problems for real users;
- Stories enable collaboration. With the end goal defined, the team can work together to decide how best to serve the user and meet that goal;
- Stories drive creative solutions. Stories encourage the team to think critically and creatively about how to best solve for an end goal;
- Stories create momentum. With each passing story the development team enjoys a small challenge and a small win, driving momentum.


#### Working with User Stories
Once a story has been written, it’s time to integrate it into your workflow. Generally a story is written by the product owner, but can also be written by the development team.

During a sprint planning meeting, the team decides what stories they’ll tackle that sprint. Teams now discuss the requirements and functionality that each user story requires. This is an opportunity to get technical and creative in the team’s implementation of the story. Once agreed upon, these requirements are added to the story.

Another common step in this meeting is to score the stories based on their complexity or time to completion. Teams use t-shirt sizes, the Fibonacci sequence, or planning poker (e.g., https://firepoker.io/) to make proper estimations. A story should be sized to complete in one sprint, so as the team specs each story, they make sure to break up stories that will go over that completion horizon. 

#### How to write User Stories?
Consider the following when writing user stories:
- Use the "As a ..., I want to ... , so that ...." template to write the user story
- Definition of “Done” --- The story is generally “done” when the user can complete the outlined task, but make sure to define what that is.
- Outline subtasks or tasks --- Decide which specific steps need to be completed and who is responsible for each of them.
- User personas --- For Whom? If there are multiple end users, consider making multiple stories.
- Ordered Steps --- Write a story for each step in a larger process, i.e., break the large story into smaller story type steps, and thus making the parent user story an Epic.
- Listen to feedback --- Talk to your users and capture the problem or need in their words. No need to guess at stories when you can source them from your customers.
- Time --- Time is a touchy subject. Many development teams avoid discussions of time altogether, relying instead on their estimation frameworks. Since stories should be completable in one sprint, stories that might take weeks or months to complete should be broken up into smaller stories or should be considered their own epic.

Once the user stories are clearly defined, make sure they are visible for the entire team (https://dasch.myjetbrains.com).

#### User Story Template and Examples

[User Story template for YouTrack issues.](https://dasch.myjetbrains.com/youtrack/newIssue?project=DSP&summary=User%20Story&description=***As%20a%20%5BUSER%5D%2C%20I%20want%20to%20%5BFEATURE%5D%20so%20that%20%5BGOAL%5D.***%0A%0A**Definition%20of%20%C2%AB%20done%20%C2%BB**%0A*Describe%20your%20definition%20of%20done.*%0A%0A**Outline%20tasks**%0A*List%20your%20tasks%20you%20should%20realise%20and%20who%20is%20doing%20what%20(in%20case%20of%20several%20developers%20involved).*%0A%0A**User%20(personas)**%0A*List%20the%20*%0A%0A**%5Boptional%5D%20Ordered%20steps**%0A*If%20the%20user%20story%20is%20part%20of%20an%20epic%20or%20related%20to%20%2F%20depends%20on%20an%20other%20user%20story%2C%20indicate%20the%20realisation%20steps%20during%20the%20process.%20E.g.%20Step%202%20(step1%3A%20DSP-12%2C%20step3%3A%20DSP-18)*%0A%0A**%5Boptional%5D%20Additional%20information%20(links%2C%20screen%20shots%2C%20feedback)**%0A*Add%20links%2C%20screen%20shots%20or%20people%20feedback%20about%20this%20user%20story.*&c=Type%20User%20Story)


User stories are often expressed in a simple sentence, structured as follows:

**“As a [persona], I [want to], [so that].”**

Breaking this down: 

- "As a [persona]": Who are we building this for? We’re not just after a job title, we’re after the persona of the person. Max. Our team should have a shared understanding of who Max is. We’ve hopefully interviewed plenty of Max’s. We understand how that person works, how they think and what they feel. We have empathy for Max.
- “Wants to”: Here we’re describing their intent — not the features they use. What is it they’re actually trying to achieve? This statement should be implementation free — if you’re describing any part of the UI and not what the user goal is you're missing the point.
- “So that”: how does their immediate desire to do something fit into their bigger picture? What’s the overall benefit they’re trying to achieve? What is the big problem that needs solving?

For example, user stories might look like:

- As Max, I want to invite my friends, so we can enjoy this service together.
- As Sascha, I want to organize my work, so I can feel more in control. 
- As a manager, I want to be able to understand my colleagues' progress, so I can better report our successes and failures. 

This structure is not required, but it is helpful for defining done. When that persona can capture their desired value, then the story is complete. Teams are encouraged to define their own structure, and then to stick to it.

#### Further Examples
Story:
- As a project admin
- I want to retrieve all members of a project
- So that I can see which users are part of the project

This story, to be implemented, needs to be split into possibly two or more Tasks:

- Add route to DSP-API
- Add project members component to DSP-APP
- Add members list component to DSP-UI-LIB
- Add route to DSP-JS-LIB
- Add methods to DSP-PY-LIB
- Add unit tests to DSP-APP and DSP-UI-LIB
- Add feature documentation to DSP-DOCS

The user story template should only be used as a guideline and not as a rigid rule. In discussions between team members, the full scope of a story will become clear.

A user story needs to be broken down if its implementation concerns different subsystems of the DaSCH Service Platform.

### What about "developer" user stories?

This:

- As a developer, I want to implement improved logging of errors so that I can more easily diagnose problems reported to me.

should be added as a task:

- Implement improved logging of errors to more easily diagnose reported problems.

### Tasks
Describe any kind of work that needs to be done to implement a User Story or fix a Bug.

The user stories are moved from the product backlog during sprint planning to the sprint backlog. At the same time, the user story is broken down into Tasks which become part of the sprint backlog.

Typically there is at least one task per involved subsystem and/or developer. 

A task, in contrast to a User Story, is typically something like code this, design that, create test data for such-and-such, automate that, and so on. These tend to be things done by one person.

In general, tasks should have a time estimate and the effective time spent attached to it.

Examples:
- Add route to `DSP-API`
- Add project members component to DSP-APP
- Add members list component to DSP-UI-LIB
- Add route to DSP-JS-LIB
- Add methods to DSP-PY-LIB
- Add unit tests to DSP-APP and DSP-UI-LIB
- Add feature documentation to DSP-DOCS
- Cl-ean up xy
- Add tests
- Bump version of library xyz

### Bug

[Bug Template for YouTrack issues](https://dasch.myjetbrains.com/youtrack/newIssue?project=DSP&summary=Bug&description=**Describe%20the%20bug**%0AA%20clear%20and%20concise%20description%20of%20what%20the%20bug%20is.%0A%0A**To%20Reproduce**%0ASteps%20to%20reproduce%20the%20behavior%3A%0A1.%20Go%20to%20'...'%0A2.%20Click%20on%20'....'%0A3.%20Scroll%20down%20to%20'....'%0A4.%20See%20error%0A%0A**Expected%20behavior**%0AA%20clear%20and%20concise%20description%20of%20what%20you%20expected%20to%20happen.%0A%0A**Screenshots**%0AIf%20applicable%2C%20add%20screenshots%20to%20help%20explain%20your%20problem.%0A%0A**Desktop%20(please%20complete%20the%20following%20information)%3A**%0A%20-%20OS%3A%20%5Be.g.%20iOS%5D%0A%20-%20Browser%20%5Be.g.%20chrome%2C%20safari%5D%0A%20-%20Version%20%5Be.g.%2022%5D%0A%0A**Smartphone%20(please%20complete%20the%20following%20information)%3A**%0A%20-%20Device%3A%20%5Be.g.%20iPhone6%5D%0A%20-%20OS%3A%20%5Be.g.%20iOS8.1%5D%0A%20-%20Browser%20%5Be.g.%20stock%20browser%2C%20safari%5D%0A%20-%20Version%20%5Be.g.%2022%5D%0A%0A**Additional%20context**%0AAdd%20any%20other%20context%20about%20the%20problem%20here.&c=Type%20Bug)

Describes an user facing defekt.

Bugs are prioritized (e.g., high, normal, low) issues which describe a defect in the DaSCH Service Platform. These defects can affect either the current released version or the next major version in development.

If a bug affects the current released (deployed) version of the platform, then it is immediately put on the board of the running sprint. Bugs with high priority should be solved during the running sprint, while normal and low priority bugs can be moved to the next sprint if necessary. Any bugs moved to the next sprint should be re-prioritized to “high” if they are not already, thus making sure that they are not pushed back again.

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

- Theme: Lists
    - User Story: Edit List Item (DSP-737)
        - Task: Edit list item (Backend)
        - Task: Edit List Item (JS-Lib)
        - Task: Edit List item (UI-LIB)
        - Task: Edit List item (DSP-APP)
        - Task: Edit List item (DSP-TOOLS)
    - User Story: Hierarchical lists (DSP-713)




1. The organization between subsystems is done at the level of a User Story and the dependencies are reflected in the Tasks with defined dependencies.
1. User Stories should be tagged with a future release, reflecting the global priorization.
