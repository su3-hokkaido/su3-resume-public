# Japanese SaaS Company (November 2021 - Present)

## Summary

I belonged to a development organization for back-office SaaS products, primarily working on development teams for financial accounting products.

As an engineering manager, engineering leader, and architect, I was stationed in Ho Chi Minh City, Vietnam for three years after joining, responsible for rebuilding the Vietnam development team.
After returning to Japan, I spent about six months until my childcare leave working on rebuilding a new service development team, promoting from PoC phase to beta development, and completing patent application as the technical lead for patent applications related to the core architecture of the new service.

Note that during the period from August 2025 to August 2026, I was on childcare leave and had no work history at this company.

## Products Managed

### Cloud Series New Service

#### Overview

This is a new service launch project selected as an investment target by the business division.
The specific content of the new service is confidential and cannot be disclosed here.

Previously, the team was run by existing Japanese members, but planning and development had not progressed for nearly two years.
The company selected it as an investment target to strengthen the service, and from December 2024, a manager from the global member team at headquarters, myself from the Vietnam product development team, two young non-JP developers, and two product managers—a total of 6 people—newly joined, starting as a team of nearly 15 people in total.
Subsequently, members from India and Vietnam bases were added, forming a team of nearly 20 people, and I led that team.

As a team, we had little experience launching new services, and most members had primarily worker experience with limited project management experience. Therefore, I mainly acted as project manager and architect, writing code initially to get things started, but rarely performed actual construction work.
Also, I took childcare leave from August 2025, leaving midway through the project, but I believe I was able to make sufficient progress in a short period by rebuilding the team to be self-sustaining and showing the path to release.

#### Job Description

- Position: Engineering Group Leader
- Participation Period: December 2024 - July 2025
- Responsibilities:
    - Project management (planning, progress, issues, risks)
    - System architecture design
    - PR review
    - Quality review
    - Process establishment
    - Member development

#### Team Structure

- PdM: 2
- EM: 1
- Engineering Group Leader: 1
- Engineers: 11 (Japan 2 + Europe 2 + India 4 + Vietnam 3)
- QA: 1
- Designer: 1

#### Technology Stack

- golang
- TypeScript
- Github
- CircleCI
- ArgoCD
- DataDog
- Vault
- Cloudflare
- MySQL
- Docker
- k8s
- AWS various services (Cloudfront, Route53, ElastiCache/Redis, S3, kafka, Glue, Athena, Route53, EC2, EKS, ECS)


### Cloud Invoice Product

#### Overview

Originally, the invoice product developed in Japan was transferred to Vietnam, and I was responsible for planning, service operations, and development management with one product manager and myself as engineering manager.
While adopting a form close to Scrum for development, we positioned Vietnamese members as the main drivers and worked to enable them to become self-sustaining, while simultaneously working on legal reform responses, feature additions, improvements, and inquiry responses for the product.
Notably, I was able to experience what I consider necessary for service operations in two years, including Invoice System compliance, Peppol compliance, architecture renewal, public API renewal, migration of various microservices to AWS, and handling the largest split-brain incident in our company's history.
Currently, both the Japan and Vietnam sides have increased in number, and the range that teams can handle themselves has expanded, so I mainly handle architecture and various improvements that require deeper understanding and research, while supporting design reviews and management support so that each group within the product can properly execute projects.

#### Job Description

- Position: Engineering Manager
- Participation Period: November 2021 - December 2024
- Responsibilities:
    - Project management (planning, progress, issues, risks)
    - System architecture design
    - Inquiry response
    - PR review
    - Quality review
    - Process establishment
    - Member development
    - Incident commander or liaison
- Note
    - In principle, I do not write code and allocate resources to management work, but in some cases, I write code myself. (Cases where quick responses are possible or emergency responses where work members cannot be gathered)

#### Team Structure

- PdM: 1
- EM: 1
- Engineering Leader: 2 (Vietnam 1 + Japan 1)
- Backend: 8 (Vietnam 7 + Japan 1)
- Frontend: 3 (Vietnam 1 + Japan 2)
- QA: 3 (Vietnam 3)
- Designer: 1 (Japan 1)

