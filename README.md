# git-cafe-exercise (Commands used)

## Bundle 5

### Exercise 1

> Enable github pages for the repository

### Exercise 2

> forked the repository from [here](https://github.com/TheGymRwanda/git-cafe-exercise)

```shell
  git clone git@github.com:devark28/git-cafe-exercise.git
  # used vscode to edit index.html
  git add -A
  git commit -m 'FIX: changed section 2 welcome title'
  git push
  ```

## Bundle 6

### Exercise 1

```shell
  git checkout -b ft/menu-page
  # used vscode to edit index-3.html
  git add -A
  git commit -m 'Feat: created a new menu page from index-3 and added some changes'
  git push --set-upstream origin ft/menu-page
  # created a pull request on github
  ```

### Exercise 2

```shell
  git checkout main
  git checkout -b ft/fix-contact-page
  # used vscode to edit index-4.html
  git add -A
  git commit -m "Fix: change title of contact page (index-4.html) to 'Contact'"
  git push --set-upstream origin ft/fix-contact-page
  # created a pull request on github
  ```

### Exercise 3

```shell
  git checkout main
  # used vscode to make phone number hotfix to index-4.html
  git add -A
  git commit -m 'Fix: hot fix the phone number'
  git push
  ```

### Exercise 4

> reviewed and merged some of my peers' pull requests
