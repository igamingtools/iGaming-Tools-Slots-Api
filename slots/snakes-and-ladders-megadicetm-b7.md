# Snakes and Ladders Megadice™

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/snakes-and-ladders-megadicetm-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/snakes-and-ladders-megadicetm-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/snakes-and-ladders-megadicetm-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/snakes-and-ladders-megadicetm-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/snakes-and-ladders-megadicetm-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "snakes-and-ladders-megadicetm-b7",
  "name": "Snakes and Ladders Megadice™",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.68",
  "rtp_variants": [
    {
      "rtp": "96.68",
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
  "release_date": "2022-02-21",
  "themes": [
    {
      "slug": "board-game",
      "name": "Board Game"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
    },
    {
      "slug": "monkeys",
      "name": "Monkeys"
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
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/snakes-and-ladders-megadicetm-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/snakes-and-ladders-megadicetm-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/snakes-and-ladders-megadicetm-b7/demand/
```

**12-month volume (illustrative):** 920 · **trend:** declining · YoY -8.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 110 | flat |
| United Kingdom | 90 | growing |
| Germany | 80 | declining |
| Finland | 60 | flat |
| Peru | 60 | growing |
| Spain | 60 | declining |
| Greece | 40 | flat |
| India | 40 | flat |
| Malaysia | 40 | flat |
| Netherlands | 40 | declining |

> Full per-country breakdown (30 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/snakes-and-ladders-megadicetm-b7/
- **Public page:** https://i-gaming.tools/slot-games/snakes-and-ladders-megadicetm-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
