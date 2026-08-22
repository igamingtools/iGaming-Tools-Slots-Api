# Clash of Gods: Anubis vs Hades

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/clash-of-gods-anubis-vs-hades-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/clash-of-gods-anubis-vs-hades-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/clash-of-gods-anubis-vs-hades-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/clash-of-gods-anubis-vs-hades-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/clash-of-gods-anubis-vs-hades-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "clash-of-gods-anubis-vs-hades-b10",
  "name": "Clash of Gods: Anubis vs Hades",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Bonus Buy",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Bonus Hunt Spins",
      "cost": "3.00",
      "is_default": false
    }
  ],
  "release_date": "2026-05-04",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "egyptian",
      "name": "Egyptian"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/clash-of-gods-anubis-vs-hades-b10/"
    }
  },
  "studio": {
    "slug": "golden-goat-gaming",
    "name": "Golden Goat Gaming"
  }
}
```

## Search Demand

`GET /api/v1/slots/clash-of-gods-anubis-vs-hades-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/clash-of-gods-anubis-vs-hades-b10/demand/
```

**12-month volume (illustrative):** 330 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 30 | flat |
| United Kingdom | 30 | flat |
| Australia | 20 | declining |
| Belarus | 20 | declining |
| Germany | 20 | growing |
| Netherlands | 20 | growing |
| United States | 20 | declining |
| Argentina | 10 | flat |
| Austria | 10 | flat |
| Brazil | 10 | declining |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/clash-of-gods-anubis-vs-hades-b10/
- **Public page:** https://i-gaming.tools/slot-games/clash-of-gods-anubis-vs-hades-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
