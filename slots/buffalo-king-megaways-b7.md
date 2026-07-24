# Buffalo King Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/buffalo-king-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/buffalo-king-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/buffalo-king-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/buffalo-king-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/buffalo-king-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "buffalo-king-megaways-b7",
  "name": "Buffalo King Megaways",
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
      "rtp": "96.49",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.50",
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
  "release_date": "2021-04-29",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "hunting",
      "name": "Hunting"
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
      "page_url": "https://i-gaming.tools/slot-games/buffalo-king-megaways-b7/"
    }
  },
  "series": {
    "slug": "buffalo-king",
    "name": "Buffalo King"
  }
}
```

## Search Demand

`GET /api/v1/slots/buffalo-king-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/buffalo-king-megaways-b7/demand/
```

**12-month volume (illustrative):** 23,000 · **trend:** flat · YoY +3.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 3,200 | declining |
| United Kingdom | 2,490 | declining |
| Greece | 2,280 | declining |
| Netherlands | 1,910 | flat |
| Argentina | 1,370 | growing |
| Germany | 1,340 | flat |
| Brazil | 980 | flat |
| Belgium | 680 | flat |
| Hungary | 640 | flat |
| United States | 580 | flat |

> Full per-country breakdown (61 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/buffalo-king-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/buffalo-king-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
