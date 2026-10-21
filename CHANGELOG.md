# Changelog

All versions of Stopwatch Application. The same list is shown in the app under Settings → What's new.

## 2.5.0 — Oct 21, 2026

- **Improved:** Built on Qt 6 (Qt for Python / PySide6) — a newer, faster Qt with better high-DPI support.
- **New:** Licenses entry in the Quick guide; third-party license texts are installed in the licenses folder.

## 2.4.2 — Oct 21, 2026

- **Improved:** The project now has one public home with the description, screenshots and downloads: github.com/k-viktors/stopwatch-application.

## 2.4.1 — Oct 20, 2026

- **Fixed:** Compact view now shows the beginning of long timer names instead of the end.
- **Improved:** Global shortcuts use Ctrl+Shift+Alt so they no longer clash with other apps.

## 2.4.0 — Oct 20, 2026

- **New:** History — every timer run is saved; see time per timer for today, this week, this month or all time, and copy sessions as CSV.
- **New:** Groups — organize timers into collapsible groups with their own total time and start/pause control.
- **New:** Templates — add a ready-made set of timers (Pomodoro, Workday, Daily standup) or save your own.
- **New:** Mini window — a small always-on-top bar showing one timer.
- **New:** Edit time — click a timer's digits to correct the time.
- **New:** One timer at a time — starting a timer can automatically pause the others.
- **New:** Start with Windows, global shortcuts, and automatic update checks in Settings.

## 2.3.0 — Oct 20, 2026

- **New:** Copy time button on every timer — copies the elapsed time as text, ready to paste anywhere.
- **New:** Copy time settings — choose the format (1h 2m, 1:02, or 1.03 decimal hours) and rounding (nearest minute, up to 5 or 15 minutes).
- **New:** Ctrl+C copies the selected timer's time.

## 2.2.0 — Oct 18, 2026

- **New:** Keyboard shortcuts — Space, Ctrl+N, Ctrl+Shift+Space, Delete, Ctrl+Z, and arrow keys to move the selection.
- **New:** Undo delete — a toast with Undo appears for 5 seconds after removing a timer.
- **New:** Countdown mode — set a duration on any timer; it stops at zero and shows Done.
- **New:** Color tags — mark each timer with one of six colors.
- **New:** Compact view, Always on top, and Close to system tray options in Settings.
- **Improved:** Header shows total time across all timers.
- **Improved:** Empty state with a clear call to action when no timers exist.
- **Improved:** Distinct icons for Lap (flag), New timer, and the combined Start/Pause all button.

## 2.1.2 — May 7, 2026

- **New:** What's new page — view release history right inside Settings, with unread badges on the gear icon.
- **Improved:** Settings header now reads "Theme, accent color & data" to match Quick guide.
- **Fixed:** Import CSV button no longer crashed when the helper functions were defined out of scope.

## 2.1.0 — May 4, 2026

- **New:** Brand-new Windows 11 / Fluent visual direction — solid surfaces, accent color picker, layered title bar.
- **New:** Settings page with light & dark themes and 12 Windows-matched accent colors.
- **New:** Quick guide panel — searchable, scrollable explanation of every feature.
- **New:** Start all / Pause all controls plus Copy and Import timers as CSV.
- **Improved:** Cleaner top bar — secondary actions moved into Settings under the Data section.
- **Improved:** Active timers now glow in the chosen accent across the whole window.

## 1.1.0 — Nov 29, 2024

- **New:** Initial release — multi-timer Stopwatch with named cards, drag-reorder, and millisecond precision.
- **New:** Original visual design with simple light surfaces and basic timer controls.
