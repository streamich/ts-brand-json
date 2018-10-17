# ts-brand-json

TypeScript type for JSON strings.

```ts
import {JSON, json} from 'ts-brand-json';

const str = '{"hello": "world"}' as json<{hello: string}>;

JSON.parse(str).hello; // OK
JSON.parse(str).foo; // Error: ...
```
