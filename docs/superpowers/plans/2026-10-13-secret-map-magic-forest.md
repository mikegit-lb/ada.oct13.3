# The Secret Map of Magic Forest — Present Continuous Adventure (Implementation Plan)

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** A 4-stage interactive ESL screen-slide adventure teaching Present Continuous for NOW vs. LATER to a 10-year-old A1 Turkish-speaking learner.

**Architecture:** Four linear app screens (Hook → Action Now → Timeline Contrast → Path Quiz), one guide character (Ollie the Owl) carrying the story from observation to planning, star-based reward system throughout.

**Tech Stack (delivery):** Screen-slide content spec; buildable as HTML/CSS/JS interactive slides or any slide-based app authoring tool.

**Spec:** User-provided mandatory output structure (4 stages, grammar focus, interaction types, final checklist) — included below verbatim in the stage content.

## Global Constraints

- Learner: Age 10, A1 English, native Turkish speaker.
- Tone: highly energetic, playful, extremely encouraging — no punishing feedback, every wrong answer gets a friendly hint + retry.
- Student-facing sentences: max ~8 words; A1 vocabulary only.
- Grammar: form is IDENTICAL in both uses (Subject + is/are + Verb-ing); only the context/time marker changes meaning.
- Time markers: NOW = now, Look!, Listen!, Shhh! · LATER = tomorrow, next week.
- Turkish L1 support: Word Helper chips on key screens (now = şimdi, tomorrow = yarın, next week = gelecek hafta).
- Every screen: one image description + sound/visual effect cue.
- Reward system: stars per correct answer, badge at the end.
- Connecting phrase for plans: "Our plan is..." (chosen over "We are going to..." to avoid mixing the going-to-future form with the target structure).

---

## STAGE 1: THE HOOK & WARM-UP 🗺️

### Screen 1.1 — Title Screen
- Title: "🗺️ The Secret Map of Magic Forest!"
- Subtitle: "A Grammar Adventure for Heroes!"
- Visual: dark magical forest at night, a glowing golden map floating in the air, fireflies and sparkles.
- Button: "▶ START THE ADVENTURE!"
- Effect: twinkle sound + sparkle animation on tap.

### Screen 1.2 — Meet the Guide
- Character: Ollie the Owl (big friendly eyes, little explorer hat).
- Ollie says: "Hello, hero! I am Ollie!"
- Ollie says: "The Golden Star is lost in the Magic Forest. Let's find it!"
- Interaction: tap Ollie → he spins and says "Hoo hoo! ✨"

### Screen 1.3 — Warm-Up Quiz 1 (visual MCQ — NO grammar yet)
- Image prompt: an old magic map lying open on a wooden table, glowing gold.
- Question: "Look! What is this?"
- Options (with pictures):
  - A) a cake 🍰
  - B) a map 🗺️ ✅
  - C) a ball ⚽
- Correct feedback: "YES! It's a MAGIC map! +10 stars! ⭐"
- Try-again feedback: "Oops! Look again — it shows us the way! It's a MAP!"

### Screen 1.4 — Warm-Up Quiz 2 (visual MCQ)
- Image prompt: the Magic Forest at night — big dark trees, tiny stars, one small bird on a branch.
- Question: "What can you see in the Magic Forest?"
- Options:
  - A) trees and stars 🌳⭐ ✅
  - B) cars and buses 🚗🚌
  - C) apples and juice 🍎🧃
- Correct feedback: "WOW! You can see the Magic Forest! +10 stars! ⭐"
- Try-again feedback: "Hmm! Look up — stars! Look around — trees!"

### Screen 1.5 — Mission Brief
- Ollie says: "First, we WATCH the forest NOW. 🌙 Then, we make our plan for TOMORROW! 📅"
- Word Helper chips: "now = şimdi" · "tomorrow = yarın"
- Effect: map folds into Ollie's wing. Music swells.

---

## STAGE 2: ACTION NOW — THE OBSERVATION SCREEN 🔭

### Screen 2.1 — The Magic Telescope
- Ollie says: "Shhh! Look through the magic telescope! 🔭 It is night. Watch what is happening NOW!"
- Grammar Gem box:
  - "We say: is / are + verb-ing"
  - Kid rule: "1 friend → is 🐦 · 2+ friends → are 🐦🐦"
- Word Helper chip: "NOW = happening right now! = şimdi"

### Screen 2.2 — Visual Prompt 1 (Drag & Drop)
- Image: ONE blue bird flying over the moonlit trees.
- Ollie says: "WOW! Look! One bird! It is flying!"
- Sentence frame: "The bird ___ flying."
- Drag tokens: [ is ] [ are ]
- Answer: **is**
- Correct feedback: "YES! One bird → IS! The bird IS flying! +15 stars! ⭐"
- Try-again feedback: "Hmm! Count the bird: 1, 2, 3... only ONE! One friend → IS. Try again!"

