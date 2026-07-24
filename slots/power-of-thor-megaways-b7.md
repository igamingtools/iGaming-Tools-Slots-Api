# Power of Thor Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/power-of-thor-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/power-of-thor-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/power-of-thor-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/power-of-thor-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/power-of-thor-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "power-of-thor-megaways-b7",
  "name": "Power of Thor Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.55",
  "rtp_variants": [
    {
      "rtp": "96.55",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.97",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2021-04-01",
  "themes": [
    {
      "slug": "mythology",
      "name": "Mythology"
    },
    {
      "slug": "norse",
      "name": "Norse"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "gamble",
      "name": "Gamble"
    },
    {
      "slug": "megaways",
      "name": "Megaways"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/power-of-thor-megaways-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/power-of-thor-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/power-of-thor-megaways-b7/demand/
```

**12-month volume (illustrative):** 6,460 · **trend:** declining · YoY -8.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 1,080 | growing |
| Ukraine | 350 | flat |
| Canada | 280 | flat |
| Thailand | 270 | flat |
| Malaysia | 260 | declining |
| Indonesia | 230 | growing |
| India | 220 | flat |
| United Kingdom | 220 | flat |
| Switzerland | 210 | declining |
| Greece | 190 | flat |

> Full per-country breakdown (55 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/power-of-thor-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/power-of-thor-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
