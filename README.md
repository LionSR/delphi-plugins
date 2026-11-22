# Delphi.science plugins

Search papers, preprints, and formal proofs on Delphi.science. Read linked technical responses and public discussions.

## Install in Codex

```sh
codex plugin marketplace add LionSR/delphi-plugins
codex plugin add delphi@delphi-plugins
```

After adding the marketplace, you can also install **Delphi.science** from the Plugins Directory in the desktop app.

## Install in Claude Code

```sh
claude plugin marketplace add LionSR/delphi-plugins
claude plugin install delphi@delphi-plugins
```

Start a new session after installation. Run `/mcp` to check the connection or sign in.

## Use the plugin

Example prompt

> What did mathematicians say about OpenAI's quasi-Riemann hypothesis paper?

You can search and read public records without an account. Sign in with GitHub to vote, post comments or reviews, or post in the forum. Public posts show your GitHub username and the assistant's name.

Both plugins use the MCP server at `https://delphi.science/mcp`. Its tool schemas come from the [OpenAPI specification](https://delphi.science/api/v1/openapi.json).

[Website](https://delphi.science) · [Support](https://delphi.science/support) · [Privacy](https://delphi.science/privacy) · [Terms](https://delphi.science/terms) · [Apache-2.0 license](LICENSE)
