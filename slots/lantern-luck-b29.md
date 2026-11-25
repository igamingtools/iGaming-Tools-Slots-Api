# Lantern Luck

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lantern-luck-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lantern-luck-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lantern-luck-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lantern-luck-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lantern-luck-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lantern-luck-b29",
  "name": "Lantern Luck",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.73",
  "rtp_variants": [
    {
      "rtp": "96.73",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "pooled",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-02-22",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "flowers",
      "name": "Flowers"
    }
  ],
  "features": [
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "respin",
      "name": "Respin"
    },
    {
      "slug": "sticky_wild",
      "name": "Sticky Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/lantern-luck-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/lantern-luck-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lantern-luck-b29/demand/
```

**12-month volume (illustrative):** 14,030 · **trend:** declining · YoY -17.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 12,680 | declining |
| Brazil | 80 | declining |
| India | 80 | growing |
| Pakistan | 80 | declining |
| Germany | 70 | flat |
| Philippines | 70 | flat |
| Argentina | 50 | growing |
| Indonesia | 50 | flat |
| Italy | 50 | growing |
| Netherlands | 50 | growing |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lantern-luck-b29/
- **Public page:** https://i-gaming.tools/slot-games/lantern-luck-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
