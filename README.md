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

### Design systems

| Name | Path | Upstream | What it covers |
| --- | --- | --- | --- |
| Design System Doc Spec (DSDS) | `vendor/design/dsds` | [repo](https://github.com/somerandomdude/design-system-documentation-schema) · [site](https://designsystemdocspec.org/) | A draft schema for writing design system documentation as structured YAML, covering components, tokens, themes and guidelines. |
| Design Tokens Format (DTCG) | `vendor/design/dtcg` | [repo](https://github.com/design-tokens/community-group) · [2025.10](https://www.designtokens.org/TR/2025.10/) | The token file format from the W3C Design Tokens Community Group. 2025.10 is its first stable version. |
