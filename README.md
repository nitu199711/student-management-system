# Student Management System

A lightweight static Student Management System built with HTML, Bootstrap and vanilla JavaScript. Data is persisted in the browser using `localStorage`. The UI uses an elegant, minimalistic design with a top navigation bar and left sidebar.

## Features
- Dashboard with summary cards:
  - Total Students count
  - Total Courses count
- Consistent left sidebar and top navigation across pages
- Students page
  - List students in a responsive table
  - Add student (form)
  - Delete student
  - Pre-seeded with 10 sample students on first load
- Courses page
  - List courses in a table
  - Add course (modal)
  - Delete course
  - Pre-seeded with 10 sample courses on first load
- Counts update across pages using `localStorage` + `storage` event

## Pages / Files
- `index.html` — login / landing
- `dashboard.html` — overview (students & courses counts)
- `students.html` — student list + delete
- `add-student.html` — add student form
- `courses.html` — course management (add/delete)
- `css/style.css` — shared styles (base typography, cards, table hover)

## Data & Behavior
- Stored in `localStorage`:
  - `students` — array `{ id, name, email, age, course }`
  - `courses` — array `{ id, name }`
- App seeds 10 courses + 10 students on first load and updates counts across pages.

## Design Notes
- Uses Bootstrap and Font Awesome via CDN.
- Shared styles in `css/style.css`; pages include small layout-specific styles.
- Responsive layout; sidebar hides on small screens.

<img width="1910" height="982" alt="image" src="https://github.com/user-attachments/assets/77e9de98-890e-4753-b42b-4f486bc10e46" />
<img width="687" height="252" alt="image" src="https://github.com/user-attachments/assets/e9f04b0c-94f1-40ca-8515-6a263c761c5a" />
<img width="1907" height="937" alt="image" src="https://github.com/user-attachments/assets/d22fe75c-e06b-437b-b2b4-413d84b94eac" />
<img width="1912" height="962" alt="image" src="https://github.com/user-attachments/assets/a03d3c88-e6b5-430b-9a3c-0bfecbca18fb" />
<img width="1857" height="877" alt="image" src="https://github.com/user-attachments/assets/2585d619-1045-40dc-b470-0478eae87c5e" />

<img width="1897" height="957" alt="image" src="https://github.com/user-attachments/assets/086336de-58e1-4686-9a57-3b20c7fb6064" />

<img width="1888" height="906" alt="image" src="https://github.com/user-attachments/assets/65b17170-a708-4246-9cee-df6510f22a71" />






