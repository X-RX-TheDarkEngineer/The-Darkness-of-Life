# World Bible — Music Card Game

## The City

An urban, dark, overpopulated, Gotham-style, post-apocalyptic, futuristic city.
Large city gates lock the city off from the Dissonance.

The city is extremely small — about the size of the New York City area — because all the refugees and survivors were pushed into it. Instead of building outwards, closer to the Dissonance and the diminished, they built UP: very tall buildings, with bridges linking building to building as a travel network, like the MTA but hand-made and futuristic. AI bots are everywhere, assisting humans with everyday tasks, policing, and the military. The city stands clearly separated from the Dissonance — a wide, empty stretch of dark wasteland lies between the city's high walls and the ruined ground beyond, so the city feels apart from the void, not pressed against it.

## The Portal

Far behind the city, over its high walls and further in the distance, hangs a large black translucent portal orb — the way Organization XIII, Heartless and Nobodies appear through black portals. A large black hand, distorted and bent wrong, pokes out of it. The hand is attached to something hidden inside the portal, watching — a vast unseen watcher trying to fit through the portal but too big to get through, so only its hand can reach out. On the title screen the portal and the entity inside it loom much bigger in the background, and one huge dark hand fills the sky, reaching slightly over the town. In the empty space between the town and X-RX lies a large slain diminishing beast.

## Ultimate weapon — the electric cello

X-RX's ultimate weapon is a minimal, skinny, futuristic electric cello carried on his back. It is as big as, or a little bigger than, his huge sword. It is still clearly recognizable as an electric cello — slim body, long neck, fingerboard, four visible strings, bridge, and a bow — with weapon adjustments: a glowing blue pulse emitter at the body, angular armoured plating, a grip and trigger on the back, a power cell, and an endpin spike at the bottom. When he plays it, it emits a blue pulse — light vibration radiating through sound waves — and that sound is his attack. It is the ultimate form of his starting sound: the cello was his first card (value 5) in character creation. Concept sheet: `assets/cello-weapon-concept.png` (front, back, top, bottom views) — the original electric cello design, scaled up to sword size (Nov 19, 2026). **Approved by Jay, Nov 19, 2026 — the weapon design is locked in, along with the three action images of X-RX using it (`x-rx-playing-cello-weapon.png`, `x-rx-firing-cello-weapon.png`, `x-rx-cello-weapon-ready.png`).**

- **Front:** slim cello body, four glowing strings, bridge, blue pulse emitter at the body.
- **Back:** weapon grip and trigger, power cell, armour plating, shoulder mount for carrying.
- **Top:** string spacing along the fingerboard, neck profile, bow resting across the strings.
- **Bottom:** endpin spike, sound-wave emitter where the blue pulse leaves the body.

## The Dissonance

The void abysmal wasteland beyond the gates. It comes to life with darkness.

## Xado_RemnantX

Also known as Xado, Remnant, RemnantX, RX, and **X-RX** (added Nov 19, 2026).

A retired mercenary of the diminished — lost souls, like Nobodies or Heartless entities — fighting his way out of the darkness. One of the few to survive complete destruction and shattering of his soul, now pieced together and realigned.

He retired after the War of Death: the battle that ended the common world, life before the apocalypse.

He is a lone wolf — a black wolf warrior spirit — and doesn't shift as often anymore. He walks alone after losing his lover, whom he devoted himself to save, until she betrayed him and lost herself in the process.

He is broken and reserved, but strong as his integrity, intellect and resilience shines through him. He IS the light in the darkness.

## The Warrior's Honor

> "We walk the dark, rise. We walk with truth and honor. We tend and earn our place. Though he walks through the valley of the shadow of death, he shall fear no evil, fore evil, is not pure against those worthy of a soul of light."

## Style

Pixel and retro, in the style of Kingdom Hearts: Chain of Memories (GBA).
2D top-down pixel art, tile-based city level, smooth movement with velocity,
acceleration and friction, and tile collision. GBA resolution 240x160, shown
scaled up. Camera follow and idle animation to come later.

