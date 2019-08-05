# personal-site
This repository contains the [Hugo academic theme](https://themes.gohugo.io/academic/) files for my personal website. Edit this `personal-site` repo and push changes to the `k8xu.github.io` repo for deployment.


### How to edit `personal-site` repo
A mistake that I had made was editing the `k8xu.github.io` repo instead of this one, which I realized did not make any changes on the actual website. If you need to add or change information on your personal website, make changes to this repository instead.

**1. Open GitHub Desktop and Visual Studio Code to edit content**

On GitHub Desktop, check that you are on `personal-site` and refresh the repository to fetch any new commits. Make any changes using Visual Studio Code in Markdown, and most of the edits should be in the `contents` folder or the `config` file.

**2. Open Git Bash to view changes**

Type `cd Documents/GitHub/personal-site` and `hugo server` in Git Bash to view your real-time changes on `localhost:1313` in your browser. Press `Ctrl + C` to stop the server at any time.

**3. Push commits in GitHub Desktop**

Push your changes with a descriptive commit statement, and refresh the repository to ensure everything is up-to-date.


### How to deploy `personal-site` changes to GitHub Pages
I had spent many hours figuring out how to push my changes to my actual website, so I made this step-by-step guide to make the process more straightforward. I assume that you have already edited the personal-site repo following the above instructions.

**1. Open Git Bash**

Use `cd` to navigate to the `personal-site` repo. You will find that there is a folder called `k8xu.github.io` inside this repo, which is a submodule pointing to the actual website.

**Resources**

Here are some websites that I used to help push my changes to `k8xu.github.io`:
1. [Website 1](placeholder)
2. [Website 2](placeholder)
