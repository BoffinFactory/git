### Introduction to Git
So you want to start working with Boffin Factory on some git repositories but
you don't know anything about Git?  Well you've come to the right place.  The
purpose of this repository is to get you up to speed on using git and provide a
list of reference materials for later projects.

#### Getting started
* Create an account on [GitHub](github.com)
* Absolutely new to git?  Read this [git
  handbook](https://guides.github.com/introduction/git-handbook/) (~10 minute
  read)
* Got more time/more questions?  Want to know a LOT more about git or solve a
  specific problem?  Check out the [Pro Git
  book](https://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub (emphasis
  on chapter's 2, and 3)

#### My first repository
Lets put some of this new-found knowledge to the test.
* Install git for your OS from the [git downloads page](https://git-scm.com/downloads)
* Create a repository on github, accept the defaults, and copy the link provided
  to your new repository.
* Launch either Git Bash (windows) or a terminal (linux / mac)
* Clone your repository with `git clone <link-copied-earlier>`
* `cd` into your repositories directory
* Create a file named `README.md` and add some text
* Stage the changes you've made with `git add README.md`
* Save a snapshot of your staged changes with `git commit`
* Update your remote repository (on github) with `git push`

After the above your repository on GitHub should have a new file named
`README.md`.  You should also notice this file gets displayed on the main page
of your repository in a pretty format due to it being a markdown file which gets
rendered by github automatically.  You can read more about markdown here: 

* [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Writing on GitHub](https://help.github.com/en/categories/writing-on-github)

A `README.md` file is a great way to document and layout your
project/repository in a slick way if used correctly.  Besides a `README.md`
there are a few other files each repository should have to assist users with
contributing to your project.

* `CONTRIBUTING.md` - File to document
* `LICENSE.md` - Describes what sort of license your work is to be protected
  under.  Check out the github page on [Licensing your
  Repository](https://help.github.com/en/articles/licensing-a-repository)
* `.gitignore` - A file that lists files and folders that git should always
  ignore when staging and commiting changes.  Read more on [how to ignore files
  in git](https://help.github.com/en/articles/ignoring-files)



