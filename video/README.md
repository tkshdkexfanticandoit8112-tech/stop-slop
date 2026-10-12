# Stop Slop promo video

A 22-second [HyperFrames](https://hyperframes.heygen.com) composition that shows three before/after rewrites from `references/examples.md`.

- `index.html` is the composition (GSAP timeline, 1920x1080).
- `assets/gsap.min.js` is GSAP 3.14.2, vendored so renders work offline.

```bash
cd video
npm run check    # lint, runtime, layout and contrast checks
npm run dev      # preview in HyperFrames Studio
npm run render   # writes an MP4 to renders/
```

Renders need Node, FFmpeg and Chrome (`npx hyperframes doctor` checks them).
