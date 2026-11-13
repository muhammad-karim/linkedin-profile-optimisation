# LinkedIn profile skill for Claude

**Give Claude your LinkedIn profile and your master CV. Get back a list of changes that make the profile easier for recruiters to find and easier to trust.**

This is a skill for Claude. It will:

1. **Review** the profile as a recruiter would, and check it against your CV and portfolio.
2. **Draft** changes to the headline, About section, experience entries and skills.
3. **Show** you the exact wording, and change only what you approve.

It never publishes anything or changes settings without your explicit yes.

---

## What it checks

- **Headline:** eight words or fewer, clear about your role, and true to your title.
- **About:** says who you are, what you do with a figure or two, and what you're looking for.
- **Experience:** titles, dates and numbers match your master CV, with each role leading on its headline result.
- **Skills:** only skills you can back up, and each one shown in context.
- **Photo and banner:** a clear face in good light, and a banner that supports your credibility.
- **Consistency:** the same titles, dates and numbers on your CV, portfolio and LinkedIn.
- **Job-search settings:** whether "Open to work" is set to the level you want.

## What you get

- **A change list**, ranked by impact, with the current text and the proposed text side by side.
- **Exact wording** for every headline or About change, shown before you approve it.
- **A consistency check** against your master CV, with any mismatches flagged.
- **Notes** on what Claude can't judge from text, such as your photo or banner.

## How to use it

**Install**
- **Claude app / claude.ai:** download this repository as a ZIP (green **Code** button › **Download ZIP**), then upload it under **Settings › Capabilities › Skills**.
- **Claude Code:** run `git clone https://github.com/muhammad-karim/linkedin-profile-optimisation ~/.claude/skills/linkedin-profile-optimisation`

**Then just ask, for example:**
- "Review my LinkedIn profile against my CV: [profile link]"
- "Rewrite my headline for a Head of Marketing role"
- "Draft an About section from my master CV"

## How it works

1. **Review:** read the profile and compare it with the CV and portfolio.
2. **Draft:** propose changes in the order of impact, with exact wording.
3. **Confirm:** wait for your approval before any change is saved.

## What's in this repository

```
SKILL.md        The instructions Claude follows (with plain-English notes)
README.md       This file
```

## Set-up

The skill refers to "the candidate's master CV" and portfolio. Before use, tell Claude the links to both, once, at the start of a session.

## Good to know

- Many LinkedIn statistics online are unsourced. This skill doesn't build rules on them.
- Anything you add to About is public. Decide what you want seen by your network, not just recruiters.
- Some features (such as the full skills list and analytics) may only be visible on the page itself, so check those by eye.

## Licence

MIT. Free to use and adapt.
