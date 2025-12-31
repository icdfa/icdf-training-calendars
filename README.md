# ICDF Academy Training Calendars Repository

Welcome to the official repository for the **International Cybersecurity and Digital Forensic Academy (ICDF Academy)** training calendars. This repository serves as a centralized hub for all training schedules, course calendars, and program timelines across all schools, programs, and cohorts.

## Repository Overview

This repository is organized in a hierarchical structure to facilitate easy navigation and access to training calendars for different schools, programs, cohorts, and phases. All training materials are professionally documented and version-controlled for consistency and accountability.

## Repository Structure

The repository follows a category-based organization system:

```
icdf-training-calendars/
├── Schools/
│   ├── School_of_Basic_Vocational_Training/
│   ├── School_of_Internship_Training/
│   ├── School_of_Advanced_Vocational_Training/
│   ├── School_of_Professional_Development/
│   └── School_of_Cyber_Risk_Governance_and_Compliance/
├── Documentation/
│   ├── CONTRIBUTING.md
│   ├── STRUCTURE_GUIDE.md
│   └── NAMING_CONVENTIONS.md
├── README.md (This file)
├── .gitignore
└── LICENSE
```

## Schools and Programs

### School of Basic Vocational Training (SBVT)

The School of Basic Vocational Training provides foundational training programs for entry-level cybersecurity professionals.

**Programs:**
- **[Fellowship in Web Application Security and Digital Forensics](Schools/School_of_Basic_Vocational_Training/Fellowship_in_Web_Application_Security_and_Digital_Forensics/)**
  - Web application security assessment
  - Digital forensics fundamentals
  - Incident response procedures

[View School Details](Schools/School_of_Basic_Vocational_Training/)

### School of Internship Training (SIT)

The School of Internship Training provides immersive internship programs combining theoretical knowledge with practical experience.

**Programs:**
- **[Ethical Hacking and Digital Forensics Internship](Schools/School_of_Internship_Training/Ethical_Hacking_and_Digital_Forensics_Internship/)**
  - Ethical hacking methodologies
  - Penetration testing techniques
  - Digital forensics investigation

[View School Details](Schools/School_of_Internship_Training/)

### School of Advanced Vocational Training (SAVT)

The School of Advanced Vocational Training offers advanced programs in specialized cybersecurity domains.

**Programs:**
- **[Advanced SOC Analyst](Schools/School_of_Advanced_Vocational_Training/Advanced_SOC_Analyst/)**
  - SOC operations and management
  - Threat detection and analysis
  - Incident response procedures

- **[Advanced Cybercrime Investigations](Schools/School_of_Advanced_Vocational_Training/Advanced_Cybercrime_Investigations/)**
  - Cybercrime investigation techniques
  - Digital forensics and evidence analysis
  - Legal and ethical frameworks
  - Real-world case studies

- **[Advanced Cybersecurity Operations and Threat Intelligence](Schools/School_of_Advanced_Vocational_Training/Advanced_Cybersecurity_Operations_and_Threat_Intelligence/)**
  - Cybersecurity operations management
  - Threat intelligence collection and analysis
  - Advanced threat hunting

[View School Details](Schools/School_of_Advanced_Vocational_Training/)

### School of Professional Development (SPD)

The School of Professional Development offers certification programs for career advancement in cybersecurity.

**Programs:**
- **[Certified Cybersecurity Instructor (CCI) Programme](Schools/School_of_Professional_Development/Certified_Cybersecurity_Instructor_Programme/)**
  - Instructional design and curriculum development
  - Teaching methodologies for cybersecurity
  - Assessment and evaluation techniques

- **[Certified Cybersecurity Consultant](Schools/School_of_Professional_Development/Certified_Cybersecurity_Consultant/)**
  - Security consulting methodologies
  - Risk assessment and management
  - Compliance and regulatory consulting

[View School Details](Schools/School_of_Professional_Development/)

### School of Cyber Risk, Governance and Compliance (SCRGC)

The School of Cyber Risk, Governance and Compliance provides specialized training in GRC frameworks and practices.

**Programs:**
- **[GRC Engineering (CGRCE)](Schools/School_of_Cyber_Risk_Governance_and_Compliance/GRC_Engineering/)**
  - GRC framework design and implementation
  - Risk assessment and management
  - Compliance with cybersecurity regulations
  - Policy development and governance

[View School Details](Schools/School_of_Cyber_Risk_Governance_and_Compliance/)

## Quick Navigation by School

| School | Programs | Status |
|---|---|---|
| [School of Basic Vocational Training](Schools/School_of_Basic_Vocational_Training/) | Fellowship in Web Application Security and Digital Forensics | Active |
| [School of Internship Training](Schools/School_of_Internship_Training/) | Ethical Hacking and Digital Forensics Internship | Active |
| [School of Advanced Vocational Training](Schools/School_of_Advanced_Vocational_Training/) | Advanced SOC Analyst, Advanced Cybercrime Investigations, Advanced Cybersecurity Operations and Threat Intelligence | Active |
| [School of Professional Development](Schools/School_of_Professional_Development/) | Certified Cybersecurity Instructor (CCI), Certified Cybersecurity Consultant | Active |
| [School of Cyber Risk, Governance and Compliance](Schools/School_of_Cyber_Risk_Governance_and_Compliance/) | GRC Engineering (CGRCE) | Active |

