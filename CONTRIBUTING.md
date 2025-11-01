# Contributing to HUMMBL Claude Skills

Thank you for your interest in contributing to HUMMBL Claude Skills! This document provides guidelines for contributing new skills or improving existing ones.

## How to Contribute

### Reporting Issues

- Use GitHub Issues to report bugs or suggest enhancements
- Provide clear descriptions and examples
- Tag issues appropriately (bug, enhancement, documentation)

### Adding a New Skill

1. **Fork the repository**
2. **Create a new branch** (`git checkout -b skill/your-skill-name`)
3. **Create skill directory** with proper structure:
   ```
   your-skill-name/
   ├── SKILL.md        # Main skill file
   └── README.md       # Skill documentation
   ```

4. **Follow the skill format** (see below)
5. **Test your skill** with Claude
6. **Submit a pull request**

## Skill Format Requirements

### SKILL.md Structure

```markdown
---
name: your-skill-name
description: Clear description of what this skill does and when to use it (max 1024 chars)
---

# Your Skill Name

[Comprehensive guidance with sections:]

## Overview
## Core Competencies
## Implementation Guidelines
## Examples (minimum 2)
## Common Pitfalls
## Resources
```

### Naming Conventions

- **Skill name:** lowercase with hyphens (e.g., `mcp-server-developer`)
- **File names:** `SKILL.md` and `README.md` (exact capitalization)
- **Description:** Must trigger on relevant keywords
- **Length:** Minimum 300 lines for comprehensive skills

### Content Requirements

**Must Include:**
- ✅ Clear use cases and when to apply
- ✅ Step-by-step implementation guidance
- ✅ At least 2 real-world examples
- ✅ Templates or frameworks
- ✅ Common pitfalls and solutions
- ✅ Quality criteria or success metrics

**Optional but Recommended:**
- Code examples
- Decision trees or flowcharts
- Checklists
- Resource links

## Quality Standards

All skills must meet these criteria:

| Criterion | Requirement |
|-----------|-------------|
| **Format** | 100% Anthropic .skill spec compliance |
| **Clarity** | Clear, unambiguous instructions |
| **Completeness** | Covers topic comprehensively |
| **Examples** | Minimum 2 practical examples |
| **Usefulness** | Immediately actionable guidance |
| **Testing** | Verified to work with Claude |

**Target Quality Score:** 9.0/10 or higher

## Pull Request Process

1. **Update README.md** - Add your skill to the catalog
2. **Update CHANGELOG.md** - Document your addition
3. **Write clear PR description** - Explain what the skill does and why it's useful
4. **Request review** - Tag @hummbl-dev/maintainers
5. **Address feedback** - Make requested changes promptly
6. **Await merge** - Maintainers will merge when ready

### PR Template

```markdown
## Skill Description
[What does this skill do?]

## Use Cases
- Use case 1
- Use case 2

## Testing
- [ ] Tested with Claude Code
- [ ] Examples run successfully
- [ ] Documentation is clear

## Checklist
- [ ] Follows .skill format
- [ ] README.md updated
- [ ] CHANGELOG.md updated
- [ ] Minimum 2 examples included
- [ ] Common pitfalls documented
```

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code.

## Style Guidelines

### Markdown

- Use ATX-style headers (`#` not `===`)
- Include blank lines around lists and code blocks
- Use fenced code blocks with language tags
- Keep lines under 120 characters when possible

### Writing Style

- **Be concise:** Get to the point quickly
- **Be specific:** Use concrete examples
- **Be practical:** Focus on actionable guidance
- **Be comprehensive:** Cover edge cases and pitfalls

## Versioning

We use [Semantic Versioning](https://semver.org/):

- **MAJOR:** Breaking changes to skill format
- **MINOR:** New skills added
- **PATCH:** Bug fixes or improvements to existing skills

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

## Questions?

- **Issues:** https://github.com/hummbl-dev/hummbl-claude-skills/issues
- **Discussions:** https://github.com/hummbl-dev/hummbl-claude-skills/discussions

## Recognition

Contributors will be recognized in:
- CHANGELOG.md (for each contribution)
- README.md (contributors section)
- GitHub contributors page

Thank you for helping make HUMMBL Claude Skills better! 🎉
