# MBX Reach for Gemini CLI

Connect [Gemini CLI](https://github.com/google-gemini/gemini-cli) to [MBX Reach](https://mbxreach.com), the email marketing platform from MediaBoxEnt Technologies.

Ask Gemini things like:
- "How many contacts joined my Newsletter list this month?"
- "Add maria@example.com to the VIP list with the tag early-access."
- "Write a campaign draft announcing our new release and check if it is ready."

Campaigns are always saved as drafts. You review them and press Send in MBX Reach.

## Install

```bash
gemini extensions install https://github.com/MediaBoxEnt-Technologies/mbx-reach-gemini-extension
```

The first time Gemini uses MBX Reach, your browser opens the MBX Reach sign-in page. Approve the connection for your workspace and you are done. To disconnect, remove the app in MBX Reach under Panel, Assistants, or run `gemini extensions uninstall mbx-reach`.

## Requirements
- An [MBX Reach](https://mbxreach.com) account.
- Gemini CLI.

## Help
- Website: https://mbxreach.com
- Email: hello@mediaboxent.tech

## License
MIT. MBX Reach is a product of MediaBoxEnt Technologies.
