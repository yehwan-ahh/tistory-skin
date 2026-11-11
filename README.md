# 3dramstory 티스토리 스킨

| 파일 | 내용 |
|---|---|
| `custom.css` | 직접 추가한 테마 부분만 (★ 사용자 설정 변수 포함) |

## 수정 흐름
1. `custom.css` 또는 `skin.html` 수정
2. `git commit` 으로 변경 기록
3. `git push` 하면 jsDelivr CDN으로 블로그에 자동 반영 (캐시 최대 12시간)
   - 바로 반영: 브라우저에서 https://purge.jsdelivr.net/gh/yehwan-ahh/tistory-skin@main/custom.css 열기

티스토리 스킨 HTML에 연결된 주소:
`https://cdn.jsdelivr.net/gh/yehwan-ahh/tistory-skin@main/custom.css`

## 되돌리기
`git log` 로 이전 버전을 찾고 `git checkout <커밋> -- custom.css` 후 다시 반영.
