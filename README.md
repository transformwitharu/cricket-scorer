# 🏏 Saturday Cricket Scorer

A simple, phone-friendly app to score our Saturday cricket matches — no more losing count of runs, overs, or wickets!

Works right in your browser. Nothing to install. One person scores, and everyone else can watch the score live on their own phone.

**👉 Live app: https://transformwitharu.github.io/cricket-scorer/

## ✨ What it does

- **Tap to score** — big buttons for 0, 1, 2, 4, 6, wides, no-balls and wickets
- **Auto totals** — score, overs and run-rate update on their own
- **Watch live** — anyone can follow the match live on their phone, no typing needed
- **Two scoring styles** — quick *Simple* mode, or *Detailed* mode with batsmen & bowlers
- **Auto strike rotation** — batsmen swap automatically on 1s, 3s and end of over
- **Edit any ball** — fix a miscount without starting over
- **Match history** — every game is saved with a full scorecard
- **AI commentary** — a fun dramatic summary at the end of each match 🎙️

---

## 🚀 Quick start

1. Open the link on your phone
2. Tap **Add to Home Screen** so it opens like an app
3. One person taps **Score it**, everyone else taps the live game to **Watch**

---

## 📖 User Guide

### Starting a match (the scorer)

1. **Room code** — leave it as `Irving` for our regular games
2. **Score it** — choose this if you're the one keeping score
3. **Pick a mode:**
   - **Simple** — just tap what happens each ball
   - **Detailed** — also tracks who's batting and bowling
4. Enter **team names**, **overs**, and **who bats first**
5. *(Optional)* Set a **PIN** if you'll pass the phone around
6. Tap **Start Match**

### Scoring each ball

Tap one button for each ball bowled:

- **0 / 1 / 2 / 4 / 6** — runs scored
- **Custom** — any other number (like 3 or 5)
- **Wide** — adds 1, doesn't count as a ball
- **No Ball** — opens a box to enter runs, adds those + 1
- **Wicket** — records the out

The score and overs at the top update automatically.

### Made a mistake?

- **Undo** — removes the last ball
- **Edit balls** — tap to see every ball, then tap any one to fix or delete it. Everything recalculates.

### Detailed mode extras

- Two batsmen always show, with a gold **ON STRIKE** marker
- Batsmen **swap automatically** — you never set strike yourself
- Pick the **bowler** from the dropdown (change it anytime)
- When a wicket falls, choose **who comes in** and which end they take
- **+ Add a player** if someone arrives late

### Watching live (everyone else)

1. Open the same link
2. On the home screen, tap the **Live now** card showing the match
3. You're now watching — the score updates as the scorer taps

In detailed mode, watchers also see who's batting, who's bowling, this over's runs, and who's yet to bat.

### Passing the phone (handover)

- The scorer taps **Take over** isn't needed on their phone
- Another person (watching) taps **✋ Take over**, enters the PIN if set, and they become the scorer
- The old scorer's phone switches to watching automatically

### End of the match

- A winner screen appears with the scorecard and a fun AI commentary 🎙️
- The match is **saved to History** automatically

### Match History

- Tap **📊 History** on the home screen
- See every past match with scores and result
- Tap a detailed match to open its **full scorecard** (batsmen, bowlers, over-by-over)
- **Download CSV** to open all matches in Excel or Google Sheets

---

## ❓ Quick tips

- **One scorer per match** — others watch. Don't have two people scoring the same game at once.
- **AI commentary needs internet.** Everything else works fine offline.
- **History is shared** across all phones via the cloud.
- Stuck? Tap **Undo** or **Edit balls** — almost anything can be fixed.

---

## 🛠️ For the curious (tech notes)

- Single `index.html` file, hosted free on **GitHub Pages**
- Live sync and shared history via **Firebase Realtime Database**
- AI commentary via the **Claude API**
- No accounts, no installs, no ads

---

*Built for our Saturday morning crew. See you at the ground! 🔥*
