# Movie Theater Ticketing System – Software Design Specification

This repository contains our group project for the Software Engineering course.  
We are incrementally building a **Software Requirements Specification (SRS)** for a **Movie Theater Ticketing System**.  

## Project Overview

The system allows users to:  
- Purchase tickets online with seat selection.  
- Cancel or reschedule tickets (subject to refund policy).  
- Receive digital tickets with a scannable entry code.  
- Managers can schedule screenings and configure auditoriums.  
- Secure payments are processed via an external provider.  

## Deliverable 2: Software Design Specification

This deliverable extends our initial Requirements Spec with:  
- **Software Architecture Diagram** (components & connectors).  
- **UML Class Diagram** (Screening, Auditorium, Seat, Order, Ticket, Payment, User Roles, Policy Values).  
- **Detailed class descriptions** (attributes with datatypes, methods with signatures).  
- **Development Plan & Timeline** (task distribution, responsibilities, schedule).  

## Repository Structure

```
/Architecture
  └── Data Management Strategy.docx  # Plan for Data Management Strategy section of SRS
/docs
  └── SRS_v1.docx        # Deliverable 1: Requirements Specification
/design
  ├── UpdatedClassUML.png        # UML Diagram updated to current specs
  ├── Updated_Arc_Diagram.png    # ARC Diagram updated to current specs
  ├── architecture.png   # Software Architecture Diagram
  ├── uml_class.png      # UML Class Diagram
  └── sources/           # Editable diagram files (e.g., .drawio, .uml) - missing
/deliverables
  ├── SRS_v2.docx          # SRS Design v2
  ├── SRS_v2.2.docx        # SRS Design v2.2
  ├── SRS_v2.3.docx        # SRS Revision History v3.1
  ├── SRS_v2.4.docx        # SRS Revision History v3.2
  └── SRS_v3.3.docx        # SRS Current Design for Submission (Numbering updated to reflect document Revision History)
/testplan
  ├── SRS_v2.3.docx       # SRS RH v3.1 add Test Plan section
  ├── SRS_v2.4.docx       # SRS RH v3.2 update diagrams
  ├── TestPlan_Assignment3.docx     # Plans for Test Plan section of SRS
  └── testCases.xlsx      # List of test cases for the Test Plan
```

## Team Responsibilities

For each assignment, tasks are redistributed among team members and completed collaboratively.  
Roles may change per deliverable, but all contributions are merged into a single master SRS document.  

⚠️ Each member must push **at least one commit** to the repository to receive credit.  

---
