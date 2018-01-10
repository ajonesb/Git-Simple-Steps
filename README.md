# Git-Simple-Steps

 Here's some very quick steps I gathered to setting up with Git and getting up and running with your project from updating, creating branch, checking out branch, merging branches, and pushing branch to repository. 

* Always update before running your app
	git pull


* git checkout master
 

* create a new branch named "feature_x" and switch to it using
	git checkout -b feature_x


* Stage the file for commit to your local repository after development
	git add .


* Commit the file that you've staged in your local repository.
	git commit -m "Add existing file"


* To merge another branch into your active branch (e.g. master), use
	git merge <branch>


* Push the changes in your local repository to GitHub or whichever repo you have setup. 
	git push origin your-branch
	# Pushes the changes in your local repository up to the remote repository you specified as the origin


* New Pull Request will be available (Will show exact url location of pull request on console.)
	Create Pull Request (Only for Bitbucket)


* Merge pull request once approved. (Only for Bitbucket)


- GIT Simple Steps Resources: 
	- http://rogerdudler.github.io/git-guide/
	- https://stackoverflow.com/questions/25053697/git-merge-two-local-branches
	- https://help.github.com/articles/adding-a-file-to-a-repository-using-the-command-line/
