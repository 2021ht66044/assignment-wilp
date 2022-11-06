# Git Basics
> Assigment Wilp


```bash
##Project assignment-wilp create directory on local system
mkdir assigment-wilp
cd assigment-wilp
```

```bash
## Create repo on github and follow the instructions on local system
echo "# assignment-wilp" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/2021ht66044/assignment-wilp.git
git push -u origin main
```
```bash
## Create a branch(development/production/feature)
git checkout -b development
git push -u origin development

git checkout -b production
git push -u origin production

git checkout -b feature
git push -u origin feature
```

```bash
##Edit files or create new files followed by commit
echo "conflict to resolved by merge"

```

```bash
##Clone the repo and Create pull-request
```

```bash
##While collaborating your work, showcase how conflicts are resolved
```

```bash
##Create tag such as open issue, or feature-added
```

```bash
##Do a force push/commit and then later reset the changes
```
```bash
##Stage “development branch to production branch”
```
```bash
##Showcase how features are released in versions (merging production to master branch)
```
```bash
##Also, state importance of Readme and gitignore files and their usage while working in a distributed environment.
```
```bash
##Bonus point: If Pull Requests are linked with e-mail to the manager who finally approves the changes.
```