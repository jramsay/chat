<h1 align="center">Live Share Chat</h1>

<h3 align="center">Chat with your team while you collaborate over code using VS Live Share</h3>

<p align="center"><img src="https://raw.githubusercontent.com/karigari/vscode-chat/master/readme/Live Share Chat.gif" alt="Screenshot" width="800" /></p>

<p align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=karigari.chat"><img alt="Visual Studio Marketplace Downloads" src="https://img.shields.io/visual-studio-marketplace/d/karigari.chat"></a>
    <a href="https://marketplace.visualstudio.com/items?itemName=karigari.chat"><img alt="Visual Studio Marketplace Rating" src="https://img.shields.io/visual-studio-marketplace/r/karigari.chat"></a>
    <a href="https://aka.ms/vsls"><img src="https://aka.ms/vsls-badge" alt="Live Share enabled" /></a>
</p>

# Get started

Live Share Chat is a companion extension for [Visual Studio Live Share](https://aka.ms/vsls), which enables you to collaboratively edit and debug code with others, in real time.

1. Install the [Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack), which packages VS Live Share with support for **audio and text chat**.
1. **Direct Messages**: DM your Live Share contacts, within or outside Live Share sessions.
1. **Session Messages**: Chat with participants, within a Live Share session

# Features

- **Quiet notifications**: Chat apps can be painfully distracting. This extension emphasizes on making chat useful, contextual, and without distracting notifications.
- **Rich formatting**: Share markdown code snippets, and add emojis to your chat messages.
- **Native look-and-feel**: Use chat in your preferred theme and grid editor layout.

<p align="center">
    <img src="https://raw.githubusercontent.com/karigari/vscode-chat/master/readme/feature-1-magnifier.png" alt="Quiet notifications" width="290" />
    <img src="https://raw.githubusercontent.com/karigari/vscode-chat/master/readme/feature-2.png" alt="Rich formatting" width="290" />
    <img src="https://raw.githubusercontent.com/karigari/vscode-chat/master/readme/feature-3.png" alt="Theme and grid layout" width="290" />
</p>

# Integrations for chat apps

Optionally, you can integrate Live Share Chat with your existing team chat apps, so your team communication is not fragmented.

## Slack

To configure your Slack workspace, run the **Sign In with Slack** command in VS Code. Are you a Slack workspace admin? [Approve this app](https://slack.com/apps/ACB4LQKN1-slack-chat-for-vs-code) for your team.

Start a new VS Live Share session within a Slack channel: Use the slash commands `/live share` and `/live end` to start and end a session.

## Discord

Discord support is experimental. Please see [this doc](docs/DISCORD.md) to set it up.

## Live Share Spaces

To explore richer ways to connect and collaborate with developers across your teams, classrooms and communities, check out [Live Share Spaces](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.spaces).

# Support

- **Configuration settings**: To use behind a network proxy and other settings, see [CONFIGURATION](docs/CONFIG.md).
- **Raise an issue**: Feel free to [report an issue](https://github.com/karigari/vscode-chat/issues), or find [me on Twitter](https://twitter.com/arjunattam) for any suggestions or support.

# Developer docs

- **Get started with contribution**: See [CONTRIBUTING](docs/CONTRIBUTING.md) to understand repo structure, building and testing.
- **New chat integrations**: The implementation can be extended to support any chat provider, see [PROVIDERS](docs/PROVIDERS.md).
- **Vision**: Read the [VISION](VISION.md) doc to understand the motivation behind this extension and the roadmap ahead.
