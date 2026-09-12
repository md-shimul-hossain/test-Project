# Cursor

Node.js + TypeScript project.

## Tech stack

- Runtime: Node.js (v20+)
- Language: TypeScript
- Module system: ESM (`"type": "module"`)
- Dev runner: `tsx`
- Compiler: `tsc` (output in `dist/`)

## Scripts

- `npm run dev` — run in watch mode
- `npm run build` — compile TypeScript
- `npm start` — run compiled `dist/index.js`

## Layout

- `src/` — TypeScript source
- `dist/` — compiled JavaScript
- `src/index.ts` — entry point

## Notes

Prefer TypeScript in `src/`. Do not add JavaScript source files for app code.
