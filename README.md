# Unicode Blocks

> Unicode blocks with ranges, script, and character counts

**Category:** dev-ref · **Data:** Unicode.org · **License:** Unicode-DFS-2.1 · **Updates:** yearly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/blocks.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/unicode-blocks/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/unicode-blocks/data.json');
const data = await res.json();
```

## Data

- Source: Unicode.org
- License: Unicode-DFS-2.1
- Last updated: `2026-08-25T03:10:21.665Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/unicode-blocks/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

Unicode-DFS-2.1
