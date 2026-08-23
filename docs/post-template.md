---
title: '글 제목'
description: '글을 한 줄로 설명합니다.'
pubDate: '2026-08-10'
heroImage: '../../assets/default-image.png'
# updatedDate: '2026-08-30'
---

여기부터 본문을 씁니다.

##### 소제목

본문에서 소제목은 `#####` 를 씁니다.

```bash
echo "코드는 언어를 붙인 코드블록으로 감쌉니다"
```

<!--
새 글 쓰는 법

1. 이 파일을 `src/content/blog/<슬러그>.md` 로 복사합니다.
   파일 이름이 곧 주소가 됩니다. (예: nvm-command.md -> /blog/nvm-command)
2. 위 frontmatter 를 채우고, 이 주석과 예시 본문은 지웁니다.

frontmatter 항목
  title        (필수) 글 제목
  description  (필수) 목록과 검색 결과에 쓰이는 한 줄 설명
  pubDate      (필수) 발행일. 'Aug 21 2026' 형식
  updatedDate  (선택) 수정일. 같은 형식
  heroImage    (선택) 썸네일 이미지 경로

썸네일을 따로 넣으려면
  `src/assets/blog/<슬러그>/` 폴더를 만들어 이미지를 넣고,
  heroImage 를 '../../assets/blog/<슬러그>/thumbnail.png' 로 바꿉니다.
  경로에 실제 파일이 없으면 빌드가 실패하니 파일을 먼저 넣어주세요.

본문에서 이미지를 쓸 때도 같은 폴더를 씁니다.
  ![설명](../../assets/blog/<슬러그>/example.png)
-->
