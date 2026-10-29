# personal-website

Source for Suyash Pandit's personal website: a static site with plain HTML and CSS and no build step.

- `index.html`: page content
- `styles.css`: styles (light and dark mode). Bump the `?v=` number in the `<link>` tags when it changes so browsers skip their cached copy.
- `theme.js`: dark mode toggle (remembers the choice, otherwise follows the system setting)
- `resume.html`: resume page
- `SuyashPanditResume.pdf`: resume (phone number removed), embedded on the resume page
- `resume.png`: image of the resume, shown instead of the PDF in browsers that cannot embed PDFs (e.g. most phones). Regenerate it with `pdftoppm -r 200 -png -singlefile SuyashPanditResume.pdf resume` when the PDF changes.

To preview it, open `index.html` in a browser.
