---
name: ebr-qbr-preparation
description: Use this Claude skill to generate a complete, executive-ready Executive Business Review (EBR) or Quarterly Business Review (QBR) document for any customer, in any industry, for any SaaS or service organization. Trigger this skill whenever a CSM, Customer Success Manager, Account Manager, or anyone mentions: EBR, QBR, business review, executive review, quarterly review, customer review, renewal prep, strategic review, or wants to "present value to a customer." Also trigger when someone says "prepare a review for [customer]", "help me with my QBR", "create an EBR", "draft a business review", or similar phrases. This skill transforms raw customer data, metrics, and context into a polished, strategic narrative suitable for C-suite presentation. Always use this skill — don't just write the document from scratch without it.
---

# EBR / QBR Deck Preparation Skill

## When to Use
Activate when a user asks for help with:
- Preparing an Executive Business Review (EBR)
- Preparing a Quarterly Business Review (QBR)
- Structuring a customer review presentation
- Summarizing customer usage or performance
- Preparing slides for customer meetings

## Instructions

When activated, follow the steps below precisely.

Step 1: Gather Information — Conversational Intake
Ask questions one at a time, in sequence. Wait for the user's answer before asking the
next question. This is a conversation, not a form. Acknowledge each answer briefly before
moving on — it builds trust and signals that you're actively listening.
Key principles:

One question at a time. Never stack multiple questions in a single message.
If an answer is vague or partial, gently probe for more before moving on:
"Got it — do you happen to know [one specific follow-up]?"
If the user says they don't know or don't have something, note it and move on — never block.
When an answer reveals something interesting, briefly reflect it back:
"That's useful context — that'll shape how we frame the Business Impact section."
After each major section completes, give a one-line summary of what was captured
so the user feels progress and can correct anything.
When all questions are done, confirm you're moving to research before proceeding.


Intake Sequence
Work through these questions in order, one at a time.
Skip questions the user has already answered in their opening message.

SECTION A — About You & Your Organization
Q1. What's your organization's name — the company conducting this EBR?
Q2. And what product or platform do you offer?
(A sentence or two is fine — just enough to understand what the customer is using.)
Q3. What's your name and role? I'll use this to personalize the document.

SECTION B — About the Customer
Q4. What's the name of the customer you're preparing this EBR for?
Q5. What industry are they in?
Q6. How large is the customer?
(Headcount, revenue range, number of offices — any rough proxy is fine.)
Q7. What are their top 2–3 business objectives this year?
(What are they trying to achieve as a business — not just from your product.)

SECTION C — Product & Subscription
Q8. Which specific product, plan, or tier has this customer subscribed to?
(e.g., "Enterprise Plan", "Core + Analytics Module", "Starter tier with SSO add-on")
Q9. What are the key features or capabilities included in their subscription?
(List whatever you know — even partial is fine.)
Q10. Of those features — are there any they're not yet using or have barely touched?
Q11. Are there any features or modules that exist in higher tiers or as add-ons that
they are not currently subscribed to?
(This feeds the expansion section — even a rough list helps.)
Q12. How many licenses or seats are contracted, and how many are actively being used?
(e.g., "100 licensed, ~70 active")
Q13. What was the primary use case the customer bought this for?
Q14. Have they adopted any secondary use cases since going live — things they're now
using the product for that weren't the original reason they bought it?
Q15. Are there any professional services, integrations, or add-ons included in their
contract beyond the core product?

