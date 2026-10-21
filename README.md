# Liminal Bloom

Audio-reactive generative art site for one track.

## Preview locally
Because this uses ES modules, serve the folder from a local web server rather than opening `index.html` directly. For example:
`python -m http.server 8000`
Then open `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` and the `audio/` folder.
3. Open Settings → Pages.
4. Choose deploy from branch, select `main` and `/ (root)`, then Save.
5. Open the URL GitHub Pages provides.

The audio is included in `audio/track.mp3`. Playback starts after the visitor clicks Enter because browsers restrict autoplay with sound.
Three.js is loaded from jsDelivr, so the site needs an internet connection to load the 3D shader renderer.
