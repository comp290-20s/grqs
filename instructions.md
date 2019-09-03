---
title: GRQ - Instructions 
author: 
- COMP290 - Fall 2019
geometry: margin=1in
---

To begin work on GRQs, begin a COMP290 command-line interface container.

On Windows, open PowerShell and navigate to your `learncli` directory. Then issue the command `.\learncli.ps1 comp290`

On Mac, open Terminal and navigate to your `learncli` directory. Then issue the command `./learncli.sh comp290`

## Download the Markdown File

Within the container, use `curl` to fetch the GRQ markdown source text from the given web URL and redirect its output to a file. In the example below the letters XY should be replaced with the GRQ assignment number.

`curl https://raw.githubusercontent.com/comp290-19f/grqs/master/grqXY.md > grqXY.md`

Use the `ls` program to list the files in your current directory and confirm you now have a file named `grqXY.md`.

## Open the GRQ Markdown File in `vim`

Run the command `vim grqXY.md`, again replacing `XY` with the GRQ assignment number. This will open `vim`.

Your first task is to change Line 4 "- Your Name Here" on Line 4 to be a dash followed by your actual name.

Refer to the handout and Lecture 1 slides for `vim` command grammar.

To save your work without exiting `vim`, be sure you are in `Normal` mode and key `:w` followed by pressing the `Enter` key.

To save your work _and_ exit `vim`, also from `Normal` mode, key `ZZ`.

To jump ahead in the file to specific text (i.e. search with Ctrl+F in a web page), from `Normal` mode key a forward slash `/` followed by the text you are searching for and press enter. For example, try `/1.1` and press enter. The text you enter her is a regular expression, just like `grep` uses. Press `n` to jump to the _next_ match and `N` to jump to the _previous_ match. This is helpful for jumping to some specific point in your file.

## Expectations of GRQ Markdown

You are expected to delete and replace the lines which contain the text "Replace this line with your answer."

You should leave in place the original question text.

Anywhere you respond with a `shell command` or `code` you should surround that text with backticks so that it is ultimately formatted in a monospace font.

If you need to format other text in a specific way, such as a bulleted list, italics, or bold, please refer to online markdown documentation. Try searching for "markdown cheat sheet".

Failure to follow these guidelines will result in style penalties.

## PDF Generation and Submission

When you are ready to submit your GRQs to Gradescope, you need to convert the markdown file to PDF format. A free, open-source program named `pandoc` makes this process easy (and can convert to many other file formats, as well).

Save your work in `vim` and quit it. From the `learncli$` prompt, issue the command:

`pandoc -o grqXY.pdf grqXY.md`

The `-o grqXY.pdf` option indicates the desired output file. The `pandoc` program uses the `pdf` extension to decide to do the PDF conversion. The `grqXY.md` argument is the name of your GRQ markdown file.

On your host operating system, open the `learncli` directory in Windows File Explorer or Mac Finder. Then navigate into the `workdir` directory. Here you should see the `grqXY.pdf` file. Open it to be sure it looks formatted as you would expect.

Once you are happy with the resulting PDF file, upload it to the correct GRQ submission page on Gradescope. Great work!
