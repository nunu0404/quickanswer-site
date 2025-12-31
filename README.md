# 검색형 Q&A 정적 사이트

이 폴더는 **배포용 정적 파일**만 들어있습니다. Cloudflare Pages에 바로 올릴 수 있어요.

## Cloudflare Pages 설정

- Framework preset: None
- Build command: 비움
- Output directory: `/`

## 꼭 수정할 것

- `sitemap.xml`, `robots.txt`의 도메인
- 필요하면 `index.html`, 각 Q&A 페이지의 canonical
- 애드센스 사용 시 `ads.txt`를 본인 값으로 교체

**추천 방법:** `qna-site-tools`에서 설정을 바꾸고 다시 빌드하세요.

```
python3 qna-site-tools/build.py
```

## 필수 페이지

- `index.html`
- `privacy.html`
- `contact.html`

AdSense 승인을 위해 최소 30~50개 Q&A 페이지를 유지하는 것을 권장합니다.
