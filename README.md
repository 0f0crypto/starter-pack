# starter-pack

> A template for creating new repositories 

This repository is meant to serve as a general template for how to set up new repositories. In general, setting up a new repository should take only a few minutes; use this repository as a way of finding example files, and use the following checklist to ensure that you've set up the repository correctly.

## Install

These instructions are basic; you can use any method to do this work. The important part is making sure that you follow the checklist.

```sh
# Overwrite this README
mv README.md setup-checklist.md
mv example-README.md README.md
# Go over and check off the checklist, and finally
rm setup-checklist
```

## Checklist

Go through this checklist after creating your repository. It should only take a couple of minutes; if there is a way to make this more efficient, open an issue and let's talk about it here!

### README
- [ ] Copy `example-README.md` from this repository to your directory.
- [ ] Manually go through and edit the rest of the README.

### Other Files
- [ ] Should you have a `CHANGELOG.md`? 

### Dotfiles
- [ ] Do you need a `.gitignore` file?
- [ ] Do you need an `.npmignore` file?

### Project
- [ ] Create a default project (template: automated kanban)
- [ ] Add `Backlog` column (as the left-most column)

### Deployment
- [ ] Create a `production` branch
- [ ] Setup github workflows (main.yml)

### Tasks
- [ ] Add a task to create the dev environment (to-do)
- [ ] Add a task to create the github environment (to-do)
- [ ] Add a task to create the production environment (to-do)

### Documentation
- [ ] Do you need Software Requirements Specifications?
- [ ] Edit (or delete) the `SRS.md`

## Contribute

If you think this could be better, please [open an issue](https://github.com/scibuff/starter-pack/issues/new)!

## License

[MIT](LICENSE) © 2021 scibuff
