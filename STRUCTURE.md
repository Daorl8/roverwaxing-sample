# STRUCTURE · roverwaxing-sample

```
roverwaxing-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = roverwaxing-sample → roverwaxing-sample.lgt3232.workers.dev
├─ .assetsignore           img/·문서·index_*.html 배포 제외
├─ rv-bodoni.woff2         영문 제목 (Bodoni Moda 정체, 가변)
├─ rv-bodoni-italic.woff2  영문 제목 이탤릭
├─ rv-pretendard.woff2     한글·본문 (Pretendard 가변 서브셋)
├─ rv-hero.webp            히어로 (왁싱 후 팔)
├─ rv-ba-*.webp            전후 비교 8컷 (헤어라인·눈썹·구레나룻·뒷목·수염·겨드랑이·다리·팔)
├─ og-rover.jpg            공유 썸네일 1200×630
├─ img/                    다올 제공 원본 (배포 제외)
├─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(마스트헤드) → `#top` 히어로 → `#care` 01 약속 → `#first` 02 첫 방문 → `#result` 03 전후 → `#price` 04 가격표 → 인용(먹 바탕) → `#visit` 05 오시는 길 → 푸터 · 모바일 하단 예약바.

## 반응형
모바일 1열(전후 2열) / ≥720 약속 2열·전후 4열·가격표 2열 / ≥980 히어로 2단·약속 3열·첫방문 2단·오시는길 2단. 내비 링크 ≤860 숨김, 하단 예약바 <860 표시.
