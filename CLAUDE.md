# 이 저장소에서 지킬 것

## 웹툰 「스틸가챠s」 작업
- 웹툰 일(이야기 후보, 콘티, 그림 프롬프트, 받은 컷 검수, 앱에 올리기)을 할 때는 **매번 `steel-gacha-webtoon` 스킬을 먼저 불러와서** 그 규칙대로 한다.
  - 정본: `savvygonsama/my-web-apps` 저장소의 `skills/steel-gacha-webtoon/` (스킬 목록에 없으면 이 폴더의 `SKILL.md`와 `references/`를 직접 읽는다)
  - 작업 중 사용자가 준 새 규칙·정정은 그 스킬 파일에 바로 반영해 커밋한다.
- 앱에 올릴 때는 스킬의 `scripts/add_episode.py`를 쓴다. 웹툰 데이터는 `src/app_tpl.html`의 `TOON` 목록, 그림은 `webtoon/`.
- PR은 만들되 **머지는 사용자가 한다.**
