---
layout: page
title: What's New
include_in_header: false
---

# Changelog

# 1.6.0

- Add URL-based navigation on Flutter web
- Updated Flutter web splash screen
- Error reporting improvements

# 1.5.0

- Update to the latest packages
- Updated splash screen on Android

# 1.4.9

- Fixed issue with force update prompt timing during app startup
- Update to flex_color_scheme 8.2.0

# 1.4.8

- Update to the latest packages
- Disable Impeller on Android due to a bug that causes flickering on gif images

# 1.4.7

- Replace Crashlytics with Sentry for error reporting
- Update to the latest packages

# 1.4.6

- Replace Sentry with Crashlytics for error reporting (for evaluation purposes)

# 1.4.5

- Fixed a bug in the initialization logic

# 1.4.4

- Add A/B testing support
- Update to the latest packages

# 1.4.3

- Update to the latest packages

# 1.4.2

- New keyboard shortcuts: left/right to navigate between tips, space to like a tip
- Enabled "Mac (Designed for iPad)" as a supported device

# 1.4.1

- Full iPad support with content and navigation panes on the same screen
- Updated to the latest packages
- Other small improvements

# 1.4.0

- Added basic iPad support
- Use tabular figures for tip numbers in the image preview page

# 1.3.2

- Fixed a bug with the image preview transition

# 1.3.1

- Update to the latest packages
- Use tabular figures for tip numbers
- Small bug fixes

# 1.3.0

- Updated to the latest packages
- Small bug fixes
- New Screenshots

# 1.2.8

- Update Privacy Manifest
- Update theming logic

# 1.2.7

- Updated to the latest packages
- Improved Firebase initialization code

# 1.2.6 

- Fixed a big in the Markdown parsing logic

# 1.2.5

- Add option to show licenses in the settings

# 1.2.4

- Improved analytics

# 1.2.3

- Improved image preview
- Updated screenshots

# 1.2.2

- Fix for image preview transition when the image could not be loaded
- Add GitHub workflow for iOS
  
# 1.2.1

- More error handling tweaks

# 1.2.0

- More robust error handling

# 1.1.20

- Improved the force update logic

# 1.1.19

- Updated all packages and dependencies

# 1.1.18

- Handle 401 Unauthorized errors
- More improvements for the force update logic
- Update to Flutter 3.24 and the latest packages

# 1.1.17

- Improved the force upgrade logic

# 1.1.16

- Fix for the pull-to-refresh UI

# 1.1.15

- Add a little easter egg - see if you can discover it 😉

# 1.1.14

- Add refresh indicator to individual tips
- Improved analytics code

# 1.1.13

- Add Posthog for analytics tracking
- Track screen view analytics
- Improved logging

## 1.1.12

- Cleanup analytics
- Targeting Android 14 (API level 34)

## 1.1.11

- Analytics improvements
- Updated packages
- Updated minimum iOS deployment version to 13.0

## 1.1.10

- Improve app startup logic
- Fix a scrolling bug on Flutter web

## 1.1.9

- Fix critical bug that was preventing new tips from loading

## 1.1.8

- Replace Crashlytics with Sentry on iOS, Android builds
- Fixed zone mismatch error on Flutter web
- Fixed "feedback" does not work with Flutter HTML renderer error

## 1.1.7

- Increased text sizes and paddings
- Use kIsWeb and defaultTargetPlatform for platform checks
- Improved error monitoring setup
- Only show feedback button on non-web builds
- Upload source maps to Sentry for web builds
- Don't report exceptions from feedback package

## 1.1.6

- Add Flutter web support
- Updated the launch screen

## 1.1.5

- Updated the launch screen

## 1.1.4

- Updated to the latest packages

## 1.1.3

- Changed the app icon

## 1.1.2

- Updated to the latest packages

## 1.1.1

- Made the app work better in offline mode

## 1.1.0

- Added favorites filter to the search screen
- Added empty placeholder for the search screen
- Improved app rating prompt logic

## 1.0.4

- About page has been renamed to Settings page
- Show a confirmation dialog before clearing the cache
- Improved anonymous data collection

## 1.0.3

- Fixed app upgrade logic

## 1.0.2

- Double tap to toggle zoom on the image viewer
- Improved accessibility labels and tooltips
- Other minor tweaks

## 1.0.1

- Added theme selector to about page
- Use bigger font for H3 markdown headings

## 1.0.0

This is the first release of the app, which offers these features:

- Browse over 150 tips and tricks about Dart and Flutter app development
- Search existing tips or choose a random tip
- Save your favourite tips
- Get access to additional resources, articles and videos about Flutter
- Offline mode: once downloaded, the tips are saved locally so you can access them at any time, even when you don't have a network connection
- Image viewer: tap, pinch and zoom on any image
- Light/dark mode, based on your system preferences
