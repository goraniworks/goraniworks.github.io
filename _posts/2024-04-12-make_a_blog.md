---
layout: post
title: "휴대폰만으로 GitHub Pages와 Jekyll로 웹사이트 만들기"
date: 2024-04-12
categories: tutorial
---

## GitHub 계정 생성 및 로그인

첫 번째 단계는 GitHub 웹사이트([GitHub.com](https://github.com/))을 방문하여 계정을 생성하거나 로그인하는 것입니다. 모바일 브라우저에서도 쉽게 할 수 있습니다.

## 새 저장소 만들기

저장소 이름은 `{yourusername}.github.io`로 설정해야 하며, 이때 `{yourusername}`은 실제 사용자 이름으로 대체합니다. 저장소는 공개 설정으로 만듭니다.

## Jekyll 테마 선택

저장소 설정으로 이동하여 "Settings" 탭을 클릭하고, "Pages" 섹션에서 "Source"를 설정한 후 "Theme Chooser"에서 원하는 Jekyll 테마를 선택합니다.

## 파일 추가 및 편집

저장소 메인 페이지로 돌아와 "Add file" -> "Create new file"을 클릭하고, 파일 이름을 `index.md`로 설정합니다. 다음과 같이 마크다운 형식으로 내용을 작성할 수 있습니다:

```markdown
---
layout: default
title: My Blog
---

# Welcome to my blog!

Hello, this is my first post. I'm using GitHub Pages and Jekyll!
