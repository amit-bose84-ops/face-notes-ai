# Face Notes AI — 10 Broad Categories

A single-page, browser-based prototype that classifies up to 10 broad visible facial-feature groups from one portrait.

## Local use
1. Open `index.html` in a modern browser.
2. Add a temporary Gemini API key to `GEMINI_API_KEY` in the HTML source.
3. Upload one JPG, PNG, or WEBP portrait and choose **Analyze with Gemini**.
4. Review/edit the category labels and export CSV, JSON, or Markdown.

## Important
- This prototype calls Gemini directly from the browser. Any API key embedded in the file is visible to people who can access the file/site. Do not publish a real key in a public repository; use a restricted temporary key and revoke it after testing.
- The image is sent to Google Gemini for processing.
- The output is a rough visual summary, not precise measurement or identity recognition.
