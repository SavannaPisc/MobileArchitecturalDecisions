<!-- # Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections: -->
# Scenario 2

# Decision Title: Selection of Data Privacy and Security Measures
## Status

Proposed

## Context

Determining the data transmission protocols and security measures that will be put into place.

## Options

- React Native Encrypted Storage
- SSL Encryption
- Jscrambler
- JSDefender
- Formik
- Use a variety of security measures together

## Decision

The decision is made to use React Native Encrypted Storage, SSL encryption, and Formik to ensure layered protection for users.

## Rationale
- Works for both iOS and Android.
- Layered protection to ensure user data security.
- Encrypts stored data, including student grades and personal information.
- Validates and sanitizes user input.
- Protects against many common security breaches, including SQL injections.

## Consequences
- Difficulties in implementing all security measures simultaneously.
- Increase in development time for security configuration.
