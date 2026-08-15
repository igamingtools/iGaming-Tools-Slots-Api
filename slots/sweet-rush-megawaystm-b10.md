# Sweet Rush MEGAWAYS™

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sweet-rush-megawaystm-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sweet-rush-megawaystm-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sweet-rush-megawaystm-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sweet-rush-megawaystm-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sweet-rush-megawaystm-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sweet-rush-megawaystm-b10",
  "name": "Sweet Rush MEGAWAYS™",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.69",
  "rtp_variants": [
    {
      "rtp": "96.69",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.69",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.69",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
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
  "release_date": "2023-02-16",
  "themes": [
    {
      "slug": "monsters",
      "name": "Monsters"
    },
    {
      "slug": "sweets",
      "name": "Sweets"
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
      "page_url": "https://i-gaming.tools/slot-games/sweet-rush-megawaystm-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/sweet-rush-megawaystm-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sweet-rush-megawaystm-b10/demand/
```

**12-month volume (illustrative):** 2,120 · **trend:** growing · YoY +63.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 210 | declining |
| United States | 160 | flat |
| Brazil | 130 | declining |
| Germany | 120 | declining |
| Switzerland | 90 | declining |
| Canada | 80 | flat |
| India | 80 | declining |
| Portugal | 80 | declining |
| Australia | 60 | flat |
| Belgium | 60 | declining |

> Full per-country breakdown (47 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sweet-rush-megawaystm-b10/
- **Public page:** https://i-gaming.tools/slot-games/sweet-rush-megawaystm-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
