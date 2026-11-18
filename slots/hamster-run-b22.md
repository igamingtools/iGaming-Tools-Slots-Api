# Hamster Run

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/hamster-run-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hamster-run-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/hamster-run-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/hamster-run-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/hamster-run-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "hamster-run-b22",
  "name": "Hamster Run",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "instant_win",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "100% Chance to Get Free Spins (Super Deal)",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "25% Chance to Get Free Spins",
      "cost": "25.00",
      "is_default": false
    }
  ],
  "release_date": "2025-03-24",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "carnival",
      "name": "Carnival"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/hamster-run-b22/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/hamster-run-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hamster-run-b22/demand/
```

**12-month volume (illustrative):** 1,100 · **trend:** growing · YoY +69.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 580 | flat |
| Pakistan | 260 | flat |
| Brazil | 60 | flat |
| Canada | 40 | growing |
| Germany | 30 | flat |
| Indonesia | 20 | flat |
| Vietnam | 20 | flat |
| Austria | 10 | flat |
| Bahrain | 10 | flat |
| Denmark | 10 | flat |

> Full per-country breakdown (16 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/hamster-run-b22/
- **Public page:** https://i-gaming.tools/slot-games/hamster-run-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
