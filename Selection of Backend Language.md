<!-- # Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections: -->
# Scenario 2

# Decision Title: Selection of Backend Language
## Status

Proposed

## Context

Determining the data transmission protocols and security measures that will be put into place.

## Options

- Python
- Java
- Javascript
- Ruby
- C#
- NodeJS

## Decision

The decision is made to use NodeJS as the backend language.

## Rationale
- Works effectively with React Native.
- Server-side JavaScript runtime.
- Scalable and quick running.
- Reusable components reduce development time.

## Consequences
- Complexity in Node.js learning curve can cause development time to be increased.
- Can lead to complex and hard to read code.
