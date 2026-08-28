# 3 Magic Pots

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/3-magic-pots-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/3-magic-pots-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/3-magic-pots-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/3-magic-pots-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/3-magic-pots-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "3-magic-pots-b28",
  "name": "3 Magic Pots",
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
      "rtp": "94.25",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-04-30",
  "themes": [
    {
      "slug": "fantasy",
      "name": "Fantasy"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
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
      "page_url": "https://i-gaming.tools/slot-games/3-magic-pots-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/3-magic-pots-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/3-magic-pots-b28/demand/
```

**12-month volume (illustrative):** 1,620 · **trend:** growing · YoY +80.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 260 | flat |
| Brazil | 160 | flat |
| United States | 160 | declining |
| Greece | 150 | flat |
| Canada | 140 | flat |
| Netherlands | 110 | flat |
| United Kingdom | 100 | flat |
| Sweden | 80 | growing |
| Australia | 70 | declining |
| Spain | 50 | flat |

> Full per-country breakdown (31 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/3-magic-pots-b28/
- **Public page:** https://i-gaming.tools/slot-games/3-magic-pots-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
