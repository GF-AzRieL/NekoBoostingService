# NekoBoostingService
The ultimate (satirical) elite boosting platform for Strinova. Featuring high-velocity rank climbs, professional throwing services, and the most sophisticated 'Bablo' economy on the web, offered by the Azu Corp. 

https://neko-boosting-service.netlify.app/

A parody boosting service website built for Strinova — made as a joke for the community, with way too much effort put into it.

> *"THIS IS A JOKE GUYS DONT TAKE IT SERIOUSLY... BUT I ACCEPT GENEROUS DONATIONS HIHI"* — Azumachi

---

## What is this?

It's a fake boosting agency website built around a group of friends who actually play Strinova at a high level. The site presents each person as a professional "booster" with their own exaggerated lore, rank, and specialty. Neko hard carries. Azumachi hard throws. Elabearie holds multiple Top 10 spots simultaneously across different accounts. You get the idea.

No real money is exchanged. No accounts are actually touched. It's just a bit with a clean UI slapped on top.

---

## The Roster

Each booster has their own profile tab on the site with a description, rank badge, main characters, and specialty. Here's the full team:

| Name | Title | Rank | Specialty | Mains |
|---|---|---|---|---|
| **Neko** | The Singularity Player | Singularity | Hard Carry | Anything you want |
| **Azumachi** | The Troll | Quark (boosted) | Reverse Boosting | Anything you want |
| **Elabearie** | The Multi-Account Warlord | Singularity | Elite Coaching | Yugiri / Fragrans |
| **Emiko** | The Eika Specialist | Singularity | Gaming Companion | Eika / Michelle |
| **Keroppi** | The Sniper Sensei | Singularity | One Trick Sniper | Kanami / Kokona |
| **Lifhee** | The Singularity Ace | Singularity | Precision Carry | Flexible |
| **Glacyeon** | The Professional Cat Gamer | Singularity | Cat Pro Gamer | Michelle |
| **Junlean** | The Baimo Incarnate | Singularity | Baimo | Baimo |

---

## Services Offered (fake)

The site has three main service categories, each broken down into sub-options:

**Rank Boosting** — You hand over your account (or play alongside), the booster does their thing, you climb. The site lists it as starting from $3.99 depending on which ranks you're going between. There's even a "Best Value" tag on the mid-tier package.

**Placement Matches** — For when you just want your placement games played by someone who actually knows what they're doing. Also useful if you can't be bothered to tryhard 10 matches for your starting rank.

**Crystals & Currency** — Probably the most troll section. You pay Neko to farm in-game currency for you. Prices are listed for 2-crystal and 4-crystal packages.

---

## How It Works (according to the site)

1. Pick a package
2. Give your Discord ID and region (no password needed for Duo/Coaching)
3. Sit back while the guys handle it, or queue alongside them

There's a proper "How It Works" section on the page with animated step icons that glow cyan on hover. It looks clean.

---

## Tech

Single HTML file. No frameworks, no build tools, nothing to install.

- **CSS**: All vanilla. Heavy use of `clip-path` for that sharp angular UI look (the clipped corners on buttons and cards), `backdrop-filter` for the frosted glass nav, and keyframe animations for the scrolling marquee review section.
- **JS**: Minimal. Just the tab switcher for the booster profiles and a scroll listener that shrinks the header on scroll.
- **Fonts**: Rajdhani for headings/buttons (gives it that competitive game aesthetic), Inter for body text.
- **Color palette**: Two main accent colors — `#00F0FF` (cyan, used for primary actions and glow effects) and `#FF6B00` (orange, used for tags and secondary highlights). Background is near-black at `#0A0B10`.

The hero and services sections use parallax backgrounds with a dark overlay. There's also a fixed disclaimer badge in the top-left corner that stays on screen at all times, which is the first thing you see and sets the tone.

---

## Reviews Section

The testimonial section is a dual-track auto-scrolling marquee. One row scrolls left, the other scrolls right. It pauses on hover. The reviews are from community members and are... in character. Some praise Neko for carrying them to Singularity. Others thank Azumachi for successfully dropping them three divisions. One person seems genuinely unsure what happened.

---

## FAQ

There's a small FAQ section at the bottom. Questions include things like "Is this safe?" and "How long does it take?" with answers that are technically serious but still clearly part of the bit.

---

## Structure

```
Neko Boosting Site/
├── index.html          # Everything — styles, markup, and scripts all in one file
└── images/             # Booster avatars, rank icons, background images, favicon
    ├── neko_avatar_new.png
    ├── azumachi_char.png
    ├── elabearie_avatar.png
    ├── emiko_avatar.png
    ├── keroppi_avatar.png
    ├── lifhee.png
    ├── glacyon.png
    ├── junlean.png
    ├── rank_singularity.png
    ├── rank_quark.png
    ├── hero_bg.jpg
    ├── services_bg_v2.jpg
    └── favicon.png
```

No build step. Just open `index.html` in a browser and it runs. If you're in VS Code, Live Server works fine.

---

Made by Azumachi 🐾


