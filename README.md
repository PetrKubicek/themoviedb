This is a [Next.js](https://nextjs.org/) project bootstrapped with [`npx create-next-app@latest . --use-pnpm`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Development

I am using [Zed](https://zed.dev/) IDE.

## Set-up with

- Pnpm
- Next 14
- Strict TS Config
- React Strict Mode
- ESLint
- Prettier
- React Testing Library & Jest
- Playwright
- GitHub Actions
- Tailwind
- TanStack Query

## To run tets

### Playwright

(just once)

```bash
pnpm exec playwright install
```

and run with

```bash
pnpm test:e2e
```

### Unit tests

```bash
pnpm test
```
