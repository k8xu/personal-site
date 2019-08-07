# personal-site
This repository contains the [Hugo academic theme](https://themes.gohugo.io/academic/) files for my personal website. Edit this `personal-site` repo and push changes to the `k8xu.github.io` repo for deployment.


### How to edit `personal-site` repo
A mistake that I had made was editing the `k8xu.github.io` repo instead of this one, which did not make any changes on the actual website. If you need to change information on your personal website, make changes to this repository instead.

**1. Open GitHub Desktop and Visual Studio Code to edit content**

On GitHub Desktop, check that you are on `personal-site` and refresh the repository to fetch new commits. Make changes in Markdown using Visual Studio Code, and most of your edits will be in the `contents/home` folder or the `config.toml` file.

**2. Open Git Bash to view changes**

Type `cd Documents/GitHub/personal-site` and `hugo server` in Git Bash to view your real-time changes on `localhost:1313` in your browser. Press `Ctrl + C` to stop the server at any time.

**3. Push commits in GitHub Desktop**

Push your changes with a descriptive commit statement, and refresh the repository to ensure everything is up-to-date.


### How to deploy `personal-site` changes to GitHub Pages
I spent hours figuring out how to push my changes to the actual website, so I made this guide to make the process more straightforward. I assume that you have already edited the personal-site repo following the above instructions.

**1. Open Git Bash**

Use `cd` to navigate to the `personal-site` repo, which is where most of the deployment process will take place. You should find a folder called `k8xu.github.io` inside this repo, which is a submodule pointing to the actual website.


### Resources
[I followed the **Deploying** section of this website with some modifications.](https://inside.getambassador.com/creating-and-deploying-your-first-hugo-site-to-github-pages-1e1f496cf88d)

[I followed the **Setup When You've Already Committed and Pushed** section of this website but did not use a `public` folder.](https://github.com/whipperstacker/blog/blob/master/content/post/deploying-a-hugo-site-to-github-pages.md)
