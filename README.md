# ts-brand-json

TypeScript type for JSON strings.

```ts
const str = '{"hello": "world"}' as JSONSTR<{hello: string}>;

JSON.parse(str).hello; // OK
JSON.parse(str).foo; // Error: ...
```
