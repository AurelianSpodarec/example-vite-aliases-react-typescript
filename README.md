# Custom Vite Path Aliases with React and TypeScript

This repository demonstrates how to set up custom path aliases in Vite using React and TypeScript.

Going from this:

```js
import Button from "./../../../../../../components/Button";
```

To this:

```js
import Button from "#components/Button";
```

or

```js
import Button from "@atoms/Button";
```

You can customize the alias structure however you wish.

For a complete implementation with automatic importing, check out the [main branch](https://github.com/AurelianSpodarec/example-vite-aliases-react-typescript)

Additionally, you can read the full article detailing this setup: https://www.aurelianspodarec.co.uk/blog/how-to-setup-aliases-in-vite-with-react-and-typescript

## Getting Started

Clone the repository:

```bash
git clone https://github.com/AurelianSpodarec/example-vite-aliases-react-typescript.git
cd example-vite-aliases-react-typescript
git checkout custom-aliases
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
