---
title: Contributing to These Docs
keywords: homepage
tags: [getting_started contributing]
sidebar: home_sidebar
permalink: overview.html
layout: contributing
summary: Instructions for contributing to these docs
---

If you'd like to suggest changes, you can open a PR against the repository. You can make your edits either on your computer or within Github itself.

## Making Edits Inside Github

If you are only suggesting small changes, then it can be easier to edit within Github instead of forking the repo and working on your local machine.

To start with this method, navigate to the page you want to make the edits to and choose the pencil icon on the right side. Most pages in this repo have a link at the bottom to take you directly to the .md file in the repository to make this easier.

![Image with edit buttom highlighted](/images/articleedit.png)

Github will automatically convert your markdown to html when you choose to preview changes, so this is an excellent way to ensure the changes will appear as you intended. Once you are ready, create a commit at the bottom of the page. Ensure that you are creating a new branch or fork even if you have permission to commit directly to the master branch.

![Image of commit text boxes](/images/commitchanges.png)

Once you've pushed 'Commit changes', Github will automatically open up the new pull request screen for you to submit a new PR with those changes.

## Setting up the Site for Local Development 

## Submitting a Pull Request

Github PR docs: https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/

Once you have made your changes, go to the main repository and open a new PR on the Pull Request tab.

![Image of PR tab](/images/newpr.png)

The base branch will be the master branch for healthygamer.github.io and the comparison branch will be the branch with your changes. If you don't see the branch from your fork in the dropdown, you can click 'compare across forks' to choose both repo and branch from the dropdowns. If you get a warning about merge conflicts,please resolve those before opening a PR. Take a minute to scroll down and review your changes and then click 'Create pull request'.

![Image of fork comparison](/images/compareforks.png)

Keep your title short and include a description of your changes in your pull request. You don't have to link your PR to an issue, but if it relates to an open issue including HealthyGamer/HealthyGamer.github.io#{issue number} in the title or description will automatically link the two together.

![Image of PR with linked issue](/images/prwithlink.png)

Github should send any updates on your PR to your account email. Please keep an eye on that or your Github account in case the maintainer needs you to resolve any issues with your PR before it can be merged.

{% include links.html %}
