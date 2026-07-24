# Sleeping Dragon

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sleeping-dragon-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sleeping-dragon-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sleeping-dragon-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sleeping-dragon-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sleeping-dragon-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sleeping-dragon-b7",
  "name": "Sleeping Dragon",
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
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Respin Bonus",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2025-05-08",
  "themes": [
    {
      "slug": "dragons",
      "name": "Dragons"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "medieval",
      "name": "Medieval"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/sleeping-dragon-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/sleeping-dragon-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sleeping-dragon-b7/demand/
```

**12-month volume (illustrative):** 5,500 · **trend:** growing · YoY +165.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Australia | 990 | declining |
| Brazil | 620 | growing |
| Romania | 570 | declining |
| Greece | 560 | flat |
| Indonesia | 200 | flat |
| Canada | 180 | flat |
| Malaysia | 180 | flat |
| Finland | 140 | declining |
| New Zealand | 140 | flat |
| Belgium | 120 | flat |

> Full per-country breakdown (55 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sleeping-dragon-b7/
- **Public page:** https://i-gaming.tools/slot-games/sleeping-dragon-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
