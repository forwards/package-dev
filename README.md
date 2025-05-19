# Forwards R Package Development Workshop

The website for the Forwards R Package Development Workshop.

The website has been set up so that the content of the modules is separate from the specifics of the workshop.

If running a workshop, you will need to do the following:

- Add a .qmd page in the `workshops` directory with the title of the workshop. 
  It would probably be sensible to copy an existing page, e.g. `summer-2025-cohort-1.qmd` and update it with the specifics of the new workshop
- Add a .qmd page in the `workshops` directory with the title of the workshop suffixed with `-intro` (the 'Welcome and introduction' slide deck).
  It would probably be sensible to copy an existing page, e.g. `summer-2025-cohort-1-intro.qmd` (if two instructors) or `summer-2025-cohort-2-intro.qmd` (if three instructors)and update it with the specifics of the new workshop
- Add photos of instructors into `images/instructors` and update the paths to the photos in the new intro slides
- In your new page with the workshop details, update the link to the intro slides for both opening in a new window, and the embedded version
- Add the page with workshop details to `workshops.qmd` as an upcoming workshop
- Review `prerequisites.qmd`. You may need to update to give the latest version numbers of R and RStudio. Update the 'last updated' date at the top of the file.
- Commit and push all changes to GitHub. This will trigger an update to the published website
  - **Note: if you have made changes to any of the slides, or any pages that contains a code chunk, then you *MUST* re-render those page and commit/push the updated pages in the `_freeze` folder, otherwise the rebuilding of the website will fail.**