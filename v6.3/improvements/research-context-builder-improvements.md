# Research & Context Builder Mode - Improvement Suggestions

## Current Role
- Gathers information from external web sources or specified code repositories based on a research query.
- Synthesizes findings into a structured Markdown summary with citations.
- Can use `browser`, `execute_command` (for `curl`), `read_file`, `list_files`, and potentially MCP tools.

## Recommended Improvements

### 1. Add Metadata Tags
- `"research"`, `"information-gathering"`, `"context-building"`, `"web-scraping"`, `"documentation-analysis"`, `"synthesis"`

### 2. Escalation & Delegation
- Should be **invoked by any mode** needing external information, deeper context on a technology, or analysis of external resources (docs, repos).
- Should escalate:
  - **Inability to find relevant information** or access key sources back to the caller.
  - **Need for complex analysis or interpretation** of the gathered data to Complex Problem Solver or Technical Architect.
  - **Need for generating a Condensed Context Index** from the research to Context Condenser.
- Should **not typically delegate** implementation tasks, but focuses on information gathering and synthesis.

### 3. Collaboration
- Serves **all other modes** by providing research findings and context.
- Collaborates with **Context Condenser** if the research output needs to be formatted into an index.
- Collaborates with **Technical Writer** if the research needs to be incorporated into formal documentation.

### 4. Role Clarification
- Emphasize the role as an **information gatherer and synthesizer**.
- Highlight the process: Plan -> Gather (Web, Files, MCP) -> Synthesize -> Report.
- Stress the importance of **source evaluation and citation**.
- Clarify the output format: **Structured Markdown summary** with executive summary, detailed findings, examples, and references.

### 5. Additional Capabilities
- Utilize **more advanced web scraping techniques** (if tools become available).
- Integrate with **academic search engines** or specific technical databases (potentially via MCP).
- Perform basic **sentiment analysis** or **trend analysis** on gathered text data.
- Generate **different summary formats** (e.g., bullet points only, Q&A format).
- Handle **different source types** more robustly (e.g., PDFs, code repositories).
- Maintain a **cache or knowledge base** of previously researched topics to avoid redundant work.

---

*Generated by Roo Commander, 2025-09-04*