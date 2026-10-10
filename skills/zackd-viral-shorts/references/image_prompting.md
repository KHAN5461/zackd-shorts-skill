# The Exact Zack D Films 3D Visual Prompting Blueprint

## 1. The Signature Zack D Visual Aesthetic
Zack D Films does **not** look like a dark, gritty AAA military game or cartoon caricature. The signature look is a **clean, stylized 3D medical/forensic simulation** rendered in Blender, Maya, or Unreal Engine with:
- **Clean Stylized 3D Character:** Smooth, matte-shaded human character model with clean features, clear expressive eyes, and natural proportions.
- **Translucent X-Ray Cutaways:** The character's outer skin becomes semi-transparent or reveals a cutaway section showing vibrant, color-coded 3D internal anatomy.
- **Color-Coded Anatomical Systems:**
  - Lungs & Air passages: Translucent pastel pink and glowing cyan airflow.
  - Circulatory System: Glowing crimson blood vessels with visible floating blood cells.
  - Nervous System: High-contrast glowing yellow/gold nerve fibers.
  - Bones & Joints: Clean ivory 3D skeleton model.
  - Pressure & Vectors: Glowing red and bright yellow 3D arrows showing forces, air blasts, or friction.
- **Pristine Studio Environment:** Clean minimalist studio setting with a light neutral gray or soft gradient infinity backdrop, soft three-point studio lighting, and subtle ground contact shadows. Zero film grain, zero grimy grunge.

---

## 2. Universal Zack D Character Anchor Token

To guarantee character consistency across Midjourney v6, Flux.1, Grok AI, and DALL-E 3, define the character token in Scene 1 and repeat it verbatim across all scenes:

```
[Character Name], a stylized 3D rendered young man with clean short dark hair, smooth matte clay-shaded skin, expressive features, wearing a solid [Color] crewneck casual t-shirt and dark gray fitted trousers, Zack D Films 3D explainer style.
```

*Default Example Anchor:*
> "Alex, a stylized 3D rendered 25-year-old man with clean short dark brown hair, smooth matte clay-shaded skin, expressive features, wearing a solid royal blue crewneck casual t-shirt and dark gray fitted trousers, Zack D Films 3D explainer style."

---

## 3. The 4-Line Zack D Image Prompt Structure

Each scene prompt must strictly follow this 4-line formula:

```
Line 1 [Character & Visible Action]: [Character Anchor] standing in a neutral posture, [specific external physical action e.g., pinching his nose and mouth tightly shut to hold in a sneeze].
Line 2 [X-Ray / Internal Cutaway]: [Translucent cross-section cutaway showing internal 3D anatomy, glowing airway passages, red force vectors, or detailed bone/organ simulation].
Line 3 [Lighting & Studio Backdrop]: Clean minimalist 3D studio background, soft neutral gray studio infinity cyclorama, soft studio key light, gentle rim lighting highlighting character silhouette, crisp ground contact shadow.
Line 4 [Rendering Engine & Style Tokens]: Stylized 3D explainer animation render, clean Blender Cycles 3D simulation, medical cross-section illustration, pristine smooth surfaces, vibrant color-coded internal anatomy, 8k render, no film grain, Zack D Films aesthetic.
```

---

## 4. Prompt Examples: Anatomy & Cutaways

### External Physical Setup:
> "Alex, a stylized 3D rendered 25-year-old man with clean short dark brown hair, smooth matte clay-shaded skin, expressive features, wearing a solid royal blue crewneck casual t-shirt and dark gray fitted trousers, Zack D Films 3D explainer style, seen from the chest up with fingers pinching his nose and mouth closed in panic. Clean minimalist studio background with soft neutral gray lighting. Stylized 3D explainer animation render, clean Blender Cycles simulation, pristine smooth textures, crisp lighting."

### Translucent X-Ray Cutaway:
> "Alex, a stylized 3D rendered 25-year-old man with clean short dark brown hair, smooth matte clay-shaded skin, expressive features, wearing a solid royal blue crewneck casual t-shirt and dark gray fitted trousers, Zack D Films 3D explainer style, with his head and neck rendered in a semi-transparent cross-section. Translucent skin reveals glowing cyan air pressure rushing upward into the pink Eustachian tubes with glowing red stress vectors highlighting the delicate eardrum. Clean light gray studio backdrop, medical 3D simulation render, high clarity, vibrant anatomical colors, Zack D Films aesthetic."
