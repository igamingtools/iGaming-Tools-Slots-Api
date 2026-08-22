# Release the Kraken Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/release-the-kraken-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/release-the-kraken-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/release-the-kraken-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/release-the-kraken-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/release-the-kraken-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "release-the-kraken-megaways-b7",
  "name": "Release the Kraken Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.40",
  "rtp_variants": [
    {
      "rtp": "96.40",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.53",
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
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins - 3 BONUS Symbols Guaranteed",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Free Spins - 4, 5 or 6 BONUS Symbols Randomly",
      "cost": "150.00",
      "is_default": false
    }
  ],
  "release_date": "2024-10-14",
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
      "slug": "pirates",
      "name": "Pirates"
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
      "page_url": "https://i-gaming.tools/slot-games/release-the-kraken-megaways-b7/"
    }
  },
  "series": {
    "slug": "release-the-kraken",
    "name": "Release the Kraken"
  }
}
```

## Search Demand

`GET /api/v1/slots/release-the-kraken-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/release-the-kraken-megaways-b7/demand/
```

**12-month volume (illustrative):** 4,370 · **trend:** declining · YoY -34.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 240 | flat |
| Finland | 220 | flat |
| Greece | 210 | flat |
| Denmark | 180 | flat |
| Switzerland | 180 | flat |
| Malaysia | 160 | flat |
| United Kingdom | 150 | flat |
| United States | 150 | declining |
| Philippines | 130 | growing |
| South Africa | 130 | flat |

> Full per-country breakdown (56 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/release-the-kraken-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/release-the-kraken-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
