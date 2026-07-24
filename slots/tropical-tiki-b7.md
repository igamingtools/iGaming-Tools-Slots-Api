# Tropical Tiki

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/tropical-tiki-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tropical-tiki-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/tropical-tiki-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/tropical-tiki-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/tropical-tiki-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "tropical-tiki-b7",
  "name": "Tropical Tiki",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.43",
  "rtp_variants": [
    {
      "rtp": "96.43",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.20",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2022-07-21",
  "themes": [
    {
      "slug": "tiki",
      "name": "Tiki"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/tropical-tiki-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/tropical-tiki-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tropical-tiki-b7/demand/
```

**12-month volume (illustrative):** 3,110 · **trend:** declining · YoY -21.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Netherlands | 320 | flat |
| Croatia | 250 | declining |
| Brazil | 210 | growing |
| Indonesia | 160 | flat |
| Greece | 130 | flat |
| Belgium | 120 | flat |
| Malaysia | 120 | declining |
| Italy | 110 | growing |
| Canada | 100 | growing |
| Germany | 100 | flat |

> Full per-country breakdown (46 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/tropical-tiki-b7/
- **Public page:** https://i-gaming.tools/slot-games/tropical-tiki-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
