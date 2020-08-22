1. Fork this repo.
2. Click the Clone or Download button to locate and copy the SSH address. (Make sure you are looking at your forked copy of the repository and not Jenn's copy!)
3. Open up your command line and navigate to the directory where you want to place your repo. Make sure you’re not inside of another repo by using the pwd or ls command.
4. Use the git clone command followed by the SSH address you copied from GitHub.
5. Use the cd command to move into your new repo: cd cp-git-guestbook.
6. Create and move into a new topic branch: git checkout -b guest-page.
7. Use the explorer . (PC) or open . (Mac) command to open the cp-git-guestbook directory.
8. Download the jenn.html file. Unzip and extract the file.
9. Rename the jenn.html file to add your first name and last initial to the file name. For example, if your name is Captain America, you’ll rename the file as captain-a.html.  
10. Move your guest page HTML file to the pages directory inside the cp-git-guestbook directory.
11. Preview your guest page HTML file in your browser to see what it looks like before editing it.
12. Open your guest page HTML file with your code editor. Replace Jenn's name with your name! Add your own thoughts and style for all to see! Save your changes when complete.
Bonus: Feel free to create your own CSS file in the css directory to style your guest book page! Name your CSS file with your first name and last initial. On the guest book HTML page, don’t forget to change the stylesheet link to the link to your custom style sheet. 
13. In the main directory, open the index.html file in your text editor.
14. Add a link to your guestbook HTML page with the other links. For example, Captain America would write: <a href="advice/captain-a-advice.html" target="_blank">Captain A's Page</a><br>. Save the file when finished.
15. Navigate back to your command line to add and commit your changes.
16. Push the changes on your branch to your repo: git push origin guest-page.
17. To make sure you’re still in sync with the source code, you’ll connect to the upstream: git remote add upstream git@github.com:maeeast/cp-git-guestbook.git.
18. Run the git remote -v command to see which repos you’re connected to. You should see the repo your version of the repo (origin) and the source code repo (upstream).
19. Use the git fetch command to update your remote branches: git fetch upstream.
20. Run the git branch -a command to view your local and remote branches. In the list of branches, you should upstream/master, which is the branch you’ll use to stay in sync with the source code.
21. Use the git checkout command to move into your master branch to make it match the source code. Merge the upstream branch into your master branch: git merge upstream/master. Now your local master branch is updated with the most recent changes!
22. Take a look at the message after you merged. If you see “Already up to date,” that means the upstream code hasn’t changed since you originally forked your repo. Or, you might see a list of files that were added or updated since you forked the repo or synced your local code. Either way, you’ll now ensure your local code is in sync with the source code!
23. To incorporate the updates from the upstream, you’ll move back into the guest-page branch using the git checkout command.
24. Use the git merge command to merge the freshly updated master branch into the guest-page branch.
25. Push the guest-page branch up to your repo: git push origin guest-page.
26. Go to your forked copy of the cp-git-guestbook repo on GitHub.
27. In the Branch drop-down menu, select the guest-page branch. Then, click the New Pull Request button.
28. On the Open a Pull Request page, click the Create Pull Request button. 
29. Then we'll merge your changes!