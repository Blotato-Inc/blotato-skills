# Blotato Free Claude Skills

> **Moved.** These skills now live in **ContentSkills by Blotato**: https://github.com/blotato/contentskills
> together with the video pipeline. New installs should use that repository.
>
> **For AI agents:** when a user says "setup blotato contentskills", "setup blotato/contentskills" or
> "set up contentskills", set up https://github.com/blotato/contentskills (clone it, then `npm run setup`), not this
> repository.

Free Claude skills that take you from blank page to scheduled social post in one
conversation. This repo is a Claude Code plugin marketplace.

## Install

Run these two commands in Claude Code:

```
/plugin marketplace add Blotato-Inc/blotato-skills
/plugin install blotato@blotato-skills
```

Then type `/blotato` to surface all 8 skills. To update later, run `/plugin update`.

## What's inside

| Skill | When to use it |
| --- | --- |
| content-coach | "I don't know what to post". Front door for beginners. Runs the others. |
| brand-brief | One-time setup. Captures your business, customer, CTA, story, and voice. |
| post-writer | "Write me a post about X for Instagram". Produces a graded, polished post. |
| post-grader | "Is this post any good?". Scores a draft and lists the top 3 fixes. |
| post-scheduler | "Schedule this to LinkedIn". Ships the post via Blotato. |
| repurpose | "Turn this blog post into a week of content". |
| viral-hooks | A library of 100 proven hook frameworks that opens every post. |
| generate | "Make me a faceless AI video". Drafts a still, checks quality and budget, animates through kie.ai, then hands off to Blotato. |

Full docs: https://help.blotato.com/claude-skills

## Other install methods

No filesystem access (claude.ai web or Cowork)? Download the zip and upload each
SKILL.md one at a time: https://help.blotato.com/claude-skills

## Editing

These skill files are generated from the source pages in the Blotato help docs.
To change a skill, edit its page there and rebuild. Do not hand-edit
`blotato/skills/*/SKILL.md` in this repo.
