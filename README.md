# Free IPTV – India

`india.m3u` is a playlist of **1,172 free-to-air channels**. Every stream was tested from an Indian connection (Airtel, Hyderabad) on 2026-10-09. Only streams that loaded **and** decoded with ffprobe were kept, so streams geo-blocked in India are excluded.

## Playlist URL

```
https://raw.githubusercontent.com/akumar36/freeiptv/main/india.m3u
```

## How to use

- **VLC:** Media → Open Network Stream → paste the URL.
- **Kodi:** install *PVR IPTV Simple Client* → M3U playlist URL → paste the URL.
- **TiviMate / IPTV Smarters / OTT Navigator (Android TV, Fire TV):** Add playlist → M3U URL → paste the URL.
- **iOS / Apple TV:** use an app such as GSE Smart IPTV or iPlayTV and add the URL.

## Groups

- **Indian channels:** `India | <Language> - <Category>`, e.g. `India | Hindi - News` or `India | Tamil - Movies`.
- **International channels (English):** `International | <Category>`, e.g. `International | News` or `International | Kids`.

Each channel name shows its resolution. Channels that don't broadcast 24/7 are marked `[Not 24/7]`. Logos and `tvg-id`s are included for EPG matching.

| India | Channels | International | Channels |
|---|---|---|---|
| Hindi | 260 | Music | 90 |
| Tamil | 68 | News | 71 |
| Telugu | 58 | Sports | 67 |
| Bengali | 52 | Series | 61 |
| Malayalam | 43 | Kids | 51 |
| English | 38 | Documentary | 36 |
| Punjabi | 31 | Movies | 36 |
| Kannada | 26 | Education | 25 |
| Marathi | 21 | Others | 6 categories |
| Other languages | 64 | | |

## Source and notes

- Stream URLs come from the public [iptv-org](https://github.com/iptv-org/iptv) database. This repo hosts no video, only links.
- Free streams change often, so some links will stop working over time.
- Shopping, adult and closed channels are excluded.
