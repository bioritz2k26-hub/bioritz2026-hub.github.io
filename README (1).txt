BIORITZ-2K26 — FINAL ASSET-EMBEDDED FIX

The previous under-20MB build referenced the logo and brochure preview as separate local
image files. On some Android content:// or GitHub upload situations those references
were not resolved, producing broken-image icons.

This build embeds compact WebP copies of:
- BIORITZ logo
- Brochure page 1
- Brochure page 2

directly into index.html. Therefore the logo and brochure preview do not depend on
separate image-file loading.

The visual design, layout, animations, text and functionality are unchanged.
index.html remains below 20 MB.
