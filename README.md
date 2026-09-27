# SBOMGuard

## Automated Framework for SBOM Generation, Vulnerability Analysis, and Supply Chain Risk Assessment

SBOMGuard is a cybersecurity project focused on improving software supply chain security through automated Software Bill of Materials (SBOM) generation, vulnerability analysis, and supply chain risk assessment.

## Problem Statement

Modern software applications depend on numerous open-source libraries, packages, containers, and third-party components. Vulnerabilities or hidden dependencies within these components can introduce security risks into the software supply chain.

Existing approaches often address SBOM generation, vulnerability scanning, dependency analysis, and risk assessment separately. There is a need for an integrated workflow that can generate SBOMs, analyze their components, correlate vulnerabilities, and provide an overall supply chain risk view.

## Objectives

- Automate SBOM generation for software projects.
- Support standardized SBOM formats such as CycloneDX and SPDX.
- Maintain and validate generated SBOM information.
- Identify vulnerabilities affecting software dependencies.
- Correlate SBOM components with vulnerability information.
- Assess and prioritize software supply chain risks.
- Provide a dashboard for security findings and risk information.
- Explore integration with CI/CD security workflows.

## Planned Modules

### 1. SBOM Generation Engine
Generates SBOMs from supported software projects, source code, binaries, and containers using suitable SBOM generation tools.

### 2. SBOM Management Engine
Provides storage, version tracking, comparison, and validation of generated SBOMs.

### 3. Vulnerability Correlation Engine
Maps software components identified in an SBOM to vulnerability information from security databases and advisories.

### 4. Risk Assessment Engine
Analyzes vulnerability and component information to provide risk prioritization and supply chain security insights.

### 5. Dashboard and Reporting
Provides a web-based interface for viewing SBOM components, vulnerabilities, risk information, and reports.

### 6. CI/CD Integration
Planned integration with CI/CD pipelines for automated security checks during software development and deployment.

## Proposed Architecture

![SBOMGuard Architecture](diagrams/proposed-architecture.png)

## Planned Technology Stack

### Backend
- Python
- FastAPI

### SBOM and Security Tools
- Syft
- Grype
- CycloneDX
- SPDX

### Vulnerability Sources
- OSV
- NVD
- GitHub Advisories

### Frontend
- React
- TypeScript

### Development and Deployment
- Docker
- GitHub
- GitHub Actions

## Current Status

**Research and Planning Phase**

### Completed
- Literature review
- Research-gap identification
- Initial project requirements
- Planned system modules
- Project work plan
- Proposed system architecture
- GitHub repository setup

### Upcoming
- Finalize functional and non-functional requirements
- Finalize technology selection
- Set up development environment
- Implement SBOM generation
- Implement vulnerability analysis
- Develop risk-assessment workflow
- Develop dashboard
- Integrate CI/CD checks
- Testing and validation
- Final documentation

## Repository Structure

```text
SBOMGuard/
├── README.md
├── .gitignore
├── SBOMGuard.pdf
├── research/
├── docs/
│   ├── literature-review.md
│   ├── research-gaps.md
│   └── project-work-plan.md
└── diagrams/
    └── proposed-architecture.png
