# 8. FAQ

## Where are my exported videos?

In this order:

1. The folder you picked with **"Change…"** in the export window.
2. If you never picked one: the **"Export"** folder inside your **media folder** (Settings → Storage).
3. If neither is set: **Movies → Onset**.

The quickest way: click **"Show in Finder"** after exporting. Or go to Settings → **Video & output** → "Open folder".

Want to decide every time? Tick **"Ask me where to save it and what to call it every time"** in the export window.
If the folder you picked is gone (for example the external drive is unplugged), Onset saves to the default place instead.

## AI Onset isn't answering?

1. **Quit Onset and open it again.** That fixes most problems.
2. Go to Settings → **AI & tools** and check:
   - **AI-helper** should say "Running". If the AI says AI-helper isn't running, reopen Onset.
   - The AI chosen at the top (Claude Code, ChatGPT · Codex, Cursor or Hermes) should say "Ready". If it isn't signed in, click **"Sign in"** and follow Terminal to sign in in the browser (see chapter 1).
   - With a local Hermes model, the model has to be loaded first, and it's slower; how slow depends on your computer.
3. Click **"Check again"**. Once AI-helper is back, Onset reconnects by itself; no need to reload.
4. During a big job (like "No shoot, just make it") the AI may be busy in the background. Check whether the chat or the status bar says it's working on something.

## Local AI is slow?

With local generation, pictures use Qwen Image 2.1, videos use MiniMax H3, and the speed depends on your computer. And **one Mac makes one thing at a time**; the rest wait.

Things that help:

- Try a "draft" first (Local AI Studio has draft options that are much faster).
- In "No shoot, just make it", switch some shots to **web pictures, stock clips or animated cards**.
- Set a **"Local limit"**: when time's up, the rest become animated cards.
- Install "H3 Turbo" and "H3 fast decode" (in Settings → Generation tools).
- In a hurry, use **cloud generation** (chapter 6, costs money).

## The voice-over is stuck, wrong, or missing?

- **One line sounds wrong:** on that line, click **"Speak line #n again"**.
- **It says no voice-over was added:** usually the voice model isn't downloaded yet, or AI-helper isn't answering. Follow its instructions (Settings → AI & tools → voice models for AI voice-over), then try again.
- **In the preview, the voice-over drifts from the picture or keeps replaying:** that was a problem in older versions and is fixed in the latest one. Please update Onset. Exported files weren't affected.

## Running out of disk space?

Onset's video files are big, and the Local AI models are bigger (tens to over a hundred GB).

- Before an export, Onset stops you if there isn't enough room and tells you roughly how many GB it needs and how many are left.
- Settings → **Storage**:
  - **Media folder**: move your video media to an **external drive**.
  - **Compress files**: make smaller copies (for WhatsApp, e-mail, small file, half size); the originals stay as they are.
  - See how much space each video and post uses, and delete what you don't need.
- If you don't use Local AI, don't install the video model (MiniMax H3 needs 170–185 GB while installing).
- When the disk is very full (around 95% or more), previews and imports may fail. Free up space first.

## Picking an avatar and typing a password every time?

Turn on "**Sign in automatically when the app opens**" in Settings → Account → Sign-in (see chapter 1, 1-8).

## "Apple could not verify the developer" when opening?

See chapter 1: right-click → "Open", or click **"Open Anyway"** in System Settings → Privacy & Security.

## The AI messed something up?

Click **"↶ Undo this AI change"** in the AI Onset chat. You can also switch back to an earlier **"Version"** of the edit.

## Can cloud generation spend money behind my back?

No. Every time, it asks first: Higgsfield quotes credits, Theater quotes an amount, and Cursor and ChatGPT say they'll use your plan's usage. It only goes ahead when you agree. When the tool is chosen automatically, it never picks a paid one.

## The phone can't see things from the Mac?

- Onset must be open on the Mac, with Settings → Sync turned on.
- Away from home, "Reach this Mac from anywhere" must be on and the Mac must stay awake.
- Away from home, big video files don't transfer; they go when you're back on the same Wi‑Fi.

---

[← Back to contents](README.md)
