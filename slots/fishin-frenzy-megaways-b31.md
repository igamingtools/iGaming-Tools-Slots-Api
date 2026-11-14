# Fishin' Frenzy Megaways

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fishin-frenzy-megaways-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fishin-frenzy-megaways-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fishin-frenzy-megaways-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fishin-frenzy-megaways-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fishin-frenzy-megaways-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fishin-frenzy-megaways-b31",
  "name": "Fishin' Frenzy Megaways",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.10",
  "rtp_variants": [
    {
      "rtp": "96.10",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.60",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "95.02",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Fishin' Frenzy Bonus Megaways Guaranteed",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2019-04-01",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    },
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
      "slug": "megaways",
      "name": "Megaways"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fishin-frenzy-megaways-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fishin-frenzy-megaways-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fishin-frenzy-megaways-b31/demand/
```

**12-month volume (illustrative):** 7,150 · **trend:** growing · YoY +5.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 4,400 | growing |
| United States | 460 | growing |
| Ireland | 360 | flat |
| Canada | 140 | flat |
| Germany | 110 | growing |
| Finland | 100 | flat |
| Greece | 100 | declining |
| India | 100 | flat |
| Italy | 80 | flat |
| Netherlands | 80 | growing |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fishin-frenzy-megaways-b31/
- **Public page:** https://i-gaming.tools/slot-games/fishin-frenzy-megaways-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
