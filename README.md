# Spellar for Cursor

Connects Cursor to your [Spellar](https://spellar.ai) account through Spellar's MCP server, so the agent can answer from your meetings and keep them up to date.

## What it can do

**Read:** meetings with their summaries and notes, transcripts with speakers and timestamps, action items, weekly recaps, folders and tags, upcoming calendar events, and search across everything you have recorded.

**Change, only if you allow it when connecting:** mark an action item done or edit it, add a note to a meeting, rename, tag or file a meeting, create a share link. Each is a separate choice on the consent screen. Nothing can be deleted.

## Setup

1. Install the plugin. It adds one MCP server: `https://mcp.spellar.ai/mcp`.
2. Cursor opens Spellar's sign-in and consent page in your browser. Sign in and choose "Allow access".

There is nothing else to configure: no API key, no local process. You need a Spellar Pro account.

To disconnect, open Spellar → Settings → AI assistants and remove Cursor.

## Example prompts

- "Find the meeting where we discussed pricing and tell me what was agreed."
- "What are my open action items, and which meeting did each come from?"
- "Mark the action item about the pilot agreement as done."

## Links

- Documentation: https://spellar.ai/docs/mcp
- Privacy: https://spellar.ai/privacy
- Support: support@spellar.ai

The MCP server itself is a hosted service; this repository holds only the plugin definition.
