# Hello, I am Clean Reactive Architecture :wave:

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

Clean Reactive Architecture is a formalized and coherent architecture for
reactive client applications - applications powered by React, Angular, Vue,
Jetpack Compose, SwiftUI, or any framework based on the observer pattern.

Clean Reactive Architecture composes with what teams already use rather than
replacing it.

## Why it matters

- **Technical agility**. The architecture supports technical agility -
  architectural units are small and independent, work splits along interfaces,
  and a change stays contained to the unit responsible for it.  Agile process
  is only part of agile development - technical agility is the rest.

- **Shared understanding**. The architecture and development methodology are
  formalized so that the system is understood in the same way by everyone. A
  developer joining a feature, a teammate picking up another person's work, or
  an AI agent given a task all share the same model and can implement it
  consistently.

- **Cross-platform portability**. The architecture is the same across
  platforms, therefore porting is not redesigning the application but
  reimplementing units against the same diagram using platform-specific tools
  and libraries.

## What's here

- [Architecture](https://github.com/clean-reactive/documentation/blob/main/docs/architecture.md) -
  the units, their responsibilities and dependencies, and the reasoning behind
  them.
- [Development Methodology](https://github.com/clean-reactive/documentation/blob/main/docs/methodology.md) -
  how features are built.

## Samples

The samples implement the same architecture with different frameworks and
libraries. The units, the boundaries do not change - only the tools used to
realize them.

- [One-file React App](https://github.com/clean-reactive/sample-react-one-file) -
  every architectural unit inlined in a single component, each one marked with
  a comment. The whole architecture on one screen, with no file structure in
  the way. The easiest place to start reading.
- [React App](https://github.com/clean-reactive/sample-react-rtk) - React and
  RTK Query.
- [Angular App](https://github.com/clean-reactive/sample-angular-tanstack-query) -
  Angular and TanStack Query.
- [Next.js App](https://github.com/clean-reactive/sample-react-nextjs) -
  full-stack, covering both the client and the server.
- [Flutter App](https://github.com/clean-reactive/sample-flutter) - WIP

> NOTE: These samples are *partially* decomposed, and deliberately so. Some
> units sit in their own files, others stay inlined in the component that uses
> them - each was extracted only where it earned it. This is the state a real
> feature sits in for most of its life, not a way station on the road to
> extracting everything. Reading them as a mandate to give every unit its own
> file from the start is the most common way to misread them. See [Continuous
> refactoring](https://github.com/clean-reactive/documentation/blob/main/docs/methodology.md#continuous-refactoring).

## Status

The architecture and development methodology are stable enough to use by
application architects. Introduction guide for beginners is a work in progress.
Any related discussions, issues, and contributions are welcome.

[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/vv4hCs5P)
