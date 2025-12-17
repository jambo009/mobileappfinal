<img width="350" height="626" alt="image" src="https://github.com/user-attachments/assets/7a567ce9-585e-4921-8902-7be8461c1987" />

<img width="351" height="616" alt="image" src="https://github.com/user-attachments/assets/ce350b52-2cc8-4618-9003-e204a916777d" />

<img width="363" height="625" alt="image" src="https://github.com/user-attachments/assets/7754c64f-4b6c-4b37-901b-df671723ecd4" />


# 🧊 나의 냉장고 (My Fridge)
> **"버려지는 식재료 제로! 자취생을 위한 스마트 유통기한 관리 솔루션"**

안드로이드 **Jetpack Compose**를 활용하여 자취생들이 냉장고 속 식재료를 직관적으로 관리하고, 불필요한 식재료 낭비를 줄여 식비를 절감할 수 있도록 돕는 실무형 애플리케이션입니다.

---

## 🚀 개발 배경 및 의도 (Motivation)
많은 자취생이 냉장고 깊숙이 있는 식재료의 유통기한을 잊어버려 음식을 버리곤 합니다. 기존 메모장 앱은 매번 남은 일수를 계산해야 하는 번거로움이 있었습니다. 저는 이 **'계산의 번거로움'**을 자동화하고, **'시각적 경고'**를 통해 즉각적인 행동(소비)을 유도하는 앱을 직접 기획하고 개발했습니다.

---

## ✨ 핵심 기능 (Key Features)
1. **세션 기반 관리**: '관리 시작' 버튼을 통한 점검 세션 구축.
2. **유통기한 신호등**: 남은 기간에 따라 🔴빨강, 🟡노랑, 🟢초록으로 상태 시각화.
3. **실시간 요약**: 유통기한 임박 식품 개수를 상단에 상시 표시.

---

## 🛠 사용 기술 및 문제 해결 (Tech Stack & Problem Solving)
* **상태 관리**: `mutableStateOf`를 활용해 데이터 변경 시 UI가 즉시 재구성(Recomposition)되도록 구현.
* **로직 설계**: `FoodItem` 클래스 내에 D-Day 계산 로직을 직접 구현하여 관심사 분리.
* **에러 해결**: API 레벨 호환성 문제 해결 및 코틀린 문자열 템플릿 오류 수정.

---

## 🏗 프로젝트 구조 (Structure)
* `MainActivity.kt`: 메인 흐름 제어
* `FoodItem.kt`: 데이터 모델 및 알고리즘
* `Components.kt`: UI 컴포넌트

---
**개발자**: 성민준
**프로젝트**: mobileappfinalmyapp 2025 기말 과제
