# Gemma

A terminal chat companion powered by Gemini API.

## Features
- Persistent memory across conversations
- Multi-key and multi-model rotation with auto-fallback
- Web search enabled by default

## Setup
1. Clone the repo
2.fill your Gemini API keys
3. Run with `node gemini-chat.js`

## Commands
| Command | Description |
|---|---|
| `/mode search` | Use relevant memory per message |
| `/mode digest` | Summarize all memory as context |
| `/memory` | View stored memory |
| `/clear` | Clear memory |
| `/status` | Show active model and key |
| `/exit` | Exit |

## Data
Conversation history and memory are stored locally in `gemini_data/`.