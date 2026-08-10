# Free-forever-API

A free, forever-free API collection. All endpoints are free to use, no registration required.

## Endpoints

- `GET /v1/models` — list available models
- `POST /v1/chat/completions` — chat completion (OpenAI-compatible)
- `POST /v1/responses` — responses API (OpenAI-compatible)

## Models

| Model | Description |
|-------|-------------|
| DeekSeep-V4-pro | Flagship model, deep reasoning |
| DeekSeep-V4-Flash | Fast responses, light tasks |
| Claude Mythos 5 | Anthropic myth series |
| Claude Opus 5 | Top-tier understanding |
| Claude Fable 5 | Creative storytelling |
| GPT-5.6 Sol | OpenAI solar series |
| GPT-5.6 Luna | OpenAI lunar series |
| Kimi K3 | Moonshot latest |
| GLM-5.2 | Zhipu AI general model |

## Quick Start

```bash
curl https://example.com/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{"model": "DeekSeep-V4-pro", "messages": [{"role": "user", "content": "Hello"}]}'
```

## License

MIT
