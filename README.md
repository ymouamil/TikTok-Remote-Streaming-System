# TikTok Remote Streaming System

This project documents a simple workflow for allowing remote hosts to appear on a TikTok livestream through Discord while letting them read TikTok chat and respond verbally.

---

## Start Here

1. [Install Required Software](docs/01-installation.md)
2. [Understand the System Architecture](docs/06-system-architecture.md)
3. [Remote Host Guide](docs/02-host-guide.md)
4. [Operator Guide](docs/03-operator-guide.md)
5. [Chat Sharing Guide](docs/04-chat-guide.md)
6. [Multiple Hosts Guide](docs/07-multiple-hosts.md)
7. [Troubleshooting](docs/05-troubleshooting.md)
8. [FAQ](docs/FAQ.md)

---

## Basic Workflow

```text
Remote Host
     ↓
Discord Screen Share
     ↓
Operator Computer
     ↓
TikTok LIVE Studio
     ↓
TikTok Live
```

Chat workflow:

```text
TikTok Viewers
     ↓
TikTok LIVE Studio Chat
     ↓
Operator Shares Chat Window Through Discord
     ↓
Remote Hosts Read Chat
     ↓
Remote Hosts Respond Verbally
```

---

## Official Downloads

- [Download Discord](https://discord.com/download)
- [Download OBS Studio](https://obsproject.com/download)
- [Open VDO.Ninja](https://vdo.ninja/)
- [VDO.Ninja Documentation](https://docs.vdo.ninja/)
- [Download Git](https://git-scm.com/downloads)
- [Download Visual Studio Code](https://code.visualstudio.com/Download)
- [Download GitHub Desktop](https://desktop.github.com/)

TikTok LIVE Studio should be downloaded from the official TikTok LIVE/Creator dashboard available to the account being used.

---

## Project Folder Structure

```text
TikTok-Remote-Streaming-System/
│
├── README.md
│
├── docs/
│   ├── 01-installation.md
│   ├── 02-host-guide.md
│   ├── 03-operator-guide.md
│   ├── 04-chat-guide.md
│   ├── 05-troubleshooting.md
│   ├── 06-system-architecture.md
│   ├── 07-multiple-hosts.md
│   └── FAQ.md
│
├── images/
│   ├── discord-download.png
│   ├── share-screen.png
│   ├── tiktok-preview.png
│   └── chat-window.png
│
├── videos/
│   └── scripts/
│
└── resources/
    ├── software-links.md
    ├── github-commands.md
    ├── screenshot-checklist.md
    ├── client-handoff-message.md
    └── glossary.md
```

---

## Screenshot Placeholders

Add your real screenshots to the `images/` folder.

Recommended screenshots:

- `discord-download.png`
- `share-screen.png`
- `tiktok-preview.png`
- `chat-window.png`

After adding screenshots, they will automatically appear inside the Markdown guides.

---

## Video Tutorials

Video scripts are located in:

[Video Scripts](videos/scripts/)

Recommended videos:

1. Overview
2. Host setup
3. Operator setup
4. Chat sharing
5. Troubleshooting

---

## Delivery Goal

The final delivery should prove:

- A remote host can join Discord.
- The host can share their screen.
- TikTok LIVE Studio can capture the Discord feed.
- The operator can share TikTok chat back to the hosts.
- Multiple hosts can read chat and respond verbally.
