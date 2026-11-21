# Santhosh N — Portfolio

A personal portfolio built with Vue 3, Vite, TypeScript, Tailwind CSS and Three.js.

## Run locally

Install Node.js 20 or newer, then run:

```sh
npm install
npm run dev
```

Use `npm run build` to create the static site in `dist/` and `npm run preview` to preview the build.

## Contact form

The form opens the visitor's email application with a prepared message. It does not store submissions. WhatsApp and direct email links are also provided.

## Publication

A repository alone does not publish the website. Deploy the contents of `dist/` to a static web host, then update the canonical Open Graph and Twitter image URLs in `index.html` to the actual website address. The included Cloudflare Pages chat prototype in `functions/` is not connected to the current site and is not required for the portfolio.
