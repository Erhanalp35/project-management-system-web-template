# Project Management System Web Template

A comprehensive and responsive project management system built with **HTML5, CSS3, and Vanilla JavaScript**.

This project provides a complete front-end administration solution for managing projects, tasks, teams, Kanban boards, milestones, deadlines, time tracking, workloads, project progress, analytics, and reports.

It is designed as a downloadable web template that can run locally without React, Next.js, a backend, database, or account system.

## Features

### Dashboard

Get a complete overview of project and team activity.

- Total Projects
- Active Projects
- Completed Projects
- On Hold Projects
- At Risk Projects
- Overdue Projects
- Total Tasks
- Open Tasks
- In Progress Tasks
- Completed Tasks
- Overdue Tasks
- Upcoming Deadlines
- Total Team Members
- Logged Hours
- Project Progress
- Team Workload
- Recent Activity
- Upcoming Milestones
- Recent Projects
- Time Logged Trend
- Quick Actions

### Project Management

Create and manage projects.

Features include:

- Create Projects
- Edit Projects
- View Project Details
- Complete Projects
- Put Projects On Hold
- Archive Projects
- Restore Projects
- Search
- Filter
- Sort
- Pagination

Project information can include:

- Project Name
- Project Code
- Description
- Status
- Priority
- Start Date
- Due Date
- Owner
- Team Members
- Progress
- Budget
- Tags
- Created Date
- Updated Date

Project statuses:

- Planning
- Active
- On Hold
- Completed
- Cancelled
- Archived

Project priorities:

- Low
- Medium
- High
- Critical

### Project Details

Project profiles can display:

- Project Information
- Project Status
- Project Priority
- Project Owner
- Team Members
- Project Progress
- Project Health
- Tasks
- Milestones
- Deadlines
- Logged Time
- Budget
- Labor Cost
- Notes
- Recent Activity

### Project Progress

Project progress can be calculated automatically from task completion.

Example:

```text
Project Progress = Completed Tasks / Total Tasks × 100
```

This allows Dashboard, Project Details, Analytics, and Reports to use the same real project progress data.

### Project Health

Projects can be classified as:

- On Track
- At Risk
- Overdue
- Completed

Project health can be calculated using:

- Due Date
- Project Progress
- Overdue Tasks
- Critical Tasks
- Missed Milestones

### Task Management

Create and manage tasks across projects.

Task information can include:

- Task Title
- Description
- Project
- Status
- Priority
- Assignees
- Start Date
- Due Date
- Estimated Hours
- Logged Hours
- Remaining Hours
- Milestone
- Tags
- Notes

Task statuses:

- Backlog
- To Do
- In Progress
- Review
- Completed
- Cancelled

Task priorities:

- Low
- Medium
- High
- Critical

### Task Workflow

Tasks can move through:

```text
Backlog
→ To Do
→ In Progress
→ Review
→ Completed
```

Completed tasks can be reopened when needed.

### Overdue Tasks

The system can automatically detect overdue tasks when:

- The due date has passed
- The task is not completed
- The task is not cancelled

Overdue tasks can appear on:

- Dashboard
- Task List
- Project Details
- Calendar
- Analytics
- Reports

### Due Soon Tasks

Tasks approaching their deadlines can be highlighted automatically.

This makes upcoming work easier to identify before it becomes overdue.

### Kanban Board

Manage tasks visually using a Kanban-style board.

Columns can include:

- Backlog
- To Do
- In Progress
- Review
- Completed

Task cards can display:

- Task Name
- Project
- Priority
- Assignees
- Due Date
- Estimated Hours
- Tags

Task status changes can persist locally after page refresh.

### Kanban Filters

Filter the board using:

- Project
- Assignee
- Priority
- Tag

### Team Management

Create and manage project team members.

Team member information can include:

- First Name
- Last Name
- Email
- Phone
- Role
- Department
- Status
- Weekly Capacity
- Hourly Rate
- Skills
- Notes

Statuses:

- Active
- On Leave
- Inactive

Roles can include:

- Project Manager
- Developer
- Designer
- QA Engineer
- Business Analyst
- Marketing
- Other

### Team Member Profiles

Profiles can display:

- Contact Information
- Role
- Department
- Skills
- Assigned Projects
- Assigned Tasks
- Open Tasks
- Completed Tasks
- Overdue Tasks
- Logged Hours
- Workload
- Recent Activity

### Multiple Task Assignees

Tasks can support multiple team members without creating duplicate task records.

