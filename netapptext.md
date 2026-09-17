## Work experience

**NetApp**

Reykjavík

Jul 2024 – Present

**Software Engineer, Cloud Volumes**

Enterprise cloud file storage, sold as a first-party service inside Azure and GCP (Azure NetApp Files). I work on the Go backend services behind the customer API, running on Kubernetes.

- Designed and shipped a new worker service that moved recurring background work — snapshot, volume, replication, backup and key-rotation sync, plus all the platform's queue consumers — off the customer-facing API, so customer requests and internal jobs no longer compete for the same pods.
- Owned it end to end: functional spec, test design, on-call runbook, and rollout across three environments. Enablement is feature-flagged with a rollback path that needs no redeploy, so it could be switched on one environment at a time and backed out safely.
- Migrated our integration with the storage controllers from a legacy proprietary API to REST, covering volume lifecycle, networking, SMB and Kerberos settings, and replication. The old path stayed as a fallback so nothing broke mid-migration, and I handled the high-availability cases where a request has to be routed to the right node in a pair.
- Instrumented the service with metrics, distributed tracing and alerting, tuned CPU and memory from actual usage, and removed a recurring class of production incidents caused by configuration drift between two related services.
- Closed compliance and supply-chain security findings across five services in a FedRAMP-authorized product: dependency and container-image scanning, base-image migration, and chart metadata and digest fixes.

## From Stefan Arngrímsson's recommendation (9 Sep 2026)

Stefan managed me directly for two years; Engineering Manager on the Azure NetApp Files control plane. Everything below is either quoted from that recommendation or marked as an inference.

### Project names and correct terminology

The CV describes both projects generically. The recommendation supplies the names the team actually uses, which are more concrete and far more searchable:

- **Cloud Volumes Service Worker** is the official name of the worker-service project.
- The "legacy proprietary API" is **ZAPI**, the programme is the **ZAPI-to-REST modernization**, and my deliverables were **ONTAP REST components**. ONTAP is the storage controller platform.
- Stefan calls ZAPI-to-REST "the largest project our group has taken on."
- He frames the worker project as moving background synchronization jobs "out of the **control plane** and into a dedicated service to improve stability and scalability." *Control plane* is the industry-standard term and lands harder than the CV's "customer-facing API".

### Leadership and mentoring (absent from the CV entirely)

- Guided **two junior developers** through the Service Worker project.
- Stefan calls this "early project leadership experience", and says it gave them "a genuinely useful onboarding path into a complex codebase".
- His description of my ownership: "he contributed to the functional specification and technical design, implemented several of its core components, and kept the implementation aligned with the design and operational requirements as the project progressed."
- Worth noting the nuance: he says *contributed to* the spec and design, and implemented *several* core components. The CV's "functional spec, test design, on-call runbook" claims slightly more sole authorship than the reference does. Aligning the two means they corroborate rather than contradict each other if both are read.

### Security Champion (the CV understates this)

- **Security Champion** was a named role for the team, and I took it on **voluntarily**.
- Scope: drove and tracked security work across projects, handled vulnerability remediation, and coordinated backports including FedRAMP items.
- Stefan's assessment: it "made a measurable difference to how visible and well-followed-through our security commitments are."
- The CV currently renders this as a list of tasks ("closed compliance and supply-chain security findings across five services"). Naming the role converts it from assigned work into owned scope.

### Engineering practice (reference-backed, good interview material)

- Invests the time to understand a problem properly before writing code, which shows up in output quality.
- Thoughtful and consistent code reviewer; feedback is "timely, specific, and aimed at maintainability and edge cases rather than surface issues."
- Picks up incoming bug tickets and production issues promptly, "even when they sit outside his assigned scope."
- Humble, clear in communication, generous with context and knowledge.
- Summary line worth quoting: "one of its most dependable and technically capable members."

### Self-directed learning

- Worked through Kubernetes and ONTAP coursework on my own initiative in the first year.
- Sharpened Git practices for a large collaborative repository.
- Adopted **AI-assisted development tools early and effectively**. This appears nowhere on the CV or LinkedIn and is unusually marketable right now.

### Candidate CV additions

The CV's main column has roughly six lines of slack, so these are written to swap in rather than pile on:

- Mentoring: "Guided two junior developers through the project, giving them a structured route into a large and unfamiliar codebase."
- Security role: "Security Champion for the team, taken on voluntarily: drove and tracked security work across projects, ran vulnerability remediation, and coordinated FedRAMP-related backports."
- Naming the tech: replace "legacy proprietary API" with "ONTAP ZAPI" and "storage controllers" with "ONTAP", so the CV matches the reference and hits real search terms.

### Dates: resolved, and there was never a discrepancy

The start date is **Jul 2024**. The CV previously said Aug 2023, which was wrong by a year and has been fixed.

That error had produced a problem that doesn't exist. Stefan's recommendation says I "joined my team as a software engineer at the start of FY25" and that he has managed me "for the past two years", which contradicted an Aug 2023 start and led to an invented explanation: that I joined the company in 2023 and only moved onto his team in mid-2024. **Discard that. It isn't true and it was never needed.**

With the correct date everything lines up on its own. NetApp's fiscal year ends in late April, so FY25 began around May 2024, and a July 2024 start genuinely is the start of FY25. Stefan's recommendation is dated September 2026, and July 2024 to September 2026 is two years and two months, which is exactly "the past two years". One date, one team, no gap to explain.

Worth noting for its own sake: the recommendation was the accurate document and the CV was not. If the two disagree again, check the CV first.

### Not mine to claim

"Founding engineer on Google Cloud NetApp Volumes" and "leading the Azure NetApp Files control plane" are from **Stefan's** own profile headline, not descriptions of my work.

## Title and level

The correct title is **Software Engineer** (earlier CV drafts said "Software Development Engineer", which was wrong and is now fixed). Internally I am a **level 3 working toward level 4**; level 4s tend to lead projects, which is what I have been doing this year.

Keep the level off the CV and off LinkedIn. Internal ladders don't transfer between companies, a "level 3" label reads as junior to anyone who doesn't know NetApp's scale, and it invites questions that lead with what I'm not yet rather than what I've done. Demonstrate the behaviours instead, which the CV now does: leading the Service Worker project end to end, guiding two junior developers, and owning Security Champion across projects.

For a promotion case specifically, Stefan's recommendation already reads as a level-4 argument in writing. It documents end-to-end project ownership, contribution to functional spec and technical design, mentoring two juniors through a complex codebase, and voluntary cross-project security ownership with a measurable result. Two things would make that case tighter:

- **Get the level rubric.** I couldn't find the level descriptions. Ask Stefan or HR for them so the evidence can be mapped point by point rather than argued in general terms.
- **Name the leadership explicitly.** "Guided two junior developers" and "kept the implementation aligned with the design as the project progressed" are the load-bearing phrases. They describe technical leadership without a title, which is exactly what a level-4 case needs.

