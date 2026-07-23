# Larry Bulen — Senior iOS / Mobile Engineer

**Swift · SwiftUI · UIKit · Objective-C · Kotlin · Kotlin Multiplatform**

I've spent 13 years building native iOS apps (and 10 alongside them on Android) across ag-tech, health, and fintech — most recently at Corteva Agriscience, developing two production iOS/Android apps for agricultural customers. I care about the layer other engineers build on: modular Swift Package Manager libraries, shared UI components, and test suites that keep pace with the platform (XCTest → Swift Testing).

## 🤖 Recent builds (2026)

The same engineering discipline — seams at the I/O boundary, tagged smoke/sanity/regression suites, honest failure UX — applied three ways:

| Project | What it shows |
|---|---|
| [**MyAIAgent**](https://github.com/lbulendev/MyAIAgent) | An agentic AI worker, built natively twice (Swift 6/SwiftUI + Kotlin/Compose): token-streamed replies over raw SSE, a client-side tool-orchestration loop against a mock CRM, an explicit agent state machine, offline resume with a replay-safe invariant, and a simulated text-to-pay flow. Mirrored test suites, 30 iOS / 29 Android. |
| [**HeartChart**](https://github.com/lbulendev/HeartChart) | Live BLE heart-rate charting for chest straps — standard GATT (no vendor SDK), Swift 6/Swift Charts/CoreBluetooth with a Kotlin/Compose mirror, and a connection state machine unit-tested without any Bluetooth. |
| [**TheMovieDBSwift**](https://github.com/lbulendev/TheMovieDBSwift) | My 2017 UIKit app modernized to Swift 6/SwiftUI/MVVM: natural-language search parsing (built for an LLM drop-in), Siri App Intents that drive the live UI, and committed test plans. A migration story in miniature. |

## 📱 Shipped apps

| App | Role | Links |
|---|---|---|
| **Granular Insights** (iOS / Android) | Senior Software Engineer — Mobile, Corteva/Granular | [App Store](https://apps.apple.com/us/app/granular-insights/id6745721003) |
| **Granular Insights Classic** (iOS / Android) | Senior Software Engineer — Mobile, Corteva/Granular | [App Store](https://apps.apple.com/us/app/granular-insights-classic/id1447163449) |
| **Granular Business** (iOS / Android) | Software Engineer — Mobile, Granular | — |
| **Epocrates Essentials** (iOS) | Mobile Developer, Athenahealth — #1 mobile medical reference, 1M+ active users | — |
| **Maverick's Solitaire** (iOS) | Personal project — sole designer, developer, and publisher | [App Store](https://apps.apple.com/us/app/mavericks-solitaire/id1513061865) |

## 🔧 How I build

- **UI:** SwiftUI and UIKit (Storyboards, XIBs, programmatic + Auto Layout), working from Figma specs with design partners
- **Architecture:** Composable Architecture (TCA), MVVM, Swift Concurrency (async/await), SwiftData, Kotlin Multiplatform shared modules (~70% shared code), Jetpack Compose
- **Quality:** Swift Testing / XCTest / JUnit 5, modularization for testability, GitLab CI/CD and Bitrise pipelines, LaunchDarkly feature flags
- **AI:** agentic tooling daily (Claude Code certified) with generated code reviewed and tested before it ships — and now agentic features *in* the product: MyAIAgent above streams the Claude API with client-side tool use on both platforms. See also [Claude-Commands-and-Skills](https://github.com/lbulendev/Claude-Commands-and-Skills)

## 🔗 Elsewhere

- [LinkedIn](https://www.linkedin.com/in/larry-bulen-0b64472)
- 📫 lbulendev@gmail.com
