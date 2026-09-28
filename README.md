# RobCo 8D

A Fallout-inspired green terminal for converting your own audio into moving stereo sound. Runs entirely in the browser, with no server, account, API key, or audio upload.

## Publish with GitHub Pages

1. Create a GitHub repository named `Robco-8d` (public if using free GitHub Pages).
2. Upload `index.html`, `styles.css`, and `app.js` into the repository root. You can also include this README and `.nojekyll`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/ (root)**, then **Save**.
6. GitHub will show the published URL when deployment finishes. For repository `h27096/Robco-8d`, the expected address is `https://h27096.github.io/Robco-8d/`.

Keep the three app files beside each other. Do not upload the ZIP itself as the website. Future commits to the publishing branch update the site.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Use it

- Open the site on iPhone or PC. On iPhone, use Safari for the native share sheet.
- Select **LOAD AUDIO**, choose an audio file, and use headphones for playback.
- Adjust rotation speed, intensity, echo, bass, and direction, or choose a preset.
- Select **Export 8D audio**, wait for rendering, then select **Save / share WAV**.
- On iPhone, choose **Save to Files**. If sharing is unavailable, the app downloads the WAV.

## Limits and privacy

- WAV export only; tracks must be 10 minutes or shorter for export.
- Browser support determines which input formats decode. MP3 and WAV are useful first choices; DRM-protected streaming downloads will not work.
- The queue lasts for the current page session. Reloading clears loaded files.
- Keep the page open while converting. Large audio files can use substantial phone memory.
- The effect uses moving left/right levels with bass and echo; it is not a true multichannel spatial recording.
- The app never sends the selected audio to GitHub or another server. GitHub still serves the website itself.
- Unofficial fan project, not affiliated with Bethesda or the Fallout rights holders.

## Run locally

Serve this directory using any static server, for example `python3 -m http.server 8000`, then open `http://localhost:8000` on that computer.
