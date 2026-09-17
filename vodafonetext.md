## Work experience

**Sýn** (trading as Vodafone Iceland during my time there)

Reykjavík

Aug 2015 – Jun 2024

**Software developer**

### Merged continuous text

Every detail from both CV versions, woven into one passage. Nothing from either version has been dropped.

Almost nine years at Sýn, the Icelandic telecoms and media group, which is why the same company ran both a mobile network and a newsroom. I started on telecoms and IT: a self-service checkout system for customers, backend services for the administrators who supported them, and several Salesforce integrations. From 2017 I was on a team focused on media and web, building for Vísir and the sites and services around it: radio websites and apps, and Vaktin, the live news and sports feed, which I rebuilt from the ground up and then extended with multiple features over the years that followed. We optimized speed and caching for Vísir using Elasticsearch, Redis and Varnish. We also built Klipparinn, an internal editor for video and audio clips that was nominated for Stafræn lausn ársins (Digital Solution of the Year) at the 2019 SVEF awards, and out of it we created VísirTV, an in-house solution codenamed Ghost that linked a new user interface in Klipparinn to a CasparCG TV broadcast server. Alongside that we built a new webstore for business customers, and worked on various websites under the Sýn umbrella and apps for Stöð 2, Bylgjan, FM957 and X977. Most of the backend was C# .NET and AWS, with React, TypeScript and various CSS frameworks on the front end. The mobile apps were React Native, and some of the work was Ruby on Rails. This was the full-stack half of my career, before I moved into backend and platform work.

### Vaktin, and how to write about it

The honest answer to "I don't know how to put that into few words" is that you can't, and shouldn't try. A CV cannot do justice to years of work on a product, and attempting it produces a paragraph that reads as padding. What a CV can do is make a reader stop and take it seriously, and that needs only two facts, both of which you already have:

- **You rebuilt it from the ground up.** That establishes scope and ownership in five words. Being handed a rewrite of a live production feed on a national news site is not a small thing, and the phrase carries that on its own.
- **You kept extending it for years afterwards.** This is the part that gets underrated. Plenty of people ship a rewrite; being the one who still owns the thing years later is the evidence that the rebuild actually worked and that they trusted you with it.

So the CV now says: "Rebuilt Vaktin, its live news and sports feed, from the ground up and kept extending it with new features." Naming it matters more than describing it. A named product invites the interviewer to ask about it, and at that point you have as long as you want — which is where the pride belongs, rather than in a CV line that has to compete with everything else on the page.

For that conversation you need three or four specifics that aren't written down anywhere yet. Worth capturing while you still remember them:

- **What made the old one bad enough to justify a rebuild.** The reason for a rewrite is usually the most interesting engineering story inside it.
- **What the architecture became.** A live feed is a real-time problem: how did updates actually reach readers? Polling, long-polling, websockets, cache invalidation through the Varnish layer? This is the detail that connects the work directly to the distributed-systems and platform work you do now, which is the connection a hiring manager cares about.
- **The traffic shape.** A sports feed on a major news site doesn't have flat traffic; it spikes hard around matches and breaking news. Serving a live-updating page under spiky load is a genuinely hard caching problem, and describing it is the best available answer to the scale gap flagged below.
- **Two or three of the features by name.** "Multiple features" is invisible to a reader. Two concrete ones are worth more than the phrase.

### Corrections made to the notes above

- **"Almost nine years" is correct, and it caught a wrong date on the CV.** This was briefly "corrected" to *almost eight* on the basis of the CV's dates, which turned out to be the thing that was wrong: the CV had Sýn ending Jul 2023 and NetApp starting Aug 2023, both a year early. NetApp started **Jul 2024**. Aug 2015 to mid-2024 is almost nine years, exactly as originally written. Lesson worth keeping: the prose was the reliable source here and the CV was not.
- **Ruby on Rails was restored.** It dropped out of your rewrite of the stack sentence. The skills list claims Rails and Sýn is its only evidence anywhere on the CV, so removing it here would leave that skill with nothing behind it.
- **"Ghost" is deliberately not on the CV.** An internal codename tells an outside reader nothing, and spending characters on it costs space that VísirTV and CasparCG use better. It's kept here because it's the term colleagues would recognize.
- Minor fixes: Elasticsearch (not ElasticSearch), Klipparinn (not Klippari), "frameworks", "a new user interface", and the "(c)" placeholder resolved to Vaktin.

### Where the versions disagree

Two details were phrased differently across CV drafts. The merged text above uses the fuller claim in the first case and the narrower one in the second; worth knowing which is accurate before an interview.

- **Stöð 2.** The original said "websites and apps for Stöð 2". A later edit narrowed this to "contributed to the Stöð 2 app" (singular, and a smaller claim). If the narrower version is the accurate one, change the merged text to match, since the difference is noticeable.
- **The media team.** The original described "a team focused on media and web" building for "Vísir and the sites and services around it". A condensed draft shortened this to "a media and web team" and "the services around it". These are only wording changes, no facts lost.
- **The checkout system.** Described as "for customers" in the original, which a condensed draft dropped. Restored above, since it distinguishes the customer-facing system from the admin backend services mentioned next.



### Things no CV version covers

Candidates for strengthening this entry, none of which I can source from the existing CVs:

- **Scale — half solved.** The CV now connects Elasticsearch, Redis and Varnish to Vísir performance work, which closes the worst part of this gap: those three skills previously sat in the sidebar with nothing behind them. What's still missing is a number. Requests per day, concurrent readers during a match, cache hit rate — any one of them would turn "tuned site speed and caching" into a claim with a size attached, and it remains the strongest single addition available to this entry.
- **Klipparinn is resolved, and the claim had to come down.** Every CV draft said "award-winning". It was **nominated**, not a winner: shortlisted for Stafræn lausn ársins (Digital Solution of the Year) at the 2019 SVEF awards, SVEF being the Icelandic web industry association. "Award-winning" would not survive anyone checking, so the CV now names the product, the category and the year instead. A named national-industry nomination is better evidence than an unnamed win anyway, because it can actually be verified.
- **Salesforce depth.** LinkedIn lists Apex Programming, which implies you wrote custom Salesforce logic rather than only wiring up integrations. The CV says only "several Salesforce integrations".
- **Nine years, one title.** The CV shows "Software developer" for the whole 2015–2024 span with no progression. If there was a promotion, a scope change, or a tech lead stint, that gap is conspicuous next to a role this long — and a year longer than previously thought makes it more conspicuous, not less.
- **Why you left.** Seven years on media and web then a jump to storage backends is a real pivot. Worth having a sentence ready, though it belongs in a cover letter rather than the CV.

