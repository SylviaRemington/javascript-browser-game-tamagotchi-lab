## 🎮 Game Overview — “Glitzarella” (Working Title)
### This is a magical, browser-based drag-pet game where you care for a fabulous drag queen creature. Instead of food, you feed it glitter. Instead of health, you manage sparkle, mood, and energy. You interact with the pet through mini actions like dancing, mirror talk, makeup touch-ups, or dramatic rest.

### As the pet’s moods shift — based on how much you care for it — its appearance, behavior, and sparkle level change.

### The goal is not to win, but to keep your pet fabulous, emotionally nourished, and stage-ready… unless it has a meltdown. In that case? Reapply mascara, feed it some glitter, and try again.

<hr>

## 🧠 Pseudocode 

### When the game starts:

- Show your drag pet on screen

- Ask the player to name their pet

- Show three stats: Mood, Sparkle, Energy

### Player can take actions:

- Feed glitter → raises Sparkle

- Dance → raises Mood, lowers Energy

- Rest → raises Energy, resets Mood

- Mirror check → shows emotional state message

- Do makeup → boosts Mood + appearance

### Behind the scenes:

- If Mood or Energy drops too low → makeup starts to fade, dance fails, pet sighs dramatically

- If Sparkle is full → unlocks new outfits, special disco ball dance mode

- If player ignores the pet:
Stats drop slowly

- Pet starts getting shady, weepy, or dramatically silent

- Eventually: “Emotional Overload” meltdown (optional reset moment)
<br/>
<hr>
<br/>
## 🎭 Game Flow Script (Player Experience)
### 1. Welcome Screen:
✨ “Meet your new drag pet. She’s dramatic, divine, and needs constant sparkle.”
🎤 Button: Start the Glam

### 2. Name Your Pet:
Input: “What’s her name?”
(Glitter sparkles around the name box)

### 3. Main Game Screen:

- Pet appears on a stage or in a dressing room

- Stats shown as glowing bars or hearts

- Buttons: [Feed Glitter] [Dance] [Rest] [Do Makeup] [Mirror Check]

### 4. Player interacts → Pet reacts in real time:

- “Oooh yes, feed me that shimmer, baby!”

- “Low energy… Can’t… Sparkle…”

- “Not me melting down mid-slay…”

### 5. Game loops continuously:

- Time passes → stats slowly decay

- Player keeps interacting → pet stays fabulous

<hr>

## 🎨 Visual Mockup Descriptions (No images — just the ideas)
### Main Screen:
Background: a glowing pastel dressing room OR stage with floating disco lights

Drag pet in center: changes facial expression + makeup based on mood

Floating glitter bar, energy bar, and mood meter — very colorful, animated

Buttons: styled like makeup compacts or spotlight switches

Mini-Actions:
Feeding glitter: animation of sparkles going into the pet’s mouth

Dancing: pet spins, vogue hands, sparkly trail follows

Makeup: pet’s face goes from smudged to flawless

Mirror: pet looks into mirror and says a dramatic one-liner based on mood

<hr>

## 💅 Character Emotional States (No clinical labels — just fabulous moods)
Mood	Appearance	Pet Behavior
Radiant	Full glam, sparkles, glowing	“Who wants a show?” 💃 Spins, smiles
Low Energy	Sparkle dimmed, bags under eyes	“Can I lie down in glitter?” 😩
Sad	Makeup running, lashes drooping	“Don’t look at me unless you brought snacks.”
Fierce	Costume glows, eyes flash	“Who said I’m too much? Name them.”
Meltdown	Wig crooked, glitter explosion	“I can’t sparkle for everyone, okay?!” 😭
Recovering	Soft glow returns, soft blush	“Thank you for seeing me… Now more glitter please.”

