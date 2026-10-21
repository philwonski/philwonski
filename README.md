# Phil Wonski

**Independent Software Developer**  
Business applications, integrations & independent products.

I like building useful software, especially the kind that small teams end up using every day.

My background is in data centers and hosting. In 2019, I began helping my wife with her web design business and its technical operations: coordinating developers, managing hosting infrastructure, securing deployments, and keeping projects version-controlled.

2020 was a strong year for folks like us in the business, and with the extra time at home I decided to become a javascript developer.

What started as a fascination with building lightweight applications evolved into several years of paid software development, particularly building custom interfaces on top of established business platforms. Basically, "custom skins" for tools like Salesforce and QuickBooks, since folks generally hate using such platforms and often need additional features.

Along the way, I developed a preference for getting a lot of mileage out of relatively little code and infrastructure. Rather than assembling large development teams or building everything from scratch, I found ways to turn existing platforms into highly customized, purpose-built software for small teams.

The approach made for sticky and repeat business, and the solo mechanics have become even more interesting in the AI era since now we have AI employees.

The recurring idea: **Sometimes you don't need to replace your system of record. You just need a much better way to interact with it.**

## Selected Client Work

Most of my commercial work lives in private repositories and behind authenticated applications. Below are two systems I continue to support.

### The OCR Killer
*Insurance Claims Management | Salesforce, Node.js, AI*

A Texas insurance claims processor handles thousands of incoming PDFs, images, and emails. Processing that information manually was time-consuming, and coordinating field and office personnel required a better shared workflow.

I developed a custom claims management application built around Salesforce, extending it with a purpose-built interface and automated document processing.

Today:
- A team of 12 collaborates through the custom application.
- The system manages tens of thousands of claim records.
- Incoming claim documents and emails are automatically parsed using AI.
- Field and office personnel work within a shared claims workflow.

The application provides a specialized operational interface while Salesforce remains the underlying system of record.

### The QuickBooks Rejoinder
*Quote-to-Cash & Project Management | QuickBooks Online, Node.js*

A NYC sound engineering studio needed the capabilities of QuickBooks without requiring its entire team to live inside QuickBooks.

I built an alternative interface around the QuickBooks API, abstracting much of its native UI and permissions complexity while adding project tracking and team collaboration features.

Today, all eight team members can work together around individual job records, from quoting through payment, without navigating the traditional QuickBooks interface.

---

## Open Source: HelloJson

One of my favorite discoveries of the pre-AI days was that TiddlyWiki — usually associated with personal note-taking — is also an incredibly capable JavaScript framework for rapidly building custom user interfaces.

I became interested in using its Node.js edition to build lightweight business applications, integrating with external systems through REST APIs. This was important because rapid UI development was the real friction when trying to ship solutions.

This all led me to develop **HelloJson**, an opinionated approach to building TiddlyWiki plugins. The driving principle was to simplify async JavaScript so a developer could abstract more and more functionality behind a lean, human-readable control plane.

Simplicity is the word:

1. Keep the plugin's entry point thin.
2. Express business logic in a human-readable class.
3. Delegate the tedious work to reusable helper modules.

This structure made it easier for me to develop integrations and custom interfaces while keeping the code understandable and maintainable.

Looking back, the approach was also rather well suited to AI-assisted development: keep the business logic plain, make the underlying functionality modular, and let other tools (or agents) do more of the heavy lifting.

It's a modest bit of open-source work, but I'm particularly proud of it because the approach helped me turn a lightweight open-source platform into real commercial software. It also led to some commercial collaboration with TiddlyWiki's founder, Jeremy Ruston, as we worked to make TiddlyWiki's syncer module more robust for multi-user apps on the server.

**Explore the projects:**

- [HelloJson — framework and documentation](https://github.com/philwonski/twplugins-hello-json)
- [HelloJson Advanced — working integration examples](https://github.com/philwonski/twplugins-hello-json-advanced)

The advanced examples include external API requests, WordPress integration, JSON data export, record creation, and experiments integrating OpenAI with TiddlyWiki.

---

## Technical Writing

Up until the first time I tried ChatGPT, I was also interested in sharing my methods and writing about lightweight software architecture, serverless development and making sophisticated infrastructure accessible to small development teams.

A few favorites:

**[Add Login to a Node.js App with Cloudflare Tunnel](https://mydigitalmark.com/add-login-to-nodejs-with-cloudflare-argo-tunnels/)**

A walkthrough of using Cloudflare Tunnel and Zero Trust to securely expose a Node.js application running on an inexpensive VPS.

Motivation: Auth was a big problem for us back in the day (and still is, really). This article was a bit of a hit and stood atop Google results for a good while. It's still helpful despite Cloudflare changing their UI every few months.

**[Serverless Form Submissions the Low-Code Way](https://mydigitalmark.com/serverless-form-submissions/)**

Building customized, stateful web forms using TiddlyWiki and serverless integrations.

Motivation: Forms have always been among the most tedious of developer tasks (second only to calendars).

**[Build Static HTML from JSON with AWS Lambda and TiddlyWiki](https://mydigitalmark.com/easily-build-static-html-sites-from-json-with-aws-lambda-and-tiddlywiki/)**

An experiment in generating static websites using TiddlyWiki as a lightweight rendering engine.

Motivation: You are not a real dev from the past if you did not try to make your own Static Site Generator. :-)

*These are older posts. Some implementation details may have changed.*

---

## What I'm Working On Now

My attention has increasingly turned toward developing and testing my own independent software products. I am particularly interested in information-heavy markets, practical AI applications, API integrations and tools that make complicated work easier for people.

AI has changed my development workflow considerably, but not really my philosophy. I'm still interested in how much useful software one person can build and maintain without accumulating unnecessary complexity.

My GitHub activity reflects the ongoing support of applications whose foundations I built before AI. My [GitLab](https://gitlab.com/philiwon/), meanwhile, increasingly reflects my use of coding agents to accelerate development. Different eras, same underlying objective: ship useful things and keep them running.

### Selected Links

**[SubstationScout](https://substationscout.com)** — Energy infrastructure research and tools for the site selection community.

**[LullabyMail](https://lullabymail.com)** — Using AI to help parents build better connections with their children through daily storytelling.

**Options Trading Software (Coming Soon)** — Early in my career I learned that I'm not great at investing, so I took up trading as an alternative way to get exposure to equities. It's been a really fun ride, and my skills increase every year.

Over the years I've developed little personal tools to help me make decisions, and I'd like to share some of that here. One of the early tools is a simple alternative to standard deviations more suited to options players called [Does It Move](https://doesitmove.com). Eventually I'd like to share more of my tools and findings, including work on timing entries into 0DTE index options.

---

Overall, my philosophy hasn't changed much: use the tools that make sense, keep infrastructure manageable, and focus on building something genuinely useful.

It's still a big thrill for me when I see somebody using software I built to make their job a little easier.
