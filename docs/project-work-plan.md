# SBOMGuard Project Work Plan

## Project
SBOMGuard: Automated Framework for SBOM Generation, Vulnerability Analysis, and Supply Chain Risk Assessment

## Current Status
Research and planning phase.

## Completed Work

- Conducted literature review on SBOM generation and software supply-chain security.
- Reviewed research on SBOM-based vulnerability analysis and Software Composition Analysis (SCA).
- Identified research gaps related to SBOM completeness, hidden dependencies, vulnerability correlation, risk prioritization, and supply-chain monitoring.
- Identified the major modules planned for SBOMGuard.
- Created the initial GitHub repository and project documentation.

## Planned Development Phases

### Phase 1 — Research and Requirements
- Complete literature review.
- Identify research gaps.
- Define functional and non-functional requirements.
- Finalize project objectives and scope.

### Phase 2 — System Architecture and Technology Selection
- Design the overall SBOMGuard architecture.
- Define the SBOM generation, management, vulnerability analysis, and risk-assessment modules.
- Select tools, frameworks, databases, and SBOM standards.

### Phase 3 — SBOM Generation Module
- Accept software projects and supported input sources.
- Generate SBOMs using suitable SBOM generation tools.
- Support standardized formats such as CycloneDX and SPDX.
- Validate generated SBOM information.

### Phase 4 — SBOM Management
- Store generated SBOMs.
- Maintain different SBOM versions.
- Compare SBOM versions to identify component changes.
- Provide SBOM validation and basic quality information.

### Phase 5 — Vulnerability Analysis
- Correlate SBOM components with vulnerability databases and security advisories.
- Identify vulnerable dependencies.
- Display vulnerability information associated with software components.
- Support vulnerability status and remediation tracking.

### Phase 6 — Supply Chain Risk Assessment
- Develop a risk-assessment mechanism using vulnerability and component information.
- Prioritize important security findings.
- Provide an overall risk view for a software project or SBOM.
- Explore additional supply-chain metadata where applicable.

### Phase 7 — Dashboard and CI/CD Integration
- Develop a web-based dashboard for SBOM and vulnerability results.
- Display component, vulnerability, and risk information.
- Integrate security checks into a CI/CD workflow.
- Define policy-based security checks where applicable.

### Phase 8 — Testing and Validation
- Test SBOM generation with sample projects.
- Validate vulnerability detection.
- Test SBOM comparison and risk assessment.
- Evaluate system results and identify limitations.

### Phase 9 — Documentation and Final Submission
- Complete technical documentation.
- Prepare project report and research documentation.
- Prepare demonstration materials.
- Finalize testing results and conclusions.
- Prepare the final project presentation.

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

### Infrastructure and Development
- Docker
- GitHub
- GitHub Actions

## Current Priority

The immediate priority is to finalize the system architecture and technology selection before beginning implementation.
