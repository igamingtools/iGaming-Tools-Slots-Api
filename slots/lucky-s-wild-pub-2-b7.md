# Lucky's Wild Pub 2

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lucky-s-wild-pub-2-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-s-wild-pub-2-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lucky-s-wild-pub-2-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lucky-s-wild-pub-2-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lucky-s-wild-pub-2-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lucky-s-wild-pub-2-b7",
  "name": "Lucky's Wild Pub 2",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "BUY ZONE POT",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "BUY X100 ZONE POT",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2026-03-12",
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "multiplier-spots",
      "name": "Multiplier Spots"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/lucky-s-wild-pub-2-b7/"
    }
  },
  "series": {
    "slug": "luckys-wild-pub",
    "name": "Lucky's Wild Pub"
  }
}
```

## Search Demand

`GET /api/v1/slots/lucky-s-wild-pub-2-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-s-wild-pub-2-b7/demand/
```

**12-month volume (illustrative):** 870 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 100 | flat |
| South Africa | 70 | declining |
| Switzerland | 60 | declining |
| United States | 60 | declining |
| Brazil | 50 | declining |
| New Zealand | 40 | flat |
| Australia | 30 | growing |
| Austria | 30 | flat |
| Greece | 30 | declining |
| Mexico | 30 | flat |

> Full per-country breakdown (32 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lucky-s-wild-pub-2-b7/
- **Public page:** https://i-gaming.tools/slot-games/lucky-s-wild-pub-2-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