### Milestone Management

Create and manage project milestones.

Milestone information can include:

- Project
- Name
- Description
- Due Date
- Status
- Progress
- Completed Date

Milestone statuses:

- Upcoming
- In Progress
- Completed
- Missed
- Cancelled

### Milestone Progress

If tasks are associated with milestones, progress can be calculated automatically from completed milestone tasks.

### Project Timeline

Project details can provide a chronological overview of:

- Project Start
- Task Deadlines
- Milestones
- Project Due Date

### Calendar

View project-related dates in one place.

The calendar can display:

- Project Start Dates
- Project Deadlines
- Task Deadlines
- Milestones

Features:

- Previous Month
- Next Month
- Today
- Date Details
- Project Filters
- Event Type Filters

### Time Tracking

Track time spent on projects and tasks.

Time entries can include:

- Team Member
- Project
- Task
- Date
- Duration
- Description
- Billable Status

Features:

- Add Time Entry
- Edit Time Entry
- Delete Time Entry
- Search
- Filter
- Sort

### Logged Time

Track:

- Logged Time by Task
- Logged Time by Project
- Logged Time by Team Member

Time can be stored internally in minutes and displayed as readable hours and minutes.

Example:

```text
150 minutes = 2h 30m
```

### Estimated vs Actual Time

Compare task estimates with real logged time.

Metrics can include:

- Estimated Hours
- Logged Hours
- Remaining Hours
- Time Overrun

### Workload Management

View team workloads based on remaining assigned work.

Metrics can include:

- Active Tasks
- Estimated Remaining Hours
- Weekly Capacity
- Workload Percentage
- Overdue Tasks

Workload states can include:

- Light
- Balanced
- High
- Overloaded

### Project Budget

Projects can contain an optional budget.

When hourly rates and time entries are available, the system can estimate labor costs.

Example:

```text
Labor Cost = Logged Hours × Hourly Rate
```

### Notes

Create multiple notes for:

- Projects
- Tasks

Notes can include:

- Author
- Message
- Created Date
- Updated Date

### Activity Tracking

Track important project activity.

Activity examples:

- Project Created
- Project Updated
- Project Completed
- Task Created
- Task Assigned
- Task Status Changed
- Task Completed
- Task Reopened
- Milestone Created
- Milestone Completed
- Time Logged
- Team Member Added

### Activity Log

View system-wide project activity.

Features:

- Search
- Project Filter
- Activity Type Filter
- Date Range Filter

### Tags

Use custom tags on:

- Projects
- Tasks

Examples:

- Frontend
- Backend
- Bug
- Feature
- Urgent
- Client
- Internal

Tags can also be used for filtering.

### Search

Search across:

- Projects
- Project Codes
- Tasks
- Team Members
- Tags

Search can support:

- Partial Matches
- Case-Insensitive Matching
- Whitespace-Tolerant Queries

### Filters

Project filters can include:

- Status
- Priority
- Owner
- Member
- Tag
- Due Date

Task filters can include:

- Project
- Status
- Priority
- Assignee
- Tag
- Due Date
- Overdue State

Milestone filters can include:

- Project
- Status
- Due Date

Time entry filters can include:

- Project
- Member
- Task
- Date Range
- Billable Status

### Sorting

Projects can be sorted by:

- Name
- Created Date
- Due Date
- Progress
- Priority

Tasks can be sorted by:

- Title
- Created Date
- Due Date
- Priority
- Status
- Estimated Hours

Team members can be sorted by:

- Name
- Workload
- Open Tasks
- Logged Hours

### Pagination

Reusable pagination can support:

- 10 Items
- 25 Items
- 50 Items

The selected page size can be stored locally.

### Global Search

A global search can locate:

- Projects
- Tasks
- Team Members

Search results can identify the entity type and allow quick navigation.

### Analytics

Analyze real project and team data.

Metrics can include:

- Total Projects
- Active Projects
- Completed Projects
- Project Completion Rate
- Total Tasks
- Completed Tasks
- Overdue Tasks
- Task Completion Rate
- Total Logged Hours
- Average Project Progress
- Team Utilization

Charts can include:

- Projects by Status
- Tasks by Status
- Tasks by Priority
- Project Progress
- Tasks Completed Over Time
- Logged Hours Trend
- Hours by Project
- Team Workload
- Overdue Tasks by Project
- Milestone Status Distribution

### Reports

Generate useful project management reports.

Available reports can include:

