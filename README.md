# upwork-skills

<p align="center"><strong>English</strong> · <a href="README.id.md">Bahasa Indonesia</a></p>

**AI agent skills for Upwork freelancers, extracted from a real Top Rated Plus playbook.**

*Community project. Not affiliated with or endorsed by Upwork.*

Five skills that turn Claude, Cursor, or any SKILL.md-compatible agent into a working freelance operator: one that qualifies jobs before you spend Connects, drafts proposals that beat the AI flood, answers invitations fast, audits your profile, and handles the hard client conversations.

Every skill is built from two sources: Upwork's own published guidance (cited inside each skill) and the real, documented playbook of a Top Rated Plus freelancer (top 3%). Where official advice and field results disagree, the skills say so and tell you which one wins. No roleplay personas, no invented stats.

## The skills

| Skill | What it does | Reach for it when |
|---|---|---|
| [upwork-job-qualifier](upwork-job-qualifier/SKILL.md) | Verdict on a job post: apply, skip, or caution. Client-history math, red flags, Connects economics. | "Is this job worth my Connects?" |
| [upwork-proposal-writer](upwork-proposal-writer/SKILL.md) | Drafts proposals with the five-move method; reviews existing drafts. | "Write a proposal for this job" |
| [upwork-invitation-responder](upwork-invitation-responder/SKILL.md) | Accept, decline, or decline-and-refer an Invitation to Interview. | "A client invited me, help me reply" |
| [upwork-profile-optimizer](upwork-profile-optimizer/SKILL.md) | Scored profile audit, prioritized fixes, including the AI-search (AEO) layer. | "Why am I not getting invites?" |
| [upwork-client-messenger](upwork-client-messenger/SKILL.md) | Mid-contract messages: delays, scope creep, rate increases, contract endings, review asks. | "The client keeps adding scope" |

Together they cover the whole loop: choose well, get chosen, be findable, and run the relationship.

## Install

With the [skills CLI](https://skills.sh):

```bash
npx skills add abullaisi/upwork-skills --all
```

Or manually: copy any skill folder into your agent's skills directory (`.claude/skills/` for Claude Code) and it loads on the next session.

## The profile shortcut

Every skill reads an optional `upwork-profile.md` from your working directory or `~/.claude/`: your identity line, niche, portfolio links, and rate. Store it once and the skills stop asking. Example:

```markdown
# My freelance profile
- Role: UI/UX designer, 5+ years, SaaS dashboards
- Rate: your hourly rate
- Portfolio: 3-5 links you actually send to clients
```

## Why these instead of just asking an AI

Upwork's built-in AI drafts proposals for every freelancer on the platform, free. That's the problem: generic AI output is now the baseline clients scroll past. These skills encode the parts a platform tool can't or won't: judgment about which jobs to skip (platforms profit when you apply more, not less), a proposal method with the field corrections that won real contracts, and client-conversation moves tested in real threads. The sources are cited in every file, so you can check the receipts.

## Contributing

Contributions are welcome, and small ones count:

- **Corrections**: guidance that's gone stale, a mechanic that changed.
- **Translations**: any skill, any language. Bahasa Indonesia versions are a first-class goal.
- **New skills**: more Upwork craft (pricing, portfolio prep, niche workflows) fits here. Other platforms deserve their own pack. Open an issue first so we agree on scope.

Keep the house rules: plain human voice, no invented statistics, sources cited, no client names or real rates in examples, and no scraping or automation that violates any platform's terms.

## License and disclaimers

MIT. Use it, fork it, ship it.

This project is not affiliated with or endorsed by Upwork. "Upwork" appears descriptively, because that's the platform the guidance is about.

Built by [Imam Abullaisi](https://github.com/abullaisi) and the Wargi Freelance community (Indonesian freelancer community, 950+ members). The lessons repo this pack grew from is coming next.
