# unofficial-llmstxt

This repository provides a collection of **unofficial `llms.txt` files** for open-source projects and documentation sites that have not yet adopted an official `llms.txt`. The goal is to help the community accelerate adoption of the [llmstxt standard](https://llmstxt.org/llms.txt) by offering ready-to-use files for popular tools and frameworks.

## What is `llms.txt`?

[`llms.txt`](https://llmstxt.org/llms.txt) is a proposed standard for declaring how Large Language Models (LLMs) should interact with a website or project. It is similar in spirit to `robots.txt`, but specifically designed to communicate LLM-related preferences, permissions, and guidelines to AI systems and their operators.

For more details, see the [official llmstxt specification](https://llmstxt.org/llms.txt).

## Repository Structure

Each subdirectory under [`llmstxt/`](llmstxt/) contains an **unofficial `llms.txt`** file for a specific open-source tool or framework. For example:

- [`llmstxt/adonisjs/`](llmstxt/adonisjs/)
- [`llmstxt/n8n/`](llmstxt/n8n/)
- [`llmstxt/react-hook-form/`](llmstxt/react-hook-form/)
- [`llmstxt/tanstack/`](llmstxt/tanstack/)

Each directory may also include a brief README describing the context or rationale for the provided file.

## Motivation

Many open-source projects have not yet published an official `llms.txt`. This repository aims to:

- Encourage adoption of the llmstxt standard.
- Provide maintainers and the community with a starting point for their own `llms.txt`.
- Make it easier for projects to communicate LLM-related policies and preferences.

## Contributing

Contributions are welcome! If you would like to add an unofficial `llms.txt` for a project not yet covered here:

1. Create a new subdirectory under `llmstxt/` named after the project.
2. Add your proposed `llms.txt` file in that directory.
3. Optionally, include a short README explaining your choices.
4. Open a pull request.

Please ensure your contributions are clearly marked as unofficial and follow the [llmstxt specification](https://llmstxt.org/llms.txt).