# loopd-public-overview
# Loopd – HIIT Timer (Android)

[View on Google Play](https://play.google.com/store/apps/details?id=com.princemwill.loopd_hiit_timer&pcampaignid=web_share)

Loopd is an Android HIIT timer app focused on reliability under real-world conditions, particularly around background execution, notifications, and audio behavior.

The app is currently published on the Google Play Store and continues to be iterated on as part of ongoing debugging and refinement work.

## Key Technical Challenges

- Foreground service behavior on Android 15 (notification persistence issues)
- Audio session conflicts with external apps (e.g., Spotify)
- Timing reliability under background execution constraints

## Development Approach

This project was developed using a combination of traditional debugging and AI-assisted workflows.

I used multiple AI tools (e.g., Gemini, ChatGPT, and an AI-enabled IDE) to accelerate iteration and explore solutions. These tools were useful for generating initial approaches, but required validation and refinement—especially when dealing with platform-specific behavior and inconsistent system-level responses.

A significant portion of the work involved manual debugging, log analysis, and testing across different scenarios to ensure consistent and reliable behavior. Some issues are still actively being debugged, reflecting the complexity of working with real-world system constraints on modern Android platforms.

This project reflects how I approach debugging in practice: isolating variables, validating assumptions, and iterating toward stable behavior in complex systems.

## Tech Stack (High-Level)

- Flutter / Android SDK (API 35)
- Background services & foreground service lifecycle
- Notification channels and system-level behavior
- Audio session handling and media interaction

## Notes

The full implementation is maintained in a private repository. This public repo serves as a high-level overview of the system and the technical challenges addressed.
