# Case Study: MIRA - AI-Powered Clinical Trial Intelligence Platform

## Executive Summary

**Client:** Global Pharmaceutical & Biotech Companies (Indegene)
**Industry:** Life Sciences / Clinical Development
**Solution:** AI-Driven Conference & Clinical Trial Intelligence
**Results:** 75% faster competitive intelligence, $3M saved in analyst time, 95% conference ROI improvement

---

## The Challenge

Life sciences companies struggled with clinical trial and conference intelligence:
- **Conference overload:** 200+ medical conferences annually
- **Manual data extraction:** Teams spent weeks compiling presentation data
- **Missed insights:** Critical competitive intelligence lost in information deluge
- **Poor ROI tracking:** No systematic way to measure conference value
- **Clinical trial complexity:** 400,000+ trials in ClinicalTrials.gov database
- **Disconnected data:** Conference insights disconnected from trial data
- **Team coordination:** Scattered notes and insights across individuals

Traditional approaches relied on manual data collection, spreadsheets, and institutional knowledge—creating blind spots and inefficiencies.

---

## The Solution

Devkraft developed MIRA, an AI-powered intelligence platform:

### Core AI Technologies
- **AI Model "o3":** Custom clinical trial processing and analysis
- **Web Scraping AI:** Automated conference website data extraction
- **NLP Classification:** Presentation categorization and tagging
- **Semantic Search:** Find relevant trials and presentations instantly
- **Predictive Analytics:** Forecast trial outcomes and conference value
- **Chat Interface:** Natural language queries for complex analysis

### Technical Architecture
- React + TypeScript frontend for rich UX
- Redux Toolkit for state management
- Backend REST API with AI processing
- Server-Sent Events (SSE) for real-time streaming
- TailwindCSS + Radix UI for modern interface
- File processing pipeline for Excel/CSV uploads

### Key Features
1. **Conference Agent:** Scrape, classify, and analyze conference data
2. **Clinical Trial Search:** NCT ID lookup with AI-powered insights
3. **Batch Processing:** Analyze 1000s of trials simultaneously
4. **AI Chat Assistant:** Ask questions about trials in natural language
5. **Team Building:** Assign conference coverage by expertise
6. **Company Booth Intelligence:** Track competitor booth activities
7. **Presentation Scheduling:** Optimize team attendance plans
8. **Export & Reporting:** Excel reports with actionable insights

---

## Implementation Approach

**Phase 1 (Weeks 1-4):** Data integration
- Integrated ClinicalTrials.gov API (400K+ trials)
- Built conference website scraping pipeline
- Created presentation classification taxonomy

**Phase 2 (Weeks 5-8):** AI model development
- Trained custom model "o3" for trial analysis
- Developed prompt-based processing for trial data
- Built semantic search for presentations and trials

**Phase 3 (Weeks 9-12):** User experience
- Designed intuitive conference planning interface
- Built AI chat for trial queries with streaming responses
- Created team coordination features

**Phase 4 (Weeks 13-16):** Deployment & adoption
- Trained 100+ medical affairs and clinical teams
- Integrated with existing BI tools
- Established feedback loops for continuous improvement

---

## Business Impact

### Quantifiable Results
| Metric | Before AI | After AI | Improvement |
|--------|-----------|----------|-------------|
| Conference Data Compilation | 40 hours | 2 hours | 95% faster |
| Clinical Trial Analysis Time | 15 min/trial | 30 sec/trial | 97% faster |
| Competitive Intelligence Gaps | 35% missed | 5% missed | 86% reduction |
| Conference ROI | 45% | 85% | 89% improvement |
| Team Coordination Efficiency | Baseline | +60% | 60% gain |
| Analyst Productivity | Baseline | 5x | 400% increase |

### Strategic Benefits
- **Competitive Advantage:** Real-time intelligence on competitor pipelines
- **Strategic Planning:** Data-driven conference attendance decisions
- **Resource Optimization:** Send right people to right sessions
- **Institutional Knowledge:** Conference insights preserved and searchable
- **Collaboration:** Cross-functional teams aligned on priorities

**Annual Value:** $3M+ (analyst time savings + better conference ROI)

---

## Technology Stack

**Frontend:**
- React, TypeScript, Vite
- Redux Toolkit, React Router
- TailwindCSS, Radix UI
- React Hook Form, React Table (TanStack)
- Axios, React Markdown, SSE.js
- Zod (validation)

**Backend & AI:**
- Custom AI model "o3" for trial processing
- REST API architecture
- Server-Sent Events for streaming
- File processing (Excel, CSV)
- Clinical trials database integration
- Web scraping engine

---

## Key Innovation: AI Conference Agent

MIRA's Conference Agent automates the entire intelligence workflow:

**1. Discovery**
- Crawls conference websites
- Extracts presentation titles, authors, times
- Identifies company affiliations

**2. Classification**
- Categorizes by therapeutic area
- Tags by presentation type (oral, poster, etc.)
- Identifies competitive vs. partnership opportunities

**3. Prioritization**
- Scores relevance to company interests
- Flags must-attend presentations
- Recommends team assignments

**4. Coordination**
- Builds optimized attendance schedules
- Avoids conflicts and gaps
- Generates team assignments

**Result:** Conference prep time reduced from 2 weeks to 2 hours

---

## Client Testimonial

> "MIRA has transformed how we approach medical conferences. We're now making data-driven decisions about where to invest our time and resources. The AI chat feature is like having a clinical trial expert on call 24/7."
>
> **— Head of Medical Affairs, Top 10 Pharma**

---

## Use Cases Delivered

1. **Competitive Intelligence:** Track competitor trial progress and data presentations
2. **Partnership Scouting:** Identify potential collaboration opportunities
3. **KOL Mapping:** Find key opinion leaders presenting at conferences
4. **Trial Benchmarking:** Compare trial designs and outcomes
5. **Evidence Gaps:** Identify unmet medical needs in trial landscape
6. **Conference ROI:** Measure value of attendance and booth presence
7. **Team Planning:** Optimize coverage across global conferences

---

## Clinical Trial AI Chat

Users can ask complex questions in natural language:

**Example Queries:**
- "Show me all Phase 3 oncology trials starting in 2025"
- "Which competitors are testing similar mechanisms to our pipeline?"
- "What's the success rate of trials in this indication?"
- "Find trials with patient populations similar to our target"
- "Summarize adverse events reported in competitor trials"

**AI Response Features:**
- Streaming responses for complex queries
- Citations to specific trial NCT IDs
- Comparative analysis tables
- Actionable insights and recommendations

---

## Company Booth Intelligence

Track competitor activities at conferences:
- Photo/video uploads from booth visits
- Notes on messaging and materials
- Product demo observations
- Lead capture strategies
- Competitive positioning analysis

All intelligence is tagged, searchable, and linked to relevant trials and products.

---

## Future Enhancements

1. **Predictive Analytics:** Forecast trial enrollment and completion
2. **Adverse Event AI:** Automatic safety signal detection
3. **Real-time Alerts:** Notify teams of breaking conference news
4. **Publication Integration:** Link trials to journal publications
5. **Voice Notes:** Audio capture of conference observations
6. **Mobile App:** On-site intelligence capture

---
