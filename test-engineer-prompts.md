# Test Engineer Prompts for WBR Application

## 1. Test Strategy & Planning

**Prompt:** "Develop a comprehensive test strategy for a business intelligence reporting application that processes CSV data and generates interactive reports:

**Testing Scope:**
- Data ingestion and validation
- YAML configuration processing
- Metric calculations and aggregations
- Chart generation and rendering
- Report publishing and sharing
- API functionality and integration
- Security and access controls

**Test Types Required:**
- Functional testing (positive/negative scenarios)
- Data integrity testing
- Performance and load testing
- Security and penetration testing
- Usability and accessibility testing
- Cross-browser and device testing
- API contract testing

Create test plans that cover all user journeys, edge cases, and system boundaries with clear pass/fail criteria."

## 2. Test Data Management & Generation

**Prompt:** "Design a comprehensive test data strategy for a reporting application that handles time-series business metrics:

**Test Data Categories:**
- Valid CSV datasets with various business scenarios
- Invalid/malformed data for error handling tests
- Large datasets for performance testing
- Edge cases (missing dates, duplicate entries, special characters)
- YAML configurations for different report types
- Historical data spanning multiple fiscal years

**Data Generation Requirements:**
- Automated test data generation
- Realistic business metric patterns
- Configurable data volumes and complexity
- Data privacy and anonymization
- Test data versioning and management
- Cleanup and reset procedures

Build a system that provides consistent, reliable test data while supporting various testing scenarios."

## 3. Automated Testing Framework

**Prompt:** "Implement a robust automated testing framework for a web-based reporting application:

**Automation Scope:**
- Unit tests for data processing functions
- API testing with various input scenarios
- UI automation for report generation workflows
- Database testing for data integrity
- File upload and processing automation
- Cross-browser testing automation

**Framework Requirements:**
- Page Object Model for UI tests
- Data-driven testing capabilities
- Parallel test execution
- Test reporting and analytics
- CI/CD integration
- Flaky test detection and handling
- Test maintenance and refactoring support

Design frameworks that are maintainable, scalable, and provide fast feedback on application quality."

## 4. Performance & Load Testing

**Prompt:** "Design comprehensive performance testing for a data processing and visualization application:

**Performance Test Scenarios:**
- Single user report generation with various data sizes
- Concurrent user load testing (10, 50, 100+ users)
- Large file upload and processing performance
- Database query performance under load
- Chart rendering performance with complex datasets
- API response times under various loads

**Metrics & Monitoring:**
- Response time percentiles (50th, 95th, 99th)
- Throughput and requests per second
- Resource utilization (CPU, memory, disk, network)
- Error rates and failure patterns
- Scalability limits and bottlenecks
- Recovery time after failures

Create performance test suites that identify bottlenecks and validate system scalability requirements."

## 5. Security Testing Framework

**Prompt:** "Develop a comprehensive security testing approach for a business data visualization platform:

**Security Test Areas:**
- Input validation and injection attacks
- Authentication and authorization testing
- File upload security (malicious files, size limits)
- Data encryption and transmission security
- Session management and timeout testing
- API security and rate limiting
- Report sharing and access control testing

**Testing Techniques:**
- Static code analysis integration
- Dynamic security scanning
- Penetration testing scenarios
- Vulnerability assessment
- Security regression testing
- Compliance validation (GDPR, SOX)

Build security testing that integrates into the development lifecycle and provides continuous security validation."

## 6. Integration & End-to-End Testing

**Prompt:** "Create comprehensive integration testing for a multi-component reporting system:

**Integration Test Scenarios:**
- File upload → processing → report generation workflow
- API integrations with external data sources
- Cloud storage integration testing
- Email notification and sharing workflows
- Database integration and data consistency
- Third-party service integrations

**E2E Test Coverage:**
- Complete user journeys from data upload to report sharing
- Multi-user collaboration scenarios
- Error recovery and system resilience
- Cross-system data flow validation
- Business process automation testing
- Disaster recovery testing

Design tests that validate the entire system works cohesively and meets business requirements."

## 7. Test Reporting & Quality Metrics

**Prompt:** "Implement a comprehensive test reporting and quality metrics system:

**Quality Metrics:**
- Test coverage (code, functional, requirements)
- Defect density and escape rates
- Test execution efficiency and automation rates
- Performance benchmarks and trends
- Security vulnerability tracking
- User acceptance and satisfaction metrics

**Reporting Requirements:**
- Real-time test execution dashboards
- Quality trend analysis and reporting
- Risk assessment and mitigation tracking
- Release readiness reports
- Stakeholder communication templates
- Continuous improvement recommendations

Create reporting systems that provide actionable insights for development teams and stakeholders."

## 8. Mobile & Cross-Platform Testing

**Prompt:** "Design testing strategies for ensuring the reporting application works across all platforms and devices:

**Platform Coverage:**
- Desktop browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Android Chrome)
- Tablet optimization testing
- Progressive Web App functionality
- Responsive design validation
- Touch interface testing

**Testing Approaches:**
- Device farm integration for real device testing
- Emulator and simulator testing
- Visual regression testing across platforms
- Performance testing on various devices
- Accessibility testing on different platforms
- Network condition testing (slow connections, offline)

Build testing strategies that ensure consistent user experience across all supported platforms and devices."