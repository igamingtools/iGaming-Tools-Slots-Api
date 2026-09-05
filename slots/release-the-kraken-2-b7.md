# Release the Kraken® 2

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/release-the-kraken-2-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/release-the-kraken-2-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/release-the-kraken-2-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/release-the-kraken-2-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/release-the-kraken-2-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "release-the-kraken-2-b7",
  "name": "Release the Kraken® 2",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.03",
  "rtp_variants": [
    {
      "rtp": "96.03",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.01",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.03",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Standard Free Spins Buy",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "VIP Free Spins Buy (King Kraken)",
      "cost": "250.00",
      "is_default": false
    }
  ],
  "release_date": "2022-11-03",
  "themes": [
    {
      "slug": "monsters",
      "name": "Monsters"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
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
      "page_url": "https://i-gaming.tools/slot-games/release-the-kraken-2-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/release-the-kraken-2-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/release-the-kraken-2-b7/demand/
```

**12-month volume (illustrative):** 5,890 · **trend:** declining · YoY -25.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 540 | flat |
| Greece | 510 | declining |
| Brazil | 310 | declining |
| Canada | 260 | flat |
| South Africa | 260 | flat |
| United States | 220 | flat |
| Finland | 160 | flat |
| Pakistan | 140 | flat |
| Germany | 120 | flat |
| Latvia | 120 | flat |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/release-the-kraken-2-b7/
- **Public page:** https://i-gaming.tools/slot-games/release-the-kraken-2-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
