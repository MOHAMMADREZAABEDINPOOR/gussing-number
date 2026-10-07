<div align="center">

<img src="assets/readme/hero.gif" width="1200" alt="GUESS THE NUMBER — rotating 3D geometry" />

**[English](README.md) · [فارسی](README.fa.md)**

<img src="assets/readme/identity.svg" width="1200" alt="learning / English and Persian documentation" />

</div>

# GUESS THE NUMBER

A console guessing game that chooses a number from 1 to 10 and records the best attempt count during the current session.

[GitHub](https://github.com/MOHAMMADREZAABEDINPOOR/gussing-number) · [PIMX / Profile](https://github.com/MOHAMMADREZAABEDINPOOR) · [Static artwork](assets/readme/hero.png)

## Features

- Higher/lower hints
- Input range validation
- Replay prompt
- In-memory high score

## Stack

| Tool | Version / source |
|---|---|
| Python | `standard library / source imports` |

## Getting started

Python 3; a desktop/Tk installation for Tkinter or turtle examples. Tkinter is provided by the Python installation, not pip. Legacy dependencies may need a compatible Python version.

```bash
git clone https://github.com/MOHAMMADREZAABEDINPOOR/gussing-number.git
cd gussing-number

python -m http.server 8000
```

## Configuration

No standard environment template is defined. Standalone exercises need no external configuration; inspect any service constants or paths in the source before running.

## Usage

Run game.py, enter your name, answer Yes and guess a number. The program gives hints until you find the answer.

## Project structure

| Path | Role |
|---|---|
| [`assets/`](assets/) | Brand/media/README assets |
| [`game.py`](game.py) | Project entry/configuration file |

## Commands and checks

No automated test command is declared in a manifest. Verify behavior through a local example run.

## Deployment

This is a local learning exercise, not a public service. Browser exercises can use static hosting.

## Limitations

Scores reset when the process exits. This exercise uses only the Python standard library.

## Troubleshooting

- GUI unavailable: use a desktop Python installation with Tk for Tkinter/turtle examples.
- Invalid input: use the numeric/text format expected by the selected script.

## Contributing

Create a focused branch, verify the affected behavior and explain the change clearly. Keep private data, build outputs and local databases out of commits.

## License

No repository-level license file is included in this snapshot. Public visibility alone does not grant reuse rights; contact the repository owner for terms.

---

Part of **PIMX** · Documentation in English and Persian.
