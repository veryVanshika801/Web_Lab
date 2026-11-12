
# P4 – GitHub README and Version Tags

## Aim

To document the project using a GitHub README file and learn how to create version tags.

## Repository README

The root README.md file provides basic information about the Web Development Lab repository. It contains the practical folder names and the technologies used.

## Git Commands

First, check the repository status:

```bash
git status
git log --oneline
```

Create an annotated version tag after the P1–P4 practical work is available locally:

```bash
git tag -a v1.0.0 -m "First version of Web Development Lab"
git tag
git push origin v1.0.0
```

To inspect the created tag:

```bash
git show v1.0.0
```

## Description

- `git status` displays the current state of the repository.
- `git log --oneline` shows the commit history in a short format.
- `git tag -a` creates an annotated version tag.
- `v1.0.0` is the name given to the version.
- `-m` adds a message describing the tag.
- `git tag` lists all available tags.
- `git push origin v1.0.0` uploads the version tag to GitHub.
- `git show v1.0.0` displays information about the selected tag.

## Result

The repository was documented using a README file. A version tag named v1.0.0 was successfully created and pushed to GitHub.
