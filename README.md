<h1 align="center">
  🇮🇳 ᴛᴜsʜᴀʀ ᴛxᴛ ᴜᴘʟᴏᴀᴅᴇʀ 🇮🇳
</h1>

![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Welcome+To+Txt+Uploader+Bot+!)

## 😎 Credit

🥳 Credit Goes To [Tushar](https://t.me/newstudent1885)

  
## 🚀 Deploy

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/nat-king-15/ADVANCE-TXT-UPLOADER)

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=advance-txt-uploader&repository=nat-king-15%2FADVANCE-TXT-UPLOADER&branch=main&builder=dockerfile&instance_type=free)

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/nat-king-15/ADVANCE-TXT-UPLOADER)

## 🔥 Commands

- **`/start`**: ⚡ check bot is alive.
- **`/tushar`**:  📁 upload txt file.
- **`/stop`**: 🛑 stop ongoing process.
- **`/restart`**: 🔮 restart the bot.
- **`/cookies`**: 🍪 upload cookies file.
- **`/e2t`**: 📝 edit txt file.
- **`/yt2txt`**: 🗃️ create txt of yt playlist (owner).
- **`/sudo add`**: 🎊 add user or group or channel (owner).
- **`/sudo remove`**: ❌ remove user or group or channel (owner).
- **`/userlist`**: 📜 list of sudo user/group/channel.
- **`/help`**: 🎉 for help.

## 📖 Guide For Heroku Deployment

**One-Click Deploy** — Click the **Deploy to Heroku** button above and fill in the required environment variables:

| Variable | Description |
|---|---|
| `API_ID` | Get from https://my.telegram.org |
| `API_HASH` | Get from https://my.telegram.org |
| `BOT_TOKEN` | Get from [@BotFather](https://t.me/BotFather) |
| `AUTH_USERS` | Your Telegram User ID |

After deploying, make sure the **worker dyno** is turned **ON** in the Heroku dashboard (Resources tab).

> **Required Buildpacks** (auto-configured via `app.json`):
> - `heroku/python`
> - `https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git`
> - `https://github.com/heroku/heroku-buildpack-apt`
