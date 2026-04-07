# TrinityHawk — Client Project Update Site

A lightweight, shareable client project update page. Built with plain HTML/CSS/JS — no build tools, no dependencies.

## Features
- Task list with checkboxes (clients can tick off tasks)
- Due dates with overdue/upcoming indicators
- Commentary sections (What's been done / What's coming up)
- Gantt-style timeline with today marker
- Milestone tracker
- Notes & links sidebar
- TrinityHawk branded (navy, gold, Bricolage Grotesque)

## Customising

Open `index.html` in a text editor and update:

1. **Project title & description** — search for `project-title` and `project-description`
2. **Tasks** — edit the `tasks` array in the `<script>` section
3. **Gantt phases** — edit the `ganttPhases` array
4. **Milestones** — edit the `milestones` array
5. **Key contacts** — update the HTML in the Key Contacts card
6. **Commentary** — pre-populated text in the `<textarea>` elements

## Deploying

1. Push to GitHub
2. Connect repo to Vercel
3. Deploy — it's a static site, no config needed beyond `vercel.json`

## Sharing

Share the Vercel URL directly with clients. No login required.
