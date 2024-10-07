# Deploy your website to GitHub Pages

We are going to deploy, or publish, our web page(s) to GitHub Pages. Please note that this works well for websites using HTML, CSS and vanilla Javascript. For React and other frameworks please checkout the [vercel deployment guide](deployment-vercel.md).

> ❗️ We are going to be publishing the contents of a specific **branch** of your repository, and a specific **folder** within that branch. For simplicity's sake, please make sure that your main file (eg. `index.html`) is at the top level of the source folder (i.e. it's at the root of your repository, not inside a sub-folder).

Please follow these steps carefully:

1. On GitHub, navigate to your site's repository.
2. Open the `Settings` tab of the repository.
3. On the left menu bar, select `Pages`.
   ![Repo setting page](./assets/repo-settings-page.png)

4. Select the branch you want to deploy. In our case, we'll choose `main`. Then click `Save`. (_Please note that you can also select a **directory** to deploy before clicking `Save`, eg. if the folder you want to deploy is not at the root of your repository_)
   ![Repo setting page](./assets/repo-settings-page-config.png)

5. Your website is now deployed! But to what URL? Click on the `Code` tab to go to your repository's main page.
6. Let's add the URL in the `About` section of your repository.
   ![Repo main page](./assets/repo-main-page-1.png)
7. On the pop-up, select `Use your Github Pages website` and then click on `Save changes`
   ![Repo main page](./assets/repo-code-about-save.png)
8. Now you will see your website's URL in the `About` section of your project! Click on it, and see your page.

You can find more information about deploying a website to GitHub Pages over [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).
