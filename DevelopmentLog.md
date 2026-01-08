# Development Log

All notable changes to the LiftKit project will be documented in this file.

## [v1.02] - 2026-01-07

### Added
* Freestyle Mode! spontanious lifting session with friends? I got you covered so you can still log those gains and maintain growth!

### Fixed
* No Bug Fixes Addressed

### Engineers Notes
I created a new UI view called FreestyleWorkoutView. It creates in-memory 'session' objects,
Its independent from sessionmanager.active session and only persists when user clicks "Finish and Save".
I reused {session" "session exercise" "sessionset"} models no changes being made. The UI is also mirrored from activesessionview to keep a consistent user exerpience.


## [v1.01] - 2026-01-01 (Launch)

### Added
* Changed Homescreen Icon

### Fixed
* Fixed Bug issue where viewing graphdata would crash the app
* - Implemented lazy loading where instead of all instance of all workout were loaded into view only the selected workout id loaded when clicked on.

---

## [v1.0.0] - 2026-01-01 (Pre Release)

### Summary
Initial app submission.

### Core Features
* **Workout Builder:** Create and save custom workout templates.
* **Active Session Manager:** Real-time logging interface with auto-advancing sets.
* **History & Analytics:** Local SwiftData storage with data visualization for volume and 1RM trends.
* **Settings:** Basic user configuration for units (lbs/kg) and theme preferences.

---

## [Noticed Bugs Being Worked On]
*Work in progress for next version Please Submit any issue through the form or DM me on instagram so I can fix any problems you may have*

* **In Progeress:** Fixing Chart tracking + ActiveSessionView for bodyweight exercises
