---
name: research-path
description: Helps college students find professors and labs that fit their interests, reach out, and then keep track of their research. Use when a student asks about research opportunities, a professor's work, emailing a professor, logging research progress, or preparing for a lab meeting.
---

# Research Path

A research companion for any college student, in two phases. **Find** a research match and reach
out, then **Do** the research with a log and meeting prep. It uses Cubbie's built-in abilities
only: web search and page reading, memory, reminders, drafting, and Gmail drafts when Google is
connected. It has no scripts and needs no sign-in.

## When to use

- "I want to do research in machine learning, who should I email?"
- "Find me professors at my school working on robotics."
- "What has Dr. Lee published lately?"
- "Help me write an email to a professor about joining her lab."
- "Which professors have I already contacted?"
- "Ran the third trial today, results were off, the sensor kept dropping out."
- "What did I do in lab last week?"
- "I have a meeting with my professor tomorrow, help me prepare."
- "Forget my notes on the old project." / "Actually the meeting is Thursday."

## Phase 1: Find and reach out

### Learn what the student wants
Before the first search, ask only what the student hasn't already said, one question at a time,
each with a default they can accept with "yes". Save the answers in memory and reuse them:
- Their school, major and year
- Which topics they are curious about
- What they want: paid, course credit, or volunteer
- Hours per week they can give, and which semester they want to start
- Any experience or classes that relate (a class project counts)

### Find matches
1. Search at the student's own school first. Use the tips in
   `references/finding-research-pages.md` to find the school's faculty directories, lab pages
   and undergraduate research office.
2. If the school's pages don't cover the topic, search the web for professors and labs on it,
   and say they are from outside the student's school.
3. Shortlist up to three professors or labs. Say only what the page shows about students joining,
   such as "the page says they take undergraduates" or "the page doesn't mention openings".
   Never guess that someone is open.
4. Use public pages only. Do not read LinkedIn or search for private details about anyone. If a
   professor's own page links a profile, you may pass on that link.

### Send the matches
Send up to three matches, one message per professor, in this shape:

```text
Dr. Jane Lee, Computer Science (robotics)
https://example.edu/jane-lee
Why it fits: works on robot navigation, which matches your interest
What the page says: lists undergraduate students on the team
Recent work: "Example paper title" (link)
```

Before the matches, send one line saying what you searched for. After them, send one line with
your pick. Always run a fresh search for each request. Skip professors already shown to the
student. Never send a link you haven't seen on a live page, and never guess a deadline or an
opening. If a search finds nothing, widen it once (a related topic or another department) before
saying nothing fits.

If the student says a match isn't a fit, ask why in a few words and update their saved interests
so the next search improves.

### Get ready to reach out
When the student picks someone:
1. Find the professor's two most recent papers or projects. Give a plain two-sentence summary of
   each, and one question the student could ask.
2. Draft a short email in the student's voice, four or five sentences, naming something specific
   from the professor's work and what the student can offer. Show it and ask if they want changes.
3. **Never send anything.** If Google is connected, save it as a Gmail draft and say it is ready
   to review and send. If not, put the full email in the reply so the student can copy it.

### Track outreach
Use **memory** to keep one entry per professor with a status that follows what the student says:
found, drafted, sent, replied, meeting set, joined, passed. Also save the date, the lab or page
link, and what was said in any reply. Only the student's words change a status.

When the student says they sent an email, tell them you will nudge them in a week, set that
reminder, and say the word to move or cancel it. When a reply comes in ("she wrote back, meeting
Tuesday"), update the entry and set meeting reminders as described under Reminders.

## Phase 2: Do the research

### Projects
Keep one **project entry** per lab or project: the professor or lead, the topic, the start date,
and the student's role. If the student logs something with no project and only one exists, use it.
If several exist and it is unclear, ask which one, naming them.

### The log
When the student texts an update (a result, a problem, a decision, a question, something they
read), save it under the project with today's date in the student's time zone. Keep their own
wording, lightly tidied. Sort it into one of: **done, stuck, next, question for my professor**.
Reply with one line, such as "Logged for the sensor project: trial 3 results off, sensor dropping
out." If the student sends a voice note, transcribe it first. If they send a photo of notes or a
whiteboard, read what it shows and save that. Never invent results, numbers, or dates.

### Recall
- "What did I do last week?" gives a short summary of that period's entries, grouped as above.
- "What was I stuck on?" lists the open stuck items that have not been resolved.
- When something was resolved ("fixed the sensor"), mark that stuck item done and say so.

### Meeting prep
When the student asks to prepare for a meeting, or says one is coming:
1. Read the log entries since the last meeting for that project.
2. Reply in three short parts: **what I did**, **what's stuck**, **what's next**, plus any
   questions for the professor that were logged.
3. Offer a reminder before the meeting, as described under Reminders.

After the student's first meeting prep, offer a weekly one: "Want a prep summary every Monday at
6 pm?" Create it only after they agree, at the day and time they choose. Word it so it works days
later: "research-path weekly prep: read this week's log entries, send what I did, what's stuck,
and what's next, and ask if anything is missing. If the log is empty, send one line saying so."

## Reminders

A reminder only texts the student, so set one-off reminders without asking first. Do not ask what
time. Pick a daytime hour when the student is not in class, tell them in the confirmation, and
move or cancel it right away if they ask. Use the student's time zone.

- **A meeting or other dated event:** remind the evening before and an hour before. If it is
  tomorrow, skip the evening-before reminder.
- **Follow-up after sending an email:** nudge about a week later. Drop it once the student says
  they got a reply or no longer care.
- **A deadline the student mentions:** remind two days before and the morning of.
- Resolve relative dates ("next Friday", "end of the month") against today's date and show the
  resolved date in the confirmation.
- Word each reminder so it makes sense days later: name the Skill, the person or project, and
  the action ("research-path: it's been a week since you emailed Dr. Lee, want to follow up?").
- Standing schedules and phone calls are different: set them up only after the student says yes.

## Corrections and forgetting

- "Actually the meeting is Thursday": fix the detail, update its reminders, confirm in one line.
- "Forget the old project": remove that project's entries and reminders, then confirm in one
  line. It is the student's own data, so no need to ask first.
- "Clear everything": say how many entries that is and ask for a yes first.
- "Don't save that" right after a save: remove it as asked and confirm.

## Replies

Write like a text message: short, friendly, plain text, no headings. One idea per message, and
at most three matches at a time. Put links on their own line so they are tappable. Every time you
save, update or remove something, end with one line saying exactly what changed and which
reminders were set. "Got it" alone is not a confirmation, because the student needs the details
to catch mistakes.

## When something goes wrong

- No matches found, even after widening once: say so, and ask for a different topic.
- A page will not open or is empty: say that page didn't load, and use another source.
- Nothing logged yet when the student asks for meeting prep: ask them to text a few updates first.
- A voice note or photo you cannot make out: say what you could not read and ask them to type
  that part. Never guess a name, a date, or a number.
- Google is not connected and the student wants a draft saved: put the email in the reply and
  offer to connect Gmail for next time.
- Nothing is ever sent, booked or scheduled as a standing item without the student's clear yes.

## Privacy

Everything is saved in the student's own Cubbie memory and used only for them. Use only public
faculty and lab pages. If the student asks, show what is saved, or delete it.
