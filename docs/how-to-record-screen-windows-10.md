# How to Record Your Screen on Windows 10 — Step-by-Step Guide

> Windows 10 has a built-in screen recorder, but it only records one app at a time. This guide shows you all three ways to record your screen on Windows 10 — including how to record the full desktop, capture any window, and save with audio.

**[← Back to main guide](../README.md)** &nbsp;·&nbsp; **[Download Aura — Free Screen Recorder for PC](https://screenrecorderforpc.com/)**

---

## Three Ways to Record Your Screen on Windows 10

| Method | Records Full Desktop | Records Any Window | Audio | Time Limit |
|---|---|---|---|---|
| Xbox Game Bar (built-in) | ✗ | Games & some apps only | ✓ | 4 hours |
| Aura (free download) | ✓ | ✓ | ✓ | None |
| OBS Studio (free download) | ✓ | ✓ | ✓ | None |

---

## Method 1: Xbox Game Bar — Built-In Screen Recorder for Windows 10

Xbox Game Bar is the fastest way to record your screen on Windows 10 without downloading anything.

**How to open Xbox Game Bar:**

1. Press **Win + G** while the app you want to record is open.
2. The Xbox Game Bar overlay appears over the app.
3. Click the **Record** button (circle icon) or press **Win + Alt + R** to start.
4. Press **Win + Alt + R** again to stop.
5. Find your recording at `C:\Users\[YourName]\Videos\Captures`.

**Keyboard shortcuts for Xbox Game Bar on Windows 10:**

| Action | Shortcut |
|---|---|
| Open Xbox Game Bar | Win + G |
| Start / stop recording | Win + Alt + R |
| Take a screenshot | Win + Alt + PrtSc |
| Show recording timer | Win + G → Capture widget |

**Limitations of Xbox Game Bar on Windows 10:**
- Cannot record File Explorer, the Windows desktop, or most system apps
- Cannot record multiple windows at once
- No custom region capture
- No annotation tools
- Requires the app to be in focus

If Xbox Game Bar says "You'll need a new app to open this xbox" or the record button is greyed out, the app is not supported. Use Aura or OBS Studio instead.

---

## Method 2: Aura — Full Desktop Screen Recorder for Windows 10

Aura records the full desktop, any window, or a custom region on Windows 10. It is free with no watermark and no recording time limit.

**How to record your screen on Windows 10 with Aura:**

1. **[Download Aura for Windows](https://screenrecorderforpc.com/)** and run the installer.
2. Open Aura. Select your capture mode: **Full Screen**, **Window**, or **Region**.
3. Set your resolution and frame rate (1080p at 30 FPS works for most recordings).
4. Click **REC** — a floating dock appears with a live timer and audio meters.
5. When done, click **Stop** in the dock or press the stop shortcut.
6. Your recording opens in the library. Trim it and export as MP4.

**What Aura can record on Windows 10 that Xbox Game Bar cannot:**
- The Windows desktop and taskbar
- File Explorer windows
- System dialogs and settings pages
- Multiple monitors (record one or all)
- Custom regions (drag a frame around any area)

---

## Method 3: OBS Studio — Advanced Screen Recorder for Windows 10

OBS Studio is the most powerful free screen recorder for Windows 10, used primarily for streaming but capable of any recording task.

**How to record your screen on Windows 10 with OBS:**

1. Download and install OBS Studio from obsproject.com.
2. In the Sources panel, click **+** and choose **Display Capture** (full desktop) or **Window Capture**.
3. Go to **File → Settings → Output** and set the recording path and bitrate.
4. Click **Start Recording** in the Controls panel.
5. Click **Stop Recording** when done. Find the file at the path you set.

OBS Studio has more settings than most users need for basic screen recording on Windows 10. If the interface feels overwhelming, Aura covers the same use cases with fewer steps.

---

## How to Record Screen with Audio on Windows 10

All three methods above support audio, but they work differently:

**Xbox Game Bar:**
- Records system audio automatically
- To add microphone: Win + G → Settings → turn on "Record audio when I record a game" and select your microphone

**Aura:**
- System audio and microphone are both enabled by default
- Adjust levels from the floating dock while recording
- Recorded as separate tracks for easy editing

**OBS Studio:**
- Add audio sources manually in the Audio Mixer
- Desktop Audio for system sound, Mic/Aux for microphone

---

## How to Record Your Screen on Windows 10 Without Lag

Lag during screen recording on Windows 10 is usually caused by one of four things:

1. **Software encoding is active** — switch to NVENC, AMF, or Quick Sync (GPU encoding) in your recorder settings
2. **Bitrate is too high for your drive** — lower to 8 Mbps for 1080p, or move the recording destination to an SSD
3. **Background apps are competing** — close browsers, cloud sync, and antivirus scans before recording
4. **Display resolution is too high** — record at 1080p even if your monitor is 1440p or 4K

See the [Best Settings guide](./best-settings.md) for specific numbers by use case.

---

## How to Find Your Screen Recordings on Windows 10

| App | Default Save Location |
|---|---|
| Xbox Game Bar | `C:\Users\[Name]\Videos\Captures` |
| Aura | Configurable; defaults to `Videos\Aura Recordings` |
| OBS Studio | Configurable; defaults to `C:\Users\[Name]\Videos` |

---

## Frequently Asked Questions

**Does Windows 10 have a screen recorder?**
Yes — Xbox Game Bar (Win + G) is built into Windows 10 and records games and most apps. It cannot record File Explorer or the desktop itself. For full-desktop recording on Windows 10, download a dedicated screen recorder for PC like Aura.

**How do I record my screen on Windows 10 for free?**
Xbox Game Bar requires no download. For full-screen recording, [Aura](https://screenrecorderforpc.com/) is free with no watermark or time limit.

**Why is Xbox Game Bar not recording on Windows 10?**
The most common causes: the app is not supported (File Explorer, desktop), Game DVR is disabled in Xbox settings, or the GPU does not support hardware encoding. Open Settings → Gaming → Xbox Game Bar and ensure it is turned on.

**Can I record my screen on Windows 10 without Xbox Game Bar?**
Yes. Download Aura or OBS Studio. Both record the full desktop, individual windows, and custom regions without needing Game Bar.

**How long can you record your screen on Windows 10?**
Xbox Game Bar caps recordings at 4 hours. Aura and OBS Studio have no built-in time limit; available disk space is the practical limit.

**Does recording your screen slow down Windows 10?**
With hardware encoding (NVENC, AMF, or Quick Sync) enabled, the performance impact is minimal — usually under 5 % CPU overhead. Software encoding (x264) can add 20–50 % CPU load.

---

*Part of the [Screen Recorder for PC](../README.md) guide by the [Aura Team](https://screenrecorderforpc.com/) · Updated October 2026*
