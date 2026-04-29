# astral-docs

Public documentation for the [Astral](https://astral.us) autonomous drone
platform. Rendered at [astral.us/docs](https://astral.us/docs) via
[Mintlify](https://mintlify.com).

## Structure

- `introduction.mdx` — what Astral is and what's open vs proprietary.
- `quickstart.mdx` — first-flight guide for hardware customers.
- `mint.json` — Mintlify navigation and theme.

## Local preview

```bash
npm install -g mintlify
mintlify dev
```

Opens on `http://localhost:3000`.

## Contributing

PRs welcome for typos, clarifications, and new pages. For substantive
docs (new SDK methods, hardware features), open an issue first so we can
align on scope.

For SDK code, see [`astral-us/astral-sdk`](https://github.com/astral-us/astral-sdk).

## License

Documentation content is Apache License 2.0. See [LICENSE](./LICENSE).
