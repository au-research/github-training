---
title: Contributing to a repo
permalink: /05-contributing-to-a-repo
layout: episode
---

At the end of this episode, learners will be able to:
* Contribute changes to someone else's repo
* Create contributing and reuse guidelines for their projects
Teaching: 15 minutes
Activities: 20 minutes

*For this episode you will need a partner. Pair up and exchange GitHub usernames.*

If you are making contributions to a repo that belongs to someone else, there is a good chance that you will not be able to push changes directly to it (unless you have been given push privileges).

If you cannot push directly to another repo, but want to submit changes for its owner to consider, you will need to follow this workflow:

1. **Fork** the repo to create your own copy
1. Edit and **commit** any changes to your forked repo
1. Submit a **pull request** for the owner to consider pulling your changes to the upstream repo

The repo owner will consider your changes in their review process and accept your changes, suggest revisions to your changes, or reject your changes.

When you submit a pull request, it is important to follow a repo’s contribution guidelines. These guidelines should outline how to submit a change request and what kind of changes are likely to be accepted or rejected. Create a CONTRIBUTING.md file to let others know how they can contribute to your project. For example, this workshop suggests how contributsion can be made by [using a CONTRIBUTING.md](https://github.com/au-research/github-training/blob/main/CONTRIBUTING.md) file.

Another useful file to add to your project is a [REUSE.md](https://au-research.github.io/ARDC-23-things/researchdata/reuse). By outlining the reuse possibilities, you are making your material a little FAIRer.

## What's the diff?

When reviewing a pull request, GitHub will show the "diff" (differences) that were made to file in the repository. Lines in the original files are red and lines in the new files are green. The diff will also highlight particular characters that have changed:

![Screenshot of diff]({{ site.baseurl }}/assets/diff-screenshot.png)

The diff makes it easier to spot the changes made while reviewing a pull request.

**Challenge** (20 minutes): Fork your partner's repo and make changes to one or more of the files. Then, submit a pull request for your partner to review. Then, swap roles and repeat.