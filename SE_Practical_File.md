# Software Engineering Practical File

**Name:** ___________________________
**Roll No.:** _______________________
**Course:** BCA
**Institute:** Sri Sukhmani Institute of Hospitality and Management
**Subject:** Software Engineering
**Session:** 2024–2025

---

---

## Assignment 1

### Identify Project Scope and Objectives

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To identify and define the **project scope** and **objectives** for:

- a) College Automation System
- b) Banking Management System

---

### 2. Theory

**Project Scope** defines the boundaries of a project — what will be included and what will NOT be included. It sets clear expectations among all stakeholders.

**Project Objectives** are specific goals that the project aims to achieve. They answer the question: *"What should the system do?"*

**Why is it important?**

- Prevents scope creep (uncontrolled changes)
- Helps in resource planning
- Gives direction to the development team

**Key elements of scope definition:**

| Element | Meaning |
|---|---|
| Deliverables | What will be produced |
| Boundaries | What is in/out of scope |
| Constraints | Limitations (time, budget) |
| Assumptions | Things taken for granted |

---

### 3. Steps / Methodology

1. Identify all **stakeholders** (users, managers, developers)
2. Gather requirements through **interviews and surveys**
3. Define **what the system will do** (functional scope)
4. Define **what the system will NOT do** (exclusions)
5. Write **measurable objectives**
6. Get approval from stakeholders

---

### 4. Diagram / Representation

```
┌─────────────────────────────────────────────────┐
│              PROJECT SCOPE BOUNDARY              │
│                                                  │
│   ┌──────────────┐      ┌──────────────────┐    │
│   │  Stakeholders│─────▶│   System Goals   │    │
│   └──────────────┘      └──────────────────┘    │
│                                  │               │
│                     ┌────────────▼────────────┐  │
│                     │   In-Scope Features     │  │
│                     └─────────────────────────┘  │
│                                                  │
│   ╔══════════════════════════════════════╗       │
│   ║     Out-of-Scope (Exclusions)        ║       │
│   ╚══════════════════════════════════════╝       │
└─────────────────────────────────────────────────┘
```

---

### 5. Example / Solution

#### a) College Automation System

**Project Scope:**

- **In Scope:**
  - Student admission and registration
  - Attendance management
  - Examination and result management
  - Fee payment and receipt generation
  - Library management
  - Staff/faculty records

- **Out of Scope:**
  - Online learning/LMS features
  - Hostel management (separate system)
  - Alumni portal

**Project Objectives:**

1. Automate student admission process to reduce manual effort by 80%
2. Maintain accurate attendance records for all students
3. Generate exam results and mark sheets automatically
4. Provide a fee management system with online payment support
5. Reduce paperwork and improve data accuracy

---

#### b) Banking Management System

**Project Scope:**

- **In Scope:**
  - Account creation and management
  - Deposit and withdrawal transactions
  - Fund transfers (within bank)
  - Loan application and tracking
  - Statement generation
  - User login and authentication

- **Out of Scope:**
  - Inter-bank transfers (requires separate integration)
  - Investment and insurance services
  - Mobile app development (phase 2)

**Project Objectives:**

1. Enable customers to manage accounts securely
2. Process financial transactions with 99.9% accuracy
3. Provide real-time balance and statement information
4. Maintain audit logs for all transactions
5. Support concurrent users without performance degradation

---

### 6. Output / Result

**Result:** The project scope and objectives for both the College Automation System and Banking Management System have been clearly identified. This provides a solid foundation for further software development phases, helping the team stay focused on defined goals and avoid scope creep.

---
---

## Assignment 2

### Develop Software Requirement Specification (SRS)

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To develop a complete **Software Requirement Specification (SRS)** document for the College Automation System and Banking Management System.

---

### 2. Theory

**SRS (Software Requirement Specification)** is a formal document that describes what a software system should do. It acts as a contract between the client and the development team.

**IEEE 830 Standard** is commonly followed for writing SRS.

**Types of Requirements:**

| Type | Description | Example |
|---|---|---|
| Functional | What the system does | Login, Add Student |
| Non-Functional | How the system performs | Speed, Security |
| Interface | How system connects to external things | Web browser, Database |

**Characteristics of good SRS:**
- Complete
- Consistent
- Unambiguous
- Verifiable
- Traceable

---

### 3. Steps / Methodology

1. **Introduction** — Purpose, scope, and definitions
2. **Overall Description** — System context and constraints
3. **Functional Requirements** — List all features
4. **Non-Functional Requirements** — Performance, security, etc.
5. **External Interface Requirements** — UI, hardware, software
6. **Review and Approval** — Validate with stakeholders

---

### 4. Diagram / Representation

**SRS Document Structure:**

```
SRS Document
├── 1. Introduction
│    ├── 1.1 Purpose
│    ├── 1.2 Scope
│    └── 1.3 Definitions
├── 2. Overall Description
│    ├── 2.1 Product Perspective
│    └── 2.2 Assumptions & Dependencies
├── 3. Functional Requirements
│    ├── FR-01: Login
│    ├── FR-02: Register
│    └── FR-03: ...
├── 4. Non-Functional Requirements
│    ├── Performance
│    ├── Security
│    └── Availability
└── 5. Interface Requirements
     ├── User Interface
     └── Hardware Interface
```

---

### 5. Example / Solution

---

#### a) SRS for College Automation System

**1. Introduction**

- **Purpose:** This SRS describes the requirements for a College Automation System (CAS) that automates admission, attendance, examination, fees, and library management.
- **Scope:** The system will be used by students, faculty, and administrative staff of the college.
- **Definitions:**
  - *Admin:* College administrative staff
  - *Faculty:* Teaching staff
  - *Student:* Enrolled learner

**2. Overall Description**

- The CAS will replace manual paper-based processes.
- It will run on a web browser and store data in a relational database.
- Assumption: All users have access to a computer/laptop with internet.

**3. Functional Requirements**

| FR ID | Requirement |
|---|---|
| FR-01 | Admin shall be able to add/edit/delete student records |
| FR-02 | Faculty shall be able to mark daily attendance |
| FR-03 | System shall generate automatic report cards after exam |
| FR-04 | Student shall be able to view fee dues and pay online |
| FR-05 | Library system shall issue/return books and show availability |
| FR-06 | System shall send SMS/email notifications for fee dues |

**4. Non-Functional Requirements**

| NFR ID | Requirement |
|---|---|
| NFR-01 | System response time shall be < 3 seconds |
| NFR-02 | System shall be available 99% of the time |
| NFR-03 | All passwords shall be stored in encrypted form |
| NFR-04 | System shall support up to 1000 concurrent users |
| NFR-05 | System shall work on Chrome, Firefox, and Edge browsers |

**5. Interface Requirements**

- **User Interface:** Web-based, responsive design
- **Hardware:** Minimum 4GB RAM server, 100 Mbps network
- **Software:** PHP/Python backend, MySQL database, Apache web server

---

#### b) SRS for Banking Management System

**1. Introduction**

- **Purpose:** This SRS describes requirements for a Banking Management System (BMS) that handles account management, transactions, and loan processing.
- **Scope:** Used by bank customers, tellers, and managers.
- **Definitions:**
  - *Account Holder:* Customer with a bank account
  - *Teller:* Bank employee handling transactions
  - *Transaction:* Any deposit, withdrawal, or transfer

**2. Overall Description**

- BMS will replace manual ledger-based banking operations.
- The system will run 24/7 with high availability.
- Assumption: Secure internet connection is available at all branches.

**3. Functional Requirements**

| FR ID | Requirement |
|---|---|
| FR-01 | Customer shall be able to create a new account |
| FR-02 | System shall allow deposit and withdrawal of funds |
| FR-03 | Customer shall be able to transfer funds between accounts |
| FR-04 | System shall generate monthly bank statements |
| FR-05 | Manager shall be able to approve/reject loan applications |
| FR-06 | System shall send OTP for transaction verification |

**4. Non-Functional Requirements**

| NFR ID | Requirement |
|---|---|
| NFR-01 | All transactions shall complete within 2 seconds |
| NFR-02 | System shall maintain 99.99% uptime |
| NFR-03 | Data shall be encrypted using AES-256 |
| NFR-04 | System shall support 5000 concurrent users |
| NFR-05 | Audit log shall be maintained for all transactions |

**5. Interface Requirements**

- **User Interface:** Web portal + Mobile app (Android/iOS)
- **Hardware:** Dedicated servers with RAID storage, 1 Gbps network
- **Software:** Java/Spring Boot backend, Oracle Database

---

### 6. Output / Result

**Result:** Complete SRS documents for both systems have been developed. These documents clearly specify what the systems must do (functional) and how well they must perform (non-functional), providing a clear blueprint for developers and a reference for testing.

---
---

## Assignment 3

### Develop UML Use Case Model

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To develop **UML Use Case Diagrams** for the College Automation System and Banking Management System.

---

### 2. Theory

A **Use Case Diagram** is a UML (Unified Modeling Language) diagram that shows the interaction between **actors** (users/external systems) and **use cases** (system functionalities).

**Key Components:**

| Symbol | Represents | Shape |
|---|---|---|
| Actor | User or external system | Stick figure |
| Use Case | System function | Oval/Ellipse |
| Association | Link between actor and use case | Solid line |
| System Boundary | Scope of the system | Rectangle box |
| `<<include>>` | Mandatory sub-function | Dashed arrow |
| `<<extend>>` | Optional extra behavior | Dashed arrow |

**Why Use Case Diagrams?**

- Easy to understand for both technical and non-technical people
- Shows what the system does from user's perspective
- Helps identify all system functionalities

---

### 3. Steps / Methodology

1. Identify all **actors** (who interacts with the system)
2. Identify all **use cases** (what the system does)
3. Draw **system boundary** (rectangle)
4. Place actors **outside** the boundary
5. Place use cases **inside** the boundary
6. Draw **associations** between actors and use cases
7. Add `<<include>>` and `<<extend>>` relationships if needed

---

### 4. Diagram / Representation

