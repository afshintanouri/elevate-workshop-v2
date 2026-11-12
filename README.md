# Elevate V2: AI Learning Journey Designer

A premium, static browser application for the workshop **Building Workforce Capability That Matters in the Age of AI**.

## Deploy to GitHub Pages

This version has no build step and no dependencies.

1. Download and extract the ZIP.
2. In your `elevate-workshop` GitHub repository, replace the existing project files with:
   - `index.html`
   - `styles.css`
   - `script.js`
3. Commit the change.
4. In **Settings → Pages**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save. GitHub will publish the app at the repository's Pages address.

Because this is a static version, you do not need Vite, npm, `package.json`, GitHub Actions or a build workflow.

## Safer replacement method

If you want to preserve the Google AI Studio version, create a new repository such as `elevate-workshop-v2` and upload these files there first.

## Privacy

All participant responses remain in the browser through `localStorage`. No data is transmitted or stored remotely.

## Customisation

Edit the `MODES` object at the top of `script.js` to change quadrant names, descriptions, literacy labels or colours.

## Export

The final plan supports browser print/save-to-PDF and JSON download.
