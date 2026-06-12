# Block Programming Environment

An early browser-based visual programming environment recovered from a Replit
export. The original folder was named `program`, but the project itself is a
Scratch-style block editor and runtime.

## What It Does

- Provides draggable/clickable command blocks, expression blocks, and nested
  program blocks.
- Saves and opens projects through `localStorage`.
- Generates JavaScript from the block structure and runs it inside an iframe.
- Includes runtime commands for sprites/characters, movement, text, audio,
  variables, lists, loops, key input, mouse position, notifications, geolocation,
  and compass direction.

## Project Shape

The implementation is mostly contained in `index.html`, including the styles,
editor UI, code generation, and runtime. `script.js` and `style.css` were
preserved as empty early scaffold files because their timestamps show the project
existed by May 2021.

## Date Notes

Replit did not export version history, so the commits use preserved file
modified times:

- `2021-05-07`: empty `script.js` and `style.css` scaffold.
- `2022-02-05`: main block programming environment in `index.html`.
- `2022-03-29`: Replit Nix config.
- `2022-10-04`: Replit project config.

These dates are evidence of when files were last modified, not exact original
creation dates.

## Recovery Notes

The local Replit `.config` directory was omitted because it is editor/runtime
state, not project source.
