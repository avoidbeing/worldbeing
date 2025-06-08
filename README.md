# Worldbeing Prototype

This project currently serves a minimal static page with an interactive Leaflet map. The files live under the `public` directory so Vercel can deploy them with no special configuration.

## Deploying to Vercel

1. Install the [Vercel CLI](https://vercel.com/docs/cli) and log in.
2. Run `vercel` the first time to set up the project.
3. Deploy to production with:
   ```bash
   vercel --prod
   ```
4. Visit `https://<your-project>.vercel.app` (or your linked domain) to see the map.

If you previously used the Haskell server in this repository, it has been removed so the deployment is purely static. You can reintroduce it later or host it separately if needed.
