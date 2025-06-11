# Vibes

A repository with GitHub Codespaces configuration that includes Claude Code with API key authentication.

## Setup

1. Fork this repository
2. Launch your Codespace by clicking "..." then "New with options..."
3. Enter your anthropic api key and be sure to choose "US West" or "Southeast Asia" as the region for a fast startup.

You can also set your `ANTHROPIC_API_KEY` environment variable directly in GitHub Codespaces secrets:
   - Go to [GitHub Codespaces Settings](https://github.com/settings/codespaces)
   - Click "New secret"
   - Name: `ANTHROPIC_API_KEY`
   - Value: Your API key from [Anthropic Console](https://console.anthropic.com/keys)

## Using Claude Code

Once your Codespace is set up with your API key, simply use Claude Code with:

```bash
claude
```

Or with a specific question:

```bash
claude "What does this repository do?"
```

## Troubleshooting

If you see a warning about missing API key when the Codespace starts:

1. Follow the on-screen instructions to set up your API key
2. After adding the secret, you may need to rebuild your Codespace for it to take effect
3. Alternatively, you can set the key for your current session with:
   ```bash
   export ANTHROPIC_API_KEY=your-api-key-here
   ```