# Yum Yum PowerWays

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/yum-yum-powerways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/yum-yum-powerways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/yum-yum-powerways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/yum-yum-powerways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/yum-yum-powerways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "yum-yum-powerways-b7",
  "name": "Yum Yum PowerWays",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.43",
  "rtp_variants": [
    {
      "rtp": "96.43",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.67",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Happy Hour",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2021-09-02",
  "themes": [
    {
      "slug": "food",
      "name": "Food"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "gamble",
      "name": "Gamble"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/yum-yum-powerways-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/yum-yum-powerways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/yum-yum-powerways-b7/demand/
```

**12-month volume (illustrative):** 820 · **trend:** flat · YoY +2.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 220 | flat |
| Indonesia | 100 | flat |
| Germany | 70 | declining |
| Philippines | 50 | flat |
| Thailand | 50 | flat |
| Greece | 40 | flat |
| Argentina | 30 | flat |
| Sweden | 30 | flat |
| Denmark | 20 | flat |
| Hungary | 20 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/yum-yum-powerways-b7/
- **Public page:** https://i-gaming.tools/slot-games/yum-yum-powerways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