### Screen 2.3 — Visual Prompt 2 (Drag & Drop)
- Image: TWO rabbits jumping near the river, water splashing.
- Ollie says: "Look! Two rabbit friends! Hop, hop!"
- Sentence frame: "The rabbits ___ jumping."
- Drag tokens: [ is ] [ are ]
- Answer: **are**
- Correct feedback: "AMAZING! Two friends → ARE! The rabbits ARE jumping! +15 stars! ⭐"
- Try-again feedback: "Oops! Count: one rabbit, TWO rabbits! Two friends → ARE. Try again!"

### Screen 2.4 — Visual Prompt 3 (Drag & Drop)
- Image: hundreds of stars twinkling over the forest; the magic map glowing below.
- Ollie says: "Ooh! The sky is awake! Look up!"
- Sentence frame: "The stars ___ shining."
- Drag tokens: [ is ] [ are ]
- Answer: **are**
- Correct feedback: "FANTASTIC! Many stars → ARE! The stars ARE shining! +15 stars! ⭐"
- Try-again feedback: "Look up! So many stars! Many friends → ARE. Try again!"

### Screen 2.5 — NOW-Check Recap
- Text: "NOW words tell us: it is happening right now!"
- Clue-word chips: "now" · "Look!" · "Listen!" · "Shhh!"

---

## STAGE 3: ACTION LATER — THE TIMELINE SCREEN 📅

### Screen 3.1 — The Big Plan
- Visual: split screen — LEFT: moon + clock (NOW) · RIGHT: sun + calendar with a star (TOMORROW).
- Ollie says: "The map is ready! Now, our plan is BIG! Our plan is for TOMORROW!"
- Plan list appears with checkmarks:
  - "Tomorrow, we are following the map. 🗺️"
  - "Tomorrow, we are opening the magic door. 🚪"
  - "Next week, we are finding the Golden Star! ⭐"
- Ollie says: "See? SAME words — is/are + verb-ing. But TOMORROW means... it is our PLAN! LATER!"
- Word Helper chips: "tomorrow = yarın" · "next week = gelecek hafta"

### Screen 3.2 — Magic Word Box (Contrast)
- NOW (şimdi): "The bird is flying." → Happening this second! Clue words: now, Look!, Listen!
- LATER (yarın / sonra): "Tomorrow, we are opening the door." → Our plan! It is fixed! Clue words: tomorrow, next week
- Key line (big, gold): "SAME grammar. DIFFERENT time!"

### Screen 3.3 — Sorting Activity (NOW vs. LATER)
- Instruction: "Sort the cards! NOW or LATER? Drag each card to the right basket!"
- Baskets: 🕐 NOW basket (moon picture) · 📅 LATER basket (calendar + rocket picture)
- Cards:
  1. "The rain is falling now." 🌧️ (image: rain on leaves) → **NOW**
  2. "The rabbit is eating a carrot now." 🥕 (image: rabbit munching) → **NOW**
  3. "The birds are singing now." 🎵 (image: birds on a branch, music notes) → **NOW**
  4. "Tomorrow, we are opening the magic door." 🚪 (image: closed magic door + calendar) → **LATER**
  5. "Tomorrow, Grandma Fox is making a big cake." 🎂 (image: fox with cake + calendar) → **LATER**
  6. "Next week, we are finding the Golden Star!" ⭐ (image: star on map + calendar) → **LATER**
- Card feedback (NOW): "Can you see the word 'now'? NOW!"
- Card feedback (LATER): "Can you see 'tomorrow' or 'next week'? That means LATER!"
- All-correct feedback: "PERFECT SORTING! +30 stars! ⭐⭐⭐"

---

## STAGE 4: GAMIFIED ASSESSMENT — WHICH WAY DO YOU GO? 🔥

### Screen 4.1 — Challenge Intro
- Title: "🔥 Which Way Do You Go? 🔥"
- Ollie says: "Three magic doors. Three challenges. Answer RIGHT to open the way! Are you ready, hero?!"
- Mechanic explainer:
  - Step 1: Read the sentence. Find the clue word.
  - Step 2: Choose the door: NOW 🕐 or LATER 📅.
  - Step 3: Choose the correct verb!
- Star meter: 3 doors = up to 3 golden stars.

### Screen 4.2 — Door 1
- Image: a bird singing under the moon, speech bubble: "Listen!"
- Scenario: "Listen! The bird ___ a happy song. (sing)"
- Door choice: 🕐 NOW · 📅 LATER → correct: **NOW** (clue: "Listen!")
- Verb options: a) is singing ✅ · b) are singing · c) is sing
- Correct feedback: "DING! Door 1 OPENS! The bird IS singing NOW! +1 ⭐"
- Wrong time: "Hmm! 'Listen!' means RIGHT NOW. Try the NOW door!"
- Wrong verb: "One bird → IS, and we need -ING: singing! Try again!"

