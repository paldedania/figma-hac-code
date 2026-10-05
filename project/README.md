# CalmWait HTML and CSS

Open `home/index.html`, or serve this directory with `python3 -m http.server 8080` and visit http://localhost:8080/home/.

The site uses plain semantic HTML and local CSS, fonts, images, and icons. No JavaScript, frameworks, CSS Grid, positioned layouts, or HTML tables are included. The light base palette follows the user's explicit choice for this project.

## Pages

- `home/index.html`: My Visit.
- `services/index.html`: Live Queue.
- `blog/index.html`: My Progress.
- `contact/index.html`: Alerts & Notifications.
- `step-out/index.html`: Step Out of Waiting Room.
- `about/index.html`: Patient Profile & Care Preferences.
- `sign-in/index.html`: Secure Patient & Staff Portal.
- `reception/index.html`: Clinic Patient Stream.
- `analytics/index.html`: Waiting-Room Operations & Flow Analytics.
- `caregiver/index.html`: Caregiver Dashboard.
- `settings/index.html`: Settings.
- `live-queue/index.html`: Live Queue.
- `alerts/index.html`: Alerts & Notifications.
- `progress/index.html`: My Progress.
- `profile/index.html`: Patient Profile & Care Preferences.

The live-queue, alerts, progress, and profile folders are descriptive aliases for the same screens. Their CSS imports the canonical page stylesheet.

The required folder names map to the clinic design: home is My Visit, about is Patient Profile, services is Live Queue, contact is Alerts, and blog is My Progress. Additional screens have descriptive folder names.

## Design source and limitations

Source: https://www.figma.com/design/BNFXBVnfrOXXn4MZjc6HHT/Untitled?node-id=36-404

The Figma MCP connector reported its Starter plan quota was exhausted. Implementation used the existing browser-exported Figma node data, CSS measurements, assets, and visual inspection of the accessible file. The exact current connector output could not be fetched. This is a responsive reconstruction, not a certified pixel-exact export. Mobile-only caregiver and settings frames are expanded for desktop. Fixed sidebars and overlays have been converted to document-flow Flexbox layouts to meet the CSS restrictions.

Values, timestamps, QR codes, patient identities, and clinical claims reproduce sample design content. They are not a live clinical service. Navigation, disclosure controls, native form validation, selectable controls, and the sample PDF download work without JavaScript. Authentication, saving preferences, alerts, audio, camera scanning, queue updates, broadcasts, and medication orders require backend integration. Controls do not claim these actions succeeded. The sign-in preview does not transmit the entered identity fields.

`css/global.css` contains the reset, font declarations, palette, typography, shared shell, forms, cards, buttons, utilities, and shared responsive rules. Each page's `style.css` contains only its own layout. Breakpoints cover desktop, 768–1199px tablets, all screens below 768px, and screens below 368px. Print styles use a light palette.

`SOURCE.md` includes every page's HTML and CSS, followed by global.css, in the requested code-block format.
