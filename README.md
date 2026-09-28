# nonsenseofrhythm.com

Nonsense of Rhythm 사이트. 걸어 다니는 공간 하나에 film · app · record 세 곳이 있다.
브랜드가 무엇인지는 `docs/NoR_소개.md`, 사이트 방향은 `docs/NoR_사이트_감도.md`, 서체는 `docs/서체_규정.md`.

## 구조

```
index.html        사이트 전부 (HTML 하나)
fonts/            Inter v3.019 Bold(로고) · Pretendard Regular/Bold(한글)
assets/           이미지·영상 — 넣을 파일 이름은 assets/README.md
privacy/          개인정보 처리방침 (앱 심사에 등록된 주소, 지우지 않는다)
docs/             브랜드 문서
```

## 고치는 법

1. `main` 에 바로 올리지 않는다. 새 브랜치를 만들어 고친다.
2. 고친 뒤 Pull Request 를 연다. 무엇을 왜 바꿨는지 한두 줄.
3. 대표가 보고 합친다. **합쳐지면 1~2분 뒤 사이트에 자동으로 반영된다.**

GitHub 웹에서도 된다: 파일 열기 → 연필 아이콘 → 고치기 → "Create a new branch" → Propose changes.

내 컴퓨터에서 확인할 때는 폴더에서 `python3 -m http.server` 를 켜고 `http://localhost:8000` 을 연다.
(index.html 을 더블클릭으로 열면 폰트와 영상이 안 뜰 수 있다.)

## 지키는 것 (이것만)

- **서체** — 로고는 Inter(`'NoR Inter'`, 700, 자간 −0.11667em). 영문은 Helvetica Neue LT Pro 400·700만 (600 없음). 한글은 Pretendard(`'NoR P'`).
- **Helvetica 파일을 저장소에 올리지 않는다.** Adobe 킷 링크(`use.typekit.net/rez7jaf.css`)로만 쓴다. `.gitignore` 가 막아 두었다.
- **비밀값(키, 비밀번호, .env)을 올리지 않는다.** 저장소가 공개일 수 있다.
- **`/privacy` 는 계속 열려 있어야 한다.**

그 밖의 것은 취향이다. 더 재밌는 쪽이 보이면 그쪽으로 간다. 결정은 대표가 한다.
