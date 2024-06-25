This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Ampli Cli demo

- Ampli 사용하는 코드 위치 [pages/withAmpli]
- Ampli 사용하지 않았을 경우 [pages/withoutAmpli]

## How to start

1. ampli 클라이언트 설치 -> [link](https://amplitude.com/docs/sdks/ampli/ampli-cli)
2. 노드 dependencies 설치 -> `npm install` or `yarn install` or `pnpm install`
3. 앰플리튜드 데이터 탭에서 원하는 데이터 정의/설정
4. `ampli pull` 실행해서 schema 생성
5. `pages/_app.tsx` 에 API KEY 설정

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.
