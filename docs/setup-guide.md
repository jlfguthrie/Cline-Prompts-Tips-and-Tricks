# Setup notes

These notes describe how to use the examples in this repository. For current installation requirements, provider configuration and Cline features, see the [official documentation](https://docs.cline.bot/).

## Start with a working Cline installation

Install Cline using its official instructions and configure the provider you intend to use. Check that you can open a project and ask a small question about its code before adding extra configuration.

## Project instructions

Read the [starter instructions](../configs/starter-clinerules.md) and adapt them to your project's languages, conventions and verification commands. Remove rules that do not apply.

Cline supports project guidance through `.clinerules`. Use its Rules interface or the format described in the current documentation to add your instructions. Do not overwrite existing project rules without reviewing them.

## Project context

The [project brief](../configs/memory-bank-template/project-brief.md) and [technical context](../configs/memory-bank-template/tech-stack.md) templates can be copied into your project's documentation. Replace the example content with facts about your system, and tell the assistant which files to read.

Keep credentials and private customer data out of shared templates.

## First task

Try the project orientation example in the [prompt collection](../prompts/README.md). Then choose a small, well-defined change and check its diff and relevant behaviour.

## Tool connections

Add MCP servers or other integrations only when the task needs them. Follow the tool provider's current setup instructions and review the access it requests. This repository does not bundle or maintain an MCP server.

## Troubleshooting

- For authentication and provider errors, check the configured account, model access and provider response.
- For missing context, identify the relevant files explicitly and keep project notes current.
- For unexpected changes, inspect the diff and reduce the next task's scope.
- For Cline configuration issues, consult the official documentation rather than relying on version-specific settings from older examples.
