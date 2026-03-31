## Summary

<!-- Concise summary of what changed and why -->

Closes: #(issue)

## References

- Contribution guide: [CONTRIBUTING.md](../CONTRIBUTING.md)
- Skills catalog and categories: [skills/README.md](../skills/README.md)

## If this PR adds a new skill

- [ ] The new skill folder is under `skills/<skill-name>/`
- [ ] `SKILL.md` frontmatter includes `name` and `description`
- [ ] `name` matches folder name and uses kebab-case
- [ ] I checked `skills/README.md` and assigned this skill to the correct category
- [ ] I considered whether this should be merged into an existing skill instead of creating a new one
- [ ] I updated `skills/README.md` (name, description, status, and link if applicable)

Chosen category in `skills/README.md`:

<!-- e.g. 3. Prediction Engines -->

Merge/Separate decision note:

<!-- Why this is a new skill vs extension of an existing one -->

## Validation

<!-- Include concrete commands and results -->

```bash
# Example:
# npx skills add . --list
# npx skills add . --skill <skill-name>
```

## Impact

- Affected skills:
- Backward compatibility:
- Risks / limitations:

## Checklist

- [ ] Change type: New skill / Update skill / Bug fix / Docs / Other
- [ ] I read [CONTRIBUTING.md](../CONTRIBUTING.md)
- [ ] I searched for duplicate PRs/issues
- [ ] I tested changes locally
- [ ] I updated related docs (README / skills catalog / examples) if needed
