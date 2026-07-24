# Tundra's Fortune

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/tundra-s-fortune-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tundra-s-fortune-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/tundra-s-fortune-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/tundra-s-fortune-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/tundra-s-fortune-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "tundra-s-fortune-b7",
  "name": "Tundra's Fortune",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.04",
  "rtp_variants": [
    {
      "rtp": "96.04",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.06",
      "variant": "default",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2023-10-12",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "winter",
      "name": "Winter"
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
      "page_url": "https://i-gaming.tools/slot-games/tundra-s-fortune-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/tundra-s-fortune-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tundra-s-fortune-b7/demand/
```

**12-month volume (illustrative):** 670 · **trend:** flat · YoY +0.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 120 | growing |
| Greece | 110 | flat |
| Brazil | 60 | declining |
| Switzerland | 60 | declining |
| Argentina | 40 | flat |
| Sweden | 40 | declining |
| Italy | 30 | flat |
| Norway | 30 | flat |
| Australia | 20 | flat |
| Netherlands | 20 | flat |

> Full per-country breakdown (22 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/tundra-s-fortune-b7/
- **Public page:** https://i-gaming.tools/slot-games/tundra-s-fortune-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
