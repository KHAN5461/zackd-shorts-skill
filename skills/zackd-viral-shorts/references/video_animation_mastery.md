# AI Video Animation Mastery Guide (Veo 3, Kling, Sora, Wan 2.1, Hailuo)

## 1. The Core AI Video Prompting Framework
AI video diffusion models (Google Veo 3, Kuaishou Kling 1.5/2.0, OpenAI Sora, Wan 2.1, and Minimax Hailuo) fail when prompts contain too many competing movements or abstract emotional words. 

This guide enforces **Micro-Movement Choreography, Strict Timestamps, and Camera Physics**.

---

## 2. Universal Video Animation Prompt Formula

Each animation prompt is formatted as a single cohesive, high-clarity paragraph containing:
1. **Initial Camera Framing & Subject Anchor**
2. **Phase 1 Motion (0–2s):** Primary micro-action and physical reaction.
3. **Phase 2 Motion (2–4s):** Secondary interaction, fluid/particle motion, or mechanical shift.
4. **Phase 3 Motion (4–6s):** Escalation, facial micro-expression, and movement settling.
5. **Final Frame Lock:** Locked resting angle and camera resting position.

---

## 3. Standard Animation Prompt Template

```
[Camera starting position and shot type]. At 0–2 seconds, [Subject Anchor] performs [simple micro-motion 1], while [subtle natural physics such as fabric shift or hair sway] responds naturally to momentum. Between 2–4 seconds, [secondary motion or environmental effect such as drifting dust/steam/fluid flow] progresses smoothly across the frame as [facial micro-expression manifests physically with widening eyes / clenched jaw]. From 4–6 seconds, the camera [controlled cinematic move: slow push-in / side pan / crane down] while [action concludes into steady state]. The scene concludes in a locked, stable [final camera framing] with [subject / object state] remaining perfectly clear in the final frame.
```

---

## 4. Translating Emotion into Physical Animation Tokens
Never use abstract emotions. Map internal feelings directly into physical render tokens:

| Abstract Concept | Physical Animation Token |
| :--- | :--- |
| **Panic / Fear** | *Eyebrows contract sharply downward, pupils rapidly dilate, breath becomes shallow with rapid chest rise, and head jerks slightly to the left.* |
| **Pain / Strain** | *Teeth clench visibly behind parted lips, neck tendons pull taut, eyes squint tightly, and shoulders stiffen upwards.* |
| **Shock / Surprise** | *Jaw drops slightly, eyelids retract showing sclera, hands freeze mid-motion, and body recoils backward two inches.* |
| **Focus / Determination**| *Gaze locks firmly forward, blinking ceases, jaw sets firmly, and torso leans subtly forward with steady controlled breathing.* |

---

## 5. Model-Specific Optimization Cheat Sheet

### Google Veo 3 & Sora
- Excels at complex physical dynamics and fluid physics.
- Specify exact lens focal lengths (e.g., `Shot on 35mm lens, f/2.8, slow forward dolly`).
- Keep light bounce and environmental volumetric lighting explicitly described.

### Kling AI (v1.5 / v2.0)
- Superb character motion fidelity.
- Use `Camera movement: Pan Left / Push In (Speed: 3/10)` or descriptive motion blocks.
- Keep background static or very slowly drifting to avoid character morphing.

### Wan 2.1 & Minimax Hailuo AI
- Extremely responsive to realistic human movement and realistic pacing.
- Use clean chronological sentences without jargon.
- Explicitly emphasize consistent character clothing and hair textures throughout.
