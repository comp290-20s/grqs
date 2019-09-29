Register a GitHub account and login.

_1. Set a profile picture for your account, your name, your company as UNC Chapel Hill or some more recent internship, your location as Chapel Hill, NC or home. Respond below with a link to your github.com profile page._

[http://github.com/<your username>]

_2. In your COMP290 container, `cat` the SSH public key file setup in Lecture 1: `/mnt/learncli/.ssh/id_rsa.pub` Establish this key as a public key with your GitHub account by going to GitHub settings, selecting SSH and GPG keys, and adding a "New SSH Key". You'll want to select, copy, and then paste the key into the Key field. Give it a title of "COMP290 Container" or the likes. Respond to this question by also pasting your key below._

Replace this line with your public key.

_3. In your COMP290 container, make a directory named `<github-username>.github.io`, but replace `<github-username>` with _your_ GitHub username. Navigate into the directory. Initialize this directory to be an empty `git` repository. Create an empty file named `index.html` using the `touch` program. Add `index.html` to staging and make an initial commit._

Add each of the commands you ran for #3 here. Consider using the shell's history of commands to avoid retyping.

_4. Use `vim` to edit the file named `index.html`. Add some basic HTML describing you (name, major, graduation year, interests, etc). [New to HTML? Check out this guide](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started). Save your changes and exit `vim`. Add the changes you made to this file to a new commit._

What commands did you run to stage and make this second commit?

_5. On GitHub, create a new personal repository named `<github-username>.github.io` if you do not already have a personal GitHube Pages repository setup. (If you do already have one setup, use a different repository name for our purposes.) It should be _Public_ and you should _skip_ initializing the repository with a README._

Replace this line with the URL to your repository here. Such as: https://github.com/<username>/<username>.github.io

_6. The quick setup steps of your new GitHub repository give you an option of selecting either an HTTP or SSH URL. Select the SSH URL and copy it to your clipboard. Add it as a remote named `github` to your local repository. Push your `master` branch to your `github` remote._

Replace this line with the commands you ran in the shell to complete step 6.

7. 