---
title: GRQ02 - Practice with `git`
author: 
- FirstName LastName
geometry: margin=1in
---

In this GRQ you will use `git` to create a new repository and GitHub to host it. Additionally, you will use GitHub pages to setup a simple web page for the project. In the process of working through this GRQ, you will gain practice working with `git`, commits, remotes, and branches.

Register a GitHub account and login.

_1. Set a profile picture for your account, your name, your company as UNC Chapel Hill or some more recent internship, your location as Chapel Hill, NC or home. Respond below with a link to your github.com profile page._

[http://github.com/<your username>]

_2. In your COMP290 container, `cat` the SSH public key file setup in Lecture 1: `/mnt/learncli/.ssh/id_rsa.pub` Establish this key as a public key with your GitHub account by going to GitHub settings, selecting SSH and GPG keys, and adding a "New SSH Key". You'll want to select, copy, and then paste the key into the Key field. Give it a title of "COMP290 Container" or the likes. Respond to this question by also pasting your key below._

Replace this line with your public key.

_3. In your COMP290 container, make a directory named `comp290site`. Navigate into the directory. Initialize this directory to be a normal, empty `git` repository as shown in lecture. Create an empty file named `README.md` using the `touch` program. Add `README.md` to staging and make an initial commit._

Add each of the commands you ran for #3 here. Consider using the shell's history of commands to avoid retyping.

_4. Use `vim` to edit the file named `README.md`. Add some basic markdown describing that this project is for the COMP290 tools course to practice `git`. Save your changes and exit `vim`. Add the changes you made to this file and make a new commit._

What commands did you run to stage and make this second commit?

_5. On GitHub, create a new personal repository named `comp290site`. It should be _Public_ and you should _skip_ initializing the repository with a README._

Replace this line with the URL to your repository here. Such as: [https://github.com/<username>/comp290site]

_6. The quick setup steps of your new GitHub repository's page give you an option of selecting either an HTTP or SSH URL. Select the SSH URL and copy it to your clipboard. Add it as a remote named `github` to your local repository as shown in GitHub. Push your `master` branch to your `github` remote. Once the project page updates on GitHub, you should see your README file's contents shown on the main page for your project on GitHub._

Replace this line with the commands you ran in the shell to complete step 6.

_7. Using GitHub, any repository can have a "project web page" by adding a branch named `gh-pages` with at least an `index.html` file to it. Begin by creating and checking out a new branch in your local repository named `gh-pages` as shown in lecture._

Replace this line with the commands you ran in the shell to complete step 7.

_8. Use `vim` to edit a file named `index.html`. Setup the basics of an HTML page (search the web for basic HTML file requirements) and be sure your name and some description that the page was created as practice for COMP290 are a part of the `<body>` content. Add this file to staging and make a new commit. Push the current branch you are on, `gh-pages`, to the `github` remote repository. Shortly after doing so, you should be able to navigate to: [https://<username>.github.io/comp290site] to see your `index.html` page published live on the internet!_

Replace this line with a link to your published project site.

_9. Navigate back to your project's repository page on GitHub: [https://github.com/<username>/comp290site] On the `Branch` dropdown, select the `gh-pages` branch. Notice this branch has your `index.html` file in it. Click on the `Commits` link (there should be at least 2 commits). Notice your `gh-pages` branch history is shown here. Finally, click on the commit where you added the `index.html` page and notice you can see the specific changes made in a commit._ 

Replace this line with a link to the commit page on GitHub where you added the `index.html` page.