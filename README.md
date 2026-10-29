# AUS email signature

Open `index.html` in a browser. Enter only the team member's full name and job title, compare the four versions, then copy the selected version into the mail account's signature settings. All AUS contact information and brand elements are locked for consistency.

- **Version 1 — Compact:** the recommended mobile-first option.
- **Version 2 — Executive banner:** a wider AUS alternative inspired by the supplied institutional example.
- **Version 3 — Portrait:** a people-focused option with an optional employee headshot.
- **Version 4 — Executive portrait:** a balanced institutional layout with a compact, professionally framed portrait and a navy logo header.

Versions 3 and 4 share an optimized media library of 11 transparent-background AUS team portraits. Abbass Mokashar is selected in the example. Users can choose another team member, remove the portrait, or upload their own image. Uploaded JPG, PNG, and WebP files are processed locally in the browser: the background is removed and the portrait is trimmed and resized to the same 320 × 400 transparent PNG format as the library.

The folder also includes `abbass-mokashar-signature.html`, a finished standalone example based on the details in the previous signature.

## Compatibility choices

- Email-safe table structure with inline styles
- Web-safe Arial fallback, with no external font dependency
- Official AUS logo supplied by the team, with a matching public website asset used in outgoing email
- PNG delivery for broader Outlook compatibility; `aus-logo.png` is included for future hosting on the AUS domain
- Neutral charcoal, white, and crimson palette with no large blue panel
- Email-safe contact and social icon markers
- Fixed-size PNG icons in zero-line-height table cells to reduce Gmail/Outlook spacing differences
- No JavaScript, SVG, CSS grid/flex, background images, or icon fonts inside the copied signature
- Hosted team-library photos are preferred for consistent delivery; a custom upload is embedded and should be verified with a test email
- Automatic upload processing uses `@imgly/background-removal` 1.7.0 in the browser; the first upload downloads and caches its processing model and may take longer
- Clickable email, phone, website, LinkedIn, and Instagram links
- 600 px maximum width for desktop and mobile email panes

## Gmail

Settings → See all settings → General → Signature. Create a signature, paste, and save changes. Make sure plain text mode is off when composing.

## Outlook / Hotmail

Settings → Accounts → Signatures. Create or edit a signature, paste, then save.

Always send a test message to both a desktop and a mobile inbox before rolling the signature out to the team.
