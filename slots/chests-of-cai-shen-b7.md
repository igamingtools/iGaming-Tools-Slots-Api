# Chests of Cai Shen

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chests-of-cai-shen-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chests-of-cai-shen-b7",
  "name": "Chests of Cai Shen",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.47",
  "rtp_variants": [
    {
      "rtp": "96.47",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.46",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.48",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Chest Feature",
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Buy Triple Chest Feature",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2024-09-30",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "money",
      "name": "Money"
    }
  ],
  "features": [
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/chests-of-cai-shen-b7/"
    }
  },
  "series": {
    "slug": "chests-of-cai-shen",
    "name": "Chests of Cai Shen"
  }
}
```

## Search Demand

`GET /api/v1/slots/chests-of-cai-shen-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-b7/demand/
```

**12-month volume (illustrative):** 3,630 · **trend:** flat · YoY -4.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 330 | flat |
| Greece | 250 | flat |
| Philippines | 240 | flat |
| Malaysia | 220 | declining |
| Australia | 180 | flat |
| Canada | 160 | flat |
| Portugal | 120 | growing |
| Peru | 110 | flat |
| Argentina | 100 | flat |
| Lithuania | 100 | flat |

> Full per-country breakdown (53 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-b7/
- **Public page:** https://i-gaming.tools/slot-games/chests-of-cai-shen-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
