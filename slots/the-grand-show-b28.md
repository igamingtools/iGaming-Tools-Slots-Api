# The Grand Show

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/the-grand-show-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-grand-show-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/the-grand-show-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/the-grand-show-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/the-grand-show-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "the-grand-show-b28",
  "name": "The Grand Show",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.28",
  "rtp_variants": [
    {
      "rtp": "96.28",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.35",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.38",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Minimum x1 Instant Prizes",
      "cost": "46.40",
      "is_default": true
    },
    {
      "label": "Minimum x5 Instant Prizes",
      "cost": "86.60",
      "is_default": false
    }
  ],
  "release_date": "2024-07-17",
  "themes": [
    {
      "slug": "carnival",
      "name": "Carnival"
    },
    {
      "slug": "tigers",
      "name": "Tigers"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
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
      "page_url": "https://i-gaming.tools/slot-games/the-grand-show-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/the-grand-show-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-grand-show-b28/demand/
```

**12-month volume (illustrative):** 1,270 · **trend:** declining · YoY -44.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 140 | declining |
| Greece | 110 | flat |
| United States | 100 | flat |
| Brazil | 80 | flat |
| Italy | 70 | declining |
| Spain | 70 | flat |
| Sweden | 70 | flat |
| Denmark | 60 | flat |
| Finland | 60 | flat |
| Netherlands | 60 | flat |

> Full per-country breakdown (31 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/the-grand-show-b28/
- **Public page:** https://i-gaming.tools/slot-games/the-grand-show-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
