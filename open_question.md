# Open Questions

Answer under each item. Rough answers are fine; "don't know" or "skip" is also an answer.

**Status:** `[x]` = answer is enough to update the docs. `[ ]` = missing or needs more detail.

**CV principle (confirmed):** Humble and attractive. No lies, no overpromising. Some details stay off the CV and are explained honestly in interviews.

## A. Employment timeline

- [x] **1. Apr – Aug 2024 (Koinworks → Antler):** What were you doing? Your Master's ran 2023–2024. Did it cover this gap?
  - Answer: TBH, I work in electrical vehicle startup for 3 month but it is not working. We can use master study to cover gap.
  - Decision: Leave the EV startup off the CV; disclose it if asked.
  - Note: Leaving it off is fine. Don't describe the gap as full-time study, because the Master's overlapped with Koinworks. Check LinkedIn doesn't list the EV startup with different dates.
- [x] **2. Dec 2024 – Jun 2025 (Antler → Bobobox):** What's your one-line answer? (e.g. job search, freelance, family, study, rest)
  - Answer: Job search and rest. Explain in interview.
- [x] **3. Jun 2026 – now:** Is the ERPNext prototype your main activity? Anything else, like consulting work or a job search?
  - Answer: AI upskilling and rest.
- [x] **4. Bobobox exit:** Why were you laid off? Company-wide, restructuring, or your role being cut? (For your interview answer only, not the CV.)
  - Answer: Company-wide restructuring. About half the tech team was laid off, and the VP role was merged into the Chief Product role.
  - Interview line: "A company-wide restructuring cut about half the tech team, and my role was merged into the Chief Product role."

## B. Metrics

### Bobobox

- [x] **5. Productivity:** How did you see it improve? (e.g. release frequency, cycle time, on-time delivery, leadership feedback)
  - Answer: Cycle time, on-time delivery, and leadership/team feedback.
  - Still needed: Any rough before/after for cycle time or on-time delivery? If none, write "none" and the CV will stay qualitative.
  - None. The SDLC is not really working when I join and I fix it 
- [x] **6. OPEX:** How much did the open-source migration save, as an amount or %? Which tools were replaced?
  - Answer: Up to 100 mio per month. Replaced the project management tool and device management (desktop/Android), moved to Linux. Also cut infra cost by simplifying architecture and downscaling.
  - Still needed: Confirm it's IDR 100 million/month, and whether that covers licenses + infra together.
  - I think it just license but let said it cover both 
  - Decision: CV credits IDR 100M/month to licences only (your best recollection). Infra savings listed separately, without a number. Claiming both would overstate it.
- [x] **7. Compliance:** Which regulation or standard did the IT governance work meet?
  - Answer: ISO 27001. Bobobox: preparation started, not certified. Koinworks: supported; mostly done by the infra team.
  - Note: The current resume says Bobobox governance was "meeting regulatory compliance". That needs softening to "began ISO 27001 preparation".
- [x] **8. Roadmap status:** Were the PMS and Lakehouse built, in progress, or still planned when you left?
  - Answer: In progress.
- [x] **9. Firefighting:** Any rough numbers? (e.g. incidents a month, outages, time to resolve)
  - Answer: No numbers. Also acted as EM for IoT and TechOps because of limited headcount from the start, including on-site internet issues.

### Koinworks

- [x] **10. LOS/LMS scale:** Loan volume, number of borrowers, number of systems, or transactions?
  - Answer: No number; asked Claude to check public data.
  - Public data found: 2.2M users in 2022 ([CIIP case study](https://ciip.com.sg/docs/default-source/default-document-library/ciip_case-study_koinworks_v2.pdf?sfvrsn=d4e8973d_1)); 900K+ MSMEs financed, cumulative, per the 2023 Impact Report ([IDN Financials](https://www.idnfinancials.com/news/50157/distribute-financing-to-900-thousand-msmes-koinworks-launches-impact-report-2023)).
  - Still needed: OK to use "a platform with 2M+ users" as company context (not your outcome)?
  - The traffic is not 2M+ user and seem overpromise to me since borrower only login when apply the load. Koinworks is shutdown right now due to legal case 
  - Decision: No scale number on the CV. Added the shutdown to SWOT threats; prepare an interview answer.
- [x] **11. Modernization roadmap:** Was any of it done while you were there?
  - Answer: Roadmap created; not executed.
- [x] **12. Interim Data lead:** For how long?
  - Answer: 4 months.

### Tiket.com

- [x] **13. Uptime:** Before and after numbers for the auth service fix?
  - Answer: No numbers. Auth service was a bottleneck during campaigns; no more campaign issues after the rewrite.
- [x] **14. Go standard:** How many services or teams adopted it?
  - Answer: No number. Most services now use Go instead of Java.

### Gojek

- [x] **15. Fraud system:** Throughput, or fraud cases or losses prevented?
  - Answer: No numbers. Keep qualitative.
- [x] **16. BaritoLog:** How many internal teams used it? Any GitHub stars or outside users?
  - Answer: Used across the entire organization.

## C. AI project

- [x] **17. Start date:** Exact month of the ERPNext project?
  - Answer: June 2026.
- [x] **18. Status:** Which features work today, and which are in progress or planned?
  - Answer: intent classifier and tool calling is complete. I can learn through the agent, get data, review approval. 
  - Follow-up: Ask the agent about ERP functionality, and it navigates to the page. Added to the CV.
- [x] **19. Stack:** Which LLM or provider, language, and framework?
  - Answer: Gemini API, Python, websocket streaming protocol. I don't use framework on LLM and create custom handler to handle multple provider yet right now just gemini
- [x] **20. Proof:** Is there a public repo, a demo video, or a write-up? Could you make one safely?
  - Answer: No proof yet; demo video planned. Also building a consultancy, navario.id.
  - Still needed: Decide whether navario.id appears on the CV (see note below).
  - I don't think it is good idea. But your sugestion?
  - Decision: Agreed, keep navario.id off the CV until it has clients. Demo video still planned.
- [x] **21. AI terms on the CV:** Have you actually used vector databases, agentic workflows, and prompt engineering, in ERPNext or anywhere else?
  - Answer: Yes, in personal projects, mostly ERPNext.
  - Note: Keep the terms, but tie them to the ERPNext entry so they aren't read as work experience.
  - Follow-up: Vector database not in the prototype yet; planned. Removed from the CV until built.
- [x] **22. "AI Implementation Strategy":** Did you do AI work at Bobobox or Koinworks, or is this only from the ERPNext project?
  - Answer: Only ERPNext.
  - Note: Rename to "Practical AI Adoption" or similar; the current label implies company-level AI work.

- [x] **23. New AI terms:** Headless AI Agent, MCP Server, Reasoning Layer, Vector Database?
  - Answer: Reasoning layer is in the ERPNext assistant (intent classifier sends complex requests to it). Headless AI agent and MCP server are consultancy offerings, with portfolio pieces being prepared. Vector database still planned.
  - Decision: Reasoning layer added to the CV. The other three stay off until built; add them to the ERPNext entry (or a new project) once there is working code.

## Resolved

- [x] **Antler tenure:** It was a 4-month program, so the short tenure is expected.
  - Action: label it "(4-month program)" on the CV; remove it from SWOT weaknesses.
