
> [!warning] Delete this before pushing this template to your GitHub repo (before you publish it)
# Automating Releases for Obsidian Template in Github

## Parts that affects the GitHub release/.zip file

- `version` - changes the version of the release in GitHub
- `release_name` - title of the release
- `only_release_if_new` - makes it so that it only releases when `version` changes
## Parts for your own use

- `date created`
- `date modified`
- Notes below the YAML frontmatter/properties

```
---
release_notes: This release includes updated docs and new content.
date created: Monday, December 9th 2024, 10:32 pm
date modified: Monday, December 9th 2024, 10:34 pm
release_name: SecOps Obsidian Vault
only_release_if_new: "true" %% or false %%
---

# Release Information

1st release of the template.  Unzip and open in Obsidian.

## Fixes
- Timestamp format fix
```

