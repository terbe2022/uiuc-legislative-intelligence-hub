# Legislative Intelligence Platform

A centralized hub for analyzing legislative text and assessing potential impacts on the University of Illinois.

---

## Overview

The Legislative Intelligence Platform brings together data engineering, machine learning, and policy analysis to transform raw legislative text into structured, actionable insights.

The platform is designed to support exploration, trend analysis, and decision support by enabling users to search, filter, and analyze legislation using AI-extracted features and metadata.

This site serves as the primary entry point to the platform’s tools, documentation, and ongoing development efforts.

---

## How the Platform Works

At a high level, the system follows an end-to-end analytical pipeline:

1. **Data Ingestion**  
   Legislative text is collected from external sources and stored in a structured, queryable format.

2. **Document Chunking**  
   Bills are segmented into smaller, meaningful units to support retrieval, analysis, and large-language-model processing.

3. **AI-Based Feature Extraction**  
   Large language models (LLaMA) are used to extract structured attributes, including:
   - Policy categories
   - Legislative goals
   - Intended beneficiaries
   - Indicators of potential university impact

4. **Scoring and Categorization**  
   Extracted features are normalized into scores, tags, and metadata that support comparison, filtering, and analysis.

5. **Exploration and Analysis**  
   The resulting data can be explored through interactive search, filtering tools, and visual analytics.

---

## Platform Components

### 🔍 Search and Filter Interface

An interactive interface for exploring legislative data using extracted features and metadata.

Capabilities include:
- Filtering by policy area and impact indicators
- Building custom subsets of legislation
- Inspecting AI-extracted attributes directly

**Launch the Search Interface:**  
https://huggingface.co/spaces/ralate2/Legislation_Dashboard

---

### 📊 Trends and Visual Analytics

A visualization-focused interface for exploring trends and patterns across legislation.

Current work includes:
- Trend analysis across time and policy categories
- Early signal detection and exploratory visualizations

*Note: This component is actively under development.*

**Launch the Visualization Interface:**  
https://huggingface.co/spaces/tjl8/legislationv2-2226

---

## In Progress and Upcoming Work

The platform is actively evolving. Planned and in-progress capabilities include:

- **Conversational AI Access**  
  Chat directly with the legislative dataset to ask targeted and exploratory questions.

- **AI-Assisted Report Generation**  
  Generate summaries and reports based on user-defined criteria and analytical goals.

- **Advanced Trend and Influence Modeling**  
  Identify emerging legislative signals and explore cross-policy and cross-state influence patterns.

---

## Contributors

This platform is a collaborative effort spanning data engineering, machine learning, and policy analysis.

- Project Lead: Tayler Erbe  
- Visualization and Trend Analysis: Rujida

Additional contributors will be added as the project evolves.

---

## Contact and Feedback

Questions, feedback, and collaboration inquiries are welcome.

Please contact the project team for additional information.
