# SocialPost skill pack

Free Claude skills for B2B founders who run their own LinkedIn.

A skill is a small instruction file that teaches Claude to do one job well, the same way every time. Load one and Claude stops improvising: it asks the right questions, follows a tested process, and hands you a finished document. This pack covers the LinkedIn jobs a founder without a marketing team actually needs.

All ten skills are ready.

## Who it's for

You run a small B2B company and your buyers are on LinkedIn. Nobody on the team owns marketing, so it's you, in the 30 to 60 minutes a week you can spare. Every skill here is sized to that budget: it asks the minimum, hands back a finished document, and never prescribes a plan that costs more time than you said you had.

## The skills

### founder-voice-profile

Figures out how you actually write. Paste 3 to 5 samples of your real writing (old posts, customer emails, a bio), or answer six interview questions if you have nothing you'd want to paste. You get two files back: `voice.md`, with 10 to 15 concrete writing rules and examples pulled from your own words, and `about.md`, the facts about your company, your buyers, and the opinions you'll defend in public. Every other skill in the pack reads these files. That's what keeps AI-drafted posts from sounding like AI.

### social-strategy-90-day

Builds a one-quarter LinkedIn strategy: positioning, audience, content pillars, posting cadence, what to measure, and a day-by-day plan for the first two weeks. Tell it you have 45 minutes a week and the whole plan costs 45 minutes a week, tracking time included. It also names the vanity metrics you should ignore, and says why.

### content-pillar-planner

Turns your positioning into 3 to 5 content pillars and a bank of 30 topic ideas. Each topic is tagged with a funnel stage and written as an angle specific enough to draft from, so "what do I post this week" becomes a lookup instead of a staring contest. If you've already run the strategy skill, it inherits your pillars rather than inventing a competing set.

### linkedin-presence-audit

Grades your LinkedIn presence from what you paste in: headline, About section, and your recent posts. You get five scores with the evidence quoted, what's already working, and the top 5 fixes in order of impact. It doesn't stop at advice; the new headline and About come back rewritten in your voice, ready to paste. Pasted fewer than 5 posts? It audits what exists and tells you which scores to trust less.

### thirty-day-content-calendar

Turns your pillars and topics into a dated month: every slot has a pillar, a specific topic, a format, a one-line hook to expand, and an empty status column, delivered as a table plus a `calendar.csv` you can import anywhere. It's sized to your real weekly budget, and if your strategy already committed part of that budget to commenting, the calendar respects it instead of quietly scheduling more. It plans and drafts; publishing stays yours.

### linkedin-post-writer

Writes one LinkedIn post at a time in your voice. Give it a topic, a customer story, a rough take, or a row straight from your calendar, and you get three opening lines built on different mechanisms (tension, an exact detail, a contrarian stance), then the full post built on the strongest one, formatted for LinkedIn. It follows `voice.md` as law when you have one, and it never pads your story with invented details: anything only you know stays as a [bracketed slot] for you to fill. One revision pass is offered, in your choice of tighter, bolder, or softer. It drafts; it will not post for you, and it will refuse to fake engagement.

### content-repurposer

Turns one piece of long-form material into a week of LinkedIn posts. Give it a blog post, a newsletter issue, a podcast or call transcript, talk notes, or a case study, and it extracts 4 to 6 angles the piece already contains, then drafts four posts in genuinely different formats: a story, a how-to in plain prose, a stance, and a short one. Every post stands on its own; none of them is a teaser for the original, and nothing gets stated that the source doesn't actually say. Name one secondary platform (X, Threads, or Facebook) and the two strongest posts come back re-cut for it, natively, not copy-pasted. It won't blast identical text everywhere or set up auto-posting, and it explains why that would work against you.

### carousel-and-visual-brief

Turns a post, topic, or framework into two documents ready for production: a slide-by-slide carousel script and a creative brief for the key visual. The script runs 5 to 8 slides with hard word limits (an 8-word hook, one idea per slide) and a line of guidance on each slide about what to emphasize and what to cut. The brief closes every decision a designer or image model would otherwise guess: background, focal element, the exact overlay text, placement zones, a readability rule for phone screens, and a what-to-avoid list. Alt text comes included. Give it your colors, logo placement, and mood in 3 words and the brief is built on them; skip them and they become slots you fill in one reply. It will not fake engagement screenshots or invented social proof, and it says why.

### engagement-comment-coach

Builds the half of LinkedIn that happens on other people's posts. One-time setup: you supply 15 to 25 names (buyers, peers, ecosystem voices) and it turns them into an engagement list and a 20-minute daily routine card: scan, 3 to 5 real comments, 0 to 2 connection notes, reply to everything on your own posts. Day to day, paste any post and it drafts two comment options that actually add something (your real experience, a respectful counterpoint, or a question worth answering), never "Great post!", plus connection notes under 280 characters that reference something real and pitch nothing. It never looks people up or builds lists from data, and it will decline auto-commenting, pods, and bulk DMs by name, with the reasons, then hand you the manual routine instead.

### social-analytics-review

Turns your LinkedIn analytics into a monthly review you can read in five minutes. Feed it LinkedIn's own export (it tells you where that lives), pasted numbers, or screenshots, and you get a one-paragraph read, a metrics table where every row carries a confidence label, what worked tied to specific posts, at most three testable changes for next month, and the vanity metrics it deliberately ignores. It is honest about small samples: two posts of a format is variance, not a trend, and it says so instead of inventing a story. If your calendar file exists it tells you which pillars earned their slots, and if you set goals it reports against them without spin. It will not pull competitor analytics, because there is no legitimate way to; it offers a manual competitive read from what you can see publicly instead.

## How they fit together