**How to draw in Word:**
> Use Insert → Shapes → Oval for use cases, Stick figure for actors, Rectangle for system boundary. Use dashed arrows for include/extend.

```
Drawing Instructions:
- Draw a large rectangle labeled "System Name"
- Draw stick figures outside (left/right) for actors
- Draw ovals inside for use cases
- Connect with lines
```

---

### 5. Example / Solution

#### a) Use Case Diagram – College Automation System

**Actors:** Student, Faculty, Admin, Librarian

```
┌──────────────────────────────────────────────────────────────┐
│                   College Automation System                   │
│                                                              │
│  ┌──────────────┐   ┌──────────────┐   ┌─────────────────┐  │
│  │  Register    │   │  View Result │   │  Pay Fees       │  │
│  └──────┬───────┘   └──────┬───────┘   └────────┬────────┘  │
│         │                  │                     │           │
│  ┌──────────────┐   ┌──────────────┐   ┌─────────────────┐  │
│  │  Mark        │   │  Generate    │   │  Manage         │  │
│  │  Attendance  │   │  Report Card │   │  Library        │  │
│  └──────┬───────┘   └──────────────┘   └─────────────────┘  │
│         │                                                    │
│  ┌──────────────┐   ┌──────────────┐                        │
│  │  Add Student │   │  Manage Staff│                        │
│  └──────────────┘   └──────────────┘                        │
└──────────────────────────────────────────────────────────────┘

   👤 Student         👤 Faculty        👤 Admin       👤 Librarian
```

**Associations:**

| Actor | Use Cases |
|---|---|
| Student | Register, View Result, Pay Fees |
| Faculty | Mark Attendance, View Student List |
| Admin | Add Student, Generate Report Card, Manage Staff |
| Librarian | Manage Library (Issue/Return Books) |

**Relationships:**
- `Pay Fees` <<include>> `Generate Receipt`
- `View Result` <<extend>> `Download Marksheet`

---

#### b) Use Case Diagram – Banking Management System

**Actors:** Customer, Teller, Manager, ATM System

```
┌──────────────────────────────────────────────────────────────┐
│                   Banking Management System                   │
│                                                              │
│  ┌──────────────┐   ┌──────────────┐   ┌─────────────────┐  │
│  │  Open Account│   │  Deposit     │   │  Withdraw       │  │
│  └──────────────┘   │  Money       │   │  Money          │  │
│                     └──────────────┘   └─────────────────┘  │
│  ┌──────────────┐   ┌──────────────┐   ┌─────────────────┐  │
│  │  Transfer    │   │  View        │   │  Apply for      │  │
│  │  Funds       │   │  Statement   │   │  Loan           │  │
│  └──────────────┘   └──────────────┘   └─────────────────┘  │
│                                                              │
│  ┌──────────────┐   ┌──────────────┐                        │
│  │  Approve     │   │  Generate    │                        │
│  │  Loan        │   │  Report      │                        │
│  └──────────────┘   └──────────────┘                        │
└──────────────────────────────────────────────────────────────┘

   👤 Customer      👤 Teller       👤 Manager     🖥️ ATM System
```

**Associations:**

| Actor | Use Cases |
|---|---|
| Customer | Open Account, Deposit, Withdraw, Transfer, View Statement, Apply Loan |
| Teller | Deposit, Withdraw, Open Account |
| Manager | Approve Loan, Generate Report |
| ATM System | Withdraw Money, Check Balance |

**Relationships:**
- `Deposit Money` <<include>> `Update Balance`
- `Apply for Loan` <<extend>> `Upload Documents`

---

### 6. Output / Result

**Result:** Use Case Diagrams for both systems have been successfully developed. They clearly represent the interactions between different actors and the system functionalities, giving a high-level view of the system behavior.

---
---

## Assignment 4

### Develop Class Diagrams

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To develop **UML Class Diagrams** for the College Automation System and Banking Management System.

---

### 2. Theory

A **Class Diagram** is a structural UML diagram that shows:
- **Classes** (objects/entities in the system)
- **Attributes** (properties/data of each class)
- **Methods** (operations/functions of each class)
- **Relationships** between classes

**Class Notation:**

```
┌───────────────────┐
│    Class Name     │  ← Class Name (bold)
├───────────────────┤
│  - attribute1     │  ← Attributes (- = private, + = public)
│  - attribute2     │
├───────────────────┤
│  + method1()      │  ← Methods/Operations
│  + method2()      │
└───────────────────┘
```

**Relationships:**

| Relationship | Meaning | Symbol |
|---|---|---|
| Association | Class A uses Class B | Solid line |
| Aggregation | "Has-a" (weak) | Line with hollow diamond |
| Composition | "Has-a" (strong) | Line with filled diamond |
| Inheritance | "Is-a" | Line with hollow triangle arrow |
| Dependency | Uses temporarily | Dashed arrow |

---

### 3. Steps / Methodology

1. Identify all **entities** in the system
2. For each entity, define **attributes** (data fields)
3. For each entity, define **methods** (behaviors)
4. Identify **relationships** between entities
5. Draw classes and connect them with appropriate relationship lines
6. Add multiplicity (1, *, 0..1, etc.) to relationships

---

### 4. Diagram / Representation

> **In Word:** Use Insert → Table (3 rows, 1 column) for each class. Use shapes for arrows.

---

### 5. Example / Solution

#### a) Class Diagram – College Automation System

```
┌─────────────────────────┐         ┌─────────────────────────┐
│         Student         │         │         Course          │
├─────────────────────────┤         ├─────────────────────────┤
│ - studentId: int        │         │ - courseId: int         │
│ - name: String          │         │ - courseName: String    │
│ - email: String         │◆────────│ - credits: int          │
│ - dob: Date             │  enrolls│ - duration: String      │
│ - semester: int         │         ├─────────────────────────┤
├─────────────────────────┤         │ + getCourseInfo()       │
│ + register()            │         │ + addCourse()           │
│ + viewResult()          │         └─────────────────────────┘
│ + payFees()             │
└─────────────────────────┘

┌─────────────────────────┐         ┌─────────────────────────┐
│         Faculty         │         │        Attendance       │
├─────────────────────────┤         ├─────────────────────────┤
│ - facultyId: int        │         │ - attendanceId: int     │
│ - name: String          │─────────│ - date: Date            │
│ - department: String    │  marks  │ - status: String        │
│ - email: String         │         │ - studentId: int        │
├─────────────────────────┤         ├─────────────────────────┤
│ + markAttendance()      │         │ + markPresent()         │
│ + uploadMarks()         │         │ + markAbsent()          │
└─────────────────────────┘         └─────────────────────────┘

┌─────────────────────────┐         ┌─────────────────────────┐
│         Admin           │         │         Exam            │
├─────────────────────────┤         ├─────────────────────────┤
│ - adminId: int          │         │ - examId: int           │
│ - username: String      │─────────│ - examName: String      │
│ - password: String      │ manages │ - date: Date            │
├─────────────────────────┤         │ - totalMarks: int       │
│ + addStudent()          │         ├─────────────────────────┤
│ + generateReport()      │         │ + scheduleExam()        │
│ + manageFaculty()       │         │ + publishResult()       │
└─────────────────────────┘         └─────────────────────────┘
```

**Relationships:**
- Student *enrolls in* Course (Many-to-Many)
- Faculty *marks* Attendance (One-to-Many)
- Admin *manages* Exam (One-to-Many)
- Student *has* Attendance (Composition)

---

#### b) Class Diagram – Banking Management System

```
┌─────────────────────────┐         ┌─────────────────────────┐
│        Customer         │         │         Account         │
├─────────────────────────┤         ├─────────────────────────┤
│ - customerId: int       │         │ - accountNo: String     │
│ - name: String          │◆────────│ - accountType: String   │
│ - address: String       │  owns   │ - balance: double       │
│ - phone: String         │         │ - openDate: Date        │
├─────────────────────────┤         ├─────────────────────────┤
│ + openAccount()         │         │ + deposit()             │
│ + applyLoan()           │         │ + withdraw()            │
│ + viewStatement()       │         │ + getBalance()          │
└─────────────────────────┘         └─────────────────────────┘

┌─────────────────────────┐         ┌─────────────────────────┐
│       Transaction       │         │          Loan           │
├─────────────────────────┤         ├─────────────────────────┤
│ - transactionId: int    │         │ - loanId: int           │
│ - type: String          │         │ - loanAmount: double    │
│ - amount: double        │─────────│ - interestRate: double  │
│ - date: Date            │ records │ - tenure: int           │
├─────────────────────────┤         │ - status: String        │
│ + processTransaction()  │         ├─────────────────────────┤
│ + generateReceipt()     │         │ + applyLoan()           │
└─────────────────────────┘         │ + approveLoan()         │
                                    └─────────────────────────┘

┌─────────────────────────┐
│         Manager         │
├─────────────────────────┤
│ - managerId: int        │
│ - name: String          │
│ - branch: String        │
├─────────────────────────┤
│ + approveLoan()         │
│ + generateReport()      │
└─────────────────────────┘
```

**Relationships:**
- Customer *owns* Account (One-to-Many)
- Account *has* Transaction (Composition, One-to-Many)
- Customer *applies for* Loan (One-to-Many)
- Manager *approves* Loan (One-to-Many)

---

### 6. Output / Result

**Result:** Class Diagrams for both systems have been developed. They show the system's static structure with all entities, their attributes, methods, and relationships, forming the basis for database design and object-oriented implementation.

---
---

## Assignment 5

### Represent Project Scheduling

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To represent **Project Scheduling** using a Gantt Chart and other scheduling techniques for both projects.

---

### 2. Theory

**Project Scheduling** is the process of organizing and allocating time to different tasks in a project to ensure timely completion.

**Common Scheduling Tools:**

| Tool | Description |
|---|---|
| Gantt Chart | Bar chart showing tasks vs. time |
| PERT Chart | Network diagram showing task dependencies |
| CPM (Critical Path Method) | Finds the longest path = minimum project duration |
| WBS (Work Breakdown Structure) | Hierarchical breakdown of tasks |

