# Cosmic Cash

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/cosmic-cash-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cosmic-cash-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/cosmic-cash-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/cosmic-cash-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/cosmic-cash-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "cosmic-cash-b7",
  "name": "Cosmic Cash",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.56",
  "rtp_variants": [
    {
      "rtp": "96.56",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.58",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Cosmic Respins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2022-07-14",
  "themes": [
    {
      "slug": "aliens",
      "name": "Aliens"
    },
    {
      "slug": "money",
      "name": "Money"
    },
    {
      "slug": "space",
      "name": "Space"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
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
      "page_url": "https://i-gaming.tools/slot-games/cosmic-cash-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/cosmic-cash-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cosmic-cash-b7/demand/
```

**12-month volume (illustrative):** 17,170 · **trend:** flat · YoY +0.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 3,380 | declining |
| Mexico | 2,710 | flat |
| Switzerland | 2,190 | growing |
| Argentina | 1,680 | declining |
| Brazil | 1,250 | growing |
| Greece | 730 | declining |
| Spain | 680 | growing |
| Canada | 580 | flat |
| India | 240 | flat |
| United States | 240 | flat |

> Full per-country breakdown (63 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/cosmic-cash-b7/
- **Public page:** https://i-gaming.tools/slot-games/cosmic-cash-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
