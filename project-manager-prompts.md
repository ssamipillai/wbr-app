# Project Manager Prompts for WBR Application

## 1. Project Overview & Requirements Analysis

**Prompt:** "Analyze and define the requirements for a Weekly Business Review (WBR) application that transforms CSV business data into interactive HTML reports using YAML configuration files. The system should support:

- CSV data ingestion with date-based time series
- YAML configuration for report structure and metrics
- Multiple chart types (6-week/12-month charts, tables)
- Report publishing with optional password protection
- Cloud storage integration (S3, GCP, Azure)
- RESTful API for programmatic access

Define functional requirements, non-functional requirements, user stories, and acceptance criteria. Include data flow diagrams and system boundaries."

## 2. Architecture & Technology Stack Planning

**Prompt:** "Design a technology-agnostic architecture for a data visualization application with these components:

**Core Requirements:**
- Web-based report generation from CSV + YAML inputs
- Real-time chart rendering with interactive features
- File upload and processing capabilities
- Report sharing and publishing system
- Multi-cloud storage support
- API-first design

**Constraints:**
- Must handle time-series business data
- Support multiple aggregation functions (sum, mean, min, max)
- Generate both weekly and monthly views
- Support fiscal year configurations
- Enable password-protected sharing

Create architectural diagrams, component specifications, and technology recommendations that could be implemented in any modern tech stack."

## 3. Project Planning & Milestone Definition

**Prompt:** "Create a comprehensive project plan for building a business intelligence reporting application with the following phases:

**Phase 1:** Core Data Processing
- CSV parsing and validation
- YAML configuration processing
- Basic metric calculations
- Data aggregation engine

**Phase 2:** Visualization Engine
- Chart generation system
- Table rendering
- Interactive dashboard creation
- Export capabilities

**Phase 3:** Web Application
- File upload interface
- Report generation UI
- User management
- Publishing system

**Phase 4:** API & Integration
- RESTful API development
- Cloud storage integration
- Authentication system
- Deployment automation

Define deliverables, timelines, dependencies, risk mitigation strategies, and resource allocation for each phase."

## 4. Stakeholder Communication Plan

**Prompt:** "Develop a stakeholder communication strategy for a business reporting application project involving:

**Primary Users:**
- Business analysts creating weekly reports
- Executives consuming dashboard data
- IT administrators managing deployments

**Technical Stakeholders:**
- Development team
- DevOps engineers
- Security team
- Data governance team

Create communication templates, status reporting formats, demo schedules, and feedback collection mechanisms. Include change management processes for evolving requirements."

## 5. Quality Assurance & Testing Strategy

**Prompt:** "Design a comprehensive QA strategy for a data visualization application that processes business metrics. Include:

**Testing Levels:**
- Unit testing for data processing functions
- Integration testing for file processing workflows
- End-to-end testing for report generation
- Performance testing for large datasets
- Security testing for data protection

**Test Data Management:**
- Sample CSV datasets with various scenarios
- YAML configuration test cases
- Edge case handling (missing data, invalid formats)
- Load testing scenarios

Define testing phases, acceptance criteria, and quality gates for each development milestone."