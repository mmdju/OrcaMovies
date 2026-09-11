[**نسخه فارسی**](./README_FA.md) | [**English Version**](./README.md)

---
# Orca Movies — Telegram Bot

> A Telegram bot for movies & TV shows: search, ratings, curated lists, and alerts for new episodes and releases.

![Platform](https://img.shields.io/badge/Platform-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Language](https://img.shields.io/badge/Language-English_%7C_Persian-informational?style=for-the-badge)
![AI Powered](https://img.shields.io/badge/AI_Powered-Workers_AI-FF6B6B?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

---

## Try it

The bot lives on Telegram — open it here:

[![Telegram Bot](https://img.shields.io/badge/Telegram_Bot-@OrcaMoviesBot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/OrcaMoviesBot)
[![Telegram Channel](https://img.shields.io/badge/Channel-@OrcaMovies-blue?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/OrcaMovies)

---

## About

**Orca Movies** is a Telegram bot for finding and tracking movies and TV shows.

Search tolerates typos, phonetic spelling, and titles in English or Persian. Ratings are shown from IMDb, Rotten Tomatoes, and Metacritic. The whole interface is bilingual (English/Persian).

> Movie cards with posters, details, and ratings, right inside Telegram:

![Orca Movies Card Preview](https://i.postimg.cc/pTxjJK5g/file-00000000238c8210af6c7922d378211a.png)

---

## Features

### Search & details

* **Full details:** posters, plot summaries, trailers, age ratings, runtimes, genres, cast & crew.
* **Three ratings side by side:** IMDb, Rotten Tomatoes, and Metacritic.
* **Forgiving search:** handles typos, phonetic spelling, and alternative/localized titles.
* **Filters:** narrow results by genre, year or decade, minimum rating, and popularity.
* **Random picks:** get a highly-rated suggestion from your favorite genre.
* **Trending:** the day's most popular titles, updated regularly.
* **Cast & crew profiles:** bio, birth date, and top titles for actors and directors.
* **Inline mode:** search and share cards in any chat or group.

---

### Curated lists

* **IMDb Top charts:** the best-rated movies and shows of all time.
* **Letterboxd collections:** top films, documentaries, and themed picks.
* **Awards & franchises:** Oscar winners, major universes, and similar collections.
* **Series by genre:** crime, spy, psychological thriller, hidden gems, long-runners, classics.
* **Browsing:** page through lists or open any title with its poster.

---

### Release tracker

* **Movies:** follow upcoming titles, get a message when they release.
* **Shows:** follow ongoing series, get a message when a new episode airs.

---

### Groups

* Add the bot to any group and use it with friends.
* In groups it only answers commands — normal chat stays clean.
* Group commands: `/search`, `/random`, `/lists`, `/help`, `/language`.
* Example: `/search inception` — results and buttons work inside the group.

---

### Personalization

* **Two languages:** switch between English and Persian with one tap (full RTL support).
* **Watchlist:** save titles and find them again later.
* **Help center:** built-in step-by-step guides for search, follows, lists, and saved items.

---

## Bot commands

| Command | Description |
| :--- | :--- |
| `/start` | Start the bot, show the main menu |
| `/search` | Search movies & series (also in groups, e.g. `/search inception`) |
| `/random` | Random highly-rated pick by genre |
| `/lists` | Browse curated collections (IMDb, Letterboxd, genres) |
| `/help` | Open the step-by-step help center |
| `/language` | Switch language (English / Persian) |
| `@OrcaMoviesBot` | Inline search and share cards in any chat |

---

## How it's built

* **Serverless:** runs on the edge, no servers to manage.
* **AI search:** understands plain-language queries and resolves titles phonetically.
* **Multiple sources:** ratings and metadata from several references, de-duplicated and cross-checked.
* **Year-aware matching:** remakes and same-name titles don't get mixed up.
* **Storage:** profiles, watchlists, and follows in a managed database.
* **Scheduled jobs:** release checks and notifications run on their own.
* **Caching:** edge cache keeps responses fast.

---

## Disclaimer

Portfolio showcase. All movie metadata, posters, and images belong to their copyright holders and the open databases they come from.
