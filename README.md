# Research Path

A [Cubbie](https://cubbie.ai) Skill that answers a question every student has: *how do I get into
research, and how do I keep it going once I'm in?*

Built for the [Cubbie Hackathon](https://hackathon.cubbie.ai), Track 1.

## What it does

**Find and reach out**
- Searches your school's faculty and lab pages for professors working on topics you care about.
- Tells you only what the page actually shows about undergraduates, and never guesses that
  someone has an opening.
- Summarizes a professor's recent work and drafts a short email in your voice.
- Saves the draft to Gmail (never sends it) and tracks who you've contacted, with a follow-up
  reminder about a week later.

**Do the research**
- Keeps a log: text an update ("ran trial 3, results were off") and it saves it.
- Recalls what you did last week or what you're stuck on.
- Prepares you for lab meetings: what I did, what's stuck, what's next.
- Sets reminders before meetings.

## Example

```text
Dr. Jane Lee, Computer Science (robotics)
https://example.edu/jane-lee
Why it fits: works on robot navigation, which matches your interest
What the page says: her group welcomes undergraduates, but no funded opening is confirmed
Recent work: "Example paper title" (link)
```

## Install on Cubbie

Text Cubbie this link, and reply "yes" when it asks to install:

```text
https://github.com/HHung310/research-path/tree/main
```

To update after changes, text the same link again.

## Try it

- "I'm a sophomore studying computer science and I'm curious about robotics. Who could I do
  research with?"
- "Help me write an email to the first professor."
- "Ran my first training run today, the loss barely moved."
- "I have a meeting with my professor tomorrow, help me prepare."

## What it needs

- Cubbie. No keys, no sign-in, no scripts.
- Optional: a connected Google account, so email drafts can be saved to Gmail.

## Privacy

Everything is saved in your own Cubbie memory. The Skill reads only public faculty and lab pages,
and it never sends an email or message for you.

## Files

- `SKILL.md`: the instructions Cubbie follows
- `references/finding-research-pages.md`: tips for finding a school's research pages
