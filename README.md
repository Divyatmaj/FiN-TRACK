Expense Tracker
Privacy-first, offline-capable Android expense tracker built with Kotlin, Jetpack Compose, Room, Coroutines, and Hilt.

Overview
Expense Tracker is a lightweight app for recording and analyzing personal spending. Data is stored locally (Room) to protect privacy. The codebase uses a modular MVVM architecture, Coroutines for async work, Hilt for DI, and Jetpack Compose for a modern, accessible UI — making it easy for contributors to add features and improve UX.

Key features
Add, edit, and delete expenses and categories
Local persistence with Room; CSV export/import
Charts and summaries (daily / weekly / monthly)
Dark mode and accessibility-friendly layouts
MVVM + Coroutines + Hilt; unit-tested core logic
Screenshots
Add screenshots to /docs/screenshots and reference them here.

Quick start (macOS)
Install Android Studio and required SDKs.
Clone the repo: git clone
Open the project: Open the android/ folder in Android Studio.
Build & run:
From Android Studio: Run configuration on an emulator or device.
From terminal (project root): ./gradlew assembleDebug ./gradlew installDebug
Run tests
./gradlew test ./gradlew connectedAndroidTest

Contributing
Contributions are welcome. Please:

Read CONTRIBUTING.md and CODE_OF_CONDUCT.md.
Open an issue before large changes.
Fork, use a feature branch, add tests for logic changes, and submit a PR with a clear description and screenshots for UI changes.
Keep commits focused and atomic.
Suggested areas to contribute:

Syncing & multi-device support
Improved analytics and charts
Internationalization and localization
UI polish and accessibility improvements
License
Recommended: MIT License. See LICENSE file.

Contact
Open issues or PRs on GitHub. For questions, use the repository discussions.

Thank you for contributing — small improvements make a big difference.
