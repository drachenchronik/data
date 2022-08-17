# DrachenChronik Backup

Hier findest du ein Backup der <a href="https://drachenchronik.com/">DrachenChronik</a> Daten im JSON Format.

Solltest du weitere Daten benötigen, melde dich bei uns im <a href="https://discord.gg/Adk9ZNZs">Discord</a>

## Daten Formate

### Videos
Youtube Videos vom Drachenlord incl. Kommentare soweit vorhanden.
```
{
  "video_id": "ID des Videos",
  "title": "Video Titel",
  "description": "Video Beschreibung",
  "publish_date": "ISO 8601 Zeit",
  "duration": "Dauer in Sekunden",
  "channel_id": "Kanal ID",
  "channel_title": "Kanal Name",
  "comments": [
    {
      "comment_id": "ID des Kommentars",
      "comment_text": "Kommentar Text",
      "comment_author": "Kanal Name",
      "comment_author_id": "Kanal ID",
      "comment_time": "ISO 8601 Zeit"
    }
  ]
}
```

### Lachschon
Posts aus dem Drachenlord Faden im Lachschon Forum.
```
{
  "time": "ISO 8601 Zeit",
  "username": "Benutzername",
  "text": "Post Test"
}
```

### Steam aktivitäten
Der Status von Rainers Steam Account.
```
{
  "time_start": "ISO 8601 Zeit",
  "time_end": "ISO 8601 Zeit",
  "gameid": "Steam Game ID",
  "gameextrainfo": "Game Name",
  "gameserverip": "Server IP:Port",
  "status": "Status"
}
```
#### Status
- 0 - Offline
- 1 - Online
- 2 - Busy
- 3 - Away
- 4 - Snooze
- 5 - looking to trade
- 6 - looking to play


