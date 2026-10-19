# LaunchKit Studio — Zero-budget MVP

A mobile-friendly, static website toolkit built with plain HTML, CSS and JavaScript. No build step, API key, account, or paid service is required to run the core tools.

## Included tools
- SEO Quick Check: checks HTML source pasted by the user for basic title, description, H1, viewport, language, image alt, canonical and noindex signals. It is not a crawler or a full SEO audit.
- Landing Page Studio: edits a small set of landing-page fields, previews them and exports a standalone HTML file.
- Launch Checklist: interactive checklist with browser-local progress and a downloadable text report.
- Gradient & Contrast: generates CSS gradient code and calculates colour contrast.

## Run locally
Open `index.html` in a browser. All main tools run client-side.

## Publish from a phone using GitHub Pages
1. Download and extract `launchkit-studio.zip` on your phone.
2. Create a new public GitHub repository, for example `launchkit-studio`.
3. Upload `index.html` and `README.md` to the repository root (not inside an extra folder).
4. Open the repository's **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
6. Wait for GitHub Pages to publish and open the URL shown in Settings → Pages.

If uploading the whole ZIP through GitHub's browser interface is inconvenient, extract it first and upload the files. GitHub Pages does not execute a ZIP directly.

## Limitations and next steps
- The SEO tool analyzes only the HTML source pasted into it. It does not fetch arbitrary sites because browser cross-origin restrictions can block this, and it does not test Google rankings.
- The app does not yet have accounts, cloud-synced projects, payments, server-side scanning, AI API calls, or email notifications.
- This first version is intentionally static and free to host. Validate it with real users before adding backend services or paid features.
