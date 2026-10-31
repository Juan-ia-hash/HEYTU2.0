# Vercel deployment preparation

The root `vercel.json` configures the build, output directory, and routing.
Import `Juan-ia-hash/HEYTU2.0` with `main` as the production branch and leave
the Root Directory at the repository root. Deploy the latest commit.

Set the Vercel build command to `npx expo export --platform web` and the output
directory to `dist`. The repository's `npm run web` command starts the local
development server; it is not the production build command.

This version works without an account or authentication environment variables.
User preferences and progress are saved locally on the device.
