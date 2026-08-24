# Rings Of Olympus

**Provider:** Turbo Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rings-of-olympus-b27/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rings-of-olympus-b27/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rings-of-olympus-b27/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rings-of-olympus-b27/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rings-of-olympus-b27/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rings-of-olympus-b27",
  "name": "Rings Of Olympus",
  "status": "active",
  "provider": {
    "slug": "turbo-games",
    "name": "Turbo Games"
  },
  "game_category": "crash",
  "rtp_default": "93.56",
  "rtp_variants": [
    {
      "rtp": "93.56",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.16",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-05-01",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "cash-out",
      "name": "Cash Out"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rings-of-olympus-b27/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rings-of-olympus-b27/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rings-of-olympus-b27/demand/
```

**12-month volume (illustrative):** 940 · **trend:** growing · YoY +754.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 240 | flat |
| Greece | 70 | flat |
| Tunisia | 70 | flat |
| Cyprus | 40 | flat |
| Germany | 40 | flat |
| Pakistan | 40 | flat |
| Ukraine | 40 | flat |
| United States | 40 | flat |
| United Kingdom | 30 | flat |
| Australia | 20 | growing |

> Full per-country breakdown (32 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rings-of-olympus-b27/
- **Public page:** https://i-gaming.tools/slot-games/rings-of-olympus-b27/
- **Full schema:** https://i-gaming.tools/api/docs/
