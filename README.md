# My LoL Page

내일배움캠프 스파르타 주특기플러스 과정 개인프로젝트

<br>

## ✨ 프로젝트 소개

-   작업기간 : 2025/03/10 ~ 2025/03/19
-   TypeScript와 Next.js를 활용한 LoL 정보 페이지
-   Tailwind를 활용한 반응형 웹페이지

<br>

## 🖥️ 사이트 소개

-   배포사이트 : [my-lol-apppp](my-lol-appp.vercel.app)
-   가능하다면 사이트 동작을 녹화한걸 gif로 만들어서 처리  
    (gif는 한개의 파일이 10mb를 넘길 수 없기 때문에 용량을 고려해야함)  
    동영상 녹화는 cmd+shift+5로 하고, 영상 변환 및 용량 처리는 [iloveimg](https://www.iloveimg.com/ko)에서 처리

## 🛠️ 주요기능 및 구조

-   lol캐릭터, 아이템, 금주의 무료 챔피언 로테이션 페이지 제공
-   챔피언 상세정보 제공 
-   다크모드 지원
-   반응형 페이지 지원

### 폴더구조

```
📁 my-lol-app
├─ .eslintrc.json
├─ README.md
├─ next.config.mjs
├─ package.json
├─ postcss.config.mjs
├─ public
│  └─ assets
│     ├─ StarGuardian19_Celebration_BG.png
│     └─ logo.svg
├─ src
│  ├─ app
│  │  ├─ api
│  │  │  └─ rotation
│  │  │     └─ route.ts
│  │  ├─ champions
│  │  │  ├─ [id]
│  │  │  │  └─ page.tsx
│  │  │  └─ page.tsx
│  │  ├─ error.tsx
│  │  ├─ favicon.ico
│  │  ├─ fonts
│  │  │  ├─ ChosunCentennial_otf.otf
│  │  │  ├─ GeistMonoVF.woff
│  │  │  ├─ GeistVF.woff
│  │  │  ├─ HeirofLightOTFBold.otf
│  │  │  └─ HeirofLightOTFRegular.otf
│  │  ├─ global-error.tsx
│  │  ├─ globals.css
│  │  ├─ items
│  │  │  └─ page.tsx
│  │  ├─ layout.tsx
│  │  ├─ loading.tsx
│  │  ├─ page.tsx
│  │  ├─ provider.tsx
│  │  └─ rotation
│  │     └─ page.tsx
│  ├─ components
│  │  ├─ ChampionComp.tsx
│  │  ├─ DetailStatsComp.tsx
│  │  ├─ MainCardComp.tsx
│  │  ├─ NavBar.tsx
│  │  └─ SidebarComp.tsx
│  ├─ constant
│  │  ├─ fetchURL.ts
│  │  └─ routePath.ts
│  ├─ hooks
│  │  ├─ championQueries.tsx
│  │  └─ getVersionQueries.tsx
│  ├─ public
│  ├─ store
│  │  ├─ darkModeStore.ts
│  │  └─ menuOpenStore.ts
│  ├─ styles
│  ├─ types
│  │  ├─ Champion.ts
│  │  ├─ ChampionDetail.ts
│  │  ├─ ChampionRotation.ts
│  │  └─ Item.ts
│  └─ utils
│     ├─ riotApi.ts
│     └─ serverApi.ts
├─ tailwind.config.ts
├─ tsconfig.json
└─ yarn.lock

```
<br>

## 🔥 트러블 슈팅

-   [[트러블슈팅] 버전정보 가져와서 쓰기 참 으릅다 으르워]([#%EB%A7%81%ED%81%AC](https://mangoman-e-ya.tistory.com/97))
-   [[트러블슈팅] build가 안된다...queryClient type 이슈](https://mangoman-e-ya.tistory.com/100)
-   [[트러블슈팅] 로딩컴포넌트를 넣었는데 왜 보이지 않을까??](https://mangoman-e-ya.tistory.com/101)

<br>

## 🏷 TechStack

![typescript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![nextjs](https://img.shields.io/badge/nextjs-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![tailwind](https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![tanstack](https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)