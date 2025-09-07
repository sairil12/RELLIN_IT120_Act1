# Git Commands Used in Activity
git init
git add .
git commit -m "Initial commit with base files"
git branch -M main
# Branch 1 
git checkout -b RELLIN_B1
git add Profile.txt
git commit -m "Add birth place, religion, parents info to Profile.txt"
# Branch 2
git checkout main
git checkout -b RELLIN_B2
git add Education.txt
git commit -m "Add college, program, year level to Education.txt"
# Branch 3
git checkout main
git checkout -b RELLIN_B3
git add Background.txt
git rm -f Test.py
git commit -m "Update Background.txt and remove Test.py"
# Branch 4
git checkout main
git checkout -b RELLIN_B4
git add Readme.txt
git rm -f Test.py
git commit -m "Add Readme commands and remove Test.py"
# Push
git remote add origin https://github.com/sairil12/RELLIN_IT120_Act1.git
git push -u origin main
git push origin RELLIN_B1 RELLIN_B2 RELLIN_B3 RELLIN_B4
