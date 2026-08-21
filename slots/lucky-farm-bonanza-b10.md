# Lucky Farm Bonanza

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lucky-farm-bonanza-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-farm-bonanza-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lucky-farm-bonanza-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lucky-farm-bonanza-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lucky-farm-bonanza-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lucky-farm-bonanza-b10",
  "name": "Lucky Farm Bonanza",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.97",
  "rtp_variants": [
    {
      "rtp": "95.97",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.03",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2022-04-01",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "farm",
      "name": "Farm"
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
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/lucky-farm-bonanza-b10/"
    }
  },
  "series": {
    "slug": "lucky-farm-bonanza",
    "name": "Lucky Farm Bonanza"
  }
}
```

## Search Demand

`GET /api/v1/slots/lucky-farm-bonanza-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-farm-bonanza-b10/demand/
```

**12-month volume (illustrative):** 530 · **trend:** growing · YoY +12.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 110 | flat |
| Belgium | 60 | flat |
| New Zealand | 50 | flat |
| Brazil | 40 | flat |
| United Kingdom | 40 | growing |
| Germany | 20 | flat |
| India | 20 | flat |
| Philippines | 20 | declining |
| Portugal | 20 | declining |
| South Africa | 20 | declining |

> Full per-country breakdown (23 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lucky-farm-bonanza-b10/
- **Public page:** https://i-gaming.tools/slot-games/lucky-farm-bonanza-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
