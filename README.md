# ðµ [Calls Music](https://github.com/callsmusic) Remix

Operasyonel ve exprimental Telegram mÃ¼zik botu.

---

## ð Achievements

-   [Mentioned in Awesome grammY](https://github.com/grammyjs/awesome-grammY)
-   [Mentioned in Awesome tgcalls](https://github.com/tgcalls/awesome-tgcalls)

## â¨ Features

### ð Streams whatever you like

You can stream audio files, voice messages, YouTube videos with any duration, YouTube lives, YouTube playlists and even custom inputs like radios or files in the place it is hosted!

### ð Streams in multiple places

Allows you to stream different things in multiple chats simultaneously. Each chat will have its own song queue.

### â¡ï¸ Fast & Light

Starts streaming your inputs while downloading and converting them. Also, it doesn't make produce files.

### ð Has cool controls

Lets you adjust volume, loop, pause, resume, mute, unmute. Also, it has a control panel.

### ð®ð»ââï¸ Safe

Accepts a command in 5 seconds, restricts control and sensitive commands to admins.

### ð£ Speaks different languages

Remix is multilingual and speaks [various languages](#available-languages), thanks to the translators.

### ð Clean

Its responses and source code don't say anything referring to Calls Music. Except some places like [`package.json`](./package.json).

## ð Running

1. Copy `example.env` to `.env` and fill it with your credentials.
2. Install dependencies and build:

```bash
npm install
```

3. Start:

```bash
npm start
```

## âï¸ Cloud platforms

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Mehmetbaba55/MamiRemix)

## â Configuring

-   `BOT_TOKEN`: Telegram bot token.
-   `STRING_SESSION`: A GramJS/Telethon string session. You can generate one [here](https://ssg.rojser.best/).
-   `API_ID`: Telegram app ID.
-   `API_HASH`: Telegram app hash.
-   `LOCALE`: An [available](#available-languages) bot language. Default: `en`.
-   `MAX_PLAYLIST_SIZE`: Max YouTube playlist size. Default: `10`.
-   `COOKIES`: Cookies for YouTube requests. Default: none.

## ð Commands

### ð¶ stream

#### _Aliases: s, play, p_

Takes a custom input, audio file, voice message or YouTube video/playlist link/ID and streams/queues it.

Custom inputs should be passed like this:

```text
/stream custom your_custom_input
```

### ð search

#### _Aliases: find_

Searches for a YouTube video.

### â cancel

Cancels the active YouTube video search.

### ð¢ playlist

#### _Aliases: pl, list_

Streams a YouTube playlist.

### ðµ now

#### _Aliases: ns, cs, np, cp_

Displays the currently streamed item.

### ð panel [ð®ð»ââï¸]

#### _Aliases: menu, control, controls_

Opens the controls panel.

### ð loop [ð®ð»ââï¸]

#### _Aliases: repeat_

Toggles loop.

### ð shuffle [ð®ð»ââï¸]

#### _Aliases: sh, mix_

Shuffles the items in the queue.

### ð volume [ð®ð»ââï¸]

#### _Aliases: vol, v_

Sets the volume.

### â¸ pause [ð®ð»ââï¸]

Pauses the stream.

### â¶ï¸ resume [ð®ð»ââï¸]

#### _Aliases: re, res, continue_

Resumes the stream.

### ð mute [ð®ð»ââï¸]

#### _Aliases: m_

Mutes the stream.

### ð unmute [ð®ð»ââï¸]

#### _Aliases: um_

Unmutes the stream.

### â© skip [ð®ð»ââï¸]

#### _Aliases: next_

Skips the current stream.

### â¹ leave [ð®ð»ââï¸]

#### _Aliases: stop_

Clears the queue and removes the bot from the call.

### ð cache [ð®ð»ââï¸]

Deletes caches.

## ð£ Available languages

```text
bn    Bengali
ckb   Central Kurdish
de    German
en    English
es    Spanish
fa    Farsi
id    Indonesian
ml    Malayalam
pt_BR Brazilian Portuguese
si    Sinhalese
tr    Turkish
```

## ð« Support

Join [our chats](https://callsmusic.me).

## ð Contributing

New languages, bug fixes and improvements following [our contribution guidelines](./CONTRIBUTING.md) are warmly welcomed!

## â¨ Inspiration

-   [eritislami/evobot](https://github.com/eritislami/evobot)

## ð License

Remix is licenced under the GNU Affero General Public License v3.0. Read more [here](./LICENSE).
