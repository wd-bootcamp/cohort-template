# Web-Challenges Workflow

Please follow this workflow when working on challenges. It helps you practicing the git branches commands every day. Practice makes perfect!

1. In the `web-challenges` repository, make sure you are on the `main` branch.
2. Create a folder with the name of the session. For example `mkdir css-basics`.
3. Navigate to the folder created in step 2, e.g. `cd css-basics`.
4. Once you are inside the folder, download **all** the challenges.
5. Add the current folder and create a commit:

   ```bash
   git add .
   git commit -m "Add challenges for css-basics"
   ```

6. Push to the `main` branch:

   ```bash
   git push
   ```

7. Decide on which challenge you want to work and change into that folder, e.g. `cd css-basics-pink-box`.
8. Open the current folder (project) in Visual Studio Code `code .`.
9. Open the terminal in VS Code (`CMD + 'J' on Mac or Ctrl + 'J' on Windows`) and use it while working on this project.
10. Create a **new** branch dedicated to that challenge **only**.
11. Focus solely on that challenge. While working, remember to make multiple `commits`.
12. Upon finishing the work on that challenge, create a pull request (PR) on the GitHub page.
13. Post the url to your PR in the session solution thread on slack.
14. Close VS Code and use the computers terminal again. Start working on the next challenge and repeat the steps beginning from point 7.
