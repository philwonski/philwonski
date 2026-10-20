# Phil Wonski

**Independent Software Developer**  
Business applications, integrations & independent products.

I like building useful software, especially the kind that small teams end up using every day.

My background is in data centers and hosting. In 2019, I began helping my wife with her web design business and its technical operations: coordinating developers, managing hosting infrastructure, securing deployments, and keeping projects version-controlled.

In the 2020 quarantine, I took the opportunity to become a proper js dev.

What started as a fascination with building lightweight applications evolved into several years of paid software development, particularly building custom interfaces on top of established business platforms... think of it as "custom skins" for tools like Salesforce and Quickbooks, since folks generally hate using such platforms and often need additional features. 

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

An NYC sound engineering studio needed the capabilities of QuickBooks without requiring its entire team to live inside QuickBooks.

I built an alternative interface around the QuickBooks API, abstracting much of its native UI and permissions complexity while adding project tracking and team collaboration features.

Today, all eight team members can work together around individual job records, from quoting through payment, without navigating the traditional QuickBooks interface.


---

## Open Source: HelloJson

One of my favorite discoveries of the pre-AI days was that TiddlyWiki — usually associated with personal note-taking — is also an incredibly capable JavaScript framework for rapidly building custom user interfaces.

I became interested in using its Node.js edition to build lightweight business applications, integrating with external systems through REST APIs. This was important (and lucrative) because rapid UI development was the real friction when trying to ship solutions. 

This all led me to develop **HelloJson**, an opinionated approach to building TiddlyWiki plugins. The driving principle is to simplify async javascript so a dev can abstract more and more functionality with a lean, human-readable control plane.  

Simplicity is the word:

1. Keep the plugin's entry point thin.
2. Express business logic in a human-readable class.
3. Delegate the tedious work to reusable helper modules.

This structure made it easier for me develop integrations and custom interfaces while keeping the code understandable and maintainable.

It's a modest bit of open-source work, but I'm particularly proud of it because the approach helped me turn a lightweight open-source platform into real commercial software. It also led to some commerical collaboration with TiddlyWiki's founder, Jeremy Ruston, as we worked to make TiddlyWiki's syncer module more robust for multi-user apps on the server. 

**Explore the projects:**

- [HelloJson — framework and documentation](https://github.com/philwonski/twplugins-hello-json)
- [HelloJson Advanced — working integration examples](https://github.com/philwonski/twplugins-hello-json-advanced)

The advanced examples include external API requests, WordPress integration, JSON data export, record creation, and experiments integrating OpenAI with TiddlyWiki.

---

## Technical Writing

Up until the first time I tried ChatGPT, I also enjoyed writing about lightweight software architecture, serverless development and making sophisticated infrastructure accessible to small development teams.

A few favorites:

**[Add Login to a Node.js App with Cloudflare Tunnel](https://mydigitalmark.com/add-login-to-nodejs-with-cloudflare-argo-tunnels/)**

A walkthrough of using Cloudflare Tunnel and Zero Trust to securely expose a Node.js application running on an inexpensive VPS. Motivation: Auth was a big problem for us back in the day (and still is, really... this article was a bit of a hit and stood atop Google results for a good while... it is still helpful despite Cloudflare changing their UI every few months).

**[Serverless Form Submissions the Low-Code Way](https://mydigitalmark.com/serverless-form-submissions/)**

Building customized, stateful web forms using TiddlyWiki and serverless integrations. Motivation: forms have always been among the most tedious of developer tasks (second only to Calendars). 

**[Build Static HTML from JSON with AWS Lambda and TiddlyWiki](https://mydigitalmark.com/easily-build-static-html-sites-from-json-with-aws-lambda-and-tiddlywiki/)**

An experiment in generating static websites using TiddlyWiki as a lightweight rendering engine. Motivation: you are not a real dev from the past if you did not try to make your own Static Site Generator. :-) 

*These are older posts. Some implementation details may have changed.*

---

## What I'm Working On Now

My attention has increasingly turned toward developing and testing my own independent software products. I am particularly interested in information-heavy markets, practical AI applications, API integrations and tools that make complicated work easier for people. 

My activity graph here on GitHub is a nod to long-term durability of my solutions, as all the commits on my graph here are in support of applications I first developed before AI; my [Gitlab graph](https://gitlab.com/philiwon/), on the other hand, is a testament to my increasing use of agents to increase ship velocity (it still excludes automated pushes).

Selected Links:

**[SubstationScout](https://substationscout.com)** — Energy infrastructure research and tools for the site selection community.

**[LullabyMail](https://lullabymail.com)** — Using AI help parents build better connections with their children via daily storytelling.

**(COMING SOON) Options Trading Software** — Early in my career I learned that I'm not great at investing, so I took up trading as an alternative way to get exposure to equities. It's been a really fun ride, and my skills increase every year. Over the years I have also developed some little personal tools to help me make decisions, and I'd like to share some of that here. One of the early tools is a simple alternative to standard deviations called [Does It Move](https://doesitmove.com), but later I would like to share more of my tools and findings such as timing entries into 0dte index options. 

Overall my philosophy hasn't changed much: use the tools that make sense, keep infrastructure manageable, and focus on building something genuinely useful.

There is still no bigger thrill for me than seeing somebody use software I built to do their job a little better.
