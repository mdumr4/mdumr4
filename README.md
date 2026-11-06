<div align="center">

<!-- Hero Terminal HUD with Visual Neural Architecture (Zero Scores, Pure Systems Design) -->
<img src="./assets/header-banner.svg" alt="Mohammed Umar F - AI Systems Architect" width="100%" style="border-radius: 12px; max-width: 100%; display: block;" />

<br/>

<!-- Fast Affordances & Profiles -->
<p align="center">
  <a href="mailto:mdumr4@gmail.com">
    <img src="https://img.shields.io/badge/Email-mdumr4%40gmail.com-161b22?style=flat-square&logo=gmail&logoColor=10b981" alt="Email" />
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/mdumr4">
    <img src="https://img.shields.io/badge/LinkedIn-in%2Fmdumr4-161b22?style=flat-square&logo=linkedin&logoColor=10b981" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://x.com/mdumr4_">
    <img src="https://img.shields.io/badge/X-@mdumr4_-161b22?style=flat-square&logo=x&logoColor=f59e0b" alt="Twitter/X" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Bangalore%2C_India-161b22?style=flat-square&logo=googlemaps&logoColor=10b981" alt="Location" />
</p>

</div>

---

### ⚡ 01. Profile & Engineering Philosophy

> **I am an AI Systems Architect & Multimodal ML Engineer based in Bangalore.** My work bridges deep learning models with production data systems: designing multimodal vision-language pipelines, two-stage hybrid neural retrieval engines (RAG), and stealth autonomous browser agents.
>
> **My Core Engineering Rule**: A machine learning model is only as useful as its systems design. Production AI demands clean architectural boundaries, sub-second inference budgets, deterministic retrieval fallbacks, and zero hallucinated attribution.

---

### 🧠 02. Core Architectural Pillars & Specializations

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>👁️ 1. Multimodal Deep Learning (Vision + NLP)</h4>
      <p>Designing dual-tower neural networks that fuse unstructured textual tokens with self-supervised visual features via cross-attention projection layers.</p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/DINOv2-0081CB?style=flat-square&logo=meta&logoColor=white" />
        <img src="https://img.shields.io/badge/ResNet34-0A66C2?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>🔍 2. Information Retrieval &amp; Two-Stage Hybrid RAG</h4>
      <p>Engineering enterprise neural search combining dense semantic vector search with learned sparse lexical expansions and pairwise Cross-Encoder reranking.</p>
      <p>
        <img src="https://img.shields.io/badge/FAISS_HNSW-0081CB?style=flat-square&logo=meta&logoColor=white" />
        <img src="https://img.shields.io/badge/SPLADE--v3-10b981?style=flat-square" />
        <img src="https://img.shields.io/badge/Cross--Encoders-f59e0b?style=flat-square" />
        <img src="https://img.shields.io/badge/Qwen_2.5-6366F1?style=flat-square" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 3. Autonomous Web Agents &amp; DOM Engineering</h4>
      <p>Building stealth Manifest V3 Chrome extensions with anti-fingerprint DOM humanizers, randomized jitter kinematics, and LLM-driven intent reasoning.</p>
      <p>
        <img src="https://img.shields.io/badge/Chrome_MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/GPT--4o--mini-412991?style=flat-square&logo=openai&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>📊 4. High-Throughput Data Systems &amp; Linkage</h4>
      <p>Implementing sub-linear candidate blocking, inverted indexing, and distance matrices for million-scale record linkage and merchant deduplication.</p>
      <p>
        <img src="https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
        <img src="https://img.shields.io/badge/Apache_Parquet-4B8BBE?style=flat-square&logo=apache&logoColor=white" />
        <img src="https://img.shields.io/badge/Levenshtein-10b981?style=flat-square" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

### 🏗️ 03. Systems I Built & Architectural Decisions

Structured portfolio case studies detailing the engineering challenges, architectural mechanisms, and technical stack behind each system:

