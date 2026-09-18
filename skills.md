## Skills

Single source of truth for the CV (`index.html` sidebar) and the LinkedIn skills section. Last reviewed 18 Sep 2026 against a 62-item LinkedIn list and the CV's 18 grouped lines.

LinkedIn caps the section at **100** skills, so at 62 there is no pressure to delete anything. Skills attached to Experience entries don't count toward the cap.

### Fix these first

- **"Reddis" is misspelled.** It should be **Redis**. LinkedIn search does exact keyword matching, so a misspelled skill is invisible to every recruiter searching the correct term, and it looks careless to anyone who reads it. Delete and re-add from autocomplete.
- **"Open API" should ideally be "OpenAPI"** (one word), which is the specification's actual name and the term that appears in job descriptions. If autocomplete only offers the spaced version, keep it; it's better than nothing.
- **"Gitlab" vs "GitLab"** — if autocomplete offered the lowercase-L version, leave it. Worth a glance to see whether the properly-capitalized entry exists, since that's the one job descriptions use.

### Recommended LinkedIn display order

Ordering is manual: Profile → Skills → pencil → More → **Reorder**, then drag. LinkedIn does *not* sort by endorsement count, so whatever order it's in now is arbitrary and worth fixing deliberately.

**Pin these three.** They display on the profile without a click and carry the most search weight. This trio reads as backend and platform rather than full-stack web, which is where the career is going:

1. Go (Programming Language)
2. Kubernetes
3. Distributed Systems

**Cloud-native platform** — highest recruiter search volume after the top three:

4. Docker
5. Helm (Software)
6. Azure Kubernetes Service (AKS)
7. Linux
8. Amazon Web Services (AWS)
9. Google Cloud Platform (GCP)

**APIs and the storage domain** — the differentiators almost nobody else has:

10. REST APIs
11. Data ONTAP
12. Open API

**Observability:**

13. OpenTelemetry
14. Prometheus.io
15. Grafana

**Delivery:**

16. Continuous Integration and Continuous Delivery (CI/CD)
17. GitHub Actions
18. Git
19. GitHub
20. Jenkins
21. Gitlab

**Security** — the Security Champion story:

22. FedRAMP
23. Application Security
24. Vulnerability Management
25. Azure Key Vault
26. Microsoft Entra ID

**Messaging, data and caching:**

27. RabbitMQ
28. Azure Service Bus
29. Redis
30. Elasticsearch
31. PostgreSQL
32. SQL
33. Varnish

**Leadership** — supports the level 4 case:

34. Technical Leadership
35. Mentoring
36. Code Review
37. Software Design

**Engineering practice:**

38. Unit Testing
39. Agile Application Development
40. Scrum
41. Object-Oriented Programming (OOP)

**Other languages:**

42. Python
43. Java
44. C#
45. .NET Framework

**Frontend:**

46. TypeScript
47. JavaScript
48. React.js
49. React Native
50. Next.js
51. Vue.js
52. Tailwind CSS
53. CSS
54. HTML5

**Earlier-career and platform-specific:**

55. PHP
56. Ruby on Rails
57. Salesforce.com Development
58. Apex Programming
59. Back-End Web Development
60. Full-Stack Development

**Personal:**

61. Public Speaking
62. Philosophy

### How LinkedIn will actually render this

Two constraints worth knowing before spending time dragging:

- LinkedIn **auto-categorizes** skills into *Industry Knowledge*, *Tools & Technologies* and *Interpersonal Skills*, and **you cannot move a skill between categories**. So the list above won't render as one flat sequence; it will be split across those buckets, and the drag-reorder works within them. Treat the numbering as a priority ranking rather than a literal final layout.
- Only the **top three** show before "Show all skills", which is why the pinned trio matters far more than the ordering of positions 30 through 60. Don't over-invest in the tail.

**Endorsements:** they're a modest search-ranking signal with diminishing returns past roughly 10–15 per skill. Worth asking a few colleagues to endorse Go, Kubernetes and Distributed Systems specifically; not worth chasing across all 62.

### The CV skills list

The sidebar, verbatim, as of 17 Sep 2026. Eighteen grouped lines. Lines are packed to just under the wrap threshold (roughly 34 characters) because a line that wraps costs about 14px of vertical space, and the sidebar has only ~30px of slack before the CV spills to a second page.

