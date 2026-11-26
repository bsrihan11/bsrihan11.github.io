# Bhavesh Srihan · portfolio site

A single static page: `index.html` plus the two résumé files it links to. No build step and no dependencies;
open `index.html` in a browser to see it.

## Files

- `index.html`: the whole site (styles at the top, content in the HTML, a small script at the bottom).
- `Bhavesh_Srihan_Resume.pdf` and `Bhavesh_Srihan_Resume.docx`: linked from the header, the hero and the footer.
  When you update your résumé, replace these two files with the same names.

## Host it (pick one)

**GitHub Pages**: create a public repo (for example `bsrihan11.github.io`), push these files to `main`, then turn
on Settings → Pages → Deploy from branch → `main` / root. The site appears at `https://bsrihan11.github.io`.

**Netlify**: go to app.netlify.com/drop and drag this folder onto the page. You get a URL straight away and can
add your own domain later.

**Vercel**: run `npx vercel` in this folder and accept the defaults.

## Editing

- Numbers in the "Impact" tiles and the before/after chart are typed into `index.html`. If you change a value in
  the chart, change its bar width too: each row is scaled so the larger value is `80%` wide.
- The email address is shown as text with a Copy button. The phone number is left off on purpose, because the
  site is public.