## Key Features

### Hierarchical Organization
The repository is organized by:
1. **School** - The academic school or division
2. **Program** - The specific training program
3. **Cohort** - The batch or cohort of students
4. **Phase** - The training phase (Phase 1, Phase 2, etc.)

### Comprehensive Documentation
Each level includes:
- README files with overview and navigation
- Training calendars with detailed course information
- Course descriptions and learning outcomes
- Case studies and practical exercises
- Resource links and references

### Version Control
All training calendars are version-controlled to track:
- Updates and revisions
- Changes to course schedules
- Modifications to program structure
- Historical records for audit purposes

## How to Use This Repository

### For Students
1. Navigate to your school and program
2. Find your cohort (batch year)
3. Access your phase training calendar
4. Review course schedules and case studies
5. Download resources and materials

### For Instructors
1. Locate your program and cohort
2. Access the training calendar for your phase
3. Review course materials and case studies
4. Update schedules as needed
5. Commit changes with clear messages

### For Administrators
1. Monitor all training calendars across schools
2. Ensure consistency in naming and structure
3. Approve updates and new programs
4. Maintain version history
5. Generate reports from calendar data

## File Naming Conventions

All files follow consistent naming conventions:
- Use underscores for spaces: `Phase_1_Training_Calendar.md`
- Use descriptive names: `Case_Study_1_E_Commerce_Data_Breach.md`
- Include version numbers when applicable: `v1.0`, `v2.0`
- Use `.md` extension for Markdown documents

## Contributing

To contribute to this repository:

1. **Clone the repository**
   ```bash
   gh repo clone icdfa/icdf-training-calendars
   ```

2. **Create a new branch**
   ```bash
   git checkout -b feature/new-program-calendar
   ```

3. **Make your changes**
   - Add or update training calendars
   - Follow the directory structure
   - Use consistent naming conventions

4. **Commit your changes**
   ```bash
   git commit -m "Add Phase 2 training calendar for Batch 2025"
   ```

5. **Push to GitHub**
   ```bash
   git push origin feature/new-program-calendar
   ```

6. **Create a Pull Request**
   - Provide clear description of changes
   - Reference any related issues
   - Wait for review and approval

## Documentation Files

- **[STRUCTURE_GUIDE.md](Documentation/STRUCTURE_GUIDE.md)** - Detailed guide to repository structure
- **[NAMING_CONVENTIONS.md](Documentation/NAMING_CONVENTIONS.md)** - File and folder naming standards
- **[CONTRIBUTING.md](Documentation/CONTRIBUTING.md)** - Contribution guidelines

## All Programs Summary

| School | Program | Batch | Phases | Status |
|---|---|---|---|---|
| SBVT | Fellowship in Web Application Security and Digital Forensics | 2025 | 1, 2 | Active |
| SIT | Ethical Hacking and Digital Forensics Internship | 2025 | 1, 2 | Active |
| SAVT | Advanced SOC Analyst | 2025 | 1, 2 | Active |
| SAVT | Advanced Cybercrime Investigations | 2025 | 1, 2 | Active |
| SAVT | Advanced Cybersecurity Operations and Threat Intelligence | 2025 | 1, 2 | Active |
| SPD | Certified Cybersecurity Instructor (CCI) Programme | 2025 | 1, 2 | Active |
| SPD | Certified Cybersecurity Consultant | 2025 | 1, 2 | Active |
| SCRGC | GRC Engineering (CGRCE) | 2025 | 1, 2 | Active |

## Adding New Programs

To add a new program or cohort:

1. Create the directory structure following the hierarchy
2. Add a README.md at each level
3. Include training calendars in Markdown format
4. Add relevant case studies and resources
5. Update parent README files with links
6. Submit a pull request for review

## Support and Questions

For questions about:
- **Repository structure**: See [STRUCTURE_GUIDE.md](Documentation/STRUCTURE_GUIDE.md)
- **Naming conventions**: See [NAMING_CONVENTIONS.md](Documentation/NAMING_CONVENTIONS.md)
- **Contributing**: See [CONTRIBUTING.md](Documentation/CONTRIBUTING.md)
- **Specific programs**: Contact the respective school or program coordinator

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | December 31, 2025 | Initial repository creation with Batch 2025 Phase 1 and Phase 2 calendars |
| 1.1 | December 31, 2025 | Added all 5 schools and 8 programs with complete structure |

## License

This repository is maintained by the International Cybersecurity and Digital Forensic Academy. All training calendars and materials are proprietary and for authorized use only.

## Academy Information

**International Cybersecurity and Digital Forensic Academy (ICDF Academy)**  
School of Advanced Training  

For inquiries, please contact the academy administration.

---

**Last Updated:** December 31, 2025  
**Repository Maintainer:** ICDF Academy Administration  
**Status:** Active
