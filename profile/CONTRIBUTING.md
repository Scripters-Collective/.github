# Contributing to Scripters-Collective

Thank you for considering contributing to the Scripters-Collective! This document outlines our guidelines to ensure all contributions are legal, ethical, and beneficial to the community.

## 🎯 Our Mission

We're building a library of practical scripts and tools for systems administrators and engineers. Quality, legality, and usefulness are our top priorities.

## ⚖️ Legal Requirements (READ CAREFULLY)

Before contributing ANY code, you must ensure:

### What You CAN Contribute

✅ Scripts you wrote entirely on your own time using your own equipment
✅ Scripts that solve general problems (not company-specific workflows)
✅ Tools based on publicly available information and documentation
✅ Modifications to existing open-source code (respecting original licenses)
✅ Scripts inspired by your work but completely rewritten from scratch
✅ Educational examples that demonstrate general concepts

### What You CANNOT Contribute

❌ Scripts that contain company-specific logic, configurations, or workflows
❌ Code copied from your employer's repositories or systems
❌ Scripts that would violate your employment agreement or NDA
❌ Code containing proprietary algorithms or business logic
❌ Any credentials, API keys, hostnames, or internal system details
❌ Scripts that automate company-specific processes or integrate with proprietary systems
❌ Code that you don't have clear legal rights to share

### The "Clean Room" Rule

When in doubt, ask yourself: "Could I recreate this script from scratch using only public documentation and general knowledge?" If the answer is no, don't contribute it.

### If You're Unsure

- Review your employment contract and any IP agreements
- Consider whether the script reveals anything about your employer's infrastructure or processes
- Ask yourself if the script would be useful to someone at a completely different organization
- When in doubt, DON'T contribute it

## 📝 Contribution Process

### 1. Before You Start

- Check if a similar tool already exists in the organization
- Open an issue to discuss your idea if it's a significant addition
- Ensure your code follows our legal requirements

### 2. Code Standards

**General Requirements:**
- Code must be well-commented and readable
- Include error handling and input validation where possible
- No hardcoded credentials or sensitive information
- Use meaningful variable and function names
- Utilize an "Oh, that makes sense." mindset

**PowerShell:**
- Follow PowerShell best practices and naming conventions
- Use approved verbs (Get-, Set-, New-, etc.)
- Include comment-based help
- Support `-WhatIf` and `-Verbose` where applicable

**Bash:**
- Use proper shebang (`#!/bin/bash` or `#!/usr/bin/env bash`)
- Follow shellcheck recommendations
- Quote variables properly
- Use functions for reusable code

**Python:**
- Follow PEP 8 style guidelines
- Use Python 3.x (We want to keep things as modern and current as possible)
- If you are using an earlier version of python for whatever reason, clearly state it in a comment earlier in your code
- Include docstrings for functions and modules
- List dependencies in requirements.txt

### 3. Documentation Requirements

Every contribution must include:

- **README.md** (if creating a new repo) explaining:
  - What the script does
  - Prerequisites and dependencies
  - Installation/setup instructions
  - Usage examples
  - Known limitations or issues
  
- **Inline comments** explaining complex logic
- **Example usage** in the README or separate examples directory
- **License information** (MIT or Apache 2.0 recommended)

### 4. Security Guidelines

- Never include credentials, even in examples (use placeholders)
- Don't hardcode IP addresses, hostnames, or domain names
- Use environment variables or config files for site-specific data
- Sanitize any logs or output that might contain sensitive information
- Consider potential security implications of your script

### 5. Making Your Contribution

As an organization member, you have direct commit access to repositories:

**For new repositories:**
1. Create a new repository in the organization (you have permissions to do this)
2. Initialize it with a README and LICENSE
3. Clone the repository locally
4. Add your code following the structure guidelines
5. Push your commits
6. Announce the new repo in Discussions so others know about it

**For existing repositories:**
1. Clone the repository
2. Create a feature branch for significant changes (`git checkout -b feature/descriptive-name`)
3. Make your changes
4. Test thoroughly
5. Commit with clear messages (`git commit -m 'Add feature: describe what it does'`)
6. Push directly to main (for small fixes) or to your feature branch
7. If using a feature branch, merge it when ready

**Best practices:**
- For minor fixes or additions, commit directly to main
- For major changes or refactors, use a feature branch and let others know in case they want to review
- Write clear commit messages that explain what and why
- Test your code before pushing

### 6. Repository Structure

Organize your repository like this:

```
repository-name/
├── README.md
├── LICENSE
├── src/
│   ├── main-script.ps1 (or .sh, .py)
│   └── helper-functions.ps1
├── examples/
│   └── usage-example.md
├── docs/
│   └── additional-documentation.md
└── .gitignore
```

## 🐛 Reporting Issues

When reporting issues:

- Use a clear, descriptive title
- Describe the expected behavior
- Describe the actual behavior
- Include steps to reproduce
- Specify your environment (OS, PowerShell/Bash/Python version, etc.)
- Include relevant error messages or logs (sanitized!)
- If something is believed to contain information that would violate an external IP, make it known. If found to be the case, the accused repo will be removed.

## 💡 Suggesting Enhancements

We love new ideas! When suggesting enhancements:

- Check if someone else has already suggested it
- Clearly describe the feature and its benefits
- Explain your use case
- Consider whether it would be useful to others

## 🔍 Trust and Integrity Model

Scripters-Collective operates on a trust-based system. All organization members are personally vetted and have direct commit access to repositories. We rely on each member's integrity and professional judgment to:

- **Self-verify legal compliance** - Ensure your contributions meet all IP requirements
- **Self-assess security** - Review your own code for security concerns before committing
- **Maintain quality** - Submit well-written, documented, and tested code
- **Consider usefulness** - Ask yourself if this will benefit the community

**With great access comes great responsibility.** Because we trust our members with direct commit access, it's crucial that everyone takes the legal and ethical guidelines seriously. Your reputation and the integrity of the collective depend on it.

If you're unsure about a contribution, reach out to other members in Discussions or create an issue to get feedback before committing.

## 🤝 Code of Conduct

Be professional and respectful:

- Be welcoming to newcomers
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy toward others

## 📋 Certification

By contributing, you certify that:

1. You have the legal right to contribute the code
2. You grant the Scripters-Collective and its members the right to use your contribution under the repository's license
3. You understand that your contribution will be publicly visible
4. The contribution does not violate any agreements you have with your employer or others
5. You will not hold the organization or its members liable for any issues arising from your contribution

## ❓ Questions?

If you have questions about whether something is appropriate to contribute, ask! Open an issue or start a discussion. It's better to ask than to accidentally contribute something problematic.

## 🙏 Thank You!

Your contributions make this collective valuable for everyone. We appreciate your time, effort, and commitment to doing things the right way.

---

**Remember: When in doubt, leave it out. Your career and the integrity of this organization depend on respecting intellectual property rights.**
