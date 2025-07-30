# TUNA Random MP3 Button

This is a minimal webpage that shows a circular TUNA button image. When clicked, it plays a random MP3 from the `audio/` folder, stopping any track that was previously playing.

## How to use
1. Replace the placeholder MP3s in `audio/` with your own files **or** rename your files to match `song1.mp3`, `song2.mp3`, `song3.mp3`.  
   - If you use different names, update the `mp3Library` array in `index.html`.
2. Open `index.html` locally to test.
3. To host on GitHub Pages:
   - Create a public repository and upload the contents of this folder.
   - In the repo settings, enable **Pages** and set it to deploy from the **main** branch.
   - Your site will be available at `https://<username>.github.io/<repo-name>/`.

## Notes
- The button uses the uploaded PNG (`Tuna Button.png`) as its background.
- Clicking the button while a track is playing will stop it and start a new random track.
