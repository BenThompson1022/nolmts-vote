# Vote page — review brief for Brand Bot

**What it is:** a one-page share link for the Best of Northwest Arkansas 2026 contest. NO LMTS is
nominated in **Services → Marketing / Creative Agency** (listed as "NO LMTS Marketing").
Going live at **nolmts.ai/vote**. Preview: https://claude.ai/artifact/WsCd9SfUoMXgGPtk3ReYBW

**The page's one job:** get a friend, client or follower to vote today AND add a daily reminder so
they vote every day until voting closes.

## Facts (verified on votebestnwa.com, 2026-11-18)
- Vote once a day through **12/11/2026 5:00 PM** (Central).
- Path: votebestnwa.com → Services → Marketing / Creative Agency → NO LMTS Marketing (11th of 13).
- The vote site is a single-page app with **no deep link** to the category and no way to preselect a
  nominee, so the page can't prefill the vote. It links out + gives the 3 taps.
- Results: BestNWA.com + winners magazine 03/21/2027.

## Files
- `index.html` — the page (self-contained; Google Fonts only).
- `vote-reminder.ics` — Apple Calendar version, daily 8 AM CT until Dec 11 (to text/email by hand).

## Calendar button
Builds a Google Calendar template link: daily, viewer's chosen time (default 8 AM), viewer's time
zone, `RRULE:FREQ=DAILY;UNTIL=20261211T230000Z`, details = link + steps. Tested: opens prefilled
as "Daily, until Dec 11, 2026".

## Brand locks it must respect
- Say **NO LMTS** in letters. Never say "A-I". **Paid media**, never "ads". **Business**, never "shop".
- No invented metrics, prices, testimonials or client wins.
- Look: black + the gold from the Best of NWA badge (contest-specific, not the main site kit).

## What to critique
1. Hook: does the H1 + first line make someone vote right now?
2. Friction: anything between "open link" and "vote cast" we can cut?
3. Reminder: will people actually tap "Add to Google Calendar"? Better wording/time?
4. "Who you're voting for" copy: on-brand? too long?
5. Mobile: most opens come from IG/text on a phone.

Reply with concrete line edits, not general notes.
