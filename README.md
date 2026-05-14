# Toki Pona Memory Matching (トキポナめくりあわせ)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple memory matching game to help you learn Toki Pona words and their Japanese translations. Flip the cards to find the matching pairs.

## Demo

**Play the game here: https://code4fukui.github.io/mekuriawase-tokipona/**

## Features

-   **Learn Toki Pona:** Match Toki Pona words with their Japanese translations.
-   **Unique Visuals:** Cards feature the Toki Pona word written in the beautiful `linja suwi` font.
-   **Dynamic Layout:** The 16-card grid is randomized on every playthrough for a new challenge.
-   **Smooth Animations:** Cards flip with a clean CSS 3D transform effect.
-   **Time Tracking:** See how fast you can clear the board.
-   **Instant Replay:** A "Retry" button lets you start a new game immediately.

## Data & Dependencies

-   Word data is sourced from the [tok2jpn](https://github.com/code4fukui/tok2jpn) Toki Pona-Japanese dictionary CSV.
-   The game is built with vanilla JavaScript and utilizes two helper libraries:
    -   [CSV.js](https://js.sabae.cc/CSV.js) for parsing the dictionary data.
    -   [shuffle.js](https://js.sabae.cc/shuffle.js) for randomizing the card layout.

## Credit

This project is a modification of the [mekuriawase-fukui](https://github.com/code4fukui/mekuriawase-fukui) memory game engine, originally created by [Taisuke Fukuno](http://fukuno.jig.jp/757).

## License

[MIT](LICENSE)