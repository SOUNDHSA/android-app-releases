# Changelog

All notable changes to Sound HSA are documented in this file.

## [1.0.4] - 2026-03-04

### Added

#### Lightning Wallet (Breez SDK)
- Full Bitcoin Lightning wallet integration via Breez SDK (upgraded to v0.10.0)
- Send and receive Lightning payments with QR code scanning
- Lightning address registration via LNURL
- Transaction list with status tracking (pending, complete, failed)
- Transaction details screen with memo fetching and date formatting
- Payment observer service for real-time payment event handling
- SDK compatibility check before wallet operations
- Conversion details (BTC/USD) attached to all payment records
- Responsive font scaling in wallet components

#### HSA Dashboard & Charts
- Connecting existing HSA with the mobile app
- Interactive HSA chart with touch-based scrubbing for BTC and USD savings cards
- Haptic feedback on chart interactions
- Animated price updates and live tooltip with date display
- Balance history fetching with Bitcoin price integration
- Pull-to-refresh on dashboard
- Updated total HSA value calculation

---

## [0.3.11] - 2025-09 (baseline)

### Features at this version

- Nostr account creation and management
- Basic HSA tab, offers screen, and earn-steps screen
- Apple HealthKit / pedometer step tracking with 7-day average
- Push notification subscription and encrypted server exchange
- Amplitude analytics with NPUB SHA256 identification
- Waitlist subscription flow
- Basic login and signup screens
- Nostr relay publishing via pool
