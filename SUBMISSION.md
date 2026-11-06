# Devpost submission: copy & paste

**Project name:** Rotkin

**Elevator pitch / tagline (≤200 chars):**
A procrastination meter where every deadline is a pumpkin. The longer you put it off, the more it rots: mold, flies, and judgmental roasts included. Finish the task and it becomes pie. 🎃🥧

**Built with (tags):** html, css, javascript, svg, github-pages

**Try it out links:** <your GitHub Pages URL> , <your GitHub repo URL>

**Video demo link:** <YouTube link to rotkin-demo.mp4>

---

## Inspiration
Every student has a to-do list they ignore. A list doesn't make you feel anything, but watching a cute pumpkin slowly turn into a moldy puddle of regret because of *you*? That hits different. We wanted a productivity tool that uses spooky-season guilt instead of boring notifications.

## What it does
- You "plant" a pumpkin for each task you're avoiding and set a deadline.
- As the deadline gets closer, the pumpkin rots in real time through 6 stages: **Farm Fresh → Slightly Soft → Questionable → Science Project → Liquid Regret → R.I.P.** It changes color, sags, grows mold, starts to stink, attracts fruit flies, and its face goes from happy to crying to X_X.
- Every stage comes with a roast, like *"There is mold. The mold has a name. It's Kevin."*
- Hitting **"😴 5 more min"** makes the pumpkin rot 12% faster out of pure disappointment.
- Hitting **"✅ I did it!"** saves the pumpkin and turns it into **pumpkin pie** with confetti.
- The **Time Machine** slider lets you preview your pumpkins' grim future if you keep procrastinating.
- Stats track pies baked, pumpkins lost, and how many times you snoozed.

## How we built it
It's one HTML file with vanilla JavaScript. The pumpkin is a hand-built SVG that's generated from a single "rot" value (time elapsed ÷ total time, plus a snooze penalty). That value drives the color blend, the squash/stretch, the mold spots, the stem droop, the stink lines, the flies and the facial expression. Tasks are saved in localStorage, so there's no sign-up or backend.

## Challenges we ran into
Making the pumpkin look like it rots *gradually* instead of jumping between pictures. We ended up interpolating colors and shapes continuously and fading mold spots in one by one. We also had to stop the page from re-drawing every second, because that reset the fly animations.

## Accomplishments that we're proud of
The pumpkin is genuinely gross by the end, and the "5 more min" button makes people laugh every time. It's also actually useful: it's a real countdown tracker for deadlines.

## What we learned
SVG + a single number can make a surprisingly expressive character, and guilt is a powerful UX tool. 🎃

## What's next for Rotkin
Browser notifications when a pumpkin hits "Science Project", sharing your Patch of Shame with friends, and a group mode where everyone's pumpkins rot together on a shared project.