**Key Terms:**

- **Milestone:** An important event/checkpoint in the project
- **Critical Path:** Sequence of tasks that determines minimum project duration
- **Slack/Float:** Extra time available for a non-critical task

---

### 3. Steps / Methodology

1. List all **tasks/activities** in the project
2. Estimate **duration** for each task
3. Identify **dependencies** (what needs to be done first)
4. Assign tasks to **team members**
5. Draw the **Gantt Chart**
6. Identify the **critical path**

---

### 4. Diagram / Representation

**Gantt Chart Format:**

```
Task Name         | W1 | W2 | W3 | W4 | W5 | W6 | W7 | W8 |
─────────────────────────────────────────────────────────────
Requirement       |████|████|    |    |    |    |    |    |
Analysis          |    |████|████|    |    |    |    |    |
System Design     |    |    |████|████|    |    |    |    |
Coding            |    |    |    |████|████|████|    |    |
Testing           |    |    |    |    |    |████|████|    |
Deployment        |    |    |    |    |    |    |████|████|

█ = Work in progress   W = Week
```

---

### 5. Example / Solution

#### a) Project Schedule – College Automation System

**Project Duration:** 16 Weeks (4 Months)

| Task No. | Task Name | Duration | Start Week | End Week | Depends On |
|---|---|---|---|---|---|
| T1 | Requirements Gathering | 2 weeks | W1 | W2 | — |
| T2 | SRS Documentation | 1 week | W2 | W3 | T1 |
| T3 | System Design (DB + UI) | 2 weeks | W3 | W5 | T2 |
| T4 | Frontend Development | 3 weeks | W5 | W8 | T3 |
| T5 | Backend Development | 4 weeks | W5 | W9 | T3 |
| T6 | Database Setup | 2 weeks | W5 | W7 | T3 |
| T7 | Integration & Testing | 2 weeks | W10 | W12 | T4, T5, T6 |
| T8 | UAT (User Acceptance Testing) | 2 weeks | W12 | W14 | T7 |
| T9 | Deployment & Training | 2 weeks | W14 | W16 | T8 |

**Gantt Chart:**
```
Week →     1  2  3  4  5  6  7  8  9  10 11 12 13 14 15 16
T1 Req.    ██ ██
T2 SRS        ██
T3 Design        ██ ██
T4 Frontend          ██ ██ ██
T5 Backend           ██ ██ ██ ██
T6 DB                ██ ██
T7 Testing                        ██ ██
T8 UAT                               ██ ██
T9 Deploy                                  ██ ██
```

**Critical Path:** T1 → T2 → T3 → T5 → T7 → T8 → T9 (16 weeks)

**Milestones:**
- End of W3: SRS Complete
- End of W9: All coding complete
- End of W12: Testing complete
- End of W16: System live

---

#### b) Project Schedule – Banking Management System

**Project Duration:** 20 Weeks (5 Months)

| Task No. | Task Name | Duration | Start Week | End Week | Depends On |
|---|---|---|---|---|---|
| T1 | Requirements & Feasibility | 2 weeks | W1 | W2 | — |
| T2 | SRS & Design Docs | 2 weeks | W3 | W4 | T1 |
| T3 | Architecture Design | 2 weeks | W4 | W6 | T2 |
| T4 | Database Design | 2 weeks | W6 | W8 | T3 |
| T5 | Core Banking Module | 4 weeks | W7 | W11 | T3, T4 |
| T6 | Transaction Module | 3 weeks | W9 | W12 | T5 |
| T7 | Loan Management Module | 3 weeks | W10 | W13 | T5 |
| T8 | Security Implementation | 2 weeks | W12 | W14 | T5, T6 |
| T9 | Integration Testing | 2 weeks | W14 | W16 | T6, T7, T8 |
| T10 | Performance Testing | 2 weeks | W16 | W18 | T9 |
| T11 | Deployment & Go-Live | 2 weeks | W18 | W20 | T10 |

**Critical Path:** T1→T2→T3→T4→T5→T6→T8→T9→T10→T11 (20 weeks)

---

### 6. Output / Result

**Result:** Project schedules for both systems have been successfully represented using Gantt Charts. The critical paths have been identified, and key milestones have been set to monitor project progress effectively.

---
---

## Assignment 6

### Estimate Effort, Schedule, and Cost of Software Project

---

### 1. Aim

To estimate the **effort**, **schedule**, and **cost** of the College Automation System and Banking Management System using standard software estimation techniques.

---

### 2. Theory

**Software Estimation** is the process of predicting the resources (time, people, money) needed to develop software.

**COCOMO Model (Constructive Cost Model):**
Developed by Barry Boehm. The basic COCOMO formula is:

```
Effort (E)    = a × (KLOC)^b   [Person-Months]
Duration (D)  = c × (E)^d      [Months]
Staff (P)     = E / D           [People]
Cost          = E × Monthly_Cost_Per_Person
```

**COCOMO Categories:**

| Mode | Project Type | a | b | c | d |
|---|---|---|---|---|---|
| Organic | Small, simple | 2.4 | 1.05 | 2.5 | 0.38 |
| Semi-detached | Medium | 3.0 | 1.12 | 2.5 | 0.35 |
| Embedded | Complex, real-time | 3.6 | 1.20 | 2.5 | 0.32 |

**KLOC** = Kilo Lines of Code (estimated thousands of lines)

---

### 3. Steps / Methodology

1. **Estimate KLOC** (size of the project)
2. **Choose COCOMO mode** (Organic/Semi-detached/Embedded)
3. **Calculate Effort** using formula
4. **Calculate Duration** using formula
5. **Calculate Staff needed**
6. **Estimate Cost** = Effort × Monthly cost per person

---

### 4. Diagram / Representation

```
Project Size (KLOC)
        │
        ▼
 Choose COCOMO Mode
        │
        ▼
  Effort = a × (KLOC)^b
        │
        ▼
  Duration = c × (E)^d
        │
        ▼
  Staff = Effort / Duration
        │
        ▼
  Cost = Effort × Rate
```

---

### 5. Example / Solution

#### a) Estimation – College Automation System

**Assumptions:**
- Estimated size = **10 KLOC** (10,000 lines of code)
- Mode = **Organic** (small academic project, simple team)
- Monthly cost per person = ₹50,000

**Calculations:**

```
Effort (E)    = 2.4 × (10)^1.05
              = 2.4 × 11.22
              = 26.93 ≈ 27 Person-Months

Duration (D)  = 2.5 × (27)^0.38
              = 2.5 × 3.75
              = 9.38 ≈ 9.4 Months

Staff (P)     = 27 / 9.4
              = 2.87 ≈ 3 People

Cost          = 27 × 50,000
              = ₹13,50,000
```

**Summary:**

| Parameter | Value |
|---|---|
| Project Size | 10 KLOC |
| Effort | 27 Person-Months |
| Schedule/Duration | ~9.4 Months |
| Team Size | 3 Developers |
| Estimated Cost | ₹13,50,000 |

---

#### b) Estimation – Banking Management System

**Assumptions:**
- Estimated size = **25 KLOC** (25,000 lines of code)
- Mode = **Semi-detached** (medium complexity, moderate team)
- Monthly cost per person = ₹80,000

**Calculations:**

```
Effort (E)    = 3.0 × (25)^1.12
              = 3.0 × 33.47
              = 100.4 ≈ 100 Person-Months

Duration (D)  = 2.5 × (100)^0.35
              = 2.5 × 5.01
              = 12.53 ≈ 12.5 Months

Staff (P)     = 100 / 12.5
              = 8 People

Cost          = 100 × 80,000
              = ₹80,00,000
```

**Summary:**

| Parameter | Value |
|---|---|
| Project Size | 25 KLOC |
| Effort | 100 Person-Months |
| Schedule/Duration | ~12.5 Months |
| Team Size | 8 Developers |
| Estimated Cost | ₹80,00,000 |

---

### 6. Output / Result

**Result:** Using the COCOMO Basic model, the effort, schedule, and cost have been estimated for both projects. The College Automation System requires ~27 person-months and ₹13.5 lakhs, while the Banking Management System requires ~100 person-months and ₹80 lakhs.

---
---

## Assignment 7

### Develop DFD (Level 0, Level 1, and Data Dictionary)

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To develop **Data Flow Diagrams (DFD)** at Level 0 and Level 1, along with a **Data Dictionary** for both systems.

---

### 2. Theory

A **DFD (Data Flow Diagram)** is a graphical representation showing how data flows through a system.

**DFD Symbols:**

| Symbol | Shape | Represents |
|---|---|---|
| External Entity | Rectangle / Square | Source or destination of data (user/external system) |
| Process | Circle / Rounded rectangle | Transforms data |
| Data Store | Open rectangle (two parallel lines) | Stores data |
| Data Flow | Arrow | Movement of data |

**DFD Levels:**

| Level | Description |
|---|---|
| Level 0 (Context Diagram) | Shows entire system as ONE process |
| Level 1 | Breaks down into major sub-processes |
| Level 2+ | Further decomposition (if needed) |

**Data Dictionary:** A catalog that defines all data elements — their name, type, size, and description.

---

### 3. Steps / Methodology

1. Identify **external entities** (who sends/receives data)
2. Draw **Level 0 DFD** (Context Diagram — system as one process)
3. Identify **main processes** in the system
4. Draw **Level 1 DFD** (decompose main process)
5. Identify **data stores**
6. Create **Data Dictionary** for all data elements

---

### 4. Diagram / Representation

> **In Word:** Use circles for processes, rectangles for external entities, parallel lines for data stores, and arrows for data flow.

---

### 5. Example / Solution

#### a) DFD – College Automation System

**Level 0 (Context Diagram):**

```
                    ┌─────────────────┐
  Student ─────────▶│                 │────────▶ Student
                    │    College      │
  Faculty ─────────▶│    Automation   │────────▶ Faculty
                    │    System       │
  Admin ───────────▶│                 │────────▶ Admin
                    └─────────────────┘
                            │
                            ▼
                       Management
```

