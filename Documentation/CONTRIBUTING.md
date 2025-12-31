# Contributing to ICDF Academy Training Calendars Repository

Thank you for your interest in contributing to the ICDF Academy Training Calendars Repository. This document provides guidelines for contributing to the repository in a way that maintains quality, consistency, and organization.

## Getting Started

### Prerequisites
- GitHub account with access to the repository
- Git installed on your local machine
- Familiarity with Markdown format
- Understanding of the repository structure (see STRUCTURE_GUIDE.md)

### Setting Up Your Local Environment

Clone the repository to your local machine:

```bash
gh repo clone icdf-academy/icdf-training-calendars
cd icdf-training-calendars
```

Create a new branch for your changes:

```bash
git checkout -b feature/your-feature-name
```

## Types of Contributions

### 1. Adding New Training Calendars

When adding a new training calendar for a new phase or cohort:

1. Create the appropriate directory structure following STRUCTURE_GUIDE.md
2. Create a comprehensive training calendar document following the template
3. Include course schedules and learning outcomes
4. Add case studies if applicable
5. Create a README.md for the new phase
6. Update parent README files with links to the new content

### 2. Updating Existing Calendars

When updating an existing training calendar:

1. Review the current calendar for accuracy
2. Make necessary changes or corrections
3. Update version numbers if making significant changes
4. Add notes about what was changed and why
5. Update the "Last Updated" date
6. Commit with a clear message describing the changes

### 3. Adding Case Studies

When adding new case studies:

1. Follow the Case_Study_{Number}_{Title}.md naming format
2. Include a clear scenario description
3. Outline the investigation focus areas
4. List the skills and techniques to be applied
5. Provide learning outcomes
6. Place in the Case_Studies subdirectory

### 4. Adding Learning Materials

When adding course materials, lecture notes, or lab exercises:

1. Follow the {CourseCode}_{MaterialType}.md naming format
2. Organize content logically with clear headings
3. Include learning objectives at the beginning
4. Provide step-by-step instructions for practical materials
5. Add references and resources
6. Place in the appropriate subdirectory

### 5. Improving Documentation

When improving documentation:

1. Update relevant .md files in the Documentation folder
2. Ensure clarity and accuracy
3. Add examples where helpful
4. Update version information
5. Maintain consistency with existing documentation

## Workflow

### Step 1: Create a Feature Branch

Create a descriptive branch name for your contribution:

```bash
git checkout -b feature/add-phase-3-calendar
git checkout -b feature/update-batch-2025-phase-2
git checkout -b feature/add-case-study-6
```

### Step 2: Make Your Changes

Make your changes following the guidelines in this document:

1. Create or modify files as needed
2. Follow naming conventions (see NAMING_CONVENTIONS.md)
3. Follow the directory structure (see STRUCTURE_GUIDE.md)
4. Ensure all files are in Markdown format (.md)
5. Update README files with links to new content

### Step 3: Verify Your Changes

Before committing, verify:

- [ ] All files follow naming conventions
- [ ] Directory structure is correct
- [ ] All Markdown is properly formatted
- [ ] Links to other files work correctly
- [ ] README files are updated with navigation links
- [ ] No sensitive information is included
- [ ] Files are properly organized

### Step 4: Commit Your Changes

Commit with clear, descriptive messages:

```bash
git add .
git commit -m "Add Phase 2 training calendar for Batch 2025"
git commit -m "Update course schedules for ACI901-ACI904"
git commit -m "Add 5 case studies for Phase 2"
```

Use the following format for commit messages:
- Start with a verb: Add, Update, Fix, Improve, etc.
- Be specific about what was changed
- Keep the message concise (50 characters or less)
- Use present tense

### Step 5: Push to GitHub

Push your branch to the remote repository:

```bash
git push origin feature/your-feature-name
```

### Step 6: Create a Pull Request

1. Go to the GitHub repository
2. Click "New Pull Request"
3. Select your feature branch
4. Provide a clear title and description
5. Reference any related issues
6. Request review from repository maintainers
7. Wait for feedback and approval

### Step 7: Address Feedback

If reviewers request changes:

1. Make the requested modifications
2. Commit the changes
3. Push to your branch
4. The pull request will automatically update

### Step 8: Merge

Once approved, a repository maintainer will merge your pull request.

## Content Guidelines

### Training Calendar Format

All training calendars should include:

