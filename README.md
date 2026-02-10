# Lockstride Kickoff Plugin (Distribution)

This repository contains the distribution package for the [Lockstride Kickoff](https://github.com/lockstride/kickoff) Claude Code plugin.

## What is this?

This is a lightweight distribution repository containing only the plugin files needed for installation. It's automatically synced from the `plugin/` directory of the main [kickoff repository](https://github.com/lockstride/kickoff).

## Why a separate repo?

To enable clean HTTPS-based installation without requiring users to clone the entire development repository (which includes tests, documentation, and build tooling).

## Installation

Within Claude Code:

```
/plugin marketplace add lockstride/claude-marketplace
/plugin install lockstride-kickoff@lockstride-marketplace
```

## Learn More

For full documentation, features, and development details, see the main repository:

**[https://github.com/lockstride/kickoff](https://github.com/lockstride/kickoff)**

## License

MIT - see [LICENSE](LICENSE) file for details.
