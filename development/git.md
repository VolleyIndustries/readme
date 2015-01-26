How we git down
===

-  Choose a repository from [our locker](https://github.com/VolleyIndustries "All our repos")
-  Clone it somewhere awesome on your local machine

`git clone <url from repo>`

- Check out a new branch with a hyphen-delimited title that's relevant to the task at hand

`git checkout -b dh-readme-adjustments origin/master`

- Change anything to your hearts content
- Push it up

`git push`

- Open a pull request (in web)
- Let someone else do a code review (ask for one on Slack)
- Once approved, merge to master (in web)
- Checkout master:

`git checkout master`

- Delete the old branch:

`git branch -d dh-readme-adjustments`

- Pull down your changes!

`git pull`
