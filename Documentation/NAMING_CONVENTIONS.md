# Naming Conventions Guide

This document outlines the standard naming conventions used throughout the ICDF Academy Training Calendars Repository.

## General Principles

1. **Clarity**: Names should clearly describe the content
2. **Consistency**: Use the same format throughout the repository
3. **Simplicity**: Keep names concise but descriptive
4. **Readability**: Use underscores instead of spaces
5. **Uniqueness**: Avoid duplicate names within the same directory

## Directory Naming

### Schools
**Format:** `{School_Name_Full}`

**Rules:**
- Use full school name
- Replace spaces with underscores
- Use title case (capitalize first letter of each word)
- No special characters except underscores

**Examples:**
- `School_of_Advanced_Vocational_Training`
- `School_of_Professional_Development`
- `School_of_Executive_Training`

### Programs
**Format:** `{Program_Name_Full}`

**Rules:**
- Use full program name
- Replace spaces with underscores
- Use title case
- Include specialization if applicable

**Examples:**
- `Advanced_Cybercrime_Investigations`
- `Digital_Forensics_Specialization`
- `Network_Security_Bootcamp`
- `Cloud_Security_Professional`

### Cohorts
**Format:** `Batch_{YYYY}` or `Cohort_{Name}`

**Rules:**
- Use `Batch_` prefix for year-based cohorts
- Use `Cohort_` prefix for named cohorts
- Include year in YYYY format for batches
- Use descriptive names for named cohorts

**Examples:**
- `Batch_2024`
- `Batch_2025`
- `Batch_2026`
- `Cohort_Spring_2025`
- `Cohort_Advanced_Track`

### Phases
**Format:** `Phase_{Number}` or `Phase_{Name}`

**Rules:**
- Use `Phase_` prefix
- Use number (1, 2, 3, etc.) for sequential phases
- Use descriptive name for named phases
- Always capitalize Phase

**Examples:**
- `Phase_1`
- `Phase_2`
- `Phase_3`
- `Phase_Foundations`
- `Phase_Advanced`

### Subdirectories
**Format:** `{Category_Name}`

**Rules:**
- Use descriptive category names
- Replace spaces with underscores
- Use title case
- Keep names short but clear

**Examples:**
- `Course_Schedules`
- `Case_Studies`
- `Learning_Materials`
- `Assessments`
- `Resources`
- `Lecture_Notes`
- `Lab_Exercises`

## File Naming

### Training Calendars
**Format:** `{Phase}_Training_Calendar.md`

**Rules:**
- Include phase identifier
- Use "Training_Calendar" suffix
- Use .md extension

**Examples:**
- `Phase_1_Training_Calendar.md`
- `Phase_2_Training_Calendar.md`
- `Phase_3_Training_Calendar.md`

### Course Schedules
**Format:** `{CourseCode}_Course_Schedule.md`

**Rules:**
- Include course code (e.g., ACI901)
- Use "Course_Schedule" suffix
- Use .md extension

**Examples:**
- `ACI901_Course_Schedule.md`
- `ACI902_Course_Schedule.md`
- `ACI903_Course_Schedule.md`

### Case Studies
**Format:** `Case_Study_{Number}_{Title}.md`

**Rules:**
- Start with "Case_Study_"
- Include sequential number
- Include descriptive title
- Replace spaces in title with underscores
- Use .md extension

**Examples:**
- `Case_Study_1_E_Commerce_Data_Breach.md`
- `Case_Study_2_Insider_Threat.md`
- `Case_Study_3_Ransomware_Attack.md`
- `Case_Study_4_Phishing_Campaign.md`
- `Case_Study_5_Dark_Web_Marketplace.md`

### Learning Materials
**Format:** `{CourseCode}_{MaterialType}.md`

**Rules:**
- Include course code
- Include material type (Lecture_Notes, Lab_Exercises, etc.)
- Use .md extension

**Examples:**
- `ACI901_Lecture_Notes.md`
- `ACI902_Lab_Exercises.md`
- `ACI903_Reading_Materials.md`
- `ACI904_Project_Guidelines.md`

### Assessment Materials
**Format:** `{CourseCode}_{AssessmentType}.md`

**Rules:**
- Include course code
- Include assessment type (Quiz, Exam, Practical, etc.)
- Use .md extension

**Examples:**
- `ACI901_Practical_Exam.md`
- `ACI902_Quiz_1.md`
- `ACI903_Final_Assessment.md`
- `ACI904_Capstone_Requirements.md`

### README Files
**Format:** `README.md`

**Rules:**
- Always use exactly "README.md"
- Place in each directory level
- No version numbers in filename

**Location Examples:**
- `Schools/README.md`
- `Schools/School_Name/README.md`
- `Schools/School_Name/Program_Name/README.md`
- `Schools/School_Name/Program_Name/Batch_YYYY/README.md`
- `Schools/School_Name/Program_Name/Batch_YYYY/Phase_N/README.md`

### Documentation Files
**Format:** `{DocumentName}.md`

