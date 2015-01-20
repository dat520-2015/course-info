# Course Info

* [Autograder Registration](https://github.com/uis-dat520/course-info/blob/master/autograder-registration.md)

* [Grading and Collaboration Policy](http://github.com/uis-dat520/course-info/blob/master/policy.md)

* [SSH for GitHub Authentication](http://github.com/uis-dat520/course-info/blob/master/github-ssh.md)

* [Frequently Asked Questions](http://github.com/uis-dat520/course-info/blob/master/FAQ.md)

* [Group Partner Match-up](http://github.com/uis-dat520/course-info/blob/master/group-partner-hunt.md)

* [Go Resources](http://github.com/uis-dat520/course-info/blob/master/go-resources.md)

# Updates to the labs repo

## Revised lab1: Multiwriter (Fri 16 Jan)

We have push out some changes to the `multiwriter*.go` files. *Be sure to read the entire bulletin before doing these instructions.* First, if you haven't made any edits to the `multiwriter*.go` files, then do this:

1. `cd $GOPATH/src/github.com/uis-dat520/labs`
2. Run the command `git pull origin master` to get the changes into your own repo.
3. Implement your own multiwriter code.
4. `git add multiwriter.go`
5. `git commit`
6. `git push labs` to push your code to your own `username-labs` repo on GitHub.

If you have already implemented some code in `multiwriter.go` files, then do this:

1. `cd $GOPATH/src/github.com/uis-dat520/labs/lab1`
2. Run `git status` and check if you have any uncommitted changes.
3. If you have changes in `multiwriter.go` you **must run**
   1. `git add multiwriter.go` and
   2. `git commit` to ensure that your changes are saved in the commit history.
4. `git pull origin master`
5. Resolve any merge conflicts and implement your own code in `multiwriter.go`. This can be a bit tricky. Please consult this [help](https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/) document.
6. `git add multiwriter.go`
7. `git commit`
8. `git push labs` to push your code to your own `username-labs` repo on GitHub.

PS: It is very helpful to understand the state of your local git repo by running the `git status` command. You can run this at any time; it will not make any changes, just tell you the status of the repo.

