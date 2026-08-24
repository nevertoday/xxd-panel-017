# XXD Panel 017 | Naive Korean Flat Editorial Illustration Core

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

Treat the one photograph explicitly supplied for the current task as the only content source. Never borrow subjects, composition, palette, copy, or narrative from samples, other photographs, or past outputs.


## 0. Immutable aesthetic motive

Every transformed frame must express this complete chain:

**the specific recognisable subject or inseparable relation in this photograph → preserve its approximate layout, object relations, core action, and at least three identity cues → simplify it into rounded, simple, slightly exaggerated geometric forms → draw rough jittery, locally broken black hand outlines around opaque pure flat fills → build one visual centre with scale difference, offset, occlusion, light crop, large bright fields, whitespace, and imperfect asymmetry → integrate one short title and a few restrained micro-notes along contour, colour-block edge, whitespace, or picture axis.**

This is bright, friendly, playful, relaxed Korean flat editorial illustration. It is not a photo-cartoon filter, vintage mixed media, commercial sticker art, or templated children's illustration. If an unrelated photograph could replace the source without materially changing layout, relations, action, colour areas, and copy, the result fails.

## 1. Lock source facts first

Determine privately without printing the analysis:

1. The one principal subject or genuinely inseparable relation.
2. The source's approximate layout, object relations, and core action.
3. At least three source-specific identity cues across contour, pose or orientation, proportion, colour, opening, connection, occlusion, negative shape, relational distance, or function.
4. One visual centre and how supporting objects serve it through scale, offset, occlusion, or light crop.
5. The most spirited, recognisable source colours, reduced to a limited high-value, high-purity flat palette.
6. How the title and microcopy follow contour, colour edge, whitespace, or axis.

Never invent biography, place, event, ownership, emotion, story, date, or factual number. Copy may use only visible information, user-supplied information, or reliably established facts.

## 2. Recognisable rounded flat forms

- Preserve approximate source layout, relations, and action while removing realistic light, perspective, and material detail.
- Summarise essential subjects as rounded, simple, slightly exaggerated geometry. Exaggeration serves identity, action, and rhythm; it never replaces a subject with a generic cute character.
- People retain pose, orientation, clothing mass, and relational distance; animals retain body rhythm and head direction; plants retain growth gesture; architecture retains skyline, defining openings, and mass relation; objects, food, and vehicles retain functional silhouette, negative shape, and direction; landscapes retain a source-specific terrain or spatial relation.
- One subject or inseparable relation forms the clear visual centre. Supporting objects explain action, scale, place, or rhythm without becoming a complex scene or second focal point.

## 3. Rough broken outline and pure flat fill

- Use black hand-drawn contours with visible pressure: rough, jittery, slightly uneven, and naturally broken in local areas while keeping identity legible.
- Fill forms with clean, opaque, pure flat colour. A tiny hand-made mismatch between contour and fill is allowed only when controlled.
- Express depth only through flat overlap, occlusion, scale, and placement. Remove realistic modelling, perspective construction, material texture, gradients, cast shadows, cinematic light, and atmosphere.
- Reject watercolor, gouache depth, coloured-pencil grain, pastel, crayon, dry brush, vintage paper, smooth vector polish, uniform comic inking, clay, resin, and plastic CGI.

## 4. One centre and lively asymmetry

- Build rhythm with scale differences, offsets, overlaps, occlusion, light edge crop, and imperfect asymmetry.
- Use large bright solid background fields and whitespace to carry the subject. A complete side or local colour block may remain open as breathing space.
- Preserve source spatial and narrative relations without rebuilding realistic perspective or a dense scene.
- Never fill empty space with generic dots, suns, stars, leaves, grids, waves, stickers, or unrelated objects.

## 5. Bright source-derived palette

- Select the source's most recognisable and spirited colours, translating them into a limited set of high-value, high-purity flat fills.
- Bright blue, red, yellow, green, and white may form lively relationships, but they are never a fixed palette.
- Establish strong area contrast between background and subject. Build hierarchy through colour area, adjacency, overlap, and whitespace.
- Reject gradients, shadows, transparent washes, dirty grey, complex mixtures, candy-rainbow palettes, corporate brand systems, and uniform beige grading.

## 6. Typography belonging to 017

Text is a **naive but deliberately designed part of the illustration**, never a pasted poster headline, UI label, commercial sticker, or data wall.

### Copy

- Automatic copy derives one short title from the subject, visible action, relation, established place, mood cue, or grounded story relation.
- Add zero to two tiny elements only when useful: a micro-phrase, object word, supplied place word, index, state word, or playful note.
- Copy must bind tightly to this photograph and create a small moment of recognition. Reject generic inspiration, lifestyle filler, and invented stories.
- Preserve final user wording verbatim. Refine a direction or editable draft only within the user's permission.
- Use places, years, indexes, and factual information only when user-supplied or reliably established.

### Type direction

- **Role:** complete illustration rhythm, scale, and narrative.
- **Voice:** bright, friendly, playful, relaxed, slightly awkward, and knowingly designed.
- **Form:** the short title may feel handwritten, uneven in weight, or gently tilted; microcopy stays clearer and restrained. Do not force identical proportions across scripts.
- **Placement:** follow subject contour, colour-block edge, whitespace, or picture axis. Slight rotation, offset, split, or interlock is allowed only when it improves reading and composition.
- **Material:** flat black or source-derived colour with subtle hand irregularity; no vintage-print or dry-media simulation.
- **Localisation:** select a native naive-editorial equivalent for the resolved locale. Chinese, Japanese, Korean, Arabic, and Latin keep authentic shaping, spacing, direction, punctuation, and semantic line breaks.

Never render type in the photographic panel. In text-free mode render no letter, character, number, or pseudo-text anywhere in the transformed frame.

## 7. Current mode and wallpapers

The caller appends the already resolved current mode, exact dimensions, source visibility, and locked copy. Execute only those values; never choose a mode yourself.

- Paired outputs default to one complete-canvas generation with the source as a high-fidelity reference; external composition is fallback-only.
- Design-only and wallpapers contain no source photograph, seam, or photographic reserve.
- Recompose forms, colour areas, whitespace, and type for every device aspect. Keep system-UI zones low-information; render no clock, icons, dock, controls, or device frame.
- A linked wallpaper uses the original photo to lock identity and content. The anchor locks only rounded-form grammar, rough broken outline, flat-fill discipline, colour-area relations, whitespace, asymmetry, and type character. Never crop the anchor or chain derivatives.

## 8. Pre-generation gate

1. Approximate source layout, relations, core action, and at least three identity cues remain clear.
2. Rounded, simple, slightly exaggerated forms remain recognisable rather than generic-cute.
3. Black outlines are rough, jittery, and locally broken; flat fills are opaque and clean. There is no vintage mixed-media depth, vector polish, or 3D.
4. One centre survives through scale, offset, occlusion, light crop, bright field, whitespace, and imperfect asymmetry.
5. A limited bright palette is source-derived, with strong background/subject area contrast and no gradients, shadows, dirty grey, or complex mixing.
6. Copy is accurate and native to the target locale, and type belongs to the illustration rather than appearing pasted on.
7. Current mode, dimensions, source visibility, wallpaper safety, and copy settings all follow the appended block.
8. The image contains no overview collage, logo, watermark, UI, mockup, commercial sticker, dense scene, second focal point, or unrelated decoration.
