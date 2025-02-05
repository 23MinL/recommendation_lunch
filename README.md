# 점심 메뉴 추천 🍽️✨

이 프로젝트는 여러분에게 점심 메뉴를 추천하는 웹 애플리케이션입니다. 🤖💬 두 가지 AI 모델을 통해, 사용자가 입력한 내용을 바탕으로 점심 메뉴를 추천해줍니다!

---

## 🧑‍💻 기술 스택

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Jekyll](https://img.shields.io/badge/Jekyll-%23D8B200.svg?style=for-the-badge&logo=jekyll&logoColor=white)](https://jekyllrb.com/)

---

## 📦 기능

- **AI 기반 점심 메뉴 추천** 🍴  
  두 가지 모델(gemini-1.5-flash, deepseek-r1)을 사용하여 점심 메뉴를 추천합니다. 🤖  
  - `gemini-1.5-flash` 모델은 간단하고 빠른 응답을 제공합니다.
  - `deepseek-r1` 모델은 더 상세한 추천을 제공합니다.

- **저장 및 삭제 기능** 🗑️  
  사용자가 입력한 점심 메뉴 추천을 저장하고, 필요 시 삭제할 수 있습니다.

- **로컬 스토리지 지원** 💾  
  데이터는 브라우저의 로컬 스토리지에 저장되어, 페이지 새로 고침 후에도 정보를 유지합니다.

---

## 🚀 사용 방법

1. 페이지가 로드되면, 원하는 모델을 선택하고 텍스트 데이터를 입력합니다.
2. **등록** 버튼을 클릭하면 AI 모델이 추천한 점심 메뉴가 출력됩니다. 🤩
3. 저장된 데이터는 화면에서 **삭제** 버튼을 클릭하여 삭제할 수 있습니다.
4. **저장된 데이터 리셋** 버튼을 클릭하면 로컬 스토리지에 저장된 모든 데이터를 삭제합니다.

---

## 🧑‍🔧 개발 환경

1. **HTML**, **CSS**, **JavaScript**로 작성된 기본 웹 애플리케이션입니다.
2. 로컬 스토리지를 사용하여 데이터 지속성 유지 💾.
3. **API 요청**을 통해 두 개의 AI 모델을 활용합니다.

---

## 🛠️ 설치 및 실행

1. 이 프로젝트를 클론하거나 압축을 풀어 로컬 환경에서 사용 가능합니다.
2. HTML 파일을 브라우저에서 열면 즉시 실행됩니다.

```bash
git clone https://github.com/yourusername/lunch-menu-recommendation.git
cd lunch-menu-recommendation
open index.html
