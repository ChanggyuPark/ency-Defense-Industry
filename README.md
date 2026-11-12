# ENCY Defense Industry — Sixshop landing

식스샵 경로: `/Defense-Industry`  
식스샵 Page ID: `page2767283`  
원본의 사이트 내부 헤더·푸터를 제외하고, 식스샵 기본 헤더·푸터를 유지하도록 구성했습니다.

## Sixshop HEAD

```html
<!-- ENCY Defense Industry -->
<link rel="stylesheet" href="https://changgyupark.github.io/ency-Defense-Industry/ency-defense.css?v=20261112-02">
<script defer src="https://changgyupark.github.io/ency-Defense-Industry/ency-defense.js?v=20261112-02"></script>
```

## 파일

- `ency-defense.css`: scoped styles
- `ency-defense.js`: route/page ID lock, mount/unmount, 원본 인터랙션
- `assets/defense-part-00.txt` ~ `defense-part-12.txt`: 원본 내장 이미지 및 랜딩 HTML. **13개 파일 모두 필수입니다.**

## 배포

1. 저장소 Settings → Pages → Build and deployment 에서 `Deploy from a branch`, `main`, `/(root)`를 선택해 활성화합니다.
2. 위 HEAD 코드를 식스샵에 추가합니다.
3. `https://www.encycadcam.co.kr/Defense-Industry`에서 랜딩/헤더/푸터/모바일/이미지 확대를 확인합니다.

상담 CTA는 첨부 원본의 링크를 유지했습니다. 별도 Monday 폼 또는 UTM 처리를 추가하지 않았습니다.

주의: GitHub Pages가 아직 활성화되지 않았다면 스크립트/이미지는 표시되지 않습니다.
