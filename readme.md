1. Initialize empty git repo - git init
2. Create git repo in github.com
3. Add remote origin to empty repo - git remote add origin https://github.com/${username}/${repo-name}.git
4. Track your files, add first commit and push files to git
git add .
git commit -m "first commit"
git push --set-upstream origin master
5. Click on "Settings" in your repo
6. Go to "Pages" tab
7. Choose source branch, for ex. "master"
8. After ~1 min you'll see a notification with the link to your deployed site

!IMPORTANT!

index.html should be in the root

Demo: https://tphvtr.github.io/git-pages-tutorial/
