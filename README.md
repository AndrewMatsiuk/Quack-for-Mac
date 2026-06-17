<h1 align="center">Quack 🦆</h1>

<p align="center">
  <b>Talk. It types. Everywhere on your Mac.</b><br>
  Local-first voice dictation that turns speech into text in any app —
  fast, private, and fully offline.
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Download for macOS</b></a>
</p>

---

## Why Quack

Typing is slow. Cloud dictation is creepy and laggy. Quack runs the speech
model **right on your Mac** — your voice never leaves the machine, there's no
subscription, and it's quick enough to use all day. Press a hotkey anywhere,
say what you mean, and the words appear exactly where your cursor is.

Built for people who actually work on their Macs — developers, writers,
founders — handling any language locally, mixed with English tech-speak,
without sending a byte to the cloud.

## What you can do

🎙 **Dictate into anything**
Global hotkey types transcribed text straight into the focused field — or the
field you hover with the mouse. Works in browsers, editors, terminals, chat.

🌍 **Speak any language, offline**
Local Whisper covers **99 languages** with smart auto-detect. Or use Apple's
instant on-device engine. Cloud (Groq) is optional and off by default.

✨ **AI cleanup & modes**
Removes fillers ("uh", "um") and false starts, fixes punctuation — on-device.
**Dictation modes** reshape the result per app: a polished email in Mail, a
casual line in chat, verbatim commands in Terminal — matched automatically to
whatever you're typing into.

🎧 **Meeting recorder**
Capture system audio + your mic, label who said what (Me / Them), and get a
clean AI summary with action items. Export transcripts or `.srt` subtitles.

🎬 **Transcribe files & video**
Drop in an mp3, m4a, wav — or an mp4/mov — and get text, notes, or subtitles.
Translate any language straight to English.

⌨️ **Built for developers**
A tech-term dictionary keeps "use effect" → `useEffect`, restores borrowed
tech terms to their original spelling, and feeds Whisper a glossary so it nails
your stack. Press ⏎ after insert to fire commands hands-free.

🧩 **MCP server — Quack as a tool for AI assistants**
A built-in MCP server plugs Quack into Claude Code, Claude Desktop or Cursor.
Ask your assistant to transcribe an audio/video file locally, search your
dictation history, read meeting notes, see usage stats — or even set up and
configure Quack for you ("switch Quack to Ukrainian and turn on press-enter").
Runs offline, no app window needed.

🤖 **Works with Claude & local LLMs**
Plug in any OpenAI-compatible endpoint (Ollama, LM Studio, Gemini…) for the AI
cleanup and notes — fully local with Ollama, or your provider of choice.

🎛 **Yours to tune**
A live waveform HUD with in-place editable review, animated duck indicator,
custom sounds, voice commands ("new line"), searchable history with stats,
launch-at-login, and configurable hotkeys.

🔒 **Private by design**
With the on-device engines, nothing ever leaves your Mac. No account, no
telemetry, no subscription.

🔄 **Updates itself**
Built-in auto-update — new versions arrive quietly, or check any time from the
menu.

## Download & install

1. **[⬇ Download the latest release](../../releases/latest)** — grab the
   **`Quack-<version>.dmg`**.
2. Open the DMG and **drag Quack into the Applications folder** (run it from
   there — that's what keeps auto-updates working).
3. First launch: **right-click Quack.app → Open → Open Anyway**
   (signed for personal distribution, not the App Store).
4. A duck 🦆 appears in your menu bar — you're in.

> **Updating?** Just replace the app — settings, history and models are kept
> (you may need to re-toggle **Accessibility** once). After that Quack updates
> itself.

## First steps

1. **Grant permissions** — Settings → Permissions: Microphone, Accessibility
   (typing), Input Monitoring (hotkey); Screen Recording only for meetings.
   Relaunch after Accessibility / Input Monitoring.
2. **Download a speech model** — Settings → Engine → pick the one recommended
   for your Mac.
3. **Dictate** — double-tap `` ` `` (backtick), speak, double-tap again. Cancel
   with `Esc`. Record a meeting with `⌃⌥R`.

## Requirements

- macOS 14 or later (macOS 26 unlocks the Apple engine + AI cleanup)
- Apple Silicon strongly recommended for local Whisper

---

<p align="center">
  Made with 🦆 by <b>Andrew Matsiuk</b> · <a href="mailto:amacyuk2@gmail.com">amacyuk2@gmail.com</a><br>
  <sub>Personal project — no warranty.</sub>
</p>