- Project Report
- Project Status Report
- Project Health Report
- Task Report
- Overdue Task Report
- Completed Task Report
- Milestone Report
- Time Tracking Report
- Team Workload Report
- Team Performance Report
- Project Hours Report
- Activity Report

### Report Date Filters

Relevant reports can support:

- Today
- Last 7 Days
- Last 30 Days
- This Month
- This Quarter
- This Year
- Custom Range

### CSV Export

Relevant reports can export currently filtered data as CSV.

Exports can include proper:

- Headers
- UTF-8 Text
- Quote Escaping
- Comma Escaping
- Multiline Text Handling

### Import & Export

Application data can be backed up locally.

Features:

- Export Complete JSON Backup
- Import JSON Backup
- Merge Imported Data
- Replace Existing Data
- Validate Imported Data
- Protect Existing Data from Invalid Imports

### Settings

Configure application preferences.

Settings can include:

- Organization Name
- Currency
- Date Format
- Time Format
- Default Project Status
- Default Task Status
- Default Task Priority
- Default Table Page Size
- Due Soon Threshold
- Theme
- Compact Mode

Supported currencies can include:

- USD
- EUR
- GBP
- TRY
- CAD
- AUD
- JPY

## Light & Dark Mode

The template includes:

- Light Theme
- Dark Theme

Theme preference can be stored locally in the browser.

## Responsive Design

The interface is designed for:

- Smartphones
- Tablets
- Laptops
- Desktop Computers

Navigation, project cards, task tables, Kanban boards, calendars, workload views, forms, dialogs, filters, analytics, and reports adapt to different screen sizes.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage
- Chart.js
- Lucide Icons

The project does not require:

- React
- Next.js
- Vue
- Angular
- Svelte
- PHP
- Backend Server
- Remote Database
- Authentication Server
- API Keys

## Modular Architecture

The project uses multiple HTML, CSS, and JavaScript files instead of one large application file.

Example structure:

```text
project-management-system-web-template/
│
├── index.html
├── projects.html
├── tasks.html
├── board.html
├── team.html
├── milestones.html
├── calendar.html
├── time-tracking.html
├── workload.html
├── activity.html
├── analytics.html
├── reports.html
├── settings.html
│
└── assets/
    ├── css/
    │   ├── variables.css
    │   ├── base.css
    │   ├── layout.css
    │   ├── sidebar.css
    │   ├── header.css
    │   ├── components.css
    │   ├── forms.css
    │   ├── tables.css
    │   ├── kanban.css
    │   ├── calendar.css
    │   ├── charts.css
    │   └── responsive.css
    │
    └── js/
        ├── core/
        ├── ui/
        ├── data/
        └── modules/
```

## Data Storage

Application data can be stored using browser `localStorage`.

Stored information may include:

- Projects
- Tasks
- Team Members
- Milestones
- Time Entries
- Project Notes
- Task Notes
- Activity Logs
- Settings

Data remains available after page refreshes unless browser storage is cleared.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Erhanalp35/project-management-system-web-template.git
```

Open the project folder:

```bash
cd project-management-system-web-template
```

Then open:

```text
index.html
```

No backend or database installation is required.

## Demo Data

The first launch may initialize realistic demo data.

Demo content can include:

- Planning Project
- Active Projects
- At Risk Project
- Completed Project
- Team Members
- Backlog Tasks
- To Do Tasks
- In Progress Tasks
- Review Tasks
- Completed Tasks
- Overdue Tasks
- Critical Tasks
- Milestones
- Time Entries
- Notes
- Activity Records

Demo data should only initialize when no valid user data already exists.

## Privacy

The application can operate entirely inside the browser.

It does not require:

- User Accounts
- Remote Databases
- Cloud Storage
- API Keys
- External Servers

## Screenshots

Add screenshots here:

```md
![Dashboard](assets/images/dashboard-preview.png)

![Projects](assets/images/projects-preview.png)

![Kanban Board](assets/images/board-preview.png)

![Analytics](assets/images/analytics-preview.png)
```

## Future Improvements

Possible future additions include:

- Real Authentication
- Role-Based Permissions
- Backend Database Integration
- Advanced Task Dependencies
- Gantt Charts
- Recurring Tasks
- Project Templates
- File Attachments
- Comments
- Notifications
- Approval Workflows
- Client Portal
- Real-Time Collaboration
- Team Permissions
- Multiple Workspaces
- Cloud Synchronization

## Contributing

Contributions, bug reports, and feature suggestions are welcome.

Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.
