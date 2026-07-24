# Queen of Atlantis

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/queen-of-atlantis-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/queen-of-atlantis-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/queen-of-atlantis-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/queen-of-atlantis-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/queen-of-atlantis-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "queen-of-atlantis-b7",
  "name": "Queen of Atlantis",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.42",
  "rtp_variants": [
    {
      "rtp": "96.42",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2017-03-01",
  "themes": [
    {
      "slug": "ocean",
      "name": "Ocean"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "pick_bonus",
      "name": "Pick Bonus"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/queen-of-atlantis-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/queen-of-atlantis-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/queen-of-atlantis-b7/demand/
```

**12-month volume (illustrative):** 340 · **trend:** declining · YoY -24.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 60 | flat |
| Argentina | 30 | flat |
| Indonesia | 30 | declining |
| United Kingdom | 30 | flat |
| Australia | 20 | declining |
| Belarus | 20 | flat |
| Brazil | 20 | flat |
| Finland | 20 | flat |
| Ukraine | 20 | flat |
| Czech Republic | 10 | flat |

> Full per-country breakdown (18 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/queen-of-atlantis-b7/
- **Public page:** https://i-gaming.tools/slot-games/queen-of-atlantis-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
