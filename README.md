# Rescuel

A native Android safety app for riders with live GPS tracking, crash detection, SOS alerts, and access to nearby medical facilities.

## Features

- **Live Cockpit** — Real-time speed, distance, and trip duration
- **Crash Detection** — Automatic impact detection with SOS countdown
- **Smart SOS Routing** — Instant alerts to emergency contacts with location
- **Medical Map** — Locate nearby hospitals in real time
- **Secure Auth** — Email and password-protected accounts
- **Dark UI** — High-contrast interface optimized for riding
- **Multilingual** — 9 languages: English, Hindi, Marathi, Gujarati, Spanish, Chinese, Japanese, Tamil, Malayalam

## Quick Start

### For Riders
1. Download APK from [releases](https://pranshupujara.github.io/Rescuel/)
2. Enable "Install unknown apps" on your Android device
3. Install and sign up with your email
4. Add emergency contacts and start riding

### For Developers
```bash
git clone https://github.com/PranshuPujara/Rescuel.git
cd Rescuel
./gradlew assembleRelease
```

## Requirements

- Android 6.0 (API 23)+
- Permissions: Location, Background activity, Vibration
- Active internet connection

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript
- Mobile: Android (Java/Kotlin)
- Tracking: GPS + motion sensors
- Maps: Google Maps API
- Auth: Firebase

## Security

- Location data encrypted in transit
- Emergency contacts only shared during SOS events
- Users retain full data control
- Tracking only active during rides


## License

© 2026 Rescuel. All rights reserved. Built by **Team Neurobyte**.

## Support

- Issues: [GitHub Issues](https://github.com/aumsantoki99-web/Rescuel/issues)

---

**Stay Safe. Ride Smart. Always Covered.**
