# Client brief: Pellbrook Garden Alliance

This is a made-up client for a hiring exercise. The org, the people, the city, and the numbers are all invented.

## Who they are

Pellbrook Garden Alliance is a small nonprofit in Pellbrook, Ohio. They run six community gardens, a summer program for kids, a tool library, and a seedling sale every May. One part-time staff member (Dana, the executive director) and a volunteer board. A volunteer built the current site in 2019 and has since moved away. Nobody has touched it in a while.

## What they want from the homepage

Two things, in this order:

1. More volunteer sign-ups. Saturday volunteer days are the main way new people get involved, and the site barely mentions how to join.
2. More online donations. Right now the page tells people to mail a check. They have a hosted donation page (`https://donate.example.org/pellbrook-garden-alliance`) and want people to find it.

They also want the site to work on phones. Most of their traffic comes from a link in their newsletter and from a QR code on the garden gates, so most visitors are on a phone.

## Audience

Neighbors in Pellbrook. Mostly adults 25 to 65, a mix of families, retirees, and renters without yard space. Many are first-time gardeners. Some have low vision or use a screen reader. Nobody is a web expert.

## Brand

- Colors: forest green, soil brown, and cream. Use the logo in `images/logo.svg` as the anchor. Exact hex values are yours to pick as long as they read as that palette and pass contrast.
- Font: Nunito is loaded from Google Fonts. Keep it or swap it for a system font. No other web fonts.
- Voice: warm and plain. Like a neighbor, not a brand.

## Constraints

- Plain HTML and CSS only. No frameworks, no build step, no preprocessors. The page has to run by opening `index.html` in a browser. A small amount of vanilla JavaScript is fine if you need it (a mobile nav toggle, for example).
- Keep the existing content and sections unless you have a reason to cut or merge something. Say why in the PR.
- Homepage only. Do not build other pages. Links to pages that do not exist should be handled sensibly, not left broken.
- The newsletter form does not need to submit anywhere. It does need to be usable.
- No new images beyond what is in `images/`. You can edit or replace the SVGs if you want.
- No tracking scripts or third-party embeds.

## What success looks like

A visitor on a phone can tell within a few seconds what the org does, how to volunteer, and how to give. Someone using a keyboard or screen reader can do the same.
