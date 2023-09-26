- FAILED What worked was to merge the [logseq hugo template](https://github.com/CharlesChiuGit/Logseq-Hugo-Template) into the logseq repo using:
  id:: 65131bc4-5155-42e2-b87c-3d91e2f691bb
	- ``` bash
	  git remote add logseq-template [GitHub - CharlesChiuGit/Logseq-Hugo-Template: This is a HUGO website template for Logseq users who wants their published posts to look more like a personal website, using GitHub Pages to host the website and logseq-schrodinger to export your Logseq pages.](https://github.com/CharlesChiuGit/Logseq-Hugo-Template.git)
	  git fetch logseq-template --tags
	  git merge --allow-unrelated-histories logseq-template/main
	  git checkout logseq-template/main .github/workflows/publish.yml
	  ```
	- However, I could not make an automated workflow to unzip the exported graphs, and kept having issues with this.
- ((65131bc4-5155-42e2-b87c-3d91e2f691bb))
- Failed attempts :)
-
- FAILED: I try installing it as a submodule of this repo. Instead of the more cumbersome process explained at their README.
  id:: 64f8d87a-1c1a-45ce-a819-f69570b6aab6
	- ``` bash
	  git submodule add https://github.com/CharlesChiuGit/Logseq-Hugo-Template.git
	  ```
	- Well, this gives error because README.md already exist in both repos, so going back
	- ``` bash
	  git rm -rf Logseq-Hugo-Template
	  ```