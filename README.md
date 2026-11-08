# JIFUNZE KISWAHILI — Version 1.0 prototype

A responsive, browser-based interactive prototype for a multilingual Kiswahili learning platform.

## Run it
1. Extract the ZIP file.
2. Open `index.html` in a modern browser.
3. Choose an explanation language from the top-right selector.
4. Explore Lessons, Words, Practice and Progress.

## Included in this prototype
- Responsive dashboard for desktop and mobile layouts
- Language selector for English, French, Arabic, Spanish, German, Chinese, Hindi, Italian, Portuguese and Japanese
- Right-to-left page direction when Arabic is selected
- Beginner greetings lesson
- Kiswahili vocabulary list
- Browser speech-synthesis pronunciation attempt (voice availability depends on the device/browser)
- Three-question interactive quiz with feedback
- Session-based progress indicators

## Important prototype limitations
- This is a front-end prototype, not a published Android/iOS application.
- Language selection currently changes navigation labels and writing direction; full lesson translations are a production content task.
- Progress is held in the current page session and is not connected to a user account or cloud database.
- Speech uses the browser's installed speech voices. A verified Kiswahili voice may not be available on every device.
- There is no backend, authentication, payment processing, certificate issuance or admin portal yet.

## Recommended production architecture
- Flutter for Android, iOS and web clients
- Supabase (or equivalent) for authentication, database and learner progress
- Professionally reviewed translations for all ten explanation languages
- Recorded Kiswahili audio from proficient/native speakers, with speech technology added where appropriate
- Content-management dashboard for lessons, quizzes and translations

## Suggested next development milestone
Build the Flutter application shell and connect a structured lesson/content database. Before public release, have Kiswahili educators and qualified translators review the curriculum and all translations.