```
Go, C# .NET, Java, Python
JavaScript, TypeScript
React, React Native, Next, Vue…
HTML, CSS, Tailwind
Rails, PHP, Salesforce (Apex)
Kubernetes, Helm, Docker, Linux
Azure AKS, Key Vault, Workload ID
AWS, Google Cloud Platform
Distributed systems, ONTAP
REST APIs, OpenAPI
SQL, PostgreSQL, Elasticsearch
Redis, Varnish cache
RabbitMQ, Azure Service Bus
OpenTelemetry, Prometheus, Grafana
CI/CD: GitHub Actions, Jenkins, GitLab
Container scanning, FedRAMP compliance
Technical leadership, mentoring
Agile, Scrum, code review, testing
```

### The one bullet not to delete

The NetApp bullet reading "Instrumented the service with metrics, distributed tracing and alerting, and tuned CPU and memory from actual usage" is the sole evidence in the entire work history for **OpenTelemetry, Prometheus and Grafana**. It was cut once for space on 18 Sep 2026 and restored the same day, which is worth recording, because the loss is invisible: the three skills still read perfectly well in the sidebar, so nothing looks wrong until someone asks what's behind them.

The About Me refers to "the observability and security work that keeps them running", but that's a claim about myself rather than something I did. The security half of that sentence has its own bullet; without this one the observability half has nothing.

It's also what makes the NetApp entry show four kinds of work instead of three — building a service, delivering API components, *operating what I built*, and owning security. The operating half is the part that distinguishes a platform engineer from a feature developer.

If the page needs a line back, take it from the Sýn entry's closing sentence about vodafone.is and the annual report websites, not from here.

### Acceptable divergences

The two documents no longer contradict each other. What's left is deliberate, driven by the CV's space limit:

- **On LinkedIn only, by design:** Software Design, Object-Oriented Programming, Back-End Web Development, Full-Stack Development, Public Speaking, Philosophy. Umbrella and interpersonal terms earn their place on LinkedIn, where they cost nothing and get searched, but not on a one-page CV.
- **Git.** Dropped from the CV when the CI/CD and source-control lines were merged. It's table stakes for any developer in 2026 and the line already names GitHub Actions and GitLab, so the signal survives. Still listed on LinkedIn.
- **Application Security and Vulnerability Management** are the LinkedIn phrasing; the CV says "container scanning, FedRAMP compliance". Same work, different register: LinkedIn wants searchable skill nouns, the CV wants the specific thing that was done.
- **Container Security** never made it onto LinkedIn. Largely covered by Application Security plus Vulnerability Management, so optional.

### Deliberately not claimed

- **Artificial Intelligence (AI).** Removed from LinkedIn on 17 Sep 2026. The real skill is using AI-assisted development tooling; "Artificial Intelligence" reads as building AI or ML systems, which surfaces the profile for roles that aren't a fit and invites an interview question with no good answer. The LinkedIn About section states it accurately instead: "I picked up AI-assisted development tooling early and use it daily, with the same skepticism I'd apply to any other tool." If a tool-specific skill ever becomes worth claiming, name the tool rather than the field.
- **Internal NetApp level (3, working toward 4).** Doesn't transfer between companies, and reads as junior to anyone who doesn't know NetApp's scale. Demonstrate the behaviours instead.
- **MySQL.** Dropped from both documents: SQL and PostgreSQL carry more weight, and the only evidence was the WAMP-stack work from 2013–2015.
- **WordPress.** Dropped from both. Real history from the SmartMedia template work, but it dates the profile and says nothing useful about a platform engineer.
- **Ruby, as a language on its own.** Dropped from both; Ruby on Rails covers it and is the term anyone actually searches.
- **LESS and SASS.** Removed during decluttering, absent from LinkedIn. Consistent; leave them off.
- **".NET" and ".NET Core".** Not available in LinkedIn's autocomplete for developers, so ".NET Framework" stands in even though it technically denotes the legacy Windows-only runtime.
- **Anything without evidence in the work history.** Terraform, gRPC and similar plausible-adjacent tooling stay off both lists until there's real work behind them.
