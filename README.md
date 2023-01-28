# Agile and SCRUM fundamentals

Agile is an **iterative approach** to software development that emphasizes flexibility, interactivity, and transparency using small (5-7, +-2), cross-functional teams.

The *Agile Manifesto* is the go to reference for describing Agile's core values:

- Individuals and interactions, over processes and tools
- Working software, over comprehensive documentation
- Customer collaboration, over contract negotiation
- Responding to change, over following a plan

The Agile approach stands opposite to the structured, step-by-step waterfall one. Working in **Minimum Viable Products** means delivering something useful quickly, by testing and learning in the smallest batches possible, reducing costs by detecting bugs early on before the code reachs production.

The Scrum Managment Framework is one of the methodologies that fall under the scope of the Agile philosophy, and it is defined by:

- Defined roles (product owner and scrum master), meetings, rules, and artifacts
- Small, autonomous, cross-functional, co-located, self-organizing and self-managing teams
- Fixed-length iterations called sprints
- Focused on producing a potentially shippable product increment with every iteration

The product owner represents stakeholders vision and requirements, while the scrum master unblockes impediments, coaches and shields the team from interference.

When done well, Scrum:
- Increases employee productivity and motivation
- Improves product quality
- Reduces time to market
- Enhances stakeholder involvement and satisfaction 

Agile is not to be adopted just in the devolpment process, but across the entire organization to prevent operational bottlenecks.

Iterative planning allows for course corrections and more accurate estimates, a different focus and new priorities

## Kanban

Scrum benefits from a dashboard-like system called *Kanban*, which function is to limit the work in progress, manage and enhance workflow by producing a product backlog, a sprint backlog and a completed increment.

A kanban board tracks plan items needing to be done, items in process, and completed items in a set of pipelines where each task gets worked on and organized from left to right on the kanban board as it is completed.

In Kanban, each task required to complete the stakeholder's vision is called a **story**. 

*A good practice is to document each story with a template that describes the task, the assumptions regarding the task and the outcome expected from a given set of preconditions to declare the task as completed (known as the *Gherkin Syntax*). Defining what "done" means for each task helps minimize misunderstandings.*

The Scrum team prestimates each story difficulty by giving it a score set on **story points**. This scale is agreed upon the team, usually by the Fibonacci scale.


## Scrum Events

#### Sprint planning: 
All of the stories are documented, broken-down and refined on the **Product Backlog** by the Product Owner to make the stories *sprint ready*, so the Scrum team can assign themselves the tasks.

The development team is responsible for creating a sprint plan by moving stories from the Product Backlog into the **Sprint Backlog**, until team's velocity (agreed full capacity) is reached.

Each developer is responsible for assigning themself the story with the highest priority that you have skills for and update the Kanban, so eveyone knows who is working on each task, and which developers are already working on a story. Scrum focuses on delivering one completed project rather than 50% of two projects.

#### Daily stand-up meetings: 
Occurs every day for 15 minutes, and must only address three questions:

- What did I accomplish the previous day?
- What will I work on today?
- What blockers or impediments are in my way?

An useful visualization to determine how far along is the team on their sprint goals is the **Burndown chart**, which displays the measurement of story points completed vs story points remaining, how many days has passed since the sprint began and how many days are left.

#### Sprint review: 
At the end of each sprint, each developer gets the chance to showcase their work and receive feedback from stakeholders. This feedback shapes next sprint's Product Backlog.

Unfinished stories should be closed and reframed as new stories to complete in the next sprint (if they are still a priority on the project).

#### Sprint retrospective:
It is a final meeting where the scrum master and development team can agree on:

- What went well? (keep doing)
- What did not go well? (stop doing)
- What should we change for the next sprint?

## Metrics

High performing teams rely on actionable metrics to measure change, from a baseline. The conventional top 4 actionable metrics are:

- Mean Lead Time (How long does it take from idea to production?) 
- Release Frequency (How often can you deliver changes?) 
- Change Failure Rate (How often do changes fail?) 
- Mean Time to Recovery (MTTR) (How quickly can you recover from failure?) 
