How we git down
===
####Starting fresh

-  Choose a repository from [our locker](https://github.com/VolleyIndustries "All our repos")
-  Clone it somewhere awesome on your local machine

`git clone <url from repo>`

####Making a new change

- Check out a new branch with a hyphen-delimited title that's relevant to the task at hand

`git checkout -b dh-readme-adjustments origin/master`

- Code baby code

####When you're done
- Fetch the latest from the master branch

`git fetch`

- Add all your additions/deletions of files (always do this even if you didn't delete or add any new files)

`git add --all`

- Commit your changes

`git commit -am "my awesome commit title"`

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
