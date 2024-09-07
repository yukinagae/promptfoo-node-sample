# promptfoo-node-sample

`promptfoo-node-sample` demonstrates how to use the [promptfoo](https://www.promptfoo.dev/) package in a Node.js application.

- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Making Changes](#making-changes)
- [License](#license)

## Requirements

Before you start, make sure you have these installed:

- **Node.js** version 22 or later
- **npm**

Check your installations by running:

```bash
$ node --version # the below version is on my environment
v22.7.0
$ npm --version # the below version is on my environment
10.8.2
```

## Setup

**Install Project Dependencies**: Open your terminal, navigate to this project's folder, and run:

```bash
$ npm install
```

## Usage

Before running the project locally, set your OpenAI API key to enable communication with OpenAI's services. Obtain your API key [here](https://platform.openai.com/api-keys) and replace `your_api_key` with the actual key.

```bash
$ export OPENAI_API_KEY=your_api_key
```

## Evaluation

TODO: not implemented

```bash
$ npm run eval
```

## Making Changes

### Building the Project

After making changes, you might need to build the project to see your changes in action:

```bash
$ npm run build
```

### Formatting and Linting

To ensure your code follows the project's coding standards, run the formatting and linting tools:

```bash
$ npm run typecheck # type check without modifying files
$ npm run check     # scan without modifying files
$ npm run fix       # modify files
```

## License

MIT
