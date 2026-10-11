# Free IPTV – India

`india.m3u` is a playlist of **1,048 free channels**. Every stream was tested from an Indian connection (Airtel, Hyderabad) on 2026-10-09. Only streams that loaded **and** decoded with ffprobe were kept, so streams geo-blocked in India are excluded.

## Playlist URL

Copy-link page: **https://akumar36.github.io/freeiptv/**

```
https://raw.githubusercontent.com/akumar36/freeiptv/main/india.m3u
```

> Use the **raw** URL above. The normal GitHub page link (`github.com/.../blob/main/india.m3u`) is a web page, not a playlist, and players will report 0 channels.

## TV guide (EPG)

The playlist header points to a free JioTV-based guide that updates daily:

```
https://mitthu786.github.io/tvepg/jiotv/epg.xml.gz
```

Most players (TiviMate, Kodi, OTT Navigator) load it automatically from the playlist. If yours doesn't, add that URL as the EPG source. 382 of the 583 Indian channels are mapped to it. International channels have no guide.

## How to use

- **VLC:** Media → Open Network Stream → paste the URL.
- **Kodi:** install *PVR IPTV Simple Client* → M3U playlist URL → paste the URL.
- **TiviMate / IPTV Smarters / OTT Navigator (Android TV, Fire TV):** Add playlist → M3U URL → paste the URL.
- **iOS / Apple TV:** use an app such as GSE Smart IPTV or iPlayTV and add the URL.

## Groups

- **Indian channels:** `<Language> - <Category>`, e.g. `Hindi - News` or `Tamil - Movies`.
- **International channels (English):** `International | <Category>`, e.g. `International | News` or `International | Kids`.

Each channel name shows its resolution. Channels that don't broadcast 24/7 are marked `[Not 24/7]`. Logos are included.

| India | Channels | International | Channels |
|---|---|---|---|
| Hindi | 229 | Music | 80 |
| Tamil | 61 | News | 70 |
| Telugu | 53 | Sports | 61 |
| Malayalam | 40 | Series | 60 |
| Bengali | 37 | Kids | 43 |
| English | 32 | Movies | 30 |
| Punjabi | 31 | Documentary | 27 |
| Kannada | 24 | Education | 25 |
| Marathi | 16 | Others | 7 categories |
| Other languages | 61 | | |

## Source and notes

- Stream URLs come from the public [iptv-org](https://github.com/iptv-org/iptv) database. This repo hosts no video, only links.
- Free streams change often, so some links will stop working over time.
- Shopping, adult and closed channels are excluded.
- Paid channels (sold only through cable, DTH or subscription apps) are excluded when the only available streams are unofficial restreams. Channels use the broadcaster's own stream or an official free ad-supported source wherever one exists.
