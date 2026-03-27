firebase init hosting
firebase deploy --only hosting

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/Raneesh-kamar/human-timeline.git
git push -u origin main

git push -u origin main --force
