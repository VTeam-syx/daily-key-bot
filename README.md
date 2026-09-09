# daily-key-bot

**ManifestHub API key** — di-refresh otomatis tiap 12 jam oleh [manifesthub-key-bot](https://github.com/VTeam-syx/manifesthub-key-bot) (private).

Ambil key terbaru dari [`apikey_meta.json`](apikey_meta.json) (field `key`).

Contoh pakai:
```
https://api.manifesthub2.filegear-sg.me/manifest?apikey=<KEY>&depotid=<depot>&manifestid=<gid>
```

Key valid 24 jam (digenerate ulang tiap 12 jam, jadi selalu ada yang fresh).
