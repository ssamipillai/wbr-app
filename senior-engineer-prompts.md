# Senior Software Engineer Prompts for WBR Application

## 1. Data Processing Engine Development

**Prompt:** "Implement a robust data processing engine for business metrics with these specifications:

**Core Processing Requirements:**
- Parse CSV files with automatic schema detection
- Handle various date formats and time zones
- Implement aggregation functions: sum, mean, min, max, first, last
- Support filtered aggregations with query expressions
- Calculate time-based comparisons (WoW, MoM, YoY)
- Generate box totals for summary statistics

**Technical Implementation:**
- Design extensible aggregation framework
- Implement efficient time-series calculations
- Handle missing data and edge cases
- Support custom fiscal year configurations
- Optimize for large dataset processing
- Include comprehensive error handling

Create modular, testable code with clear separation of concerns and proper abstraction layers."

## 2. Configuration Management System

**Prompt:** "Build a flexible configuration management system that processes YAML files to define report structures:

**Configuration Features:**
- Metric definitions with column mappings
- Chart configuration (types, styling, axes)
- Table layouts and formatting
- Function-based metric calculations
- Conditional logic and filters
- Validation and error reporting

**Implementation Requirements:**
- Schema validation for YAML configurations
- Dynamic metric calculation engine
- Support for nested configurations
- Configuration inheritance and overrides
- Real-time validation feedback
- Migration support for configuration changes

Design a system that balances flexibility with type safety and provides clear error messages for configuration issues."

## 3. Chart Generation & Visualization Engine

**Prompt:** "Develop a comprehensive chart generation system supporting multiple visualization types:

**Chart Types Required:**
- 6-week + 12-month combination charts
- Time-series line charts with dual axes
- Data tables with custom formatting
- Summary statistics boxes
- Target vs actual comparisons
- Embedded content support

**Technical Features:**
- Responsive design for multiple screen sizes
- Interactive tooltips and legends
- Custom formatting (currency, percentages, scaling)
- Export capabilities (PNG, PDF, SVG)
- Real-time data updates
- Accessibility compliance

Build a modular visualization framework that can be extended with new chart types and supports theming and customization."

## 4. File Processing & Upload System

**Prompt:** "Implement a robust file processing system handling CSV and YAML uploads:

**File Processing Features:**
- Multi-format file upload (drag-drop, browse, URL)
- Progress tracking for large files
- File validation and error reporting
- Temporary file management
- Virus scanning integration
- File size and type restrictions

**Processing Pipeline:**
- Asynchronous file processing
- Queue management for batch operations
- Error recovery and retry logic
- Processing status notifications
- File cleanup and garbage collection
- Audit logging for file operations

Design a system that handles concurrent uploads efficiently while maintaining data integrity and security."

## 5. Report Publishing & Sharing System

**Prompt:** "Build a comprehensive report publishing system with sharing capabilities:

**Publishing Features:**
- Generate shareable URLs for reports
- Password protection for sensitive data
- Expiration dates for shared reports
- Custom branding and themes
- Print-optimized layouts
- Mobile-responsive design

**Technical Implementation:**
- Secure URL generation with tokens
- Report caching and optimization
- Access control and permissions
- Analytics for report usage
- Bulk publishing operations
- Integration with external systems

Create a system that balances ease of sharing with security and provides detailed access controls."

## 6. API Development & Integration Layer

**Prompt:** "Develop a comprehensive RESTful API for programmatic access to the reporting platform:

**API Endpoints Required:**
- Data upload and processing
- Report generation (sync/async)
- Configuration management
- Publishing and sharing
- User management
- System administration

**Technical Requirements:**
- OpenAPI specification compliance
- Request/response validation
- Rate limiting and throttling
- Comprehensive error handling
- API versioning strategy
- Authentication and authorization
- Webhook support for notifications

Build APIs that are intuitive for developers while maintaining security and performance standards."

## 7. Testing & Quality Assurance Framework

**Prompt:** "Implement a comprehensive testing framework covering all aspects of the application:

**Testing Layers:**
- Unit tests for data processing functions
- Integration tests for file workflows
- End-to-end tests for report generation
- Performance tests for large datasets
- Security tests for data protection
- API contract testing

**Test Data Management:**
- Generate realistic test datasets
- Create edge case scenarios
- Mock external dependencies
- Test data cleanup and isolation
- Continuous testing in CI/CD
- Test reporting and metrics

Design testing strategies that ensure reliability while maintaining fast feedback loops for development teams."