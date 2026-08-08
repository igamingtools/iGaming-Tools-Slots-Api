# Luck & Magic Scratch

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/luck-magic-scratch-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/luck-magic-scratch-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/luck-magic-scratch-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/luck-magic-scratch-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/luck-magic-scratch-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "luck-magic-scratch-b10",
  "name": "Luck & Magic Scratch",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "scratch",
  "rtp_default": "90.00",
  "rtp_variants": [
    {
      "rtp": "90.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-05-08",
  "themes": [
    {
      "slug": "fantasy",
      "name": "Fantasy"
    }
  ],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/luck-magic-scratch-b10/"
    }
  },
  "series": {
    "slug": "luck-magic",
    "name": "Luck & Magic"
  }
}
```

## Search Demand

`GET /api/v1/slots/luck-magic-scratch-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/luck-magic-scratch-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/luck-magic-scratch-b10/
- **Public page:** https://i-gaming.tools/slot-games/luck-magic-scratch-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
