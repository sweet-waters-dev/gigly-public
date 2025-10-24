# gig.ly
[![iOS CI (macOS 26 / Xcode 26)](https://github.com/sweet-waters-dev/gig.ly/actions/workflows/ios-ci.yml/badge.svg?branch=main)](https://github.com/sweet-waters-dev/gig.ly/actions/workflows/ios-ci.yml)

gig.ly is a SwiftUI-based mobile app designed to help gig workers track and analyze Instacart, DoorDash, and other gig economy data. *

## Features (planned)
- Batch/order logging
- Pay, mileage, and time tracking
- Data dashboards + charts
- Export / sync support

## Tech Stack
- SwiftUI
- Xcode
- GitHub + Jira integration

## Setup
1. Clone the repository
2. Open `gig.ly.xcodeproj` in Xcode
3. Run on iOS Simulator or device

## Contributing
Work is managed in Jira (linked).  
Branching strategy: TBD (see GIG-31).

## Build & Run

**Requirements**
- macOS (Apple silicon or Intel)
- Xcode 15 or newer
- iOS 17.0+ deployment target (adjust in project settings if needed)

**Quick start**
1. Clone the repo:
  ```bash
  git clone https://github.com/sweet-waters-dev/gig.ly.git
  cd gig.ly
2. Open in Xcode: Gigly.xcodeproj
3. Select an iPhone simulator (e.g., iPhone15) and press ⌘ to run.

**Notes**
- Dependencies: Swift Package Manager only (no Pods yet).
- If you hit signing errors on device, set your *Team* under project Signing & Capabilities.
