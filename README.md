This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# 1. NextJS 버전
```
npx create-next-app@14.1.0
```

# 2. 필수 패키지
```
yarn add react-spinners@^0.13.8
yarn add react-icons@^5.0.1
yarn add tailwind-merge@^2.2.1
yarn add zustand@^4.5.0
```

# 3. install shadcn
- 설치법 : https://ui.shadcn.com/docs/installation/next
- https://ui.shadcn.com/docs/components/carousel

```npx shadcn-ui@latest init
✔ Which style would you like to use? › Default  
✔ Which color would you like to use as base color? › Slate  
✔ Would you like to use CSS variables for colors? … no / yes
```

- tailwind.config.ts > content 부분에 js,ts,jsx,tsx,mdx 작성 되어 있는지 확인


# 4. darkmod
- https://ui.shadcn.com/docs/dark-mode/next

```
yarn add next-themes
```
- 다크모드 provider 제공
- .dark 클래스에 다크 모드 관련 색상 정의


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
