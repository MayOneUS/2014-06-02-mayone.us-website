# WARNING: DO NOT EDIT mayoneus.github.io DIRECTLY. GO TO [mayoneus-testing.github.io](https://github.com/MayOneUs-Testing/mayoneus-testing.github.io/) INSTEAD

## If you're on mayoneus-testing.github.io, read on.

mayoneus.github.io is the live website. This fork is a staging area available via
[mayoneus-testing.github.io](http://mayoneus-testing.github.io). Changes should be 
committed here first, checked to make sure they're good at [http://mayoneus-testing.github.io/](http://mayoneus-testing.github.io/), and then merged into 
mayoneus.github.io with a pull request. That way the staging branch is never 
missing any commits.

### For simple content changes
1. Open the file you want to edit in the github interface.
2. Make your changes.
3. At the bottom of the page, describe your change (or don't if it's trivial), and click "Commit changes".
4. In another tab, go to [http://mayoneus-testing.github.io/](http://mayoneus-testing.github.io/), verify your changes have been made and look good.
5. Back in your github tab, go back to the main page for the repository by clicking the [mayoneus-testing.github.io](https://github.com/MayOneUs-Testing/mayoneus-testing.github.io/) link at the top of the page.
6. Above the list of files, there's a green button with arrows on it. When you mouse over it, it says "Compare, review, create a pull request". This is the button that will let us push our changes into production. Click it.
7. Take a look at the changes you're going to pull over. If they look good, click "Create Pull Request".
8. Give it a title (doesn't really matter what it is), and click "Send Pull Request".
9. If you have direct commit access to the repo, you'll now be able to "Merge" the pull request (another green button). Click it.
10. Click "Confirm"
11. Check [mayone.us](http://mayone.us). Your changes should be live almost instantly.

### Local Testing

If you're making a trickier change, you may want to run jekyll locally so you 
don't have to push to see your changes.

Ruby must be installed on your system, as well as the version of Jekyll used by GitHub Pages: `gem install github-pages`

Simply run `jekyll serve --watch` and visit http://localhost:4000/

After you're satisfied, perform pretty much the same steps above.
