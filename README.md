# Responsive Final Project

Open `index.html` in your browser. No installation or build step is needed.

The original content and images come from the course starter:
https://github.com/academic-innovation-online-learning/WD4E-Advanced_Styling_with_Responsive_Design/tree/main/RD-week2-responsive_hw_starter

## Layout

- Below 772px: one div per row.
- From 772px: two divs per row, each 45vw wide. Images have a maximum height of 30vh and stay inside their divs.
- From 998px: three divs per row, each 30vw wide. The tablet image rules still apply.

`vw` means a percentage of the viewport width. `vh` means a percentage of the viewport height.

The starter's base div display and width were corrected to make the mobile layout one column. An extra closing div tag was also removed. The two media queries are in `css/style.css`.

## Host with GitHub Pages

1. Sign in to GitHub and create a public repository named `responsive-final-project`. Select Add README so the main branch exists.
2. In the repository, choose Add file, then Upload files.
3. Upload the contents of this project folder: `index.html`, the `css` folder, the `images` folder, and this README. Upload the extracted files, not the ZIP. Keep `index.html` at the repository's top level.
4. Click Commit changes.
5. Open Settings, then Pages.
6. Under Build and deployment, choose Deploy from a branch.
7. Choose the `main` branch and `/(root)` folder, then click Save.
8. Wait for publishing, then use Visit site on the Pages screen.
9. Share the published website link for the assignment.

The address will normally be `https://YOUR-USERNAME.github.io/responsive-final-project/`.

Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Check the three views

Open the page in Chrome. Open developer tools, enable the device toolbar, and select Responsive. Check widths of 390px, 772px, and 998px. You should see one, two, and three divs per row respectively. Also check 771px and 997px to confirm the breakpoints.

Local file checks confirmed that the stylesheet and all nine image files exist, the HTML div tags are balanced, and the stylesheet contains the two required media queries. Final browser layout verification has not been completed.
