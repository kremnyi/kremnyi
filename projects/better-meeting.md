---
title: "Better Meeting: macOS recording and local transcription"
description: "Independent SwiftUI macOS app adapted from GivenFLY’s Better Meeting, with on-device transcription, recoverable processing, and Homebrew releases."
author: "Bohdan Kremnyi"
---

# Better Meeting: macOS recording and local transcription

I built and released a native Swift/SwiftUI adaptation of [GivenFLY’s Better Meeting](https://github.com/GivenFLY/better-meeting). It records meetings from the macOS menu bar, transcribes them on device, and keeps the recording and review files together in one folder per meeting.

[Source code](https://github.com/kremnyi/better-meeting) · [Download for macOS](https://github.com/kremnyi/better-meeting/releases/latest)

## Recording and processing

The original project provided a workflow for extracting transcripts and screen content from recordings. I built a native macOS application around that workflow, using ScreenCaptureKit for screen, system-audio, and microphone capture, and WhisperKit for local speech recognition.

The interface includes recording controls, audio meters, processing progress, and searchable meeting history. Recordings stay on the Mac. Speech models require an initial download; transcription then runs on device.

## Recovering interrupted work

Multilingual processing can take time. Completed language passes are cached so a retry can reuse them. The app checks the audio file, model, and decoding settings before reusing a result.

Re-transcription keeps the existing transcript until the replacement is ready. If processing fails or is cancelled, the previous transcript remains available. This also protects manually edited transcripts from a failed replacement attempt.

## Reviewing the meeting

The app exports timestamped transcripts in Markdown and JSON, alongside screenshots and text extracted with Apple Vision. A timeline brings speech and screen content together for review. These files can be opened and reused outside the app; meeting content is not uploaded by the application.

## Distribution

Published Apple Silicon builds for macOS 15 and later through GitHub Releases and a Homebrew cask. macOS CI runs the Swift tests and app build. Release packaging includes signature verification and a checksum; the current releases are self-signed.

## Attribution

This is an independent open-source project. The original extraction workflow and multilingual merging approach come from GivenFLY’s Apache-2.0 project. My work covers the native macOS application, processing integration, recovery behavior, and distribution. Speech recognition uses Argmax’s WhisperKit and Whisper models.

## Technology

Swift, SwiftUI, ScreenCaptureKit, AVFoundation, WhisperKit, Core ML, Vision, Homebrew, GitHub Actions.
