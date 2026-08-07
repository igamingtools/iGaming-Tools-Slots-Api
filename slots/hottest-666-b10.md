# Hottest 666

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/hottest-666-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hottest-666-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/hottest-666-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/hottest-666-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/hottest-666-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "hottest-666-b10",
  "name": "Hottest 666",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.00",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus Game",
      "cost": "80.00",
      "is_default": true
    }
  ],
  "release_date": "2023-12-20",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "random-wilds",
      "name": "Random Wilds"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/hottest-666-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/hottest-666-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hottest-666-b10/demand/
```

**12-month volume (illustrative):** 230 · **trend:** declining · YoY -37.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 60 | declining |
| Greece | 60 | flat |
| Germany | 30 | flat |
| Switzerland | 30 | flat |
| Poland | 20 | declining |
| United Kingdom | 20 | growing |
| Italy | 10 | declining |

> Full per-country breakdown (7 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/hottest-666-b10/
- **Public page:** https://i-gaming.tools/slot-games/hottest-666-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
