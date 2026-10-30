# Jamboree Request Maker

A small web page for writing **Super Mario Party Jamboree** lobby requests in the format used in `#jamboree-requests` on the Mario Party Netplay Discord server.

**Use it here:** https://gmn3e.github.io/jamboree-request-maker/

Pick your settings, tap **Copy request**, and paste it into Discord. For example:

```
Looking for 2, Luigi & Bowser Taken
Mall
15 Turns
Bonus On
Minigame Help Off
Motion Off
Minigame Vote
ID: WY9HB6
```

> Pasted text can't ping roles. After pasting, type `@Jamboree Matchmaking` and pick the role from Discord's list.

## Features

**Lobby**
- Status: looking for 1–3 players, full, or session aborted
- **Copy bump** for a quick "Still looking for 2!!"
- Characters already taken: tap **Choose** to pick from all 22 characters in a pop-up. It won't let the lobby go over 4 players (taken characters + players still needed).

**Board and rules**
- All seven boards, 10–30 turns, or **Surprise me** for a random board and turn count
- **Party Rules** or **Pro Rules**. With Pro Rules the game fixes 12 turns, the Bonus Star and minigame voting, so those options are hidden. Minigame Help and Motion minigames can still be set.
- Bonus Stars, Minigame Help and Motion minigames on/off, minigame vote or random
- House rules (no teaming up, no quitting, or your own)
- Room ID and an optional chat channel
- Compact layout or "Label: value" layout

**Presets and sharing**
- **Save as preset** stores your usual setup (board, turns, rules, chat, layout). Saved presets appear at the top of the page; tap one to load it. Room ID and taken characters are never saved.
- **Edit** at the top renames or deletes presets (delete needs a second tap). Up to 6 presets.
- **Copy setup link** makes a link that opens the page with your settings filled in, so friends can host with the same rules and save it as their own preset.
- **Paste a setup link** loads a link inside the page. Useful on iPhone, where the home-screen app keeps its own storage separate from Safari.

**Use it like an app**
- On phones, a "Use it like an app" box explains how to add the page to the home screen (iPhone: Safari → Share → Add to Home Screen with **Open as Web App** on; Android: Chrome menu → Add to Home screen / Install app).
- The box is hidden when the page is opened from the home screen, can be hidden with **Hide this**, and on Android hides itself once the home-screen app has been opened.
- Opened from the home screen, the page runs full-screen with the buttons kept clear of the rounded screen corners.

Your last settings and presets are remembered in your own browser. The version number is shown at the bottom of the page.

## Privacy

The page has no tracking, cookies, accounts or forms, and sends nothing you type anywhere. Settings and presets stay on your own device. Fonts are served from this site, not from Google. GitHub Pages, the host, keeps standard server logs.

## Files

- `index.html`: the whole page (HTML, CSS and JavaScript in one file)
- `icon.svg`, `favicon-32.png`, `apple-touch-icon.png`: site and home-screen icons (original artwork)
- `fonts/`: Fredoka and Nunito, from [Fontsource](https://fontsource.org), licensed under the SIL Open Font License 1.1 (see `fonts/OFL-*.txt`)

Fan-made tool, not affiliated with Nintendo. Super Mario Party Jamboree and character names are trademarks of Nintendo.