#### Technology Stack

- Ruby on rails
- React
- TypeScript
- Sidekiq
- Github
- CircleCI
- ArgoCD
- DataDog
- Rollbar
- Grafana
- Vault
- Cloudflare
- MySQL
- k8s
- Linux
- BigQuery
- SendGrid
- AWS various services (ElastiCache, Redis, S3, Route53, EC2, DMS, Lambda, EKS, ECS)

#### Major Projects Experienced

- Centralized database separation (2021-2024)
- Invoice System compliance (2022-2023)
- Peppol compliance (2023)
- Credit card payment feature implementation (2023)
- Architecture renewal (k8s migration, AWS migration) (2023-2024)
- Public API renewal (2022-2023)
- WAF implementation (2023)
- OEM service closure (2022-2023)
- Monolith architecture improvement (2024-)

#### Major Incidents Experienced

- Split-brain incident response (2022)
- Large-scale request attack on public API (2022)
- Redis automatic update failure (2023)
- Service exposure due to member operation mistake (2023)
- Mail server attack response (2024)
- Existing architecture defect response (2021-2023)

#### Note

From 2021 to 2022, there were no experienced members, so I served as both incident commander and SME. From 2022 to around 2023, I mainly served as incident commander. From around 2024, I transferred the incident commander role to the development team and assumed the liaison role handling communication with VPoE and organization leaders.


### Cloud Company Incorporation Product

#### Overview

For a product developed in Vietnam, product operations became unstable due to the departure of highly skilled engineers in the past and changes in product managers more than 3 times in the past 2 years, so I joined as the engineering leader for rebuilding.
To avoid causing backlash and confusion by making a 180-degree change to the culture created by the current team, I gradually made improvements while introducing change points such as improving review processes, release restrictions, changing operation methods, and training product managers.

#### Job Description

- Position: Engineering Manager
- Participation Period: December 2023 - November 2024
- Responsibilities:
    - Project management coaching
    - System architecture design
    - PR review
    - Process establishment
    - Member development
    - Incident commander or liaison

#### Team Structure

- PdM: 1
- EM: 1
- Communicator: 1 (Vietnam 1)
- Engineering Leader: 1 (Vietnam 1)
- Backend: 4 (Vietnam 4)
- Mobile: 1 (Vietnam 1)
- Frontend: 0
- QA: 1 (Vietnam 1)
- Designer: 0

#### Technology Stack

- Ruby on rails
- React
- TypeScript
- Sidekiq
- Github, Github Actions
- CircleCI
- DataDog
- Rollbar
- Cloudflare
- Linux
- BigQuery
- AWS various services (ElastiCache, Redis, S3, Route53, EC2, SES, DMS, Lambda, ECS)

#### Major Projects Experienced

I did not specifically handle many projects, but partially participated in the following projects:

- IP address restriction, two-factor authentication implementation policy planning (resolving BASIC authentication)
- Production and staging environment difference resolution
- Ruby/rails major upgrade response plan
- Sidekiq implementation plan

#### Major Incidents Experienced

- Incident due to online table column addition (2024)
- Secondary incident due to other product incidents (2024)

----------------------------------------

# Vietnamese Local IT Offshore Company (May 2017 - September 2021)

## Summary

I joined a Vietnamese local company as the first Japanese employee and worked as a system consultant from an outsourcing standpoint, engaging in project management and organizational operations. I broadened my career by dealing and negotiating with a wide range of companies, expanding my capabilities as an engineer by working with diverse technologies, and gaining extensive experience from sales to engineering, as well as building overseas engineering organizations.

## Project Overview

### Attendance Management System for Specific Company (2,000 employees)

