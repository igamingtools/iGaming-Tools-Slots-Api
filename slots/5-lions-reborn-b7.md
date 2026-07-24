# 5 Lions Reborn

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/5-lions-reborn-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/5-lions-reborn-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/5-lions-reborn-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/5-lions-reborn-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/5-lions-reborn-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "5-lions-reborn-b7",
  "name": "5 Lions Reborn",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "80.00",
      "is_default": true
    },
    {
      "label": "Buy Super Free Spins",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2025-04-17",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "lions",
      "name": "Lions"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/5-lions-reborn-b7/"
    }
  },
  "series": {
    "slug": "5-lions",
    "name": "5 Lions"
  }
}
```

## Search Demand

`GET /api/v1/slots/5-lions-reborn-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/5-lions-reborn-b7/demand/
```

**12-month volume (illustrative):** 4,980 · **trend:** growing · YoY +73.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 660 | flat |
| Argentina | 340 | flat |
| Switzerland | 300 | flat |
| Malaysia | 220 | flat |
| Greece | 210 | growing |
| Finland | 200 | flat |
| Brazil | 190 | flat |
| Germany | 160 | growing |
| Peru | 160 | flat |
| Indonesia | 150 | declining |

> Full per-country breakdown (55 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/5-lions-reborn-b7/
- **Public page:** https://i-gaming.tools/slot-games/5-lions-reborn-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
