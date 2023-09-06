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