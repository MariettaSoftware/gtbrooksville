# Grace & Truth Bible Chapel — website

Static site. No build step: open `index.html` in a browser, or serve the folder.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Main page — simple schedule, short statement of faith, scriptures, location, email |
| `schedule.html` | Detailed schedule, Zoom details, neighboring assemblies, camps & missions |
| `beliefs.html` | Full statement of faith and the assembly's practices |
| `gallery.html` | Pictures of the chapel |
| `css/styles.css` | Shared stylesheet for all pages |
| `images/` | Photographs, resized for the web (originals are in `../info/`) |

## Local preview

    python3 -m http.server 8000

Then visit http://localhost:8000

## Notes

- Mobile-first; nothing requires JavaScript.
- Source content comes from `../info/`: the brochure PDF (detail pages) and
  `GTBC Website verse.docx` (main page).
- Styling is deliberately plain so the real template can be dropped in later —
  colors live as CSS variables at the top of `css/styles.css`.
