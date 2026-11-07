SHREYA BIRTHDAY WEBSITE — DRAFT 1

Open index.html in a browser on a computer to preview. For iPhone Safari, hosting this folder as a static website (e.g. Netlify Drop / GitHub Pages) is the most reliable option. Opening local HTML from iOS Files may use a preview and can restrict audio or scripts.

Replace photo placeholders: edit index.html to point to your JPG/PNG images, or replace the existing SVGs with your photos and update extensions in HTML.

Place your audio file at music/tum-se-hi.mp3. Music starts after tapping Open your surprise; iOS Safari prevents autoplay without user interaction.

All interactive code is contained in index.html. The optional Google Fonts require internet; Georgia and Arial are offline fallbacks.

The letters, quiz and reasons are editable starter text, not personal stories.


PASSWORD ENTRANCE
The opening screen asks for the relationship start date in DDMMYYYY format.
The current draft accepts 05032023.

PRIVACY NOTE
This is a client-side surprise gate, not real security. The password check is in the website's JavaScript, and anyone who can inspect the deployed files may discover or bypass it. Do not upload intimate or sensitive photos to a public static host on the assumption that this gate protects them. For genuine privacy, deploy behind server-side authentication / an access-control service.
