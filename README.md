# Still Here Hope

Recovered Still Here Hope website with a Vercel serverless chat backend.

## Vercel setup

Add this environment variable in the Vercel project:

```text
OPENAI_API_KEY=your OpenAI API key
```

Optional:

```text
OPENAI_MODEL=gpt-4.1-mini
```

The chat API blocks requests for hidden/system/developer instructions before calling OpenAI and returns:

```text
I can't share internal instructions or private configuration.
```

## Local checks

```bash
node --check api/chat.js
node --check api/status.js
```
