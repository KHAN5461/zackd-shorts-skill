# AAA Game Cutscene Image Prompting System (Unreal Engine 5.4 / Unity HDRP)

## 1. Aesthetic Target: Stylized 3D Realism
Zack D Films visuals are neither cartoon Pixar nor uncanny hyper-photorealism. They are modeled after **AAA Video Game In-Engine Cutscenes**:
- **Geometry:** Crisp, high-poly stylized game meshes.
- **Shading:** Subsurface scattering on skin, matte roughness on plastics, brushed metal textures, worn concrete.
- **Lighting:** Three-point volumetric lighting, soft ambient occlusion, subtle rim light highlighting silhouettes.
- **Color Grading:** Controlled, slightly desaturated tones with accent focal colors (e.g., hazard orange, surgical cyan, arterial red).

---

## 2. Character Persistence Anchor Formula
To eliminate character distortion across Midjourney v6, Flux.1 Pro, DALL-E 3, and Stable Diffusion XL, construct a persistent character anchor string in Scene 1 and repeat it verbatim in all scenes:

```
[Character Name], a [Age]-year-old [Gender] with [Exact Hairstyle & Hair Color], [Facial Structure / Beard / Eyebrows], wearing [Specific Upper Clothing with Material & Color] and [Specific Lower Clothing].
```

*Example Character Anchor:*
> "Mark, a 28-year-old man with short cropped dark brown hair, light stubble along his jawline, wearing a fitted matte slate-gray zip-up technical jacket with subtle stitch seams and dark charcoal cargo trousers."

---

## 3. Scene Image Prompt Structure (3–5 Lines)

Each prompt must consist of 4 structured components:

```
Line 1 [Subject & Action]: [Character Anchor] [Precise physical action or anatomical cross-section].
Line 2 [Environment & Props]: [Detailed setting description, floor/wall materials, industrial or organic textures, background depth].
Line 3 [Lighting & Atmosphere]: [Directional game lighting, subtle volumetric light rays, light atmospheric fog or micro-dust particles, muted color palette].
Line 4 [Camera & Rendering Specs]: [Camera shot type (Close-up / 35mm medium shot / Cross-section cutaway / Low angle), Unreal Engine 5.4 render, AAA game cutscene style, subtle depth of field, 8k octane detail, volumetric shading].
```

---

## 4. Visual Consistency Rules
1. **Never switch character outfits** midway through a script unless explicitly required by the narrative.
2. **Lock camera aesthetic:** Always maintain the same video game engine render quality across all 10 scenes.
3. **Cross-Sections & Cutaways:** For biological or mechanical internals, specify clear 3D anatomical cutaways with glowing energy or fluid flow indicators.
