# Lucky Clover Riches

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lucky-clover-riches-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-clover-riches-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lucky-clover-riches-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lucky-clover-riches-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lucky-clover-riches-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lucky-clover-riches-b30",
  "name": "Lucky Clover Riches",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.77",
  "rtp_variants": [
    {
      "rtp": "96.77",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2023-06-01",
  "themes": [
    {
      "slug": "irish",
      "name": "Irish"
    },
    {
      "slug": "pub",
      "name": "Pub"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/lucky-clover-riches-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/lucky-clover-riches-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-clover-riches-b30/demand/
```

**12-month volume (illustrative):** 1,030 · **trend:** growing · YoY +83.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 200 | flat |
| Brazil | 160 | growing |
| Pakistan | 120 | flat |
| Philippines | 100 | declining |
| Indonesia | 70 | flat |
| Canada | 60 | flat |
| Tunisia | 50 | declining |
| Finland | 40 | flat |
| Chile | 30 | flat |
| Vietnam | 30 | growing |

> Full per-country breakdown (22 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lucky-clover-riches-b30/
- **Public page:** https://i-gaming.tools/slot-games/lucky-clover-riches-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
