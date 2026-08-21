# Juicy Fruits Multihold

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/juicy-fruits-multihold-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/juicy-fruits-multihold-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/juicy-fruits-multihold-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/juicy-fruits-multihold-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/juicy-fruits-multihold-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "juicy-fruits-multihold-b7",
  "name": "Juicy Fruits Multihold",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.04",
  "rtp_variants": [
    {
      "rtp": "96.04",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.02",
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
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2023-12-14",
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
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    },
    {
      "slug": "multihold",
      "name": "Multihold"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/juicy-fruits-multihold-b7/"
    }
  },
  "series": {
    "slug": "juicy-fruits",
    "name": "Juicy Fruits"
  }
}
```

## Search Demand

`GET /api/v1/slots/juicy-fruits-multihold-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/juicy-fruits-multihold-b7/demand/
```

**12-month volume (illustrative):** 6,070 · **trend:** declining · YoY -11.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Netherlands | 350 | declining |
| Tunisia | 310 | declining |
| Finland | 260 | declining |
| Greece | 260 | declining |
| South Africa | 260 | declining |
| Canada | 240 | flat |
| United States | 230 | declining |
| Switzerland | 210 | flat |
| Belgium | 200 | declining |
| India | 180 | declining |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/juicy-fruits-multihold-b7/
- **Public page:** https://i-gaming.tools/slot-games/juicy-fruits-multihold-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
