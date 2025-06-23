# 🚀 Helper Markdowns

> A curated collection of markdown templates designed to streamline AI-assisted development workflows across Claude, Codex, and Cursor.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Template Categories](#template-categories)
- [Quick Start](#quick-start)
- [Template Reference](#template-reference)
- [Usage Examples](#usage-examples)
- [Best Practices](#best-practices)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

Helper Markdowns provides battle-tested markdown templates that help developers communicate more effectively with AI coding assistants. Whether you're debugging complex issues, writing comprehensive documentation, or planning architectural changes, these templates ensure you get the most accurate and helpful responses from your AI tools.

### Why Use Helper Markdowns?

- **🎨 Consistency**: Standardized formats across all your AI interactions
- **⚡ Speed**: Pre-structured templates save time on repetitive tasks
- **🎯 Precision**: Optimized prompts yield better AI responses
- **🔄 Reusability**: Copy-paste ready templates for common scenarios

## ✨ Features

- **Multi-Platform Support**: Templates optimized for Claude, Codex, and Cursor
- **Comprehensive Coverage**: From API documentation to security reviews
- **Developer-Focused**: Built by developers, for developers
- **Easy Integration**: Simple markdown files that work anywhere
- **Extensible**: Easy to customize and extend for your specific needs

## 📁 Template Categories

### 🤖 Claude Code Templates
Advanced templates optimized for Claude's capabilities:
- `api-docs.md` - API documentation generation
- `architecture.md` - System architecture planning
- `code-review.md` - Comprehensive code reviews
- `debug.md` - Debugging assistance
- `issues.md` - Issue tracking and resolution
- `migration.md` - Migration planning and execution
- `pull-requests.md` - PR descriptions and reviews
- `refactor.md` - Code refactoring strategies
- `release-notes.md` - Release note generation
- `security-review.md` - Security analysis
- `tests.md` - Test generation and strategies

### 💻 Codex Templates
Specialized templates for GitHub Copilot and OpenAI Codex:
- `api-docs.md` - API endpoint documentation
- `code-review.md` - Code quality assessment
- `debug.md` - Bug investigation
- `diff.md` - Code diff analysis
- `docstring.md` - Documentation string generation
- `issues.md` - Issue templates
- `optimize.md` - Performance optimization
- `pull-requests.md` - PR workflows
- `refactor.md` - Refactoring patterns
- `snippet.md` - Code snippet generation
- `tests.md` - Unit test creation

### 🖱️ Cursor Templates
*(Coming Soon)* - Templates optimized for Cursor IDE

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/helper-markdowns.git
   cd helper-markdowns
   ```

2. **Choose your AI tool folder**
   ```bash
   cd claude-code  # or codex/cursor
   ```

3. **Select a template**
   ```bash
   cat api-docs.md  # View template
   ```

4. **Copy and customize**
   - Copy the template content
   - Fill in the placeholders
   - Paste into your AI assistant

## 📚 Template Reference

### Claude Code Templates

| Template | Purpose | Best For |
|----------|---------|----------|
| `api-docs.md` | Generate comprehensive API documentation | REST APIs, GraphQL schemas |
| `architecture.md` | Design system architecture | New projects, major refactors |
| `code-review.md` | Perform thorough code reviews | PR reviews, code audits |
| `debug.md` | Debug complex issues | Production bugs, edge cases |
| `issues.md` | Create detailed issue reports | Bug tracking, feature requests |
| `migration.md` | Plan database/code migrations | Version upgrades, platform changes |
| `pull-requests.md` | Write effective PR descriptions | Code contributions |
| `refactor.md` | Plan refactoring strategies | Legacy code, optimization |
| `release-notes.md` | Generate release notes | Version releases, changelogs |
| `security-review.md` | Security vulnerability analysis | Security audits, pen testing |
| `tests.md` | Generate test suites | Unit tests, integration tests |

### Codex Templates

| Template | Purpose | Unique Features |
|----------|---------|-----------------|
| `diff.md` | Analyze code differences | Git diff interpretation |
| `docstring.md` | Generate documentation strings | Multiple language support |
| `optimize.md` | Performance optimization | Profiling, benchmarking |
| `snippet.md` | Quick code snippets | Boilerplate generation |

## 💡 Usage Examples

### Example: Using the Debug Template

```markdown
# 🐛 Debug Request

## Problem Description
Users report intermittent 500 errors when uploading files larger than 10MB.

## Environment
- Node.js 18.x
- Express 4.18
- Multer 1.4.5

## Error Messages
```
PayloadTooLargeError: request entity too large
    at readStream (/app/node_modules/raw-body/index.js:155:17)
```

## Steps to Reproduce
1. Upload file > 10MB via /api/upload endpoint
2. Error occurs ~50% of the time

## Expected Behavior
Files up to 50MB should upload successfully
```

### Example: Using the API Docs Template

```markdown
# 📝 API Documentation Request

## Endpoint Details
- **Path**: `/api/v1/users/:id`
- **Method**: GET, PUT, DELETE
- **Authentication**: Bearer token

## Request/Response Examples
```json
// GET Response
{
  "id": "123",
  "email": "user@example.com",
  "created_at": "2024-01-01T00:00:00Z"
}
```

## Generate
- OpenAPI 3.0 specification
- Response schemas
- Error handling
- Rate limiting details
```

## 🎯 Best Practices

1. **Be Specific**: Fill in all template sections with relevant details
2. **Provide Context**: Include file paths, versions, and environment info
3. **Show Examples**: Add code snippets and expected outputs
4. **Iterate**: Use follow-up prompts to refine results
5. **Version Control**: Track your customized templates

### Pro Tips

- 🔧 Customize templates for your tech stack
- 📊 Create project-specific template variants
- 🔄 Share successful templates with your team
- 📈 Track which templates yield best results

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b add-new-template
   ```
3. **Add your template**
   - Follow existing naming conventions
   - Include clear placeholders
   - Add usage examples
4. **Submit a PR**
   - Describe the template's purpose
   - Include usage examples
   - Tag relevant AI platforms

### Contribution Guidelines

- Use clear, descriptive template names
- Include comprehensive examples
- Test templates with target AI tools
- Document any platform-specific optimizations
- Keep templates focused and single-purpose

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/abdurmasood/helper-markdowns/issues">Report Bug</a> •
  <a href="https://github.com/abdurmasood/helper-markdowns/issues">Request Feature</a> •
  <a href="https://github.com/abdurmasood/helper-markdowns/discussions">Discussions</a>
</p> 