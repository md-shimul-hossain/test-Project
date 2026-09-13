# test-projects

A Node.js project written in TypeScript (ESM).

## Requirements

- Node.js 20 or later
- npm

## Setup

```bash
npm install
```

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Run `src/index.ts` in watch mode with `tsx` |
| `npm run build` | Compile TypeScript to `dist/` |
| `npm start` | Run the compiled app (`dist/index.js`) |

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Modules:** ESM (`"type": "module"`)
- **Dev runner:** [tsx](https://github.com/privatenumber/tsx)
- **Compiler:** `tsc`
- **Env:** [dotenv](https://github.com/motdotla/dotenv)

## Project layout

```
src/           TypeScript source
src/index.ts   App entry point
dist/          Compiled JavaScript (after build)
tsconfig.json  TypeScript config
cursor.md      Project notes for Cursor
```

## License

ISC
git