# Joker Poker

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/joker-poker-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/joker-poker-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/joker-poker-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/joker-poker-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/joker-poker-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "joker-poker-b22",
  "name": "Joker Poker",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "table",
  "rtp_default": "97.95",
  "rtp_variants": [
    {
      "rtp": "97.95",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-03-25",
  "themes": [
    {
      "slug": "cards",
      "name": "Cards"
    }
  ],
  "features": [
    {
      "slug": "gamble",
      "name": "Gamble"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/joker-poker-b22/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/joker-poker-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/joker-poker-b22/demand/
```

**12-month volume (illustrative):** 2,120 · **trend:** flat · YoY +2.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 480 | growing |
| India | 200 | flat |
| United States | 130 | flat |
| Germany | 120 | flat |
| Brazil | 110 | flat |
| Romania | 100 | flat |
| South Africa | 90 | flat |
| Pakistan | 80 | flat |
| United Kingdom | 80 | flat |
| Canada | 60 | growing |

> Full per-country breakdown (41 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/joker-poker-b22/
- **Public page:** https://i-gaming.tools/slot-games/joker-poker-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
