---
title: "Intentional, Not Reflexive: A Manager's Thoughts on AI"
date: 2025-11-11
draft: false
ShowToc: true
description: "\"Oooh, look! A blog post about AI! How trendy!\""
ogimage: "https://scottkosman.com/ai-for-managers.png"
tags:
  - leadership
  - ai
  - chatgpt
  - gemini
  - priorities
  - automation
  - intentionality

---

## A Manager’s Identity Crisis

When Tobi Lütke’s *"[Reflexive AI usage is now baseline expectation at Shopify](https://x.com/tobi/status/1909251946235437514?lang=en)"* memo started circulating, I had a... _visceral_ reaction. Every CEO on LinkedIn was pausing their “here’s what getting engaged taught me about b2b sales” posts to praise Tobi’s boldness and future-proof mindset. 

Meanwhile, I was sitting there like *"I don’t use AI tools for anything. Am I an out-of-touch relic? Do I have any future employability?"*

Honestly, it kinda rattled me. For a while, I genuinely wondered if I was being left behind, and when I started asking other managers across the industry it turned out I wasn't alone. 

---

## Go away before I replace you with a shell script

When I was an IC, even in the dark days of IE6 in the early 2000s I was on a mission to automate _everything_. Any task I had to repeat more than once became a candidate for automation. I wrote AppleScripts to batch-rename files, Photoshop actions to export images for various use cases, even system-level macros on my computer for running everyday routines so I wouldn't have to think about them. As technology continued to evolve, the advent of JavaScript task runners like Grunt and Gulp gave developers a new level of power and flexibility over how our projects were built.

This attitude only continued to grow as I made the transition from IC to Management. When I started at Resn as their Technical Director, on day one I learned that the team's "release process" for web apps was whichever developer hopefully had the latest build would drag a folder from their desktop into an FTP client. _That_ shit had to go. I immediately implemented a CI/CD pipeline using Jenkins to create builds directly from GitHub.

These tools were like _candy_ for me. Any chance I had to automate and abstract away repetitive, time-consuming nonsense I did. Not only because I'm extremely lazy and I hate repetitive tasks, but this also allows me to **focus on what really matters.**

<center><img src="/nothing-got-done.gif" alt="Ron Swanson: 'I'd work all night if it meant nothing got done.'"></center>

Now AI tools have taken that instinct and kicked it into high gear as I've tried to implement that type of thinking in both personal projects as well as at the day job. On the home front I've recently joined a local ukulele club and used ChatGPT to build a shell script that automates building song sheet PDFs from a catalog every week, which scratches a _delightfully_ nerdy itch. At work I've set up custom GPTs to pull daily Jira sprint data for analysis, read PR metadata to highlight risks/bottlenecks, and to pipe that data into templates for the different cross-functional updates I'm responsible for.

Over the past year, as I’ve experimented with AI in more of my day-to-day work, my mindset around what “using AI” really means has started to shift. The instinct to systematize the boring shit I don't want to do never left, it's just shifted from build pipelines to people systems.

---

## Going From Doing to Thinking

When I examined my discomfort with that Shopify memo, I realized my mistake. I’d been considering AI through an IC's lens: making it all about speed, output, and execution. And tbh, while modern AI tools are amazing at juicing an engineer's velocity and output, the challenge for managers is that "velocity" and "output" aren't the measuring stick by which we're judged. Managers win on **clarity, judgment, and communication.** 

For individual contributors AI is about **doing faster**. That may be crushing code, writing tests, scaffolding out an app. High _throughput_.

For managers, AI is about **thinking better**. We need to cut through the noise, frame decisions, clarify direction, and communicate about all of these while doing them. High _leverage_. 

This was a galaxy-brain moment for me. I had spent so much time hearing about how ICs were using AI and I was trying to shoehorn that methodology into my management work. I was trying to extend my hands instead of my mind and unfortunately not everything can go in the square hole. Once I stopped trying to use AI like my developers do I started finding the real value nuggets that fit the work of Leadership.

<center><img src="/squarehole.gif" alt="that's right, it goes in the square hole!"></center>

---

## The Hidden Benefit of Cognitive Offloading

In the process of this journey I found something I wasn't expecting... a profound sense of _relief_. Management work happens in your head with dozens of open loops spinning at once, and suddenly using AI gave me a safe way to unload that noise without judgment or consequence. Some days my brain becomes a bag of cats and I can quickly spin myself in circles with too many scattered thoughts competing for mindshare at the same time. Being able to hammer those down into a prompt window in no particular order and ask "what am I really trying to say here?" has saved me literal **hours** of effort in a single day.

I’ve come to think of it as *cognitive offloading.* By pushing my internal monologue into a medium that reflects it back to me more clearly, I preserve energy for the parts of leadership that actually matter: listening, coaching, connecting.

---

## How Managers Can Actually Use AI