**Simplified Level 0:**
```
[Student] ──── Student Info ────▶ ┌──────────────────┐ ──── Result ────▶ [Student]
[Faculty] ──── Attendance Data ──▶ │  0               │ ──── Reports ───▶ [Admin]
[Admin]   ──── Admin Request ────▶ │  College         │
                                   │  Automation      │
                                   │  System          │
                                   └──────────────────┘
```

---

**Level 1 DFD:**

```
[Student] ──Student Data──▶ (1.0 Registration) ──Student Record──▶ {D1: Student DB}
                                                                          │
[Faculty] ──Attendance──▶  (2.0 Attendance     ) ──Attendance Rec──▶ {D2: Attendance DB}
                              Management
                                                                          │
[Student] ──Exam Request──▶ (3.0 Exam          ) ──Result──────────▶ {D3: Result DB}
                              Management                    │
                                                            └──▶ [Student]

[Admin]   ──Fee Request──▶  (4.0 Fee           ) ──Fee Record──▶ {D4: Fee DB}
                              Management                │
                                                        └──▶ [Student]
```

**Processes (Level 1):**
1. **1.0 Registration** — Process student admission
2. **2.0 Attendance Management** — Mark and track attendance
3. **3.0 Exam Management** — Schedule exams, publish results
4. **4.0 Fee Management** — Collect and record fees

**Data Stores:**
- D1: Student Database
- D2: Attendance Database
- D3: Result Database
- D4: Fee Database

**Data Dictionary:**

| Data Element | Type | Size | Description |
|---|---|---|---|
| StudentID | Integer | 6 digits | Unique student identifier |
| StudentName | String | 50 chars | Full name of student |
| Semester | Integer | 1 digit | Current semester (1-8) |
| AttendanceDate | Date | DD/MM/YYYY | Date of attendance |
| AttendanceStatus | Char | 1 char | P=Present, A=Absent |
| ExamID | Integer | 6 digits | Unique exam identifier |
| Marks | Integer | 3 digits | Marks obtained (0-100) |
| FeeAmount | Decimal | 8 digits | Amount of fee paid |
| PaymentDate | Date | DD/MM/YYYY | Date of fee payment |

---

#### b) DFD – Banking Management System

**Level 0 (Context Diagram):**

```
[Customer] ──── Account Request ────▶ ┌─────────────────┐ ──── Account Info ────▶ [Customer]
[Teller]   ──── Transaction Data ───▶ │   Banking        │ ──── Receipt ──────────▶ [Customer]
[Manager]  ──── Loan Approval ──────▶ │   Management     │ ──── Report ───────────▶ [Manager]
                                       │   System         │
                                       └─────────────────┘
```

**Level 1 DFD:**

```
[Customer] ──Account Data──▶  (1.0 Account     ) ──Account Record──▶ {D1: Account DB}
                               Management

[Customer] ──Txn Request──▶   (2.0 Transaction  ) ──Txn Record──▶ {D2: Transaction DB}
[Teller]   ──Teller Input──▶   Processing               │
                                                         └──▶ [Customer] (Receipt)

[Customer] ──Loan Request──▶  (3.0 Loan         ) ──Loan Record──▶ {D3: Loan DB}
[Manager]  ──Approval──────▶   Management               │
                                                         └──▶ [Customer] (Status)

[Manager]  ──Report Request──▶ (4.0 Report       ) ──▶ [Manager] (Report)
                                Generation         {D1, D2, D3}
```

**Data Dictionary:**

| Data Element | Type | Size | Description |
|---|---|---|---|
| AccountNo | String | 12 chars | Unique account number |
| CustomerID | Integer | 8 digits | Unique customer ID |
| Balance | Decimal | 12 digits | Current account balance |
| TransactionID | Integer | 10 digits | Unique transaction ID |
| TransactionType | String | 10 chars | Deposit/Withdrawal/Transfer |
| Amount | Decimal | 12 digits | Transaction amount |
| TransactionDate | Date | DD/MM/YYYY | Date of transaction |
| LoanID | Integer | 8 digits | Unique loan ID |
| LoanAmount | Decimal | 12 digits | Loan amount requested |
| LoanStatus | String | 10 chars | Approved/Pending/Rejected |

---

### 6. Output / Result

**Result:** DFD Level 0, Level 1, and Data Dictionaries for both systems have been successfully developed. The diagrams clearly show the flow of data between external entities, processes, and data stores, providing a complete picture of the system's data model.

---
---

## Assignment 8

### Develop Sequence Diagram

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To develop **UML Sequence Diagrams** for key scenarios in the College Automation System and Banking Management System.

---

### 2. Theory

A **Sequence Diagram** is a UML behavioral diagram that shows how objects interact with each other **over time** in a sequential order.

**Key Elements:**

| Element | Symbol | Description |
|---|---|---|
| Actor/Object | Box at top | Participant in the interaction |
| Lifeline | Vertical dashed line | Shows object's existence over time |
| Activation Bar | Thin rectangle on lifeline | Shows when object is active |
| Message | Horizontal arrow | Communication between objects |
| Return Message | Dashed arrow | Return value/response |
| Self Message | Arrow to same object | Object calling its own method |

**Types of Messages:**
- **Synchronous (→):** Sender waits for response (solid arrowhead)
- **Asynchronous (→):** Sender does not wait (open arrowhead)
- **Return (- ->):** Returning control/value

---

### 3. Steps / Methodology

1. Identify the **scenario/use case** to be represented
2. List all **objects/actors** involved
3. Draw **lifelines** for each object
4. Show messages in **chronological order** (top to bottom)
5. Show **return messages** after each operation
6. Add **activation bars** where necessary

---

### 4. Diagram / Representation

> **In Word:** Draw vertical boxes at top (objects), vertical dashed lines below (lifelines), horizontal arrows between lifelines (messages). Label all arrows.

```
Object1          Object2          Object3
   │                │                │
   │──message1()──▶│                │
   │                │──message2()──▶│
   │                │◀─response2()─│
   │◀──response1()─│                │
   │                │                │
```

---

### 5. Example / Solution

#### a) Sequence Diagram – Student Login & View Result (College System)

```
Student       LoginPage      AuthSystem     Database      ResultPage
   │              │               │              │              │
   │──enterLogin()──▶             │              │              │
   │              │──validate()──▶│              │              │
   │              │               │──queryDB()──▶│              │
   │              │               │◀──userData()─│              │
   │              │◀──authResult()│              │              │
   │◀──showDashboard()            │              │              │
   │                                                            │
   │──viewResult()──────────────────────────────────────────▶  │
   │                                             │◀──fetchResult()
   │                                             │──resultData──▶
   │◀──displayResult()────────────────────────────────────────  │
```

**Steps:**
1. Student enters username and password on Login Page
2. Login Page sends credentials to Auth System
3. Auth System queries Database to verify credentials
4. Database returns user data
5. Auth System returns authentication result
6. Login Page shows Dashboard to Student
7. Student requests to View Result
8. Result Page fetches result from Database
9. Database returns result data
10. Result Page displays result to Student

---

#### b) Sequence Diagram – Bank Transaction (Deposit Money)

```
Customer      ATM/Portal    TransactionCtrl   AccountDB    NotifService
   │              │               │               │              │
   │──insertCard()──▶             │               │              │
   │              │──verifyPIN()─▶│               │              │
   │              │               │──checkAcct()─▶│              │
   │              │               │◀──acctInfo()──│              │
   │              │◀──verified()──│               │              │
   │◀──showMenu()─│               │               │              │
   │──selectDeposit()──▶          │               │              │
   │──enterAmount()──▶            │               │              │
   │              │──processDeposit()──▶          │              │
   │              │               │──updateBalance()──▶          │
   │              │               │◀──balanceUpdated()           │
   │              │               │──sendNotification()──────────▶
   │              │◀──success()───│               │              │
   │◀──printReceipt()             │               │              │
```

**Steps:**
1. Customer inserts card at ATM/Portal
2. ATM verifies PIN via Transaction Controller
3. Transaction Controller checks account in Account DB
4. Account DB returns account info
5. Customer selects "Deposit" from menu
6. Customer enters deposit amount
7. ATM sends deposit request to Transaction Controller
8. Transaction Controller updates balance in Account DB
9. Notification Service sends SMS to customer
10. ATM prints receipt for customer

---

### 6. Output / Result

**Result:** Sequence Diagrams for key scenarios (Student Login/View Result and Bank Deposit Transaction) have been successfully developed. They clearly show the time-ordered interaction between system components, making the system behavior easy to understand.

---
---

## Assignment 9

### Develop Structured Design from DFD

---

### 1. Aim

To develop **Structured Design** (Structure Chart) from the Data Flow Diagrams (DFD) of the College Automation System and Banking Management System.

---

### 2. Theory

**Structured Design** is a method that transforms DFD into a **hierarchical program structure** using a **Structure Chart**.

**Structure Chart** shows:
- **Modules** (program units/functions)
- **Hierarchy** (which module calls which)
- **Data flow** between modules (couples)
- **Control flow** (flags/conditions)

**Key Concepts:**

| Concept | Description |
|---|---|
| Module | A unit of code (function/procedure) |
| Coupling | Degree of dependency between modules (lower = better) |
| Cohesion | How related the functions within a module are (higher = better) |
| Transform Analysis | Mapping DFD transforms to modules |
| Transaction Analysis | Mapping DFD transactions to modules |

**Types of Coupling (best to worst):** Data → Stamp → Control → Common → Content

**Types of Cohesion (best to worst):** Functional → Sequential → Communicational → Procedural → Temporal → Logical → Coincidental

---

### 3. Steps / Methodology

1. Take the **Level 1 DFD** as input
2. Identify **input, processing, and output** transforms
3. Identify the **central transform** (main processing)
4. Apply **Transform Analysis** to map DFD to Structure Chart
5. Create a **hierarchy of modules**
6. Show **data passing** between modules using arrows with labels
7. Evaluate **coupling and cohesion** of modules

