# Vite Path Aliases with React and TypeScript

This repository demonstrates how to set up automatic path aliases in Vite using React and TypeScript.

Going from this:

```js
import Button from "./../../../../../../components/Button";
```

To this:

```js
import Button from "@components/Button";
```

I'll be showing you a custom way to set up each alias manually, and an automatic way on how Next.js does it. To see how Next.js does it, change the branch to [nextjs-path-aliases-in-vite](https://github.com/AurelianSpodarec/example-vite-aliases-react-typescript/tree/nextjs-path-aliases-in-vite)

You can read the full article here: https://www.aurelianspodarec.co.uk/blog/how-to-setup-aliases-in-vite-with-react-and-typescript

## Getting Started

Clone the repository:

```bash
git clone https://github.com/AurelianSpodarec/example-vite-aliases-react-typescript.git
cd example-vite-aliases-react-typescript
```

Install NPM dependencies:

```bash
npm install
```

To start the development server, run:

```bash
npm run dev
```

## Contributions

Feel free to open an issue or create a pull request. I'm always happy to add notes to the article and/or code.  

You can contact me on Twitter/X to direct message if needed.

## License

This project is licensed under the MIT License. Feel free to use the code freely!
