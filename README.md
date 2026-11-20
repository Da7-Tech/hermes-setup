# Hermes setup

A skill for people who want help getting [Hermes Agent](https://hermes-agent.nousresearch.com/)
ready for the first time. Give it to Claude Code, Codex, Devin, or another agent
that can browse documentation and work on your device.

Your agent asks what you need, follows Hermes' current official instructions,
installs it, connects your models, personalizes it, and checks that it works.
Voice, Telegram, Discord, and other connections are optional.

## Get started

Send this to your agent:

> Use this skill to install and set up Hermes Agent for me:
> https://github.com/Da7-Tech/hermes-setup/blob/main/skills/hermes-setup/SKILL.md

Or install it with the [Skills CLI](https://github.com/vercel-labs/skills)
(requires Node.js 22.20 or later):

```bash
npx skills add Da7-Tech/hermes-setup --skill hermes-setup -g
```

Choose your agent. This installs the skill for your user account. You can also
copy the [skill folder](skills/hermes-setup/) into your agent's skills directory.
Then ask: **“Help me set up Hermes.”**

You choose where to use Hermes, which models to connect, and whether to add voice
or messaging. For personalization, give your own instructions or let your agent
use relevant preferences it already knows about you.

The setup uses Hermes' official installers, settings, and customization features.
It checks the documentation for your device and release as it works. Existing
settings are preserved, and changes are backed up.

## Release

[Version 1.0.0](https://github.com/Da7-Tech/hermes-setup/releases/tag/v1.0.0)
contains the complete skill. See the [release notes](CHANGELOG.md).

Independent project by [Da7-Tech](https://github.com/Da7-Tech). [MIT license](LICENSE).