### Screen 4.3 — Door 2
- Image: a fox and a rabbit with backpacks, sunrise, calendar page showing "Tomorrow."
- Scenario: "Tomorrow, the fox and the rabbit ___ to the river. (walk)"
- Door choice: 🕐 NOW · 📅 LATER → correct: **LATER** (clue: "Tomorrow")
- Verb options: a) is walking · b) are walking ✅ · c) are walk
- Correct feedback: "DING! Door 2 OPENS! Tomorrow = LATER, and two friends → ARE walking! +1 ⭐"
- Wrong time: "'Tomorrow' is our plan — that's LATER! Try again!"
- Wrong verb: "Two friends (fox AND rabbit) → ARE + walking! Try again!"

### Screen 4.4 — Door 3
- Image: Ollie asleep ON the magic map, speech bubble: "Shhh!", moon + clock.
- Scenario: "Shhh! Look! Ollie ___ on the map! (sleep)"
- Door choice: 🕐 NOW · 📅 LATER → correct: **NOW** (clues: "Shhh! Look!")
- Verb options: a) is sleep · b) are sleeping · c) is sleeping ✅
- Correct feedback: "DING! Door 3 OPENS! Ollie IS sleeping NOW — shhh! +1 ⭐"
- Wrong time: "'Look!' means RIGHT NOW! Choose NOW!"
- Wrong verb: "Ollie is one friend → IS + sleepING! Try again!"

### Screen 4.5 — Victory Screen
- Image: Golden Star treasure chest bursting with confetti; Ollie awake and celebrating.
- Ollie says: "HOO HOO! You did it! You are a PRESENT CONTINUOUS HERO! 🏆"
- Badge unlocked: "⭐ Present Continuous Explorer ⭐"
- Recap chips:
  - "NOW = is/are + verb-ing → it is happening NOW!"
  - "LATER = is/are + verb-ing → our plan for tomorrow!"
- Button: "▶ PLAY AGAIN!"

---

## ANSWER KEY (Teacher/Admin Panel)

- Stage 1: B (map) · A (trees and stars)
- Stage 2: is · are · are
- Stage 3 sorting: NOW, NOW, NOW, LATER, LATER, LATER
- Stage 4: Door 1 = NOW + is singing · Door 2 = LATER + are walking · Door 3 = NOW + is sleeping

### v2 content expansion (+30 per exercise, implemented in `index.html`)

The screens above are the story-critical first items of each queue. `index.html` now
holds data-driven question banks and the story items above appear verbatim as the
openers; the rest are auto-generated in the same patterns (every item: clue word
glow, friendly retry feedback, star values identical to v1).

- Stage 1 MCQ queue: **32** items (v1's 2 open the queue) — 10⭐ each, max 320⭐
- Stage 2 fill-in queue: **33** items (v1's 3 open the queue) — 15⭐ each, max 495⭐
- Stage 3 sorting: **36** cards in 6 rounds of 6 (v1's 6 open round 1) — 5⭐/card + 30⭐ round bonus, max 210⭐
- Stage 4 doors: **33** scenarios (v1's 3 open the queue) — 1⭐ per door, max 33⭐
- Perfect-run total: **1058⭐** (320 + 495 + 210 + 33)

Rules preserved across all new items: "1 friend → IS, 2+ friends → ARE"; no "I am"
forms; NOW clues (now / Listen! / Look! / Shhh!) glow teal, LATER clues (Tomorrow /
Next week / Soon) glow amber; every retry message names the clue or the count rule.

## Self-Review (run against spec checklist)

- [x] Stage 1: visual MCQ, no grammar, simple image prompt — Screens 1.3–1.4
- [x] Stage 2: three visual prompts, drag-and-drop is/are, "The bird ___ flying." example — Screens 2.2–2.4
- [x] Stage 3: time markers (Tomorrow, Next Week), "Our plan is..." connector, sorting NOW vs. LATER — Screens 3.1–3.3
- [x] Stage 4: "Which Way Do You Go?" path quiz, three unique scenarios, pick time marker + conjugate verb — Screens 4.2–4.4
- [x] Same form (S + is/are + V-ing), meaning driven by context — Magic Word Box 3.2 + recap 4.5
- [x] A1 vocabulary, ~8-word sentences, Turkish glosses — verified per screen
- [x] Energetic/playful/encouraging tone; friendly retry feedback everywhere
- [x] Story transitions naturally: observe NOW (Stage 2) → plan for TOMORROW (Stage 3)
