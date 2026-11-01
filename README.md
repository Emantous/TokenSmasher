# Brevity

Brevity is a work-in-progress Visual Studio Code extension for reducing token
usage in AI-assisted development workflows.

The project is at an early stage. The extension scaffold is in place, while
the token-reduction functionality is still being designed and implemented.

## Current status

At present, Brevity provides a basic `Hello World` command to verify the
extension lifecycle and development setup. It is not yet ready for production
use or published on the Visual Studio Code Marketplace.

Planned areas of work include:

- identifying redundant or low-value context before it is sent to an AI tool;
- reducing prompts and workspace context while preserving useful information;
- making token savings visible and understandable;
- integrating smoothly with existing VS Code workflows.

## Requirements

- Visual Studio Code `1.140.0` or newer for development and testing;
- Node.js and npm.

## Development

Clone the repository, install dependencies, and open the project in VS Code:

```bash
npm install
code .
```

Press `F5` to launch an Extension Development Host. Open the Command Palette
(`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS) and run **Hello World**.

### Scripts

```bash
npm run lint
npm test
```

The test command runs the extension test suite and the configured lint checks.

## Extension details

The extension currently contributes one command:

| Command | Command ID |
| --- | --- |
| Hello World | `brevity.helloWorld` |

No user settings are currently contributed.

## Contributing

Contributions and ideas are welcome while the project takes shape. Please
focus changes on the extension's core goal: reducing unnecessary token usage
without making AI-assisted development less useful.

Before submitting a change, run:

```bash
npm run lint
npm test
```

## Known limitations

- Token-reduction behavior has not been implemented yet.
- The extension is not published to the Marketplace.
- The command and API surface may change during development.

## License

No license has been declared yet.
