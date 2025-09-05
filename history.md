# Git Branching Task

```bash
git clone https://github.com/Rishitha2707/Git-branching-task.git
ls
cd Git-branching-task/
ls
git branch
mv README.md mf1
git add mf1
git commit -m "first file in master"
git tag v0.1
git checkout -b develop
touch df1
git add df1
git commit -m "1st file in develop branch"
touch df2
git add df2
git commit -m "2nd file in develop branch"
touch df3
git add df3
git commit -m "3rd file in develop branch"
git checkout -b feature1
touch ff1
git add ff1
git commit -m "1st file in feature1"
touch ff2
git add ff2
git commit -m "2nd file in feature1"
git checkout develop
git checkout -b feature2
touch f2f1
git add f2f1
git commit -m "1st-feature 2"
touch f2f2
git add f2f2
git commit -m "2nd file- feature 2"
touch f2f3
git add f2f3
git commit -m "3rd file-feature 2"
git checkout main
git checkout -b hotfix
touch hf1
git add hf1
git commit -m "1st file- hotfix"
git checkout main
touch mf2
git add mf2
git commit -m "2nd file - main"
git merge hotfix -m "merging hotfix into main"
git tag v0.2
git checkout develop
touch df4
git add df4
git commit -m "4th file- develop"
touch df5
git add df5
git commit -m "5th file- develop"
git merge hotfix -m "merging hotfix into develop branch"
touch df6
git add df6
git commit -m "6th file- develop"
git merge feature2 -m "merging feature2 to develop"
git checkout -b release
touch rf1
git add rf1
git commit -m "1st file - release"
touch rf2
git add rf2
git commit -m "2nd file - release"
git checkout develop
touch df7
git add df7
git commit -m "7th file - develop"
git checkout release
git checkout develop
git merge release -m "merging release into develop"
git checkout feature2
touch f2f4
git add f2f4
git commit -m "4th file - feature 2"
git merge develop -m "merging develop into feature 2"
touch f2f5
git add f2f5
git commit -m "5th file - feature 2"
touch f2f6
git add f2f6
git commit -m "6th file - feature 2"
git checkout release
touch rf3
git add rf3
git commit -m "3rd file - release"
touch rf4
git add rf4
git commit -m "4th file - release"
git checkout main
touch mf3
git add mf3
git commit -m "3rd file - main"
git merge release -m "merging release into main"
git tag v1.0
git checkout develop
touch df8
git add df8
git commit -m "8th file - develop"
git merge release -m "merging release into develop"
git checkout feature1
touch ff3
git add ff3
git commit -m "3rd file - feature 1"
touch ff4
git add ff4
git commit -m "4th file - feature 1"
git checkout develop
touch df9
git add df9
git commit -m "9th file - developo"
git merge feature2 -m "merging feature 2 into develop"
git merge feature1 -m "merging feature 1 into develop"
git checkout release
touch rf5
git add rf5
git commit -m "5th file - release"
git merge develop -m "merging develop into release"
git checkout develop
touch df10
git add df10
git commit -m "10th file - develop"
git merge release -m "merging release into develop"
git checkout release
git checkout main
touch mf4
git add mf4
git commit -m "4th file - main"
git merge release -m "merging release into main branch"
git push --all
git push --tags
```
