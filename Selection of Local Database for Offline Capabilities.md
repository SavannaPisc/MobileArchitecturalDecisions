<!-- # Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections: -->
# Scenario 2

# Decision Title: Selection of Local Database for Offline Capabilities

## Status

Proposed

## Context

Determining the offline capabilities and data synchronization mechanisms for seamless user experience across platforms.

## Options

- Realm
- Firebase
- SQLite

## Decision

The decision is made to use the Realm local database in tandem with React Native

## Rationale
- Runs in the background, collecting and saving user data and services as they interact with the application.
- Employs variety of encryption security measures to ensure safety of data stored.
- Open-source and regular version is free.
- Easy use of React Hooks API.
- Faster than many alternatives.
- Simple incorporation into projects.

## Consequences
- If requiring the pro version, a payment of $1,750 a month must be made.
- Unable to request to merge database tables.
- Not suitable for complex, large-scale applications.
