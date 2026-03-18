# Contributing

We’re glad you want to help. You can fix docs, improve templates, add tooling, or help out in Discord.

**Docs:** Fix typos, clarify wording, add examples, or translate. New tutorials and guides are welcome.

**Code:** Improve workflows, submission checks, or starter templates. Bug fixes and small tools help.

**Design:** Better docs layout, diagrams, or assets. We’re not picky.

**Community:** Answer questions, give feedback on submissions, or run a small workshop.

**Setup:** You need a GitHub account and Git. Discord helps for discussion. Fork the repo, then:

```bash
git clone https://github.com/conflux-fans/global-hackfest-2026.git
cd global-hackfest-2026
```

2. **Add Upstream Remote**
   ```bash
   git remote add upstream https://github.com/conflux-fans/global-hackfest-2026.git
   ```

3. **Create a Branch**
   ```bash
   git checkout -b feature/your-contribution-name
   ```

## 🔄 Contribution Process

### 1. Planning Your Contribution

Before starting work:
- **Check existing issues** to see if your idea is already being worked on
- **Create an issue** to discuss your proposed changes
- **Get feedback** from maintainers and community members
- **Clarify scope** and requirements

### 2. Making Changes

#### Documentation Changes
- Use clear, concise language
- Follow existing formatting and style
- Include examples where helpful
- Test all links and references
- Ensure accessibility (alt text for images, clear headings)

#### Code Changes
- Follow existing code style and conventions
- Include appropriate tests
- Update documentation as needed
- Ensure changes don't break existing functionality

### 3. Testing Your Changes

#### Documentation Testing
- **Spell check**: Use a spell checker
- **Link validation**: Ensure all links work
- **Formatting**: Preview markdown rendering
- **Accessibility**: Check for accessibility issues

#### Code Testing
- **Run existing tests**: Ensure nothing breaks
- **Add new tests**: For new functionality
- **Manual testing**: Test changes manually
- **Cross-platform**: Test on different environments if applicable

### 4. Submitting Your Contribution

#### Commit Guidelines
Use clear, descriptive commit messages:

```bash
# Good examples
git commit -m "docs: fix typo in submission checklist"
git commit -m "feat: add automated link validation workflow"
git commit -m "fix: correct prize distribution in hackathon"

# Commit message format
type(scope): description

# Types: feat, fix, docs, style, refactor, test, chore
# Scope: area of change (optional)
# Description: brief description of change
```

#### Pull Request Process

1. **Update your branch**
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Push your changes**
   ```bash
   git push origin feature/your-contribution-name
   ```

3. **Create Pull Request**
   - Go to GitHub and create a pull request
   - Use the pull request template
   - Provide clear description of changes
   - Link related issues

4. **Respond to feedback**
   - Address reviewer comments
   - Make requested changes
   - Update documentation if needed

## 📝 Style Guidelines

### Documentation Style

#### Writing Style
- **Clear and concise**: Use simple, direct language
- **Active voice**: Prefer active over passive voice
- **Consistent terminology**: Use the same terms throughout
- **Inclusive language**: Use gender-neutral and inclusive language

#### Formatting
- **Headers**: Use descriptive headers with proper hierarchy
- **Lists**: Use bullet points or numbered lists for clarity
- **Code blocks**: Use appropriate syntax highlighting
- **Links**: Use descriptive link text, not "click here"

#### Structure
```markdown
# Main Title (H1)

## Section Title (H2)

### Subsection Title (H3)

#### Detail Title (H4)

- Bullet point
- Another bullet point

1. Numbered item
2. Another numbered item

**Bold text** for emphasis
*Italic text* for subtle emphasis
`Code text` for technical terms
```

### Code Style

#### General Principles
- **Readability**: Code should be self-documenting
- **Consistency**: Follow existing patterns
- **Simplicity**: Prefer simple solutions
- **Comments**: Explain why, not what

#### File Organization
```
global-hackfest-2026/
├── docs/                    # Documentation files
├── .github/                 # GitHub-specific files
│   ├── ISSUE_TEMPLATE/     # Issue templates
│   └── workflows/          # GitHub Actions
├── templates/              # Template files
└── scripts/               # Utility scripts
```

## 🏷️ Issue Guidelines

### Creating Issues

#### Bug Reports
Use the bug report template and include:
- **Clear description** of the problem
- **Steps to reproduce** the issue
- **Expected behavior** vs actual behavior
- **Environment details** (browser, OS, etc.)
- **Screenshots** if applicable

#### Feature Requests
Use the feature request template and include:
- **Problem statement** - what problem does this solve?
- **Proposed solution** - how should it work?
- **Alternatives considered** - other approaches
- **Additional context** - mockups, examples, etc.

