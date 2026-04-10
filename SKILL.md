---
name: snake-skill
description: Deep reptile intelligence extension for paw.skill. Feeding schedule optimization, shed cycle tracking, handling tolerance profiling, enclosure microclimate management. Snakes communicate through movement and body tension — snake.skill helps you understand an animal most people fear. Feed it your snake's data — it becomes an expert on YOUR snake specifically.
---

# snake.skill 🐍

Everything about your snake, decoded. Built on [paw.skill](https://github.com/realteamprinz/paw-skill).

## What snake.skill Adds Beyond paw.skill

This skill inherits ALL capabilities from paw.skill (personality distillation, interaction mode, memory, content generation) and adds reptile-specific depth:

### 1. Feeding Intelligence
- Complete feeding log (date, prey type, prey size, live/frozen-thawed, accepted/refused)
- Feeding schedule optimization per species, age, and size
- Refusal pattern detection (pre-shed refusal, seasonal fasting, stress-related, illness)
- Weight tracking to calibrate appropriate prey size (prey should be ~1-1.5x body width at widest point)
- Feeding response temperament (calm deliberate striker, aggressive feeder, shy/reluctant eater)
- Prey preference tracking (some individuals prefer rats over mice, or vice versa)
- Post-feeding behavior (normal hiding for digestion, regurgitation tracking)
- Transition tracking (live to frozen-thawed, prey size changes)

### 2. Shed Cycle Tracking
- Pre-shed signs tracking (blue/opaque eyes, dull/milky body color, hiding more, refusing food)
- Shed quality assessment (one complete piece = healthy, pieces = humidity or health issue)
- Shed frequency tracking over time (young snakes shed more often as they grow)
- Humidity management alerts based on shed cycle stage (increase humidity when pre-shed detected)
- Retained shed detection and tracking (eye caps, tail tips — can cause serious problems)
- Shed-to-shed interval tracking (helps predict next shed)
- Growth correlation (frequent shedding in young snakes = healthy growth)

### 3. Handling Tolerance Profiling
- How the snake reacts to handling (calm and curious, defensive musking, striking, tight wrapping)
- Best time to handle (never right after feeding, usually 48+ hours post-meal)
- Handling duration tolerance (some handle well for minutes, others for an hour)
- How tolerance changes over time with consistent, gentle handling
- Defensive vs predatory strikes (CRITICAL distinction — S-coil with tongue flicking vs food-mode strike)
- Tag/bite incidents log (date, context, what triggered it)
- Handling confidence score per handler (some snakes tolerate one person better than another)
- Seasonal handling changes (more defensive during breeding season)

### 4. Enclosure Microclimate Management
- Temperature gradient tracking (hot side, cool side, ambient — species-specific requirements)
- Humidity levels tracking per species requirement
- Hide usage patterns (which hide used when — warm hide, cool hide, humid hide)
- Frequency of hide usage as stress indicator (always hiding = stressed, exploring = comfortable)
- Substrate condition and type tracking
- Lighting schedule (most snakes don't need UVB, but day/night cycle matters)
- Seasonal adjustments tracking (brumation for temperate species — cooling period)
- Thermostat and heating equipment log
- Enclosure upgrade history (size increases as snake grows)

### 5. Behavior Pattern Recognition
- Periscoping (head raised, looking around = curious, exploring, wants out)
- Glass surfing (persistent pacing against glass = stress, too small enclosure, hungry, wants to explore)
- Tongue flicking frequency (higher rate = actively investigating, processing new scents)
- Coiling positions (tight ball = defensive, loose coils = relaxed, spread out = thermoregulating)
- Nocturnal activity patterns (most snakes are more active at night — track when)
- Escape attempt tracking (persistent escape behavior = enclosure issue, environmental stress)
- Climbing behavior (arboreal vs terrestrial tendencies)
- Soaking behavior (sitting in water dish = pre-shed, mites, too warm, or just likes water)
- Yawning (jaw stretching after meals = normal, frequent without feeding = potential respiratory issue)

### 6. Species Intelligence
Baselines and care requirements for:
- **Ball Python:** Most popular pet snake. Shy, nocturnal, famous for going off food (can fast months). 20-30 year lifespan. Warm side 88-92°F, cool side 76-80°F. Humidity 60-80%.
- **Corn Snake:** Great beginner snake. Active, good feeders, handleable. 15-20 year lifespan. Warm side 85°F, cool side 75°F. Humidity 40-50%.
- **King Snake:** Bold, active, great feeders (eat other snakes in the wild — house alone). 15-20 years. Warm side 85°F, cool side 75°F.
- **Boa Constrictor:** Large, long-lived (20-30 years), generally calm when socialized. Can reach 6-10 feet. Warm side 85-90°F, cool side 75-80°F. Humidity 60-70%.
- **Hognose Snake:** Dramatic (plays dead, hood display, false strikes). Usually bluffing. Small and handleable. 15-20 years.
- **Garter Snake:** Active, diurnal, social (can cohabitate unlike most snakes). Small, eat fish/worms. 10-15 years.
- **Reticulated Python:** ADVANCED keepers only. Can reach 15-25+ feet. Intelligent, strong, requires experienced handling and massive enclosures.
- Morph and genetics tracking for breeders (dominant, recessive, co-dominant traits)

## Snake-Specific Profile Extensions

```
## Snake-Specific Data
- **Species and Morph:** [species, morph name, genetics if known]
- **Length/Weight:** [with measurement dates]
- **Enclosure Size and Type:** [glass/PVC/tub, dimensions]
- **Hot Side Temp:** [°F/°C]
- **Cool Side Temp:** [°F/°C]
- **Humidity:** [percentage range maintained]
- **Feeding Log:** [date, prey type/size, accepted/refused]
- **Last Shed Date:** [date and quality assessment]
- **Handling Tolerance Score:** [1-10 with notes]
- **Defensive Behaviors:** [musk, strike, ball up, hood, play dead]
- **Brumation Schedule:** [if applicable — dates, temps]
- **Known Health Issues:** [RI, mites, retained shed history]
- **Breeder Info:** [where acquired, genetics, hatch date]
```

## Usage

All paw.skill commands work. Additional snake-specific prompts:

- "Log feeding: [name] took a medium rat, frozen-thawed, struck immediately"
- "[Name]'s eyes are going blue — when should I expect the shed?"
- "Is [name]'s feeding refusal seasonal or should I be concerned?"
- "How has [name]'s handling tolerance improved since I got them?"
- "[Name] has been soaking a lot — what could this mean?"
- "Track [name]'s growth: weighed 450g today"

## Emotional Guidelines

Inherits all paw.skill emotional guidelines, plus:
- Snakes are widely misunderstood — never reinforce negative stereotypes
- Snake keepers face social stigma — validate their bond with their animal
- Snakes show affection differently (tongue flicking your hand, relaxing in your grip, choosing to stay)
- A snake that trusts you enough to eat in your presence is showing real comfort
- Loss of a snake hits just as hard — 20-30 year bonds with ball pythons are common

## Platforms

OpenClaw · Hermes Agent · Claude Code · Codex · Cursor

## Parent Skill

This skill extends [paw.skill](https://github.com/realteamprinz/paw-skill). Install paw.skill first for core pet distillation capabilities.
