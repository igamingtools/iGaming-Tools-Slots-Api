# Multihand Blackjack

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/multihand-blackjack-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/multihand-blackjack-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/multihand-blackjack-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/multihand-blackjack-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/multihand-blackjack-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "multihand-blackjack-b10",
  "name": "Multihand Blackjack",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "table",
  "rtp_default": "99.33",
  "rtp_variants": [
    {
      "rtp": "99.33",
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
  "release_date": null,
  "themes": [],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/multihand-blackjack-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/multihand-blackjack-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/multihand-blackjack-b10/demand/
```

**12-month volume (illustrative):** 460 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 80 | growing |
| Canada | 60 | flat |
| Finland | 40 | growing |
| India | 40 | growing |
| Sweden | 30 | flat |
| United Kingdom | 30 | flat |
| Australia | 20 | growing |
| Germany | 20 | growing |
| Indonesia | 20 | flat |
| Netherlands | 20 | flat |

> Full per-country breakdown (17 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/multihand-blackjack-b10/
- **Public page:** https://i-gaming.tools/slot-games/multihand-blackjack-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
