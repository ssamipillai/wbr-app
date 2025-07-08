# Software Architect Prompts for WBR Application

## 1. System Architecture Design

**Prompt:** "Design a scalable, microservices-based architecture for a business intelligence reporting platform with these requirements:

**Core Services Needed:**
- Data ingestion service (CSV processing)
- Configuration management service (YAML parsing)
- Metrics calculation engine
- Chart generation service
- Report publishing service
- File storage abstraction layer

**Technical Requirements:**
- Support for multiple data aggregation methods
- Real-time chart rendering
- Configurable fiscal year calculations
- Multi-tenant data isolation
- Horizontal scalability
- Cloud-agnostic deployment

Design service boundaries, data flow patterns, API contracts, and inter-service communication strategies. Include caching strategies and data consistency patterns."

## 2. Data Architecture & Processing Pipeline

**Prompt:** "Architect a robust data processing pipeline for time-series business metrics with these capabilities:

**Data Flow Requirements:**
- CSV ingestion with schema validation
- Time-series data normalization
- Multiple aggregation functions (sum, mean, min, max, first, last)
- Fiscal year and calendar year calculations
- Week-over-week, month-over-month, year-over-year comparisons
- Box total calculations for summary statistics

**Processing Patterns:**
- Stream processing for real-time updates
- Batch processing for historical data
- Data transformation and enrichment
- Error handling and data quality checks

Design the data models, transformation logic, and storage patterns that support both operational and analytical workloads."

## 3. API Design & Integration Patterns

**Prompt:** "Design a comprehensive API strategy for a reporting platform that supports:

**API Categories:**
- Data ingestion APIs (file upload, URL-based data sources)
- Report generation APIs (synchronous and asynchronous)
- Configuration management APIs
- Publishing and sharing APIs
- Administrative APIs

**Integration Requirements:**
- RESTful API design with proper HTTP semantics
- File upload handling with progress tracking
- Webhook support for external integrations
- Rate limiting and throttling
- API versioning strategy
- Authentication and authorization patterns

Create OpenAPI specifications, error handling patterns, and client SDK requirements."

## 4. Security Architecture

**Prompt:** "Design a comprehensive security architecture for a business data visualization platform handling sensitive corporate metrics:

**Security Domains:**
- Data protection (encryption at rest and in transit)
- Access control (RBAC, data isolation)
- Authentication (multi-factor, SSO integration)
- API security (rate limiting, input validation)
- Report sharing security (password protection, expiration)

**Compliance Requirements:**
- Data privacy regulations (GDPR, CCPA)
- Corporate data governance
- Audit logging and monitoring
- Secure file handling
- Cloud security best practices

Define security controls, threat modeling, and compliance frameworks."

## 5. Scalability & Performance Architecture

**Prompt:** "Architect a high-performance system for processing large business datasets and generating interactive reports:

**Performance Requirements:**
- Handle CSV files up to 100MB
- Generate reports with 1000+ data points
- Support 100+ concurrent users
- Sub-second chart rendering
- Efficient caching strategies

**Scalability Patterns:**
- Horizontal scaling for compute-intensive operations
- Database sharding for multi-tenant data
- CDN integration for static assets
- Asynchronous processing for long-running operations
- Auto-scaling based on demand

Design caching layers, database optimization strategies, and monitoring approaches for performance visibility."

## 6. Cloud Architecture & Deployment Strategy

**Prompt:** "Design a cloud-native architecture that supports deployment across multiple cloud providers (AWS, GCP, Azure):

**Cloud Services Integration:**
- Object storage abstraction (S3, Cloud Storage, Blob Storage)
- Container orchestration (Kubernetes)
- Serverless computing options
- Managed database services
- Content delivery networks

**Deployment Patterns:**
- Infrastructure as Code (IaC)
- CI/CD pipeline design
- Blue-green deployment strategies
- Disaster recovery and backup
- Multi-region deployment

Create deployment architectures that maximize cloud-native benefits while maintaining portability."