# Repository Structure Guide

This guide explains the hierarchical organization of the ICDF Academy Training Calendars Repository and how to navigate and maintain it.

## Hierarchy Levels

### Level 1: Schools

The top level organizes content by academic schools or divisions within ICDF Academy.

**Location:** `Schools/`

**Example:**
```
Schools/
├── School_of_Advanced_Vocational_Training/
├── School_of_Professional_Development/
└── School_of_Executive_Training/
```

**Directory Naming:** Use full school names with underscores replacing spaces.

### Level 2: Programs

Each school contains multiple training programs.

**Location:** `Schools/{SchoolName}/`

**Example:**
```
School_of_Advanced_Vocational_Training/
├── Advanced_Cybercrime_Investigations/
├── Digital_Forensics_Specialization/
└── Network_Security_Bootcamp/
```

**Directory Naming:** Use descriptive program names with underscores replacing spaces.

### Level 3: Cohorts

Each program is organized by cohorts (batches of students) typically identified by year.

**Location:** `Schools/{SchoolName}/{ProgramName}/`

**Example:**
```
Advanced_Cybercrime_Investigations/
├── Batch_2024/
├── Batch_2025/
└── Batch_2026/
```

**Directory Naming:** Use format `Batch_{YYYY}` for year-based cohorts, or `Cohort_{Name}` for named cohorts.

### Level 4: Phases

Each cohort is divided into training phases.

**Location:** `Schools/{SchoolName}/{ProgramName}/{CohortName}/`

**Example:**
```
Batch_2025/
├── Phase_1/
├── Phase_2/
└── Phase_3/
```

**Directory Naming:** Use format `Phase_{Number}` for numbered phases.

## File Organization Within Each Phase

### Phase Directory Structure

```
Phase_2/
├── README.md                          # Phase overview and navigation
├── Phase_2_Training_Calendar.md       # Main training calendar
├── Course_Schedules/
│   ├── ACI901_Course_Schedule.md
│   ├── ACI902_Course_Schedule.md
│   ├── ACI903_Course_Schedule.md
│   └── ACI904_Course_Schedule.md
├── Case_Studies/
│   ├── Case_Study_1_E_Commerce_Data_Breach.md
│   ├── Case_Study_2_Insider_Threat.md
│   ├── Case_Study_3_Ransomware_Attack.md
│   ├── Case_Study_4_Phishing_Campaign.md
│   └── Case_Study_5_Dark_Web_Marketplace.md
├── Learning_Materials/
│   ├── Course_1_Materials/
│   ├── Course_2_Materials/
│   ├── Course_3_Materials/
│   └── Course_4_Materials/
├── Assessments/
│   ├── Quizzes/
│   ├── Practical_Exams/
│   └── Capstone_Requirements.md
└── Resources/
    ├── Tools_and_Software.md
    ├── Reference_Materials.md
    └── External_Links.md
```

## README Files at Each Level

Each level should include a README.md file providing:

### School Level README
- School name and description
- List of programs offered
- Navigation links to programs
- Contact information

### Program Level README
- Program name and description
- Program objectives and outcomes
- List of cohorts
- Navigation links to cohorts
- Program coordinator information

### Cohort Level README
- Cohort name and year
- Enrollment information
- List of phases
- Navigation links to phases
- Cohort timeline

### Phase Level README
- Phase name and number
- Phase duration and dates
- List of courses
- Navigation links to courses
- Phase objectives and outcomes

## File Naming Conventions

### Training Calendars
- Format: `{Phase}_Training_Calendar.md`
- Example: `Phase_1_Training_Calendar.md`, `Phase_2_Training_Calendar.md`

### Course Schedules
- Format: `{CourseCode}_Course_Schedule.md`
- Example: `ACI901_Course_Schedule.md`

### Case Studies
- Format: `Case_Study_{Number}_{Title}.md`
- Example: `Case_Study_1_E_Commerce_Data_Breach.md`

### Learning Materials
- Format: `{CourseCode}_{MaterialType}.md`
- Example: `ACI901_Lecture_Notes.md`, `ACI902_Lab_Exercises.md`

### General Rules
- Use underscores for spaces: `Training_Calendar` not `Training Calendar`
- Use descriptive names that clearly indicate content
- Include course codes or numbers when applicable
- Avoid special characters except underscores and hyphens
- Use `.md` extension for all Markdown documents

## Adding New Content

### Adding a New School

1. Create directory under `Schools/`
   ```bash
   mkdir -p Schools/New_School_Name
   ```

2. Create README.md
   ```bash
   touch Schools/New_School_Name/README.md
   ```

3. Update parent README with link to new school

### Adding a New Program

1. Create directory under school
   ```bash
   mkdir -p Schools/School_Name/New_Program_Name
   ```

2. Create README.md
   ```bash
   touch Schools/School_Name/New_Program_Name/README.md
   ```

3. Update parent README with link to new program

### Adding a New Cohort

1. Create directory under program
   ```bash
   mkdir -p Schools/School_Name/Program_Name/Batch_YYYY
   ```

2. Create Phase directories
   ```bash
   mkdir -p Schools/School_Name/Program_Name/Batch_YYYY/Phase_1
   mkdir -p Schools/School_Name/Program_Name/Batch_YYYY/Phase_2
   ```

3. Create README.md files at each level

### Adding a New Phase

1. Create directory under cohort
   ```bash
   mkdir -p Schools/School_Name/Program_Name/Batch_YYYY/Phase_N
   ```

2. Create subdirectories for organization
   ```bash
   mkdir -p Phase_N/Course_Schedules
   mkdir -p Phase_N/Case_Studies
   mkdir -p Phase_N/Learning_Materials
   mkdir -p Phase_N/Assessments
   mkdir -p Phase_N/Resources
   ```

3. Create README.md and training calendar

## Best Practices

### Documentation
- Keep README files concise but informative
- Use clear headings and subheadings
- Include navigation links to related content
- Update version information regularly

### Organization
- Maintain consistent directory naming
- Keep related files together
- Avoid deeply nested structures beyond 4 levels
- Use descriptive folder names

### Version Control
- Commit changes with clear, descriptive messages
- Include date and author information
- Maintain a changelog for significant updates
- Tag releases with version numbers

### Maintenance
- Review and update calendars regularly
- Remove outdated materials
- Archive completed cohorts
- Keep documentation current

## Examples

### Complete Path to Phase 2 Training Calendar
```
Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/Batch_2025/Phase_2/Phase_2_Training_Calendar.md
```

### Complete Path to Case Study
```
Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/Batch_2025/Phase_2/Case_Studies/Case_Study_1_E_Commerce_Data_Breach.md
```

### Complete Path to Course Schedule
```
Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/Batch_2025/Phase_2/Course_Schedules/ACI901_Course_Schedule.md
```

## Troubleshooting

### Cannot find a file
- Check spelling of directory and file names
- Verify you're in the correct school/program/cohort
- Use the navigation links in README files

### Directory structure looks wrong
- Refer to the hierarchy diagram above
- Ensure you're following the 4-level structure
- Check that naming conventions are consistent

### Need to reorganize content
- Create new directories first
- Move files carefully
- Update all navigation links
- Commit changes with clear messages

## Support

For questions about repository structure, refer to:
- Main README.md for overview
- NAMING_CONVENTIONS.md for naming standards
- CONTRIBUTING.md for contribution guidelines

---

**Last Updated:** December 31, 2025
