# expo-wind-zustand

[Go expo-wind-zustand Github](https://github.com/scorchedrice/expo-wind-zustand)

[Go npm](https://www.npmjs.com/package/expo-wind-zustand)

✨ **Expo + TailwindCSS + Zustand** 기반의 프로젝트를 빠르게 시작할 수 있는 템플릿 생성 CLI입니다.

## 🚀 주요 기능

✅ Expo 기반 React Native 프로젝트 템플릿

✅ TailwindCSS (NativeWind) 설정, 버전 불일치 이슈 해결

✅ expo-lint 설정 (recommend) 및 prettier-plugin-tailwind 적용

✅ Zustand로 상태관리 기본 설정 포함

✅ Storybook 설정 포함

## 📦 사용법

```bash
npx expo-wind-zustand
```

실행 시 아래와 같은 흐름으로 진행됩니다.

1. 프로젝트의 이름을 입력받고 디렉토리 생성
2. [Github 레포지토리](https://github.com/scorchedrice/expo-wind-zustand)에서 코드 복사 진행

```bash
cd [projectName]
npm install
npm run start
```

storybook을 사용하고 싶다면

```bash
npm run storybook
```

## 📁 기본 디렉토리 구조

```
[projectName]/
├── app/                # expo-router 기반 라우팅
├── components/         # UI 컴포넌트
├── hooks/              # 커스텀 훅 (zustand 포함)
├── constants/          # 상수 정의
├── tailwind.config.js
├── tsconfig.json
├── global.css
└── ...
```

## 제작자

[scorchedrice](https://github.com/scorchedrice)
