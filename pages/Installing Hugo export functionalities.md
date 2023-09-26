public:: true

- I installed [a plugin](https://github.com/sawhney17/logseq-schrodinger) to export to a Hugo blog.
	- And I think I need to install Hugo before checking how it works...
	  id:: 64f8dc26-094c-48aa-9f40-2ae8cc44f02f
	- I try to install this [logseq hugo template](https://github.com/CharlesChiuGit/Logseq-Hugo-Template).
		- ((64f8d87a-1c1a-45ce-a819-f69570b6aab6))
	- What worked was to merge the [logseq hugo template](https://github.com/CharlesChiuGit/Logseq-Hugo-Template) into the logseq repo using:
		- ``` bash
		  git remote add logseq-template [GitHub - CharlesChiuGit/Logseq-Hugo-Template: This is a HUGO website template for Logseq users who wants their published posts to look more like a personal website, using GitHub Pages to host the website and logseq-schrodinger to export your Logseq pages.](https://github.com/CharlesChiuGit/Logseq-Hugo-Template.git)
		  git fetch logseq-template --tags
		  git merge --allow-unrelated-histories logseq-template/main
		  git checkout logseq-template/main .github/workflows/publish.yml
		  ```