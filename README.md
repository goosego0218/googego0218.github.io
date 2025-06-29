# goosego의 블로그

이 프로젝트는 Jekyll을 사용하여 만든 GitHub Pages 블로그입니다. 파이썬과 NumPy를 배우고 나누는 기술 블로그입니다.

## 특징

- Jekyll 기반의 정적 사이트 생성
- 반응형 디자인
- 카테고리별 포스트 분류
- 검색 기능
- 소셜 미디어 링크
- 코드 하이라이팅

## 설치 및 실행

### 사전 요구사항

- Ruby 2.4.0 이상
- RubyGems
- GCC 및 Make

### 설치 방법

1. 저장소를 클론합니다:
```bash
git clone https://github.com/goosego0218/googego0218.github.io.git
cd googego0218.github.io
```

2. Jekyll과 의존성을 설치합니다:
```bash
bundle install
```

3. 로컬에서 블로그를 실행합니다:
```bash
bundle exec jekyll serve
```

4. 브라우저에서 `http://localhost:4000`으로 접속합니다.

## 포스트 작성

새로운 포스트를 작성하려면 `_posts` 폴더에 마크다운 파일을 생성하세요:

```markdown
---
layout: post
title: "포스트 제목"
date: YYYY-MM-DD
categories: [카테고리명]
tags: [태그1, 태그2]
author_profile: true
toc: true
toc_sticky: true
---

포스트 내용...
```

## 배포

GitHub Pages에 배포하려면:

1. 저장소를 GitHub에 푸시합니다
2. 저장소 설정에서 GitHub Pages를 활성화합니다
3. 소스 브랜치를 `main` 또는 `master`로 설정합니다

## 커스터마이징

### 설정 파일 수정

`_config.yml` 파일을 수정하여 블로그 설정을 변경할 수 있습니다:

- 사이트 제목 및 설명
- 작성자 정보
- 소셜 미디어 링크
- 플러그인 설정

### 스타일 수정

CSS 스타일을 수정하려면 `assets/css/main.scss` 파일을 편집하세요.

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 기여

버그 리포트나 기능 요청은 GitHub Issues를 통해 제출해 주세요.

## 연락처

- 이메일: sonks9@naver.com
- GitHub: [goosego0218](https://github.com/goosego0218)

---

**배워서 남주자 - goosego** 