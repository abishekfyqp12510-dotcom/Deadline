# Schedule Submission Reminder

A simple web app whose only job is to remind you when a schedule of work is due for submission.

## Features
- Add a schedule with a title, a submit-by date/time, and a reminder lead time
- Reminders appear on the page and as browser notifications
- Mark a schedule as submitted, or make it repeat weekly
- Data is saved in the browser (localStorage), so no server or database is needed

## Run locally
Open `index.html` in any modern browser. That's it.

## Deploy with GitHub Pages
1. Create a repository on GitHub (e.g. `schedule-reminder`).
2. Upload `index.html` and `README.md` to the repository.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
4. Open `https://<your-username>.github.io/schedule-reminder/`.

## Limitations
- Notifications appear only while the page is open in a browser tab.
- Data is stored per browser and device. It does not sync between devices.

## Possible next steps
- Make it a Progressive Web App (PWA) so it installs on a phone
- Add sync across devices with a small backend or a service such as Firebase
- Add email or push reminders
