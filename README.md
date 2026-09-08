# AgentHacks — complete website source

This ZIP contains the complete standalone website from the AgentHacks redesign preview: editable HTML, CSS, JavaScript, original hero artwork, favicon, and a locally hosted font with its license.

## Open the site

1. Extract the ZIP.
2. Open `agenthacks-site/index.html` in your browser.

No installation, API key, or build step is required. All runtime assets are included.

For a local web server, open a terminal in the extracted `agenthacks-site` folder and run:

    python3 -m http.server 8000

On Windows, you can also use `py -m http.server 8000`. Then open http://localhost:8000 in your browser. Stop the server with Ctrl+C.

## Edit the site

- `index.html`: all visible text, sections, navigation, project examples, and FAQ entries.
- `styles.css`: colors, typography, spacing, and desktop/mobile layouts.
- `script.js`: mobile menu and project-example filters.
- `assets/agent-loop.png`: hero artwork.
- `assets/favicon.svg`: browser-tab icon.
- `assets/InterVariable.woff2`: local font.
- `assets/Inter-LICENSE.txt`: font license.
- `HACKATHON-IDEAS.md`: proposed theme, alternative prompts, and organizer guidance.

## Host the site

The extracted folder is a complete static website. Upload its contents together to a static host, keeping `index.html`, `styles.css`, `script.js`, and `assets/` in the same arrangement. Configure the host to serve this folder directly; no build command is needed.

To integrate into your existing GitHub repository, preserve its publishing configuration and place these files in the folder it serves. There is no framework dependency, package installation, or backend service.

## Event status

This is the standalone proposal created in this conversation. The original `tams-BEACON/agentHacks` repository was inaccessible during creation, so this archive is not an export of that repository. The theme is proposed; dates, registration, eligibility, team sizes, judging rules, and prizes need organizer confirmation. The page currently collects no registrations or personal information.

The website files are the same as the private preview. Account-specific hosting metadata and Git history are not needed to run this portable copy.
