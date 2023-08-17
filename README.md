# 🍡 jellycrew-front

## ⚙️ 프로젝트 구성

```
. # root
├── apps
│   └── jc-admin # Next.js
│   └── jc-creator-dashboard # Next.js
│   └── jc-open-market # Next.js
└── common
    └── jc-design # React + Storybook
```

## 💻 프로젝트 실행

```bash
yarn

# jc-admin 실행
yarn admin dev

# jc-creator-dashboard 실행
yarn dashboard dev

# jc-open-market 실행
yarn market dev

# jc-design 실행
yarn design sb
```

## 🛠️ 기술 스택

- Node.js v18.17.1
- Yarn Berry (node-modules)
- Yarn Workspaces

### apps

- Next.js
- React
- TypeScript
- Tailwind CSS

### common

#### jc-design

- React
- TypeScript
- Storybook
- Vite
- SWC
