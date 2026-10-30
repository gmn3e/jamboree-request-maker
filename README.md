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

## What it does

- Status: looking for 1–3 players, full, or session aborted
- Characters already taken
- All seven boards, 10–30 turns
- Bonus Stars, Minigame Help and Motion minigames on/off, minigame vote or random
- House rules (no teaming up, no quitting, or your own)
- Room ID and an optional chat channel
- Compact layout or "Label: value" layout
- **Copy bump** for a quick "Still looking for 2!!"

Your last settings are remembered in your own browser.

> Pasted text can't ping roles. After pasting, type `@Jamboree Matchmaking` and pick the role from Discord's list.

## Privacy

The page has no tracking, cookies, accounts or forms, and sends nothing you type anywhere. Fonts are served from this site, not from Google. GitHub Pages, the host, keeps standard server logs.

## Files

- `index.html`: the whole page (HTML, CSS and JavaScript in one file)
- `fonts/`: Fredoka and Nunito, from [Fontsource](https://fontsource.org), licensed under the SIL Open Font License 1.1
