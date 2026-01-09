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

