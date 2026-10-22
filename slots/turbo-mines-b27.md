# Turbo Mines

**Provider:** Turbo Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/turbo-mines-b27/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/turbo-mines-b27/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/turbo-mines-b27/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/turbo-mines-b27/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/turbo-mines-b27/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "turbo-mines-b27",
  "name": "Turbo Mines",
  "status": "active",
  "provider": {
    "slug": "turbo-games",
    "name": "Turbo Games"
  },
  "game_category": "crash",
  "rtp_default": "94.71",
  "rtp_variants": [
    {
      "rtp": "94.71",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.89",
      "variant": "player_config",
      "is_default": false
    },
    {
      "rtp": "94.59",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-09-01",
  "themes": [
    {
      "slug": "gems",
      "name": "Gems"
    }
  ],
  "features": [
    {
      "slug": "adjustable-grid",
      "name": "Adjustable Grid"
    },
    {
      "slug": "batch-reveal",
      "name": "Batch Reveal"
    },
    {
      "slug": "cash-out",
      "name": "Cash Out"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/turbo-mines-b27/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/turbo-mines-b27/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/turbo-mines-b27/demand/
```

**12-month volume (illustrative):** 4,270 · **trend:** declining · YoY -44.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 1,560 | growing |
| Ghana | 290 | flat |
| South Africa | 260 | growing |
| Canada | 200 | flat |
| Brazil | 180 | declining |
| Italy | 130 | declining |
| Vietnam | 130 | declining |
| Pakistan | 120 | flat |
| Germany | 100 | flat |
| Indonesia | 100 | declining |

> Full per-country breakdown (46 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/turbo-mines-b27/
- **Public page:** https://i-gaming.tools/slot-games/turbo-mines-b27/
- **Full schema:** https://i-gaming.tools/api/docs/
