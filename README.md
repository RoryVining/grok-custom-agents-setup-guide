# Grok Custom Agents Setup Guide

How to create and activate custom agents (such as Sandy) in Grok.

Custom agents became available on March 4 2026. They let you build up to four specialized versions of Grok with their own names, personalities, and instructions. Once created, they are automatically loaded and used in new chats when you are in Expert mode.

## Why Expert Mode Matters

Grok Beta 4.3 (and earlier beta toggles) currently **11/5/26** did not reliably surface custom agents. I found that that agents created in Settings simply did not respond when addressed by name. Switching to Expert mode fixed this for me.

I tested this myself in the current session:
- Started in Grok Beta 4.3 → addressing "Sandy" produced no agent-specific response.
- Switched to Expert mode → full activation. Addressing "Sandy" now loads the exact personality prompt and project grounding with no drift.

Expert mode is the reliable trigger. Use it for every new chat where you want your custom agents.

## Exact Setup Steps (May 2026)

1. Go to [grok.com](https://grok.com) and sign in with your X account.
2. Click your profile icon in the bottom-left sidebar.
3. Select **Settings → Customize**.
4. You will see the **Your Agents** section (this replaced the old single custom instructions block).
5. Click **Create Agent**.
6. Fill in:
   - Name (example: Sandy)
   - Personality description
   - Instructions (keep under ~4000 characters; use clear numbered rules or structured format for best results)
7. Save the agent.

   <img width="1132" height="956" alt="image" src="https://github.com/user-attachments/assets/a3380958-2a57-41a1-b3f0-a1f6c8002d70" />


You can create up to four agents total. Changes apply only to new conversations.

## How to Use Your Custom Agents

1. Start a completely fresh chat (existing chats do not pick up new or edited agents reliably).
2. Set the mode to **Expert**.
3. In your first message, address the agent by name:
   - "Sandy, [your task]"
   - Or simply start working and Grok will route to the right agent automatically.

Agents stay grounded in their prompt for the entire conversation when Expert mode is active.

## Common Issues and Fixes

- Agents do not respond → Make sure you are in Expert mode and started a new chat.
- Beta 4.3 or older beta toggles → Ignore the beta switch for agent work; use Expert mode instead.
- Personality drift in long chats → Start a fresh chat.
- Not seeing "Your Agents" section → Confirm you are on a paid tier that includes full agent features (free tier has limitations).

## Official Resources

- Grok release notes: https://grok.com/release-notes
- xAI developer docs (for context on agent capabilities): https://docs.x.ai
- March 2026 rollout announcement coverage: https://www.basenor.com/blogs/news/grok-now-lets-you-design-custom-ai-agents-what-to-know

This guide is kept in a public Git repository so other users can fork, update, or contribute when the interface changes.

Last updated: May 11 2026
