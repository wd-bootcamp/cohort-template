# How to share your exercises

You will commit your exercises progress to a personal repository on Github.

## Fork the template

[Visit the template page](https://github.com/neuefische/web-exercises-template), rename the fields to just `web-exercises` then fork it:

![Fork the existing template](./assets/git-workflow-exercises-01.png)

Now you should have it on your Github profile like:

![Your updated repo](./assets/git-workflow-exercises-02.png)

Copy the git URL that you see after clicking on the green **Code** button / SSH, then clone it locally:

```
git clone git@github.com:<your-username>/web-exercises.git
cd web-exercises
code .
```

**Note:** make sure to be _outside_ of any other git repository you have on your machine!

## Working locally

After every session, you'll find instructions about how to download the corresponding challenges, like:

```
npx degit@latest neuefische/web-exercises/sessions/html-forms/personal-profile-form html-forms/personal-profile-form
```

This will create a new folder with the challenge, that you can access in VSCode and start working on:

![Local exercise copy](./assets/git-workflow-exercises-03.png)

Whenever you are satisfied with your progress, commit your changes and push them to your remote repository:

```
git add index.html styles.css
git commit -m "Solve html-forms challenge #1"
git push
```

You can now share the remote github URL on the Slack Solutions / Questions thread.