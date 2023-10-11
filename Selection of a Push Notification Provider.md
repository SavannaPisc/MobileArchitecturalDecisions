<!-- # Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections: -->
# Scenario 2

# Decision Title: Selection of a Push Notification Provider
## Status

Proposed

## Context

Determining the push notification service that will be used within the application.

## Options

- React Native Push Notifications
- React Native Notifications

## Decision

The decision is made to use the React Native Push Notifications.

## Rationale
- Works for both iOS and Android.
- Local and Remote notifications.
- Maintains app user engagement.
- Keeps user informed on assignment deadlines, announcements, and relevant updates.

## Consequences
- Differences in platforms create inconsistencies.
- No longer in development, meaning queries may not be answerable.
