# swiftlint-config

> Good starter config for [SwiftLint](https://github.com/realm/SwiftLint)

SwiftLint has a lot of [rules](https://github.com/realm/SwiftLint) and it takes time to adjust them to something sensible.

## Usage

1. Create a `.swiftlint.yml` file in the root of your project with the following:

```
parent_config: https://raw.githubusercontent.com/sindresorhus/swiftlint-config/main/.swiftlint.yml
```

*(Replace `main` with a specific commit hash if you want predictable builds)*

2. Follow the [SwiftLint setup instructions](https://github.com/realm/SwiftLint#installation).
