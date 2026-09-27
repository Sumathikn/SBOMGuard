# SBOMGuard Research Gaps

## Project
SBOMGuard: Automated Framework for SBOM Generation, Vulnerability Analysis, and Supply Chain Risk Assessment

## Identified Research Gaps

### 1. SBOM Completeness and Accuracy
Existing studies show that SBOM generation tools may produce incomplete or inconsistent dependency information, especially for transitive dependencies, manually installed packages, and different software ecosystems.

SBOMGuard plans to improve dependency visibility by supporting multiple input types and integrating automated SBOM generation and validation.

### 2. Hidden and Missing Dependencies
Research has identified security blind spots caused by hidden dependencies, cloned code, shaded components, and modified component variants. Conventional package-level SCA may not always identify these relationships.

SBOMGuard plans to include dependency analysis and additional component information to improve identification of missing or hidden dependencies.

### 3. Differences Between SBOM Generation Tools
Studies comparing SBOM generators have shown that different tools can produce different component inventories and dependency information. This can affect the results of subsequent vulnerability analysis.

SBOMGuard plans to use standardized SBOM formats such as CycloneDX or SPDX and provide a common workflow for generated SBOM data.

### 4. Vulnerability Correlation
Existing research shows that SBOM generation alone is not sufficient for software security. Generated components must be continuously correlated with vulnerability information from vulnerability databases and advisory sources.

SBOMGuard plans to connect SBOM components with vulnerability information from sources such as OSV, NVD, and GitHub Advisory data.

### 5. Vulnerability Risk Prioritization
Vulnerability scanners may generate a large number of findings. Severity information alone may not provide sufficient context for deciding which vulnerabilities should be addressed first.

SBOMGuard plans to provide risk assessment using vulnerability severity together with additional contextual information to help prioritize findings.

### 6. SBOM Lifecycle Management
Research discusses challenges in generating, distributing, validating, consuming, and maintaining SBOMs. Managing multiple SBOM versions over time is also important for continuous software supply-chain monitoring.

SBOMGuard plans to provide centralized SBOM storage, version tracking, comparison, and validation.

### 7. Integration with CI/CD Pipelines
Several studies propose SBOM and vulnerability analysis within CI/CD environments, but there is still a need for practical integration of SBOM generation, vulnerability checking, risk assessment, and deployment policies in a single workflow.

SBOMGuard plans to support CI/CD integration so that security checks can be performed during the software development and deployment process.

### 8. Supply Chain Risk Beyond CVEs
Some research shows that software supply-chain risk can also depend on factors such as component maintenance, repository activity, provenance, and developer or project metadata.

SBOMGuard can extend SBOM analysis by incorporating additional component and repository information for broader supply-chain risk assessment.

### 9. Runtime Visibility
Build-time or source-based SBOMs may not always represent everything that is actually present or executed at runtime. Research on runtime SBOM generation highlights the need for visibility into dynamically loaded or runtime components.

SBOMGuard identifies runtime analysis as a future extension for comparing build-time SBOM information with runtime component information.

## Overall Research Gap

The reviewed literature demonstrates strong progress in SBOM generation, vulnerability analysis, software composition analysis, SBOM integrity, and supply-chain risk assessment. However, these capabilities are often addressed separately or focus on a specific ecosystem or stage of the software lifecycle.

SBOMGuard proposes an integrated framework that combines SBOM generation, SBOM management, vulnerability correlation, risk assessment, and software supply-chain monitoring within a common workflow.
