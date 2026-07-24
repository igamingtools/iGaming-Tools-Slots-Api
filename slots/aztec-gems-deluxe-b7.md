# Aztec Gems Deluxe

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/aztec-gems-deluxe-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/aztec-gems-deluxe-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/aztec-gems-deluxe-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/aztec-gems-deluxe-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/aztec-gems-deluxe-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "aztec-gems-deluxe-b7",
  "name": "Aztec Gems Deluxe",
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
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-08-05",
  "themes": [
    {
      "slug": "aztec",
      "name": "Aztec"
    },
    {
      "slug": "gems",
      "name": "Gems"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
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
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/aztec-gems-deluxe-b7/"
    }
  },
  "series": {
    "slug": "aztec-gems",
    "name": "Aztec Gems"
  }
}
```

## Search Demand

`GET /api/v1/slots/aztec-gems-deluxe-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/aztec-gems-deluxe-b7/demand/
```

**12-month volume (illustrative):** 5,040 · **trend:** growing · YoY +15.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 1,590 | flat |
| Finland | 1,020 | growing |
| Indonesia | 510 | growing |
| India | 180 | flat |
| Mexico | 130 | flat |
| Philippines | 130 | flat |
| Argentina | 120 | flat |
| Malaysia | 120 | flat |
| Thailand | 100 | flat |
| Switzerland | 90 | declining |

> Full per-country breakdown (40 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/aztec-gems-deluxe-b7/
- **Public page:** https://i-gaming.tools/slot-games/aztec-gems-deluxe-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
