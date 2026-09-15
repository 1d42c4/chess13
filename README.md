# Make a Plan

**[Open the live GitHub Pages course](https://1d42c4.github.io/chess13/)**

From positional clues to moves you can explain. Read pawn structure and piece activity, choose a realistic target, and revise a plan when the position changes.

## Who it is for

Players who see basic tactics but feel lost when nothing immediate is happening.

This is an extensive course through a defined practical skill area, not a claim to cover all of chess. The full four-course route is aimed at human learners building reliable habits from the basics toward club play.

## What is included

- 24 distinct lessons in four modules, each with an explanation, task, answer, common mistake, and recall prompt.
- 144 interactive exercises with saved answer data.
- A six-week study plan and links to the full 24-week route.
- Browser-local progress, a review queue, private study notes, and progress import/export.
- A printable workbook with an answer key, Markdown notes, PGN positions, and structured JSON exercises.
- Offline scripts and styles; no account, analytics, remote fonts, or runtime engine service required.

## Modules

1. Evaluate before planning
2. Read the pawns
3. Coordinate the pieces
4. Convert, defend, and review

## Start here

[Lesson directory](https://1d42c4.github.io/chess13/) · [Practice lab](https://1d42c4.github.io/chess13/practice.html) · [Study plan](https://1d42c4.github.io/chess13/study-plan.html) · [Downloads](https://1d42c4.github.io/chess13/downloads.html) · [Sources and verification](https://1d42c4.github.io/chess13/sources.html)

## The four-course collection

| Repository | Course | Live site |
| --- | --- | --- |
| [chess11](https://github.com/1d42c4/chess11) | See the Board | [Open](https://1d42c4.github.io/chess11/) |
| [chess12](https://github.com/1d42c4/chess12) | Calculate with Purpose | [Open](https://1d42c4.github.io/chess12/) |
| [chess13](https://github.com/1d42c4/chess13) | Make a Plan | [Open](https://1d42c4.github.io/chess13/) |
| [chess14](https://github.com/1d42c4/chess14) | Finish the Game | [Open](https://1d42c4.github.io/chess14/) |

## Use offline

Choose **Code → Download ZIP**, extract the archive, and open `index.html` in a browser. External reference and analysis links require internet access. Progress is browser-local; export it before clearing storage or changing devices.

## Verification

All 144 exercises use original positions reached through legal moves. Answers are deterministic counts computed from chess.js attack maps, legal moves, or pawn locations. Attack-map questions explicitly count geometric attacks, including pinned pieces; legal-move questions separately enforce king safety. A structural count is not a claim that the position is strategically won.

See [VALIDATION.json](VALIDATION.json) for check results. The original prose is AI-created educational material; report a concrete correction with its lesson or exercise ID. No rating improvement is promised.

## Maintain and publish

The editable source is [data/course.json](data/course.json). Run `node tools/build.mjs` to regenerate the pages, then `node tools/validate.cjs` for content, answer-legality, PGN, and link checks. The browser data and downloadable files are regenerated from the same source.

GitHub Pages serves the root of `main` with `.nojekyll`. Active branch rules require pull requests, prevent force pushes, and prevent deleting the default branch, with no bypass actors. Repository owners can still change settings or delete the repository.

## Credits

Original course writing, interface, and generated practice positions were prepared with AI for 1d42c4. Cburnett SVG chess pieces by Colin M. L. Burnett are included unmodified under GPL-2.0-or-later, with [source and attribution](assets/pieces/README.md) and the [full license](assets/pieces/COPYING.txt). The bundled chess.js library is BSD-2-Clause licensed; its full notice is in [vendor/chess-LICENSE.txt](vendor/chess-LICENSE.txt). Stockfish was used for local analysis and is not redistributed here. Tablebase facts are credited to the Lichess Syzygy service.
