# Typing Test - Rust

A typing test (calculates your **WPM** words per minute) in the terminal, written in rust!

> yet another nerd project :)

## Usage

Really quite simple yet again!

Choose the desired quote length using the **left and right arrows**, and **tab** to generate a new quote. When you have a quote you'd like to type, just start typing! It will show your errors in red, which you can either correct or leave.

Press **escape** at any time to leave.

## Demo


https://github.com/user-attachments/assets/3968cf39-4dee-4317-9e8d-dbb40be03af2


## Installation

You can either download the executable from the RELEASE tab, or compile it yourself by:

1. cloning the repo

```
git clone https://github.com/KodeurKubik/wpm-rust
cd wpm-rust
```

2. running with [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)

```
cargo run --release
```

## Credits

To (MonkeyType)[https://monkeytype.com] for the quotes dataset (`english.json`)[https://github.com/monkeytypegame/monkeytype/blob/master/frontend/static/quotes/english.json]
