# How to use this Repository

## Once

Clone the repository via its ssh url:

```
git clone <ssh url> # e.g., 'git clone git@github.com:neuefische/...'
```

## Steps for every day

1. Update your local repository before working in it (`git switch main` (alternative: `git checkout main`), then `git pull`)
2. Create a new branch (example name: `weekX-dayY`) and switch to it.
3. Copy the `template.md` file and paste it into your current week's folder.
4. Rename the copied template file (example: `2022-XX-XX-monday.md`).
5. Save your file and commit your changes.
6. In the `images` folder, upload the screenshot for attendence (example name: `WD_22.3_HH_XX.XX.2022.png`).

   - The `22.3_HH` part represents your course id and location.
   - Make sure that all names, date and time are visible ([read here how to display all names in zoom](docs/zoom-participant-manual.md)).

7. Update your markdown file with the notes, pictures and links of the day; follow the checklist and delete it as soon as you are done.
8. Commit and push your changes to GitHub.
9. Create a Pull Request.
10. The next day in the student recap,
    - discuss the content of your protocol with your team,
    - add additional notes,
    - write down open questions which you want to discuss with your coaches after the student recap
    - commit and push your changes after the questions are answered.
11. Tell the next author that he/she is going to write the protocol tomorrow.
12. On GitHub, merge your Pull Request into main and delete your branch.
13. On your computer, checkout/switch to main, pull your merged changes and delete the feature branch you have worked in.
