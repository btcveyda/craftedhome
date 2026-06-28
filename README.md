# CraftedHome

CraftedHome is an Angular landing page for a handcrafted home decor business. It is designed as a lightweight portfolio-style site and can be deployed as a static site.

## Local development

```bash
npm install
npm start
```

Open `http://localhost:4200` in your browser.

## Build

```bash
npm run build
```

The production site is generated in `dist/craftedhome-app`.

## Render deployment

This project includes a `render.yaml` file for Render static hosting. Set the build command to `npm install && npm run build` and publish `dist/craftedhome-app`.
