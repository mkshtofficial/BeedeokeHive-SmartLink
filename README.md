<div align="center">

<img src="https://github.com/mkshtofficial/BeedeokeHive/blob/main/smartlink_icon.png" alt="Beedeoke SmartLink" width="112" />

# Beedeoke SmartLink

**Your Beedeoke Hive remote and wireless microphone.**

Search songs, manage reservations, follow lyrics, and sing from your Android phone.

**Android 10+ · Phones & tablets · Local Wi-Fi connection**

</div>

---

Beedeoke SmartLink is a companion app for a compatible Beedeoke Hive player. The main player handles karaoke playback and the song library; SmartLink provides controls, synchronized lyrics, and an experimental wireless microphone.

## Features

### Remote control

- Enter song codes with a six-digit keypad and preview the title and artist.
- Play a song immediately, reserve it, or place it first in the queue.
- View reservations and remove queued songs.
- Replay, pause/resume, skip, and stop playback.
- Adjust key, tempo, volume, melody, and player background mode.
- Start and stop karaoke recording on supported player versions, with recording status shown in the remote.

Available controls depend on the connected player. Unsupported controls display a message instead of changing playback.

### Songs and favorites

- Search the connected player's catalog by title, artist, or code.
- Browse songs by initial letter.
- Save favorites and switch between **All** and **Favorites**.
- Choose **Reserve**, **Play Now**, or **1st Reserve** from a song's actions.

SmartLink favorites are saved on the remote device, independently of the main player's favorites.

### Live lyrics

- Follow synchronized lyric rows, highlighting, countdowns, and instrumental sections from a compatible player.
- Open lyrics fullscreen.
- Customize alignment, highlight color, portrait/landscape text size, outline, shadow, and background.
- Choose two or four lyric lines in portrait mode.

### Wireless microphone (Use Device Mic or Wired Microphone)

Use your phone's microphone to send live audio to Beedeoke Hive over Wi-Fi.

- Switch the microphone **ON** or **OFF** from the **Mic** tab.
- Adjust microphone volume and player effects: echo, delay, reverb, clarity, and sensitivity threshold.
- Enable noise suppression on supported phones.
- Keep the microphone running while the screen is locked, with a foreground notification and a stop action.

Microphone quality and delay depend on the phone, player, audio output, and local network. Keep the phone away from speakers to reduce feedback.

## Getting started

1. Install Beedeoke SmartLink on your Android phone or tablet.
2. Connect the phone and Beedeoke Hive player to the same local Wi-Fi network.
3. Enable **Remote Server** in the main player's settings, then open **Enter KTV**.
4. In SmartLink, tap **Scan QR** and scan the connection QR code shown on the karaoke screen. Allow camera access when requested.
5. Alternatively, enter the player's IP address or `IP:port`, then tap **Connect**. The default server port is **18662**; use the port configured on your player.
6. Enter the player password if one is configured. An empty player password allows a connection without a password.

Allow local-network access if Android requests it. SmartLink remembers the player address and reconnects when reopened. Use the player's local address, rather than the phone's address.

## Using the microphone

1. Connect SmartLink and open **Enter KTV** on an activated Beedeoke Hive player.
2. In the player's **Settings → Audio → MICROPHONE**, enable **Microphone Stream**.
3. Choose **Smart Link Mic Only** or **Use Both** as the microphone source. **Device Mic Only** uses the main player's microphone and does not accept SmartLink microphone audio.
4. Open SmartLink's **Mic** tab, allow microphone access, and switch it **ON**.
5. Start a song if the player is using **Enabled with Standby**. **Enable (Always On)** also permits microphone audio while KTV is idle.
6. Switch **OFF**, or use the notification's stop action, when finished.

Only one SmartLink microphone can be in use at a time. Leaving the Mic tab stops the wireless microphone; locking the screen can keep it active.

**Mic Settings:** effects are applied by the player. Saving microphone settings automatically restarts an active mic. **Mic Delay** controls echo repeats, not network transmission latency. A higher sensitivity threshold rejects quiet sounds and may cut off soft singing; **0%** disables the threshold. Noise suppression can also affect soft vocals.

## Tabs

| Tab | Purpose |
| --- | --- |
| Remote | Song-code entry and playback controls |
| Song List | Catalog search, song actions, and favorites |
| Queue | View and remove reservations |
| Lyric | Follow live lyrics and open fullscreen |
| Mic | Wireless microphone and microphone settings |
| Settings | Connection port, lyric appearance, backgrounds, and remote preferences |

## Troubleshooting

**Cannot connect:** confirm that Remote Server is enabled, Enter KTV is open, and both devices are on the same network. Check the IP address, server port, and password. Guest Wi-Fi or client isolation can prevent devices from reaching each other. Try manual IP entry if discovery is unavailable.

**QR code is rejected:** scan the connection QR code displayed by a compatible Beedeoke Hive player. You can also connect manually.

**Song list or lyrics are missing:** confirm the main player has loaded its resources and songs. Refresh the song list. Live lyrics require a player version that supports SmartLink lyric updates and a song with supported lyrics.

**Mic is in standby:** start a song, or change the player's Microphone Stream mode to Always On.

**Mic will not start:** check microphone permission, player activation, the selected microphone source, and Microphone Stream. Close another SmartLink microphone connection if one is already in use.

**Mic cuts off quiet singing:** lower the sensitivity threshold and try disabling noise suppression.

**Recording control is unavailable:** update the main Beedeoke Hive app to a version that supports remote recording. Recordings are saved by the main player in its configured recording directory.

## Feedback

Include the SmartLink version, Beedeoke Hive version, device models, Android versions, and steps to reproduce the issue. Screenshots or short recordings are helpful. Keep passwords, connection QR codes, activation codes, and private song files out of public reports.

## Credits

The app includes the DSEG font. Its license is preserved in [DSEG-LICENSE.txt](app/src/main/assets/DSEG-LICENSE.txt).
