# Single Search Demo

Demo app for ROR's new single search affiliation matching strategy.

## Usage

Start a local server:

```bash
python -m http.server 8000
```

Open `http://localhost:8000/app/` in a browser.

Enter an affiliation string or click "Example" to load a random test case from `app/examples.json`.

A test instance is also available at [https://adambuttrick.github.io/single-search-demo/app/](https://adambuttrick.github.io/single-search-demo/app/)

## API Queries/Parameters

- Multisearch: `https://api.ror.org/organizations?affiliation={string}`
- Single Search: `https://api.ror.org/organizations?affiliation={string}&single_search=true`
