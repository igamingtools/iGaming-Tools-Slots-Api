# Zeus vs Hades – Gods of War 250

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "zeus-vs-hades-gods-of-war-250-b7",
  "name": "Zeus vs Hades – Gods of War 250",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.56",
  "rtp_variants": [
    {
      "rtp": "96.56",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.60",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.56",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Olympus — Free Spins",
      "cost": "75.00",
      "is_default": true
    },
    {
      "label": "Olympus — Super Free Spins 1",
      "cost": "300.00",
      "is_default": false
    }
  ],
  "release_date": "2026-02-02",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "fire",
      "name": "Fire"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
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
      "page_url": "https://i-gaming.tools/slot-games/zeus-vs-hades-gods-of-war-250-b7/"
    }
  },
  "series": {
    "slug": "zeus-vs-hades-gods-of-war",
    "name": "Zeus vs Hades – Gods of War"
  }
}
```

## Search Demand

`GET /api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/demand/
```

**12-month volume (illustrative):** 2,620 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 150 | declining |
| Canada | 120 | growing |
| Greece | 120 | declining |
| Finland | 100 | declining |
| United Kingdom | 90 | flat |
| India | 80 | flat |
| United States | 80 | flat |
| Denmark | 70 | declining |
| Australia | 60 | growing |
| Germany | 60 | declining |

> Full per-country breakdown (57 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-250-b7/
- **Public page:** https://i-gaming.tools/slot-games/zeus-vs-hades-gods-of-war-250-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
