# Hand of Midas 2

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/hand-of-midas-2-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hand-of-midas-2-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/hand-of-midas-2-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/hand-of-midas-2-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/hand-of-midas-2-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "hand-of-midas-2-b7",
  "name": "Hand of Midas 2",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.07",
  "rtp_variants": [
    {
      "rtp": "96.07",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.04",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-06-27",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
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
      "page_url": "https://i-gaming.tools/slot-games/hand-of-midas-2-b7/"
    }
  },
  "series": {
    "slug": "hand-of-midas",
    "name": "Hand of Midas"
  }
}
```

## Search Demand

`GET /api/v1/slots/hand-of-midas-2-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hand-of-midas-2-b7/demand/
```

**12-month volume (illustrative):** 10,070 · **trend:** declining · YoY -24.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 1,480 | declining |
| Greece | 1,420 | declining |
| Italy | 770 | growing |
| Switzerland | 450 | flat |
| Canada | 400 | flat |
| Brazil | 360 | declining |
| Germany | 330 | flat |
| United Kingdom | 270 | flat |
| Romania | 250 | declining |
| Indonesia | 230 | declining |

> Full per-country breakdown (55 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/hand-of-midas-2-b7/
- **Public page:** https://i-gaming.tools/slot-games/hand-of-midas-2-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
