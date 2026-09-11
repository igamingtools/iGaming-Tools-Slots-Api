# Raiden Shogun

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/raiden-shogun-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/raiden-shogun-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/raiden-shogun-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/raiden-shogun-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/raiden-shogun-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "raiden-shogun-b29",
  "name": "Raiden Shogun",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.62",
  "rtp_variants": [
    {
      "rtp": "96.62",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.67",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.64",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "55.96",
      "is_default": true
    }
  ],
  "release_date": "2026-04-30",
  "themes": [
    {
      "slug": "devils",
      "name": "Devils"
    },
    {
      "slug": "japanese",
      "name": "Japanese"
    },
    {
      "slug": "lions",
      "name": "Lions"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/raiden-shogun-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/raiden-shogun-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/raiden-shogun-b29/demand/
```

**12-month volume (illustrative):** 5,930 · **trend:** declining · YoY -59.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 840 | growing |
| India | 300 | flat |
| Canada | 240 | flat |
| Malaysia | 240 | flat |
| Philippines | 240 | flat |
| Indonesia | 200 | flat |
| Finland | 180 | flat |
| Belgium | 160 | declining |
| Brazil | 160 | flat |
| Poland | 140 | growing |

> Full per-country breakdown (66 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/raiden-shogun-b29/
- **Public page:** https://i-gaming.tools/slot-games/raiden-shogun-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
