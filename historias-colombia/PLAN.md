# "Nico Viaja en el Tiempo": Colombian history reels with Google Flow

A complete plan to make short vertical videos (Reels / TikTok / Shorts) where an AI-generated
Colombian kid, **Nico**, travels back in time and tells history stories in Colombian Spanish.

> **Note on the reference reel:** the Instagram link could not be opened from the session that
> wrote this plan, because Instagram is blocked on its network. The breakdown below describes the common
> "AI kid tells history like a vlog" format. If the original differs (animation style, pacing,
> narrator off-screen and so on), adjust section 1 and keep everything else.

---

## 1. Reverse-engineering the format

How these reels are put together:

| Element | How it works | Why it works |
|---|---|---|
| **Hook (0–2 s)** | Character talks straight to camera: "Hi! I'm in [place, year]…" plus big on-screen text | Viewers stop scrolling when someone talks right at them |
| **Vlog POV** | Selfie-style framing, the kid holds the camera or talks to it, and history happens behind them | Feels like a real video from the past, not a lesson |
| **One clip = one idea** | Each 8-second AI clip carries one sentence of the story | Veo makes 8 s clips, so the story is told in 8 s beats |
| **6–8 clips** | About 45–60 s total | Good length for watch time and replays |
| **Same character every time** | Same face, outfit and voice in every clip and every episode | Builds a recognizable "show", and people follow for the character |
| **A twist or a fun fact at the end** | "And the vase still exists!" plus a question to the viewer | Drives comments and saves |
| **Burned-in captions** | Big, word-by-word subtitles | Most people watch without sound |
| **Signature opener and closer** | Same catchphrase every episode | Branding |

## 2. The character: Nico

Use **exactly the same description in every prompt** (copy the block below). This is the most
important rule for keeping him consistent.

**Default style: stylized 3D animation (Pixar-like).** It looks great, keeps the character more
consistent than photorealism, and avoids the restrictions AI tools often apply to photorealistic
children.

### Character block (paste it at the start of every clip prompt)

```
Stylized 3D animated film style, soft cinematic lighting, vertical 9:16.
NICO: a 10-year-old Colombian boy from Bogotá, warm light-brown skin, big expressive dark-brown
eyes, short curly black hair, small gap-toothed smile. He wears a bright yellow hoodie with thin
blue and red stripes on the cuffs, under his grandmother's gray-and-brown wool ruana (Colombian
poncho), dark jeans and white sneakers. He talks to the camera like a vlogger, energetic and curious.
Voice: young boy, cheerful, Spanish with a Bogotá Colombian accent.
```

**Story device:** "la ruana de mi abuela", his grandmother's magic ruana that sends him to
the past. It's culturally Colombian, gives a reason for the time travel, and is a recognizable visual.

