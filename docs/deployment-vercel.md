# Vercel Deployment Guide

Vercel is a popular cloud web hosting provider with a fast deployment workflow. Follow these steps to get your project online:

1. **Sign Up/Log In to Vercel**  
   - Go to [vercel.com](https://vercel.com) and log in using your GitHub account.
2. **Import GitHub Repository**
   - Click `New Project` on the Vercel dashboard.
   - If using Vercel for the first time: Select `Continue with GitHub` and authorize Vercel if needed.
   - From the dropdown, select your personal user account.
   - Find your GitHub repository and click `Import`.
3. **Configure Project Settings**
   - For most projects, Vercel preconfigures your project correctly.
   - If you are using API keys or other sensitive information stored in a `.env` file, add the information in the `Environment Variables` section.
4. **Deploy Your Project**
   - Click `Deploy` to start the deployment process.
   - Vercel will clone your repository, install dependencies, build the project, and deploy it automatically.
5. **View Your Deployment**
   - After deployment is complete, you’ll receive a URL to visit your live website.
   - Vercel provides automatic updates: Every time you push changes to GitHub, your site will redeploy.
   - When you create a pull request on Github, Vercel will automatcally create a **preview deployment** for that feature branch and post a link in the respective PR.
6. **Deployment Protection**     
  ⚠️ If others cannot access your deployment, it may be because **Deployment Protection** is turned on. To disable it:  
   - Navigate to the `Settings` tab of your project on Vercel.
   - Select `Deployment Protection`.
   - Turn off the `Vercel Authentication` toggle.

That's it! You've successfully deployed your project to Vercel. 🎉
