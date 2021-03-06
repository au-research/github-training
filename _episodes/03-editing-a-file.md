---
title: Editing a file
permalink: /03-editing-a-file
layout: episode
---

At the end of this episode, learners will be able to:
* Refer to markdown documentation
* Edit a file in their own GitHub repo
Teaching: 15 minutes
Activities: 20 minutes

## Before we edit - Markdown

You might notice that GitHub can render files with formatting similar to documents and websites - headers, **bold**, *italic*, _underline_, and dot points.

It does this by using a markup language known as markdown. Markdown lets an author use characters to apply formatting to their text. As an example, inspect the ["raw" markdown](https://raw.githubusercontent.com/au-research/your-first-step-to-fair/main/episodes/01-introduction.md) for some [teaching material](https://au-research.github.io/your-first-step-to-fair/01-introduction). You can also use a service like [HackMD](https://hackmd.io/cSdCixNBSICU4yor5sxwjQ?both) to simultaneously view markdown and the rendered text.

GitHub uses some conventions beyond standard markdown, and so it uses what is called "GitHub-flavored markdown". GitHub has published [a guide for the different formatting options](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax) and syntax to using them.

Markdown itself is a free and open standard, which means that anybody can incorporate it into their software or projects without needing to pay a licensing fee. By using Markdown to write documents in our project, we are avoiding the need to install proprietary software like Microsoft Office.

## Editing a file

Every file you view in GitHub should have an edit icon above it. When you click that icon, GitHub will behave differently depending on whether you have the right to edit files in that repo.

If you *do* have the right to edit files, you can edit the file and commit the changes directly back to the repo. You will also have the option to create a new branch with your changes and submit a pull request so that your changes can be reviewed before being incorporated.

If you *do not* have the right to edit files, GitHub will automatically fork the repo for you to work in, and let you submit a pull request so that your changes can be reviewed before being incorporated.

**Demonstration** (5 minutes): Create a LICENCE.md file containing the text of your preferred Creative Commons licence (but not CC0!)

**Challenge** (15 minutes): Edit the README.md file in the repo you created in episode 2. Use some markdown formatting to add a link to LICENCE.md before committing your changes directly to the main branch. Do not create a new branch and start a pull request - we will be doing that later in this workshop.

You might like to use [readme.so](https://readme.so/) to help you structure your README.

**Challenge** (5 minutes): Edit the [README.md file for this lesson](https://github.com/au-research/github-training/blob/main/README.md). What happens differently?