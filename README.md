# 우리 팀 취미 모음

팀원들이 각자 좋아하는 취미를 소개하는 정적 웹사이트입니다. (HTML/CSS만 사용, 빌드 필요 없음)

## 구조

```
index.html, style.css      ← 홈 (팀원 카드 목록)
members/
  member1/index.html, style.css   ← 팀원 1 페이지
  member2/...                     ← 팀원 2 페이지
  member3/...                     ← 팀원 3 페이지
  member4/...                     ← 팀원 4 페이지
```

## 내 페이지 꾸미는 법

1. 저장소를 받습니다: `git clone <저장소 주소>`
2. **자기 폴더(`members/memberN/`)만** 수정합니다. 사진도 이 폴더에 넣으세요.
   - `index.html`: 내용 (이름, 취미, 이유, 사진 등)
   - `style.css`: 디자인 (`--main` 색상만 바꿔도 분위기가 달라집니다)
3. 홈 `index.html`에서 내 카드의 이름/취미/이모지도 바꿔주세요.
4. 확인: `index.html`을 브라우저로 열면 됩니다.
5. 올리기:
   ```bash
   git pull
   git add .
   git commit -m "member1: 내 취미 페이지 꾸미기"
   git push
   ```

각자 폴더가 분리되어 있어서 동시에 작업해도 충돌이 거의 없습니다.
