# NDIS Incident Report Form (Form 04)

A highly optimized, digital version of the standard NDIS Form 04 Incident Report. This web-based utility is designed to dramatically increase form-filling speed, reduce errors, and ensure accurate record keeping for support workers and NDIS providers.

## 🚀 Features

- **Blazing Fast Entry**: Date and time fields automatically pre-fill to the current time.
- **Voice Dictation (Speech-to-Text)**: Built-in microphone buttons (`🎤 Dictate`) above all major description text boxes. Uses native browser Web Speech API (optimized for Australian English `en-AU`) with live text preview.
- **Auto-Save & Draft Recovery**: The form automatically saves every keystroke locally to your browser (`localStorage`). If you accidentally close the tab, lose internet, or refresh, your progress is instantly recovered when you reopen the page.
- **Dynamic Layout**: Sections like "Injury Information" remain hidden unless toggled, keeping the interface clean. Action plans and corrective strategies feature dynamic lists to easily add or remove multiple rows.
- **Gold-Standard PDF Generation**: Clicking "Generate & Print Report" converts the form into a highly compressed, perfectly formatted formal document. It natively handles long text descriptions, ensuring zero text is trimmed and dynamically breaking pages perfectly in the resulting PDF.

## 🛠️ Usage

1. Clone or download this repository.
2. Double-click the `incident_report.html` file to open it in any modern web browser (Google Chrome, Microsoft Edge, or Safari recommended for Speech-to-Text support).
3. Fill out the incident details.
4. Click **"Generate & Print Report"** at the bottom to save it as a PDF or print a physical copy.
5. Click **"Clear Form"** when you are ready to wipe the saved draft and start a brand new report.

## 💻 Tech Stack
- Single-file Vanilla HTML, CSS, and JavaScript. 
- No build steps, no external dependencies, and no backend database required. 
- Everything runs completely locally and securely in the user's browser, ensuring strict patient data privacy.
