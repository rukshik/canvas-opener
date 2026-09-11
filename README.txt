Canvas Smart Opener

Behavior:
- iPhone/iPad: opens the assignment in Canvas Student using canvas-courses://
- Mac/other desktop: opens the normal Canvas HTTPS assignment page
- iPhone/iPad without Canvas Student: falls back to the normal web page

Recommended free hosting: GitHub Pages in a tiny public repo containing only index.html.
No Canvas token, Todoist token, or private ICS URL goes in this repo.

After publishing, your opener URL will look like:
https://YOUR-GITHUB-USERNAME.github.io/canvas-opener

Set CANVAS_OPENER_URL to that base URL in the existing GitHub Actions workflow.
