# 다야의 GitHub 블로그

Jekyll과 GitHub Pages로 만든 개인 블로그입니다.

## 🚀 시작하기

### 1. Repository 만들기
1. GitHub에서 새 repository 생성
2. Repository 이름: `[your-username].github.io`
3. Public으로 설정

### 2. 코드 업로드
```bash
git init
git add .
git commit -m "Initial blog setup"
git branch -M main
git remote add origin https://github.com/[your-username]/[your-username].github.io.git
git push -u origin main
```

### 3. GitHub Pages 활성화
1. Repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: main, folder: / (root)
4. Save

### 4. 블로그 접속
몇 분 후 `https://[your-username].github.io`로 접속 가능!

## 📝 포스트 작성하기

`_posts` 폴더에 다음 형식으로 파일 생성:
- 파일명: `YYYY-MM-DD-title.md`
- 예시: `2025-01-08-my-first-post.md`

```markdown
---
layout: post
title: "포스트 제목"
date: 2025-01-08
categories: [카테고리1, 카테고리2]
tags: [태그1, 태그2]
---

포스트 내용을 여기에 작성하세요.
```

## 🎨 커스터마이징

- `_config.yml`: 사이트 설정 변경
- `assets/css/style.css`: 스타일 수정
- `_layouts/`: 레이아웃 템플릿 수정

## 🛠 로컬에서 테스트하기

```bash
# Ruby와 Jekyll 설치 필요
bundle install
bundle exec jekyll serve
```

`http://localhost:4000`에서 확인 가능

## 📚 폴더 구조

```
.
├── _config.yml          # 사이트 설정
├── _layouts/           # 레이아웃 템플릿
├── _posts/            # 블로그 포스트
├── assets/            # CSS, JS, 이미지
├── about/             # 소개 페이지
├── posts/             # 포스트 목록 페이지
└── index.html         # 홈페이지
```