# Mustang Gold Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mustang-gold-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mustang-gold-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mustang-gold-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mustang-gold-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mustang-gold-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mustang-gold-megaways-b7",
  "name": "Mustang Gold Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.46",
  "rtp_variants": [
    {
      "rtp": "96.46",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.47",
      "variant": "ante_bet",
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
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "120.00",
      "is_default": true
    }
  ],
  "release_date": "2024-09-02",
  "themes": [
    {
      "slug": "horses",
      "name": "Horses"
    },
    {
      "slug": "western",
      "name": "Western"
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
      "page_url": "https://i-gaming.tools/slot-games/mustang-gold-megaways-b7/"
    }
  },
  "series": {
    "slug": "mustang-gold",
    "name": "Mustang Gold"
  }
}
```

## Search Demand

`GET /api/v1/slots/mustang-gold-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mustang-gold-megaways-b7/demand/
```

**12-month volume (illustrative):** 6,280 · **trend:** declining · YoY -21.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Philippines | 1,070 | flat |
| Indonesia | 590 | declining |
| Greece | 460 | flat |
| Belgium | 340 | declining |
| Argentina | 330 | declining |
| Brazil | 250 | flat |
| Canada | 220 | flat |
| Finland | 200 | flat |
| United Kingdom | 180 | flat |
| Germany | 160 | flat |

> Full per-country breakdown (57 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mustang-gold-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/mustang-gold-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