---

### 4. Diagram / Representation

```
         ┌─────────────────┐
         │   Main Program  │
         └────────┬────────┘
         ┌────────┴────────┐
    ┌────▼────┐        ┌────▼────┐
    │ Input   │        │ Output  │
    │ Module  │        │ Module  │
    └────┬────┘        └─────────┘
    ┌────▼────┐
    │ Process │
    │ Module  │
    └─────────┘
```

---

### 5. Example / Solution

#### a) Structure Chart – College Automation System

```
                    ┌──────────────────────────┐
                    │   Main Control Module    │
                    │   (College Automation)   │
                    └─────────────┬────────────┘
          ┌──────────────┬────────┴────────┬──────────────┐
          ▼              ▼                  ▼              ▼
┌──────────────┐ ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
│  Student     │ │ Attendance   │ │    Exam      │ │    Fee       │
│  Management │ │ Management   │ │  Management  │ │  Management  │
└──────┬───────┘ └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
       │                │                │                │
  ┌────┴────┐      ┌────┴────┐      ┌────┴────┐      ┌────┴────┐
  │  Add    │      │  Mark   │      │ Schedule│      │Collect  │
  │ Student │      │ Present │      │  Exam   │      │  Fee    │
  └─────────┘      └─────────┘      └─────────┘      └─────────┘
  ┌─────────┐      ┌─────────┐      ┌─────────┐      ┌─────────┐
  │  View   │      │Generate │      │ Publish │      │Generate │
  │ Profile │      │  Report │      │ Result  │      │ Receipt │
  └─────────┘      └─────────┘      └─────────┘      └─────────┘
```

**Module Descriptions:**

| Module | Function | Cohesion Type |
|---|---|---|
| Student Management | Handles all student operations | Functional |
| Attendance Management | Marks and reports attendance | Functional |
| Exam Management | Manages exams and results | Functional |
| Fee Management | Processes fee payments | Functional |
| Add Student | Adds new student record | Functional |
| Mark Present | Records attendance | Functional |

---

#### b) Structure Chart – Banking Management System

```
                      ┌─────────────────────────────┐
                      │   Main Control Module       │
                      │   (Banking Management)      │
                      └──────────────┬──────────────┘
        ┌─────────────┬──────────────┼──────────────┬─────────────┐
        ▼             ▼              ▼               ▼             ▼
┌─────────────┐ ┌──────────┐ ┌──────────────┐ ┌──────────┐ ┌──────────┐
│   Account   │ │ Deposit  │ │  Withdrawal  │ │  Loan    │ │ Report   │
│  Management │ │ Module   │ │   Module     │ │ Module   │ │ Module   │
└──────┬──────┘ └────┬─────┘ └──────┬───────┘ └────┬─────┘ └────┬─────┘
       │             │              │               │             │
  ┌────┴────┐   ┌────┴────┐   ┌────┴────┐   ┌────┴────┐   ┌────┴────┐
  │  Open   │   │ Accept  │   │ Verify  │   │  Apply  │   │Generate │
  │ Account │   │ Amount  │   │ Balance │   │  Loan   │   │Statement│
  └─────────┘   └─────────┘   └─────────┘   └─────────┘   └─────────┘
  ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐
  │ Verify  │   │ Update  │   │ Dispense│   │ Approve │
  │   KYC   │   │ Balance │   │  Cash   │   │  Loan   │
  └─────────┘   └─────────┘   └─────────┘   └─────────┘
```

**Coupling Analysis:**

| Module Pair | Coupling Type | Notes |
|---|---|---|
| Main → Account Management | Data Coupling | Passes account ID |
| Main → Deposit Module | Data Coupling | Passes amount |
| Deposit → Update Balance | Data Coupling | Passes amount + account |
| All modules are loosely coupled | Good design | ✓ |

---

### 6. Output / Result

**Result:** Structured Design (Structure Charts) have been successfully derived from the DFDs of both systems. The charts show a clean hierarchical module structure with low coupling and high cohesion, indicating a well-designed system.

---
---

## Assignment 10

### Develop Waterfall, Prototype, and Spiral Models

---

### 1. Aim

To describe and represent the **Waterfall Model**, **Prototype Model**, and **Spiral Model** of software development.

---

### 2. Theory

Software development models (also called **SDLC models**) define the process and order in which software development activities are performed.

---

#### A. Waterfall Model

The **Waterfall Model** is the oldest and most basic SDLC model. Phases are executed **sequentially** — one phase must be complete before the next begins.

**Phases:**
1. Requirement Analysis
2. System Design
3. Implementation (Coding)
4. Testing
5. Deployment
6. Maintenance

**Advantages:**
- Simple and easy to understand
- Phases are clearly defined
- Works well for small, well-understood projects

**Disadvantages:**
- No flexibility for changes once phase is complete
- Customer sees product only at the end
- Not suitable for complex or uncertain projects

---

#### B. Prototype Model

The **Prototype Model** involves building a **working demo (prototype)** of the system early, getting user feedback, and refining it.

**Phases:**
1. Gather Initial Requirements
2. Build Prototype
3. User Evaluates Prototype
4. Refine Requirements
5. Build Actual System
6. Delivery

**Advantages:**
- User gets early visibility
- Reduces misunderstandings
- Good for unclear requirements

**Disadvantages:**
- May give false impression of finished product
- Can lead to scope creep

---

#### C. Spiral Model

The **Spiral Model** combines **risk analysis** with the iterative approach. Each loop in the spiral represents a phase with four quadrants.

**Quadrants per cycle:**
1. Planning (Determine objectives)
2. Risk Analysis (Identify and resolve risks)
3. Engineering (Development and testing)
4. Evaluation (Customer review)

**Advantages:**
- Risk-driven approach
- Works for large, complex projects
- Flexible — allows changes

**Disadvantages:**
- Expensive and complex
- Requires risk assessment expertise
- Not suitable for small projects

---

### 3. Steps / Methodology

**For Waterfall:** Follow phases linearly, complete documentation at each phase, no going back.

**For Prototype:** Build quick demo → get feedback → improve → repeat → build final system.

**For Spiral:** Each cycle: Plan → Analyze Risk → Build → Evaluate → repeat until delivery.

---

### 4. Diagram / Representation

#### Waterfall Model:
```
┌─────────────────────────────────────────┐
│         WATERFALL MODEL                 │
│                                         │
│  ┌─────────────────────────────┐        │
│  │  Requirements Analysis      │        │
│  └──────────────┬──────────────┘        │
│                 ▼                       │
│  ┌─────────────────────────────┐        │
│  │      System Design          │        │
│  └──────────────┬──────────────┘        │
│                 ▼                       │
│  ┌─────────────────────────────┐        │
│  │   Implementation (Coding)   │        │
│  └──────────────┬──────────────┘        │
│                 ▼                       │
│  ┌─────────────────────────────┐        │
│  │         Testing             │        │
│  └──────────────┬──────────────┘        │
│                 ▼                       │
│  ┌─────────────────────────────┐        │
│  │       Deployment            │        │
│  └──────────────┬──────────────┘        │
│                 ▼                       │
│  ┌─────────────────────────────┐        │
│  │       Maintenance           │        │
│  └─────────────────────────────┘        │
└─────────────────────────────────────────┘
```

#### Prototype Model:
```
┌─────────────────────────────────────────┐
│           PROTOTYPE MODEL               │
│                                         │
│  Requirements ──▶ Build Prototype       │
│       ▲                │                │
│       │                ▼                │
│  Refine           User Reviews          │
│  Requirements ◀── Prototype             │
│       │                                 │
│       ▼ (when satisfied)                │
│  Build Final System ──▶ Deliver         │
└─────────────────────────────────────────┘
```

#### Spiral Model:
```
            Planning
               │
    ┌──────────┴──────────┐
    │                     │
Evaluation          Risk Analysis
    │                     │
    └──────────┬──────────┘
               │
           Engineering
               │
         (Next Cycle)
         Spiral grows
         outward each
            cycle
```

*Each spiral = one development cycle (outer = later, larger phase)*

---

### 5. Example / Solution

#### College Automation System

| Model | Suitable? | Reason |
|---|---|---|
| Waterfall | Partially | Requirements are known, but changes may arise during development |
| Prototype | Yes | Admin/Faculty may not be sure of exact UI — prototype helps |
| Spiral | Overkill | Small project — spiral is too expensive |

**Best approach:** Prototype Model (build demo for admin panel, get feedback, then develop fully)

#### Banking Management System

| Model | Suitable? | Reason |
|---|---|---|
| Waterfall | No | Complex system, requirements may change |
| Prototype | Partially | Good for UI demo, but not for core banking logic |
| Spiral | Yes | High risk, large system — risk analysis is critical |

**Best approach:** Spiral Model (each cycle handles one major module)

---

### 6. Output / Result

**Result:** All three SDLC models — Waterfall, Prototype, and Spiral — have been described with diagrams. The Prototype model suits the College Automation System, while the Spiral model is best for the Banking Management System due to its complexity and risk factors.

---
---

## Assignment 11

### Explain Which Model is Best and Why

---

### 1. Aim

To evaluate and compare the **Waterfall, Prototype, and Spiral Models** and determine the most suitable model for each project with reasoning.

---

### 2. Theory

Different software development models suit different types of projects. The choice depends on:
- **Size of project** (small / medium / large)
- **Clarity of requirements** (clear / unclear / changing)
- **Risk level** (low / medium / high)
- **Customer involvement** (low / high)
- **Budget and time** (fixed / flexible)

**Comparison Table:**

| Factor | Waterfall | Prototype | Spiral |
|---|---|---|---|
| Requirements | Must be clear and fixed | Can be unclear initially | Can evolve |
| Flexibility | Low | Medium | High |
| Customer Interaction | At start and end | Frequent | At each cycle |
| Cost | Low | Medium | High |
| Risk Management | Poor | Medium | Excellent |
| Best For | Small, simple projects | Projects with UI/UX focus | Large, complex, risky projects |
| Documentation | Extensive | Less formal | Moderate |
| Testing | Done after coding | Done iteratively | Done in each cycle |

