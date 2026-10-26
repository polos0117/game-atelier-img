# game-atelier-img

[game-atelier](https://github.com/polos0117/game-atelier) 의 그림 저장소. 코드 저장소가 무거워지지 않게 그림은 여기 둔다 — Pages 로 `https://polos0117.github.io/game-atelier-img/img/<파일>` 에서 읽는다.

- `img/` — 그림(webp, 1024×1536). 이름 꼴은 코드 저장소 `IMAGE_RULES.md` 3절: `<게임>_<폼>_<화풍>_f.webp` · `<게임>_<폼>_open_<화풍>_f.webp` · `<게임>_<화풍>_f_casual<n>.webp`
- `img/thumb/` — 썸네일(긴 변 512, webp 72). 같은 이름
- `records/<게임>/<자리>-import.json` · `<자리>-ui.json` — 어떻게 만들었나. 원본 PNG 는 올리지 않고 sha256 만 적는다

등록(코드 저장소 `data/img.json`)은 서가와 등록 워크플로가 오기 전까지 손으로 적는다. 그림을 덮어쓰지 않는다 — 바꿔 달라고 한 그림만 바꾸고 앞 그림의 sha256 을 `replacement.json` 에 남긴다.
