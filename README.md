# SocialPost skill pack

Free Claude skills for B2B founders who run their own LinkedIn.

A skill is a small instruction file that teaches Claude to do one job well, the same way every time. Load one and Claude stops improvising: it asks the right questions, follows a tested process, and hands you a finished document. This pack covers the LinkedIn jobs a founder without a marketing team actually needs.

Five skills are ready. Five more are coming.

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

## How they fit together

The skills pass files to each other through your working folder:

1. founder-voice-profile writes `voice.md` and `about.md`.
2. social-strategy-90-day reads them and writes `strategy.md`.
3. content-pillar-planner reads all three and writes `topic-bank.md`.
4. thirty-day-content-calendar reads the bank (or the strategy) and writes `calendar.csv`.

linkedin-presence-audit sits alongside that chain: it reads `voice.md` and `about.md` when they exist, so its scores and rewrites match how you actually sound.

Any skill also works on its own. It will just ask you for whatever the files would have told it, so running them in order means answering fewer questions each time.

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

That installs all five skills at once. When new skills land in this repo, pull them with:

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

## Coming next

Five more skills are planned, including a post writer that drafts in your voice from your topic bank or calendar, and an analytics review that closes the loop at day 30. Add the marketplace now and `/plugin marketplace update socialpost-skills` will bring each one to you as it passes testing.

Found a problem, or want a skill that doesn't exist yet? Open an issue.
