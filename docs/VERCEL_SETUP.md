# Vercel deployment preparation

Set the Vercel build command to `npx expo export --platform web` and the output
directory to `dist`. The repository's `npm run web` command starts the local
development server; it is not the production build command.

This version works without an account or authentication environment variables.
User preferences and progress are saved locally on the device.
