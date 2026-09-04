# Joker Troupe

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/joker-troupe-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/joker-troupe-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/joker-troupe-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/joker-troupe-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/joker-troupe-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "joker-troupe-b28",
  "name": "Joker Troupe",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.68",
  "rtp_variants": [
    {
      "rtp": "96.68",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.26",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.29",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 4,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Blue Joker Feature",
      "cost": "42.50",
      "is_default": true
    },
    {
      "label": "Green Joker Wheel",
      "cost": "41.60",
      "is_default": false
    }
  ],
  "release_date": "2020-02-17",
  "themes": [
    {
      "slug": "carnival",
      "name": "Carnival"
    },
    {
      "slug": "joker",
      "name": "Joker"
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/joker-troupe-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/joker-troupe-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/joker-troupe-b28/demand/
```

**12-month volume (illustrative):** 4,940 · **trend:** declining · YoY -18.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 710 | flat |
| Romania | 250 | flat |
| Canada | 240 | flat |
| United States | 240 | flat |
| Belgium | 160 | growing |
| Finland | 160 | flat |
| Denmark | 150 | declining |
| India | 140 | flat |
| Germany | 130 | flat |
| Spain | 130 | flat |

> Full per-country breakdown (59 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/joker-troupe-b28/
- **Public page:** https://i-gaming.tools/slot-games/joker-troupe-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
