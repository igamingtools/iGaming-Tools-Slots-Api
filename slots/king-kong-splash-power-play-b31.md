# King Kong Splash Power Play

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/king-kong-splash-power-play-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/king-kong-splash-power-play-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/king-kong-splash-power-play-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/king-kong-splash-power-play-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/king-kong-splash-power-play-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "king-kong-splash-power-play-b31",
  "name": "King Kong Splash Power Play",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "94.00",
  "rtp_variants": [
    {
      "rtp": "94.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "94.00",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-08-13",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "fishing",
      "name": "Fishing"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
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
      "page_url": "https://i-gaming.tools/slot-games/king-kong-splash-power-play-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/king-kong-splash-power-play-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/king-kong-splash-power-play-b31/demand/
```

**12-month volume (illustrative):** 220 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 80 | declining |
| Austria | 20 | flat |
| Brazil | 20 | flat |
| Canada | 20 | declining |
| Netherlands | 20 | flat |
| Spain | 20 | flat |
| Denmark | 10 | declining |
| Ireland | 10 | declining |
| New Zealand | 10 | declining |
| Sweden | 10 | declining |

> Full per-country breakdown (10 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/king-kong-splash-power-play-b31/
- **Public page:** https://i-gaming.tools/slot-games/king-kong-splash-power-play-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
