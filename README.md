# Prompt Tester for OpenAI Text APIs

A Next.js prompt testing workspace for OpenAI chat conversations, prompts, folders, imports, exports, and model settings.

Live: [https://prompt-tester-for-open-ai-text-api-s.vercel.app](https://prompt-tester-for-open-ai-text-api-s.vercel.app)

## Mission

Prompt testing should be quick, local, and inspectable. This fork keeps a practical UI for saving conversations, managing prompt templates, trying model settings, and exporting work while preserving the MIT-licensed Chatbot UI foundation.

## What This Repository Contains

Next.js 13 chatbot interface built from Chatbot UI, with OpenAI model calls, conversation and prompt sidebars, folders, import/export, i18n, markdown rendering, syntax highlighting, Docker, tests, and deployment examples.

## Highlights

- Chat with OpenAI text/chat models.
- Store and search conversations, prompts, and folders in the browser.
- Import and export prompt testing data.
- Render markdown, math, and code blocks across multiple locales.

## Tech Stack

- Next.js 13 and React 18
- TypeScript
- Tailwind CSS
- OpenAI SDK
- next-i18next
- Vitest
- Docker and Kubernetes manifests

## Getting Started

```bash
npm install
cp .env.local.example .env.local
npm run dev
```

## Quality Checks

```bash
npm run lint
npm run test
npm run build
```

## Repository Notes

- This project is based on MIT-licensed Chatbot UI by Mckay Wrigley; preserve original copyright notices.
- Keep OpenAI API keys in .env.local or deployment secrets only.

## Contributing

Contributions are welcome. The best contributions are specific, tested, and grounded in the product mission. Good places to help include documentation, accessibility, tests, bug reports, UI polish, data validation, and safer AI behavior.

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## Security

Please do not open public issues for secrets, auth bypasses, data exposure, provider key leaks, or abuse vectors. Follow [SECURITY.md](SECURITY.md).

## Code of Conduct

This project follows [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Be direct, kind, and useful.

## License

MIT. See [LICENSE](LICENSE).
