# Mad Blast

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mad-blast-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mad-blast-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mad-blast-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mad-blast-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mad-blast-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mad-blast-b28",
  "name": "Mad Blast",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.34",
  "rtp_variants": [
    {
      "rtp": "96.34",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.29",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.35",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Initial Multiplier x2 with 8 Free Spins",
      "cost": "150.00",
      "is_default": true
    },
    {
      "label": "Initial Multiplier x8 with 12 Free Spins",
      "cost": "750.00",
      "is_default": false
    }
  ],
  "release_date": "2025-02-20",
  "themes": [
    {
      "slug": "monsters",
      "name": "Monsters"
    },
    {
      "slug": "robots",
      "name": "Robots"
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
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/mad-blast-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mad-blast-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mad-blast-b28/demand/
```

**12-month volume (illustrative):** 1,510 · **trend:** declining · YoY -26.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 240 | flat |
| Greece | 110 | flat |
| Netherlands | 110 | growing |
| Belgium | 100 | flat |
| Romania | 80 | declining |
| Brazil | 70 | flat |
| Denmark | 70 | flat |
| United Kingdom | 70 | flat |
| Canada | 60 | flat |
| United States | 60 | growing |

> Full per-country breakdown (34 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mad-blast-b28/
- **Public page:** https://i-gaming.tools/slot-games/mad-blast-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
