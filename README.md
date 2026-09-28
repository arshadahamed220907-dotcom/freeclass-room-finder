# SRM Student Tools

A single GitHub Pages project with two separate student tools:

- [Attendance planner](attendance.html): subject-level forecasts, OD and medical leave simulation, attendance health visuals, and an in-browser advisor.
- [FreeClass room finder](freeclass.html): timetable-based availability, floor map, class countdown, and WhatsApp squad invite.

The home page at [index.html](index.html) links to both tools. Use the navigation bar to move between pages.

## Data notes

The Attendance Planner loads its original timetable scan images from the public [attendance-planner repository](https://github.com/arshadahamed220907-dotcom/attendance-planner). FreeClass uses the timetables supplied for this project. Its first-year timetable is from 2024-25 and is excluded from current-term room availability. AC, room capacity, and live access are not verified by the timetables.

The project is static HTML, CSS, and JavaScript. GitHub Actions deploys the site to GitHub Pages on pushes to `main`.
