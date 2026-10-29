GB DELIVERY ROTATION — TEST BUILD

Files:
- index.html
- gb-logo.png

How to test:
1. Upload both files to a NEW GitHub repository or a new folder/repository path. Do not overwrite the existing 120 DAYS project.
2. Enable GitHub Pages for the new repository.
3. Open the published URL.
4. Go to Settings and enter the real project start date.
5. The 12 fixed names have been entered. In Team & points, use Edit to enter each worker's existing cumulative delivery count and (if known) their last delivery date.
6. Use the candidate buttons to test the dynamic priority list.

Important limitations:
- This is a browser-local prototype. localStorage means changes are saved only in the browser/device that made them. It is NOT yet shared/synchronized across 12 phones.
- For the real shared version, connect a cloud database (for example Supabase) and add appropriate database rules. Do not use this demo as the official shared record yet.
- Demo points are fictional. Replace them with actual counts before presenting the ranking as real.
- The start date is intentionally blank because the project start date has not been supplied. The app calculates project day from the date you enter.
- Default candidature hours are 07:00–14:00 and can be changed in Settings; the closing time remains configurable.
- Daily candidates are reset on the next calendar day. This browser demo uses the device's local date/time; the shared version should use server time in Europe/London.
