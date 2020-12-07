git init
git checkout -b MyNew
git add .
git branch secondB
git add .
git commit -m 'second branch'
git checkout MyNew
git remote add origin https://github.com/digitworm/ItProger.git
git push -u origin MyNew