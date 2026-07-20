# The Dog House – Muttley Crew

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/the-dog-house-muttley-crew-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-muttley-crew-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/the-dog-house-muttley-crew-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/the-dog-house-muttley-crew-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/the-dog-house-muttley-crew-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "the-dog-house-muttley-crew-b7",
  "name": "The Dog House – Muttley Crew",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.54",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy 10 Free Spins (3 Scatters)",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy 15 Free Spins (4 Scatters)",
      "cost": "250.00",
      "is_default": false
    }
  ],
  "release_date": "2024-10-03",
  "themes": [
    {
      "slug": "dogs",
      "name": "Dogs"
    },
    {
      "slug": "pirates",
      "name": "Pirates"
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
      "page_url": "https://i-gaming.tools/slot-games/the-dog-house-muttley-crew-b7/"
    }
  },
  "series": {
    "slug": "the-dog-house",
    "name": "The Dog House"
  }
}
```

## Search Demand

`GET /api/v1/slots/the-dog-house-muttley-crew-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-muttley-crew-b7/demand/
```

**12-month volume (illustrative):** 4,230 · **trend:** declining · YoY -10.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 620 | flat |
| Switzerland | 300 | growing |
| Canada | 200 | flat |
| Finland | 200 | growing |
| Brazil | 140 | flat |
| Germany | 140 | flat |
| Belarus | 130 | flat |
| Peru | 130 | flat |
| Hungary | 120 | flat |
| Lithuania | 120 | flat |

> Full per-country breakdown (42 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/the-dog-house-muttley-crew-b7/
- **Public page:** https://i-gaming.tools/slot-games/the-dog-house-muttley-crew-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
