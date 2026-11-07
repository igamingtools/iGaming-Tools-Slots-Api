# Vampire's Charm

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/vampire-s-charm-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/vampire-s-charm-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/vampire-s-charm-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/vampire-s-charm-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/vampire-s-charm-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "vampire-s-charm-b30",
  "name": "Vampire's Charm",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.75",
  "rtp_variants": [
    {
      "rtp": "96.75",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-10-01",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "vampires",
      "name": "Vampires"
    }
  ],
  "features": [
    {
      "slug": "expanding-symbols",
      "name": "Expanding Symbols"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/vampire-s-charm-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/vampire-s-charm-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/vampire-s-charm-b30/demand/
```

**12-month volume (illustrative):** 350 · **trend:** declining · YoY -45.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 200 | flat |
| Philippines | 50 | growing |
| Indonesia | 20 | flat |
| Mexico | 20 | flat |
| Chile | 10 | flat |
| El Salvador | 10 | flat |
| Netherlands | 10 | flat |
| Peru | 10 | flat |
| Thailand | 10 | flat |
| Ukraine | 10 | flat |

> Full per-country breakdown (10 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/vampire-s-charm-b30/
- **Public page:** https://i-gaming.tools/slot-games/vampire-s-charm-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
