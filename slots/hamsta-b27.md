# Hamsta

**Provider:** Turbo Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/hamsta-b27/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hamsta-b27/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/hamsta-b27/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/hamsta-b27/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/hamsta-b27/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "hamsta-b27",
  "name": "Hamsta",
  "status": "active",
  "provider": {
    "slug": "turbo-games",
    "name": "Turbo Games"
  },
  "game_category": "crash",
  "rtp_default": "95.00",
  "rtp_variants": [
    {
      "rtp": "95.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-10-01",
  "themes": [
    {
      "slug": "post-apocalyptic",
      "name": "Post-Apocalyptic"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    },
    {
      "slug": "zombies",
      "name": "Zombies"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
    },
    {
      "slug": "prize-ladder",
      "name": "Prize Ladder"
    },
    {
      "slug": "variable_volatility",
      "name": "Variable Volatility"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/hamsta-b27/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/hamsta-b27/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hamsta-b27/demand/
```

**12-month volume (illustrative):** 650 · **trend:** declining · YoY -8.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 420 | flat |
| South Africa | 90 | growing |
| Vietnam | 40 | growing |
| Greece | 20 | flat |
| Netherlands | 20 | flat |
| Pakistan | 20 | flat |
| Algeria | 10 | flat |
| France | 10 | flat |
| Hungary | 10 | flat |
| Saudi Arabia | 10 | flat |

> Full per-country breakdown (10 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/hamsta-b27/
- **Public page:** https://i-gaming.tools/slot-games/hamsta-b27/
- **Full schema:** https://i-gaming.tools/api/docs/
