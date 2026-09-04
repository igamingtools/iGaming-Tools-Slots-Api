# 10 Flaming Bisons

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/10-flaming-bisons-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/10-flaming-bisons-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/10-flaming-bisons-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/10-flaming-bisons-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/10-flaming-bisons-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "10-flaming-bisons-b28",
  "name": "10 Flaming Bisons",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.26",
  "rtp_variants": [
    {
      "rtp": "96.26",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.28",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.46",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Free Spins",
      "cost": "75.00",
      "is_default": true
    }
  ],
  "release_date": "2024-12-11",
  "themes": [
    {
      "slug": "buffalo",
      "name": "Buffalo"
    },
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "native-american",
      "name": "Native American"
    }
  ],
  "features": [
    {
      "slug": "adjustable-grid",
      "name": "Adjustable Grid"
    },
    {
      "slug": "adjustable-paylines",
      "name": "Adjustable Paylines"
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
      "page_url": "https://i-gaming.tools/slot-games/10-flaming-bisons-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/10-flaming-bisons-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/10-flaming-bisons-b28/demand/
```

**12-month volume (illustrative):** 1,020 · **trend:** declining · YoY -26.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 150 | flat |
| Greece | 120 | growing |
| Canada | 100 | flat |
| Denmark | 70 | flat |
| Netherlands | 70 | declining |
| Austria | 60 | growing |
| Finland | 60 | flat |
| Germany | 50 | declining |
| India | 40 | flat |
| Spain | 40 | flat |

> Full per-country breakdown (27 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/10-flaming-bisons-b28/
- **Public page:** https://i-gaming.tools/slot-games/10-flaming-bisons-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
