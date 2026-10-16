# Everyday Computer Help Desk: Setup Guide

One set of instructions, packaged for Claude, ChatGPT, and Gemini.

## What's in this folder
| File | Use it for |
| :--- | :--- |
| `skills/everyday-computer-help-desk/` | The Claude skill (SKILL.md + references/) |
| `everyday-computer-help-desk.zip` | The same skill, zipped for uploading to claude.ai |
| `portable/everyday_computer_help_desk_instructions.md` | Paste-in instructions for ChatGPT, Gemini, Claude Projects, or any API (~6,400 characters) |
| `portable/troubleshooting_reference.md` | Optional knowledge file: OS identification, first checks per problem, escalation list |

The portable instructions work without the reference file. Adding the file gives better first checks.

## Claude
**Claude Code (skill):**
```bash
cp -r skills/everyday-computer-help-desk ~/.claude/skills/
```
**claude.ai (skill):** Upload `everyday-computer-help-desk.zip` in Settings → Capabilities → Skills. [verify the menu location]
**Claude Project (no skill):** Paste the portable instructions into Project instructions, and add `troubleshooting_reference.md` to Project knowledge.

## ChatGPT (Custom GPT)
1. Create a new GPT and open the **Configure** tab.
2. Paste the portable instructions into **Instructions**. They fit under the 8,000-character limit. [verify]
3. Upload `troubleshooting_reference.md` under **Knowledge**.
4. Suggested conversation starters: "My Wi-Fi isn't working", "My printer says offline", "A virus warning popped up".

## Google Gemini (Gem)
1. In Gemini, open **Gems** and choose **New Gem**.
2. Paste the portable instructions into **Instructions**.
3. Add `troubleshooting_reference.md` as a knowledge file. [verify the file upload option is on your plan]

## API / agent frameworks
Put the portable instructions in the system-level slot. If you include the reference, append it after the instructions.
| Provider | Where it goes |
| :--- | :--- |
| Anthropic (Claude) | `system` parameter |
| OpenAI | `instructions` (Responses API) or a `system`/`developer` message |
| Google (Gemini) | `system_instruction` / `systemInstruction` |

## Why it's portable
- Plain Markdown only: no Claude-only tags, no tool calls, no platform-specific syntax.
- Short enough for the strictest limit (Custom GPT instructions).
- The long lookup tables are in a separate knowledge file that every platform supports.

## Quick test inputs (run on each platform)
1. "my internet thing disappeared": should ask which device first.
2. "A box popped up saying I have a virus and to call this number": should say don't call, then give steps to close it.
3. "Printer says offline on my Windows laptop": should give numbered single-action steps, each saying what should appear.
