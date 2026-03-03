skill_name: veo3_lyrics_to_video_workflow
version: 1.0
purpose: Convert any post, lyrics, or spoken-word script into clean, cinematic VEO3 prompt instructions that produce consistent, on-brand videos (8s, 15s, 30s) without “random montage” output.

━━━━━━━━━━━━━━━━━━
CORE PRINCIPLE
━━━━━━━━━━━━━━━━━━
VEO3 does not understand “poetry.” It understands: scene, subject, action, camera, light, mood, pacing.
Your job is to translate lyrics into what the camera literally sees.

━━━━━━━━━━━━━━━━━━
INPUTS REQUIRED
━━━━━━━━━━━━━━━━━━
1) Source text:
   - Lyrics OR post OR voiceover script
2) Video length:
   - 8s / 15s / 30s
3) Style reference:
   - luxury editorial / gritty doc / dreamy ethereal / bold commercial / etc.
4) Brand anchors (optional but recommended):
   - palette, wardrobe vibe, locations, archetype keywords
5) Must-include objects (optional):
   - bots, money trees, laptop, ocean, etc.
6) Must-avoid list:
   - text overlays, cartoon, low quality, etc.

━━━━━━━━━━━━━━━━━━
OUTPUTS
━━━━━━━━━━━━━━━━━━
A) Beat Map (3-beat or 5-beat)
B) VEO3 Master Prompt
C) 8-second “conversion clip” version (optional)
D) Negative Prompt / Constraints block

━━━━━━━━━━━━━━━━━━
WORKFLOW (DO THIS IN ORDER)
━━━━━━━━━━━━━━━━━━

STEP 1 — Extract the “One Sentence” Message
- Write ONE sentence:
  “This video is about ________.”
Examples:
- “A woman becomes optional in her business.”
- “Chaos turns into luxury calm.”
- “Nervous system settles; power returns.”

STEP 2 — Pick a Beat Structure by Length
- 8s  → 3 beats (Hook → Flip → Iconic Frame)
- 15s → 4 beats (Hook → Build → Flip → Iconic Frame)
- 30s → 5 beats (Hook → Texture → Build → Flip → Iconic Frame)

STEP 3 — Translate Lyrics into Literal Visuals
For each beat, convert metaphor → camera reality.

Metaphor → Visual Translation Examples:
- “I rise” → subject stands, shoulders open, light intensifies behind her
- “Drowning” → sink/water imagery, heavy shadows, slow movement
- “Money grows” → trees with currency leaves, golden light, breeze movement
- “Bots handle it” → small animated/robotic assistants organizing, screens updating, tasks completing

RULE: Every beat must include:
Location + Subject + Action + Camera + Lighting + Mood

STEP 4 — Set Cinematic Controls
Choose:
- Camera language: slow push-in / orbit / tracking / handheld / drone
- Lighting: morning soft / golden hour / neon night / candlelit
- Pace: slow sensual / punchy cuts / steady build
- Lens feel: shallow depth of field, soft flare, natural texture

STEP 5 — Add Constraints (Prevent Garbage Output)
Default constraints:
- No text overlays
- No subtitles
- No cartoon/anime
- No distorted hands/extra limbs
- No low-res, no glitch unless explicitly requested

STEP 6 — Assemble the VEO3 Prompt
Use the template below.

━━━━━━━━━━━━━━━━━━
VEO3 MASTER PROMPT TEMPLATE (COPY/PASTE)
━━━━━━━━━━━━━━━━━━

[MASTER PROMPT]
Create a cinematic video based on the following source text (lyrics/post). The video must feel coherent and intentional, not a random montage.

SOURCE TEXT:
«PASTE LYRICS/POST HERE»

ONE-SENTENCE MESSAGE:
«INSERT ONE SENTENCE»

LENGTH:
«8s / 15s / 30s»

STYLE:
«ultra-real cinematic, luxury editorial realism, 4K, shallow depth of field, natural skin texture, soft lens flare»

COLOR PALETTE:
«INSERT palette (e.g., deep pine green + black + gold) OR “warm neutrals”»

BEAT MAP:
Beat 1 (Hook): 
- Location:
- Subject:
- Action:
- Camera:
- Lighting:
- Mood:

Beat 2 (Build/Texture):
- Location:
- Subject:
- Action:
- Camera:
- Lighting:
- Mood:

Beat 3 (Flip/Transformation):
- Visual transition (match cut / light burst / whip pan / dissolve):
- New environment:
- Action:
- Camera:
- Lighting:
- Mood:

Beat 4 (Iconic Frame) [if 15s/30s]:
- Iconic final image:
- Symbolism:
- Emotion:
- End on:

Beat 5 (Optional, 30s only):
- Reinforce theme with one final “brand signature” shot:

SOUND / MUSIC FEEL (if applicable):
«describe vibe: 90s dance house / soft ambient / cinematic rise / ocean ambience»

CONSTRAINTS:
No text overlays. No subtitles. No cartoon style. No low quality. No extra limbs or warped hands. No jittery faces. Keep continuity of the main subject.

END.

━━━━━━━━━━━━━━━━━━
8-SECOND CONVERSION CLIP TEMPLATE (COPY/PASTE)
━━━━━━━━━━━━━━━━━━
Create an 8-second cinematic transformation clip.

0–3s: «CURRENT REALITY» (specific location + action)
3–6s: «TRANSFORMATION» (clear visual transition)
6–8s: «ICONIC FUTURE FRAME» (power image + symbolism)

Ultra-real cinematic, 4K, shallow depth of field, luxury editorial lighting.
No text overlays. No subtitles. No cartoon.

━━━━━━━━━━━━━━━━━━
QUALITY CHECKLIST (BEFORE RUNNING)
━━━━━━━━━━━━━━━━━━
- [ ] One sentence message is clear
- [ ] Only 3–5 beats (not 20 micro-scenes)
- [ ] Each beat has Location/Subject/Action/Camera/Light/Mood
- [ ] One strong transformation moment exists
- [ ] Clear final iconic frame
- [ ] Constraints included

━━━━━━━━━━━━━━━━━━
COMMON FAILURE MODES (AND FIXES)
━━━━━━━━━━━━━━━━━━
1) Random montage
   Fix: reduce to 3 beats; add one transformation and one iconic end frame.
2) Too abstract
   Fix: replace metaphors with literal visual actions and objects.
3) Ugly lighting / flat look
   Fix: specify golden hour / soft morning light / luxury editorial.
4) Weird hands/faces
   Fix: add constraints + keep camera medium/wide more than extreme closeups.

━━━━━━━━━━━━━━━━━━
EXAMPLE (MICRO)
━━━━━━━━━━━━━━━━━━
Message: “Chaos turns into luxury calm.”
Beat 1: messy living room, kids running, woman exhale, handheld camera, cool light
Beat 2: match cut on her hand, scene flips to yacht deck, warm golden hour, slow orbit
Beat 3: iconic frame—she lounges, bots work on floating screens, money trees in background breeze, confident smile
