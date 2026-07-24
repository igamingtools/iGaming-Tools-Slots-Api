# Mahjong Wins Triple Pot

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mahjong-wins-triple-pot-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mahjong-wins-triple-pot-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mahjong-wins-triple-pot-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mahjong-wins-triple-pot-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mahjong-wins-triple-pot-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mahjong-wins-triple-pot-b7",
  "name": "Mahjong Wins Triple Pot",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-06-18",
  "themes": [
    {
      "slug": "asian",
      "name": "Asian"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "mahjong",
      "name": "Mahjong"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
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
      "page_url": "https://i-gaming.tools/slot-games/mahjong-wins-triple-pot-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mahjong-wins-triple-pot-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mahjong-wins-triple-pot-b7/demand/
```

**12-month volume (illustrative):** 430 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 280 | growing |
| Malaysia | 60 | growing |
| Belgium | 20 | growing |
| Philippines | 20 | flat |
| Thailand | 20 | flat |
| Japan | 10 | growing |
| Singapore | 10 | growing |
| Vietnam | 10 | growing |

> Full per-country breakdown (8 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mahjong-wins-triple-pot-b7/
- **Public page:** https://i-gaming.tools/slot-games/mahjong-wins-triple-pot-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
