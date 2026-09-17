## Work experience — the earlier roles

The two roles that predate Sýn, kept together because neither is long enough to carry its own document and because they read as one stretch: the start of the career, May 2013 to July 2015.

**Fons Juris ehf.**

Reykjavík

Jun 2014 – Jul 2015

**Software developer**

**SmartMedia**

Vestmannaeyjar

May 2013 – Sep 2013

**Software developer**

### Merged continuous text

Both entries woven into one passage, in chronological order rather than the CV's reverse order. Nothing from the CV has been dropped.

My first development work was at SmartMedia in Vestmannaeyjar, from May to September 2013, building templates for SmartWebber, the company's own website product, which was used mostly for e-commerce sites for small and medium businesses. It was a summer position, taken partway through the computer science degree I finished at Reykjavik University in 2014. From June 2014 to July 2015 I was at Fons Juris in Reykjavík, the first role I took after that degree. Fons Juris published Icelandic legal reference material — court judgments, statute collections and similar writings — sold on user contracts to lawyers, law firms and companies that kept lawyers on staff. I worked on improving the search engine over that material, and built its admin interface from scratch: until then, managing users and content had meant writing SQL queries by hand. The stack was the same as at SmartMedia: SQL, PHP, HTML, CSS and JavaScript.

Taken together these fourteen months and five months are where the full-stack half of the career starts, and May 2013 is the date the "13 years of experience" claim counts from. The Fons Juris work is also the earliest instance of a thread that runs through the whole CV: a body of documents that has to be searchable and fast, which turns up again as Elasticsearch on the Vísir sites at Sýn and as storage APIs at NetApp.

### Why these stay on the CV, and why they stay short

Worth stating deliberately, because the CV is fighting for space and these are the obvious deletion candidates. They are twelve and thirteen years old, they take about six lines of a one-page CV, and nothing in them would win an interview on its own.

They earn their place for one reason: they anchor the timeline. Without them the CV begins in 2015 and the "13 years" in the About Me contradicts the work history on the same page. A reader who notices that stops trusting the rest. Six lines is a cheap price for internal consistency.

But they should not grow, and adding the details below proved it. The first pass at writing them into the CV pushed the page to two, and the way it broke is worth knowing: education entries can't split across pages, so the BA Philosophy entry jumped to page two as a whole block. That means the real budget was two lines, not the ~30px the measurement suggested. A block that can't break makes the last 60px of the page unusable.

Two things were traded to buy those lines back:

- **The Fons Juris stack list is gone.** It read "Classic WAMP stack: SQL, PHP, HTML, CSS and JavaScript" and now reads just "Classic WAMP stack." No real loss: SmartMedia names WAMP on the line below, and SQL, PHP, HTML, CSS and JavaScript are all in the skills sidebar already. The admin-interface detail is worth far more than a second listing of five languages.
- **The commercial context is gone.** An earlier draft said the database was "sold on user contracts to lawyers and law firms". True, and good interview material, but it's context rather than achievement and it cost a line and a half.

If the page ever needs another line back, trimming SmartMedia to a single clause is a safer cut than shortening anything at NetApp or Sýn.

### Claims that were corrected

Both overstatements came from earlier CV drafts and are now fixed in the CV as well as above.

- **"Custom" search engine.** The engine already existed; the work was improving it, not building it. "Custom" implied authorship that isn't there, so it's gone. What *was* built from scratch is the admin interface, and that claim has moved onto the stronger of the two things.
- **"Large" database.** Unquantified size adjectives are the weakest kind of claim: they invite the follow-up question ("how large?") without surviving it. Naming the material instead — court judgments and statute collections — is concrete, verifiable, and tells a reader more than "large" ever did.

### The admin interface is the load-bearing detail

Of everything in these two roles, this is the one thing worth keeping sharp: **before it existed, user and content management was done with hand-written SQL queries.**

That is a genuine before-and-after, and it's rare to have one this clean from early-career work. It says the tool wasn't a nice-to-have rewrite of an existing screen — it was the difference between a product that could be administered and one that couldn't. It also explains who the users were, since the people writing those queries by hand were presumably staff who shouldn't have had to. Built from scratch, for a commercial product with paying subscribers, in the first year out of a degree. Lead with that if either of these roles comes up.

### The search engine: what to say and what to leave out

The CV stays exactly as it is — "improved the search engine" and nothing more. This section doesn't grow. The role ended badly and there's no version of a longer CV entry that pays for the questions it invites.

But the diagnosis is worth keeping, because it's better than the work. The content was scattered and tightly coupled to the web layer, so searching it was unreliable: you often didn't get the result you were looking for. There was no ranking to speak of and the indexing was poor. The proposed fix from above was to buy a Google Search Appliance and point it at the site, which cost a small fortune and changed nothing. What was actually needed was structural — decouple the content from the presentation, stop fetching it ad hoc from the front end, and index it properly.

That diagnosis is a genuinely senior read on the problem, and it can be told without a word about the company:

> The content was scattered and tightly coupled to the presentation layer, so search results were unreliable. There was no real ranking and the indexing was weak. I argued the fix was structural — decouple the content from the page and index it properly — rather than putting another search product on top of it. That wasn't the direction taken, and I moved on.

Nothing in that is unkind, and it answers a technical question with a technical answer. **Keep out of interviews:** the appliance, the price, the boss, and how the role ended. None of it makes you look better and all of it invites follow-ups you don't want.

### The through-line worth noticing

There is a straight line from that argument to the best work on the CV, and it's flattering because it's true.

At Fons Juris the diagnosis was coupling: content welded to the presentation layer, and the proposed remedy was to buy hardware and bolt it on. At NetApp, ten years later, you moved every queue consumer and all recurring background sync out of the control plane into a dedicated service, so customer requests and internal jobs stopped competing for the same pods. Same shape of problem, same instinct: identify the structural coupling and separate the concerns, rather than adding capacity around it.

That's a good answer to "tell me about a time you were overruled" and an even better one to "how has your judgement changed over your career" — you were right early and couldn't get it done, and you were right again later with the standing to see it through. Worth having, given it costs the CV nothing.

### Still open

- **The SmartWebber name.** You flagged this as uncertain recall. It's now on the CV, and while nobody is going to fact-check a 2013 template product, confirm the spelling if you can. The company has since become a consultancy adapting WooCommerce and similar platforms, so the original product is unlikely to be findable online.
- **Active user count.** You don't remember it, and it isn't worth chasing. "Lawyers and law firms on user contracts" already establishes it was a real commercial product; a user number would only matter if it were large enough to impress, and you'd remember it if it were.
- **Don't let WAMP resurrect MySQL.** WAMP implies MySQL, and MySQL was deliberately dropped from both the CV and LinkedIn because this 2013–2015 work was its only evidence. The CV says "SQL", which is the right call. Leave it.

