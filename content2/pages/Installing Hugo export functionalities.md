---
title: Installing Hugo export functionalities
tags: 
categories: 
date: 2023-09-26
lastMod: 2023-09-26
---
I installed [a plugin](https://github.com/sawhney17/logseq-schrodinger) to export to a Hugo blog.

+ And I think I need to install Hugo before checking how it works...

+ I try to install this [logseq hugo template](https://github.com/CharlesChiuGit/Logseq-Hugo-Template).

	+ FAILED: I try installing it as a submodule of this repo. Instead of the more cumbersome process explained at their README.

	+ FAILED What worked was to merge the [logseq hugo template](https://github.com/CharlesChiuGit/Logseq-Hugo-Template) into the logseq repo using:

	+ I will try with this approach: [Export Logseq to Markdown](https://github.com/dom8509/logseq-to-markdown), that seems to have had the same issues I did: 1) not being able to call logseq plugins functions from the terminal, 2) not to have automatic actions to publish in github pages, etc.

		+ ``` bash
npm install @dom8509/logseq-to-markdown -g
git remote add logseq-hugo-template [GitHub - dom8509/hugo-PaperMod: A fast, clean, responsive Hugo theme.](https://github.com/dom8509/hugo-PaperMod.git)
git fetch logseq-hugo-template
git merge --allow-unrelated-histories logseq-hugo-template/master 
```

		+ After  solving some merge issues in README and configuration files, the hugo template will be ready to be used after configuring it.

		+ NEXT Follow this installation process and publish a github action for converting logseq to markdown [Publishing actions in GitHub Marketplace - GitHub Docs](https://docs.github.com/en/actions/creating-actions/publishing-actions-in-github-marketplace)

