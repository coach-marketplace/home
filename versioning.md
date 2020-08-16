# Versioning

Obviously we use [Git](https://git-scm.com/) to keep tracking of version history for the project. And if you read that you are surely on Github, the software we use on top of that.

## Branching model

We set some rules for the way we use branching model and naming.

The `master` branch is the principal one, it's directly linked to the server on production, so we never work directly on it, except for hot fixes.

The most important branch is `staging`, is the main development branch. We always branch from it to develop a new feature.

![branching model image](https://user-images.githubusercontent.com/39580007/89981141-a6711500-dc73-11ea-9711-3732d4565232.png)

## Branches naming conventions

### Master

Production version

### Staging

Staging version

### feature/

Any new feature should be develop on the branch (from `staging`) and have a name like `feature/add-login-button` for example. This will help to keep all ongoing feature in the `feature` folder (if you are using a git client)

### fix/

If you need to work on a bug, you can name your branch `fix/wrong-redirection-on-newsletter-form` for example.

### docs/

Use `docs` convention name for any change, add or deletion if it's related to a readme file, code documentation or any documentation related change.

### imp/

If you need to code on any kind of improvement, like testing, refactoring, optimise performances,... You can use the `imp` convention (for improvement). Example: `imp/add-testing-for-service-creation`

## Development process

If you need to develop anything, be sure to always branch from `staging` (Don't forget to be up-to-date pulling the last version).

- Once your branch is created locally, and you did any change on it, you can already open a `draft` pull request to the target branch (could be staging or any other sub-branch, but never master) to get review during the development process.
- Be sure to use correct label on your Pull Request and add the [ready](https://github.com/fitigai/api/labels/%F0%9F%99%8C%20ready%20%F0%9F%99%8C) label when you think the branch is ready to be merged.
