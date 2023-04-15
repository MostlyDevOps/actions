# Reusable GitHub Actions for MostlyDevOps

> An example repo of how an org would consolidate all their reusable GitHub Actions into a single repo. 
> Other code and IaC repos would call these workflows from their repos.
> Other repo owners would copy `/templates` that they need to `.github/workflows` in their repos.
> This repo can also be used to store template linter configs in `.github/linters` used by super-linter or megalinter

## This repo is a demo implementation of the following [@BretFisher](https://github.com/BretFisher) examples

- [bretfisher/github-actions-templates](https://github.com/BretFisher/github-actions-templates) - Main reusable templates repository
- [bretfisher/super-linter-workflow](https://github.com/BretFisher/super-linter-workflow) - Reusable linter workflow
- [bretfisher/docker-build-workflow](https://github.com/BretFisher/docker-build-workflow)- Reusable docker build workflow
