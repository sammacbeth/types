This project contains some TypeScript definitions for currently untyped libraries. Definitions may not be complete.

## Usage

### Hypercore

Add the following to your project's `types.d.ts` file:

```typescript
declare module 'hypercore' {
  import { Hypercore } from "@sammacbeth/types/hypercore"
  export = Hypercore.Hypercore
}
```
