# UIUC Legislative Intelligence Platform

## AI-Powered Legislative Intelligence for Strategic University Decision Support

The Legislative Intelligence Platform transforms raw legislative text into structured, actionable intelligence to help the University of Illinois understand policy direction, emerging trends, and institutional impact.

This site serves as the central gateway to the platform’s tools, analytics, and ongoing development.

---

## Platform Access

### Search and Filter Interface

Explore legislation using AI-extracted attributes including policy categories, legislative intent, beneficiaries, ideological alignment, and institutional impact indicators.

<p>
  <a href="https://huggingface.co/spaces/ralate2/Legislation_Dashboard" target="_blank">
    <button style="padding:12px 20px; font-size:16px; background-color:#2b6cb0; color:white; border:none; border-radius:6px; cursor:pointer;">
      Launch Search Interface
    </button>
  </a>
</p>

---

### Trends and Visualization Dashboard

Analyze legislative activity across time, policy domains, and impact signals. Identify patterns, momentum shifts, and emerging areas of influence.

<p>
  <a href="https://huggingface.co/spaces/tjl8/legislationv2-2226" target="_blank">
    <button style="padding:12px 20px; font-size:16px; background-color:#2b6cb0; color:white; border:none; border-radius:6px; cursor:pointer;">
      Launch Visualization Dashboard
    </button>
  </a>
</p>

---

### Legislative Assistant (Conversational AI Interface)

The Legislative Assistant is now available for testing.

The assistant leverages the most recent vectorized legislative dataset (including chunked text with reduced outliers) to provide structured, citation-backed responses to natural language queries.

For this proof of concept (POC), responses are structured in the following format:

- **Short answer** (1–3 sentences)  
- **What the bill does** (plain language bullet points)  
- **Where it applies / who it affects** (bullet points)  
- **Key dates & status** (as available from source data)  
- **Potential UI impacts** (clearly marked as interpretation)  
- **Citations / bill references** (bill number, version date if available, relevant section numbers)

<p>
  <a href="https://copilotstudio.microsoft.com/environments/Default-44467e6f-462c-4ea2-823f-7800de5434e3/bots/copilots_header_bee2b/webchat?__version__=2" target="_blank">
    <button style="padding:12px 20px; font-size:16px; background-color:#2f855a; color:white; border:none; border-radius:6px; cursor:pointer;">
      Launch Legislative Assistant
    </button>
  </a>
</p>

Please test the agent and share feedback regarding response clarity, structure, or edge cases.

---

### Network and Influence Graphs (In Development)

Visualize relationships between legislative intent, beneficiaries, policy domains, and cross-state influence patterns to support advanced trend modeling and strategic analysis.

*Status: Under active development*

---

## How the Platform Works

The system follows an end-to-end analytical pipeline:

### 1. Data Ingestion
Legislative text is collected from external sources and standardized into a structured, queryable format.

### 2. Document Chunking
Bills are segmented into structured units to support retrieval and large-language-model processing.

### 3. AI-Based Feature Extraction
Large language models are used to extract structured attributes including:

- Legislative goals  
- Policy domains and subcategories  
- Intended beneficiaries  
- Institutional impact indicators  
- Ideological alignment  
- Impact ratings  

### 4. Scoring and Normalization
Extracted features are standardized into structured metadata to enable filtering, comparison, and analytics.

### 5. Interactive Exploration
Users access search tools, dashboards, visualization components, and conversational AI tools to explore legislative intelligence at scale.

---

## Platform Vision

The Legislative Intelligence Platform is designed to evolve into a comprehensive institutional intelligence system capable of:

- Early signal detection  
- Cross-policy and cross-state influence modeling  
- Probability-of-passage research  
- AI-assisted executive reporting  
- Institutional risk monitoring  

---

## Contributors

**Platform Architect and Technical Lead**  
Tayler Erbe, Data Scientist  

**Lead Data Engineer and Pipeline Architect**  
Tejasri Joshi, Data Science Analyst  

**Lead AI Engineer, Retrieval-Augmented Search Systems**  
Tanvi Lakhani, Data Science Analyst  

**Lead, Predictive Modeling and Policy Analytics**  
Ruchita Alate, Data Science Analyst  

**AI Solutions Team Lead and Conversational AI Systems Lead**  
Pramod Joshi, AI Coordinator (Lead)

---

## Contact

For collaboration, research partnerships, or technical inquiries, please contact the project team.
