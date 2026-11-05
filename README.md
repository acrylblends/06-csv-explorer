# CSV Explorer

A local-first data workbench for importing CSV files, profiling columns, filtering rows and charting a selected field.

An ACRYL Blends blueprint for the **Data** category (`acrylblends.csv-explorer`, category 06 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.csv-explorer
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
