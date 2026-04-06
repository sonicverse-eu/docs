# Sonicverse Docs

Documentation for [Sonicverse](https://sonicverse.eu) — open-source software for independent media.

Powered by [Mintlify](https://mintlify.com).

## Projects

- **[Audio Streaming Stack](https://sonicverse.eu/audiostreaming-stack)** — Self-hosted Docker Compose stack for live radio streaming. Ingest from any studio encoder and deliver via Icecast2 and HLS adaptive bitrate, with automatic fallback, silence detection, analytics, alerts, and a real-time operator dashboard.

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the following command at the root of this repository, where `docs.json` is located:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

To check for broken links:

```bash
mint broken-links
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on editing pages, local development setup, and submitting pull requests.

## Publishing

Changes pushed to the default branch are deployed to production automatically via the Mintlify GitHub app.

## Resources

- [Sonicverse GitHub](https://github.com/sonicverse-eu)
- [Sonicverse OSS Slack](https://join.slack.com/t/sonicverse-oss/shared_invite/zt-3u969i5rr-cmfgEycFAi8V7Baj0uBx0A)
- [Mintlify documentation](https://mintlify.com/docs)

## Troubleshooting

- If your dev environment isn't running: run `mint update` to get the latest CLI version.
- If a page loads as a 404: make sure you are running from the folder containing `docs.json`.

## License

This documentation repository is licensed under the [MIT License](LICENSE).
