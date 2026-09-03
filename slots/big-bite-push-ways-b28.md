# Big Bite Push Ways

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-bite-push-ways-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bite-push-ways-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-bite-push-ways-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-bite-push-ways-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-bite-push-ways-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-bite-push-ways-b28",
  "name": "Big Bite Push Ways",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.27",
  "rtp_variants": [
    {
      "rtp": "96.27",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.37",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.36",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Bonus Symbol Feature",
      "cost": "120.00",
      "is_default": true
    }
  ],
  "release_date": "2025-03-13",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "winter",
      "name": "Winter"
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
      "slug": "level-progression",
      "name": "Level Progression"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/big-bite-push-ways-b28/"
    }
  },
  "series": {
    "slug": "big-bite",
    "name": "Big Bite"
  }
}
```

## Search Demand

`GET /api/v1/slots/big-bite-push-ways-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bite-push-ways-b28/demand/
```

**12-month volume (illustrative):** 1,940 · **trend:** growing · YoY +39.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 240 | flat |
| Finland | 200 | flat |
| Netherlands | 150 | flat |
| Greece | 130 | flat |
| Latvia | 120 | flat |
| United Kingdom | 120 | flat |
| Norway | 90 | flat |
| Italy | 80 | flat |
| India | 60 | declining |
| Sweden | 60 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-bite-push-ways-b28/
- **Public page:** https://i-gaming.tools/slot-games/big-bite-push-ways-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
