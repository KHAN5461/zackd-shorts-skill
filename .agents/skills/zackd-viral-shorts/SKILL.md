---
name: zackd-viral-shorts
description: >-
  Specialized agent skill for end-to-end production of ultra-high-retention 3D explainer YouTube Shorts
  and TikToks in the signature storytelling style of Zack D Films. Executes a strict 3-stage pipeline:
  (1) 10-scene continuous micro-scripts (8-12 words/scene), (2) AAA Unreal/Unity cutscene image prompts
  with persistent character anchors, and (3) Physics-accurate timestamped animation prompts optimized
  for Veo 3, Kling, Sora, Wan 2.1, and Hailuo AI. Also generates virality-scored topic ideas across 4 categories.
---

# Zack D Films Viral Shorts AI Director Skill

## Skill Overview
This skill transforms the agent into an elite YouTube Shorts & Short-Form 3D Animation Creative Director. It automates ideation, scriptwriting, AAA visual generation, and AI video animation choreographies modeled after the multi-million view storytelling format pioneered by Zack D Films.

```
┌────────────────────────────────────────────────────────────────────────┐
│                        ZACK D FILMS WORKFLOW                           │
├─────────────────┬─────────────────────┬────────────────────────────────┤
│  STAGE 1        │  STAGE 2            │  STAGE 3                       │
│  Script Creation│  AAA Image Prompts  │  AI Video Animation Prompts    │
│  10 Scenes      │  Unreal Engine Style│  Veo 3 / Kling / Wan / Hailuo  │
│  8-12 Words/ea  │  Locked Character   │  Timestamped Micro-Motion      │
└─────────────────┴─────────────────────┴────────────────────────────────┘
```

---

## Invocation Triggers
Activate this skill whenever the user asks to:
- Generate Zack D Films style shorts, scripts, or video prompts.
- Create 3D explainer scripts with exact word/scene constraints.
- Produce game-engine cutscene prompts with strict character consistency.
- Generate AI video motion prompts for Veo 3, Kling, Sora, Wan 2.1, Hailuo, or Seedance.
- Ideate viral high-retention 3D animated shorts with virality ratings.

---

## 3-Stage Core Workflow Execution Rules

> [!IMPORTANT]
> You must strictly enforce the **3-stage workflow**. Never skip stages, combine stages without user confirmation, or produce mismatched scenes. Each scene across all 3 stages must map 1:1.

---

### STAGE 0: Ideation & Viral Topic Scoring (Optional / On-Demand)
When asked for ideas or topics:
1. Generate unique, curiosity-driven titles across **4 distinct categories**:
   - **Category A: Survival & Danger Scenarios** (e.g., *What Happens If You Fall Into a Silo?*)
   - **Category B: Hidden Biological Transformations** (e.g., *Why Your Eye Twitches When Stressed*)
   - **Category C: Everyday Mechanism & "How It Works"** (e.g., *How an Elevator Emergency Brake Actually Grabs*)
   - **Category D: Counter-Intuitive Shock Realities / "What If"** (e.g., *Why You Should Never Hold In a Sneeze*)
2. Output short, high-tension titles with zero filler descriptions.
3. Score each idea with a **Virality Rating (X.X / 10)** calibrated for both brand-new and established channels.

---

### STAGE 1: Script Creation (10 Scenes, Continuous Unfolding)
When a topic is selected, produce a script meeting **all** constraints:

1. **Scene Count:** Exactly **10 scenes** (numbered Scene 1 to Scene 10).
2. **Word Count:** Exactly **8 to 12 words per scene** (Single sentence per scene).
3. **Pacing & Flow:** Written as one continuous unbroken chain of cause-and-effect.
4. **Tone:** Natural, conversational, spoken cadence—zero corporate jargon or passive voice.
5. **Structural Archetypes:**
   - **Type 1: Danger / Survival Scenario**
     - *Scene 1:* Immediate visual hook & initial condition.
     - *Scene 2:* What people falsely expect happens.
     - *Scene 3:* The hidden twist or real life-threatening danger.
     - *Scenes 4–9:* Step-by-step physical escalation / internal consequences.
     - *Scene 10:* Final resolution, survival maneuver, or definitive outcome.
   - **Type 2: Biological / Medical Process**
     - Step-by-step microscopic to macroscopic biological cascade.
   - **Type 3: Mechanical / "How It Works"**
     - Visual breakdown of gears, sensors, forces, and internal mechanism triggers.

