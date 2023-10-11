<!-- # Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections: -->
# Scenario 2

# Decision Title: Selection of Techniques to Enhance App Compatibility and Minimize Data Usage

## Status

Proposed

## Context

Determining the techniques established to maximize optimization and data usage across a range of devices and platforms.

## Options

- RESTful API
- React Query
- ReduxToolKit Query
- GraphQL

## Decision

The decision is made to use the React Query API.

## Rationale
- Data handling focus.
- Array of resources from a commited community.
- Provides a more responsive user experience.
- Able to debug and inspect application queries and cache.
- Ensures data is constantly up-to-date.
- Reduces number of API requests for a single piece of data.
- Reduces data usage.

## Consequences
- Not suitable for complex, large-scale applications.
- Not optimized for updating data.
