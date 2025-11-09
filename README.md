# Table Components

> Table components (TanStack Table)

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
v0.1.0

## License
MIT
