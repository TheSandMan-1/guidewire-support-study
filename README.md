# Guidewire support during catheter withdrawal

An independent study of how much support a guidewire needs while an IVUS catheter is pulled back in wrist-to-leg
(radial-to-peripheral) cases. It starts from Philips' 2025 field safety notice for Visions PV catheters, which asks for
a guide sheath of appropriate length.

**View the presentation:** https://thesandman-1.github.io/guidewire-support-study/

## What's in it

- `index.html`: the 8-page presentation. It covers the procedure, the reported problem, two model runs, what the free
  length of wire changes, and the bench test I'd run next.
- `how-the-model-works.html`: how the model works, with its assumptions, equations, checks and sources.
- The `.mp4` and `.jpg` files: the procedure and model films and their stills.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Limits

This is an independent study. It is not affiliated with or endorsed by Philips. The model uses assumed inputs and has
not been compared with a physical test, and it does not establish a safe support length. Anatomy, devices and timing in
the films are simplified illustrations, not a procedural guide.

© 2026 Ali Awarke. All rights reserved.
