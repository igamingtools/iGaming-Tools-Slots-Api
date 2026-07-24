# Zeus vs Hades – Gods of War

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/zeus-vs-hades-gods-of-war-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "zeus-vs-hades-gods-of-war-b7",
  "name": "Zeus vs Hades – Gods of War",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.05",
  "rtp_variants": [
    {
      "rtp": "96.05",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.04",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.01",
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
      "label": "Olympus Free Spins",
      "cost": "75.00",
      "is_default": true
    },
    {
      "label": "Olympus Super Free Spins",
      "cost": "300.00",
      "is_default": false
    }
  ],
  "release_date": "2023-05-22",
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
      "page_url": "https://i-gaming.tools/slot-games/zeus-vs-hades-gods-of-war-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/zeus-vs-hades-gods-of-war-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-b7/demand/
```

**12-month volume (illustrative):** 6,040 · **trend:** growing · YoY +33.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 460 | growing |
| Brazil | 440 | declining |
| United Kingdom | 310 | declining |
| Canada | 280 | flat |
| Germany | 250 | flat |
| India | 240 | growing |
| Greece | 220 | flat |
| Argentina | 210 | flat |
| Netherlands | 200 | flat |
| Malaysia | 180 | growing |

> Full per-country breakdown (53 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/zeus-vs-hades-gods-of-war-b7/
- **Public page:** https://i-gaming.tools/slot-games/zeus-vs-hades-gods-of-war-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
