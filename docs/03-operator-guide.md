# Operator Guide

[← Back to Home](../README.md)

---

## Who This Is For

The operator is the person controlling the stream from the main computer.

The operator:

- Opens Discord
- Opens TikTok LIVE Studio
- Captures the host screen
- Starts the stream
- Shares chat back to hosts

---

## Before The Stream

Open:

- Discord
- TikTok LIVE Studio
- Optional: OBS Studio

---

## Step 1: Start Discord Call

1. Open Discord.
2. Start or join the host call.
3. Confirm the remote host can hear you.
4. Ask the host to share their screen.

---

## Step 2: Confirm Host Screen Share

The host should share their screen or application.

Confirm:

- [ ] Host screen is visible
- [ ] Host audio is working
- [ ] No private information is visible
- [ ] Host knows they are being captured

---

## Step 3: Capture Discord In TikTok LIVE Studio

In TikTok LIVE Studio:

1. Add a source.
2. Choose screen/window capture.
3. Select Discord.
4. Confirm the preview shows the host.

Screenshot placeholder:

![TikTok Preview](../images/tiktok-preview.png)

---

## Important Problem: Discord Sidebars

If TikTok LIVE Studio captures the full Discord window, it may show sidebars, server lists, and channels.

Quick fixes:

1. Make the Discord shared screen full screen.
2. Hide extra panels if possible.
3. Use OBS to crop the Discord capture if needed.

---

## Optional Better Setup With OBS

If using OBS:

```text
Discord
  ↓
OBS Window Capture
  ↓
Crop unwanted Discord sidebars
  ↓
OBS Virtual Camera
  ↓
TikTok LIVE Studio
```

OBS is recommended when the stream needs to look polished.

---

## Step 4: Share Chat Back To Hosts

See the [Chat Guide](04-chat-guide.md).

---

## Step 5: Go Live

Before going live, confirm:

- [ ] Host visible
- [ ] Host audio working
- [ ] TikTok preview correct
- [ ] Chat panel visible
- [ ] Chat shared back to hosts
- [ ] Hosts know to respond verbally

Then click **Go Live**.

---

Next: [Chat Guide](04-chat-guide.md)
