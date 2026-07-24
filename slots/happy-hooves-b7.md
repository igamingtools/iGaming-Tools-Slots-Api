# Happy Hooves

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/happy-hooves-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/happy-hooves-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/happy-hooves-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/happy-hooves-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/happy-hooves-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "happy-hooves-b7",
  "name": "Happy Hooves",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.49",
  "rtp_variants": [
    {
      "rtp": "96.49",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.29",
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
      "label": "Buy Respin Feature",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2022-09-08",
  "themes": [
    {
      "slug": "farm",
      "name": "Farm"
    },
    {
      "slug": "horses",
      "name": "Horses"
    },
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
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
      "page_url": "https://i-gaming.tools/slot-games/happy-hooves-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/happy-hooves-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/happy-hooves-b7/demand/
```

**12-month volume (illustrative):** 780 · **trend:** declining · YoY -12.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 100 | declining |
| Canada | 80 | flat |
| United Kingdom | 60 | flat |
| Bulgaria | 50 | growing |
| Finland | 40 | flat |
| Germany | 40 | declining |
| Greece | 40 | declining |
| Lithuania | 40 | flat |
| United States | 40 | growing |
| Croatia | 30 | growing |

> Full per-country breakdown (23 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/happy-hooves-b7/
- **Public page:** https://i-gaming.tools/slot-games/happy-hooves-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