---

### 3. Steps / Methodology

1. List the **characteristics** of the project
2. Compare with **features of each model**
3. Select the model that has the **most matching features**
4. Justify with **reasoning**

---

### 4. Diagram / Representation

```
Project Characteristics
         │
    ┌────┴─────────────────────────────┐
    │                                  │
    ▼                                  ▼
Are requirements    ──YES──▶  Is it small/simple?
clear and fixed?                   │
    │                        ┌──────┴──────┐
   NO                       YES            NO
    │                        │              │
    ▼                        ▼              ▼
Is risk high?         WATERFALL         PROTOTYPE
    │
    ├──YES──▶  SPIRAL MODEL
    │
   NO
    │
    ▼
PROTOTYPE MODEL
```

---

### 5. Example / Solution

#### a) College Automation System — Recommended: Prototype Model ✓

**Reasons:**

1. **Unclear UI Requirements:** Faculty and students may not know exactly what they want in the interface until they see it.
2. **Low Risk:** The system is not mission-critical; errors can be corrected.
3. **User Involvement:** Admin and faculty should give feedback on the working demo.
4. **Simple Scope:** Attendance, fees, results — well understood domains.
5. **Fast Delivery:** A prototype can be ready in 2-3 weeks; feedback speeds up final development.

**How Prototype Model Helps:**
- Build a working demo of the attendance module
- Show to faculty → get suggestions
- Improve and show fee module demo to admin
- Continue refining until final system is built

**Conclusion:** Prototype Model is best for College Automation System because requirements are not 100% clear, user feedback is important, and the risk is low.

---

#### b) Banking Management System — Recommended: Spiral Model ✓

**Reasons:**

1. **High Risk:** Deals with financial data — any failure can cause major loss.
2. **Large and Complex:** Multiple modules — accounts, transactions, loans, security.
3. **Changing Regulations:** Banking rules and compliance requirements may change.
4. **Critical Security:** Risk analysis in each spiral cycle ensures security vulnerabilities are identified early.
5. **Long Duration:** 12-20 month project needs iterative development with regular reviews.

**How Spiral Model Helps:**
- **Cycle 1:** Build basic account management module
- **Cycle 2:** Add transaction processing with risk analysis
- **Cycle 3:** Implement loan management
- **Cycle 4:** Security hardening and performance optimization
- Each cycle includes customer review and risk assessment

**Conclusion:** Spiral Model is best for Banking Management System because it is a high-risk, large-scale, complex system where risk management is critical.

---

**Final Comparison:**

| Project | Best Model | Why |
|---|---|---|
| College Automation | Prototype | Unclear requirements, user feedback needed, low risk |
| Banking Management | Spiral | High risk, large system, changing requirements, security critical |

---

### 6. Output / Result

**Result:** After comparing all three models, the **Prototype Model** is recommended for the College Automation System and the **Spiral Model** is recommended for the Banking Management System. This decision is based on project size, risk level, requirement clarity, and customer involvement.

---
---

## Assignment 12

### Develop Working Protocol (Algorithm / Flow)

#### a) College Automation System | b) Banking Management System

---

### 1. Aim

To develop **Working Protocols** in the form of **algorithms and flowcharts** for key functionalities of both systems.

---

### 2. Theory

**Algorithm:** A step-by-step set of instructions to solve a problem or perform a task. It is language-independent.

**Properties of a good algorithm:**
- Clear and unambiguous
- Has a definite start and end
- Produces correct output for given input
- Efficient (minimal steps)

**Flowchart:** A visual representation of an algorithm using standard symbols.

**Flowchart Symbols:**

| Symbol | Shape | Meaning |
|---|---|---|
| Terminal | Oval/Rounded rectangle | Start / Stop |
| Process | Rectangle | Processing step |
| Decision | Diamond | Yes/No condition |
| Input/Output | Parallelogram | Read/Write data |
| Connector | Circle | Connect parts of flowchart |
| Arrow | Line with arrow | Flow direction |

---

### 3. Steps / Methodology

1. Understand the **process/functionality**
2. Identify **inputs, outputs, and conditions**
3. Write a step-by-step **algorithm**
4. Draw a **flowchart** representing the algorithm

---

### 4. Diagram / Representation

> **In Word:** Use Insert → Shapes to draw flowchart symbols. Connect with arrows. Label each shape.

---

### 5. Example / Solution

#### a) College Automation System

**Scenario 1: Student Login and Attendance Marking**

**Algorithm:**
```
Algorithm: Student_Login_Attendance
Input: Username, Password, StudentID, Date
Output: Attendance record or Error message

Step 1: START
Step 2: Input username and password from user
Step 3: Query database for user with entered username
Step 4: IF user found THEN
Step 5:     IF password matches THEN
Step 6:         Display dashboard
Step 7:         Input StudentID for attendance
Step 8:         Query attendance database for today's record
Step 9:         IF record exists THEN
Step 10:            Display "Attendance already marked"
Step 11:        ELSE
Step 12:            Mark attendance as Present
Step 13:            Save record to database
Step 14:            Display "Attendance marked successfully"
Step 15:        END IF
Step 16:    ELSE
Step 17:        Display "Invalid password"
Step 18:    END IF
Step 19: ELSE
Step 20:    Display "User not found"
Step 21: END IF
Step 22: STOP
```

**Flowchart:**
```
         ┌─────────┐
         │  START  │
         └────┬────┘
              ▼
    ┌──────────────────┐
    │ Input: Username, │
    │     Password     │
    └────────┬─────────┘
             ▼
    ┌────────────────────┐
    │ User found in DB?  │◆──NO──▶ "User not found" ──▶ STOP
    └────────┬───────────┘
             │ YES
             ▼
    ┌────────────────────┐
    │ Password correct?  │◆──NO──▶ "Invalid Password" ──▶ STOP
    └────────┬───────────┘
             │ YES
             ▼
    ┌─────────────────────┐
    │ Show Dashboard      │
    └────────┬────────────┘
             ▼
    ┌─────────────────────┐
    │ Input: StudentID    │
    └────────┬────────────┘
             ▼
    ┌──────────────────────────┐
    │ Attendance already       │◆──YES──▶ "Already marked"
    │ marked today?            │
    └────────┬─────────────────┘
             │ NO
             ▼
    ┌─────────────────────────┐
    │ Mark Present in DB      │
    └────────┬────────────────┘
             ▼
    ┌─────────────────────────┐
    │ "Attendance Marked"     │
    └────────┬────────────────┘
             ▼
         ┌────────┐
         │  STOP  │
         └────────┘
```

---

#### b) Banking Management System

**Scenario: ATM Withdrawal**

**Algorithm:**
```
Algorithm: ATM_Withdrawal
Input: AccountNo, PIN, WithdrawalAmount
Output: Cash or Error

Step 1: START
Step 2: Input AccountNo
Step 3: Input PIN
Step 4: Verify PIN from database
Step 5: IF PIN is correct THEN
Step 6:     Display balance and menu
Step 7:     Input WithdrawalAmount
Step 8:     IF WithdrawalAmount > 0 THEN
Step 9:         IF WithdrawalAmount <= AccountBalance THEN
Step 10:            Deduct amount from balance
Step 11:            Update database
Step 12:            Dispense cash
Step 13:            Print receipt
Step 14:        ELSE
Step 15:            Display "Insufficient Balance"
Step 16:        END IF
Step 17:    ELSE
Step 18:        Display "Invalid Amount"
Step 19:    END IF
Step 20: ELSE
Step 21:    Display "Wrong PIN"
Step 22: END IF
Step 23: STOP
```

**Flowchart:**
```
         ┌─────────┐
         │  START  │
         └────┬────┘
              ▼
    ┌──────────────────┐
    │ Input: Account   │
    │ No. and PIN      │
    └────────┬─────────┘
             ▼
    ┌────────────────────┐
    │    PIN Correct?    │◆──NO──▶ "Wrong PIN" ──▶ STOP
    └────────┬───────────┘
             │ YES
             ▼
    ┌──────────────────────┐
    │ Show Balance & Menu  │
    └────────┬─────────────┘
             ▼
    ┌──────────────────────┐
    │ Input Amount         │
    └────────┬─────────────┘
             ▼
    ┌──────────────────────────┐
    │ Amount <= Balance?       │◆──NO──▶ "Insufficient Balance" ──▶ STOP
    └────────┬─────────────────┘
             │ YES
             ▼
    ┌─────────────────────────┐
    │ Deduct & Update DB      │
    └────────┬────────────────┘
             ▼
    ┌─────────────────────────┐
    │ Dispense Cash           │
    └────────┬────────────────┘
             ▼
    ┌─────────────────────────┐
    │ Print Receipt           │
    └────────┬────────────────┘
             ▼
         ┌────────┐
         │  STOP  │
         └────────┘
```

---

### 6. Output / Result

**Result:** Working protocols (algorithms and flowcharts) for key scenarios — Student Attendance (College System) and ATM Withdrawal (Banking System) — have been successfully developed. These provide a clear, step-by-step logic for implementing the functionalities.

---
---

## Assignment 13

### Use LOC, Function Point, and Cyclomatic Complexity Metrics

---

### 1. Aim

To calculate and apply **software metrics** — LOC (Lines of Code), Function Point (FP), and Cyclomatic Complexity — to measure software quality and size.

---

### 2. Theory

**Software Metrics** are quantitative measures used to assess different aspects of software.

---

#### A. LOC (Lines of Code)

The simplest metric — counts the number of lines in source code.

**Types:**
- **SLOC (Source LOC):** Counts only executable lines
- **KLOC:** Thousands of Lines of Code
- **LLOC:** Logical LOC (counts statements)

**Formulas:**

```
Productivity  = KLOC / Person-Month
Error Rate    = Defects / KLOC
Cost/LOC      = Total Cost / LOC
```