**Catchphrases**
- Opening: *"¡Quiubo, parceros! …"* ("Hey, guys!")
- Closing: *"¿Ustedes sabían esto? ¡Síganme pa' más historias! ¡Chao, parceros!"* ("Did you know
  this? Follow me for more stories! Bye, guys!")
- Kid-friendly Colombian words to use: *parce, bacano, ¡uy, no!, berraco/berraca (brave),
  ¿sí o qué?, qué nota*.

## 3. Google Flow workflow (step by step)

Flow (labs.google/flow) uses Veo for video plus an image model. Veo makes about 8-second clips with
**sound and dialogue**.

### Step 0: Setup (once)
1. Go to **labs.google/flow** and sign in with a Google account on a **Google AI Pro or Ultra**
   plan. Credits are monthly, and Ultra gets more credits and features.
2. Create a project called **"Nico Viaja en el Tiempo"**.
3. Set the aspect ratio to **9:16 (portrait)** if the option is there. If it isn't, generate 16:9 and
   crop to vertical in the editor, keeping Nico centered.

### Step 1: Create Nico's reference image (once)
1. In Flow, generate an **image** with the character block plus: *"full body and close-up character
   sheet, neutral background, front view, smiling"*.
2. Generate several, then **pick the best one and save it**. This is Nico's official face.
   Optionally make one more of him holding a phone like a vlogger.

### Step 2: Generate each clip
Choose the mode that fits your plan:

- **Ingredients to Video** (best for consistency): upload Nico's reference image as an
  ingredient, plus optionally a second ingredient for a recurring historical character such as
  La Pola. Then paste the clip prompt.
- **Frames to Video** (fallback): use Nico's image, or the last frame of the previous clip, as the
  **first frame**, then paste the prompt.
- **Text to Video**: works too, as long as you paste the character block every time.

For each clip:
1. Paste the **character block** plus the **clip prompt** from the script file.
2. Use **Fast/draft mode** first to test cheaply, then regenerate your favorites in **Quality**.
3. Generate 2–4 versions and keep the one with the best lip-sync and face.
4. Keep the Spanish dialogue **short** (about 20 words or fewer per 8 s clip). Longer lines get cut off or rushed.

### Step 3: Assemble
- Add clips in order in **Scenebuilder** inside Flow, or download them all and edit in **CapCut**.
- Download as MP4.

### Prompting rules that make a big difference
- Write the scene in **English** and put the **dialogue in Spanish in quotes**, and say
  *"speaks in Spanish with a Colombian Bogotá accent"*.
- Add **"no subtitles, no on-screen text"**, because AI text comes out garbled. Add real captions in CapCut.
- Add **"no background music"** so every clip sounds the same, then add one music track in the edit.
- Describe **camera** (selfie close-up, handheld), **place**, **time of day** and **sound**
  (crowd, rain, horses).
- Keep historical people consistent by reusing the same short description (for example *"La Pola:
  young mestiza woman, about 22, dark hair in a braid, simple blue colonial dress"*).

## 4. Editing (CapCut, free)

1. Import clips in order, trim dead frames at the start and end of each clip.
2. **Auto captions** → Spanish → big bold style, yellow highlight on the key word, centered
   in the lower third (above the Instagram UI).
3. **On-screen hook text** for the first 2 s, for example **"¿Una guerra por un FLORERO? 🏺"**.
4. Add **one music track** (soft adventure or epic) at low volume (about 10–15%).
5. Add whoosh sound effects on the time-travel cuts.
6. Export **1080×1920, 30 fps**.

## 5. Posting plan

| # | Episode | Suggested date | Why |
|---|---|---|---|
| 1 | La Pola, la espía | **Nov 14, 2026** | Día de la Mujer Colombiana (her execution date) |
| 2 | El Florero de Llorente | the following week | Most famous "funny" story in Colombian history |
| 3 | El Dorado y la Laguna de Guatavita | +1 week | Myth and gold, very visual |
| 4 | La Batalla de Boyacá | +1 week | Epic battle, horses |
| 5 | Blas de Lezo y Cartagena | +1 week | Underdog story with a twist |

- Post **2–3 times per week** once you have a backlog. Consistency matters more than perfection.
- **Instagram:** turn on the **"AI info" label** (Meta requires disclosure for realistic AI video,
  and it builds trust).
- Caption formula: question + 1-line summary + call to action + hashtags. Each script file has one ready.
- Cross-post the same video to **TikTok** and **YouTube Shorts**.
- Pin a comment asking: *"¿Qué historia quieren para el próximo video?"* ("Which story do you want
  next?") Their answers are your next episodes.

## 6. More episode ideas (for later)

- La Gaitana, the Indigenous chief who fought the conquistadors
- Simón Bolívar escapes through the window (Sept 25, 1828, with help from Manuela Sáenz)
- La Expedición Botánica and José Celestino Mutis
- The founding of Bogotá (1538) by Gonzalo Jiménez de Quesada
- San Andrés and the Raizal people
- The history of the vallenato and the Festival de la Leyenda Vallenata
- Ciudad Perdida (Teyuna), older than Machu Picchu
- Benkos Biohó and San Basilio de Palenque, the first free town in the Americas

## 7. Budget and time per episode (rough)

- About **7 clips × 2–4 attempts**, so 15–30 generations per episode. Draft in Fast mode, and use Quality only
  for the final takes.
- Time: about 1–2 h generating plus 30–45 min editing per episode once you get the hang of it.
- Check your remaining Flow credits before each episode. Credit costs per mode change, so see the
  Flow pricing page.

## 8. Accuracy note

The scripts follow the widely taught versions of each story. Where historians debate details
(for example whether the Florero fight was planned, or the "short ladders" at San Felipe), Nico
says *"dicen que…"* ("they say that…"). That is honest, and it invites comments.
