# Table Components

[![npm version](https://badge.fury.io/js/%40modsynth%2Ftable-components.svg)](https://www.npmjs.com/package/@modsynth/table-components)
[![npm downloads](https://img.shields.io/npm/dm/@modsynth/table-components.svg)](https://www.npmjs.com/package/@modsynth/table-components)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Table components with TanStack Table and utilities

Part of the [Modsynth](https://github.com/modsynth) ecosystem.

## Features

- TanStack Table (React Table v8) integration
- Sorting, filtering, pagination
- TypeScript support
- ✨ **CSV Export**: Export table data to CSV (v0.2.0)
- ✨ **Pagination Helpers**: Simplified pagination utilities (v0.2.0)

## What's New in v0.2.0

- **CSV Export**: `exportToCSV()` function for data export
- **Pagination Utilities**: Helper functions for pagination logic

## Installation

```bash
npm install @modsynth/table-components @tanstack/react-table
```

## Usage

```tsx
import { useReactTable, getCoreRowModel, flexRender } from '@modsynth/table-components';

const columns = [
  { accessorKey: 'name', header: 'Name' },
  { accessorKey: 'age', header: 'Age' }
];

const data = [{ name: 'John', age: 30 }];

const table = useReactTable({
  data,
  columns,
  getCoreRowModel: getCoreRowModel()
});
```

## Version

Current version: `v0.2.0`

## License

MIT
