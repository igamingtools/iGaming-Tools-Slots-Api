# American Blackjack

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/american-blackjack-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/american-blackjack-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/american-blackjack-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/american-blackjack-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/american-blackjack-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "american-blackjack-b29",
  "name": "American Blackjack",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "table",
  "rtp_default": "99.65",
  "rtp_variants": [
    {
      "rtp": "99.65",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "unknown",
  "bonus_buys": [],
  "release_date": null,
  "themes": [],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/american-blackjack-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/american-blackjack-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/american-blackjack-b29/demand/
```

**12-month volume (illustrative):** 1,570 · **trend:** growing · YoY +68.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 120 | growing |
| United States | 120 | flat |
| Lebanon | 100 | flat |
| Germany | 80 | flat |
| Indonesia | 70 | flat |
| Mexico | 70 | growing |
| Argentina | 60 | declining |
| India | 60 | flat |
| Switzerland | 60 | declining |
| Tunisia | 50 | declining |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/american-blackjack-b29/
- **Public page:** https://i-gaming.tools/slot-games/american-blackjack-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
