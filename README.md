<p align="center">
    <img src="./favicon.svg" width="96" alt="Thor" />
    <h3 align="center">Thor</h3>
    <p align="center">OpenRouter models ranked by cost.</p>
    <p align="center">
        <a href="https://thor.clivern.com">
            <img src="https://img.shields.io/badge/Live-thor.clivern.com-111111.svg" alt="Live site" />
        </a>
    </p>
</p>

<br/>

Thor lists [OpenRouter](https://openrouter.ai) models sorted by average price, with input and output cost per million tokens, relative cost vs the cheapest paid model, and context length.

## Features

- Live pricing from the OpenRouter models API
- Input, output, and average cost (`$/M` tokens)
- Includes chat and decisions models
- Search by model or provider
- Filter: all, paid only, or free only

## Usage

Open the live site: [thor.clivern.com](https://thor.clivern.com)

Or run locally:

```zsh
# from the repo root
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## License

Copyright © 2026 [Clivern](https://github.com/Clivern).
