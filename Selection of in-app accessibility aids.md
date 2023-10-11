<!-- # Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections: -->
# Scenario 2

# Decision Title: Selection of In-app Accessibility Features

## Status

Proposed

## Context

Determining the accessibility aids that the application will offer to users.

## Options

- Google Cloud Speech to Text
- React-Native-TTS library
- High contrast modes
- Support for assistive technologies
- Implement multiple features using Google Cloud Speech to Text, high contrast modes, and support for assistive technologies
- Implement multiple features using React-Native-TTS library, high contrast modes, and support for assistive technologies

## Decision

The decision is made to use the React-Native-TTS library for text-to-speech implementation, along with the use of high contrast modes and a support for assistive technologies.

## Rationale
- Enables a wide variety of users to effectively interact with the appplication.
- Works for both iOS and Android.
- Able to use some text-to-speech features offline.
- Multiple accessibility features ensure the useability of the application in any environment.

## Consequences
- Differences between platforms creates lack of consistency.