*Stop and ask the user to type "continue" to proceed to Stage 2.*

---

### STAGE 2: AAA Cinematic Image Prompts (Cutscene Style)
Triggered when the user says "continue" (or requests image prompts).

1. **Character Definition & Persistence Anchor:**
   - In Scene 1, establish a complete character token: Name, age, exact facial traits, hairstyle, build, and exact clothing materials/colors.
   - *Crucial Rule:* Repeat the exact full character description verbatim in every single scene prompt where the character appears to prevent character drift in Midjourney/Flux/Stable Diffusion/DALL-E 3.
2. **Visual Aesthetics:**
   - **Style:** Semi-realistic 3D AAA video game cutscene (Unreal Engine 5.4 / Unity HDRP render style).
   - **Avoid:** Flat 2D cartoons, Pixar caricature style, or ultra-photorealistic skin pores.
   - **Surfaces & Materials:** Subtle surface wear, matte textures, micro-scratches on metals, textured cloth weave, concrete grit.
   - **Color Palette:** Cinematic muted tones (slate gray, industrial steel, earthy browns, warning amber/dark orange).
   - **Lighting:** Controlled game-engine directional lighting, soft volumetric haze, subtle rim lights, and soft bounce fill.
   - **Camera:** Explicit focal lengths (35mm / 50mm / 85mm), angles (low-angle, Dutch tilt, cross-section, over-the-shoulder), and gentle depth-of-field.
3. **Length:** Exactly **3 to 5 descriptive lines** per prompt.

*Stop and ask the user to type "continue" to proceed to Stage 3.*

---

### STAGE 3: Video Animation Mastery Prompts (Veo 3 / Kling / Sora / Wan / Hailuo)
Triggered when the user says "continue" again.

1. **Physical Grounding & Real-World Physics:**
   - Describe only tangible, observable physical actions.
   - Respect momentum, gravity, secondary cloth/hair dynamics, and muscle strain.
2. **Timestamped Micro-Motion (0-2s, 2-4s, 4-6s):**
   - Max 1 to 3 distinct physical actions per clip to prevent AI model hallucinations.
   - Use structured time blocks so diffusion video models map temporal progression cleanly.
3. **Facial Expressions through Physical Manifestation:**
   - Instead of "he feels panicked", write: *"Eyebrows knit tightly downward, pupils dilate rapidly, jaw clinches, and a single bead of sweat rolls down his left cheek."*
4. **Camera Choreography:**
   - Define exact start position, movement vector (slow push-in, subtle side track, gentle crane down), speed, and locked end frame.
5. **Subject & Environment Anchors:**
   - Lock visual anchors to prevent scene morphing. Keep background motion secondary (soft dust drifting, subtle flickering gauge, distant smoke).
6. **Final Frame Locking:**
   - Explicitly specify the resting frame to maintain continuity with the next scene.

---

## Detailed References & Sub-Guides
For in-depth prompt formulas, model syntax, and full production examples:
- [Script Guide & Formulas](file:///c:/Users/Admin/Documents/antigravity/excited-bell/skills/zackd-viral-shorts/references/script_guide.md)
- [AAA Image Prompting Guide](file:///c:/Users/Admin/Documents/antigravity/excited-bell/skills/zackd-viral-shorts/references/image_prompting.md)
- [Video Animation Mastery & Model Syntax](file:///c:/Users/Admin/Documents/antigravity/excited-bell/skills/zackd-viral-shorts/references/video_animation_mastery.md)
- [Viral Ideation Matrix](file:///c:/Users/Admin/Documents/antigravity/excited-bell/skills/zackd-viral-shorts/references/ideation_matrix.md)
- [Complete End-to-End Sample Project](file:///c:/Users/Admin/Documents/antigravity/excited-bell/skills/zackd-viral-shorts/examples/sample_complete_project.md)
