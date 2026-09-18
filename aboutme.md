## LinkedIn About section

Backend and platform engineer building distributed systems in Go on Kubernetes. Most recently the control plane behind Azure NetApp Files and Google Cloud NetApp Volumes: enterprise file storage sold as a first-party service inside Azure and GCP.

At NetApp I led the Cloud Volumes Service Worker project end to end, moving background synchronization and every queue consumer out of the control plane into a dedicated service to improve stability and scalability, and guided two junior developers through the work. I instrumented it with OpenTelemetry tracing, Prometheus metrics, Grafana dashboards and alerting, then tuned its CPU and memory from real usage. I also delivered ONTAP REST components for their ZAPI-to-REST modernization, the largest project the group had taken on.

I was also the Security Champion for the team, a role I took on voluntarily: tracking security work across projects, driving vulnerability remediation, and coordinating FedRAMP-related backports in a FedRAMP-authorized product. I closed supply-chain findings across five services through dependency and image scanning, base-image migration and chart digest fixes.

My first decade was full-stack web work. Nine of those years were at Sýn, Iceland's telecoms and media group, building Vísir, one of the country's largest news sites, and the products around it. I rebuilt Vaktin, its live news and sports feed, from the ground up and kept extending it with new features for years afterwards, and worked on site speed and caching with Elasticsearch, Redis and Varnish. I also helped build Klipparinn, an internal video and audio editor nominated for Digital Solution of the Year at the 2019 SVEF awards. Mostly C# .NET and AWS on the backend, with React and TypeScript on the front end, React Native for the radio and TV apps, and Ruby on Rails for the self-service checkout and admin services.

The thread through all of it is that I'd rather understand a problem properly before writing code. I came to software from a philosophy degree, which turns out to be reasonable training for picking apart an ambiguous problem before committing to an answer. In practice that means systems that are well-instrumented, well-tested and easy to operate and code reviews aimed at maintainability and edge cases rather than style. I picked up AI-assisted development tooling early and use it daily, with the same skepticism I'd apply to any other tool.

Always happy to talk about Go, Kubernetes, distributed systems, storage control planes, or how to make security work visible on a busy team.

## Notes for future edits

### Check the experience dates before pasting this

The CV had both NetApp and Sýn a year early, and that error was corrected on 18 Sep 2026. **The LinkedIn experience entries probably carry the same wrong dates.** Correct values:

- **NetApp:** Jul 2024 – Present
- **Sýn:** Aug 2015 – Jun 2024

This matters more on LinkedIn than on the CV, because LinkedIn computes and displays a duration under every entry. The paragraph below says "nine of those years were at Sýn", and if the entry still reads Aug 2015 – Jul 2023, the profile will contradict itself in two places a reader can see at once. Fix the entries first, then paste.

### Deliberately no years count

The experience total is **13 years** (counting from SmartMedia, May 2013). That number lives on the CV, which gets regenerated often, and is kept out of this section on purpose: this field gets updated rarely, so a hardcoded number silently goes stale and ends up understating experience. "My first decade was full-stack web work" is the substitute and does not age.

The one duration that *is* stated is the nine years at Sýn, which was previously written as eight. Aug 2015 to Jun 2024 is eight years and ten months, so nine is the honest round number, and it's the one LinkedIn will display anyway.

### The fold

Only about **265 characters show on desktop** and **200 on mobile** before "see more". The opening paragraph is 246 characters, so it survives desktop intact but mobile cuts it partway through the second sentence.

That's why the paragraph is built as two sentences rather than one. The first is 78 characters and carries the whole identity — backend and platform, distributed systems, Go, Kubernetes — so mobile readers get a complete, self-sufficient hook before the cut. The product names are in the second sentence, where losing them on mobile costs credibility but not comprehension. Keep that shape in any future edit: never let the first sentence run past ~190 characters.

### Written in the past tense, on purpose

NetApp is closing its Iceland office. The whole section now reads as somewhere I worked rather than somewhere I work: "At NetApp I led...", "I also delivered...", "I was also the Security Champion...". The opening says "Most recently the control plane behind..." rather than "I build the Go control plane behind...", which stays true regardless of employment status.

An earlier draft of this file argued for keeping the body in the present tense, on the grounds that rewriting a profile into the past is a visible signal you're leaving. **That reasoning is void.** An office closure is public and the whole Iceland organization is affected at once, so there is no signal left to protect — and the usual downside, looking like you jumped before you were pushed, doesn't apply when the building is closing behind everyone.

