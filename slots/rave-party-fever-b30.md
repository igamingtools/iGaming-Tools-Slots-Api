# Rave Party Fever

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rave-party-fever-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rave-party-fever-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rave-party-fever-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rave-party-fever-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rave-party-fever-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rave-party-fever-b30",
  "name": "Rave Party Fever",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.73",
  "rtp_variants": [
    {
      "rtp": "96.73",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "cluster",
  "reels": 7,
  "rows": 7,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2023-02-01",
  "themes": [
    {
      "slug": "music",
      "name": "Music"
    },
    {
      "slug": "neon",
      "name": "Neon"
    },
    {
      "slug": "party",
      "name": "Party"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rave-party-fever-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rave-party-fever-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rave-party-fever-b30/demand/
```

**12-month volume (illustrative):** 2,640 · **trend:** declining · YoY -29.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 740 | declining |
| Brazil | 620 | growing |
| Indonesia | 300 | declining |
| Philippines | 140 | flat |
| Pakistan | 120 | flat |
| Thailand | 110 | growing |
| Mexico | 60 | growing |
| Estonia | 50 | flat |
| Chile | 40 | flat |
| Japan | 40 | flat |

> Full per-country breakdown (35 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rave-party-fever-b30/
- **Public page:** https://i-gaming.tools/slot-games/rave-party-fever-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
