# Event form redirect

This folder contains a standalone GitHub Pages entry page. It redirects to the existing Apps Script web app and includes an **Open event form** link if automatic navigation does not complete. It has no external libraries, analytics, or form fields. Event data is still entered and processed in the Google-hosted app.

## Set the destination

`index.html` is already configured with the supplied `pomegranets.com` Apps Script deployment. To change the destination later, update the `href` on the **Open event form** link. This is the only destination setting. Use the published `/exec` URL, not the editor-only `/dev` URL. Standard and Workspace-domain Apps Script URLs are supported.
