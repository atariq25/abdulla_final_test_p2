# abdulla_final_test_p2

Abdulla Tariq — simple typing speed tester web app included in this project.

## Files
- `webapp.html` — single-file typing speed tester (HTML/CSS/JS)

## Typing tester features
- Difficulty selector: `Easy`, `Medium`, `Hard`
- Multiple sample texts with `Next Sample` and `Random` sample buttons
- Measures time, WPM and accuracy
- Stores best WPM per difficulty in your browser (`localStorage`)

## Usage
Open `webapp.html` in your browser. From PowerShell you can run:

```powershell
ii webapp.html
# or
Start-Process webapp.html
```

Click `Start` to begin typing. The test finishes automatically when your text matches the sample. Use `Reset` to stop and clear.

## Notes
- WPM calculation: (correct characters / 5) ÷ minutes
- Best scores are saved per difficulty in the browser and shown in the UI

If you want more samples, export/import for best scores, or a standalone static site, tell me which and I'll add it.
