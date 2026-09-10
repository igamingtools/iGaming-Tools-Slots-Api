# Disco Beats

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/disco-beats-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/disco-beats-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/disco-beats-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/disco-beats-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/disco-beats-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "disco-beats-b29",
  "name": "Disco Beats",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.62",
  "rtp_variants": [
    {
      "rtp": "96.62",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "ways",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-03-29",
  "themes": [
    {
      "slug": "music",
      "name": "Music"
    },
    {
      "slug": "party",
      "name": "Party"
    }
  ],
  "features": [
    {
      "slug": "retrigger",
      "name": "Retrigger"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    },
    {
      "slug": "wheel_bonus",
      "name": "Wheel Bonus"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/disco-beats-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/disco-beats-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/disco-beats-b29/demand/
```

**12-month volume (illustrative):** 22,070 · **trend:** declining · YoY -38.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 19,500 | declining |
| United States | 620 | flat |
| Canada | 260 | flat |
| United Kingdom | 150 | flat |
| India | 140 | flat |
| Malaysia | 80 | flat |
| New Zealand | 80 | flat |
| Ukraine | 80 | flat |
| Germany | 60 | declining |
| Pakistan | 60 | flat |

> Full per-country breakdown (56 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/disco-beats-b29/
- **Public page:** https://i-gaming.tools/slot-games/disco-beats-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
