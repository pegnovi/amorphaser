# Contribution information

### Where to find information/examples: http://phaser.io/examples/

### Type script versions of the same examples (note this repo is mostly incomplete but you may find some good examples anyway): https://github.com/mikaturunen/phaser-examples-typescript

### Typescript features:
https://basarat.gitbooks.io/typescript/content/docs/project/tsconfig.html

# Rules
- don't submit code that breaks the build :)
- this phaser game is written with typescript, so use it instead of js
- contributions should be done in feature branches and then merged with develop via pull requests

# How to PR
- the following will ensure your develop branch is up to date for your new branch
```
git checkout develop
git pull origin develop
git checkout -b feature-1
```
- do some work on feature-1 branch like so...
```
git add . && git commit -m "[feature-1] did some work on a feature"
git push origin feature-1
```
- push your branch to github then, go to the github page and click create new Pull Request
- create a Pull Request merging your branch (feature-1) into develop
- you'll receive feedback or your code will be merged into develop

## Style
- use tabs, with 2 spaces per tab
- if your code uses an external dependency please --save it to package.json or manually add it so others simply have to npm install to get your code working

## linting
- todo: setup tslint

## releases
