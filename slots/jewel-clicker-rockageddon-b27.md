# Jewel Clicker: Rockageddon

**Provider:** Turbo Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/jewel-clicker-rockageddon-b27/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jewel-clicker-rockageddon-b27/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/jewel-clicker-rockageddon-b27/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/jewel-clicker-rockageddon-b27/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/jewel-clicker-rockageddon-b27/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "jewel-clicker-rockageddon-b27",
  "name": "Jewel Clicker: Rockageddon",
  "status": "active",
  "provider": {
    "slug": "turbo-games",
    "name": "Turbo Games"
  },
  "game_category": "instant_win",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-10-01",
  "themes": [
    {
      "slug": "arcade",
      "name": "Arcade"
    },
    {
      "slug": "gems",
      "name": "Gems"
    }
  ],
  "features": [
    {
      "slug": "batch-bet-purchase",
      "name": "Batch Bet Purchase"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/jewel-clicker-rockageddon-b27/"
    }
  },
  "series": {
    "slug": "jewel-clicker",
    "name": "Jewel Clicker"
  }
}
```

## Search Demand

`GET /api/v1/slots/jewel-clicker-rockageddon-b27/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jewel-clicker-rockageddon-b27/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/jewel-clicker-rockageddon-b27/
- **Public page:** https://i-gaming.tools/slot-games/jewel-clicker-rockageddon-b27/
- **Full schema:** https://i-gaming.tools/api/docs/
