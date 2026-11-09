# anwalt-dornstadt.de

Static HTML/CSS website. No dependencies, build tools, or backend required.

## Local preview

Open `index.html` directly in a browser. All styles and local navigation work without a server. Review all three pages at desktop and mobile widths, including keyboard navigation and the link to the separate Betreuungsbüro website.

## Outstanding client-approved content

- `impressum.html`: replace the marked placeholder block with the complete, client-approved Impressum.
- `datenschutz.html`: replace the marked placeholder block with the complete, client-approved privacy policy, accounting for the actual hosting configuration and server logging.

No legal details or privacy policy text have been invented. Both placeholder pages currently include a `noindex` meta tag; review it when approved content is inserted.

## Upload to STRATO Webhosting

**Publish only after the client approves the preview and supplies the approved legal content.** These are instructions for a later upload; the website has not been deployed.

1. Back up the existing website.
2. Connect with an SFTP client using the host, port, username, and credentials provided for the STRATO hosting account.
3. Open the existing web directory assigned to `anwalt-dornstadt.de`.
4. Upload `index.html`, `impressum.html`, `datenschutz.html`, and `styles.css` together into that directory. Keep this README locally; no build step is needed.
5. Check whether an existing `index.php` or another default document takes precedence over `index.html`. Back up conflicting old files before removing them.
6. Verify HTTPS, all three pages, footer navigation, and the Betreuungsbüro link after upload.

Do not configure DNS or change domain settings as part of this project. The Betreuungsbüro website remains separate.
