# Fire 88

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fire-88-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fire-88-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fire-88-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fire-88-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fire-88-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fire-88-b7",
  "name": "Fire 88",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.45",
  "rtp_variants": [
    {
      "rtp": "96.45",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2018-04-26",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
    }
  ],
  "features": [
    {
      "slug": "pick_bonus",
      "name": "Pick Bonus"
    },
    {
      "slug": "respin",
      "name": "Respin"
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
      "page_url": "https://i-gaming.tools/slot-games/fire-88-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fire-88-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fire-88-b7/demand/
```

**12-month volume (illustrative):** 1,320 · **trend:** flat · YoY +3.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 130 | flat |
| Nicaragua | 130 | flat |
| El Salvador | 100 | flat |
| Indonesia | 100 | declining |
| Mexico | 80 | flat |
| Peru | 80 | growing |
| India | 60 | flat |
| Argentina | 50 | declining |
| Guatemala | 50 | declining |
| Finland | 40 | flat |

> Full per-country breakdown (36 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fire-88-b7/
- **Public page:** https://i-gaming.tools/slot-games/fire-88-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
