# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Pre-installation instructions in README.md for required library dependencies
- Support for React Native 0.80.0
- Support for Gradle 8.14.2
- Support for React 19.1.0

### Changed
- Upgraded React Native from 0.69.12 to 0.80.0
- Upgraded Gradle from 7.6.1 to 8.14.2
- Upgraded React from 18.0.0 to 19.1.0
- Updated Android build tools to version 34.0.0
- Updated Android SDK versions to 34
- Updated NDK version to 26.1.10909125
- Updated Android Gradle Plugin to 8.4.0
- Updated Java compatibility to version 17
- Added namespace declaration in app build.gradle
- Updated gradle.properties with React Native 0.80 compatible settings
- Updated all development dependencies to compatible versions

### Fixed
- Removed deprecated MaxPermSize JVM option for Java 17 compatibility
- Fixed dependency conflicts with React Native 0.80

### Technical Details
- Updated package.json with React Native 0.80 compatible dependencies
- Updated metro-react-native-babel-preset to 0.77.0
- Updated @react-native-community/cli to 18.0.0
- Added new React Native 0.80 specific gradle properties
- Configured parallel builds and optimized JVM settings 