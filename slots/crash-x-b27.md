# Crash X

**Provider:** Turbo Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/crash-x-b27/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/crash-x-b27/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/crash-x-b27/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/crash-x-b27/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/crash-x-b27/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "crash-x-b27",
  "name": "Crash X",
  "status": "active",
  "provider": {
    "slug": "turbo-games",
    "name": "Turbo Games"
  },
  "game_category": "crash",
  "rtp_default": "95.99",
  "rtp_variants": [
    {
      "rtp": "95.99",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "88.07",
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
  "release_date": "2021-03-12",
  "themes": [
    {
      "slug": "space",
      "name": "Space"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
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
      "page_url": "https://i-gaming.tools/slot-games/crash-x-b27/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/crash-x-b27/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/crash-x-b27/demand/
```

**12-month volume (illustrative):** 1,220 · **trend:** declining · YoY -42.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 200 | flat |
| Indonesia | 100 | declining |
| United States | 70 | flat |
| Canada | 60 | declining |
| Germany | 60 | flat |
| Netherlands | 60 | flat |
| Pakistan | 60 | flat |
| Ukraine | 60 | flat |
| Vietnam | 60 | declining |
| Algeria | 30 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/crash-x-b27/
- **Public page:** https://i-gaming.tools/slot-games/crash-x-b27/
- **Full schema:** https://i-gaming.tools/api/docs/