#### Documentation Issues
- **Specific location** of the problem
- **Suggested improvement** or correction
- **Context** for why the change is needed

### Issue Labels

| Label | Description |
|-------|-------------|
| `bug` | Something isn't working |
| `enhancement` | New feature or request |
| `documentation` | Improvements or additions to docs |
| `good first issue` | Good for newcomers |
| `help wanted` | Extra attention is needed |
| `question` | Further information is requested |
| `wontfix` | This will not be worked on |

## 👥 Community Guidelines

### Communication Standards
- **Be respectful**: Treat everyone with respect and kindness
- **Be constructive**: Provide helpful, actionable feedback
- **Be patient**: Remember that people have different experience levels
- **Be inclusive**: Welcome newcomers and diverse perspectives

### Code of Conduct
All contributors must follow our [Code of Conduct](CODE_OF_CONDUCT.md). Key points:
- No harassment or discrimination
- Professional and respectful communication
- Focus on constructive collaboration
- Report violations through Discord or Telegram

### Getting Help
- **Discord**: https://discord.gg/4A2q3xJKjC
- **Telegram**: https://t.me/ConfluxDevs
- **Documentation**: https://doc.confluxnetwork.org/
- **GitHub Discussions**: For detailed technical discussions
- **Issues**: For specific bugs or feature requests

## 🎖️ Recognition

### Contributor Recognition
We recognize valuable contributions through:
- **GitHub contributors page**: Automatic recognition for merged PRs
- **Special mentions**: In release notes and announcements
- **Community highlights**: Featured in Discord and social media
- **Contributor badges**: Special Discord roles for active contributors

### Types of Recognition
- **First-time contributor**: Welcome and encouragement
- **Regular contributor**: Ongoing recognition and thanks
- **Expert contributor**: Invitation to review others' contributions
- **Community leader**: Opportunity to help guide project direction

## 📚 Resources

### Learning Resources
- **Git Tutorial**: [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- **Markdown Guide**: [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- **GitHub Flow**: [Understanding GitHub Flow](https://guides.github.com/introduction/flow/)
- **Open Source Guide**: [How to Contribute](https://opensource.guide/how-to-contribute/)

### Conflux Resources
- **Conflux Documentation**: [doc.confluxnetwork.org](https://doc.confluxnetwork.org/)
- **Developer Portal**: [developer.confluxnetwork.org](https://developer.confluxnetwork.org/)
- **Community Forum**: [forum.conflux.fun](https://forum.conflux.fun/)
- **GitHub Organization**: [github.com/Conflux-Chain](https://github.com/Conflux-Chain)

### Tools and Utilities
- **Markdown Editors**: Typora, Mark Text, or VS Code with markdown extensions
- **Git Clients**: GitHub Desktop, GitKraken, or command line
- **Image Optimization**: TinyPNG, ImageOptim for reducing file sizes
- **Accessibility Testing**: WAVE, axe DevTools for accessibility checking

## 🚀 Advanced Contributions

### Becoming a Maintainer
Active contributors may be invited to become maintainers. Responsibilities include:
- **Reviewing pull requests**: Ensuring quality and consistency
- **Triaging issues**: Organizing and prioritizing community feedback
- **Community support**: Helping newcomers and answering questions
- **Project planning**: Contributing to roadmap and feature decisions

### Technical Leadership
Experienced contributors can take on technical leadership roles:
- **Architecture decisions**: Helping design new features and improvements
- **Code review**: Providing detailed technical feedback
- **Mentorship**: Guiding new contributors and sharing expertise
- **Documentation**: Creating comprehensive technical documentation

## 📞 Contact

### Maintainer Team
- **Lead Maintainer**: [Name] - [email]
- **Documentation Lead**: [Name] - [email]
- **Community Manager**: [Name] - [email]

### Getting in Touch
- **Discord**: https://discord.gg/4A2q3xJKjC
- **Telegram**: https://t.me/ConfluxDevs
- **Documentation**: https://doc.confluxnetwork.org/

## 📄 License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project (MIT License). See [LICENSE](LICENSE) for details.

---

## 🙏 Thank You

Thank you for contributing to Global Hackfest 2026! Your contributions help make the blockchain development community more welcoming, educational, and innovative.

Every contribution, no matter how small, makes a difference. Whether you're fixing a typo, adding a new feature, or helping someone in Discord, you're helping build something amazing.

**Happy contributing!** 🎉

---

*This contributing guide is a living document. If you have suggestions for improvements, please open an issue or submit a pull request.*

*Last updated: 2026-01-23* 