The skills pass files to each other through your working folder, and the chain ends in something you can actually publish:

1. founder-voice-profile writes `voice.md` and `about.md`.
2. social-strategy-90-day reads them and writes `strategy.md`.
3. content-pillar-planner reads all three and writes `topic-bank.md`.
4. thirty-day-content-calendar reads the bank (or the strategy) and writes `calendar.csv`.
5. linkedin-post-writer reads `voice.md` and `about.md`, takes any row of `calendar.csv` as a complete brief, and writes the post itself.

Run in order, that's one path from "how do I sound" to a finished post, and each step means fewer questions at the next one because the files already hold the answers.

Two skills sit alongside the chain rather than inside it. linkedin-presence-audit reads `voice.md` and `about.md` when they exist, so its scores and rewrites match how you actually sound. content-repurposer reads the same two files and brings its own source material: it starts from something long you already wrote instead of a calendar slot, and it can cover a whole week on its own when you have a blog post or transcript to feed it.

One skill picks up where the others leave off: carousel-and-visual-brief takes any finished post, whether the post writer drafted it, the repurposer extracted it, or you wrote it yourself, and turns it into a carousel script plus the visual brief that gets it produced.

And one skill works the other side of the feed: engagement-comment-coach reads the same voice and about files and covers the 20 minutes a day you spend on other people's posts, which is where comments become conversations with buyers.

social-analytics-review closes the loop at the end of the month: it reads `calendar.csv` to tell you which pillars earned their slots, reports against the goals your strategy set, and its three changes feed the next month's plan.

Any skill also works on its own. It will just ask you for whatever the files would have told it. The post writer, for example, is happy to work from nothing more than a story you paste in.

## Install

Three ways, easiest first.

### Claude Code: one command, updates included

This repo is also a Claude Code plugin marketplace, so there's nothing to download by hand. Inside Claude Code, run:

```
/plugin marketplace add SocialPostAI/socialpost-claude-skills
```

then:

```
/plugin install socialpost-skill-pack@socialpost-skills
```

That installs all ten skills at once. When new skills land in this repo, pull them with:

```
/plugin marketplace update socialpost-skills
```

### Claude on the web or desktop

Each skill is one downloadable file; no cloning needed. Grab the skill you want:

| Skill | Download |
|-------|----------|
| founder-voice-profile | [founder-voice-profile.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/founder-voice-profile.skill) |
| social-strategy-90-day | [social-strategy-90-day.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/social-strategy-90-day.skill) |
| content-pillar-planner | [content-pillar-planner.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/content-pillar-planner.skill) |
| linkedin-presence-audit | [linkedin-presence-audit.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/linkedin-presence-audit.skill) |
| thirty-day-content-calendar | [thirty-day-content-calendar.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/thirty-day-content-calendar.skill) |
| linkedin-post-writer | [linkedin-post-writer.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/linkedin-post-writer.skill) |
| content-repurposer | [content-repurposer.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/content-repurposer.skill) |
| carousel-and-visual-brief | [carousel-and-visual-brief.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/carousel-and-visual-brief.skill) |
| engagement-comment-coach | [engagement-comment-coach.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/engagement-comment-coach.skill) |
| social-analytics-review | [social-analytics-review.skill](https://github.com/SocialPostAI/socialpost-claude-skills/raw/main/dist/social-analytics-review.skill) |

Then in Claude, open Settings, find Skills, and upload the file. A `.skill` file is a standard ZIP archive; if the upload dialog only accepts `.zip`, rename the file and it will work as is. Skills on claude.ai need a paid plan with code execution enabled.

### Claude Code, manual (no plugins)

Copy any skill into your skills folder with one line, swapping the skill name as needed:

```bash
mkdir -p ~/.claude/skills/founder-voice-profile && curl -fsSL https://raw.githubusercontent.com/SocialPostAI/socialpost-claude-skills/main/skills/founder-voice-profile/SKILL.md -o ~/.claude/skills/founder-voice-profile/SKILL.md
```

Use a project's `.claude/skills/` instead of `~/.claude/skills/` to install for one project only. Skills are plain instructions in a text file; nothing executes on your machine.

## What these skills will never do

No scraping, no browser extensions, no engagement pods, no bulk DMs, no automation of any kind. Everything works from what you paste in yourself or from LinkedIn's own data export, and nothing here ever posts to your account. Two reasons. Automated collection breaks LinkedIn's terms and gets accounts restricted, and yours is the account this whole effort is supposed to grow. And advice built on data you provided is advice you can check.

They also won't invent numbers. When a skill uses a working figure (a good post takes 20 to 30 minutes to draft and edit), it tells you it's a rule of thumb. When it can't promise something, like a post trending, it says so instead of promising.

## Where SocialPost fits

We make [SocialPost.ai](https://socialpostai.com), which takes what your AI wrote and handles the visuals, formatting per platform, and scheduling. This pack is our way of being useful before asking for anything. The skills are complete on their own and never require our product. When one of them finishes something you'd naturally want designed and scheduled, it may mention our free Solo tier once, with a tracked link so we know whether the pack is worth maintaining. Tell it you use another scheduler and the mention disappears for good.

## How a skill earns its place here

Every skill is tested before it ships. It runs against scripted scenarios (a detailed realistic request, a vague one, and one built to tempt it into breaking its own rules), gets graded against written pass/fail checks by reviewers that didn't write it, and its trigger description is tested against 20 prompts so it fires when it should and stays quiet when a different skill owns the job. A skill only lands in this repo after all of that passes.

## The pack is complete

All ten skills are shipped. Fixes and improvements still land through the marketplace; `/plugin marketplace update socialpost-skills` picks them up whenever you like.

Found a problem, or want a skill that doesn't exist yet? Open an issue.
