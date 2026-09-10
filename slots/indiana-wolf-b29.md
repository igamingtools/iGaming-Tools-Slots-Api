# Indiana Wolf

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/indiana-wolf-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/indiana-wolf-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/indiana-wolf-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/indiana-wolf-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/indiana-wolf-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "indiana-wolf-b29",
  "name": "Indiana Wolf",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.39",
  "rtp_variants": [
    {
      "rtp": "96.39",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.13",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.76",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "variable_ways",
  "reels": 5,
  "rows": null,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature (3-5 Scatters)",
      "cost": "59.96",
      "is_default": true
    }
  ],
  "release_date": "2025-09-16",
  "themes": [
    {
      "slug": "native-american",
      "name": "Native American"
    },
    {
      "slug": "wolves",
      "name": "Wolves"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/indiana-wolf-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/indiana-wolf-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/indiana-wolf-b29/demand/
```

**12-month volume (illustrative):** 500 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 310 | growing |
| India | 40 | flat |
| Lebanon | 30 | flat |
| Panama | 30 | flat |
| Belgium | 20 | flat |
| Germany | 10 | flat |
| Ghana | 10 | flat |
| Jordan | 10 | flat |
| Lithuania | 10 | flat |
| Mexico | 10 | flat |

> Full per-country breakdown (12 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/indiana-wolf-b29/
- **Public page:** https://i-gaming.tools/slot-games/indiana-wolf-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
