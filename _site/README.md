# Our Software Development Life Cycle
We use an agile-based approach to creating our software, from its inception to its release. This allows us to quickly adapt to changing requirements from our customers and the market, and to deliver continuously in value-added increments.

We tailor each project's workflow to it's scope, impact, and other criteria, but our standard workflow looks like this:

![SDLC Diagram](/assets/images/sdlc_diagram.webp)

## Product scoping document
#### Description
Documenting requests from stakeholders, targeting business timing and prioritization

#### Input
Stakeholder requests collected by Product & Program

#### Output
Product Charter, product scope document

## User Research
#### Description
Iterative research to better understand user behaviors, needs, and motivations through a variety of research techniques.

#### Input
User testing plan, user screener, in-person interviews, remote usability sessions through usertesting.com, in-person formal usability tests with paper or clickable prototypes or a working build

Program to assist with organizing. and scheduling sessions

#### Output
User feedback deck with findings and recommendations


## Product Spec
#### Description
Product creates specs

#### Input
Product Scoping Document, User Feedback

Program to assist in tracking & closing out requirements

#### Output
Gold Standard spec


## Engineering & UED review (Of spec)
#### Description
Engineering and UED team review the specs for a general feasability assessment and offering any technical / UI insights. Preferably this should happen as a meeting with select members from each team.

#### Input
Product Spec

#### Output
Spec feedback, approval from UED/Eng that spec is complete enough to begin work


## Wireframing
#### Description
"Blueprints" of the UI based on specs, including major pages as well as interaction and experience.

#### Input
Product Spec and engineering insights

#### Output
Wireframes


## Engineering & Product review (Of wire frames)
#### Description
* Engineering reviews wireframes for feasability, raises any risks or concerns and offers technical insights
* Product reviews wireframes to confirm that Product Specs are fulfilled

#### Input
Wireframes

#### Output
Feedback/Approval from Product/Eng


## Product creates test cases
#### Description
Product creates test cases to outline application flow and user stories outlining proposed functionality

#### Input
Product Spec, Wire Frames

#### Output
Test Cases


## Comps and Content
#### Description
UED creates detailed comps and content for the feature.

#### Input
Product Spec, Wireframes

#### Output
Comps and Content (manuscript).  Comps uploaded into InVision.


## Tech Doc & Risk Assessment with InfoSec
#### Description
Engineer creates a technical specification (https://eng.lyft.com/awesome-tech-specs-86eea8e45bb9) outlining architecture/system changes, engineering tasks involved, potential risks, and effort required.
Engineer reviews system changes & risks with the INFOSEC team

#### Input
Product Spec & Wireframes

#### Output
Tech Spec & INFOSEC signoff


## Engineering Product Review & High Fidelity Sizing
#### Description
Engineering and Product review Comps, Tech Doc (optional), and Test cases and sizes stories accurately (as opposed to T shirt sizing, etc)

#### Input
Comps, Tech Doc (optional), and Test cases

#### Output
Sized Stories/Tasks


## Sprint & Release Planning
#### Description
Groom the release and sprint backlog based on value, effort, and risk

#### Input
Sized Stories/Tasks, Comps, Tech Doc, Test Cases

#### Output
Groomed and prioritized backlog for release and sprint


## Dev Build
#### Description
Engineers complete the tasks (as prioritized), using the techniques from their playbook such as TDD, Pair Programming, etc.

#### Input
Groomed and prioritized sprint backlog, Dev process

#### Output
Completed Tasks/Sprint, built feature deployed to testing environment (Sandbox, QA, etc.)


## QA
#### Description
QA team completes the QA process, using the techniques from their playbook. Engineers resolve bugs and deploy fixes to the testing environment

#### Input
Deployed Feature Branch, Test Cases, QA Process

#### Output
Quality application/features that passes the Product test cases with few to no defects
Signoff from QA


## Fit & Finish
#### Description
UED reviews the latest build, and checks interactions and design specs for any discrepancies. Engineers resolve design issues and deploy fixes to the testing environment

#### Input
Deployed Feature Branch, Comps, Fit & Finish Process

#### Output
Well designed application/features that matches the comps
Signoff from UED


## Deployment (Staging)
#### Description
Engineers/Devops deploy the application to a staging environment. Staging should have production-like data and environment settings

#### Input
Polished application/features with signoff from QA & UED

#### Output
Deployed application where Stakeholders can review before release


## Release
#### Description
Engineers/Devops/Release Engineers deploy the application to the production environment per the release process defined in their playbook

#### Input
Polished application, stakeholder approval, release playbook

#### Output
Feature/application goes live and is available to end users


## Monitor & Support
#### Description
Engineers, Production Support, and Product(?) monitor the application via logs, error reporting, and user feedback per the monitoring & support processes defined in their playbook.

#### Input
Deployed application

#### Output
Metrics to verify release success, support for end users, feedback for future iterations.
