# MotionOps Founder Post Review

Interactive UI mockup of a LinkedIn post review and scheduling portal for MotionOps founders (Trevor and Nikola).

## What it does

- **Admin mode** (Braca): create posts before founders see them - upload visual, write caption, pick founder, date and time. Manage each founder's pipeline, resend fixed posts, delete drafts.
- **Posts feed** (founders): scroll big post cards, edit the text inline, change date/time, then click **Schedule** or **Not approved** (with a note explaining what to fix).
- **Calendar**: month view with status dots, drag a dot to reschedule, click to edit text and visual in a popup.
- **Stats**: per-founder metrics (followers, impressions, reach, engagement), per-post performance table, daily impressions chart with Week/Month toggle, format breakdown, posting cadence.

## Run

Open `index.html` in a browser. Single self-contained file, no build, no dependencies. All state is in-memory (refresh resets it) - this is a mockup for the real app (planned: Cloudflare Pages + Worker + D1 + ContentStudio API for publishing).
