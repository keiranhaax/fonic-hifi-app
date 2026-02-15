# Changelog

All notable milestones for Fonic HiFi are documented here.

## [0.5.0] — 2026-02-06
### Improved
- Refined home screen with Liquid Glass album sheets
- Audio session sample rate alignment with source playback
- Simplified album expansion UI
- Decomposed diagnostics architecture with full orchestrator test coverage
- Raised test coverage to 40%+ across app target

## [0.4.0] — 2025-12-07
### Added
- On-device AI-powered music recommendations using Apple Foundation Models
- Smart search with natural language queries and AI-generated explanations
- Home screen discovery: Continue Listening, Rediscover, time-based greetings
- Listening session history tracking
- Album color extraction for dynamic UI theming
- Artist, genre, and album browsing sections

## [0.3.0] — 2025-12-06
### Added
- 10-band parametric equalizer with persistence and true bypass
- Playback speed control with AVAudioUnitTimePitch
- Gapless playback via dual-player architecture
- A-B loop controls with visual markers on progress slider
- Queue management view
- Lyrics display
- Favorites system
- Now Playing overflow menu consolidation
- Resume playback from last position on app launch

## [0.2.0] — 2025-09-30
### Added
- iOS 26 Liquid Glass UI migration
- Comprehensive Makefile build system
- SwiftLint and SwiftFormat integration
- Domain layer with repository pattern

### Improved
- Swift 6.2 strict concurrency compliance
- Complete project structure reorganisation
- Stabilised audio engine switching and error handling

## [0.1.0] — 2025-05-29
### Added
- Initial audio engine with AVAudioEngine and AudioKit adapters
- Multi-format support: FLAC, ALAC, WAV, AIFF, MP3, AAC
- Bit-perfect playback up to 32-bit/384kHz
- SwiftData-backed music library with actor-based persistence
- File import and metadata extraction
- Basic Now Playing UI with playback controls
- Settings interface
- Privacy-first architecture — no network, no analytics
