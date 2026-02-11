# storage

storage is a lightweight TypeScript/JavaScript utility library for managing browser storage in a structured and consistent way.

It provides a simple abstraction over common storage mechanisms (such as `localStorage`) and helps standardize read/write operations in frontend applications.

---

## Features

- Simple wrapper around browser storage APIs
- TypeScript support
- Modular architecture
- Test coverage
- Example usage included
- CI-ready configuration

---

## Installation

Using npm:

```bash
npm install <package-name>
```

Or using pnpm:

```bash
pnpm add <package-name>
```

(Replace `<package-name>` with the published package name if available.)

---

## Usage

Basic example:

```ts
import storage from 'storage';

storage.set('key', { name: 'John' });

const value = storage.get('key');
console.log(value);
```

---

## Development

Clone the repository:

```bash
git clone https://github.com/<your-username>/storage.git
cd storage
```

Install dependencies:

```bash
npm install
```

---

## Build

```bash
npm run build
```

---

## Testing

Run tests:

```bash
npm test
```

---

## Project Structure

- `src/` – Source code (TypeScript)
- `test/` – Unit tests
- `example/` – Usage examples
- `docs/` – Documentation
- `tsconfig.json` – TypeScript configuration
- `package.json` – Project metadata and scripts

---
