# Generous Jack

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/generous-jack-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/generous-jack-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/generous-jack-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/generous-jack-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/generous-jack-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "generous-jack-b28",
  "name": "Generous Jack",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.23",
  "rtp_variants": [
    {
      "rtp": "96.23",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.55",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.45",
      "variant": "feature",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Free Spins",
      "cost": "150.00",
      "is_default": true
    }
  ],
  "release_date": "2022-12-12",
  "themes": [
    {
      "slug": "casino",
      "name": "Casino"
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
      "page_url": "https://i-gaming.tools/slot-games/generous-jack-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/generous-jack-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/generous-jack-b28/demand/
```

**12-month volume (illustrative):** 1,020 · **trend:** declining · YoY -25.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 110 | flat |
| Bulgaria | 90 | flat |
| Romania | 90 | flat |
| Switzerland | 90 | flat |
| United Kingdom | 90 | declining |
| Germany | 80 | declining |
| Sweden | 70 | declining |
| Canada | 60 | growing |
| Italy | 60 | declining |
| Norway | 60 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/generous-jack-b28/
- **Public page:** https://i-gaming.tools/slot-games/generous-jack-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
