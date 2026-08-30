# Artwork provenance

## Mask & Moonlight

- File: `backgrounds/01-mask-and-moonlight.webp`
- Preview: `preview.png`
- Copyright: © 2026 Patrizio Rullo
- License: [Creative Commons Attribution 4.0 International](./LICENSES/CC-BY-4.0.txt)
- Created with: OpenAI's built-in image generation tool
- Visual reference: the Baziu illustration from the MIT-licensed
  [Bazilion repository](https://github.com/rullopat/bazilion)
- Post-processing: resized from 1672×941 to 3840×2160 with Lanczos resampling
  and encoded as high-quality WebP; the PNG preview is derived from that file

The artwork is a stylized tribute based on Baziu's established illustrated
identity. It was created before photographic references were supplied and is
not presented as a photo-accurate portrait.

### Generation brief

```text
Use case: stylized-concept
Asset type: 16:9 Omarchy desktop wallpaper, intended for a polished 3840 x 2160 final asset
Primary request: Create a quiet, elegant memorial wallpaper inspired by Baziu, the beloved Neva Masquerade cat represented in Image 1. This is a celebration of his presence, warm and peaceful rather than sad.
Input images: Image 1 is the subject and visual-identity reference; preserve the recognizable fluffy cream coat, deep chocolate face mask, ears and paws, and luminous sapphire-blue eyes, while adapting the composition into a wide wallpaper.
Scene/backdrop: a minimal twilight interior suggested with broad abstract shapes and a softly glowing window-like sapphire oval, on a deep warm chocolate background with subtle cream paper grain. Keep the environment restrained.
Subject: Baziu resting calmly in the lower-right third, seen in a graceful three-quarter pose, fluffy silhouette and one front paw visible, looking gently toward the viewer.
Style/medium: sophisticated editorial gouache and softly layered digital illustration; tactile paper texture; clean large shapes; refined, timeless, slightly dreamlike; aligned with the existing Bazilion identity, not photorealistic and not childish.
Composition/framing: true wide landscape 16:9; generous calm negative space across the left and center; no important details along the top edge where a desktop bar sits; balanced for cropping on common desktop displays.
Lighting/mood: low, warm, serene evening light with a subtle sapphire glow in the eyes; affectionate, comforting, quietly luminous.
Color palette: deep chocolate #211810 and #1A140F, warm cream #F5F0E8, ivory #FAF8F4, mocha #7A6555, sapphire #4A7C9B and #6BA3C2, one very restrained dusty-rose #C4878A accent.
Materials/textures: fine paper grain, soft gouache edges, gentle tonal depth.
Constraints: no text, no logos, no watermark; no halo, wings, rainbow bridge, gravestone, or overt mourning symbols; only one cat; avoid clutter; preserve strong desktop readability and negative space.
```

## Sapphire Gaze

- File: `backgrounds/02-sapphire-gaze.webp`
- Copyright: © 2026 Patrizio Rullo
- License: [Creative Commons Attribution 4.0 International](./LICENSES/CC-BY-4.0.txt)
- Created with: OpenAI's built-in image generation tool
- Visual reference: a private photograph of Baziu supplied by Patrizio Rullo;
  the original photograph is not included in this repository
- Style reference: `backgrounds/01-mask-and-moonlight.webp`
- Post-processing: resized from 1672×941 to 3840×2160 with Lanczos resampling
  and encoded as high-quality WebP

The private photograph was used only to preserve Baziu's identity, upright
pose, and expression. The photographed room and all of its objects were
deliberately excluded; the dawn landscape is entirely invented.

### Generation brief

```text
Use case: stylized-concept
Asset type: companion 16:9 Omarchy desktop wallpaper, intended for a polished 3840 x 2160 final asset
Primary request: Create “Sapphire Gaze,” a warm first-light companion to “Mask & Moonlight,” centered on the real Baziu shown in Image 1.

Input images:
- Image 1 is the subject identity and pose reference only, not an edit target. Preserve Baziu’s distinctive physical traits and expression, but do not reproduce the photographed room or any of its objects.
- Image 2 is the style, finish, and palette reference only. Match its refined editorial-gouache language without copying its pose, setting, oval window, plant, or other objects.

Scene/backdrop: an entirely invented minimal dawn field made from broad abstract parchment, muted dusty rose, smoky sapphire, mocha, and deep cocoa shapes, with a subtle low horizon and fine paper grain. Keep the field sufficiently dark and quiet for a dark desktop theme.

Subject: Baziu seated upright in the lower-left third, front-facing with both dark paws close together and gaze slightly upward. Faithfully preserve his long warm-ivory coat, very full cream chest ruff, deep seal-brown near-black face mask, ears, forelegs and paws, tall triangular slightly tufted ears, small dark nose, broad fan of long fine white whiskers, and huge round widely spaced eyes with pale sapphire rims around naturally dilated dark pupils and clean catchlights. His expression is gentle, trusting, alert, and slightly expectant. Keep his slim upright proportions; do not turn him into a rounded or reclining cat.

Style and medium: sophisticated editorial gouache with softly layered digital paint, tactile paper texture, timeless and restrained, affectionate but unsentimental. Stay consistent with Image 2 while making this scene brighter and more open. Not photorealistic, not childish, not chibi.

Composition and framing: true wide 16:9. Keep Baziu fully inside the lower-left third with both ears and every whisker safely uncropped. Preserve quiet, low-detail negative space across the right two-thirds and top edge for desktop icons and windows. Desktop-friendly crop with a clear silhouette at thumbnail size.

Lighting and mood: warm first-light glow on the cream ruff with subtle smoky-sapphire reflections in the eyes. Peaceful and alive, celebratory rather than mournful.

Color palette: deep chocolate #1A140F and #211810, mocha #7A6555, cream #F5F0E8, ivory #FAF8F4, smoky sapphire #4A7C9B and #7BB4D2, restrained dusty rose #C4878A and #D89A9D.

Constraints: exactly one cat; no text, logo, signature, or watermark; no kitchen, bowls, food, cabinets, floorboards, bags, packages, labels, or any identifiable/private room detail; no oval window, plant, or copied object from Image 2; no halo, wings, rainbow bridge, gravestone, or overt mourning symbol; do not exaggerate the eyes beyond Image 1 or make them neon, anime-styled, crossed, or asymmetrical.
```

## Adding future photo-based backgrounds

For a private local background, place the image under
`~/.config/omarchy/backgrounds/baziu/`; it does not need to be published.

For a background intended for this public repository:

1. Confirm that you own the photograph and choose its license explicitly.
2. Use a 16:9 crop at 3840×2160 when possible.
3. Name it `backgrounds/NN-short-title.ext` so Omarchy's lexical ordering is
   predictable.
4. Add its source, changes, copyright holder, and license to this file.
5. Refresh `preview.png` only when changing the theme's primary preview.
