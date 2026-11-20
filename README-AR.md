# SafeDose-JOR

**Medication Safety at Home | سلامة الدواء في المنزل**

A bilingual (Arabic/English), mobile-friendly educational web app focused on safer medication use at home in Jordan.

## Features
- Before-taking medication checklist.
- Paracetamol / acetaminophen duplicate-ingredient warning.
- Safe storage and medicine disposal guidance.
- Missed-dose and extra-dose safety guidance.
- Emergency warning signs and Jordan unified emergency number (911).
- Interactive five-question quiz with score and explanations.
- Trusted medical references.
- Responsive design, PWA manifest, and basic offline caching.

## GitHub Pages deployment
1. Create a **Public** repository named `SafeDose-JOR`.
2. Extract the ZIP file on your device.
3. Upload the **contents of the extracted folder** to the repository root (not the ZIP file itself).
4. Confirm that `index.html` is directly visible at the repository root.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`, then Save.
8. Wait for GitHub Pages to publish the site.

## Important educational notice
This project is an educational prototype, not a clinical decision-support tool. It does not calculate doses, diagnose poisoning, or replace a clinician, pharmacist, product leaflet, or local emergency services. Missed-dose instructions are medicine-specific. Suspected overdose requires prompt professional advice even if no symptoms are present.

## References
- FDA — Acetaminophen: https://www.fda.gov/drugs/safe-use-over-counter-pain-relievers-and-fever-reducers/acetaminophen
- MedlinePlus — Storing your medicines: https://medlineplus.gov/ency/patientinstructions/000534.htm
- NHS Specialist Pharmacy Service — Missed or delayed doses: https://sps.nhs.uk/articles/advising-on-missed-or-delayed-doses-of-medicines/
- FDA — Disposal of unused medicines: https://www.fda.gov/drugs/safe-disposal-medicines/disposal-unused-medicines-what-you-should-know
- Jordan Government — Emergency numbers: https://jordan.gov.jo/EN/List/Contact_Us_2

## Files
- `index.html` — application structure and content
- `styles.css` — responsive design
- `app.js` — bilingual interactions and quiz
- `manifest.json` — PWA metadata
- `sw.js` — offline cache
- `icons/icon.svg` — app icon
