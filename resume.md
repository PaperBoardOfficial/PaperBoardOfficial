# Mohit Puri
hiremohitforsoftwarerole@gmail.com | [GitHub](https://github.com/PaperBoardOfficial) | [LinkedIn](https://linkedin.com/in/mohit-p-a18b5a342)

## Technical Skills
- **Languages**: Java, Python, JavaScript, TypeScript, Go
- **Frontend**: React.js, Vue.js, Next.js, React Native
- **Backend**: Spring Boot, Django, Node.js, FastAPI
- **Cloud & DevOps**: AWS (Lambda, S3, Cognito, API Gateway, CloudWatch, EC2), Kafka, RabbitMQ, Docker, Kubernetes, Jenkins
- **Databases**: MySQL, PostgreSQL, DynamoDB
- **Testing**: JUnit 5, Mockito, Playwright
- **Other**: Microservices, REST APIs, Multithreading, Distributed Systems, CI/CD Pipelines, Git, Object-Oriented Design

## Work Experience
### Software Engineer
**Paytm** | June 2022 - July 2024
- Awarded Rock Star recognition for outstanding contributions
- Mentored junior developers and led knowledge-sharing sessions on distributed systems and microservices architecture
- **Serverless File Transformation Service**:
  - Developed a service that transforms files across multiple formats (text, excel, csv, zip) from 100+ different banks with various payment modes (credit card, debit card, UPI, bank mandate)
  - Reduced operational costs to $15/month leveraging AWS Lambda
  - Minimized TAT from 3 hours to 15 minutes using multiprocessing/multithreading
  - Engineered solutions for processing 4GB+ compressed files (expanding to 12GB+ uncompressed) within Lambda's memory constraints using streaming and multipart uploads
  - Optimized Lambda cold start performance by implementing connection pooling for Kafka and database connections.
- **Payment Reconciliation Module (Re-engineered)**:
  - Migrated from EC2 to AWS Lambda, cutting costs by 33% (from $540 to $360/month)
  - Reduced code size by 50.75% utilizing JSR 380 and Jackson CSVMapper annotations
  - Achieved 85% test coverage with JUnit 5 and Mockito
  - Implemented validation checks that prevented potential fund losses by identifying reconciliation discrepancies
  - Managed critical financial reconciliation system handling transactions worth crores (tens of millions) of rupees daily
- **Kafka Migration**:
  - Migrated RabbitMQ producers/consumers to Kafka, implementing multithreading for efficiency
  - Enabled auto-retries and manual intervention using REST APIs
  - Built resilient distributed systems handling high throughput with Kafka
- **Gmail Attachment Downloader Service**:
  - Automated file downloads from Gmail to AWS S3, reducing manual effort for the finance team
- **Chargeback Dispute Resolution System**:
  - Improved critical APIs for Paytm's Payment Gateway enabling dispute resolution, document submission, and fund retention
  - Implemented robust validation checks to prevent potential fund losses during dispute processing
- **EMI Conversion System**:
  - Implemented configurable workflow system allowing real-time parameter adjustments without redeployment
  - Reduced processing time through optimized database queries and caching strategies
  - Integrated with multiple bank files to support various EMI conversion formats and requirements

### Software Engineer Intern
**Paytm** | January 2022 - June 2022
- Developed a React.js interface for JSON configuration updates
- Automated Jira ticket creation triggered by successful onboarding
- Collaborated with senior engineers on distributed system design and API integration

## Achievements
- Received job offer from **Flipkart** (Bengaluru) based on technical expertise and problem-solving skills
- Awarded Rock Star recognition at Paytm for outstanding contributions

## Open Source Contributions
### [Browser-Use](https://github.com/browser-use/browser-use) | Contributor
- Implemented drag-and-drop functionality for web automation, resolving multiple user issues ([PR #1208](https://github.com/browser-use/browser-use/pull/1208))
- Added browser extension support for ad-blocking and custom extensions ([PR #801](https://github.com/browser-use/browser-use/pull/801))
- Fixed screenshot flickering issues by dynamically adjusting window size based on screen resolution ([PR #740](https://github.com/browser-use/browser-use/pull/740))
- Enhanced PDF file streaming capabilities ([PR #626](https://github.com/browser-use/browser-use/pull/626))
- Improved click element action with retry mechanisms and navigation handling ([PR #726](https://github.com/browser-use/browser-use/pull/726))
- Added Slack integration for notifications ([PR #409](https://github.com/browser-use/browser-use/pull/409))
- Fixed DOM tree rendering issues for empty anchor tags ([PR #641](https://github.com/browser-use/browser-use/pull/641))

### [SuperGlue](https://github.com/superglue-ai/superglue) | Contributor
- Integrated Vercel AI SDK to support multiple LLM providers (OpenAI, Anthropic, Google Gemini, Mistral, xAI, DeepSeek) ([PR #80](https://github.com/superglue-ai/superglue/pull/80))

### [Novu](https://github.com/novuhq/novu) | Contributor
- Fixed UI bug with Intercom chat bubble visibility after closing integration sidebar ([PR #4951](https://github.com/novuhq/novu/pull/4951))

### [Surf.new](https://github.com/steel-dev/surf.new) | Contributor
- Implemented comprehensive Markdown rendering with support for tables, code blocks, and nested formatting ([PR #38](https://github.com/steel-dev/surf.new/pull/38))
- Added cross-platform compatibility for Windows users ([PR #33](https://github.com/steel-dev/surf.new/pull/33))
- Implemented linting configuration for consistent code style ([PR #34](https://github.com/steel-dev/surf.new/pull/34))

### [Repomix](https://github.com/yamadashy/repomix) | Contributor
- Added folder upload functionality with drag-and-drop support ([PR #387](https://github.com/yamadashy/repomix/pull/387))

## Technical Assignments & Projects
### [Bowtie Healthcare API](https://github.com/PaperBoardOfficial/bowtie-assignment)
- Developed a RESTful API for healthcare provider management using Django, Django REST Framework, and PostgreSQL
- Implemented Docker containerization with Docker Compose for easy deployment
- Created comprehensive API documentation with Swagger UI and ReDoc
- Utilized Redis for caching to improve performance of GET requests

### [Narrative File Processing System](https://github.com/PaperBoardOfficial/narrative-assignment)
- Built a scalable text processing application with Python backend and TypeScript frontend
- Implemented efficient file transformation service for handling multiple file formats
- Designed responsive UI for configuration management and monitoring

### [Scalex Book Management System](https://github.com/PaperBoardOfficial/scalex-assignment)
- Developed a Go-based book management system with authentication and authorization
- Achieved high test coverage with comprehensive unit tests
- Implemented CSV-based data storage with efficient data retrieval mechanisms

### [Dyte Browser Extension](https://github.com/PaperBoardOfficial/dyte-assignment)
- Created a Tampermonkey userscript to enhance web page functionality
- Implemented dynamic DOM manipulation and event handling
- Developed asynchronous JavaScript functions for improved user experience

### [PomoSpace](https://github.com/PaperBoardOfficial/PomoSpace) | Creator & Developer
- Developing a comprehensive productivity mobile application that combines Pomodoro technique, spaced repetition learning, and habit tracking
- Built with Expo, React Native, Zustand for state management, and NativeWind for styling
- Implementing features for time management, learning optimization, and habit formation in a single integrated platform
- Designed intuitive UI/UX to make productivity techniques accessible to users of all experience levels

### [Attendance Marker Tool](https://github.com/PaperBoardOfficial/attendance-marker)
- Developed a serverless AWS Lambda solution to automate daily attendance tracking for Paytm employees
- Implemented secure authentication using AWS Secrets Manager to store credentials
- Configured AWS EventBridge for scheduling automated punch-in/out operations
- Built notification system for success/failure alerts via email
- Saved colleagues from potential salary deductions by eliminating manual attendance marking errors
- Utilized Python with beautifulsoup for web automation and AWS CloudWatch for monitoring

## Education
### National Institute of Technology Jalandhar
**B.Tech. in Electronics and Communications (CGPA: 8.73)** | Minor in Computer Science | 2018 - 2022
- Secured All India Rank 8,513 in IIT-JEE Advanced and 13,813 in IIT-JEE Mains (2018)
- Relevant Coursework: Operating Systems, Databases, Computer Architecture, Data Structures & Algorithms, Python Scientific Computing

## Certifications
- Data Structures (UC San Diego) – Mastered efficient data manipulation techniques
- AWS Development (Amazon) – Developed secure and scalable cloud applications
- C++ STL (Coding Blocks) – Mastered algorithms, containers, and STL functions