SECTION D — Contract Details
Q16. When did the contract start?
Q17. When does it expire or come up for renewal?
(If it's within 90 days, flag this — it changes how the EBR is positioned.)
Q18. What's the contract value — ACV or TCV, whichever you know?
Q19. What's the pricing model — flat fee, per-seat, usage-based, or something else?
Q20. Has the contract been amended, upsold, or discounted since the original signature?
(e.g., added seats, removed modules, applied a renewal discount)
Q21. Are there any outstanding contractual commitments on your side — things the vendor
promised to deliver that are still pending?
(e.g., a feature, integration, training, SLA milestone)
Q22. Have any SLA breach clauses, credits, or penalties been triggered during this period?
Q23. What's the customer's budget cycle or fiscal year?
(Helps us time any expansion or renewal conversation in the EBR.)

SECTION E — This Review Period
Q24. What time period does this EBR cover?
(e.g., Q1 2025, Jan–Mar 2025, H1 2025)
Q25. Is this the first EBR / QBR with this customer, or have there been previous ones?
(If previous:)
Q25b. Do you have the notes or output from the last EBR meeting — action items,
commitments made, decisions reached, or the deck itself?
Please paste, upload, or summarize whatever you have.
(Even rough notes or bullet points are valuable — I'll extract open loops and narrative
threads from them so this EBR explicitly picks up where the last one left off.)
Q25c. Were the commitments from the last review followed through on?
(Which ones were delivered, which are still open, and which slipped?)
Q26. What were the key goals agreed with this customer at the start of this review period?

SECTION F — Data & Charts
This section collects all numbers and datasets that will be turned into charts in the
presentation. The more data provided here, the richer and more visual the deck will be.
Paste raw numbers, tables, spreadsheet exports, or even rough figures — format doesn't matter.
Q27. What product usage data do you have for this period?
(e.g., DAU / MAU numbers by month, feature adoption rates, login frequency)
👉 If you have this as a table or export, paste it directly — it will become a trend chart.
Q28. How has adoption or usage trended compared to the previous period?
(Numbers by month or quarter work best — e.g., "Jan: 340 active users, Feb: 390, Mar: 420")
👉 Month-over-month or quarter-over-quarter data will become a line or bar chart.
Q29. Seat / license utilization — how many contracted vs. active, broken down over time
if possible?
(e.g., "Q1: 100 contracted, 68 active; Q2: 100 contracted, 82 active")
👉 This becomes a utilization gauge or comparison bar chart.
Q30. Support and service data — ticket volumes, resolution times, CSAT or NPS scores?
(By month if possible, and flag any spikes or notable drops.)
👉 Ticket volume trend + CSAT score over time will be charted.
Q31. SLA performance — uptime %, response time averages, incident count?
(Numbers by month or quarter, plus any SLA breach events.)
👉 Uptime % will become a goal-vs-actual bar or scorecard.
Q32. ROI or business impact numbers — cost savings, hours saved, errors reduced,
revenue influenced, process improvements?
(Even rough estimates or ranges are fine — note if they're estimates.)
👉 These become the Business Impact slide's headline stat callouts or comparison charts.
Q33. Do you have any other data that is critical to this customer's business —
numbers they track internally, KPIs they care about, or stats they've shared with you?
(e.g., "They told us their manual process used to take 4 hours, now takes 20 minutes"
or "They shared that error rates dropped from 8% to 1.2% after rollout")
👉 Customer-owned metrics are the most compelling data in any EBR — paste everything.
Q34. Do you have any comparative or benchmark data?
(e.g., industry averages, peer customer benchmarks, prior-period baselines)
👉 Comparisons make individual numbers meaningful — "78% adoption vs. 62% industry avg".
After collecting all data, build a Chart Inventory before generating the PPTX:
CHART INVENTORY

Chart 1 — [Slide 5: Performance]
  Type: Line chart
  Title: "Monthly Active Users — Q1 2025"
  Data: Jan: X, Feb: Y, Mar: Z
  Key callout: [e.g., "23% growth over the quarter"]

Chart 2 — [Slide 5: Performance]
  Type: Bar chart (grouped)
  Title: "Licensed Seats vs. Active Users"
  Data: Contracted: X, Active: Y → utilization = Z%
  Key callout: [e.g., "Up from 68% last quarter"]

Chart 3 — [Slide 6: Business Impact]
  Type: Stat callout (large number)
  Title: "Hours Saved This Quarter"
  Data: X hours
  Key callout: [e.g., "Equivalent to 4.5 FTE months"]

[Continue for all available datasets]

Data Gaps (no numbers provided — use placeholder or qualitative):
  - [e.g., "SLA uptime % — CSM to confirm before presenting"]
Use this inventory to drive chart generation in the PPTX. Every chart must use real
data provided by the CSM — never invent numbers or use placeholder figures in charts.
If data is missing for a chart, use a clearly labelled placeholder graphic with a note:
"[Insert [metric name] data before presenting]"

SECTION G — Who's in the Room
Q35. Who's joining from the customer side?
Let's go through them one by one — start with the most senior person attending.
(For each attendee, ask in sequence:)

What's their full name and job title?
How long have they been in this role?
Do you have their LinkedIn profile URL? (optional but useful)
Anything you know about their priorities, pet topics, or sensitivities?

(Repeat for each attendee until all are captured, then:)
Q35z. Any dynamics between the attendees I should know about?
(e.g., a new exec who may challenge the existing champion, someone historically skeptical)

SECTION H — History & Context
Q36. Beyond the last EBR notes we already covered — do you have any other previous
call notes, meeting summaries, or CRM records you can share or paste in?
I'll mine them for expansion signals and any open commitments I may have missed.
Q37. Any emails, Slack summaries, or support conversations where the customer
said something notable — about the product, their direction, or the relationship?
Q38. Has the customer ever mentioned — even informally — new use cases, new teams
that could benefit, or interest in features they don't currently have?
Q39. Are there any known strategic initiatives the customer is pursuing this year
that are relevant to what your product does?
Q40. Any current market or industry trends you think are affecting this customer
that we should factor into the strategic recommendations?

SECTION I — Final Input
Q41. Is there anything specific you want to make sure gets highlighted or emphasized
in this EBR — a win, a story, a relationship moment?
Q42. Is there anything you want to deliberately keep out of the document or avoid
raising in this meeting?
Q43. Any particular tone, format preference, or examples of past EBRs you'd like
me to match the style of?

Completing Intake
Once all questions have been answered (or skipped), confirm with the user:

"Great — I have everything I need. Here's a quick summary of what we've captured:
[Vendor], [Product] | Customer: [Customer Name], [Industry]
Subscription: [Plan/Modules] | Contract: [Value, renewal date]
Review period: [Period] | Attendees: [Names & titles]
Previous EBR notes: [Captured / Not provided]
Charts I can generate from your data: [List chart titles from Chart Inventory]
Data gaps flagged for your review: [List any missing datasets]
I'll now move into research — audience profiling, interaction history, external signals,
and expansion opportunities — before drafting both documents. Let's go."


How Contract & Product Data Shapes the EBR
Once collected, use contract and product data to drive these specific sections:
Data PointHow It Is UsedSubscribed modules vs. unused featuresGrowth section — frame unused features as untapped value, not a sales pitchLicensed seats vs. active usersPerformance section — adoption rate; Growth section — seat expansion opportunityContract renewal dateRoadmap section — time the renewal conversation; flag to CSM if within 90 daysACV / TCVBusiness Impact section — frame ROI relative to contract investmentSLA breach clauses triggeredChallenges section — must be addressed directlyOutstanding vendor commitmentsChallenges / Next Steps — acknowledge and update statusBudget cycleStrategic Recommendations — time expansion proposals to align with budget windowsFeatures adopted beyond original use caseKey Achievements — strong proof of platform stickinessHigher-tier features not in subscriptionGrowth section — concrete, value-anchored upsell

Step 2: Conduct Research (Before Writing)
Always run this research step after gathering intake. This step has two parallel objectives:

Engagement health — find signals that affect the customer's appetite to renew, expand,
reduce, or re-prioritize the partnership
Expansion identification — surface genuine opportunities to grow the engagement, grounded
in both the customer's own history with the vendor and external signals

Every finding must pass at least one of these two tests:

"Does this change how the customer values, uses, or is likely to invest in our product?"
"Does this reveal an unmet need, new use case, or adjacent problem our product could solve?"

Research in parallel where possible. Clearly label anything sourced from research.
2a. Mine Historical Customer Interactions (Expansion & Continuity Focus)
Run this before any web research. The richest expansion signals are almost always
already in the customer's own words — buried in previous EBRs, call notes, emails, or
casual comments. Extract them before reaching for external data.
Sources to process (in order of richness):

Previous EBR / QBR documents or summaries
Call notes, meeting summaries, or CRM records
Support tickets or escalation threads with strategic commentary
Email chains or Slack summaries the CSM has shared
Any NPS/CSAT verbatim comments

For each source, extract the following signals:
Expansion Opportunity Signals
Look for any moment — explicit or implied — where the customer expressed:

Interest in features, modules, or capabilities they don't currently use
Pain points that the vendor's product could solve but hasn't been configured to
New teams, departments, or regions that might benefit from the product
Workflow gaps or manual workarounds mentioned in passing
Positive outcomes they wished they could replicate elsewhere
Questions about pricing, packaging, or "what else" the vendor offers
Requests that were deferred or deprioritized — they may still be live

Expansion Signal Catalogue:
Signal ObservedSource & DateExpansion OpportunityConfidence[e.g., "CFO asked if we could run this for APAC team too"][Call notes, Nov 2024]Geographic expansion — APAC rolloutHigh[e.g., "Ops lead mentioned manual reporting still a problem"][Previous EBR, Q3 2024]Automate reporting module — currently unused]Medium
Commitments & Open Loops
Extract any unresolved commitments from previous interactions — both vendor-made and
customer-made. These must be addressed explicitly in this EBR.
CommitmentMade ByDateStatus[e.g., "We will deliver SSO integration by Q1"]VendorEBR Q3 2024[Follow up][e.g., "Customer to schedule training for new joiners"]CustomerCall Dec 2024[Follow up]
Sentiment & Relationship Trajectory
Note how the tone of interactions has shifted over time:

Are executive sponsors more or less engaged than in previous reviews?
Has the champion changed or gone quiet?
Have there been repeated frustrations that haven't been formally resolved?
Is there growing enthusiasm in any area that signals expansion readiness?

Narrative Continuity
Identify 2–3 threads from the previous EBR that this review should explicitly close or
advance. Customers notice when their own words and concerns disappear between reviews.


2b. Audience Research — Know Everyone in the Room
Run this for every named attendee from the customer side. The same EBR content lands
very differently depending on who is sitting across the table. A CFO needs to hear about
cost and risk. A CTO wants reliability and roadmap. A Head of Ops wants efficiency and
adoption. Knowing the room lets the CSM frame the right story to the right people.
For each attendee, run the following:
Step 1 — LinkedIn Profile Research
If a LinkedIn URL was provided, fetch it directly. If not, search:

"[Full Name]" "[Company Name]" LinkedIn
"[Full Name]" "[Job Title]" "[Company Name]"

Extract from their profile:

Current role and how long they've been in it (new to role = still forming vendor opinions)
Career background and prior companies (what worlds do they come from?)
Any content they've posted, shared, or liked recently (what are they publicly thinking about?)
Skills, endorsements, or certifications that hint at priorities
Any mutual connections the CSM might mention to build rapport


⚠️ Privacy Rule: Only use publicly available LinkedIn information. Do not attempt
to access gated content. Summarize findings professionally — never quote personal posts
verbatim in the EBR documents. Use insights to shape framing and talking points only.

Step 2 — Designation-Level Intelligence
If a LinkedIn profile is unavailable or sparse, infer priorities from the job title alone
using the designation intelligence table below:
DesignationPrimary LensWhat They Need to Walk Away WithCEO / MD / PresidentStrategic growth, competitive position, board narrative"This partnership is accelerating our strategy"CFO / VP FinanceROI, cost control, risk, budget justification"We are getting measurable value for this spend"CTO / CIO / VP EngineeringReliability, security, integration, technical roadmap"The platform is sound and keeps up with our needs"COO / VP OperationsEfficiency, process improvement, adoption, scale"This is making our operations faster and leaner"CPO / VP ProductRoadmap alignment, innovation, feature velocity"Their roadmap will help us build better products"CHRO / VP PeopleUser experience, change management, team enablement"Our teams are actually using and benefiting from this"VP Sales / CRORevenue impact, pipeline, customer-facing outcomes"This helps us win and retain more customers"Head of IT / IT DirectorUptime, security, support quality, integration health"It works reliably and support is responsive"Procurement / Vendor MgmtContract value, compliance, renewal terms"The contract delivers on its commitments"Champion / Power UserFeature depth, roadmap, day-to-day value"My team gets more done because of this tool"
Step 3 — Build an Audience Profile Card for Each Attendee
ATTENDEE PROFILE: [Full Name]
Title: [Designation]
Time in Role: [e.g., "8 months — relatively new"]
LinkedIn: [URL or "Not available"]

What Matters to Them (based on role + LinkedIn signals):
  - [Priority 1 — e.g., "Publicly posting about AI-driven cost reduction in logistics"]
  - [Priority 2 — e.g., "Recently shared article on vendor consolidation"]
  - [Priority 3 — e.g., "Background in finance — will scrutinize ROI claims carefully"]

Inferred Sensitivities:
  - [e.g., "New to role — may want to demonstrate value to their own stakeholders"]
  - [e.g., "Previously at a competitor — may have strong prior tool preferences"]

Key Message to Land With This Person:
  [One sentence that will resonate most based on their lens]

Slide / Section to Emphasize for This Person:
  [e.g., "Business Impact (Slide 6) and ROI numbers need to be tight for this attendee"]

Talking Point Suggestion for CSM:
  [e.g., "Reference their recent LinkedIn post about supply chain visibility —
  segue into how our analytics feature directly addresses that"]
Step 4 — Compose the Room Summary
After profiling all attendees, write a one-paragraph room-level summary:
ROOM SUMMARY
[e.g., "The room skews financial and operational — the CFO and COO will dominate the
conversation. The CTO is likely observing for technical soundness. Lead with ROI and
efficiency outcomes, keep technical detail in the appendix. The VP of Sales is new to
the account — open with context on the partnership history before diving into metrics.
The champion (Head of Ops) will be the internal ally — direct energy-boosting moments
toward them to strengthen their position internally."]

2c. Customer Company Research (Engagement-Impact Focus)
Search for recent customer news and filter ruthlessly for engagement relevance.
Search queries to run:

"[Customer Company Name]" news [current year]
"[Customer Company Name]" earnings OR "annual report" OR strategy [current year]
"[Customer Company Name]" layoffs OR restructuring OR "cost cutting" [current year]
"[Customer Company Name]" leadership OR "executive team" [current year]
"[Customer Company Name]" technology OR "digital transformation" OR investment [current year]

Engagement-relevant signals to prioritize:
Finding TypeEngagement ImpactBudget cuts / cost-reduction programsRenewal risk — EBR must lead with hard ROINew CTO / CIO / COO / VP of OpsStakeholder risk — new exec may re-evaluate vendor stackAcquisitions or mergersScope change — may expand or consolidate engagementRapid headcount growth or new business unitsExpansion signal — new teams may need the productStated digital transformation initiativeAlignment opportunity — position vendor as enablerFunding secured (startup/scaleup)Upsell window — investment typically precedes expansionFinancial distress or public downgradeChurn risk — flag internally, tone the EBR carefully
Discard: General PR, awards, or any news with no plausible link to the vendor engagement.

2d. Industry & Market Trends Research (Engagement-Impact Focus)
Search for industry trends, then ask: "Does this create new urgency, relevance, or risk
for the customer's specific use of our product/service?"
Search queries to run:

[Customer Industry] trends [current year]
[Customer Industry] challenges OR headwinds [current year]
[Customer Industry] regulation OR compliance [current year]
[Customer Industry] [relevant tech category e.g. "AI adoption"] [current year]

Engagement-relevant signals to prioritize:

Regulatory changes that make the vendor's product more (or less) critical to compliance
Industry-wide cost pressure that makes ROI conversations more urgent
Technology mandates or standards the vendor's product helps the customer meet
Competitive shifts creating pressure to consolidate tools or move faster

Frame each trend as: "[Trend] → [Why this makes our engagement more/less important now]"

2e. Competitive & Vendor Landscape Research (run always)
Understanding what alternatives the customer could consider strengthens every EBR conversation.
Search queries to run:

[Vendor Product/Service] alternatives OR competitors [current year]
[Customer Industry] best [product category] [current year]
"[Customer Company Name]" AND "[Vendor/Product Name]" (check for public mentions)

Engagement-relevant signals to prioritize:

Competitors gaining ground in the customer's specific industry segment
Peer companies that recently switched away from or to this vendor
Notable capability gaps vs. competitors that could surface in a renewal conversation

Note: Do not present competitive research in the EBR. Use it to sharpen the CSM's
narrative and prepare them for tough renewal or upsell objections.

2f. Research Summary — Engagement, Expansion & Audience Map
Build this map before writing. Every entry must pass one of the two Step 2 objectives
(engagement health or expansion identification), or directly inform audience tailoring.
RESEARCH FINDINGS — ENGAGEMENT, EXPANSION & AUDIENCE MAP

Audience Intelligence:
  [Paste Attendee Profile Cards from Step 2b here — one per attendee]

  Room Summary: [Paste the Room Summary paragraph here]

  Presentation Tailoring Notes:
    - Sections to emphasize given this room: [e.g., "Business Impact, ROI"]
    - Sections to keep brief: [e.g., "Technical detail — move to appendix"]
    - Opening framing: [e.g., "Start with partnership story for the benefit of new CFO"]
    - Tone calibration: [e.g., "More formal — CFO and COO set the register"]
    - Watch out for: [e.g., "CTO has strong opinions on vendor lock-in — avoid this language"]

Historical Interaction Intelligence:
  Expansion Signal: [e.g., "APAC expansion mentioned in Nov 2024 call"]
  Confidence: High / Medium / Low
  Opportunity Type: [Geographic / New Team / Unused Feature / New Use Case / Upsell]
  Evidence: [Exact quote or paraphrase from source + date]
  Recommended Action in EBR: [e.g., "Surface in Growth section with APAC-specific ROI"]

  Open Loop: [e.g., "SSO integration promised for Q1 — not yet delivered"]
  Status: [Delivered / Overdue / In Progress]
  How to Address: [e.g., "Acknowledge in Challenges section + give updated timeline"]

  Sentiment Shift: [e.g., "Champion less engaged since Nov — 2 no-shows to check-ins"]
  Risk Level: High / Medium / Low
  Recommended Action: [e.g., "Flag to CSM privately; do not surface in EBR"]

Customer Intelligence:
  Finding: [e.g., "Acme Corp announced 15% workforce reduction in Jan 2025"]
  Engagement Impact: [e.g., "Budget scrutiny likely — EBR must lead with hard ROI data"]
  Expansion Implication: [e.g., "Consolidation may open door for broader platform deal"]
  Where to use in EBR: [e.g., "Business Impact section, Executive Summary tone"]

Industry Trends:
  Trend: [e.g., "DORA compliance deadline for EU financial firms: Jan 2026"]
  Engagement Impact: [e.g., "Our audit trail features directly support DORA readiness"]
  Expansion Implication: [e.g., "Compliance module could expand to legal and risk teams"]
  Where to use in EBR: [e.g., "Strategic Recommendations, Industry Context section"]

Competitive Context:
  Finding: [e.g., "Competitor X launched lower-cost tier targeting mid-market"]
  Engagement Impact: [e.g., "Renewal risk if customer is price-sensitive"]
  Where to use in EBR: [e.g., "Prepare CSM for pricing objections; Growth section"]

Expansion Opportunity Summary (synthesized):
  Opportunity 1: [Name] | Type: [Feature / Geo / Team / Use Case] | Confidence: [H/M/L]
  Opportunity 2: [Name] | Type: [Feature / Geo / Team / Use Case] | Confidence: [H/M/L]
  Opportunity 3: [Name] | Type: [Feature / Geo / Team / Use Case] | Confidence: [H/M/L]

Confidence Rating: [High / Medium / Low — and why]
Discarded Findings: [Anything researched but not engagement- or expansion-relevant]

⚠️ Research Integrity Rule: Only include findings verifiable from credible sources
or directly traceable to customer-provided interaction history.
Flag uncertain findings with [Unverified — please confirm before presenting].
Never fabricate company news, financial data, interaction history, or LinkedIn activity.


2g. CSM Field Intelligence — Personal Notes Placeholder
After sharing the full Research, Expansion & Audience Map, always ask the CSM:

"Here's everything I've found — audience profiles for everyone joining from the
customer side, expansion opportunities from your past interactions, and external
research. A few questions before I draft:

Do the audience profiles feel accurate? Anything I've missed or got wrong about
any of the attendees — their priorities, sensitivities, or what they'll care about?
Are there any dynamics between the attendees I should know about?
(e.g., a new exec who may challenge the champion, or someone who's historically skeptical)
Do the expansion opportunities match what you're sensing? Any to add or remove?
Any open loops or past commitments not captured in the documents you shared?
Any relationship dynamics or sensitivities I should be aware of?
Champion / sponsor health — is your main contact still engaged and supportive?
Informal signals or themes from recent conversations not captured above?
Specific wins, stories, or moments you want highlighted?
Any talking points or asks you want to land in this meeting?
Anything you want intentionally kept out?

Rough notes are completely fine — just share what's on your mind."

Treat CSM field intelligence as the highest-priority input. It can override, sharpen, or
deprioritize any finding from audience research, expansion signals, or external data.
If the CSM has nothing to add, embed this visible placeholder in the final document:


📝 CSM Notes — Before You Present:

[ ] Confirm audience profiles are accurate and sensitivities are noted
[ ] Note any inter-attendee dynamics to be aware of in the room
[ ] Confirm expansion opportunities are valid and well-timed
[ ] Verify all open loops and past commitments are addressed
[ ] Relationship context or sensitivities
[ ] Champion / sponsor health
[ ] Verbal feedback or informal signals from recent interactions
[ ] Specific talking points or asks for this meeting
[ ] Anything to emphasize or intentionally avoid




Step 3: Internal Analysis (Think Before Writing)
Before generating the documents, internally reason through the following — incorporating
CSM-provided data, historical interaction intelligence, and external research findings:

Customer Goal Alignment — How well does the data show progress against stated goals?
Value Translation — Convert raw metrics into business outcomes, not just numbers.
Highlight vs. Concern Balance — Identify 2–3 wins and 1–2 honest risk/challenge areas.
Audience Tailoring — Given the Room Summary, how should the narrative be framed?
Which sections need to be reinforced, shortened, or reordered to serve the specific
people in the room? What language, metrics, and examples will resonate most with each
attendee's lens? Are there any sensitivities that should shape tone or omission?
Narrative Continuity — What threads from the previous EBR must be explicitly picked up,
closed, or advanced? The customer will notice if their past concerns vanish without resolution.
Open Loop Audit — Are all past commitments (vendor and customer) acknowledged and
addressed? Unresolved commitments left out of the EBR damage trust.
Expansion Opportunity Scoring — From all signals collected, rank each expansion
opportunity on two dimensions:

Evidence strength: Is this grounded in something the customer actually said or did,
an external signal, or an assumption?
Timing readiness: Is now the right moment to surface this, or would it feel premature
or tone-deaf given the current engagement health?
Only include expansion opportunities that score reasonably on both dimensions.


Strategic Framing — What narrative connects product performance to their business
strategy AND the external trends and customer history uncovered in research?
Research Integration — Which research findings strengthen the narrative, open strategic
conversations, or credibly justify an expansion recommendation?
Next Steps Logic — What are the most impactful actions for the next period?
Executive Tone Check — Is every section concise, strategic, and free of jargon?


Step 4: Generate All Three Output Documents
This skill always produces three documents — no exceptions. Generate them in this order:
Document 1: EBR/QBR Presentation (PPTX)
Document 2: Research Intelligence Report (DOCX)
Document 3: Roleplay & Talking Points Guide (DOCX)
All three are produced in the same run. Tell the user upfront:

"I'll produce three files: the EBR presentation deck, a research intelligence report
with all findings, and a roleplay guide so you can rehearse the meeting and prepare
for every question and objection before you walk in the room."


⛔ Document Generation Guardrail
Before delivering anything to the user, verify all three files exist and are complete.
After generating all three documents, run this check:
DOCUMENT COMPLETION AUDIT

[ ] Document 1 — EBR Presentation (PPTX)
    File exists: YES / NO
    Slides generated: [count] of 13 expected
    Charts built: [count] | Placeholders used: [count]
    Internal slides (12, 13) present and hidden: YES / NO

[ ] Document 2 — Research Intelligence Report (DOCX)
    File exists: YES / NO
    Sections present: [count] of 6 expected
    Audience Intelligence section populated: YES / NO

[ ] Document 3 — Roleplay & Talking Points Guide (DOCX)
    File exists: YES / NO
    Sections present: [count] of 7 expected
    Slide talking points generated for slides 1–11: YES / NO
    Q&A blocks generated for all [X] attendees: YES / NO
If any file is missing or any section is incomplete:

Do NOT deliver partial output
Do NOT ask the user to wait while you fix it — fix it silently first
Re-generate the missing file or section before proceeding
Only present files to the user once all three pass the audit

If a file could not be generated due to a technical error:

Tell the user which file failed and why
Offer to retry immediately
Never deliver two files and describe the third as "coming soon"

The user should receive all three files in a single delivery message — not one at a time.

Document 1: EBR Presentation (PPTX)
Always read /mnt/skills/public/pptx/SKILL.md and follow its instructions to create this file.
The presentation is the primary customer-facing deliverable. Build it as a polished PPTX
using pptxgenjs. Do not produce a Markdown draft and ask — go straight to the file.
Integrate research findings naturally throughout — do not add a "research" slide.
Research surfaces as context, framing, and supporting evidence within the existing sections.
Chart Generation Rules
Every chart must use real data provided by the CSM during intake — never invent numbers.
Use the Chart Inventory built during Section F of intake to determine which charts to build.
Apply these chart type decisions:
Data TypeChart TypeSingle metric over time (monthly/quarterly)Line chart with data point labelsTwo metrics compared over time (e.g., contracted vs. active seats)Grouped bar chartSingle-period comparison (e.g., this quarter vs. last)Side-by-side bar or % change calloutAdoption rate / utilization %Gauge-style or filled bar with % labelA single large headline number (hours saved, cost saved)Large stat callout — number dominant, label belowSupport ticket trend + CSATDual-axis line chart (volume on left, CSAT score on right)RAG status across multiple goalsColour-coded table with ✅ ⚠️ ❌Before / after comparisonTwo-column layout with contrastMultiple KPIs at a glanceKPI card grid (2×2 or 2×3)
If data is missing for a planned chart:

Do not skip the slide or leave it blank
Render the chart as a clearly styled placeholder with the message:
📊 [Chart title] — insert [metric name] data before presenting
Use a muted/greyed colour scheme for placeholder charts so the CSM knows at a glance
which slides need data filled in before the meeting

Customer-provided business stats (Q33) get special treatment:

These are the most compelling data points in any EBR — the customer's own numbers
Surface them as large callout stats or "before vs. after" visuals, not buried in tables
Always attribute them: "As reported by [Customer Name]"

Slide Structure
SlideTitleContent1CoverOrg × Customer name, Review Period, CSM name/team, date2Executive Summary3–5 sentence prose narrative — partnership health, top win, one candid challenge, forward commitment3Customer Objectives & Success CriteriaTable: Objective / KPI / RAG status (✅ ⚠️ ❌)4Key Achievements3–5 bold outcome bullets with supporting data5Performance & Usage InsightsAdoption %, support metrics, SLA — trends not snapshots6Business ImpactLead with $ / hours / risk — use [Metric → Business Outcome] formula7Industry & Market Context2–3 engagement-relevant trends with source citations8Challenges & Risk AreasPer-challenge: name / root cause / action taken / status9Strategic Recommendations3–5 recs — each with Context / Action / Outcome / Why Now10Growth & Expansion OpportunitiesOnly if genuinely relevant — "unlocking value" framing11Roadmap & Next StepsTable: Action / Owner / Target Date + closing commitment12Audience Intelligence (internal — mark as hidden/appendix)See format below13CSM Notes (internal — mark as hidden/appendix)See format below
Slide 12 — Audience Intelligence (Internal / Hidden):
One profile block per attendee. This is the CSM's in-room cheat sheet — concise enough
to glance at during the meeting. Design it as a clean card layout (one card per person).
[Name] — [Title]
🎯 What they care about: [1–2 key priorities]
💬 Key message for them: [One sentence]
⚠️  Watch out for: [Sensitivity or likely objection]
📌 Talking point: [One specific, research-backed hook]
Slide 13 — CSM Notes (Internal / Hidden):
This slide is for the CSM's eyes only. Include:
📝 CSM NOTES — Before You Present

[ ] Audience profiles confirmed and sensitivities noted
[ ] Inter-attendee dynamics to manage:
    _________________________________________________
[ ] Expansion opportunities validated and timed:
    _________________________________________________
[ ] Open loops / past commitments all addressed:
    _________________________________________________
[ ] Relationship context or sensitivities:
    _________________________________________________
[ ] Champion / sponsor health:
    _________________________________________________
[ ] Verbal signals from recent conversations:
    _________________________________________________
[ ] Specific talking points or asks:
    _________________________________________________
[ ] Things to avoid:
    _________________________________________________
Design guidelines: Follow the PPTX skill's design principles — bold color palette,
varied layouts (stats callout, two-column, icon+text), no text-only slides, no accent lines
under titles. Pick a palette that fits the customer's industry and the vendor's brand tone.

Document 2: Research Intelligence Report (DOCX)
Always read /mnt/skills/public/docx/SKILL.md and follow its instructions to create this file.
This document captures all research findings from Step 2 — including those that were
filtered out as not engagement-relevant. Its purpose is to give the CSM a complete picture
of what was found, ranked by how likely it is to matter, even if it didn't make the slides.
The audience is the CSM alone — this is an internal working document, not customer-facing.
Document Structure
RESEARCH INTELLIGENCE REPORT
[Customer Company Name] EBR — [Review Period]
Prepared by: AI Research Assistant | [Date]
For internal CSM use only

Section 1: Audience Intelligence (attendee profiles — internal use only)
Full Attendee Profile Cards generated in Step 2b, including:

LinkedIn research summary per person
Designation-level intelligence applied
Key message, talking point, and sensitivity per attendee
Room Summary paragraph


Section 2: Engagement-Critical Findings (used in the presentation)
Section 2: Engagement-Critical Findings (used in the presentation)
These findings directly shaped the EBR narrative. Listed with full context.
For each finding:
Finding: [Specific, factual statement]
Source: [Publication / URL / Report name]
Confidence: High / Medium / Low
Engagement Impact: [How this affects the vendor-customer relationship]
Used In: [Which slide/section it informed]

Section 3: Notable Findings — Not Used in EBR (ranked by potential importance)
Findings that were researched and verified but deemed not directly relevant to the EBR.
Ranked in descending order of potential importance — most strategically significant first.
Ranking criteria (apply in order):

Could affect renewal decision or budget allocation
Could affect stakeholder dynamics or executive alignment
Could signal future expansion or contraction of scope
Industry/regulatory change with long-term relevance
Competitive intelligence worth monitoring
General market context — informative but not action-driving

For each finding:
Rank: [#]
Finding: [Specific, factual statement]
Source: [Publication / URL]
Confidence: High / Medium / Low
Why Not Used: [Brief reason — e.g., "No direct link to current product usage"]
Why It Might Matter Later: [Forward-looking note]

Section 4: Discarded / Unverifiable Findings
Items excluded because they could not be verified, were clearly irrelevant, or came from
low-credibility sources.
Finding: [What was found]
Source: [Where it appeared]
Reason Discarded: [Unverifiable / Irrelevant / Low-credibility source / Duplicate]

Section 5: Research Gaps
Areas where research was attempted but yielded insufficient data.
Research Gap: [Topic that was searched but not resolved]
Queries Attempted: [What was searched]
Suggested Follow-up: [How the CSM might close this gap]

Section 6: CSM Field Intelligence
Pre-filled with any notes the CSM provided in Step 2g. If nothing was provided, this section
contains the full placeholder for the CSM to complete before the meeting.
📝 CSM NOTES — Add Before Presenting

Audience dynamics or inter-attendee sensitivities:
[CSM input or blank]

Relationship dynamics or sensitivities:
[CSM input or blank]

Champion / sponsor health:
[CSM input or blank]

Verbal feedback or informal signals:
[CSM input or blank]

Specific talking points or asks:
[CSM input or blank]

Anything to emphasize or intentionally avoid:
[CSM input or blank]

Research Report Design
Use professional but utilitarian formatting — this is a working document, not a presentation.

Clear section headings (H1/H2 in the DOCX)
Consistent table format for findings
Color-code confidence levels: green (High), amber (Medium), red (Low)
Include page numbers and a document header with customer name + date
Keep font clean: Arial 11pt body, Arial Bold for headings


Document 3: Roleplay & Talking Points Guide (DOCX)
Always read /mnt/skills/public/docx/SKILL.md and follow its instructions to create this file.
This is the CSM's private rehearsal document — built to simulate the meeting before it
happens. It gives the CSM scripted talking points for every slide, anticipated questions and
objections from each attendee based on their profile, and model responses to practise aloud.
The goal: the CSM should be able to walk into the meeting having already had it once.
Audience: CSM only — strictly internal. Never shared with the customer.
Document Header
ROLEPLAY & TALKING POINTS GUIDE
[Customer Company Name] EBR — [Review Period]
Prepared for: [CSM Name] | [Date]
STRICTLY INTERNAL — DO NOT SHARE

Section 1: Meeting Opening — How to Start
Provide a scripted opening the CSM can practise word for word. It should:

Welcome everyone by name (use attendee list from intake)
Frame the purpose of the meeting in one sentence
Acknowledge any new faces (e.g., a recently joined exec) and briefly orient them
Set the agenda and expected duration
Open on a positive but credible note — not sycophantic

SUGGESTED OPENING (practise this aloud):

"Thanks everyone for making time today — [names]. For those joining for the first time,
I'm [CSM Name] from [Vendor], and I've been working with your team since [start date].

Today's agenda: we'll cover [three-line summary of sections], and we're aiming to
wrap in [X] minutes. I want to make sure we leave [Y] minutes at the end for open
questions and to align on next steps together.

Let me start with something I'm genuinely proud of from this past [period]..."
Provide 2–3 variations of the opening so the CSM can pick the tone that fits the room.

Section 2: Slide-by-Slide Talking Points
For every slide in the deck, provide:
────────────────────────────────────────────
SLIDE [#]: [SLIDE TITLE]
────────────────────────────────────────────

🎤 WHAT TO SAY (30–60 second verbal narrative):
[Scripted or semi-scripted delivery — what to say out loud, not just what's on the slide.
Written in first-person, natural spoken language. Includes transitions to the next slide.]

💡 KEY POINT TO LAND:
[The one thing that must land from this slide — if they remember nothing else.]

📊 HOW TO PRESENT THE DATA (if this slide has a chart):
[How to walk through the chart — what to point to first, what the trend means,
what comparison to draw the audience's attention to.]

🔗 TRANSITION TO NEXT SLIDE:
[One sentence bridge to maintain narrative flow.]
Generate this block for every slide (1–11). Slides 12–13 are internal and need no talking points.

Section 3: Anticipated Questions — By Attendee
For each customer attendee, generate a personalised Q&A block based on their
role, LinkedIn profile, known sensitivities, and the content of the EBR.
Structure each block as a simulated roleplay exchange:
────────────────────────────────────────────
ANTICIPATED QUESTIONS FROM: [Name] — [Title]
Based on: [Role lens + any LinkedIn/profile signals]
────────────────────────────────────────────

Q: "[Likely question they will ask — written in their voice]"
→ BEST RESPONSE: [Model answer — specific, confident, not defensive. 2–4 sentences.]
→ SUPPORTING DATA: [Which slide or stat backs this up]
→ IF THEY PUSH BACK: [One more sentence if they challenge the answer]

Q: "[Second likely question]"
→ BEST RESPONSE: [...]
→ SUPPORTING DATA: [...]
→ IF THEY PUSH BACK: [...]

[Generate 3–5 questions per attendee based on their profile]
Use designation-level intelligence from Step 2b to anticipate question style:

CFO questions tend to be about ROI, cost per outcome, and contract value justification
CTO questions tend to be about reliability, architecture, roadmap, and security posture
COO questions tend to be about adoption rates, process efficiency, and operational risk
New executives tend to ask "why did you choose this approach?" and "what would you do differently?"
Champions tend to ask about roadmap and what they need to do to expand internally


Section 4: Objection Handling Playbook
Cover the most likely objections this specific customer might raise, based on
the EBR content, the contract situation, the engagement health, and the attendee profiles.
Each objection gets a full response card:
────────────────────────────────────────────
OBJECTION: "[Exact phrasing they might use]"
Likely from: [Which attendee / role]
Trigger: [What in the EBR or context makes this likely]
────────────────────────────────────────────

ACKNOWLEDGE: [One sentence that shows you heard them — not defensive]

REFRAME: [Shift the frame before answering — e.g., "That's exactly why we..."]

RESPOND: [The actual answer — specific, data-backed, 3–5 sentences]

CLOSE THE LOOP: [One sentence that checks they're satisfied and moves forward]

DANGER ZONE: [What NOT to say — the defensive or dismissive response that would backfire]
Always include cards for these universal EBR objections (plus any specific to this customer):

"The adoption numbers are lower than I expected"
"We're not sure we're getting the value for what we're paying"
"There have been some service issues I'm still concerned about"
"I want to revisit the contract terms before we discuss renewal"
"We've been looking at [competitor] — how do you compare?"
"This is a lot of information — what's the one thing I should take away?"

Add any objections specific to this customer based on known challenges, open loops,
sentiment signals, or competitive threats surfaced in research.

Section 5: Expansion Conversation Guide
For each expansion opportunity identified in Step 2, provide a scripted conversation
opener the CSM can use to introduce the topic naturally — without it feeling like a
sales pitch mid-review.
────────────────────────────────────────────
EXPANSION OPPORTUNITY: [Name of opportunity]
Best moment to raise: [Which slide / moment in the meeting]
────────────────────────────────────────────

NATURAL OPENER (practise this — it should feel like observation, not pitch):
"[Something like: 'One thing that's come up in conversations with similar customers
in your space is [X] — and actually, looking at how your team has been using [feature],
I think there's a version of that opportunity here too. Worth a quick conversation?']"

IF THEY SHOW INTEREST:
[2–3 sentences to advance the conversation — value framing, not feature list]

IF THEY DEFLECT:
[One sentence to acknowledge and park it gracefully without killing it]
[e.g., "Completely understand — maybe something for the next review cycle."]

DO NOT:
[What to avoid — e.g., "Don't jump straight to pricing", "Don't present the
feature list unprompted", "Don't frame it as 'we'd like to sell you more'"]

Section 6: Closing the Meeting — How to End Strong
Provide a scripted close the CSM can use to wrap the meeting with energy and clarity:
SUGGESTED CLOSE (practise this aloud):

"Before we wrap — I want to make sure we're aligned on what happens next.
[Read through the Next Steps table from Slide 11 — action, owner, date for each item.]

From our side, I'll [specific commitment] by [date].
From your side, we'd need [specific ask] by [date] to keep things on track.

Is there anything from today that we didn't cover, or anything you want to revisit?

[Pause and listen.]

Thank you all for the time and the honest conversation. We're genuinely invested in
[customer name]'s success, and I'm looking forward to [next milestone]."
Provide a shorter variant for when time is running out.

Section 7: Post-Meeting Follow-Up Checklist
Immediately after the meeting, the CSM should:
WITHIN 24 HOURS:
[ ] Send follow-up email with: summary of key points, confirmed next steps + owners + dates
[ ] Log any new expansion signals or objections raised in CRM
[ ] Update open loop tracker — mark items resolved, flag new ones
[ ] Note any executive sentiment shifts observed in the room
[ ] Flag any renewal risk signals to internal stakeholders if applicable

WITHIN ONE WEEK:
[ ] Deliver on any immediate commitments made in the meeting
[ ] Schedule the next check-in or milestone review if agreed
[ ] Draft agenda for next EBR based on open items from this one

Roleplay Document Design

Use clear visual separation between sections (thick horizontal rules)
Each roleplay exchange should be visually distinct — use bordered boxes or shading for Q&A cards
Objection cards and expansion openers should be formatted like playbooks — scannable in seconds
Use bold for what to say, italics for what not to say
Page numbers + section bookmarks so the CSM can navigate quickly during prep
Header on every page: "[Customer Name] EBR Roleplay Guide — INTERNAL ONLY"


Step 5: Quality Check Before Delivering
Do not proceed to delivery until all three documents have passed both the Document
Completion Audit (Step 4 guardrail) AND the content checks below.
If a document fails any check — fix it before moving on. Never deliver to compensate.
Presentation (PPTX):

 Chart Inventory was built from Section F data before generating the PPTX
 Every chart uses real CSM-provided data — no invented numbers anywhere
 Charts with missing data have clearly styled placeholder graphics, not blank slides
 Customer-owned business stats (Q33) are surfaced as headline callouts or before/after visuals
 Last EBR notes were mined and open commitments are explicitly addressed
 LinkedIn / designation research completed for every named customer attendee
 Attendee Profile Cards built and Room Summary written
 Narrative framing reflects the Room Summary — right emphasis for this audience
 Historical interaction history mined for expansion signals and open loops
 All open loops and past commitments from previous EBRs explicitly addressed
 Expansion opportunities grounded in evidence — not wishful thinking
 Research findings woven in naturally — no standalone "research" slide
 Every research-sourced claim has a source citation on the slide
 Metrics translated to business outcomes — not raw numbers
 Narrative continuity — threads from previous EBR picked up and advanced
 Tone calibrated to the room — executive-level, strategic, concise
 Challenges section honest and constructive
 Growth section only includes opportunities with solid evidence and good timing
 Strategic Recommendations have Context / Action / Outcome / Why Now
 Next Steps specific, owned, and time-bound
 Slide 12 (Audience Intelligence) present and marked internal/hidden
 Slide 13 (CSM Notes) present and marked internal/hidden
 No jargon the customer's executives wouldn't know

Research Intelligence Report (DOCX):

 Section 1: Audience Intelligence — all attendee profiles and Room Summary included
 LinkedIn findings summarized professionally (no verbatim post quotes)
 Interaction history mining captured (expansion signals, open loops, sentiment)
 Sections 2–6 all present
 Section 3 (not-used findings) ranked in descending importance order
 Expansion Opportunity Summary table populated
 Every finding has: source, confidence level, engagement and/or expansion note
 Discarded findings logged with reason
 Research gaps identified with suggested CSM follow-up
 CSM Field Intelligence present — pre-filled or blank placeholder
 Document marked "For internal CSM use only"

Roleplay & Talking Points Guide (DOCX):

 Section 1: Meeting opening — 2–3 scripted variants, personalised with attendee names
 Section 2: Slide-by-slide talking points — every slide 1–11 covered with full block
 Section 3: Anticipated Q&A — 3–5 questions per attendee based on their profile/role
 Section 4: Objection playbook — 6 universal objections + any customer-specific ones
 Section 5: Expansion conversation guide — one opener per expansion opportunity
 Section 6: Closing script — full version + short variant for when time is short
 Section 7: Post-meeting follow-up checklist included
 All Q&A and objection cards formatted for quick scanning — not walls of prose
 Talking points written in natural spoken language — not slide bullet language
 Document marked "STRICTLY INTERNAL — DO NOT SHARE"


Step 6: Deliver & Offer Follow-Up
Final gate before delivery — confirm all three files are present:
✅ Document 1: [filename].pptx — READY
✅ Document 2: [filename]-research.docx — READY
✅ Document 3: [filename]-roleplay.docx — READY
If any line shows ❌ — stop, fix, re-audit before presenting files to the user.
Only once all three show ✅, deliver them together in a single message:

"Here are your three files:
📊 [Customer] EBR Deck — the customer-facing presentation with [X] slides and [Y] charts
🔍 Research Intelligence Report — all findings including what didn't make the slides, ranked by importance
🎭 Roleplay & Talking Points Guide — slide-by-slide scripts, Q&A by attendee, objection playbook, and expansion openers. Practise this before you walk in."

Then offer:

Rehearse right now — "Want to run a mock Q&A? I'll play one of your attendees and you practise your responses."
Revise the presentation — "Want me to adjust tone, expand a section, or rework any slide?"
Deepen an objection card — "Any objection you're especially worried about? I can expand that card with more detail."
Prepare a send email — "Would you like a short email to send the deck with?"
Dig deeper on a research gap — "I flagged [X] as a research gap — want me to search further?"


Reference Files

references/ebr-examples.md — Sample EBR sections and tone reference
references/metrics-translation-guide.md — How to translate raw metrics into business outcomes

Read these when you need additional depth, examples, or benchmark data.
Also read /mnt/skills/public/pptx/SKILL.md before building the presentation and
/mnt/skills/public/docx/SKILL.md before building the research report.
