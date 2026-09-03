# Fish 'n' Nudge

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fish-n-nudge-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fish-n-nudge-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fish-n-nudge-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fish-n-nudge-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fish-n-nudge-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fish-n-nudge-b28",
  "name": "Fish 'n' Nudge",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.40",
  "rtp_variants": [
    {
      "rtp": "96.40",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.41",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "94.38",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Initial Multiplier x1",
      "cost": "42.00",
      "is_default": true
    },
    {
      "label": "Initial Multiplier x10",
      "cost": "87.00",
      "is_default": false
    }
  ],
  "release_date": "2023-10-10",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
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
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fish-n-nudge-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fish-n-nudge-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fish-n-nudge-b28/demand/
```

**12-month volume (illustrative):** 920 · **trend:** declining · YoY -39.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 110 | flat |
| Finland | 80 | growing |
| Denmark | 70 | flat |
| Netherlands | 70 | declining |
| Canada | 60 | flat |
| Greece | 60 | declining |
| Norway | 60 | declining |
| Romania | 50 | flat |
| Sweden | 50 | flat |
| Germany | 40 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fish-n-nudge-b28/
- **Public page:** https://i-gaming.tools/slot-games/fish-n-nudge-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
