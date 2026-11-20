# OpenCinema

OpenCinema is an open-source movie and TV discovery app built with Next.js. Browse titles, search the TMDB catalog, and launch the available video players. The app does not provide accounts, cloud-synced watchlists, or viewing history.

## Features

- Browse popular, trending, upcoming, and top-rated movies and TV shows.
- Search for titles, actors, and genres.
- Responsive layout with light and dark themes.
- Installable progressive web app.

## Technology

- Next.js App Router, React, and TypeScript
- Tailwind CSS and HeroUI
- TanStack Query
- TMDB API

## Run locally

1. Install [Bun](https://bun.sh/).
2. Install dependencies with `bun install`.
3. Copy `.env.local.example` to `.env.local` and set `TMDB_ACCESS_TOKEN` to a TMDB API read access token.
4. Start the development server with `bun dev`.
5. Open `http://localhost:3000`.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow.

## License

OpenCinema is distributed under the MIT License. See [LICENSE](LICENSE) for the original copyright notice and terms.