**Limitations:** LOC varies by programming language, doesn't measure quality.

---

#### B. Function Point (FP)

Measures software size based on **functionality delivered to the user**, independent of programming language.

**5 Function Types:**

| Type | Description | Simple | Average | Complex |
|---|---|---|---|---|
| EI (External Input) | User inputs to system | 3 | 4 | 6 |
| EO (External Output) | System outputs to user | 4 | 5 | 7 |
| EQ (External Inquiry) | User queries (no update) | 3 | 4 | 6 |
| ILF (Internal Logical File) | Internal data files | 7 | 10 | 15 |
| EIF (External Interface File) | External data files | 5 | 7 | 10 |

**Formula:**
```
UFP = Σ (count × weight for each function type)
FP  = UFP × (0.65 + 0.01 × Σ Fi)
```
*Where Fi = 14 complexity adjustment factors (0-5 each)*

**Simplified:** FP ≈ UFP × CAF (Complexity Adjustment Factor, typically 0.65–1.35)

---

#### C. Cyclomatic Complexity

Measures the **complexity of a program's control flow**. Developed by Thomas McCabe.

**Formula:**
```
V(G) = E - N + 2P

Where:
E = Number of edges in control flow graph
N = Number of nodes in control flow graph
P = Number of connected components (usually 1)
```

**Alternative Formula (easier):**
```
V(G) = Number of decision points (IF, WHILE, FOR, CASE) + 1
```

**Interpretation:**

| V(G) Value | Risk Level | Action |
|---|---|---|
| 1-10 | Low risk | Simple program |
| 11-20 | Moderate risk | Review carefully |
| 21-50 | High risk | Restructure required |
| > 50 | Very high risk | Major redesign needed |

---

### 3. Steps / Methodology

**For LOC:**
1. Count total lines in the program
2. Exclude blank lines and comments (for SLOC)
3. Divide by 1000 for KLOC
4. Apply productivity/error formulas

**For FP:**
1. Count EI, EO, EQ, ILF, EIF items
2. Assign complexity weights
3. Calculate UFP = sum of (count × weight)
4. Apply CAF to get final FP

**For Cyclomatic Complexity:**
1. Draw the control flow graph or
2. Count all decision points (IF, WHILE, FOR, SWITCH-CASE) in code
3. Add 1 to get V(G)

---

### 4. Diagram / Representation

**Control Flow Graph Example:**

```
For code with IF, WHILE loop:

    ┌─────┐
    │  1  │ ─────▶ Node 1: Start
    └──┬──┘
       ▼
    ┌─────┐
    │  2  │ ─────▶ Node 2: IF condition (Decision)
    └──┬──┘
   YES │   NO
    ┌──▼──┐  ┌─────┐
    │  3  │  │  4  │
    └──┬──┘  └──┬──┘
       └────┬───┘
            ▼
         ┌─────┐
         │  5  │ ─────▶ End
         └─────┘

Edges (E) = 5, Nodes (N) = 5, P = 1
V(G) = 5 - 5 + 2(1) = 2
```

---

### 5. Example / Solution

#### a) LOC – College Automation System (Student Login Module)

```python
# Student Login Function (Python)
def student_login(username, password):           # Line 1
    db = connect_database()                      # Line 2
    user = db.query(username)                    # Line 3
    if user is None:                             # Line 4
        return "User not found"                  # Line 5
    if user.password != hash(password):          # Line 6
        return "Invalid password"                # Line 7
    session.create(user)                         # Line 8
    return "Login successful"                    # Line 9
```

| Metric | Value |
|---|---|
| Total LOC | 9 |
| SLOC (executable) | 8 (excluding function def line as non-executable logic) |
| KLOC | 0.009 |

If project has 500 similar functions: KLOC ≈ 500 × 0.009 = **4.5 KLOC**

**Productivity** (if 2 developers, 3 months): = 4.5 / 6 = **0.75 KLOC/person-month**

---

#### b) Function Point – College Automation System

| Function Type | Count | Weight | FP |
|---|---|---|---|
| EI (External Inputs) | 5 (login, add student, mark attendance, pay fee, add exam) | 4 | 20 |
| EO (External Outputs) | 4 (report card, receipt, attendance report, result) | 5 | 20 |
| EQ (External Inquiries) | 3 (view profile, check fee, view result) | 4 | 12 |
| ILF (Internal Logical Files) | 4 (Student DB, Attendance DB, Fee DB, Result DB) | 10 | 40 |
| EIF (External Interface Files) | 1 (SMS/Email gateway) | 7 | 7 |
| **UFP Total** | | | **99** |

```
CAF = 1.0 (assumed average complexity)
FP  = UFP × CAF = 99 × 1.0 = 99 Function Points
```

---

#### c) Cyclomatic Complexity – ATM Withdrawal (Banking System)

```
Code logic:
IF PIN correct
  IF amount > 0
    IF amount <= balance
      deduct and dispense
    ELSE
      insufficient balance
    END IF
  ELSE
    invalid amount
  END IF
ELSE
  wrong PIN
END IF
```

**Decision points:** 3 (three IF statements)

```
V(G) = Decision Points + 1 = 3 + 1 = 4
```

**Interpretation:** V(G) = 4 → **Low Risk** (simple, easy to test)

---

#### d) Summary Table

| Metric | College System | Banking System |
|---|---|---|
| KLOC (estimated) | 10 KLOC | 25 KLOC |
| Function Points | 99 FP | ~250 FP |
| Cyclomatic Complexity (avg module) | 4-6 | 8-12 |
| Complexity Risk | Low | Moderate |

---

### 6. Output / Result

**Result:** Software metrics have been successfully calculated. LOC gives a size estimate, Function Points measure functionality independent of language, and Cyclomatic Complexity measures code complexity. These metrics help in quality assessment, testing effort estimation, and resource planning.

---
---

## Assignment 14

### Find Maintainability Index and Reusability Index

---

### 1. Aim

To calculate and analyze the **Maintainability Index (MI)** and **Reusability Index (RI)** for software modules.

---

### 2. Theory

---

#### A. Maintainability Index (MI)

**Maintainability** refers to how easily software can be modified (bug fixing, improvement, adaptation).

The **Maintainability Index** is a composite metric that combines:
- **Halstead Volume (HV)** — size/complexity of code based on operators and operands
- **Cyclomatic Complexity (V(G))** — control flow complexity
- **LOC** — Lines of Code

**Formula (Microsoft Visual Studio version):**

```
MI = MAX(0, (171 - 5.2 × ln(HV) - 0.23 × V(G) - 16.2 × ln(LOC)) × 100 / 171)
```

**Simplified Microsoft formula:**
```
MI = 171 - 5.2 × log₂(V) - 0.23 × G - 16.2 × log₂(LOC)
```

Where:
- V = Halstead Volume
- G = Cyclomatic Complexity
- LOC = Lines of Code

**Interpretation:**

| MI Score | Maintainability | Meaning |
|---|---|---|
| 85-100 | High (Green) | Easy to maintain |
| 65-84 | Moderate (Yellow) | Acceptable |
| 0-64 | Low (Red) | Difficult to maintain |

---

#### Halstead Volume (V):

```
V = N × log₂(η)

Where:
N = Total operators + Total operands (N1 + N2)
η = Unique operators + Unique operands (η1 + η2)
```

---

#### B. Reusability Index (RI)

**Reusability** refers to the degree to which a software component can be used in multiple systems.

**Simple Reusability Index Formula:**

```
RI = (N_reused / N_total) × 100%

Where:
N_reused = Number of modules/components reused
N_total  = Total number of modules/components
```

**Factors that affect Reusability:**
- Low coupling (independent modules)
- High cohesion (focused modules)
- Good documentation
- Generalized (not specific to one use case)
- Well-tested

---

### 3. Steps / Methodology

**For Maintainability Index:**
1. Count operators and operands in the code
2. Calculate Halstead Volume (V)
3. Calculate Cyclomatic Complexity (V(G))
4. Count LOC
5. Apply MI formula
6. Interpret the result

**For Reusability Index:**
1. List all modules in the system
2. Identify which modules can be/are reused
3. Calculate RI = (reused / total) × 100

---

### 4. Diagram / Representation

```
Code Module
    │
    ├──▶ Count Operators/Operands ──▶ Halstead Volume (V)
    │
    ├──▶ Count Decision Points ──────▶ Cyclomatic Complexity (G)
    │
    ├──▶ Count Lines ─────────────────▶ LOC
    │
    └──▶ Apply Formula ───────────────▶ Maintainability Index
```

---

### 5. Example / Solution

#### a) Maintainability Index – College Automation System (Login Module)

**Given Code Module:**
```python
def student_login(username, password):
    user = db.get_user(username)
    if user is None:
        return False
    if user.password == hash_password(password):
        return True
    return False
```

**Counting:**

| Item | Count |
|---|---|
| Operators (if, ==, return, =) | η1 = 4 unique, N1 = 6 total |
| Operands (user, username, password, None, False, True) | η2 = 6 unique, N2 = 9 total |

```
N = N1 + N2 = 6 + 9 = 15
η = η1 + η2 = 4 + 6 = 10

Halstead Volume:
V = N × log₂(η) = 15 × log₂(10) = 15 × 3.32 = 49.8

Cyclomatic Complexity:
V(G) = Decision points + 1 = 2 + 1 = 3

LOC = 7 (executable lines)

MI = 171 - 5.2 × log₂(49.8) - 0.23 × 3 - 16.2 × log₂(7)
   = 171 - 5.2 × 5.64  - 0.23 × 3 - 16.2 × 2.81
   = 171 - 29.33 - 0.69 - 45.52
   = 95.46
```

**MI = 95.46 → HIGH Maintainability (Green) ✓**

---

#### b) Reusability Index – College Automation System

