# Node-RED 4.1.4 Release Notes

**Release Date:** January 2026

## Overview

Node-RED 4.1.4 is a maintenance release focusing on bug fixes and stability improvements. This release addresses several issues related to error handling, race conditions, and module loading.

## What's Changed

### Bug Fixes

#### Core Runtime
- **Fix uncaught exceptions in core node event handlers** - Prevents uncaught exceptions from crashing the runtime when errors occur in node event handlers
- **Prevent race condition in localfilesystem context store during shutdown** - Ensures reliable context data persistence during Node-RED shutdown
- **Fix double resolve in node close callback** - Resolves an issue where node close callbacks could be called multiple times

#### Node Registry
- **Fix importModule base dir for exports subpaths** - Corrects module loading when using package.json subpath exports, improving compatibility with modern npm packages

#### Nodes
- **Prevent incorrect array modification in delay node** - Fixes a bug where the delay node could incorrectly modify message arrays, resolving potential data corruption issues

#### Editor
- **Revert overflow fix in editableList** - Reverts a previous change that caused unintended side effects in editable list components

#### Dependencies
- **Update tar dependency** - Updates the tar library to address security vulnerabilities

## Contributors

Special thanks to the following contributors who made this release possible:

- @Dennis-SEG - Multiple critical bug fixes
- @yuan-cloud - Module registry improvements
- @knolleary - Release coordination and edits

## Upgrading

To upgrade Node-RED to version 4.1.4:

### Using npm
```bash
npm install -g node-red@4.1.4
```

### Using Docker
```bash
docker pull nodered/node-red:4.1.4
```

## Requirements

- Node.js 18.x or later (Node.js 20.x LTS recommended)

## Full Changelog

For a complete list of changes, see the [full changelog on GitHub](https://github.com/node-red/node-red/compare/4.1.3...4.1.4)

## Known Issues

No new critical issues identified in this release.

## Support

- [Node-RED Documentation](https://nodered.org/docs/)
- [Node-RED Forum](https://discourse.nodered.org/)
- [Node-RED Slack](https://nodered.org/slack/)
- [GitHub Issues](https://github.com/node-red/node-red/issues)
