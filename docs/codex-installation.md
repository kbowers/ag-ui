# Installing `@openai/codex`

Attempting to install the legacy `@openai/codex` package globally with:

```bash
npm install -g @openai/codex
```

currently returns a `403 Forbidden` error from the npm registry. This indicates that the
package is not available for public installation.

If you need Codex functionality, use the [OpenAI API](https://platform.openai.com/docs/api-reference)
with a supported model instead of the deprecated package.
