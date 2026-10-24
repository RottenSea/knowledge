# knowledge

Personal knowledge base for documentation.

External documents are git submodules under `vendor/`, each pinned to a commit.

## Cloning

```bash
git clone --recurse-submodules https://github.com/RottenSea/knowledge.git
```

In an existing clone, run `git submodule update --init` to fetch the submodules.

## Updating sources

`git submodule update --remote` moves every submodule to the latest commit on the branch set in `.gitmodules`. Review what changed, then commit the new pointers.

## Sources

### Accessibility

| Name | Path | Upstream | What it covers |
| --- | --- | --- | --- |
| Web Content Accessibility Guidelines (WCAG) | `vendor/a11y/wcag` | [repo](https://github.com/w3c/wcag) · [WCAG 2.2](https://www.w3.org/TR/WCAG22/) | The W3C Recommendation for accessible web content. It is a shallow clone, so only the latest commit is fetched. |
| ARIA Authoring Practices Guide (APG) | `vendor/a11y/apg` | [repo](https://github.com/w3c/aria-practices) · [site](https://www.w3.org/WAI/ARIA/apg/) | Keyboard and ARIA patterns for common widgets such as dialogs, tabs and menus, each with a working example. |

### Conventions

GitHub Docs has paths longer than 260 characters. On Windows, run `git config --global core.longpaths true` before cloning, or those files fail to check out.

| Name | Path | Upstream | What it covers |
| --- | --- | --- | --- |
| Conventional Commits | `vendor/conventions/conventional-commits` | [repo](https://github.com/conventional-commits/conventionalcommits.org) · [site](https://www.conventionalcommits.org/) | A format for commit messages that tools can parse to build changelogs and pick version bumps. |
| GitHub Docs | `vendor/conventions/github-docs` | [repo](https://github.com/github/docs) · [contributing guide](https://docs.github.com/en/contributing) | The source of docs.github.com. Its style guide and content model are in `content/contributing/`. It is a shallow clone, so only the latest commit is fetched. |
| Keep a Changelog | `vendor/conventions/keep-a-changelog` | [repo](https://github.com/olivierlacan/keep-a-changelog) · [site](https://keepachangelog.com/) | How to structure a CHANGELOG.md, with sections such as Added, Changed and Fixed under each release. |
| Semantic Versioning | `vendor/conventions/semantic-versioning-specification` | [repo](https://github.com/semver/semver) · [site](https://semver.org/) | The MAJOR.MINOR.PATCH version scheme and when to bump each part. |
| Standard Readme | `vendor/conventions/standard-readme` | [repo](https://github.com/RichardLitt/standard-readme) | A specification for which sections a README has and in what order. |

### Design systems

| Name | Path | Upstream | What it covers |
| --- | --- | --- | --- |
| Design System Doc Spec (DSDS) | `vendor/design/dsds` | [repo](https://github.com/somerandomdude/design-system-documentation-schema) · [site](https://designsystemdocspec.org/) | A draft schema for writing design system documentation as structured YAML, covering components, tokens, themes and guidelines. |
| Design Tokens Format (DTCG) | `vendor/design/dtcg` | [repo](https://github.com/design-tokens/community-group) · [2025.10](https://www.designtokens.org/TR/2025.10/) | The token file format from the W3C Design Tokens Community Group. 2025.10 is its first stable version. |
