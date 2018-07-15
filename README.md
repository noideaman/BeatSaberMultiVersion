# BeatSaberMultiVersion
Simple bash script to parse the release page of [BeatSaberMultiplayer](https://github.com/andruzzzhka/BeatSaberMultiplayer/releases)

This script is run as a cron job every 10 minutes at my server
- [json](https://beatsaber.weebvr.com/release.json)
- [csv](https://beatsaber.weebvr.com/release.csv)


It will display the latest version for each part of the plugins
ServerHub (Linux/Windows)
MultiplayerServer (Linux/Windows)
MultiPlayerClient (Steam/Oculus)

For thoese interested in making useful stuff out of this. You can curl/parse the data and make things like
- Subscription mailing lists
- A pretty webui
- Discord announcement bot (getting permissions from discord server owners first)

The goal of this: No clue. I was just bored and wanted something to give me a bit of an easier setup for updates, but I stopped after making the csv and json outputs
