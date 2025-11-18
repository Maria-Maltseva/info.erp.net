# Project Management in ERP.net: Cases

Each Case serves as a living document, capturing updates, decisions, and changes as the task advances. 
Once the work associated with the Case is completed and approved, the Case is formally closed, signifying task completion within the project.

This granular kind of task management lets organizations gain better control over scope, resources, and progress for every project. 
As each Case acts as a documented trail of work, it ensures that team members, stakeholders, and managers can see who did what and when. This supports auditability and accountability.

### Ownership

Еach Case is assigned an owner, who is the person responsible for its execution and completion.
By default, the creator of a Case becomes its initial owner. 
However, ownership can be reassigned to another user, allowing team members to create Cases on behalf of colleagues and delegate responsibility as needed.

This flexibility supports efficient workload distribution and ensures clear accountability, which leads to smoother collaboration and faster task resolution across teams.

### Detailed Description

When creating a new Case, the author is expected to provide a detailed Description.
This is entered through a markdown-enabled field that supports rich text formatting — including headings, bullet points, numbered lists, quotes, images, and file attachments — allowing for clear, structured, and visually organized content.

This enhances communication and reduces misunderstandings by ensuring that all relevant information is presented in a readable and professional format, leading to more efficient task execution and fewer follow-up questions.

### Priorities

When a new Case is created, the author estimates its initial priority level. 
If the assigned priority is 3 or higher (indicating lower urgency), the system automatically adjusts the Case's priority to level 2 once actual work begins — reflecting its increased relevance during execution.

This dynamic adjustment helps teams focus on active work items by elevating their visibility, ensuring that resources are allocated efficiently and critical tasks are not overlooked.

### Developments

From the moment a Case is created until it is closed, every action and update is automatically logged in the system. 
These logs are displayed in the Developments sub-panel. 
It provides a detailed timeline of all activities, including status changes, edits, and their respective authors.

The layout of this panel can be customized for better readability and focus. 
Any edits made to entries are also tracked, ensuring full transparency and traceability.

This comprehensive activity log enhances accountability, supports informed decision-making, and serves as a reliable audit trail. 
Teams can easily review what was done, by whom, and when — reducing miscommunication, simplifying handovers, and strengthening process compliance across the project lifecycle.

### Discussions

A distinctive feature of Agile PM in ERP.Net is the Case Discussion tab — an informal, built-in chat channel linked to each individual Case. 
This space allows team members to exchange quick messages, ask questions, resolve disputes, or share explanations without cluttering the formal Case documentation. 
While these discussions are kept separate from the official work log, they remain visible to all relevant users and are fully preserved for future reference.

Additionally, any new comment in the Discussion tab triggers a notification to involved users, ensuring timely collaboration and responsiveness.

This feature fosters transparent, real-time communication while maintaining the integrity of formal project records. 
It reduces reliance on external tools (like email or messaging apps), centralizes conversations around the work item, and ensures that critical context is never lost — improving decision-making, speeding up resolutions, and enhancing team alignment.

### Case Statuses

Every case has several consequent statuses that reflect the stage of work on the specific task. 
These statuses are called States:

*Backlog –> Consider –> Ready –> In progress –> Waiting –> Resolved –> Closed*

The user can change back and forward between these statuses.

The __Backlog__ gives the start of the Case; it usually contains the initial information - description of a task/problem/request, reasoning, possibly some imagery, author (owner).

The __Consider__ phase is the phase for evaluation: gathering additional information, surveying, detailing, testing, etc. 
This is usually done by some kind of responsible person or supervisor.

__Ready__ is the phase when a Case gets green light to be processed. 
At this stage it can be assigned to an employee who becomes responsible for the Case.

Once the employee accepts the task and starts work on the Case, it enters the __In progress__ status.
When the initial level of priority is 3 or higher, now that the Case enters “In progress” state, the priority will automatically get higher (priority level 2).

Whenever there is retardation on the work process, the Case enters the __Waiting__ status.
A common reason may be the need to wait for feedback from the customer. Starting active work again brings the Case __In Progress__ again.

After a resolution is achieved, the Case may be moved to __Resolved__ status.
In the end it is supposed to be __Closed__.

__Note: A Case cannot be closed without being resolved first.__

**_N.B.: A case that is already closed can no more be edited_**.

### Tasks
Each user involved in a Case can add personal Tasks (To-Do items) directly within the Case profile. 
These are small, routine action items that support the completion of the overall Case. 
Users can also assign these Tasks to other team members working on the same Case, enabling shared responsibility and collaboration on specific details.

This feature promotes personal accountability, helps structure daily work, and ensures that no minor steps are overlooked. 
It also enhances teamwork by enabling micro-level task delegation, leading to more organized, efficient, and transparent Case execution.

**_Note: A Case cannot be Resolved and Closed while having active/open Tasks._**

### Cases Hierarchy

Cases in Agile PM can be organized into a hierarchical structure, where a newly created Case may be subordinated to an existing Parent Case. 
This allows complex work to be broken down into smaller, more manageable sub-Cases.

The hierarchy is strictly maintained and clearly displayed, showing the full structure of parent and child Cases.

This hierarchical organization improves clarity, enables better tracking of dependencies, and helps project managers visualize the full scope of work. 
It also enhances reporting, prioritization, and resource allocation by showing how individual tasks contribute to broader project goals.

### Estimated time hours

Each Case summary can include an estimated number of work hours required to complete the task. 
This initial time estimate supports more accurate planning of resources, scheduling, and budgeting. 
As work progresses, the estimation can be updated to reflect new insights or changes in scope, ensuring it remains relevant throughout the Case lifecycle.

By providing a clear view of expected effort, time estimations help project managers balance workloads, avoid overloading, and allocate team capacity effectively. 
This leads to improved forecasting, cost control, and overall project efficiency.
