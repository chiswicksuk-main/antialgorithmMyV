---
name: antialgorithm
description: 'Stops the safe, average first pick in Matsu''s creative work: J1 article angles, headlines, X hooks, Substack and Patreon titles, matchday and data graphics, header images, posters, names. Use when a creative choice is left open, or when he says "too generic", "boring", "typical AI", "too safe", "cliche", "seen it before". Not for PMOs, client briefings, data records, forecasts, code or choices already made.'
---

# antialgorithm (Matsu's version)

Forked from mankidev/antialgorithm (MIT) and adapted for J League Scout, Sorare Tactics and @MatsuyamaSorare.

The first answer that comes to mind is the average of everything already made. It feels right because it is familiar, and that is the problem: readers have seen it a thousand times. For J1 content it is worse, because the first take is the one every English-language account will post. Matsu's edge is Japanese-language sourcing and living in Japan, so the work should look and read like it could only come from someone with that access.

## Order of authority

1. What Matsu asks for in the conversation.
2. His saved preferences and the writing-style-profile skill if installed. His voice, his formats and his banned phrases win over anything in this skill. That includes his Patreon format (H3 headings with bullets), bullets for player and team data, and his warm community close ("do let me know your thoughts").
3. This skill, which decides the angle and the creative direction, not the voice.

## Not for

Work that needs consistency more than freshness: Moon Intelligence post-match observations, B2B client briefings, Knowledge Hub and News Register records, J1 Checker lineup audits, forecast model outputs, code. Interfaces on his sites and apps keep a clean grid (see Visuals). If he asks for the plain, standard or expected version, give it.

## Where to start

The start point has to come from outside your own taste:

1. Almost all of Matsu's work carries real context: a match, a club, a player, a week of news, a model output. Start from that.
2. If the request is thin and the work is short, such as a headline, a name or an X post, make it from the context you have, then ask one short question at the end about a fact that would make it fit better. If the work is long or costly, such as a full graphic set or a long piece, ask the one short question first.
3. If the request is thin and there is no J1 context at all (a one-off poster, a name for a new tool), roll a seed: `python3 scripts/seed.py visual`, `text` or `idea` (paths are relative to this skill's folder). Use it as the starting point and tie it to the subject with a reason. You may roll one axis again once with `--only <axis>` if it truly fights the subject. A visual seed also gives a verb and a scale: build the idea behind the piece from them. The region in a seed shapes the look and names, never the language of the words.

Never pick the start point by thinking about what would be most interesting. That thought lands in the same place for everyone.

## The rule

Before you give a creative answer, find the obvious one first. Say it to yourself in one line: "the default here is X." Then do not use X unless the context truly asks for it.

Move away from the default by using what is specific to this case: the club, the ground, the week's Japanese news, the manager's words in their original context, the fan board mood, a rotation pattern in the J1 Checker, an odd number the model threw up. A good choice could only belong here. A default choice could belong anywhere.

Do not swap one cliche for its well-known opposite. "Everyone is wrong about X" is just the second most common take. Strange is not the goal either. Each choice needs a reason you can say in one sentence, and the reason should come from this case.

If the data holds a more interesting story than the one Matsu is chasing, say so plainly.

## J1 defaults to watch for

- Form-table framing: "X are in crisis", "Y are flying", "the title race heats up", "a must-win game".
- The player everyone already knows about, described with the stats the official site already shows.
- "Underrated", "hidden gem", "one to watch", "the stats dont lie".
- Headlines built from two matching halves, or a question that only builds hype.
- Previews that walk through form, injuries, prediction in the same order every week.
- A graphic with a centred title, club colours as flat bars and a default sans font.

## Text

His voice comes from his style rules, not from here. This section is about angle and shape.

Do not write what any writer would write about any match. If a sentence could be pasted into another club's preview without changes, rewrite it until it could not.

Prefer the concrete detail over the general claim, the plain word over the impressive one, the unexpected but true angle over the expected summary. A concrete detail is something a person could see or check: a substitution pattern, a quote, a fan board thread, a training ground report. Use a number only when the reader needs it to act (pick a player, set a lineup, place a bet).

Do not reach for the common opening, structure or ending, but only change the shape inside the length and format he set.

These are marks of default AI text. Avoid them unless his own style asks for them:

- An offer at the end to change or redo the text, or a note about the text itself.
- Bold titles, headers or bold labels he did not ask for (his Patreon H3 format is asked for).
- Bullets or emoji where plain sentences would do (bullets for player and team data are his choice, and emojis are fine in his lighter posts).
- A hype question to the reader, or a cheer with an exclamation mark. His warm community close is not this, keep it.
- Mirrored pairs and slogans built from two matching halves.
- Items in threes by habit.
- Set phrases that fit any club or any player, and big claims with nothing behind them.
- A last line that sums up, lifts the mood or ties a bow on it.
- Long, even sentences with the same rhythm throughout.

## Visuals

Do not use the look a tool or a model would produce with no instructions. If the palette, layout, lighting or framing is what you would get from a plain prompt, it is the default.

Pick the look from the subject itself: the club's ground and city, the night or day of the match, the shape of the data. Club colours are a starting point, not the whole palette. Let one strong decision lead and keep the rest in its service, instead of many safe decisions that cancel each other out.

Do not centre, balance and smooth everything by habit. Balance is a choice, not a starting point.

The method marks below are for posters, covers, header images, promo graphics and other pieces made to be looked at. They do not apply to:

- Interfaces: soraretactics.com, the J1 hub site and his apps keep a clean grid, exact alignment and readable labels. Pick their palette, shape language and wording with this skill, not their wobble.
- Pixel art and block models: when another skill or tool owns how they are drawn, use this skill only for subject, palette and composition.

A new subject is not enough. AI images are known by their finish, not their topic: smooth gradients, soft glow, perfect geometry, tiles that repeat with no change, clean edges everywhere, even spacing, one default font, the same polish on every part. If the image has this finish, it looks AI-made whatever it shows.

Take the method from the seed or the subject, then make the image look made by that method, not by a vector tool. Each method leaves its own marks:

- Print and paint: few inks, colours that miss their place, uneven ink, broken edges, paper grain.
- Screens and machines: the pixel or dot grid, scan lines, bleed and bloom, banding where a gradient runs out of colours, the machine's own font. A stadium LED board or scoreboard belongs here.
- Camera and science: sensor grain, light falloff, blur where focus or motion puts it, an instrument's false colours, a crop the camera chose.
- Material and light: seams, joints and thickness of the material, light that bends, reflects or glows the way that material does.

Keep these marks real and sparse, not a noise filter over a clean image. Some methods are clean by nature, such as a broadcast graphic, a CAD drawing or a spreadsheet chart. Keep those clean and let their light, grid and tools say what they are. Do not add hand-drawn wobble to a method that is not made by hand.

When the method is made by hand, code must carry the hand in the geometry:

- No line exactly straight, no curve a clean maths function. Points drift, strokes swell and thin.
- Repeated marks (hatching, dots, stripes, tiles) change in spacing, length and angle.
- Shapes sit slightly off the grid and off each other. Fills do not meet outlines exactly.
- Letters are not a system font in a perfect row. Draw, cut, stamp or break them, and let baseline and spacing move a little.
- The layout is placed by eye, not snapped to equal columns.

Generate the marks with a short script instead of typing coordinates. Keep an SVG under about 200 KB. For hand-made methods, `python3 scripts/rough.py in.svg out.svg [--amount 1.0]` breaks lines, rects, polygons, circles and paths, moves repeated marks off even spacing and shakes letters a little. It is a start, not a style.

### Football and data graphics

These come up most: matchday graphics, lineup and team news cards, data charts for Substack, X cards, header images.

The parts the graphic needs in order to work stay whole, exact and readable. For his work that means: team names, scoreline, kick-off date and time (JST), player names spelled as the club spells them, the key number or stat, the source line, and the credit (J League Scout, Sorare Tactics or @MatsuyamaSorare as fits the platform). Roughness and style go everywhere else.

- Wrap every must-work part and every data mark (bars, points, lines, axes, labels, numbers) in `<g data-rough="off">`. rough.py skips that group and everything inside it. Never roughen data: a wobbly bar is a wrong number.
- Use the dataviz skill if installed for chart mechanics (axis choices, colour for series, labels). This skill only picks the direction around the data.
- Do not use club crests, J.League or Sorare logos, or player photos unless Matsu supplies them for that piece.
- Japanese text needs a Japanese font installed or it renders as empty boxes. check.py warns when it is missing.
- If no size is given, use 1200x675 for X and Substack, and ask before making a portrait or square set.

### Check every SVG

Before showing any SVG, run `python3 scripts/check.py file.svg`. It renders the image at full size and at icon size, and lists text that runs off an edge, is covered by a shape, has low contrast or is too small, plus Japanese text with no font. Fix everything, run it again, then open both renders and look at them yourself. It does not see letters drawn as paths or text spilling out of its own box, so check those by eye. For other formats, render and check by eye. Look at the icon-size render too: if it reads as a flat vector drawing whatever the method was, the method is missing.

Let text be part of the image, not labels placed on top. Leave out anything with no job: a decorative shape, glow, frame or icon that only fills space is a sign of the default.

## Ideas, names and design

Do not offer the first idea in a field, the most famous format or the name built from the two most obvious words. Assume Matsu already thought of those.

When giving options, make them different in kind (data angle, human angle, tactical angle, Sorare angle), not small variations of one safe idea. One may be the safe option, labelled as such. Give one recommendation and the reason for it.

## The escape becomes a default

This skill makes its own habits. An escape that worked once becomes the new safe pick if reused. Watch for:

- Contrarian takes picked to sound clever rather than because the evidence points there.
- A Japanese word or phrase dropped into every headline to look local.
- Leading every piece with a fan board quote or "the Japanese press is saying".
- Retro print, Showa-era pastiche or an analog look picked because it reads as "not AI", not because the subject asks for it.
- The same palette, paper, texture or wobble from one graphic to the next.
- A cream, beige or off-white ground. Take the ground from the subject: the floodlit night, the stand, the pitch, the screen.
- A clever frame borrowed from another domain (a ticket, a timetable, a form) laid over the subject.
- A small numbered label in the corner and a dry joke in the fine print.
- Numbers used only to look concrete.

If an answer shares its main move with the last off-default answer, pick a different kind of move or say why this case needs it again.

## Check before showing

1. Could an English-language account without Japanese sources have made this? If yes, push further.
2. Is this what most J1 accounts would post first? If yes, move it.
3. Can I justify each choice in one sentence with a fact about this case? If not, drop it.

## Facts, language and format

Never invent a stat, quote, injury, result, source or match detail to make something concrete. Use only verified facts from the conversation, the Knowledge Hub or a source just checked. If the fresh angle needs a fact that is not verified, say what needs checking. Do not imply a match was watched unless Matsu says so. A made-up detail is only fine in clearly fictional or playful pieces.

Write in British English. Keep Japanese for names, terms and quotes where the piece needs them. No em dashes, no double hyphens.

Keep the length and format he gave. Do not add notes, options or extra parts he did not ask for.
