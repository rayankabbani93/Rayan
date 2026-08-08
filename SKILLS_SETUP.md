# Claude Code Skills Setup Guide

This document tracks all available skills from the claude-skills marketplace for easy installation.

## Add the Marketplace

```bash
/plugin marketplace add alirezarezvani/claude-skills
```

## Skill Bundles by Domain

### Engineering Skills
```bash
/plugin install engineering-skills@claude-code-skills          # 24 core engineering skills
/plugin install engineering-advanced-skills@claude-code-skills  # 25 POWERFUL-tier skills
```

### Product Skills
```bash
/plugin install product-skills@claude-code-skills               # 12 product skills
```

### Marketing Skills
```bash
/plugin install marketing-skills@claude-code-skills             # 43 marketing skills
```

### Regulatory & Quality Management
```bash
/plugin install ra-qm-skills@claude-code-skills                 # 12 regulatory/quality skills
```

### Project Management
```bash
/plugin install pm-skills@claude-code-skills                    # 6 project management skills
```

### C-Level Advisory
```bash
/plugin install c-level-skills@claude-code-skills               # 28 C-level advisory (full C-suite)
```

### Business & Growth
```bash
/plugin install business-growth-skills@claude-code-skills       # 4 business & growth skills
```

### Finance
```bash
/plugin install finance-skills@claude-code-skills               # 2 finance skills (analyst + SaaS metrics)
```

## Individual Skills

For targeted use, install specific skills:

### Development & Testing
```bash
/plugin install skill-security-auditor@claude-code-skills       # Security scanner
/plugin install playwright-pro@claude-code-skills                  # Playwright testing toolkit
```

### AI & Learning
```bash
/plugin install self-improving-agent@claude-code-skills         # Auto-memory curation
```

### Content Creation
```bash
/plugin install content-creator@claude-code-skills              # Single skill
```

## Installation Methods

### Quick Setup (All Recommended Skills)
```bash
# Add marketplace
/plugin marketplace add alirezarezvani/claude-skills

# Install all bundles
/plugin install engineering-skills@claude-code-skills
/plugin install engineering-advanced-skills@claude-code-skills
/plugin install product-skills@claude-code-skills
/plugin install marketing-skills@claude-code-skills
/plugin install ra-qm-skills@claude-code-skills
/plugin install pm-skills@claude-code-skills
/plugin install c-level-skills@claude-code-skills
/plugin install business-growth-skills@claude-code-skills
/plugin install finance-skills@claude-code-skills
```

### Minimal Setup (Engineering Focus)
```bash
/plugin marketplace add alirezarezvani/claude-skills
/plugin install engineering-skills@claude-code-skills
/plugin install engineering-advanced-skills@claude-code-skills
/plugin install playwright-pro@claude-code-skills
/plugin install skill-security-auditor@claude-code-skills
```

## Total Skills Available

- **Engineering**: 24 + 25 = 49 skills
- **Product**: 12 skills
- **Marketing**: 43 skills
- **Regulatory/Quality**: 12 skills
- **Project Management**: 6 skills
- **C-Level**: 28 skills
- **Business & Growth**: 4 skills
- **Finance**: 2 skills
- **Individual Skills**: 4 skills

**Total**: 160+ skills across all domains

## Usage

After installation, use skills with Claude Code:

```bash
/skill-security-auditor
/playwright-pro
/senior-architect
# etc...
```

Refer to individual skill documentation for usage examples and best practices.
