# CC4057 Introduction to Information Systems: Module Hub

A static website (no build step) with weekly materials, assessment help, study tools and references.

## Put it online with GitHub Pages
1. On github.com, create a new repository, for example `cc4057-hub` (public, or private if your plan allows Pages on private repos).
2. Upload everything in this folder: `index.html`, `css/`, `js/`, `materials/`, `.nojekyll` and this README. (Add file > Upload files, then drag the contents in.)
3. Go to **Settings > Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/cc4057-hub/`.

## Update it each week (only `js/data.js` needs editing)
- **New slides:** copy the PowerPoint into `materials/`, then in `js/data.js` set that week's `file: "materials/Your_File.pptx"` and `status: "ready"`.
- **This week highlight:** change `currentWeek`.
- **Contact details and office hours:** edit the `contact` block.
- **Links, glossary terms, quiz questions, FAQ:** edit the matching lists in `data.js`.
- Check every item marked as a draft (assessment dates, weights, CW1 plan) against the module handbook.

## Notes
- Student ticks and checklists are saved in their own browser only (localStorage). Nothing is sent anywhere.
- Slides are PowerPoint downloads. Only upload material you have the right to share.
- To preview locally, open `index.html` in a browser.

## Student notes and saved links
- Each week page has a notes box and a place to save links. **My study** gathers all notes, saved links and a backup tool.
- Everything is stored in the student's own browser (nothing is sent to you or anyone else), so remind students to use **Backup** now and then.

## Learning sections (no extra setup)
- **Databases for beginners** (`js/db-lessons.js`): 13 step-by-step lessons plus a practice playground. SQL runs in the browser using a small built-in engine (`js/sqlengine.js`) on made-up sample data. It supports basic SELECT (WHERE, ORDER BY, LIMIT, GROUP BY, HAVING, INNER JOIN, COUNT/SUM/AVG/MIN/MAX), INSERT, UPDATE and DELETE.
- **UML guide** (`js/uml.js`): use case, activity, class and ER diagrams, drawn as built-in SVG, with practice tasks and a checklist.
- **Careers and skills** (`js/careers.js`): skills gained per week, a skills log, a CV bullet builder and next steps. Add your university careers service in `js/data.js` (`contact.careers`).
