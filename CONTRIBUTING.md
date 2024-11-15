# Contributing to DevSecOps Learning Journey

First off, thank you for considering contributing to this learning repository! While this is primarily a personal learning journey, thoughtful contributions that enhance the learning experience are welcome.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [Repository Structure](#repository-structure)
- [Module Structure](#module-structure)
- [File Naming Conventions](#file-naming-conventions)
- [Content Guidelines](#content-guidelines)
- [Pull Request Process](#pull-request-process)
- [Pull Request Template](#pull-request-template)
- [Review Criteria](#review-criteria)
- [Questions?](#Questions?)

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

Basic principles:
- Be respectful and inclusive
- Focus on constructive feedback
- Maintain professional discourse
- Support the learning environment

## Repository Structure

```markdown
DevSecOps-Learning-Journey/
├── 00-Meta/                  # Meta information and templates
├── 01-Modules/              # Core learning modules
├── 02-Labs/                 # Hands-on labs
├── 03-Projects/             # Projects
├── 04-Resources/            # Reference materials
├── 05-Diagrams/             # Visual content
├── 06-Daily-Notes/          # Daily learning logs
└── 07-Archive/              # Deprecated content
```

### Module Structure
Each module follows this structure:
```markdown
M[XX]-[Module-Name]/
├── 01-[topic]/
│   ├── 01-[subtopic]/
│   │   ├── 01-[content].md
│   │   └── README.md
│   └── README.md
├── 02-[topic]/
├── 03-practice/
│   ├── 01-[exercise-type]/
│   │   └── README.md
│   └── README.md
└── 04-resources/
    ├── 01-templates/
    │   └── README.md
    └── README.md
```

## File Naming Conventions

1. **Directories**:
   - Top-level numbered directories: `00-Meta`, `01-Modules`, etc.
   - Module directories: `M01-DevSecOps-Intro`, `M02-Linux-Shell`, etc.
   - Sub-directories: Always prefixed with numbers (`01-fundamentals`, `02-tools`, etc.)

2. **Files**:
   - All markdown files: lowercase with hyphens (`01-introduction.md`)
   - Each directory should contain a `README.md`
   - Content files should be numbered (`01-overview.md`, `02-setup.md`)

3. **READMEs**:
   - Every directory should have a `README.md`
   - Should provide overview and navigation for that directory

## Content Guidelines

1. **README Files**
   - Directory overview
   - List of contents
   - Prerequisites (if any)
   - Learning objectives
   - Navigation guide

2. **Content Files**
   - Clear headings and structure
   - Code examples where applicable
   - Links to resources
   - Practice exercises or examples

3. **Documentation**
   - Clear and concise
   - Include examples
   - Link to related content
   - Include diagrams where helpful

## Pull Request Process

1. **Fork and Clone**
   - Fork the repository
   - Clone your fork locally
   - Create a new branch for your changes

2. **Make Changes**
   - Follow the directory structure
   - Maintain consistent naming conventions
   - Include README.md files
   - Test all links and code examples

3. **Submit PR**
   - Push changes to your fork
   - Create Pull Request
   - Fill in PR template
   - Link relevant issues

### Pull Request Template
```markdown
## Description
[Describe your changes here]

## Type of Change
- [ ] New module content
- [ ] Content update/correction
- [ ] Structure/organization
- [ ] Documentation
- [ ] Other (please specify)

## Checklist
- [ ] Files follow naming convention
- [ ] Directory structure maintained
- [ ] README.md files included
- [ ] Content is clear and accurate
- [ ] Links are working
- [ ] Code examples tested
```

## Review Criteria

Contributions will be reviewed based on:
1. Adherence to style guides
2. Technical accuracy
3. Documentation quality
4. Overall value addition

## Questions?

If you have questions about contributing:
1. Check existing issues and documentation
2. Create a new issue with the "question" label
3. Be specific about your query
4. Include relevant context

---

Thank you for contributing to making this learning journey better! 🚀
