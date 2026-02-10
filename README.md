# Data-Dev-Demo-Reel

> A portfolio showcase of data development, software engineering, and compliance intelligence projects

## Table of Contents

- [About](#about)
- [Featured Projects](#featured-projects)
- [Skills & Technologies](#skills--technologies)
- [Contact](#contact)

## About

Enterprise data engineer and full-stack developer with 8+ years building production systems at the University of Toronto. I architect end-to-end solutions — from multi-source ETL pipelines processing 400K+ records to full-stack Flask/PostgreSQL applications with audit logging and compliance controls. I specialize in sanctions screening, entity resolution, and research security platforms.

## Featured Projects

### Project 1: Risk Analysis System V2
- **Description**: Full-stack sanctions screening platform with entity resolution across OFAC SDN, BIS Entity List, and EU consolidated sanctions lists. Three-layer architecture: Data Integration Layer (6 APIs) → Processing Engine (fuzzy matching, entity resolution, risk scoring) → Output Systems (Flask UI, REST APIs, PDF reports).
- **Technologies**: Python, Flask, PostgreSQL, OpenSanctions API, OpenCorporates API, SEC EDGAR, fuzzy matching algorithms, REST APIs
- **Key Features**:
  - Real-time entity matching across international sanctions lists (OFAC SDN, BIS Entity List, EU consolidated sanctions)
  - High-precision entity-resolution workflow with fuzzy matching and AI-assisted disambiguation
  - Multi-user support with role-based security, audit logging, and collaborative threat assessment
  - Automated PDF report generation and alerts system
  - OneDrive sync for institutional document management

### Project 2: Research Security ETL v2.0
- **Description**: Multi-source intelligence ingestion and validation pipeline integrating six intelligence APIs with near real-time processing. Optimized from hours to 2-3 minute runtime through indexing, vectorized operations, and intelligent caching.
- **Technologies**: Python (pandas, numpy), PostgreSQL, OpenSanctions, Scopus, Dimensions, OpenAlex, OpenCorporates, Strider Technologies API
- **Key Features**:
  - Multi-source data ingestion from 6+ intelligence APIs with automated validation
  - Runtime optimization from hours to 2-3 minutes through smart caching and vectorized operations
  - 20-sheet comprehensive Excel reports with risk matrices
  - GUI and CLI interfaces for analyst workflows
  - Feeds provincial oversight (MCURES Ontario) safeguarding requirements

### Project 3: Bibliometric Analytics System
- **Description**: Automated reconciliation engine processing 264,196 publication records with three-tier deduplication logic and data quality validation. Reduced UTQAP processing from ~320 to ~16 person-hours.
- **Technologies**: Python (pandas, numpy), Tableau, Excel automation, fuzzy matching, DOI resolution
- **Key Features**:
  - Three-tier deduplication: UTORID matching → Title/Author fuzzy matching → DOI reconciliation
  - O(n²) → O(n log n) optimization through architecture redesign
  - 14-sheet output structure for institutional reporting and UTQAP submissions
  - Automated department-level deliverables across all university faculties

### Project 4: Faculty Profile RAG System
- **Description**: Production Retrieval-Augmented Generation system using LangChain for automated faculty profile generation from web-scraped bibliometric data. Combines traditional ETL with generative AI for entity resolution and profile synthesis.
- **Technologies**: Python, LangChain, RAG, LLM tool orchestration, web scraping, prompt engineering, structured JSON output
- **Key Features**:
  - ETL pipeline → LLM processing → structured JSON output architecture
  - LLM-enhanced entity resolution and profile synthesis at scale
  - Context window management for large-scale processing
  - Output validation and structured JSON generation
  - Web-scraped bibliometric data as RAG knowledge base

### Project 5: GA4 Intelligence Pipeline
- **Description**: Automated research engagement and visibility analytics pipeline covering 156+ countries. Built executive-facing dashboards with anomaly detection and automated aggregations for institutional strategic planning.
- **Technologies**: Python, Google Analytics 4 API, Tableau, BigQuery, Google Cloud Storage, Looker Studio
- **Key Features**:
  - GA4 API extraction with automated transformation for Tableau-ready outputs
  - Anomaly detection and statistical aggregation across 150+ countries
  - Executive dashboards for institutional ranking strategy and visibility metrics
  - Quarterly automated reporting for research engagement tracking

### Project 6: CCR ETL Pipeline & Analytics Platform
- **Description**: Production ETL pipeline joining multi-source institutional data (ROSI student information system, Co-Curricular Record, HRIS) processing 400,000+ student records across three campuses with automated validation and compliance reporting.
- **Technologies**: Python, SQL, Tableau Server, ROSI API, HRIS integration, SharePoint
- **Key Features**:
  - Multi-source institutional data joining with automated validation checkpoints
  - Dual output architecture: CSV imports for mass record population + automated mailing lists
  - Tableau Server administration (projects, permissions, scheduled refreshes) for tri-campus stakeholders
  - QA dashboards tracking adoption, accuracy, and support-volume trends

## Skills & Technologies

### Programming Languages
- Python (pandas, numpy, scikit-learn, Flask)
- SQL (PostgreSQL, SQLite)
- JavaScript / TypeScript (Node.js)
- R (statistical analysis)
- Rust (high-performance microservices)
- Scala (Spark Structured Streaming)
- VBA

### Data Technologies
- **ETL/ELT Pipelines**: 8+ years building multi-source integration pipelines
- **Database Management**: PostgreSQL, MongoDB, Redis, FileMaker Pro
- **Data Visualization**: Tableau, Power BI, Looker Studio, Google Analytics 4
- **Entity Resolution**: Fuzzy matching, sanctions screening, deduplication algorithms
- **API Integration**: REST APIs, OpenSanctions, Scopus, Dimensions, OpenAlex, OpenCorporates, SEC EDGAR
- **Machine Learning**: LangChain, RAG systems, TensorFlow, scikit-learn, prompt engineering

### Development Tools
- Git & version control
- Docker
- Azure DevOps (Agile/Scrum boards, CI/CD pipelines)
- Azure, Google Cloud Platform (BigQuery, Cloud Storage)
- Flask (full-stack web applications)
- Playwright (browser automation)

### Domain Expertise
- Sanctions screening (OFAC SDN, BIS Entity List, EU consolidated sanctions)
- Corporate investigations & enhanced due diligence
- OSINT methodologies
- Data governance, audit logging, FIPPA compliance
- Research security & export controls

## Contact

- **GitHub**: [@jdoash](https://github.com/jdoash)
- **Email**: jesse.ashiedu@gmail.com
- **LinkedIn**: [linkedin.com/in/jesseadigwe](https://linkedin.com/in/jesseadigwe)

---

*Last Updated: February 2026*
