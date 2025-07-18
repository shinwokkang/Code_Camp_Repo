# 📘 공부 내용 PR 템플릿

## 📅 날짜

- YYYY-MM-DD (예: 2025-07-18)

---

## 🧠 공부한 주제

- [ ] useEffect 의존성 배열 개념
- [ ] Git stash 사용법
- [ ] JSX 조건부 렌더링

---

## 💻 실습 코드 요약

> 핵심 코드 블록 또는 커밋 링크를 정리해주세요.

<details>
<summary>예시 코드 보기</summary>

```tsx
useEffect(() => {
  console.log("컴포넌트 마운트 시 실행됨");

  return () => {
    console.log("언마운트 시 실행됨");
  };
}, []);
