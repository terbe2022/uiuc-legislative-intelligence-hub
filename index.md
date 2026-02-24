UIUC Legislative Intelligence Platform
AI-Powered Legislative Intelligence for Strategic University Decision Support

The Legislative Intelligence Platform transforms raw legislative text into structured, actionable intelligence to help the University of Illinois understand policy direction, emerging trends, and institutional impact.

This site serves as the central gateway to the platform’s tools, analytics, and ongoing development.

Platform Access
Search and Filter Interface

Explore legislation using AI-extracted attributes including policy categories, legislative intent, beneficiaries, ideological alignment, and institutional impact indicators.

<p> <a href="https://huggingface.co/spaces/tjl8/legislationv2-2226" target="_blank"> <button style="padding:12px 20px; font-size:16px; background-color:#2b6cb0; color:white; border:none; border-radius:6px; cursor:pointer;"> Launch Search Interface </button> </a> </p>
Trends and Visualization Dashboard

Analyze legislative activity across time, policy domains, and impact signals. Identify patterns, momentum shifts, and emerging areas of influence.

<p> <a href="https://huggingface.co/spaces/ralate2/Legislation_Dashboard" target="_blank"> <button style="padding:12px 20px; font-size:16px; background-color:#2b6cb0; color:white; border:none; border-radius:6px; cursor:pointer;"> Launch Visualization Dashboard </button> </a> </p>
Legislative Assistant (Conversational AI Interface)

The Legislative Assistant leverages the most recent vectorized legislative dataset to provide structured, citation-backed responses to natural language queries.

Responses are structured as:

Short answer (1–3 sentences)

What the bill does

Where it applies / who it affects

Key dates & status

Potential UI impacts (clearly marked as interpretation)

Citations / bill references

<p> <a href="https://copilotstudio.microsoft.com/environments/Default-44467e6f-462c-4ea2-823f-7800de5434e3/bots/copilots_header_bee2b/webchat?__version__=2" target="_blank"> <button style="padding:12px 20px; font-size:16px; background-color:#2f855a; color:white; border:none; border-radius:6px; cursor:pointer;"> Launch Legislative Assistant </button> </a> </p>

Please test the agent and share feedback regarding response clarity, structure, or edge cases.

Network and Influence Graphs (In Development)

Visualize relationships between legislative goals, beneficiaries, policy domains, and institutional impact patterns to support advanced trend modeling and strategic analysis.

Status: Under active development

How the Platform Works

The system follows an end-to-end analytical pipeline:

1. Data Ingestion

Legislative data is sourced directly from LegiScan and the Illinois General Assembly (ILGA) FTP site, ensuring access to official bill text, status updates, and metadata across sessions.

Raw legislative files are standardized into structured, queryable formats for downstream analytics.

2. Document Chunking

Bills are truncated to safe processing limits and segmented into structured text units to enable scalable large-language-model analysis and retrieval workflows.
Chunking ensures long legislative documents can be analyzed efficiently while preserving contextual continuity.

3. AI-Based Feature Extraction

Large language models extract structured legislative intelligence from each bill, including:

Llama Summary – A concise plain-language overview of the bill’s purpose and actions.

Legislative Goal – The primary intended outcome or policy objective of the bill.

Policy Domain – High-level policy categories or issue areas the bill aligns with.

Key Provisions – Core legal changes, mechanisms, or structural adjustments introduced.

Intended Beneficiaries – Stakeholders or populations directly affected.

Legislative Strategy – Procedural or political approach embedded in the bill design.

Increasing Aspects – What the bill aims to expand, fund, authorize, or strengthen.

Decreasing Aspects – What the bill seeks to reduce, restrict, repeal, or eliminate.

Category & Subcategory – Assigned political or institutional classification labels.

Ideological Alignment – Inferred ideological framing when identifiable.

Potential Impact – Concise assessment of possible implications for UIUC.

Impact Rating – Structured impact level (Very Impactful, Moderately Impactful, Slightly Impactful, Not Impactful).

Intent – One-sentence articulation of legislative purpose.

Motivation – One-sentence articulation of the underlying driver or context.

Original Law – Referenced statutes or legal frameworks being amended or cited.

These features convert unstructured legislative language into structured intelligence signals.

4. Scoring, Standardization, and Analytical Enrichment

Extracted features are normalized through multiple independent analytical methods, including:

Static institutional category frameworks

Unsupervised clustering (e.g., K-Means topic modeling)

Category mapping and crosswalk alignment

Feature normalization and deduplication

Entity and action extraction for relational modeling

Entities (actors, institutions, policy objects) and actions (mandates, appropriations, restrictions) are extracted to construct relationship networks that map how legislative goals connect across domains, enabling advanced network graph analysis and influence modeling.

5. Interactive Exploration

Users access search tools, dashboards, visualization components, and conversational AI tools to explore legislative intelligence at scale.

The platform enables filtering by policy domain, impact rating, beneficiaries, ideological patterns, institutional relevance, and temporal activity.

Platform Vision

The Legislative Intelligence Platform is designed to evolve into a comprehensive institutional intelligence system capable of:

Early signal detection

Cross-policy and cross-state influence modeling

Probability-of-passage research

AI-assisted executive reporting

Institutional risk monitoring

Legislative relationship graph analytics

Contributors

Platform Architect and Technical Lead
Tayler Erbe, Data Scientist

Lead Data Engineer and Pipeline Architect
Tejasri Joshi, Data Science Analyst

Lead AI Engineer, Retrieval-Augmented Search Systems
Tanvi Lakhani, Data Science Analyst

Lead, Predictive Modeling and Policy Analytics
Ruchita Alate, Data Science Analyst

AI Solutions Team Lead and Conversational AI Systems Lead
Pramod Joshi, AI Coordinator (Lead)