"Ok, that's great, but what the fuck are you actually talking about?" Good question, pretend reader. It's all fine and good to give theoretical advice on this but let's talk practicalities. 

Here’s how I think about AI in my day-to-day now:

### Clarity

AI helps me process complexity. I alluded to this one earlier, but when I’m unpacking a messy idea, I’ll paste my rough thoughts and ramblings into ChatGPT and ask something like “summarize what you think I'm going after here and call out any inconsistencies you see in my thinking.”

ChattyG is brilliant at taking input from any number of sources (Slack threads, Google docs, Notion pages, emails, slide decks, whatever you can throw at it) and synthesizing and summarizing them into an easily-digestible single source of truth. It’s like having a structured sounding board that never gets tired of putting up with your bullshit.

### Communication

Performance feedback, planning docs, and executive updates all demand precision. I use AI to refine tone and tighten structure: “help me make this feedback concise and constructive without softening the message.”

A critical point here is that I'm not _outsourcing_ the thinking process. I'm not asking AI to do the hard thinking for me, I'm not ready yet to embrace the Matrix that closely. Instead of asking AI to create a Slack post or 30-60-90 day plan or whatever from scratch, I'll feed it rough notes, a first draft, or a skeleton of an idea _first_ and then ask it to _refine_ that. I've committed to always starting with my own ideas and then using AI to smooth out the rough edges. 

### Coaching

Managers deal with a lot of sticky and complex performance management situations and AI can be a great coaching assistant. I’ll ask coaching questions such as "I have a senior dev that's stagnating, suggest a few ideas to inspire them” or "my mid-level dev is chasing a promotion, suggest growth areas based on [paste of job description or company career ladder or whatever]." 

### Operations

This is yet another spot where my automation jam kicks back in. I've discovered how awesome AI is at collecting, summarizing, and visualizing operational data so I can spot patterns faster. Piping Jira data into ChatGPT quickly flags an overloaded engineer, a PR that's gone stale, or a potential timeline slippage. These are all things that my dumb human eyes can easily miss in the noise of all the other things vying for their attention.

<center><img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGF1N3d1ODZuMXNkeGM1c3I4YWExdWR3NmU1YWZjcHptbm8xZXkyNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/11LK0CKzYtkaic/giphy.gif" alt="a well-oiled machine"></center>

---

## Power Move: Create a "Master Prompt"

In true "automate all the things" fashion I've recently started using a **Master Prompt** with AI and it's been a huge shot in the arm. A Master Prompt makes sure that whatever AI you're using knows your priorities, team, needs, and communication style before you even ask it to work. Think of it as like scaffolding a web app: you're giving the system the structure and context to work in before you even get started asking or building. Creating it takes a little time, but the payoff is huge: you’re tailoring ChatGPT, Gemini, or whatever LLM of choice you happen to be using today to give you the most valuable output while cutting down on the number of times you need to refine your prompts.

Start by telling the AI your name, role, and company. Ask it to create a Master Prompt and let it fire back every question it needs to understand you and your context. Then spend the next 45 minutes or so answering everything it throws at you. Cover your job, your team, your reporting structure, your values, current projects, communication style, and anything else that matters for how you operate.

When you’re done, the AI will generate your Master Prompt. Give it a read, make sure it’s accurate, and tighten up anything that feels off. Once you’re happy with it, export the final version as a PDF. You can now drop that file into every project, chat, or custom GPT you start. It gives the AI context right from the start so you don’t have to repeat yourself every time.

Every quarter or so, ask the AI to update your prompt. Teams change, priorities shift, titles evolve, and an outdated prompt ain’t gonna help you much.

---

## Intentional, Not Reflexive

When that Shopify memo hit, honestly, I hated it. I told people I hated it. I probably told _too many_ people I hated it. A few months later and I've come around to acting just like it says I should.

That said, I do still take one very large issue with it: Tobi called AI usage "reflexive." "Reflexive" implies something that's automatic and unthinking, a habit formed without thought. While I get where he's coming from, I don't think it's healthy for a leader to have very many habits that fall into that "reflexive" category because anything you do without thinking automatically becomes something you can't **evolve**. You can't grow something you're not paying attention to.

Right now I'm calling my AI usage **intentional**, not reflexive. I know the kinds of problems I want it to help me solve. I experiment using it for types of problems I'm not sure how it'll handle. I also have a pretty good read on the type of tasks where it falls over and when to launch it into the sun. 

The same instinct that once drove me to automate build scripts now drives me to automate clarity. AI doesn’t make me a faster manager, but it sure as hell can make me a _clearer_ one. It helps me communicate more thoughtfully, coach more effectively, and reclaim time for the human parts of leadership. So yeah, "reflexive" AI use might be Tobi's baseline expectation now but the real unlock isn’t using it constantly, it’s knowing and learning when it’s the right tool for the kind of thinking you need to do.

And that, more than any memo, is what future-proofs us.

<center><img src="/memo.gif"><center>