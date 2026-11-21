# 6. Cloud generation: Higgsfield and Theater

Local generation is free but slow, and some Macs can't run the video model at all. **Cloud generation** uses your own cloud account to make pictures and videos on someone else's computers. It's much faster, but it costs money.

Onset works with four services: **Higgsfield** and **Theater**, plus **Cursor** and **ChatGPT** for pictures only. You can add them all, and choose which one to use for each shot.

## 6-1 Add a cloud service

No account yet? Sign up on their websites first:

- **Theater**: [https://theater.thedaydreamer.ai](https://theater.thedaydreamer.ai)
- **Higgsfield**: [https://higgsfield.ai](https://higgsfield.ai)

1. Avatar at the top right → **"Settings"** → **"Generation tools"**, then scroll down to **"Cloud generation"**. (The "Generation tools" button at the bottom left of "No shoot, just make it" brings you here too.)
2. Click **"＋ Add a cloud service"** and pick Theater, Higgsfield, Cursor or ChatGPT. (Cursor and ChatGPT have to be added here by hand.)
3. Click **"Sign in to Theater"** or **"Sign in to Higgsfield"**:
   - **Theater**: nothing to install. The Theater sign-in page opens in your browser.
   - **Higgsfield**: install Higgsfield's small command-line tool first (the page shows the one-line install command; a tech-savvy friend can paste it into Terminal), then click "Sign in to Higgsfield" and sign in in the browser.
4. Back in Onset, click **"Check again"**. When it says signed in, you're set.

Onset never sees or stores your password: you sign in in the browser.

![Cloud generation settings](images/76-cloud.jpg)

> The Higgsfield and Cursor account status in this screenshot has been blurred.

To stop using one, click the **✕** on its line ("Remove from the list").

## 6-2 Which one goes first

**"Use first"**:

- **Automatic (list order)**: use the one at the top of the list; if it can't be used (not signed in, no credits), use the next one.
- Or pick a specific service.

## 6-3 Choose the model and resolution

Once you're signed in, each service shows:

- **"Picture model"** and **"Clip model"**: the default is "Default (the cloud chooses)", or pick one yourself.
- After you pick a model, you can choose its **"Resolution"**. Higher resolution usually costs more.

## 6-4 Higgsfield credits vs. Theater quotes

| | Higgsfield | Theater |
|---|---|---|
| How you pay | With **credits** in your account (buy or claim them on Higgsfield first) | By the **quote** each time, charged to your Theater account |
| Can Onset see your balance? | Yes, e.g. "Signed in (plan, N credits)" | No, check your Theater account |
| What it asks before starting | "…credits in all, spend them?" | Videos: "about US$…, go ahead?"; pictures: Theater quotes first |
| If you say no | Those shots become flying text | Nothing is made |

**Neither one spends money until you agree.**

## 6-5 Cursor and ChatGPT: pictures on your own plan

If you already pay for Cursor or ChatGPT, you can use them to make pictures too:

- **Pictures only, no video.** For video, use Theater, Higgsfield or local generation.
- **Reference pictures work** (chapters 3 and 4).
- **It uses your plan's usage, with no price per picture.** Before making anything it asks whether to use your Cursor (or ChatGPT) plan, and only goes ahead when you click "Make with Cursor" or "Make with ChatGPT". If you say no, those shots become flying text.
- **Cursor**: uses your signed-in Cursor account (install and sign in to Cursor in Settings → AI & tools).
- **ChatGPT**: goes through Codex with your ChatGPT account, and **needs ChatGPT Plus or higher** (the free plan can't make pictures). When your usage is used up, Onset tells you when you can make pictures again.

Once they're on the list, you can choose them:

- **No shoot, just make it**: set a shot's source to "**Cursor picture**" or "**ChatGPT picture**" (chapter 5).
- **AI note cards**: set the "Tool" to "Cursor (pictures, your plan)" or "ChatGPT (pictures, your plan)" (chapter 3).
- **AI Onset**: just say "draw this one with ChatGPT".

## 6-6 Where cloud generation is used

- **"Cloud AI" on the AI generation page**: make a picture or a video straight into the AI library, without opening a video first. Choose a picture or a video, how many seconds of video, the model and size, see the price first, and nothing starts until you click "**Make it**" (chapter 2, 2-6). You can also tell AI Onset "draw a … in the cloud", and even attach pictures you gave it in the chat.
- **Restyle and change the scene**: turn a part you filmed into another look (chapter 3, 3-12).

- **No shoot, just make it**: choose "Cloud generation" or "Mixed", or switch a shot in the shot list to "Higgsfield cloud clip", "Theater cloud picture" and so on (chapter 5).
- **AI note cards**: pick "Higgsfield (paid)" or "Theater (paid)" as the "Tool". Generating shows a quote first, then asks whether to go ahead (chapter 3).
- When the tool is chosen "Automatically", **it never picks a paid one**.

### Reference pictures

For reference pictures given to an AI note card or to AI Onset (chapters 3 and 4): **Theater, Cursor and ChatGPT make from them**; **Higgsfield doesn't take them**, and only the AI writing the prompt sees them. To make from a picture, choose anything but Higgsfield.

> No real money was spent while testing, so this chapter has no screenshot of an actual quote.

---

Next: [The iPhone app and sync →](07-iphone.md)
