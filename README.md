# Exercism — Python Track

My solutions to the [Exercism Python track][track], kept as a personal learning
reference. Each folder is one self-contained exercise, shipped with Exercism's own
`README.md` and `HINTS.md`, my solution file, and the test suite that grades it.

Exercises are grouped below **by Python concept** rather than by completion order, so
you can jump straight to the topic you want to revisit — loops, lists, dictionaries, and
so on.

Written and tested against **Python 3.13**.

## Concept index

[Basics & Functions](#basics--functions) ·
[Numbers](#numbers) ·
[Booleans](#booleans) ·
[Comparisons](#comparisons) ·
[Conditionals](#conditionals) ·
[Loops](#loops) ·
[Strings](#strings) ·
[Lists](#lists) ·
[Tuples](#tuples) ·
[Dictionaries](#dictionaries) ·
[Unpacking & Multiple Assignment](#unpacking--multiple-assignment)

---

## Basics & Functions

Getting a first program to run, then writing real functions with constants and
documentation.

| Exercise | File | What it covers |
| --- | --- | --- |
| [Hello World](hello-world/) | `hello_world.py` | The traditional first program — `def` and `return` |
| [Guido's Gorgeous Lasagna](guidos-gorgeous-lasagna/) | `lasagna.py` | Name assignment, constants in `SCREAMING_SNAKE_CASE`, function definitions, comments, docstrings |

## Numbers

*Building a currency calculator for a friend who is worried about being scammed at
exchange counters.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Currency Exchange](currency-exchange/) | `exchange.py` | `int` vs `float`, arithmetic, floor division `//`, modulo `%`, casting with `int()` |

## Booleans

*Implementing the state rules of Pac-Man.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Ghost Gobble Arcade Game](ghost-gobble-arcade-game/) | `arcade_game.py` | The `bool` type, `and` / `or` / `not`, returning a Boolean expression directly instead of `if/else` |

## Comparisons

*Scoring a hand of Blackjack.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Black Jack](black-jack/) | `black_jack.py` | `==`, `<`, `>`, membership with `in`, identity with `is`, comparing values across types |

## Conditionals

*A control system that keeps a nuclear reactor at criticality — without a meltdown.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Meltdown Mitigation](meltdown-mitigation/) | `conditionals.py` | `if` / `elif` / `else`, combining conditions, testing against value ranges |

## Loops

*Correcting student exams — rounding, filtering and ranking scores.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Making the Grade](making-the-grade/) | `loops.py` | `for` loops, `range()`, `enumerate()`, `zip()`, list comprehensions |

## Strings

*Helping a little sister with her vocabulary homework, then editing her school essay.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Little Sister's Vocabulary](little-sisters-vocab/) | `strings.py` | Immutability, concatenation, indexing, slicing (`[1:]`, `[:-4]`), `.split()`, `.join()`, `.strip()` |
| [Little Sister's Essay](little-sisters-essay/) | `string_methods.py` | `.title()`, `.strip()`, `.replace()`, `.endswith()` |

## Lists

*Tracking poker rounds in Vegas, then managing the two queues of a roller coaster.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Card Games](card-games/) | `lists.py` | List literals, indexing, slicing, `len()`, `sum()`, `list()`, `enumerate()`, list comprehensions |
| [Chaitana's Colossal Coaster](chaitanas-colossal-coaster/) | `list_methods.py` | `.append()`, `.insert()`, `.pop()`, `.remove()`, `.index()`, `.count()`, `sorted()`, and mutation vs. copying |

## Tuples

*Two pirates cross-referencing their treasure lists against map coordinates.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Tisbury Treasure Hunt](tisbury-treasure-hunt/) | `tuples.py` | The `tuple()` constructor, immutability, indexing, slicing, concatenation with `+` |

## Dictionaries

*Running a warehouse inventory, then an automated grocery shopping cart.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Inventory Management](inventory-management/) | `dicts.py` | Building dicts, `.get()`, `.items()`, `.pop()`, iterating, adding and removing keys |
| [Mecha Munch Management](mecha-munch-management/) | `dict_methods.py` | `.update()`, `.get()`, `.items()`, `dict.fromkeys()`, sorting dict entries with `sorted()` |

## Unpacking & Multiple Assignment

*Fixing the route and wagon data of a locomotive engineer.*

| Exercise | File | What it covers |
| --- | --- | --- |
| [Locomotive Engineer](locomotive-engineer/) | `locomotive_engineer.py` | `*args` and `**kwargs`, the `*` / `**` unpacking operators, multiple assignment, nested unpacking |

---

## Running the tests

Every exercise ships with a pytest suite next to the solution file.

```bash
python -m pytest                     # run every exercise
python -m pytest making-the-grade/   # run a single exercise
```

pytest and pylint (`--max-line-length=130`) are already configured for the workspace in
[`.vscode/settings.json`](.vscode/settings.json).

## Credits

Exercise statements, test suites and per-exercise `README.md` / `HINTS.md` files come
from [Exercism][track] and belong to their authors. Only the solution files are my own
work.

[track]: https://exercism.org/tracks/python