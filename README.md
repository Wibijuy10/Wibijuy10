I’Requirements

Discord Bot Token Guide

YouTube Data API v3 Key Guide

2.1 (Optional) Soundcloud Client ID Guide

Node.js v14.0.0 or newer

🚀 Getting Started

If deploying to Heroku make sure to create config variables

git clone https://github.com/eritislami/evobot.git

cd evobot

npm install

After installation finishes you can use node index.js to start the bot.

⚙️ Configuration

Copy or Rename config.json.example to config.json and fill out the values:

⚠️ Note: Never commit or share your token or api keys publicly ⚠️

{

  "TOKEN": "",

  "YOUTUBE_API_KEY": "",

  "SOUNDCLOUD_CLIENT_ID": "",

  "MAX_PLAYLIST_SIZE": 10,

  "PREFIX": "/",

  "PRUNING": false,

  "LOCALE": "en",

  "DEFAULT_VOLUME": 100,

  "STAY_TIME": 30

}

Currently available locales are:

English (en)

French (fr)

Spanish (es)

Turkish (tr)

Korean (ko)

Brazilian Portuguese (pt_br)

Simplified Chinese (zh_cn)

Traditional Chinese (zh_tw)

Check Contributing if you wish to help add more languages!

📝 Features & Commands

Note: The default prefix is '/'

🎶 Play music from YouTube via url

/play https://www.youtube.com/watch?v=GLvohMXgcBo

🔎 Play music from YouTube via search query

/play under the bridge red hot chili peppers

🎶 Play music from Soundcloud via url

/play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive

🔎 Search and select music to play

/search Pearl Jam

Reply with song number or numbers seperated by comma that you wish to play

Examples: 1 or 1,2,3

📃 Play youtube playlists via url

/playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c

🔎 Play youtube playlists via search query

/playlist linkin park meteora

Now Playing (/np)

Queue system (/queue, /q)

Loop / Repeat (/loop)

Shuffle (/shuffle)

Volume control (/volume, /v)

Lyrics (/lyrics, /ly)

Pause (/pause)

Resume (/resume, /r)

Skip (/skip, /s)

Skip to song # in queue (/skipto, /st)

Move a song in the queue (/move, /mv)

Remove song # from queue (/remove, /rm)

Play an mp3 clip (/clip song.mp3) (put the file in sounds folder)

List all clips (/clips)

Show api ping (/ping)

Show bot uptime (/uptime)

Toggle pruning of bot messages (/pruning)

Localization in 6 languages

Help (/help, /h)

Command Handler from discordjs.guide

Media Controls via Reactions

reactions

🤝 Contributing

Fork the repository

Clone your fork: git clone https://github.com/your-username/evobot.git

Create your feature branch: git checkout -b my-new-feature

Commit your changes: git commit -am 'Add some feature'

Push to the branch: git push origin my-new-feature

Submit a pull request

📝 Credits

@iCrawl For the queue system used in this application which was adapted from @iCrawl/discord-music-botm @Wibijuy10
- 👀 I’m interested in ...
- 🌱 I’m crrently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Wibijuy10/Wibijuy10 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
ok at your changes.

