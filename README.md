# helperfn.github.io

Personal site. One self-contained `index.html` - no build step, no dependencies.

Live at <https://helperfn.github.io>

## Layout

Five pages (Home, Work, Projects, Skills, Education) routed client-side off the
URL hash, so the whole thing stays a single file. Without JavaScript the pages
render as one continuous document rather than disappearing.

Set in the Windows console font stack (Consolas first). Light and dark themes,
toggled from the title bar and remembered in `localStorage`; with no explicit
choice stored it follows the OS.

`resume.pdf` is linked from the hero and from the foot of Work and Projects.

## Editing

Open `index.html` and edit it. That is the whole workflow.
