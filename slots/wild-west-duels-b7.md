# Wild West Duels

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-west-duels-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-west-duels-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-west-duels-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-west-duels-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-west-duels-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-west-duels-b7",
  "name": "Wild West Duels",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
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
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Beer Game",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Duel",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2023-02-01",
  "themes": [
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/wild-west-duels-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-west-duels-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-west-duels-b7/demand/
```

**12-month volume (illustrative):** 18,560 · **trend:** declining · YoY -55.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 6,720 | declining |
| India | 1,320 | declining |
| Indonesia | 1,210 | growing |
| Denmark | 1,200 | declining |
| Greece | 760 | declining |
| Finland | 500 | declining |
| Malaysia | 440 | declining |
| Switzerland | 390 | declining |
| Philippines | 330 | flat |
| United Kingdom | 310 | declining |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-west-duels-b7/
- **Public page:** https://i-gaming.tools/slot-games/wild-west-duels-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
