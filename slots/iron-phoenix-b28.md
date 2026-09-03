# Iron Phoenix

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/iron-phoenix-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/iron-phoenix-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/iron-phoenix-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/iron-phoenix-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/iron-phoenix-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "iron-phoenix-b28",
  "name": "Iron Phoenix",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.24",
  "rtp_variants": [
    {
      "rtp": "96.24",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.38",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "94.01",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Bonus Symbols",
      "cost": "65.00",
      "is_default": true
    }
  ],
  "release_date": "2025-06-25",
  "themes": [
    {
      "slug": "birds",
      "name": "Birds"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
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
      "page_url": "https://i-gaming.tools/slot-games/iron-phoenix-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/iron-phoenix-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/iron-phoenix-b28/demand/
```

**12-month volume (illustrative):** 800 · **trend:** growing · YoY +95.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 200 | flat |
| Greece | 90 | flat |
| Finland | 60 | flat |
| Sweden | 60 | growing |
| United Kingdom | 60 | growing |
| Belgium | 40 | growing |
| Denmark | 40 | growing |
| Germany | 40 | flat |
| United States | 40 | flat |
| Italy | 30 | flat |

> Full per-country breakdown (20 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/iron-phoenix-b28/
- **Public page:** https://i-gaming.tools/slot-games/iron-phoenix-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
