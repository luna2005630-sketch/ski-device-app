# 설雪 SKI RENTAL 데모

Firebase Authentication과 Cloud Firestore를 사용하는 정적 스키 장비 대여·반납 데모입니다.

## GitHub Pages 배포

1. GitHub에서 새 저장소를 만듭니다.
2. `index.html`, `firestore.rules`, `.nojekyll`을 저장소에 업로드합니다.
3. 저장소의 **Settings → Pages**에서 Source를 `Deploy from a branch`로 선택합니다.
4. Branch는 `main`, 폴더는 `/ (root)`로 선택하고 저장합니다.
5. 발급된 `https://사용자명.github.io/저장소명/` 주소로 접속합니다.

## Firebase 설정

Firebase Console → Authentication → Settings → Authorized domains에 GitHub Pages 도메인을 추가해야 합니다.

예:

```text
사용자명.github.io
```

Firestore Rules는 `firestore.rules` 내용을 Firebase Console의 Firestore Database → Rules에 배포합니다.

이 프로젝트는 별도 빌드 과정이 없는 단일 `index.html` 정적 앱입니다.