## Style Bible — Chain of Memories (from Jay's reference screenshots, Nov 18, 2026)

Saved in `assets/reference/` — five screenshots of Kingdom Hearts: Chain of Memories (GBA, 2004). **Jay, Nov 18, 2026: it does NOT have to be exactly the same colours and everything — what matters is the overall playing style, the artistic design, and the storytelling.** So: take CoM's systems and feel, keep OUR colours (the dark city, electric blue #00bfff, deep darks), and make it ours.

- **Playing style (the priority):** three-quarter field exploration with a following camera; enemies wandering the field, touch one to start a battle; card battles with values 0–9 and breaks; deck building; Sleights from three cards; Map Cards that build rooms; floors as reimagined places; Enemy Cards earned from defeated enemies.
- **Artistic design:** detailed pixel art with outlines, shading and shadows (ellipse shadow under feet), patterned floors, wall faces along the top edge, rich saturated colour — but in OUR palette, not a copy of CoM's Traverse Town or Agrabah colours.
- **Storytelling:** dialogue boxes with a speaker portrait and text (cream box in CoM; ours in our own colours), cutscene moments, the creed and the lore carried through the game — the city, the gates, the Dissonance, the War of Death, the diminished, the black wolf.
- **Battle HUD:** HP bars in the top corners with round character portraits; cards along the bottom — large ornate cards with crown-shaped tops, card art in the middle, a number in a circle for the value; the played card shows its art large in the centre of the screen.
- **Battles:** arena with a patterned floor, attack effects as star bursts and light slashes, the Sleight name shown on a banner when three cards fuse.

## Starting sound

Cello — chosen by Jay, Nov 18, 2026, as Xado_RemnantX's starting sound in character creation (Step 3). The cello is his intended primary instrument for a future on-campus music degree. His first card is the Cello card, a low, warm, bowed sound; later cards come from his own instruments — ABYSS drones, GRAVITY bass, STRATA pads.

## How we match Chain of Memories

Jay's question, Nov 18, 2026: how do we make the gameplay and art style match CoM? Answer: copy the systems and the craft, keep our colours and story.

**Gameplay systems, in build order:**
1. Field — three-quarter rooms, camera follow, patterned floors, wall faces, shadows; enemies wandering; treasure chests; doors to the next room.
2. Touch an enemy → battle arena. Real-time movement, attack with a card, cards have values 0–9, higher value breaks the opponent's card, 0 breaks anything but anything breaks a 0, cards reload after use.
3. Deck building — the deck is a list of owned cards; a cost limit keeps it fair; edit it between battles.
4. Sleights — three cards played together fuse into one stronger move (our version: three note cards fuse into a chord/melody phrase) and the first card is lost; the Sleight name shows on a banner.
5. Map Cards — choose a card to create the next room; its value sets the room's size, enemies and treasure.
6. Floors — each floor is one of his songs/instruments reimagined; a story scene and a boss at the end of each floor.
7. Progression — level up, choose more HP, more deck capacity, or a new Sleight; Enemy Cards earned from defeated enemies grant their sound.

**Art style:**
- Detailed pixel sprites with outlines and shading, drawn as pixel maps (letters = colours) or as PNG sprite sheets; 4-frame walk cycles, 2-frame idle bob, ellipse shadow under every character.
- Patterned tile floors, wall faces along the top edge, lamps and lit windows, furniture and props; one palette per area (the city: dark blue and purple with electric-blue light).
- Dialogue boxes with a speaker portrait; ornate cards with crown-shaped tops and values in circles; HP bars with round portraits in the top corners; star-burst and light-slash attack effects.

## How this maps to the game

- The city is the hub: the first level, loaded idle, inside the gates.
- The gates are the boundary: beyond them lies the Dissonance, where the battles happen.
- The diminished are the enemies: lost souls, fought with note cards.
- The black wolf is his warrior spirit: a transformation the player earns, not something he uses often.
- The creed is the game's voice: it belongs on the title screen, under his image.
