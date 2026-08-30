# Razor Returns

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/razor-returns-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-returns-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/razor-returns-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/razor-returns-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/razor-returns-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "razor-returns-b28",
  "name": "Razor Returns",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.55",
  "rtp_variants": [
    {
      "rtp": "96.55",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.55",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.16",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "3 Torpedo Free Spins",
      "cost": "106.00",
      "is_default": true
    },
    {
      "label": "4 Torpedo Free Spins",
      "cost": "186.00",
      "is_default": false
    }
  ],
  "release_date": "2023-07-04",
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
      "page_url": "https://i-gaming.tools/slot-games/razor-returns-b28/"
    }
  },
  "series": {
    "slug": "razor",
    "name": "Razor"
  }
}
```

## Search Demand

`GET /api/v1/slots/razor-returns-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-returns-b28/demand/
```

**12-month volume (illustrative):** 70,140 · **trend:** declining · YoY -29.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 28,830 | declining |
| United Kingdom | 4,820 | growing |
| Switzerland | 3,330 | growing |
| United States | 2,980 | declining |
| Austria | 2,940 | growing |
| Netherlands | 2,940 | flat |
| Sweden | 2,620 | growing |
| Finland | 2,560 | growing |
| Denmark | 2,300 | growing |
| Greece | 2,050 | growing |

> Full per-country breakdown (77 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/razor-returns-b28/
- **Public page:** https://i-gaming.tools/slot-games/razor-returns-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