<table>
  <tr>
    <td width="50%" valign="top">
      <p><code>sys://retrieval/resume-ranker</code> &nbsp; <img src="https://img.shields.io/badge/HYBRID_RAG-10b981?style=flat-square" /></p>
      <h3>📄 <a href="https://github.com/mdumr4/resume-ranker">resume-ranker</a></h3>
      <p><b>Enterprise Two-Stage Hybrid Neural Retrieval Engine</b></p>
      <ul>
        <li><b>The Challenge:</b> Pure dense vector search suffers from semantic drift and misses critical keyword credentials, while legacy BM25 fails on semantic synonyms.</li>
        <li><b>Architecture:</b> Combines dense semantic search via <code>FAISS (HNSW)</code> with sparse lexical expansion via <code>SPLADE-v3</code> for high-recall candidate discovery. Candidates pass through a pairwise <code>Cross-Encoder</code> for deep query-resume interaction scoring.</li>
        <li><b>Explainability:</b> <code>Qwen 2.5</code> synthesizes structured rationale summaries, guaranteeing 100% explainable rankings with zero hallucinated attribution.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/FAISS-0081CB?style=flat-square&logo=meta&logoColor=white" />
        <img src="https://img.shields.io/badge/SPLADE--v3-10b981?style=flat-square" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <p><code>sys://multimodal/pricing-engine</code> &nbsp; <img src="https://img.shields.io/badge/MULTIMODAL_AI-f59e0b?style=flat-square" /></p>
      <h3>🏷️ <a href="https://github.com/mdumr4/Smart-Product-Pricing">Smart-Product-Pricing</a></h3>
      <p><b>Dual-Tower Multimodal Pricing Engine · Amazon ML Challenge</b></p>
      <ul>
        <li><b>The Challenge:</b> E-commerce product catalogs contain noisy, unstructured text coupled with diverse product imagery that single-modality models fail to represent accurately.</li>
        <li><b>Architecture:</b> Dual-tower neural network. The visual tower uses Meta’s self-supervised <code>DINOv2 (ViT)</code> to extract 768-dim spatial embeddings; the text tower uses fine-tuned <code>DistilBERT</code> to encode product specifications.</li>
        <li><b>Data Pipeline:</b> Projected through a custom cross-attention fusion layer and streamed via Snappy-compressed <code>Parquet</code> directly into gradient-boosted <code>LightGBM</code>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/DINOv2-0081CB?style=flat-square&logo=meta&logoColor=white" />
        <img src="https://img.shields.io/badge/DistilBERT-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
        <img src="https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square&logo=scikitlearn&logoColor=white" />
        <img src="https://img.shields.io/badge/Parquet-4B8BBE?style=flat-square&logo=apache&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p><code>sys://vision/plantdocbot</code> &nbsp; <img src="https://img.shields.io/badge/COMPUTER_VISION-10b981?style=flat-square" /></p>
      <h3>🌿 <a href="https://github.com/mdumr4/PlantDocBot">PlantDocBot</a></h3>
      <p><b>Multimodal Agronomy Diagnosis · Infosys Springboard</b></p>
      <ul>
        <li><b>The Challenge:</b> Visual similarity between distinct foliar diseases (fungal vs. nutrient deficiencies) often tricks standalone vision models into high-consequence misdiagnoses.</li>
        <li><b>Architecture:</b> Deep convolutional foliage classification (<code>ResNet34</code>) operates in parallel with a fine-tuned <code>DistilBERT</code> NLP parser extracting symptom severity from farmer field notes.</li>
        <li><b>Confidence Arbitration:</b> Dynamic confidence gating module evaluates inter-modality agreement before confirming recommendations, falling back to uncertainty states on conflicting inputs.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/ResNet34-0A66C2?style=flat-square&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/DistilBERT-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <p><code>sys://agents/eylo-reddit</code> &nbsp; <img src="https://img.shields.io/badge/AUTONOMOUS_AGENT-f59e0b?style=flat-square" /></p>
      <h3>🤖 <a href="https://github.com/mdumr4/Eylo-Reddit-v2">Eylo-Reddit-v2</a></h3>
      <p><b>Autonomous Growth &amp; Outreach Agent · Manifest V3</b></p>
      <ul>
        <li><b>The Challenge:</b> Automated browser workflows trigger anti-bot heuristics, fingerprinting defenses, and session blocks due to linear, mechanical DOM manipulation.</li>
        <li><b>Architecture:</b> Manifest V3 extension featuring anti-detection DOM humanization (randomized Bezier cursor kinematics, typing jitter, realistic scroll physics).</li>
        <li><b>Agentic Qualification:</b> Ingests live community discussions, qualifies user purchase intent using <code>GPT-4o-mini</code>, and syncs state via <code>Supabase</code> to deduplicate leads across accounts.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Chrome_MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/GPT--4o--mini-412991?style=flat-square&logo=openai&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <p><code>sys://data/entity-resolution</code> &nbsp; <img src="https://img.shields.io/badge/BIG_DATA_LINKAGE-10b981?style=flat-square" /></p>
      <h3>🏢 <a href="https://github.com/mdumr4/Business-Entity-Resolution">Business-Entity-Resolution</a></h3>
      <p><b>Million-Scale Merchant Deduplication · Big Data &amp; Record Linkage</b></p>
      <ul>
        <li><b>The Challenge:</b> Exact pairwise comparison across 1,000,000+ merchant records requires $O(N^2) \approx 5 \times 10^{11}$ operations, making naive matching computationally impossible.</li>
        <li><b>Architecture:</b> Two-tier sub-linear pipeline. Stage 1 uses <code>TF-IDF n-gram inverted index blocking</code> to eliminate 99.8% of obvious non-matching pairs in sub-linear time. Stage 2 evaluates candidate pairs using vectorized Levenshtein edit distance matrices and a gradient-boosted classification reranker.</li>
        <li><b>Core Innovation:</b> Scaled enterprise record deduplication to 1M+ entities with sub-linear processing overhead and high candidate pair recall.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
        <img src="https://img.shields.io/badge/TF--IDF_Blocking-10b981?style=flat-square" />
        <img src="https://img.shields.io/badge/Levenshtein_Matrix-0081CB?style=flat-square" />
        <img src="https://img.shields.io/badge/Snappy_Parquet-4B8BBE?style=flat-square&logo=apache&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

