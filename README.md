
## Purpose

Quick & dirty CLI clone of ChatGPT that requires an OpenAI key.

Allows you to experiment with the API and various techniques such as preprocessing, postprocessing, and chaining, and so on

## Prerequisites

- *nix terminal or WSL for Windows
- Docker
- VS Code with `devcontainers` extension installed
- An OpenAI API key

## Instructions

1. Clone this repository from your terminal:

```sh
git clone git@github.com:bill-c-martin/chatgpt-cli-clone.git
```

2. Open in VS Code:

```sh
cd chatgpt-cli-clone && code .
```

3. Open the VS Code command pallete (`Ctrl+Shift+P`) and entering `Dev Containers: Reopen in container`
4. Open a new terminal window within VS Code itself
5. Run `npm install`
6. Add your OpenAI key to an `OPENAI_API_KEY` variable in a newly-created `.env` file, replacing `your-key-here` with your actual OpenAI API key:

```sh
echo "OPENAI_API_KEY=your-key-here" > .env
```

7. Finally, start the ChatGPT CLI clone by runnning: `node index.js`