**Rules:**
- Use descriptive names
- Replace spaces with underscores
- Use title case
- Use .md extension

**Examples:**
- `STRUCTURE_GUIDE.md`
- `NAMING_CONVENTIONS.md`
- `CONTRIBUTING.md`
- `CHANGELOG.md`
- `LICENSE.md`

### Configuration Files
**Format:** `.{filename}`

**Rules:**
- Start with dot for hidden files
- Use lowercase
- No extension unless standard (e.g., .gitignore)

**Examples:**
- `.gitignore`
- `.github/`
- `.gitattributes`

## Special Characters

### Allowed Characters
- Letters (A-Z, a-z)
- Numbers (0-9)
- Underscores (_)
- Hyphens (-) - Use sparingly

### Forbidden Characters
- Spaces (use underscores instead)
- Periods (except for file extensions)
- Commas
- Semicolons
- Colons
- Quotes
- Slashes
- Backslashes
- Asterisks
- Question marks
- Angle brackets

## Case Conventions

### Directory Names
- **Use Title Case**: `School_of_Advanced_Vocational_Training`
- **Capitalize each word**: `Advanced_Cybercrime_Investigations`
- **Capitalize Phase/Batch**: `Phase_1`, `Batch_2025`

### File Names
- **Use Title Case for main words**: `Phase_1_Training_Calendar.md`
- **Use UPPERCASE for acronyms**: `ACI901_Course_Schedule.md`
- **Use lowercase for extensions**: `.md`, `.txt`, `.pdf`

### Markdown Headings
- **Use Title Case**: `# Phase 1 Training Calendar`
- **Use sentence case for subheadings**: `## Course overview`

## Version Numbering

### For Files with Versions
**Format:** `{FileName}_v{MajorVersion}.{MinorVersion}.md`

**Rules:**
- Use v prefix
- Use semantic versioning
- Include in filename only if multiple versions exist

**Examples:**
- `Phase_1_Training_Calendar_v1.0.md`
- `Phase_1_Training_Calendar_v1.1.md`
- `Phase_1_Training_Calendar_v2.0.md`

## Date Formats

### In File Content
**Format:** `YYYY-MM-DD` or `Month DD, YYYY`

**Rules:**
- Use ISO 8601 format for data (YYYY-MM-DD)
- Use readable format in documentation (Month DD, YYYY)
- Always include year

**Examples:**
- `2025-12-31` (ISO format)
- `December 31, 2025` (Readable format)

## Course Code Naming

### Format
**Format:** `{School_Prefix}{Program_Number}{Course_Number}`

**Rules:**
- School prefix (e.g., ACI for Advanced Cybercrime Investigations)
- Program number (e.g., 9 for Phase 2)
- Course number (e.g., 01, 02, 03, 04)

**Examples:**
- `ACI901` - Advanced Cybercrime Investigations, Phase 2, Course 1
- `ACI902` - Advanced Cybercrime Investigations, Phase 2, Course 2
- `ACI903` - Advanced Cybercrime Investigations, Phase 2, Course 3
- `ACI904` - Advanced Cybercrime Investigations, Phase 2, Course 4

## Common Mistakes to Avoid

| Incorrect | Correct | Reason |
|-----------|---------|--------|
| `Phase 1 Training Calendar.md` | `Phase_1_Training_Calendar.md` | Use underscores, not spaces |
| `phase_1_training_calendar.md` | `Phase_1_Training_Calendar.md` | Use title case for clarity |
| `ACI-901_Course_Schedule.md` | `ACI901_Course_Schedule.md` | No hyphens in course codes |
| `Case Study 1.md` | `Case_Study_1_Title.md` | Use underscores, include title |
| `Readme.md` | `README.md` | Use uppercase for README |
| `training calendar.md` | `Training_Calendar.md` | Capitalize each word |

## Examples of Complete Paths

### Phase 2 Training Calendar
```
Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/Batch_2025/Phase_2/Phase_2_Training_Calendar.md
```

### Case Study 1
```
Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/Batch_2025/Phase_2/Case_Studies/Case_Study_1_E_Commerce_Data_Breach.md
```

### Course Schedule
```
Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/Batch_2025/Phase_2/Course_Schedules/ACI901_Course_Schedule.md
```

### Learning Materials
```
Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/Batch_2025/Phase_2/Learning_Materials/ACI901_Lecture_Notes.md
```

## Checklist for New Files

Before creating a new file, verify:

- [ ] Name clearly describes content
- [ ] Follows appropriate naming format
- [ ] Uses underscores instead of spaces
- [ ] Uses title case for directories and main words
- [ ] Includes appropriate file extension
- [ ] Avoids special characters
- [ ] Doesn't duplicate existing files
- [ ] Fits within the repository hierarchy
- [ ] Is placed in the correct directory

## Questions?

For questions about naming conventions:
1. Check this document first
2. Review examples in the repository
3. Consult STRUCTURE_GUIDE.md for hierarchy
4. Ask the repository maintainer

---

**Last Updated:** December 31, 2025
