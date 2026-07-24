# Trees of Treasure

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/trees-of-treasure-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/trees-of-treasure-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/trees-of-treasure-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/trees-of-treasure-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/trees-of-treasure-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "trees-of-treasure-b7",
  "name": "Trees of Treasure",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.10",
  "rtp_variants": [
    {
      "rtp": "96.10",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-02-05",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/trees-of-treasure-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/trees-of-treasure-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/trees-of-treasure-b7/demand/
```

**12-month volume (illustrative):** 880 · **trend:** declining · YoY -34.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 80 | flat |
| Canada | 80 | flat |
| Greece | 80 | flat |
| Malaysia | 80 | growing |
| Argentina | 70 | flat |
| Indonesia | 70 | flat |
| United States | 60 | declining |
| Italy | 50 | flat |
| Philippines | 50 | growing |
| India | 40 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/trees-of-treasure-b7/
- **Public page:** https://i-gaming.tools/slot-games/trees-of-treasure-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
