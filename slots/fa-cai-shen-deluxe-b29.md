# Fa Cai Shen Deluxe

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fa-cai-shen-deluxe-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fa-cai-shen-deluxe-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fa-cai-shen-deluxe-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fa-cai-shen-deluxe-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fa-cai-shen-deluxe-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fa-cai-shen-deluxe-b29",
  "name": "Fa Cai Shen Deluxe",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.75",
  "rtp_variants": [
    {
      "rtp": "96.75",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": null,
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "money",
      "name": "Money"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fa-cai-shen-deluxe-b29/"
    }
  },
  "series": {
    "slug": "fa-cai-shen",
    "name": "Fa Cai Shen"
  }
}
```

## Search Demand

`GET /api/v1/slots/fa-cai-shen-deluxe-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fa-cai-shen-deluxe-b29/demand/
```

**12-month volume (illustrative):** 1,560 · **trend:** growing · YoY +51.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 1,390 | flat |
| India | 40 | growing |
| Brazil | 30 | flat |
| Indonesia | 20 | flat |
| Argentina | 10 | flat |
| Belarus | 10 | flat |
| Chile | 10 | flat |
| Colombia | 10 | flat |
| Italy | 10 | flat |
| Portugal | 10 | flat |

> Full per-country breakdown (12 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fa-cai-shen-deluxe-b29/
- **Public page:** https://i-gaming.tools/slot-games/fa-cai-shen-deluxe-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
