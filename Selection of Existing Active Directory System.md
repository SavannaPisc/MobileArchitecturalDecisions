<!-- # Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections: -->
# Scenario 2

# Decision Title: Selection of Existing Active Directory System.

## Status

Proposed

## Context

Determining the Active Directory system to be used for securing user data.

## Options

- Active Directory Authentication Library
- Microsoft Authentification Library

## Decision

The decision is made to use the Active Directory Authentication Library.

## Rationale
-  Consistent between both iOS and Android.
-  Easy to configure and use.
-  Provides basic authentification functions for professor roles and permissions.

## Consequences
-  Needs a working CocoaPods installation.
