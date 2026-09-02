# Mirae-N-Math-Xi-Home-Page

## 현재 상태: 홈페이지 임시 폐쇄(점검 안내 페이지)

`index.html` / `404.html` 이 "임시 점검 중" 안내 페이지로 교체되어 있습니다.
원래 홈페이지 전체 내용은 삭제되지 않았고, git 기록(커밋 `b1e6985`)에 그대로 보존되어 있습니다.

### 다시 여는 방법 (원본 복구)

```bash
git checkout b1e6985 -- index.html
git rm 404.html
git commit -m "홈페이지 재오픈: 원본 index.html 복구"
git push origin main
```

원본 `index.html` blob: `92f9b06f291b60de7ac383b73cd546b8f9305793`
