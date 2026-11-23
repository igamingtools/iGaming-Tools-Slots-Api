# Legend Of Nezha

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/legend-of-nezha-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/legend-of-nezha-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/legend-of-nezha-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/legend-of-nezha-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/legend-of-nezha-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "legend-of-nezha-b29",
  "name": "Legend Of Nezha",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.78",
  "rtp_variants": [
    {
      "rtp": "96.78",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.64",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.70",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "pooled",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Games",
      "cost": "31.71",
      "is_default": true
    }
  ],
  "release_date": "2023-07-01",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
    },
    {
      "slug": "fire",
      "name": "Fire"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "duplicating-wild",
      "name": "Duplicating Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/legend-of-nezha-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/legend-of-nezha-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/legend-of-nezha-b29/demand/
```

**12-month volume (illustrative):** 2,950 · **trend:** declining · YoY -46.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 2,520 | declining |
| Malaysia | 60 | flat |
| United States | 60 | flat |
| Philippines | 40 | declining |
| Singapore | 40 | declining |
| Indonesia | 30 | growing |
| Hungary | 20 | flat |
| India | 20 | flat |
| Pakistan | 20 | declining |
| Thailand | 20 | growing |

> Full per-country breakdown (22 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/legend-of-nezha-b29/
- **Public page:** https://i-gaming.tools/slot-games/legend-of-nezha-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
