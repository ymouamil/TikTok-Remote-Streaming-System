# Multiple Hosts Guide

[← Back to Home](../README.md)

---

## Purpose

This guide explains how to handle multiple remote hosts in one stream.

---

## Basic Layout

```text
Host A
Host B
Host C
     ↓
Discord Call
     ↓
Operator Computer
     ↓
TikTok LIVE Studio
```

---

## Host Rules

All hosts should:

- Join the same Discord call.
- Wear headphones.
- Avoid talking over each other.
- Keep microphones muted when not speaking, if needed.
- Watch the shared chat window.
- Respond verbally to viewers.

---

## Chat For Multiple Hosts

The operator shares one TikTok chat window through Discord.

All hosts watch the same chat.

```text
TikTok Chat
     ↓
Discord Screen Share
     ↓
Host A
Host B
Host C
```

---

## Production Tip

For more than one host, OBS is recommended because it allows better layouts.

Example OBS layout:

```text
┌─────────────┬─────────────┐
│ Host A      │ Host B      │
├─────────────┴─────────────┤
│ Host C                    │
└───────────────────────────┘
```

---

## Checklist

- [ ] All hosts joined Discord
- [ ] All hosts can hear operator
- [ ] All hosts can see shared chat
- [ ] Main host screen is visible
- [ ] Backup host plan exists
- [ ] Everyone knows who speaks first

---

Next: [Troubleshooting](05-troubleshooting.md)
