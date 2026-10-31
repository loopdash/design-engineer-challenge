# Loopdash design engineer challenge: Arkhelm Aerospace

This is the take-home for our **Design Engineer** role. It suits students and recent grads. There is no years-of-experience requirement.

Loopdash is a small web agency. In this job you read client email, design and build pages from a client's brand standards, ship them as pull requests for Gary to review, and tell the client what changed in plain language. This exercise has you do each of those once.

## The scenario

Open `index.html` in the repo root. It is an email from Dana, head of communications at Arkhelm Aerospace, a hard-tech startup that builds reusable rockets. Marcus is the CEO. She attached three things:

- **The current site** in `site/`. The homepage is finished and on brand. Treat it as the reference for how Arkhelm looks on the web.
- **The brand sheet** in `brand/`. Logo files, colors, fonts, photography, and voice. Open `brand/index.html`.
- **The event notes** in `content/open-house.md`. Facts for a page that doesn't exist yet. No layout, just facts.

Prefer to look before you clone? The live versions are here: [Dana's email](https://loopdash.github.io/design-engineer-challenge/), [the current site](https://loopdash.github.io/design-engineer-challenge/site/), and [the brand sheet](https://loopdash.github.io/design-engineer-challenge/brand/). To do the work, fork the repo (steps below).

The main job is the Open House RSVP page. The homepage nav already links to it, but nobody has designed it. You will, using only the brand sheet and the homepage as your guide. Dana's other asks are quick. Some are exact, some pull against good design. Make a call, and say what you decided.

Arkhelm, Dana, Marcus, and everything else here are made up. Do not look anyone up or contact anyone.

## What to deliver

1. **A short plan.** A few lines in `TASKS.md` or at the top of your PR: what you'll do, in what order, and what you'll skip if time runs out.
2. **The Open House page, designed and built.** Create `site/open-house.html` from the brand sheet and `content/open-house.md`. It should feel like the same site as the homepage. Include an intro, what to expect, and the date, time, and location. Build the RSVP form with real states: default, hover, focus-visible, invalid (HTML validation is fine), submitting/disabled, and success. There is no backend, so fake the submit. It must work on mobile and desktop. Figma first is welcome but optional.
3. **Dana's quick homepage asks.** The other three bullets in her email. Use your judgment where an ask and good design disagree, and explain what you did.
4. **A few design tokens.** Turn the brand sheet into a small set of CSS custom properties (colors, fonts, spacing, radius, whatever earns its place) and use them on both pages. Give each a one-line comment on what it's for. Buttons need hover, focus-visible, and pressed states. Respect `prefers-reduced-motion`.
5. **A pull request** with before and after screenshots of the homepage, desktop and mobile screenshots of the new page, what changed, what you didn't do and why, and how you tested it. The PR template has a spot for each.
6. **One example of how you used AI**, in the PR. Paste one prompt or skill you used, and one thing you rejected or corrected from the output, with a sentence on why.
7. **A wrap-up email to Dana**, written after the work is done. Plain language. What's ready, what isn't, and what you need from her. Put it in `CLIENT_EMAIL.md` or in the PR.
8. **Your 3 best UX improvements**, beyond what Dana asked for. For each one, give the problem, the change you propose, and why it matters to the people using the site, in a short paragraph or 2 to 3 bullets. You don't have to build them. Budget about 15 minutes.

Optional stretch: run Lighthouse on your new page and post the accessibility score in the PR. Aim for 90 or higher.

## Time box

About 3 hours, 4 at most, for all eight. Most of it should go to the new page. When the time is up, stop and list what's left in the PR. A finished, polished page with a few things on the to-do list beats a rushed pass at everything.

## Tools

Use Claude, ChatGPT, Cursor, MCP tools, Figma and Figma AI, or anything else you like. We use them every day. Be ready to explain any line you submit.

## Ground rules

- Plain HTML and CSS, plus a little vanilla JavaScript for the form if you need it. No frameworks or build tools. The site has to work by opening the HTML files in a browser.
- Use the brand sheet's logo, colors, fonts, and photos. Don't add new brand colors or fonts.
- Leave the root `index.html` alone. It is the email, not the site.

## How to submit

1. Fork this repo.
2. Make a branch, such as `yourname/open-house`.
3. Commit as you go with clear messages.
4. Open a pull request from your fork to this repo's `main` branch and fill in the template.
5. Send us the PR link at the email address in your invite.

Optional: turn on GitHub Pages for your fork and put the link in your email to Dana as the staging link.

## What happens next

After you submit, we'll set up a 30 minute call with Gary. This is not part of the time box. You'll walk through the new page and your PR and explain your choices, including your 3 UX improvements. For a few minutes Gary will play Dana and bring you a new request, and you'll answer as you would on a real client call. You don't need to prepare anything beyond your submission.

## What we look for

- The new page looks like it belongs to the brand and the homepage, without being a copy.
- Clear hierarchy: a visitor knows what the event is, when it is, and how to RSVP within seconds.
- The form handles every state well, on a phone and on a laptop.
- Small, sensible tokens that you actually use.
- Good judgment on Dana's and Marcus's asks, explained plainly.
- Dana could read your email on her phone and know what to do next.
- You use AI tools well and catch it when they're wrong.
- You can explain your choices and hold a fair line when a client pushes.
