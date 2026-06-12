# System Architecture

[← Back to Home](../README.md)

---

## Main Idea

The hosts are not streaming directly to their own TikTok accounts.

Instead, they send their screen/camera to the operator through Discord. The operator captures that feed and broadcasts it from one TikTok account.

---

## Video Flow

```text
Host A
Host B
Host C
     ↓
Discord Call / Screen Share
     ↓
Operator Computer
     ↓
TikTok LIVE Studio
     ↓
TikTok Live
```

---

## Chat Flow

```text
TikTok Viewers
     ↓
TikTok LIVE Studio Chat
     ↓
Operator
     ↓
Discord Screen Share
     ↓
Hosts
```

---

## Why This Works

The remote hosts only need to read chat and respond verbally.

They do not need:

- TikTok login access
- TikTok LIVE access
- Stream keys
- Databases
- APIs
- Custom chat bots

---

## Version 1 System

Version 1 uses:

- Discord for host screen sharing
- TikTok LIVE Studio for broadcasting
- Discord screen share for sending chat back to hosts

---

## Version 2 Optional Upgrade

If the client wants cleaner production later, add OBS:

```text
Hosts
  ↓
Discord or VDO.Ninja
  ↓
OBS Studio
  ↓
OBS Virtual Camera
  ↓
TikTok LIVE Studio
  ↓
TikTok Live
```

OBS helps with:

- Cropping Discord sidebars
- Layout control
- Branding
- Overlays
- Multiple host layouts
- Recording

---

Next: [Multiple Hosts](07-multiple-hosts.md)
