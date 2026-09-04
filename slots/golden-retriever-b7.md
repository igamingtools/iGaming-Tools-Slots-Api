# Golden Retriever

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/golden-retriever-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-retriever-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/golden-retriever-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/golden-retriever-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/golden-retriever-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "golden-retriever-b7",
  "name": "Golden Retriever",
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
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.52",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "120.00",
      "is_default": true
    },
    {
      "label": "Buy Super Feature",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2026-08-20",
  "themes": [
    {
      "slug": "dogs",
      "name": "Dogs"
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/golden-retriever-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/golden-retriever-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-retriever-b7/demand/
```

**12-month volume (illustrative):** 140 · **trend:** growing · YoY +16.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 120 | flat |
| Austria | 10 | growing |
| Switzerland | 10 | flat |

> Full per-country breakdown (3 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/golden-retriever-b7/
- **Public page:** https://i-gaming.tools/slot-games/golden-retriever-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
