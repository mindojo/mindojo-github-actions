# Mindojo reusable github-actions and workflows

Use those workflows and actions in your repos to not reinvent a bicycle and to synchronise the development process across our repositories.

Learn how to take advantage of reusable workflows in [github docs](https://docs.github.com/en/actions/using-workflows/reusing-workflows#calling-a-reusable-workflow).


## Release drafter
If you want to reuse the reusable config that is located at `.github/release-drafter.yml`, create a new file in your repository, name it `release-drafter.yml` and save it in `.github/release-drafter.yml`. The contents of the file should be the following:
```
_extends: mindojo/mindojo-github-actions:.github/release-drafter.yml
```