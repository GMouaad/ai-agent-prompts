# AI Agent Prompts Repository

AI Agent Prompts is a content repository for collecting and organizing AI agent prompts, instructions, and related documentation. This is a documentation-focused repository with no build system, dependencies, or complex setup requirements.

Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Working Effectively

This repository requires no build steps, dependency installation, or complex setup. All operations are standard git and file editing workflows.

### Initial Setup and Validation
- Clone the repository (if not already done): `git clone https://github.com/GMouaad/ai-agent-prompts.git`
- Navigate to repository: `cd ai-agent-prompts` 
- Verify repository structure: `ls -la` -- takes <1 second
- Check git status: `git --no-pager status` -- takes <1 second
- View current branch: `git branch` -- takes <1 second

### Content Management
- Find all markdown files: `find . -name "*.md" -type f` -- takes <1 second
- View repository structure: `tree` (if available) or `find . -type f | head -20` -- takes <1 second
- View file contents: `cat README.md` or use your preferred editor
- Edit files using any text editor (vim, nano, vscode, etc.)

### Git Operations
- Check repository status: `git --no-pager status` -- takes <1 second
- View recent commits: `git --no-pager log --oneline -10` -- takes <1 second
- View file differences: `git --no-pager diff` -- takes <1 second
- Stage changes: `git add .` or `git add <specific-file>` -- takes <1 second
- Commit changes: `git commit -m "your message"` -- takes <1 second
- Push changes: `git push` -- takes 1-5 seconds depending on network

## Validation

Since this is a content repository with no application logic, validation primarily involves:
- Ensuring markdown files are properly formatted
- Verifying links work (if any are added)
- Checking that git operations complete successfully
- Manual review of content for accuracy and completeness

**NO BUILD OR TEST COMMANDS REQUIRED** - This repository contains only documentation and content files.

## Repository Structure

### Current Files
The repository currently contains minimal content:
```
.
├── .git/                 # Git repository data
├── .github/             # GitHub configuration (this file)
│   └── copilot-instructions.md
├── LICENSE              # MIT License
└── README.md            # Main repository readme (currently minimal)
```

### Expected Content Types
Based on the repository name "ai-agent-prompts", this repository is intended to contain:
- AI agent prompts and instructions
- Documentation for prompt engineering
- Examples and templates
- Best practices and guidelines
- Markdown-formatted content files

## Common Tasks

### Adding New Content
1. Create new markdown files: `touch new-prompt.md`
2. Edit content using your preferred editor
3. Stage changes: `git add new-prompt.md`
4. Commit: `git commit -m "Add new prompt: [description]"`
5. Push: `git push`

### Organizing Content
- Create subdirectories as needed: `mkdir prompts/`, `mkdir examples/`, etc.
- Move files: `mv file.md subdirectory/`
- Update any internal links if files are moved

### Content Review
- Preview markdown files in your editor or using tools like `markdown` command
- Check for broken links (manually or with link checking tools)
- Ensure consistent formatting and style

## Key Information for AI Agents

### Repository Purpose
This repository is designed to collect and organize AI agent prompts and related documentation. It serves as a knowledge base for prompt engineering and AI agent instructions.

### File Types
- **Primary**: Markdown (.md) files for documentation and prompts
- **Secondary**: Text files (.txt) for simple prompts
- **Configuration**: YAML (.yml) or JSON (.json) for structured data if needed

### No Complex Dependencies
- **NO package.json** - This is not a Node.js project
- **NO requirements.txt** - This is not a Python project  
- **NO build scripts** - No compilation or build process needed
- **NO test suite** - Content validation is manual
- **NO CI/CD pipelines** - Simple git workflows suffice

### Working with Content
- Always check existing content before adding new files to avoid duplication
- Follow consistent naming conventions (lowercase, hyphens for spaces)
- Use clear, descriptive filenames that indicate the prompt's purpose
- Include appropriate markdown headers and structure
- Consider adding a table of contents in README.md as content grows

### Git Workflow
- Work on feature branches for significant changes: `git checkout -b feature/new-prompts`
- Use descriptive commit messages that explain what prompts or content were added
- Keep commits focused on related changes
- Push regularly to avoid losing work

## Troubleshooting

### Common Issues and Solutions

**Issue**: "Repository appears empty"
**Solution**: This is expected for a new content repository. Begin adding markdown files with your prompts and documentation.

**Issue**: "No build files found"  
**Solution**: This is correct - no build system is needed. This is a content-only repository.

**Issue**: "Git operations failing"
**Solution**: Ensure you have proper git configuration and authentication set up. Run `git config --list` to verify settings.

**Issue**: "Changes not appearing"
**Solution**: Verify you've staged (`git add`) and committed (`git commit`) your changes before pushing.

### Performance Notes
All commands in this repository execute in under 1 second due to the minimal content and lack of build processes. No timeouts or long-running operations are expected.

## Repository Maintenance

### Regular Tasks
- Review and update README.md as content grows
- Organize content into logical directories
- Remove outdated or duplicate prompts
- Update this instruction file if repository structure changes significantly

### Content Guidelines
- Use clear, descriptive titles for prompts
- Include context and use cases for each prompt
- Provide examples where helpful
- Maintain consistent markdown formatting
- Consider adding metadata (tags, categories) for better organization