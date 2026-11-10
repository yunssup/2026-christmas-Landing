<div align="center">

🎄 ✨ 🎁 ✨ 🎄

# 2026 신내동성당 성탄제 랜딩페이지

### 🔔 신(내)의 한수 : 감정 투자 대작전 🔔

*신내동성당 중고등부 주일학교 2026 성탄제와 성탄 밴드 미사를 알리는 홍보 페이지*

<br/>

![HTML](https://img.shields.io/badge/HTML-single_file-1a4a3b?style=for-the-badge&logo=html5&logoColor=f1d495)
![CSS](https://img.shields.io/badge/CSS-vanilla-b3262e?style=for-the-badge&logo=css3&logoColor=f1d495)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-1a4a3b?style=for-the-badge&logo=javascript&logoColor=f1d495)
![Mobile](https://img.shields.io/badge/Mobile-Ready-b3262e?style=for-the-badge&logo=googlechrome&logoColor=f1d495)

❄️ ⛄ ❄️ ⛄ ❄️

</div>

---

## 🎅 어떤 페이지인가요?

성탄제 게임 **신(내)의 한수 : 감정 투자 대작전**과 성탄 **밴드 미사**를 소개하는 한 장짜리 랜딩페이지예요.
빌드 도구나 라이브러리 없이 `index.html` 파일 하나로 동작합니다.

게임 웹앱은 별도 저장소에 있어요 👉 [yunssup/2026-christmas](https://github.com/yunssup/2026-christmas)

---

## 📅 행사 일정

| | 행사 | 일시 | 장소 |
|:-:|:--|:--|:--|
| 🎮 | **성탄제 게임** | 12월 27일 (일) 오전 10시 | 신내동성당 |
| 🎸 | **초중고 합동 성탄 미사** (밴드) | 12월 25일 (금) 오후 3시 | 신내동성당 |
| 🎸 | **중고등부 성탄 미사** (밴드) | 12월 27일 (일) 오전 10시 | 신내동성당 |

---

## 📜 게임 소개

매 라운드 **성경 이야기를 뉴스처럼 바꾼 헤드라인**이 하나 공개돼요.
팀원들과 어떤 성경 이야기인지 추리하고, 그 장면에서 **어떤 감정이 오르고 내릴지** 예측해 투자합니다.
10라운드가 끝났을 때 자산이 가장 많은 팀이 🏆 **2026 신내동 투자왕**!

| 항목 | 내용 |
|:--|:--|
| 👥 참가 팀 | 6팀 |
| 💰 초기 자금 | 팀마다 1,000,000원 |
| 🪙 정보 코인 | 팀마다 7개 |
| 🔔 진행 | 총 10라운드 |
| 💭 투자 대상 | 탐욕 · 사랑 · 질투 · 믿음 · 분노 · 용기 · 나태 · 희망 · 슬픔 · 절제 · 두려움 · 화합 |

---

## 🎸 밴드 라인업

| 파트 | 이름 |
|:--|:--|
| 🎤 보컬 | 송민준 · 이사랑 |
| 🎸 기타 | 송문권 |
| 🎹 키보드 | 김해율 |
| 🥁 드럼 | 박재인 |

---

## ✨ 페이지 구성

| 섹션 | 내용 |
|:--|:--|
| 🎄 **첫 화면** | 제목, 행사 일시, **성탄제까지 D-day** (매일 자동으로 줄어듦) |
| 📈 **감정 시세 띠** | 12가지 감정이 주식 시세처럼 흘러가는 전광판 (예시 시세) |
| 📜 **게임 소개** | 게임 방법과 연습 문제 (정답 보기 버튼) |
| 💭 **상장 종목** | 감정 12개 카드, 시세 미리보기 버튼 |
| 🔔 **라운드 흐름** | 헤드라인 공개 → 팀별 회의 → 투자 → 수익률 확인 → 다음 라운드 |
| 🏆 **투자왕 시상대** | 1~3위 시상대 |
| 🎸 **밴드 미사** | 미사 일정과 밴드 라인업 |
| 🎁 **참가 안내** | 대상, 일시, 문의 |

**🎨 디자인**
- 눈 내리는 겨울 낮 하늘 배경과 하얀 카드
- 소나무 초록 · 베리 레드 · 골드 컬러, 캔디케인 줄무늬
- 둥글고 귀여운 글씨체 (주아 · 고운돋움 · 개구)
- 화면 위로 소복소복 내리는 눈 ❄️ (움직임 줄이기 설정을 켜면 꺼져요)
- 휴대폰 · 태블릿 · PC 어디서나 깨지지 않는 반응형 레이아웃

---

## 🛷 실행 방법

`index.html`을 브라우저로 열면 끝이에요. 🎄

로컬 서버로 보고 싶다면:

```bash
git clone https://github.com/yunssup/2026-christmas-Landing.git
```

```bash
cd 2026-christmas-Landing
```

```bash
npx serve .
```

### 🌐 GitHub Pages로 배포하기

저장소 **Settings → Pages**에서 Source를 `Deploy from a branch`, 브랜치를 `main` / `(root)`로 고르면
`https://yunssup.github.io/2026-christmas-Landing/` 주소로 바로 공개돼요.

---

## 🎀 내용 수정하기

일정이 바뀌면 `index.html` 맨 아래 `<script>` 안의 `EVENT`만 고치면 돼요.

```js
const EVENT = {
  gameDate: "12.27 (일) 오전 10시",      // 페이지에 보이는 성탄제 일시
  festival: new Date(2026, 11, 27),     // D-day 기준 날짜 (월은 0부터: 11 = 12월)
};
```

- 밴드 미사 일정과 라인업은 `BAND MASS` 섹션의 HTML에서 바로 고칠 수 있어요.
- 색은 `<style>` 맨 위 `:root`의 변수(`--pine-*`, `--berry-*`, `--gold-*` 등)에서 한 번에 바꿀 수 있어요.

---

## 📁 폴더 구조

```
.
├── 🎄 index.html   # 랜딩페이지 (HTML · CSS · JS 한 파일)
└── 📜 README.md
```

---

<div align="center">

⭐ 🎄 ⭐

**Merry Christmas & Happy Investing!**

*올해 당신의 한 수는 어떤 감정인가요?* 🎅

❄️ ⛄ 🎁 ⛄ ❄️

</div>
