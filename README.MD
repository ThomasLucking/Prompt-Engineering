# Prompt Engineering Library

A personal collection of AI prompts designed for effective learning, code improvement, and document analysis. Built by Thomas, a 16-year-old Swiss IT apprentice.

## Quick Start

**New here?** Check out [index.mdx](./index.mdx) for an interactive prompt selector and full catalog.

**Learning prompt engineering?** Start with [Meta-prompts/Prompt_Template.mdx](./Meta-prompts/Prompt_Template.mdx) to understand the framework.

## What's Inside

This library contains **10 specialized prompts** organized into 4 categories:

### Code Learning & Tutoring (4 prompts)
Build better code through Socratic teaching methods:
- **[learnReact.mdx](./Code_workflow/learnReact.mdx)** - React/TypeScript code review tutor
- **[WebProject.mdx](./Code_workflow/WebProject.mdx)** - Web app project guidance (HTML/CSS/TypeScript)
- **[Tutor.mdx](./Code_workflow/Tutor.mdx)** - General CS tutor with lesson creation
- **[Typescript.mdx](./Code_workflow/Typescript.mdx)** - TypeScript style guide & best practices

### Document & Data Analysis (4 prompts)
Understand complex documents and analyze data effectively:
- **[DocAnalysisExcel.mdx](./Document-Analyse/DocAnalysisExcel.mdx)** - Full data analysis workflow (Excel/Word/PPT)
- **[DocExam.mdx](./Document-Analyse/DocExam.mdx)** - Pivot tables and visualization for exams
- **[DocAnalysisNotes.mdx](./Document-Analyse/DocAnalysisNotes.mdx)** - Simplify complex technical documents
- **[RiskAnalysis.mdx](./Code_workflow/RiskAnalysis.mdx)** - Generate risk analysis documents

### Prompt Engineering (2 prompts)
Learn to create better prompts:
- **[Prompt_Template.mdx](./Meta-prompts/Prompt_Template.mdx)** - 4-component framework (Role, Context, Task, Constraints)
- **[prompt_short.mdx](./Code_workflow/prompt_short.mdx)** - Get feedback on your prompts

### Knowledge Base
- **Knowledge/** - Reserved for future learning prompts and concept notes

## Repository Structure

```
Prompt-Engineering/
├── index.mdx                    # Main catalog with prompt selector
├── README.MD                    # This file
├── Code_workflow/               # Code learning & tutoring prompts
│   ├── learnReact.mdx
│   ├── WebProject.mdx
│   ├── Tutor.mdx
│   ├── Typescript.mdx
│   ├── RiskAnalysis.mdx
│   └── prompt_short.mdx
├── Document-Analyse/            # Document & data analysis prompts
│   ├── DocAnalysisExcel.mdx
│   ├── DocExam.mdx
│   └── DocAnalysisNotes.mdx
├── Meta-prompts/                # Prompt engineering frameworks
│   └── Prompt_Template.mdx
└── Knowledge/                   # Future: Learning notes and concepts
```

## Features

### Standardized Metadata
Every prompt includes frontmatter with:
- Title and description
- Version and date
- Tags for categorization
- Related prompts for navigation
- Type classification

### Cross-References
Each prompt links to related prompts, making it easy to discover complementary tools.

### Teaching Philosophy
Most prompts use the **Socratic method**:
- Ask guiding questions instead of giving answers
- Help develop problem-solving strategies
- Never rewrite code directly
- Provide increasingly specific hints

### Structured Workflows
Task-specific prompts include:
- Clear input/output requirements
- Step-by-step processes
- Validation guidelines
- Format examples

## How to Use

1. **Browse** the [index.mdx](./index.mdx) prompt selector
2. **Choose** a prompt that matches your need
3. **Copy** the entire prompt content
4. **Paste** into your AI chat interface
5. **Customize** the context sections with your specific situation
6. **Follow** the workflow instructions in the prompt

## Tags Reference

Browse prompts by tag:
- `teaching`, `tutoring` - Learning-focused prompts
- `code-review` - Code improvement and feedback
- `data-analysis` - Excel and data visualization
- `document-analysis` - Document comprehension
- `socratic-method` - Guided discovery learning
- `meta-prompt` - Prompt engineering tools
- `task-specific` - Structured task workflows
- `reference` - Standards and guidelines

## Recent Updates

- **2025-11-22**: Enhanced structure with frontmatter, cross-references, and index
- **2025-10-16**: WebProject v1.1 - Added localStorage → REST API migration focus
- **2025-10-16**: Created learnReact v1.0 for React/TypeScript learning

## Contributing

When adding new prompts:
1. Follow the [Prompt_Template.mdx](./Meta-prompts/Prompt_Template.mdx) framework
2. Add complete frontmatter (see existing prompts for examples)
3. Include a "Related Prompts" section with cross-references
4. Update the [index.mdx](./index.mdx) catalog
5. Add an entry to this README

## Next Steps

Planning to add:
- Knowledge base articles in `Knowledge/` directory
- Version history tracking
- Usage examples for each prompt
- Static site generator integration for better navigation (considering Quartz or Typst)

---

**Built with:** Markdown/MDX | **Powered by:** Prompt Engineering Principles | **Made by:** Thomas