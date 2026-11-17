# PMC Services — Frontend Demo

A responsive, role-based PMC Services frontend built using plain HTML, CSS and JavaScript.

## Run locally
1. Extract the ZIP.
2. Open the `PMC-Services-Frontend` folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension and click **Go Live**.

No npm installation or build step is required.

## Demo access
On the login screen, select Administrator, Project Manager, Employee or Client. Any non-empty email and password will enter the selected demo role. The email field changes automatically when the role changes.

## Included
- Four distinct role-specific interfaces and navigation structures.
- No duplicated Workspace navigation.
- Admin client/project/people/task/finance/document/report views.
- Project Manager delivery, task, milestone, team and report views.
- Employee personal tasks, schedule, project and document views.
- Client project portal, shared documents, milestones and queries.
- Frontend demo interactions: create clients/projects/tasks/milestones/expense records, update tasks, approve expenses, share document records, submit queries, export project CSV.
- Responsive layout and browser localStorage persistence.

## Important limitations
This is intentionally a **frontend-only prototype**. Data is stored in the browser's localStorage for demonstration. It does not implement real JWT authentication, backend APIs, MongoDB, server-side role-based authorization, secure document storage, real file uploads, or multi-user synchronization. Those requirements need a backend and database. Demo role switching is not security.

Some charts are illustrative visual summaries. Employee directory and file records are demo data. The UI does not claim to be a production-secure application.
