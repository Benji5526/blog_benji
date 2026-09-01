# blog_benji

Benji의 개인 블로그입니다. Jekyll로 만들었고 GitHub Actions를 통해 GitHub Pages에 자동 배포됩니다.

**사이트:** https://benji5526.github.io/blog_benji/

## 내용

AI 에이전시(AI Agent) 수업을 공부하며 배운 내용과 진행 상황을 날짜별로 기록합니다. 글은 `_posts/` 폴더에 `YYYY-MM-DD-제목.md` 형식으로 저장되며, `ai-agent-study` 카테고리로 관리합니다.

## 로컬에서 실행하기

```bash
bundle install
bundle exec jekyll serve
```

`http://localhost:4000/blog_benji/` 에서 미리보기를 확인할 수 있습니다.

## 배포

`main` 브랜치에 push하면 `.github/workflows/jekyll.yml` 워크플로우가 자동으로 빌드하고 GitHub Pages에 배포합니다.