### 🛠️ 04. Technical Tooling & Competencies

| Domain | Production Tooling, Models & Frameworks |
| :--- | :--- |
| **Languages & Core** | `Python 3.11+` (AsyncIO, PyTorch, NumPy) · `TypeScript` · `JavaScript (ES6+)` · `SQL (PostgreSQL / pgvector)` · `Bash` |
| **Deep Learning & Vision** | `PyTorch` · `DINOv2 (Meta ViT)` · `ResNet34` · `Hugging Face Transformers` · `Torchvision` · `OpenCV` · `LightGBM` |
| **Neural Search & RAG** | `FAISS (HNSW Indexing)` · `SPLADE-v3` · `Pairwise Cross-Encoders` · `Sentence-Transformers` · `Qwen 2.5` · `GPT-4o` |
| **Platforms & Infrastructure**| `Chrome Extensions (MV3 APIs)` · `FastAPI` · `Supabase` · `Snappy Parquet` · `Docker` · `Streamlit` · `GitHub Actions` |

---

### 🏆 05. Honors & Engineering Recognition

- 🥇 **Infosys Springboard Project** — *Excellence Distinction*: Engineered PlantDocBot, a dual-tower foliar disease diagnosis engine pairing ResNet34 vision with symptom NLP and confidence arbitration.
- 🥇 **Amazon ML Challenge** — *Competitive Placement*: Designed an end-to-end multimodal pricing pipeline fusing DINOv2 self-supervised vision representations with DistilBERT text and cross-attention LightGBM.
- 🥇 **IBM Hackathon** — *Featured Innovation*: Architected an autonomous multi-agent clinical dietary reasoning system enforcing deterministic biomarker and medical safety constraints.

---

### 📬 06. Contact & Terminal Dispatch

```bash
$ curl -s https://api.umar.dev/contact | jq .
{
  "name": "Mohammed Umar F",
  "role": "AI Systems Architect & Multimodal ML Engineer",
  "email": "mdumr4@gmail.com",
  "linkedin": "in/mdumr4",
  "twitter": "@mdumr4_",
  "location": "Bangalore, India",
  "status": "Open for Senior / Staff AI Roles"
}
```

<div align="center">
  <p align="center">
    <a href="mailto:mdumr4@gmail.com"><b>📧 Start a Conversation</b></a> &nbsp;•&nbsp;
    <a href="https://linkedin.com/in/mdumr4"><b>💼 Connect on LinkedIn</b></a> &nbsp;•&nbsp;
    <a href="https://x.com/mdumr4_"><b>𝕏 Follow on Twitter</b></a>
  </p>
</div>
