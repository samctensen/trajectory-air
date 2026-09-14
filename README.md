# Trajectory Air

An interactive web application for exploring air-quality model data on a map.

Built with Next.js, TypeScript, React, Mapbox, and Recharts. This legacy application was retired in June 2025; the existing deployment redirects to [aero.traceaq.com](https://aero.traceaq.com).

## Develop

With Node.js and npm installed:

```sh
npm ci
npm run dev
```

Set `NEXT_PUBLIC_MAPBOX_TOKEN` and `NEXT_PUBLIC_MAPBOX_USERNAME` in `.env.local` for your Mapbox setup. Run `npm run build` for a production build. The redirect in `vercel.json` remains part of the archived deployment configuration.

## Project

- `app/`, `components/` — application pages and interface.
- `functions/`, `constants/`, `types/` — data handling and shared definitions.
- `UploadNetCDFs.py` — an earlier upload script.
- [Trajectory Air Uploader](https://github.com/samctensen/trajectory-air-uploader) — the separate data preparation and upload pipeline.
