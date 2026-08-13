# Fortune Red Packets

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fortune-red-packets-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fortune-red-packets-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fortune-red-packets-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fortune-red-packets-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fortune-red-packets-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fortune-red-packets-b10",
  "name": "Fortune Red Packets",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "crash",
  "rtp_default": "98.40",
  "rtp_variants": [
    {
      "rtp": "98.40",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-02-10",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    }
  ],
  "features": [
    {
      "slug": "prize-ladder",
      "name": "Prize Ladder"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fortune-red-packets-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fortune-red-packets-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fortune-red-packets-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fortune-red-packets-b10/
- **Public page:** https://i-gaming.tools/slot-games/fortune-red-packets-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
