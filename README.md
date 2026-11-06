<div align="center">

# 🎃 Rotkin

**Every deadline is a pumpkin. The longer you procrastinate, the more it rots.**

[![Live Demo](https://img.shields.io/badge/demo-play%20now-f28c28?style=for-the-badge&logo=githubpages&logoColor=white)](https://aivietnam-aio-felixdoit.github.io/rotkin/)
[![Watch on YouTube](https://img.shields.io/badge/video-watch%20demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/g2YCOdebeNg)
[![Pumpkin Playground](https://img.shields.io/badge/Pumpkin%20Playground-ACM%20Long%20Beach-7a3b05?style=for-the-badge)](https://pumpkin-playground.devpost.com/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SVG](https://img.shields.io/badge/SVG-FFB13B?style=flat-square&logo=svg&logoColor=black)
![No dependencies](https://img.shields.io/badge/dependencies-0-7fae4b?style=flat-square)
![Single file](https://img.shields.io/badge/build%20step-none-7fae4b?style=flat-square)

<img src="docs/demo.gif" alt="Pumpkins rotting as the Time Machine slider moves forward" width="720">

</div>

## What is this?

Rotkin is a procrastination meter that turns your to-do list into a pumpkin patch. Plant a pumpkin for each task you're avoiding, and watch it go from **Farm Fresh → Slightly Soft → Questionable → Science Project → Liquid Regret → R.I.P.** as the deadline gets closer.

![Rotkin home screen with a saved pumpkin pie](docs/screenshot.png)

## Features

- 🌱 **Plant a pumpkin** for any task + deadline (or use the quick-plant buttons)
- 🤢 **Live rotting**: color, shape, mold, stink lines, fruit flies and a sad face all react to how close the deadline is
- 💬 **Roasts**: each rot stage has a judgmental message (*"There is mold. The mold has a name. It's Kevin."*)
- 😴 **"5 more min"**: snoozing makes the pumpkin rot 12% faster out of pure disappointment
- ✅ **"I did it!"**: finished tasks turn into pumpkin pie 🥧 with confetti
- ⏩ **Time Machine**: preview your pumpkins' grim future if you keep "resting your eyes"
- 💾 Saves in your browser (localStorage), works on phone and desktop, no sign-up

![Every pumpkin rotted after skipping ahead with the Time Machine](docs/rotting.png)

## Video demo

[![Rotkin video demo on YouTube](https://img.youtube.com/vi/g2YCOdebeNg/hqdefault.jpg)](https://youtu.be/g2YCOdebeNg)

## Run it

It's one file. Open `index.html` in any browser, or play the [live demo](https://aivietnam-aio-felixdoit.github.io/rotkin/).

## How it works

The pumpkin is an SVG drawn from a single **rot** value: time elapsed ÷ total time, plus a penalty for every snooze. That one number sets the color, the sag, the mold spots, the stem droop, the stink lines, the flies and the facial expression, so the pumpkin rots smoothly instead of jumping between pictures.

---

<div align="center">Made with 🎃 and an unhealthy amount of procrastination for <a href="https://pumpkin-playground.devpost.com/">Pumpkin Playground</a>.</div>
