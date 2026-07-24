# Greedy Wolf

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/greedy-wolf-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/greedy-wolf-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/greedy-wolf-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/greedy-wolf-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/greedy-wolf-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "greedy-wolf-b7",
  "name": "Greedy Wolf",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.48",
  "rtp_variants": [
    {
      "rtp": "96.48",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.51",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-08-04",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "fairy-tale",
      "name": "Fairy Tale"
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
      "slug": "guaranteed-win",
      "name": "Guaranteed Win"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/greedy-wolf-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/greedy-wolf-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/greedy-wolf-b7/demand/
```

**12-month volume (illustrative):** 5,780 · **trend:** declining · YoY -16.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 510 | flat |
| Denmark | 370 | declining |
| Netherlands | 340 | declining |
| Greece | 300 | flat |
| Canada | 240 | flat |
| Finland | 220 | flat |
| Switzerland | 210 | declining |
| United States | 200 | declining |
| India | 160 | flat |
| Malaysia | 160 | declining |

> Full per-country breakdown (56 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/greedy-wolf-b7/
- **Public page:** https://i-gaming.tools/slot-games/greedy-wolf-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