- Period: Approximately 1 year
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 3, QA 1, Bridge SE 1
- Technologies: WPF (C#), PostgreSQL

### Advanced Medical Center Ophthalmology Data Warehouse

- Period: Approximately 6 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 2, QA 1
- Technologies: WPF (C#), PostgreSQL

### New Development of Home Care/Nursing App for Long-term Care Support System Package

- Period: Approximately 1 year 6 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 7 (C# 5, Objective-C 2), QA 3, Interpreter 1, Infrastructure 1
- Technologies: Objective-C (for iOS app), .NET C# (desktop app), PostgreSQL, AWS (Cloudfront, Route53, EC2, ECS, ...)

### Chemical Information Data Search System

- Period: Approximately 6 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 2, QA 1
- Technologies: WPF (C#), PostgreSQL

### Drug Composition Table Management App

- Period: Approximately 6 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 3 (Android 1, iOS 1, .NET C# 1), QA 2
- Technologies: .NET C#, Kotlin, Swift, MySQL, SQLite

### Health Checkup Information Distribution App

- Period: Approximately 4 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 3, QA 1
- Technologies: Flutter, SQLite, PostgreSQL

### Health Checkup Support System

- Period: Approximately 10 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 5, QA 2
- Technologies: WPF (C#), MySQL, AWS

### Medical Questionnaire App

- Period: Approximately 3 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 3, QA 1
- Technologies: Flutter, SQLite, PostgreSQL

### Hospital Reservation Management App

- Period: Approximately 6 months
- Position: Project Manager
- Responsibilities: Requirements definition, design, quality assurance, release planning, etc.
- Team Structure: App engineers 3, QA 1
- Technologies: Flutter, SQLite, PostgreSQL

----------------------------------------

# Major SIer Company (April 2013 - March 2017)

## Summary

As a system engineer, I was primarily responsible for the implementation and development of internal information package systems (personnel management, payroll management, financial accounting management, etc.) for prefectural and municipal governments, as well as project management.
Specifically, I visited city and town halls to conduct requirement definition, requirements specification, and system implementation proposals. After receiving orders, I customized package systems according to the requirements of each municipality, built systems, and conducted system implementation training. I also performed follow-up and maintenance after system implementation, which I believe contributed to skill improvement in all aspects including sales, consulting, project management, development, and QA.

## Technology Stack
- COBOL
- Java
- Oracle DB
- Solaris
- Windows Server
- jcl (used for existing system investigation)
- VBA (used as auxiliary tools provided to users)

## Project Experience List

### Global HR Database Construction

- Period: July 2013 - September 2013
- Position: System Engineer (temporarily participated as a member)
- Responsibilities: DB data entry
- Team Structure: Unknown (approximately 200 people at peak)

### Prefectural Government Internal Information System Renewal

- Period: October 2013 - September 2014
- Position: Development Leader (temporary employee system functions)
- Responsibilities: Requirements definition, design, coding, testing, release, user education
- Team Structure: Approximately 100 people

### City Hall Personnel Payroll System Renewal

- Period: October 2014 - September 2015
- Position: Personnel Payroll Leader
- Responsibilities: Participated from negotiation phase, responsible for requirements definition to design, development, operation verification, operational support, and launch
- Team Structure: Manager 1, Members 4

### Personnel Payroll System Large-scale Legal Reform Response Project

- Period: April 2015 - October 2015
- Position: Development Center Overall Leader
- Responsibilities:
  - Hearing on systems from Cabinet Office and municipal mutual aid associations
  - System implementation policy planning, creation of business lists and business flows
  - Project progress management, issue management
  - Requirements definition, external design, internal design, development, testing, maintenance management
- Team Structure: Overall PM 1, Overall PMO 1, Field SE approximately 50 + Development center approximately 10

### Offshore Development Team Building

- Period: November 2015 - December 2016
- Position: PM
- Responsibilities: Requirements definition, design, coding, testing, and member education related to these
- Team Structure: Japan 3, Vietnam 6

### My Number BPO Service Implementation

- Period: January 2016 - September 2016
- Position: Consulting Leader
- Responsibilities: Requirements definition, BPO center education, user follow-up
- Team Structure: Consulting team 10, BPO center
- Note: Since it was possible to handle multiple companies in parallel, the number of companies handled is unknown. Supported implementation for approximately 30 companies.

### Package System Version Upgrade Development

- Period: September 2016 - March 2017
- Position: System Engineer
- Responsibilities: Requirements definition, design, coding, testing
- Team Structure: PKG development team approximately 50 people
