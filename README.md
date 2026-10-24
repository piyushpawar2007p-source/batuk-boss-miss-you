# For Batuk Boss ♥ — I Miss You Website

A romantic, mobile-first React + Vite website from Rehan to Batuk Boss. It includes a landing screen, emotional message, photo placeholders, interactive letter, optional background music, and a final animated message.

## Run locally
1. Install Node.js LTS from https://nodejs.org/ if it is not installed.
2. Extract this folder and open it in VS Code.
3. Open Terminal in VS Code and run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL printed in the terminal (usually `http://localhost:5173`).
5. Before publishing, run `npm run build` to check the production build.

## Add photos
Put three photos in `public/photos/` with these exact names:
- `memory-1.jpg`
- `memory-2.jpg`
- `memory-3.jpg`

You can use `.png` or `.webp`, but if you do, update the filenames in `src/App.jsx` too. Use photos you have permission to share, and get both people's consent before publishing intimate or private pictures.

## Add music
Choose a song you have permission to use. Put the audio file in `public/music/` and name it `our-song.mp3`. The music button starts playback only after the visitor taps it. If you use a different filename, update `songPath` in `src/App.jsx`.

## Personalize the letter and captions
Open `src/App.jsx` and edit:
- `memories` for photo captions
- `letter` for the personal letter
- the hero and final-section text in the JSX
- `songPath` for the song file

The included letter is deliberately gentle: it acknowledges an argument, apologizes for one's part without pressuring her to forgive, and gives her room to respond when ready. Change it so it reflects what Rehan genuinely means.

## Publish on Vercel (free tier)
### Option A: Deploy with GitHub (recommended)
1. Create an account at https://github.com/ if needed.
2. Create a new repository and upload the contents of this project folder (not the ZIP file itself).
3. Open https://vercel.com/ and sign in with GitHub.
4. Choose **Add New → Project**, import your repository, and keep the detected Vite settings.
5. Click **Deploy**. Vercel will give you a public URL you can share.
6. Any future GitHub push will trigger a new deployment.

### Option B: Deploy with Vercel CLI
1. Install Node.js LTS.
2. In this project folder run `npm install`.
3. Run `npx vercel` and follow the prompts to sign in and deploy.
4. For a production deployment, run `npx vercel --prod`.

## Important
- The website does not send messages or collect information; all interactions run in the browser.
- Do not publish personal photos or private messages without permission.
- A song file is not included. Use music you have rights or permission to use.
