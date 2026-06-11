📋 Release Notes: Version 1.2
🚀 What's New & Enhancements
Cleaned Codebase (Legacy Feature Removal):
Completely removed the legacy Time Codes system to simplify session flow.
Streamlined UI across the Dashboard, Start Session, and Manage Session screens.
Dynamic Versioning:
The About Screen now retrieves the app version dynamically (v1.2 / versionCode 3) directly from the package configuration.
Updater & License Integration:
In-app automatic update checker fetching updates directly from the official GitHub releases.
Fully accessible About & Updater screens even when not logged in or when the license is invalid.
Improved Database & UI Stability:
Incremented database version to 3 with fallback destructive migrations to prevent crash loops on schema updates.
Cleaned up navigation flows and redundant routes.
