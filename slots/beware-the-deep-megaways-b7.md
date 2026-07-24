# Beware The Deep Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/beware-the-deep-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/beware-the-deep-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/beware-the-deep-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/beware-the-deep-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/beware-the-deep-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "beware-the-deep-megaways-b7",
  "name": "Beware The Deep Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.52",
  "rtp_variants": [
    {
      "rtp": "96.52",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.53",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.51",
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
      "label": "Bonus Buy",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Buy",
      "cost": "250.00",
      "is_default": false
    }
  ],
  "release_date": "2024-03-11",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "monsters",
      "name": "Monsters"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "gamble",
      "name": "Gamble"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/beware-the-deep-megaways-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/beware-the-deep-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/beware-the-deep-megaways-b7/demand/
```

**12-month volume (illustrative):** 1,570 · **trend:** declining · YoY -21.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | declining |
| Greece | 90 | declining |
| Indonesia | 80 | growing |
| Italy | 80 | flat |
| Philippines | 70 | flat |
| United Kingdom | 70 | declining |
| Argentina | 60 | declining |
| Bulgaria | 60 | flat |
| Canada | 60 | flat |
| Romania | 50 | flat |

> Full per-country breakdown (41 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/beware-the-deep-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/beware-the-deep-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