The product names stay, and they should. Azure NetApp Files and Google Cloud NetApp Volumes are strong search terms, and having worked on them doesn't stop being true.

### How to frame the departure

**An office closure is the cleanest exit there is.** It's structural, it's verifiable, it has nothing to do with performance, and it affected everyone, so it needs no defending. Two rules follow:

- **Don't pre-empt it in the profile.** No "seeking new opportunities following restructuring" line in the About section. It puts the layoff in the first thing a recruiter reads and frames the profile around a setback rather than the work. The experience dates will say what happened.
- **Say it plainly when asked.** "NetApp closed its Iceland office" is a complete answer. No hedging, no extra explanation, no apology. Anything longer reads as defensiveness about something that doesn't warrant any.

### Two things this changes

- **"Open to work" is now worth turning on.** An earlier note here argued against it because it was unsafe to display while employed. That no longer holds. The recruiter-only version is the cautious option; the public green banner measurably increases inbound, and there is no employer left to hide it from.
- **Speed matters more than polish now.** Every engineer in NetApp Iceland reaches the market in the same few weeks, with overlapping skills and the same story. The profile doesn't need to be perfect; it needs to be live before the wave. Stefan's recommendation is already written and dated 9 Sep 2026, which is fortunate timing — get it posted to the profile, because a manager's written recommendation is the one thing in this situation that separates you from colleagues applying for the same roles.

### Why each paragraph is there

- **Opening.** Names Azure NetApp Files and Google Cloud NetApp Volumes rather than describing them generically. Both are public first-party services, so naming them is more credible and both are terms a recruiter might search.
- **Leadership.** Previously absent from the profile entirely, despite being the substance of this year's work and the thing that separates level 3 from level 4. Positioned to land above the desktop fold.
- **Observability, added this revision.** The keyword list at the bottom of this file used to claim OpenTelemetry, Prometheus and Grafana, but none of those words actually appeared in the text, so LinkedIn was not indexing them and a recruiter searching any of the three would not have found this profile. They are now named explicitly, attached to the Service Worker rather than floating as a generic claim. The same gap existed for "distributed systems", now carried by the closing line.
- **Security Champion.** FedRAMP work in a FedRAMP-authorized product is a real differentiator for enterprise and government-adjacent roles, and naming the role reads as owned scope rather than assigned tickets. The supply-chain sentence was added to give it a concrete result instead of only responsibilities.
- **Background.** Now leads with Vaktin, rebuilt from the ground up and extended for years, which is the strongest single piece of work from that decade and was missing entirely. Klipparinn stays as the verifiable proof point. Elasticsearch, Redis, Varnish and React Native were added because all four are skills on the profile that previously had nothing in the text behind them.
- **How I work.** The philosophy degree is attached to the trait Stefan documented ("invests the time to understand a problem properly before he starts writing code") so it explains a strength instead of reading as a non-sequitur.

### Verify before posting

- **The three observability tools.** The text now claims OpenTelemetry, Prometheus and Grafana by name. They're all on the skills list, but the CV bullet only says "metrics, distributed tracing and alerting" generically. If any of the three isn't what the team actually runs, swap the name out — a specific wrong tool is worse than a vague right one.

### Kept off this section

- **Internal level (3, working toward 4).** Doesn't transfer between companies and reads as junior to anyone who doesn't know NetApp's scale. Demonstrate the behaviours instead.
- **Any "open to work" wording in the text itself.** The closing line invites conversation and names four topics of expertise, which does the job without dating the section. Use LinkedIn's own "Open to work" setting for the availability signal instead — it's a structured field recruiters filter on, and unlike a sentence in this text it can be switched off in one click when the search ends.
- **VísirTV and CasparCG.** On the CV, left off here. Broadcast-server integration is a memorable detail in conversation but too niche to spend profile space on, and it competes with Vaktin for the same slot.
- **Fons Juris and SmartMedia.** Covered by "my first decade was full-stack web work"; the experience entries carry the detail.

### Keywords this section carries

Go, Kubernetes, Azure, GCP, Azure NetApp Files, Google Cloud NetApp Volumes, ONTAP, ZAPI, REST, control plane, queue consumers, distributed systems, FedRAMP, supply-chain security, OpenTelemetry, Prometheus, Grafana, C# .NET, AWS, React, TypeScript, React Native, Ruby on Rails, Elasticsearch, Redis, Varnish.

LinkedIn indexes this field for search, so several of these were added specifically to close gaps found when comparing the CV's skills against the profile's. Every term on this list now appears verbatim in the text above — that was not true of the previous version, so check it stays true after any edit.
