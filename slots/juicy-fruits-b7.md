# Juicy Fruits

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/juicy-fruits-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/juicy-fruits-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/juicy-fruits-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/juicy-fruits-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/juicy-fruits-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "juicy-fruits-b7",
  "name": "Juicy Fruits",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.51",
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
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2021-03-25",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
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
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/juicy-fruits-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/juicy-fruits-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/juicy-fruits-b7/demand/
```

**12-month volume (illustrative):** 26,520 · **trend:** declining · YoY -21.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 2,780 | flat |
| Romania | 2,410 | declining |
| Netherlands | 2,210 | flat |
| Canada | 1,600 | declining |
| Denmark | 1,440 | declining |
| United Kingdom | 1,390 | growing |
| Finland | 1,020 | growing |
| United States | 900 | declining |
| Croatia | 800 | declining |
| Switzerland | 780 | growing |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/juicy-fruits-b7/
- **Public page:** https://i-gaming.tools/slot-games/juicy-fruits-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
