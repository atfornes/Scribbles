public:: true

- I installed [a plugin](https://github.com/sawhney17/logseq-schrodinger) to export to a Hugo blog.
	- And I think I need to install Hugo before checking how it works...
	  id:: 64f8dc26-094c-48aa-9f40-2ae8cc44f02f
	- I try to install this [logseq hugo template](https://github.com/CharlesChiuGit/Logseq-Hugo-Template).
		- ((64f8d87a-1c1a-45ce-a819-f69570b6aab6))
		- ((65131bc4-5155-42e2-b87c-3d91e2f691bb))
		- I will try with this approach: [Export Logseq to Markdown](https://github.com/dom8509/logseq-to-markdown), that seems to have had the same issues I did: 1) not being able to call logseq plugins functions from the terminal, 2) not to have automatic actions to publish in github pages, etc.
			- ``` bash
			  npm install @dom8509/logseq-to-markdown -g
			  git remote add logseq-hugo-template [GitHub - dom8509/hugo-PaperMod: A fast, clean, responsive Hugo theme.](https://github.com/dom8509/hugo-PaperMod.git)
			  git fetch logseq-hugo-template
			  git merge --allow-unrelated-histories logseq-hugo-template/master 
			  ```
			- After  solving some merge issues in README and configuration files, the hugo template will be ready to be used after configuring it.
			- NEXT Follow this installation process and publish a github action for converting logseq to markdown [Publishing actions in GitHub Marketplace - GitHub Docs](https://docs.github.com/en/actions/creating-actions/publishing-actions-in-github-marketplace)
			-