1. **Header** with academy name, school, program, and batch information
2. **Executive Summary** providing an overview of the phase
3. **Training Schedule** with dates, course codes, and descriptions
4. **Course Details** for each course including:
   - Course code and name
   - Duration and dates
   - Unit credits
   - Exam type
   - Course overview
   - Learning outcomes
5. **Case Studies** (if applicable) with scenarios and investigation focus
6. **Program Structure Summary** in table format
7. **Assessment Information**
8. **Footer** with version and update information

### Markdown Formatting

Use proper Markdown formatting:

```markdown
# Main Heading (H1)
## Section Heading (H2)
### Subsection Heading (H3)

**Bold text** for emphasis
*Italic text* for secondary emphasis

- Bullet points for lists
1. Numbered lists for sequences

| Column 1 | Column 2 |
|----------|----------|
| Data 1   | Data 2   |

[Link text](URL)

> Blockquotes for important information
```

### Content Quality

Ensure all content:

- Is accurate and up-to-date
- Is clearly written and easy to understand
- Follows professional standards
- Includes relevant examples
- Provides clear learning outcomes
- Is organized logically
- Includes proper citations and references

## Style Guidelines

### Writing Style

- Use professional, formal language
- Write in complete sentences and paragraphs
- Avoid jargon unless necessary; define technical terms
- Be concise but comprehensive
- Use active voice when possible
- Maintain consistency with existing documentation

### Formatting Style

- Use consistent heading levels
- Use tables to organize information
- Use bold for emphasis on key terms
- Use blockquotes for definitions or important statements
- Keep line lengths reasonable (under 100 characters)
- Use proper spacing between sections

### Code and Examples

- Use code blocks for commands and code snippets
- Include syntax highlighting when applicable
- Provide clear explanations of examples
- Test code examples before submitting

## Common Contributions

### Adding a New Batch

To add a new batch (e.g., Batch 2026):

1. Create the directory structure:
   ```bash
   mkdir -p Schools/School_Name/Program_Name/Batch_2026/Phase_1
   mkdir -p Schools/School_Name/Program_Name/Batch_2026/Phase_2
   ```

2. Create README files at each level

3. Copy and adapt training calendars from previous batch

4. Update all parent README files with links

5. Commit with message: "Add Batch 2026 training calendars"

### Adding a New Program

To add a new program:

1. Create the directory structure:
   ```bash
   mkdir -p Schools/School_Name/New_Program_Name/Batch_YYYY/Phase_1
   mkdir -p Schools/School_Name/New_Program_Name/Batch_YYYY/Phase_2
   ```

2. Create comprehensive README files

3. Create training calendars for each phase

4. Add course schedules and materials

5. Update school-level README with link to new program

6. Commit with message: "Add New_Program_Name to School_Name"

### Adding a New School

To add a new school:

1. Create the directory structure:
   ```bash
   mkdir -p Schools/New_School_Name/Program_Name/Batch_YYYY/Phase_1
   ```

2. Create comprehensive README at school level

3. Add programs and training calendars

4. Update main repository README with link to new school

5. Commit with message: "Add New_School_Name to repository"

## Review Process

All contributions go through a review process:

1. **Automated Checks**: GitHub Actions verify file structure and naming conventions
2. **Manual Review**: Repository maintainers review content for accuracy and quality
3. **Feedback**: Reviewers may request changes or clarifications
4. **Approval**: Once approved, contributions are merged

## Conflict Resolution

If your changes conflict with other changes:

1. Pull the latest version: `git pull origin main`
2. Resolve conflicts in your files
3. Commit the resolved changes
4. Push to your branch
5. The pull request will update automatically

## Questions and Support

For questions about contributing:

1. Check this document and related guides
2. Review existing contributions for examples
3. Ask in the pull request comments
4. Contact the repository maintainer

## Code of Conduct

All contributors are expected to:

- Be respectful and professional
- Provide constructive feedback
- Follow the guidelines in this document
- Maintain the quality and integrity of the repository
- Respect the intellectual property of the academy

## Recognition

Contributors who make significant contributions will be recognized in:

- The repository's CONTRIBUTORS.md file
- Commit history
- Release notes for major updates

## License

By contributing to this repository, you agree that your contributions are licensed under the same license as the repository (as specified in the LICENSE file).

---

**Last Updated:** December 31, 2025

For more information, see:
- [STRUCTURE_GUIDE.md](STRUCTURE_GUIDE.md) - Repository structure
- [NAMING_CONVENTIONS.md](NAMING_CONVENTIONS.md) - Naming standards
- [README.md](../README.md) - Repository overview
