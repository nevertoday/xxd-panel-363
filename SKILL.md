---
name: xxd-panel-363
description: "XXD Panel 363｜Paper Cut-out Sketch: keeps the photo on top, identity, pose, texture and light intact, colour lightly adjusted, and below takes the subject out of that same soft, pale room and pastes a hand-cut white sheet where it stood. The sheet follows the outer contour: uneven margin, hard corners, thin shadow. The drawing is black crayon of jumping weight, burred edge, hair or the darkest mass filled solid, few folds, face only an outline. A scene keeps its structure and turns only one thing into paper. The same pen adds offset lines on a table, door or floor and tiny messy notes with curved leaders on the wall, one near-black, paper left white, Chinese in simplified characters, nothing crossing the middle. Outputs PNG top-bottom comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-363 or asks for a white-paper cut-out, a crayon line figure on a real photo, or a shop-space sketch from a photo."
---

# XXD Panel 363

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design is the photograph's own space, in its cleanest, brightest real colours and slightly softened, with the subject taken out. A pure-white sheet is pasted where it stood, hand-cut along the outer contour, with an uneven margin, hard corners and a thin shadow. It sits a little below centre, complete, with room above it and clear of the centre fold. On the paper the subject is black crayon only, weight jumping, edge slightly burred: hair or the darkest mass filled solid black, a few clothing folds, the face only an outline, the pose matching the photograph. People, animals, buildings and objects all become this same cut-out. The same pen adds a few lines on the table, door frame or floor, slightly off the real edges, and a few tiny messy notes with curved leaders on the empty wall. The notes are the only words, far smaller than the subject, the same near-black; numbering restarts each image, a place is named only when the photo shows it, Chinese is simplified, and the words say something the photograph implies rather than naming what is drawn. Paper and lines take no other colour. A scene keeps its structure, drops the clutter, and turns only its most representative thing into paper. Reject a full copy of the scene, a templated poster, the subject left as a photograph, neat square or rounded paper, thin even outlines, a flat-colour background, colour on the paper or the lines, a wall full of writing, signs copied below, text above the fold, and a drawn fold line.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-363/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-363-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
