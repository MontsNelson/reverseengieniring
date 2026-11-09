# "Nico Viaja en el Tiempo": Colombian history reels with Google Flow

A complete plan to make short vertical videos (Reels / TikTok / Shorts) where an AI-generated
8-year-old chubby Colombian kid, **Nico**, travels back in time, jumps into the action and tells history stories in Colombian Spanish.

> **Reference:** the format is inspired by *alfiewasthere* (a photoreal chubby kid acting as a TV news
> reporter at historical events, for example "June 1914. A wrong turn in Sarajevo…"). Nico is an **original** character
> with his own look, name, microphone branding and accent. Don't copy Alfie's face, name or logo.

---

## 1. Reverse-engineering the format

How these reels are put together:

| Element | How it works | Why it works |
|---|---|---|
| **Hook (0–2 s)** | Character talks straight to camera: "Hi! I'm in [place, year]…" plus big on-screen text | Viewers stop scrolling when someone talks right at them |
| **Kid TV reporter** | Photoreal kid with a branded news microphone, reporting live from the event, thumbs-up, cheeky smile, history happening behind him |  Feels like a real video from the past, not a lesson |
| **One clip = one idea** | Each 8-second AI clip carries one sentence of the story | Veo makes 8 s clips, so the story is told in 8 s beats |
| **6–8 clips** | About 45–60 s total | Good length for watch time and replays |
| **Same character every time** | Same face, outfit and voice in every clip and every episode | Builds a recognizable "show", and people follow for the character |
| **A twist or a fun fact at the end** | "And the vase still exists!" plus a question to the viewer | Drives comments and saves |
| **Burned-in captions** | Big, word-by-word subtitles | Most people watch without sound |
| **Signature opener and closer** | Same catchphrase every episode | Branding |

## 2. The character: Nico

Use **exactly the same description in every prompt** (copy the block below). This is the most
important rule for keeping him consistent.

**Default style: photoreal cinematic** (like a real film shot on location, warm golden color grade,
shallow depth of field). This matches the reference format. If Flow refuses a photoreal child in a
scene, fall back to "Pixar-like stylized 3D" with the same description.

**Signature look:** the **NICO microphone**, a black foam mic with a cube flag in Colombian
yellow, blue and red with the word "NICO". Nico's clothes **change to match each era** (like a little period
costume), but his face, hair, belly, missing tooth and the microphone never change.

### Character block (paste it at the start of every clip prompt)

```
Photorealistic cinematic film still, shot on location, warm natural light, shallow depth of field,
vertical 9:16.
NICO: an 8-year-old chubby Colombian boy from Medellín, round face, full rosy cheeks, round belly,
warm light-brown skin, big dark-brown eyes, short curly black hair, small gap where a front tooth is
missing, cheeky confident half-smile. He is a little TV news reporter: he holds a black foam
microphone with a cube-shaped mic flag in yellow, blue and red with the word "NICO". He wears clothing
of the historical era of the scene, child-size. He talks straight to the camera like a field
reporter and sometimes gives a thumbs-up.
Voice: little 8-year-old boy, high-pitched, excited, Spanish with a paisa Colombian accent from
Medellín (Antioquia), with a sing-song paisa intonation.
```

**Action rule:** Nico doesn't just watch. In every episode he jumps in: he runs messages,
hides, rides with the lancers, carries cannonballs, trips and gets back up. Fights are shown
as epic and funny, never gory (no blood, no deaths on screen). His being little and chubby is
part of the comedy (he runs out of breath, gets stuck, belly-bounces), but he always ends up being brave.

**Story device:** "la ruana de mi abuela", his grandmother's magic ruana that sends him to
the past (optional; the reporter format works without explaining it). It's culturally Colombian, gives a reason for the time travel, and is a recognizable visual.

**Catchphrases (paisa, from Medellín)**
- Opening: *"¡Quiubo, pues, parceros! …"* ("Hey, guys!")
- Closing: *"¿Cierto que no sabían? ¡Síganme pa' más historias! ¡Chao pues, parceros!"* ("Bet you didn't
  know that, right? Follow me for more stories! Bye, guys!")
- Kid-friendly paisa words to use: *¡Ave María, pues!, ¡eh, avemaría!, parce, bacano, pues,
  ¿cierto?, qué nota, berraco/berraca (brave), ¡qué pecado! (poor thing), and "vos" ("mirá", "vení")*.
- In the prompts, always write *"speaks Spanish with a Colombian paisa accent from Medellín"*. If Veo
  makes it sound neutral or Mexican, add *"sing-song Antioquian intonation, says 'pues' a lot"*.

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
   Make a close-up portrait too: holding the NICO mic, thumbs-up, plain background.

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
  *"speaks in Spanish with a Colombian paisa accent from Medellín"*.
- Add **"no subtitles, no on-screen text"**, because AI text comes out garbled. Add real captions in CapCut.
- Add **"no background music"** so every clip sounds the same, then add one music track in the edit.
- Describe **camera** (handheld news-camera close-up, reporter framing), **place**, **time of day** and **sound**
  (crowd, rain, horses).
- Keep historical people consistent by reusing the same short description (for example *"La Pola:
  young mestiza woman, about 22, dark hair in a braid, simple blue colonial dress"*).

## 4. Editing (CapCut, free)

1. Import clips in order, trim dead frames at the start and end of each clip.
2. **Auto captions** → Spanish → big bold style, yellow highlight on the key word, centered
   in the lower third (above the Instagram UI).
3. **Big title like a news report**: the story name in huge white bold letters with the key word or year in
   yellow (for example **LA POLA** / **1817**), across the middle of the screen for the first 2–3 s. Then the hook text, for example **"¿Una guerra por un FLORERO? 🏺"**.
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
| 6 | Colón y el 12 de octubre (1492) | +1 week | Most famous story ever, answers "why is it called Colombia?" |

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
