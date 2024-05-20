# Anime Infinite Scroll Saga

Anime Infinite Scroll Saga is a Next.js web application built with TypeScript, Tailwind CSS, and Framer Motion. It allows users to explore various anime series with an infinite scroll feature.

## Features

- Fetches and displays anime data
- Infinite scroll to continuously fetch and display more anime series
- Responsive grid layout to display anime series
- Server actions to handle API requests

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- Framer Motion (for animations)

## Getting Started

1. Clone the repository

```bash

git clone https://github.com/Mahmoud-D/anime-infinite-scroll-saga.git
```


2. Install dependencies
```bash
   npm install
```

   3. Start the development server
```bash

   npm run dev
```


4. Open http://localhost:3000 in your browser

## Usage

The `Home` function in `page.tsx` fetches anime data and renders it using the `AnimeCard` and `LoadMore` components. The infinite scroll feature is implemented using the `LoadMore` component.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

