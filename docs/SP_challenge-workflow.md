# Instructions on How to Work in the Challenges Repo

Here is guidance on how to navigate and conquer the challenges.

1. In the `challenges` repository, make sure you are on the `main` branch.
2. Create a folder with the name of the session. For example, `css-basic`.
3. Navigate to the folder created in step 2, e.g., `css-basics`.
4. Once you are inside the folder, download **all** the challenges.
5. Navigate back to the main folder of the repository, `challenges`.
6. Add the files and create a commit:

    ```bash
    git add .
    git commit -m "Add a comment"
    ```

7. Push to the `main` branch:

    ```bash
    git push origin main
    ```

8. Decide on which challenge you want to work.
9. Create a **new** branch dedicated to that challenge **only**.
10. Focus solely on that challenge. While working, remember to make multiple `commits`.
11. Upon finishing the work on that challenge, create a pull request (PR) on the GitHub page.
12. Share the PR link in the Slack on the thread: :checkered_flag: `Solution Thread: <session name>`.
    The message in the slack channel should include the following:

    ```markdown
    **Challenge:** Challenge Name
    **PR link:** PR link
    ```

    A random classmate will be assigned to review your PR.
13. Switch back to the `main` branch.
14. Repeat the steps starting from step 8.

**Important**: You should work on only one challenge per branch! If the session includes three different challenges, then you will require three separate branches.

**Important**: When a classmate approves your PR, you can merge it into the `main` branch. However, do not forget to pull the `main` branch into your local machine.

## Reactions

- 👀 : looking at the PR.
- ✔️: Note in PR.
- ✅: PR Approved.
