How we git down
===

1. Choose a repository from [our locker](https://github.com/VolleyIndustries "All our repos")
2. Clone it somewhere awesome on your local machine

`git clone <url from repo>`

3. Check out a new branch with a hyphen-delimited title that's relevant to the task at hand

`git checkout -b dh-readme-adjustments origin/master`

4. Change anything to your hearts content
5. Push it up

`git push`

6. Open a pull request (in web)
7. Let someone else do a code review (ask for one on Slack)
8. Once approved, merge to master (in web)
9. Checkout master:

`git checkout master`

10. Delete the old branch:

`git branch -d dh-readme-adjustments`

11. Pull down your changes!

`git pull`
