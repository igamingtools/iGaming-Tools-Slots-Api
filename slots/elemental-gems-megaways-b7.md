# Elemental Gems Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/elemental-gems-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/elemental-gems-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/elemental-gems-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/elemental-gems-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/elemental-gems-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "elemental-gems-megaways-b7",
  "name": "Elemental Gems Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 3,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-02-10",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
    },
    {
      "slug": "gems",
      "name": "Gems"
    }
  ],
  "features": [
    {
      "slug": "megaways",
      "name": "Megaways"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/elemental-gems-megaways-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/elemental-gems-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/elemental-gems-megaways-b7/demand/
```

**12-month volume (illustrative):** 1,260 · **trend:** declining · YoY -6.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 300 | declining |
| Brazil | 170 | growing |
| Mexico | 70 | flat |
| Philippines | 70 | flat |
| Germany | 60 | flat |
| Malaysia | 60 | flat |
| United States | 60 | declining |
| Argentina | 50 | declining |
| United Kingdom | 40 | flat |
| Greece | 30 | flat |

> Full per-country breakdown (32 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/elemental-gems-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/elemental-gems-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
