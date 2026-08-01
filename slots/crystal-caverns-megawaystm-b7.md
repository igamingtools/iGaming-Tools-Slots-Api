# Crystal Caverns Megaways™

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/crystal-caverns-megawaystm-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/crystal-caverns-megawaystm-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/crystal-caverns-megawaystm-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/crystal-caverns-megawaystm-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/crystal-caverns-megawaystm-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "crystal-caverns-megawaystm-b7",
  "name": "Crystal Caverns Megaways™",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.46",
  "rtp_variants": [
    {
      "rtp": "96.46",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.47",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "80.00",
      "is_default": true
    }
  ],
  "release_date": "2021-12-14",
  "themes": [
    {
      "slug": "gems",
      "name": "Gems"
    },
    {
      "slug": "winter",
      "name": "Winter"
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
      "slug": "megaways",
      "name": "Megaways"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/crystal-caverns-megawaystm-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/crystal-caverns-megawaystm-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/crystal-caverns-megawaystm-b7/demand/
```

**12-month volume (illustrative):** 1,710 · **trend:** flat · YoY +4.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 220 | growing |
| Indonesia | 160 | flat |
| Brazil | 150 | flat |
| Tunisia | 100 | flat |
| United Kingdom | 70 | declining |
| Canada | 60 | flat |
| Finland | 60 | flat |
| Greece | 60 | growing |
| Netherlands | 60 | growing |
| Peru | 60 | declining |

> Full per-country breakdown (41 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/crystal-caverns-megawaystm-b7/
- **Public page:** https://i-gaming.tools/slot-games/crystal-caverns-megawaystm-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
