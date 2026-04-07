### My name is Nikita Titov. 
### I am a professional multidisciplinary software development engineer with a primary focus on mobile.

Building [Task Studio](https://tasks.titov.dev/) — a task management & time tracking app. Cross-platform (iOS, Android, macOS, Windows, Linux, Web), Flutter + Django, solo development from architecture to App Store.

- **E2E encryption** — AES-256-GCM, PBKDF2 100K iterations. Encryption key derived from a passcode that never leaves the device, with optional biometric unlock. Developers, admins, and analytics have zero access to private data by design.
- **Optional analytics and crash reporting** - you are asked to choose your preference when creating a new account, and you can change it at any time from Settings → Privacy. If you do not give consent for a particular category (usage analytics or crash reports), the corresponding data is never collected, processed, or transmitted from your device.
- **Offline-first, eventual consistency** — local SQLite as source of truth, cursor-based async sync, real-time WebSocket push.
- **OpenAPI single source of truth** — one spec, auto-generated clients for both Flutter and Django. No hand-written API layer, no data/type conversion errors.
- **No ORM on client** — raw SQLite3, cached prepared statements. Distinct ID types per entity (Dart extension types over String, zero runtime cost) — `TaskIdentityId` can't be passed where `TaskScheduleId` is expected, caught at compile time.
- **Immutable data where possible** — core entities are append-only; mutations create new versions via supersede pattern, preserving full history.
- **3 custom native plugins** — background midnight badge (headless Flutter engine), precise timer notifications, iOS Live Activities.
- **Bare-metal server** — Debian 13 Trixie, 4 cores, 2 GB RAM, Django + Gunicorn (9 workers), PostgreSQL, WebSocket relay (Dart). Stripe-style prefixed IDs (`usr_`, `tmr_`, `tsk_`). No Docker in production.
- **Locked 60fps** — no jank, no shortcuts.

🌿 ˙ · . · ˙ 🌿 ˙ · . · ˙ 🌿 ˙ · . · ˙ 🌿 ˙ · . · ˙ 🌿

🌟 Expert iOS Developer | Swift, Objective-C, Flutter, and React Native  Specialist 🌟
<br/>
<br/>Are you looking for a skilled developer to create high-performing mobile applications?
<br/>
<br/>With 15 years of experience, I specialize in delivering top-tier, cross-platform mobile solutions.

✅ Native iOS Expertise: Swift, SwiftUI & Objective-C. ✅
<br/>
- Proficient in Swift and Objective-C to develop robust, high-quality native iOS applications.
- Extensive experience with UIKit, Core Data, AVFoundation, and In-App Purchases.
- Skilled in using Xcode for development, testing, and AppStore deployment.

✅ Flutter & Dart Development: ✅
<br/>
- Crafting dynamic and responsive cross-platform mobile apps to enhance user experience on both iOS and Android.

✅ React Native & JavaScript/TypeScript: ✅
<br/>
- Building versatile apps using React Native with Redux and Context API for seamless performance.

✅ Custom UI/UX Design: ✅
<br/>
- Designing intuitive and engaging user interfaces for optimal user satisfaction.

✅ Backend Integration: ✅
<br/>
- Proficient in integrating RESTful APIs, Firebase, GraphQL, and more for comprehensive app functionality.

🌟 Proven Success: 🌟
<br/>
- Expertise in managing complex projects from conception to deployment with outstanding results.

🚀 Finally: 🚀
<br/>
### Let’s collaborate to transform your ideas into successful applications!
