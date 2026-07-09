# Study Desk

A weekly study tracker for four topics: COMP10002, COMP20008, INFO20003, and MAST10010.

Each topic gets:
- A 10-hour weekly study countdown timer
- A break timer that automatically pauses the study timer (and vice versa)
- A goals notepad for the session
- Progress saved automatically per topic

## Usage

Just open `index.html` in a browser. No build step, no dependencies — it's a single self-contained file (HTML, CSS, and JS all inline).

Note: the progress-saving feature relies on a `window.storage` API that's provided by the Claude.ai artifact environment. If you open this file directly in a regular browser (outside Claude.ai), the timers and goals text will still work during your session, but won't persist between visits unless you wire up your own storage (e.g. localStorage).