| Module | Reusable? | Reason |
|---|---|---|
| Authentication Module | ✓ Yes | Can be reused in any web system |
| Email Notification | ✓ Yes | Generic email sender |
| Database Connection | ✓ Yes | Generic DB utility |
| Attendance Module | ✗ No | Specific to college domain |
| Fee Calculation | ✗ No | College-specific logic |
| Report Generator | ✓ Yes | Generic PDF generator |
| Student Registration | ✗ No | College-specific |
| Library Management | ✗ No | Domain-specific |

```
N_total  = 8 modules
N_reused = 4 modules (Auth, Email, DB, Report)

RI = (4 / 8) × 100 = 50%
```

**RI = 50% → Moderate Reusability**

---

#### c) Maintainability Index – Banking System (Transfer Module)

**Simplified Calculation (assumed values):**

```
LOC = 35
V(G) = 8 (multiple decision points for validations)
V (Halstead Volume) = 230 (estimated for 35 LOC)

MI = 171 - 5.2 × log₂(230) - 0.23 × 8 - 16.2 × log₂(35)
   = 171 - 5.2 × 7.85 - 0.23 × 8 - 16.2 × 5.13
   = 171 - 40.82 - 1.84 - 83.11
   = 45.23
```

**MI = 45.23 → LOW Maintainability (Red) ⚠**

*This suggests the transfer module needs to be simplified/refactored.*

---

#### d) Reusability Index – Banking Management System

| Module | Reusable? |
|---|---|
| Authentication | ✓ Yes |
| OTP Generator | ✓ Yes |
| Email/SMS Service | ✓ Yes |
| PDF Statement Generator | ✓ Yes |
| Account Management | ✗ No |
| Loan Calculator | ✗ No |
| Transaction Processing | ✗ No |
| Branch Management | ✗ No |
| Interest Calculator | ✓ Yes |

```
N_total  = 9
N_reused = 5

RI = (5 / 9) × 100 = 55.6%
```

**RI = 55.6% → Moderate Reusability**

---

### 6. Output / Result

**Result:** Maintainability Index and Reusability Index have been calculated for both systems. The College Automation login module has high maintainability (95.46), while the Banking transfer module needs improvement (45.23). Reusability is moderate (~50-55%) in both systems. These metrics guide developers to improve code quality.

---
---

## Assignment 15

### Using CASE Tool – Find Number of Statements, Depth, and Complexity

---

### 1. Aim

To use a **CASE (Computer-Aided Software Engineering) tool** to analyze a small program and find the **number of statements**, **nesting depth**, and **cyclomatic complexity**.

---

### 2. Theory

**CASE Tools** are software applications that assist in software development activities such as design, coding, analysis, and testing.

**Types of CASE Tools:**

| Type | Description | Examples |
|---|---|---|
| Upper CASE | Requirements, design | Enterprise Architect, Rational Rose |
| Lower CASE | Coding, testing | Eclipse, Visual Studio |
| Integrated CASE | Full lifecycle | IBM Rational Suite |
| Metrics Tools | Code analysis | SonarQube, PyMetrics, Understand |

**What CASE Metric Tools Measure:**

| Metric | Definition |
|---|---|
| Number of Statements | Total executable statements in the code |
| Nesting Depth | Maximum depth of nested control structures (IF inside IF, etc.) |
| Cyclomatic Complexity | V(G) = Decision points + 1 |

---

**Nesting Depth:**
- Depth 1: A single IF or loop
- Depth 2: An IF inside a loop
- Depth 3: An IF inside a loop inside another IF, etc.

High nesting depth → hard to read and test → poor quality

---

### 3. Steps / Methodology

1. Write a small program (or take existing module)
2. Open in CASE/Metrics tool (e.g., **SonarQube**, **PyMetrics**, or manually)
3. Analyze the code to find:
   - **Statements count** — count executable lines
   - **Nesting depth** — count maximum levels of nesting
   - **Cyclomatic Complexity** — count decision points + 1
4. Interpret results and suggest improvements

*Note: For this practical, we will **manually simulate** what a CASE tool would report.*

---

### 4. Diagram / Representation

**Nesting Depth Visual:**

```
Depth 1:
  IF condition:         ──▶ Depth = 1
    statement

Depth 2:
  FOR loop:             ──▶ Depth = 1
    IF condition:       ──▶ Depth = 2
      statement

Depth 3:
  WHILE loop:           ──▶ Depth = 1
    IF condition:       ──▶ Depth = 2
      FOR loop:         ──▶ Depth = 3
        statement
```

---

### 5. Example / Solution

#### Sample Program – Student Fee Calculation (College System)

```python
def calculate_fee(student_id, semester):           # Statement 1
    student = get_student(student_id)              # Statement 2
    if student is None:                            # Statement 3  [D1]
        return "Student not found"                 # Statement 4
    
    base_fee = 15000                               # Statement 5
    
    if semester <= 2:                              # Statement 6  [D2]
        fee = base_fee                             # Statement 7
    elif semester <= 4:                            # Statement 8  [D3]
        fee = base_fee + 2000                      # Statement 9
    elif semester <= 6:                            # Statement 10 [D4]
        fee = base_fee + 4000                      # Statement 11
    else:                                          # 
        fee = base_fee + 6000                      # Statement 12
    
    if student.category == "SC/ST":               # Statement 13 [D5]
        if student.income < 200000:               # Statement 14 [D6] (Depth 2)
            fee = fee * 0.5                        # Statement 15
        elif student.income < 500000:             # Statement 16 [D7]
            fee = fee * 0.75                       # Statement 17
    
    if student.sports_quota:                      # Statement 18 [D8]
        fee = fee - 1000                           # Statement 19
    
    return fee                                     # Statement 20
```

---

**CASE Tool Analysis Report (Simulated):**

| Metric | Value | Analysis |
|---|---|---|
| **Total Lines** | 20 | Including all lines |
| **Executable Statements** | 18 | Excluding function definition line |
| **Comments** | 0 | No comments (should add) |
| **Maximum Nesting Depth** | 2 | (IF inside IF for SC/ST check) |
| **Decision Points** | 8 | (D1 through D8 marked above) |
| **Cyclomatic Complexity V(G)** | 9 | = 8 decision points + 1 |

---

**How Nesting Depth = 2 was found:**

```
Level 0: Function body
Level 1: if student.category == "SC/ST":       ← Depth 1
Level 2:     if student.income < 200000:        ← Depth 2 (Maximum!)
                 fee = fee * 0.5
```

---

**Cyclomatic Complexity Calculation:**

```
Decision Points:
1. if student is None
2. if semester <= 2
3. elif semester <= 4
4. elif semester <= 6
5. if student.category == "SC/ST"
6. if student.income < 200000
7. elif student.income < 500000
8. if student.sports_quota

V(G) = 8 + 1 = 9
```

**Interpretation:** V(G) = 9 → **Low Risk** (Within acceptable range of 1-10)

---

#### Sample Program – Bank Account Balance Check (Banking System)

```java
public double checkBalance(String accountNo, String pin) {  // Statement 1
    Account acc = database.findAccount(accountNo);          // Statement 2
    if (acc == null) {                                       // Statement 3  [D1]
        throw new Exception("Account not found");           // Statement 4
    }
    if (!acc.verifyPin(pin)) {                              // Statement 5  [D2]
        if (acc.getFailedAttempts() >= 3) {                 // Statement 6  [D3] Depth 2
            acc.blockAccount();                             // Statement 7
            throw new Exception("Account blocked");         // Statement 8
        }
        acc.incrementFailedAttempts();                      // Statement 9
        throw new Exception("Wrong PIN");                   // Statement 10
    }
    acc.resetFailedAttempts();                              // Statement 11
    return acc.getBalance();                                // Statement 12
}
```

**CASE Tool Report (Simulated):**

| Metric | Value |
|---|---|
| **Total Statements** | 12 |
| **Executable Statements** | 11 |
| **Maximum Nesting Depth** | 2 |
| **Decision Points** | 3 |
| **Cyclomatic Complexity V(G)** | 4 |
| **Maintainability** | High |

---

**Summary of Both Programs:**

| Program | Statements | Nesting Depth | V(G) | Complexity Level |
|---|---|---|---|---|
| Fee Calculation (College) | 18 | 2 | 9 | Low Risk ✓ |
| Balance Check (Banking) | 11 | 2 | 4 | Low Risk ✓ |

---

**CASE Tool Used:** SonarQube (or PyMetrics for Python) / Manual simulation
**Language:** Python / Java

---

### 6. Output / Result

**Result:** Using CASE tool analysis (simulated), the following metrics were obtained:

- **Fee Calculation Module:** 18 statements, depth = 2, complexity = 9 (Low Risk)
- **Balance Check Module:** 11 statements, depth = 2, complexity = 4 (Low Risk)

Both modules are within acceptable complexity limits. The nesting depth of 2 is manageable and does not pose a readability or maintenance concern. These metrics confirm that the code is well-structured and maintainable.

---

---

## Summary Table – All 15 Assignments

| Assignment | Topic | Systems Covered |
|---|---|---|
| 1 | Project Scope & Objectives | College, Banking |
| 2 | SRS Document | College, Banking |
| 3 | UML Use Case Diagram | College, Banking |
| 4 | Class Diagram | College, Banking |
| 5 | Project Scheduling (Gantt Chart) | College, Banking |
| 6 | Effort, Schedule & Cost Estimation (COCOMO) | College, Banking |
| 7 | DFD Level 0, Level 1 & Data Dictionary | College, Banking |
| 8 | Sequence Diagram | College, Banking |
| 9 | Structured Design (Structure Chart) | College, Banking |
| 10 | Waterfall, Prototype & Spiral Models | College, Banking |
| 11 | Best Model Selection with Reasoning | College, Banking |
| 12 | Algorithm & Flowchart | College, Banking |
| 13 | LOC, Function Point & Cyclomatic Complexity | College, Banking |
| 14 | Maintainability Index & Reusability Index | College, Banking |
| 15 | CASE Tool — Statements, Depth, Complexity | College, Banking |

---

*Practical File Prepared By: ___________________________*
*Roll No.: _____________________________________________*
*BCA — Sri Sukhmani Institute of Hospitality and Management*
