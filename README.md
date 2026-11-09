# LG Remote

A tiny web remote for LG webOS TVs. One HTML file, no install, no server. It talks to the TV directly over your Wi-Fi.

**Use it:** open the GitHub Pages link for this repo on your phone, then use your browser's **Add to Home Screen**.

## First-time setup

1. Find your TV's IP: **Settings → Network → Wi-Fi → Advanced**. (Tip: reserve that IP for the TV in your router so it never changes.)
2. Enter the IP and tap **Connect**.
3. If it won't connect, tap **"Open the TV's address"**, accept the browser's security warning (the TV uses a self-signed certificate), then come back and tap **Connect** again.
4. Accept the **"allow this device?"** prompt on the TV with your regular remote. After that it reconnects automatically.

## Features

Power off · D-pad + OK · Back / Home / Exit / Settings · Volume and channel (hold to repeat) · Mute · Play / pause / rewind / fast-forward · Input picker and app launcher loaded from your TV · Arrow keys and Enter on a computer

## Notes

- The phone and TV must be on the same Wi-Fi network.
- Turning the TV **on** isn't supported. The TV's network connection sleeps when it's off.
- Your pairing key is stored only in your browser.
