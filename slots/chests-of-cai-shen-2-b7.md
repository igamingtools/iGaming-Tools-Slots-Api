# Chests of Cai Shen 2

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chests-of-cai-shen-2-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-2-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-2-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-2-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-2-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chests-of-cai-shen-2-b7",
  "name": "Chests of Cai Shen 2",
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
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Fulfillment",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy X100 Fulfillment",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2025-10-09",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
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
      "slug": "multihold",
      "name": "Multihold"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/chests-of-cai-shen-2-b7/"
    }
  },
  "series": {
    "slug": "chests-of-cai-shen",
    "name": "Chests of Cai Shen"
  }
}
```

## Search Demand

`GET /api/v1/slots/chests-of-cai-shen-2-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-2-b7/demand/
```

**12-month volume (illustrative):** 3,810 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 600 | flat |
| South Africa | 460 | flat |
| Canada | 140 | flat |
| Malaysia | 140 | declining |
| Switzerland | 120 | flat |
| United States | 120 | declining |
| Germany | 110 | flat |
| Greece | 110 | growing |
| Australia | 100 | declining |
| France | 100 | flat |

> Full per-country breakdown (59 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chests-of-cai-shen-2-b7/
- **Public page:** https://i-gaming.tools/slot-games/chests-of-cai-shen-2-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
