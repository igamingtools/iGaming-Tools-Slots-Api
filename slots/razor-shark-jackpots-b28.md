# Razor Shark Jackpots

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/razor-shark-jackpots-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-shark-jackpots-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/razor-shark-jackpots-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/razor-shark-jackpots-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/razor-shark-jackpots-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "razor-shark-jackpots-b28",
  "name": "Razor Shark Jackpots",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.38",
  "rtp_variants": [
    {
      "rtp": "96.38",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.18",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-06-03",
  "themes": [
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "sharks",
      "name": "Sharks"
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
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/razor-shark-jackpots-b28/"
    }
  },
  "series": {
    "slug": "razor",
    "name": "Razor"
  }
}
```

## Search Demand

`GET /api/v1/slots/razor-shark-jackpots-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-shark-jackpots-b28/demand/
```

**12-month volume (illustrative):** 1,230 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 100 | declining |
| Germany | 90 | growing |
| Finland | 80 | declining |
| Canada | 60 | flat |
| Switzerland | 60 | flat |
| Netherlands | 50 | flat |
| Norway | 50 | growing |
| Belgium | 40 | declining |
| Denmark | 40 | declining |
| Sweden | 40 | declining |

> Full per-country breakdown (43 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/razor-shark-jackpots-b28/
- **Public page:** https://i-gaming.tools/slot-games/razor-shark-jackpots-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
