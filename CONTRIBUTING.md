# Contributing to Overlord Class Mod

Thank you for your interest in contributing to the Overlord Class Mod for Darkest Dungeon! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Reporting Bugs
- Use the [Bug Report Template](.github/ISSUE_TEMPLATE/bug_report.md)
- Provide detailed steps to reproduce the issue
- Include game version and mod version information
- Attach screenshots if applicable

### Suggesting Features
- Use the [Feature Request Template](.github/ISSUE_TEMPLATE/feature_request.md)
- Consider game balance implications
- Provide implementation ideas if possible

### Code Contributions
- Fork the repository
- Create a feature branch (`git checkout -b feature/amazing-feature`)
- Make your changes
- Test thoroughly
- Commit with clear messages (`git commit -m 'Add amazing feature'`)
- Push to your branch (`git push origin feature/amazing-feature`)
- Open a Pull Request

## 🛠️ Development Setup

### Prerequisites
- Darkest Dungeon game files
- Basic understanding of modding
- Text editor (VS Code recommended)

### File Structure
```
├── heroes/ainz/           # Character files
│   ├── ainz.info.darkest  # Character stats and skills
│   ├── ainz.art.darkest   # Visual configuration
│   └── anim/              # Animation files
├── effects/               # Skill effects
├── localization/          # Text and descriptions
├── campaign/              # Town and district files
└── modfiles.txt          # File manifest
```

### Key Files to Modify
- **`heroes/ainz/ainz.info.darkest`**: Character stats, skills, equipment
- **`heroes/ainz/ainz.art.darkest`**: Visual effects, animations
- **`effects/ainz.effects.darkest`**: Skill effects and mechanics
- **`localization/ainz.string_table.xml`**: Text and descriptions

## 📋 Coding Standards

### File Naming
- Use descriptive names
- Follow existing conventions
- Use lowercase with underscores

### Code Style
- Use clear, descriptive comments
- Follow existing formatting
- Test changes thoroughly

### Commit Messages
- Use conventional commit format
- Be descriptive and clear
- Reference issues when applicable

## 🎮 Testing Guidelines

### Before Submitting
- Test all modified skills
- Check for balance issues
- Verify compatibility with other mods
- Test in different game scenarios

### Testing Checklist
- [ ] Skills work as intended
- [ ] No crashes or errors
- [ ] Balance feels appropriate
- [ ] Text displays correctly
- [ ] Animations work properly

## ⚖️ Balance Guidelines

### Character Balance
- Ainz should be powerful but not overpowered
- Skills should have clear trade-offs
- Consider interaction with other characters
- Maintain thematic consistency

### Skill Design
- Each skill should have a clear purpose
- Consider risk vs reward
- Balance damage, utility, and limitations
- Maintain Overlord theme

## 📝 Documentation

### Code Comments
- Comment complex logic
- Explain game mechanics
- Document balance decisions
- Reference source material when applicable

### User Documentation
- Update README.md for user-facing changes
- Update CHANGELOG.md for all changes
- Provide clear installation instructions
- Document new features

## 🚀 Release Process

### Version Numbering
- Follow semantic versioning (MAJOR.MINOR.PATCH)
- Increment appropriately for changes
- Update project.xml version

### Release Checklist
- [ ] All tests pass
- [ ] Documentation updated
- [ ] Version numbers updated
- [ ] Changelog updated
- [ ] Tagged and released

## 🤝 Community Guidelines

### Be Respectful
- Respect other contributors
- Provide constructive feedback
- Be patient with questions
- Help newcomers

### Communication
- Use clear, respectful language
- Provide context for suggestions
- Be open to different perspectives
- Follow project conventions

## 📞 Getting Help

### Questions and Support
- Check existing issues and discussions
- Use GitHub Discussions for questions
- Tag maintainers for urgent issues
- Provide detailed information when asking for help

### Resources
- [Darkest Dungeon Modding Guide](https://www.reddit.com/r/darkestdungeon/wiki/modding/)
- [Game Files Documentation](https://www.reddit.com/r/darkestdungeon/wiki/modding/)
- [Community Discord](https://discord.gg/darkestdungeon)

## 📄 License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to the Overlord Class Mod! Your help makes the mod better for everyone.