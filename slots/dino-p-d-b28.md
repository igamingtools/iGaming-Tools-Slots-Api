# Dino P\.D\.

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/dino-p-d-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dino-p-d-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/dino-p-d-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/dino-p-d-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/dino-p-d-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "dino-p-d-b28",
  "name": "Dino P.D.",
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
      "rtp": "96.50",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "94.43",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Bronze Free Spins Feature",
      "cost": "70.00",
      "is_default": true
    },
    {
      "label": "Silver Free Spins Feature",
      "cost": "140.00",
      "is_default": false
    }
  ],
  "release_date": "2023-04-26",
  "themes": [
    {
      "slug": "dinosaurs",
      "name": "Dinosaurs"
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
      "page_url": "https://i-gaming.tools/slot-games/dino-p-d-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/dino-p-d-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dino-p-d-b28/demand/
```

**12-month volume (illustrative):** 1,040 · **trend:** flat · YoY -4.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 120 | declining |
| Netherlands | 120 | flat |
| Germany | 90 | flat |
| Greece | 70 | flat |
| Canada | 60 | flat |
| Romania | 60 | flat |
| Ukraine | 60 | flat |
| Australia | 50 | flat |
| Belgium | 40 | flat |
| United Kingdom | 40 | declining |

> Full per-country breakdown (26 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/dino-p-d-b28/
- **Public page:** https://i-gaming.tools/slot-games/dino-p-d-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
