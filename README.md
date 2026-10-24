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

### Design systems

| Name | Path | Upstream | What it covers |
| --- | --- | --- | --- |
| Design System Doc Spec (DSDS) | `vendor/design/dsds` | [repo](https://github.com/somerandomdude/design-system-documentation-schema) · [site](https://designsystemdocspec.org/) | A draft schema for writing design system documentation as structured YAML, covering components, tokens, themes and guidelines. |
| Design Tokens Format (DTCG) | `vendor/design/dtcg` | [repo](https://github.com/design-tokens/community-group) · [2025.10](https://www.designtokens.org/TR/2025.10/) | The token file format from the W3C Design Tokens Community Group. 2025.10 is its first stable version. |
