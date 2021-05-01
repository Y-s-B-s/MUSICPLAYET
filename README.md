# 🎧 Calls Music 2 — The first open-source project based on [PyTgCalls](https://github.com/Y-s-B-s/MUSICPLAYET)

## Please deploy ooriginal bot because im editing this for my personal use 

## ✍️ Requirements

- FFmpeg
- Node.JS 15+
- Python 3.7+

## 🚀 Deployment

### 🛠 Config

Copy `example.env` to `.env` and fill it with your credentials.

### ✨ The good way

1. Install Python requirements:
   ```bash
   pip install -U -r requirements.txt
   ```
2. Run:
   ```bash
   python -m callsmusic
   ```

### 🐬 Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

### 💵 Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Y-s-B-s/MUSICPLAYET)

## ℹ️ Commands

| Command  | Description                                  |
| -------- | -------------------------------------------- |
| /play    | play the replied audio file or YouTube video |
| /pause   | pause the audio stream                       |
| /resume  | resume the audio stream                      |
| /skip    | skip the current audio stream                |
| /stop    | clear the queue and stop the audio stream    |
| /channel | set chat channel                             |

## 📄 License

### GNU Affero General Public License v3.0

[Read more](https://www.gnu.org/licenses/#AGPL)
