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

## Generation brief

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
