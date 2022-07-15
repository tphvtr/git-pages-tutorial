1. Initialize empty git repo - git init
2. Create git repo in github.com
3. Add remote origin to empty repo - git remote add origin https://github.com/${username}/${repo-name}.git
4. Track your files, add first commit and push files to git
git add .
git commit -m "first commit"
git push --set-upstream origin master