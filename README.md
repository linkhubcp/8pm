# 저녁여덟시 — 링크 페이지

유튜브·인스타·X 프로필에 거는 링크 허브입니다.

- 페이지 본체는 `index.html` 한 장이고, **손으로 고치지 마세요.**
- 원본은 `vibe-money-project/.claude/skills/shortform/assets/link_hub/` 이고,
  `pipeline/update_link_hub.py`가 상품 목록(`today_cart_products.json`)으로 생성합니다.

## 상품 추가

```
python .claude/skills/shortform/pipeline/update_link_hub.py add "상품명" "https://link.coupang.com/a/XXXXX"
python .claude/skills/shortform/pipeline/deploy_link_hub.py
```

## 고지

이 페이지의 링크에는 쿠팡파트너스 링크가 포함될 수 있으며, 이를 통해 일정액의 수수료를 제공받습니다.
