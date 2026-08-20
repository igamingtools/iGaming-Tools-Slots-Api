# Calle Piñata

**Provider:** PoggiPlay

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/calle-pi-ata-b23/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/calle-pi-ata-b23/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/calle-pi-ata-b23/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/calle-pi-ata-b23/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/calle-pi-ata-b23/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "calle-pi-ata-b23",
  "name": "Calle Piñata",
  "status": "active",
  "provider": {
    "slug": "poggiplay",
    "name": "PoggiPlay"
  },
  "game_category": "video_slot",
  "rtp_default": "94.51",
  "rtp_variants": [
    {
      "rtp": "94.51",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Sticky Wild",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "1x5 Wild",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2024-10-29",
  "themes": [
    {
      "slug": "day-of-the-dead",
      "name": "Day of the Dead"
    },
    {
      "slug": "mexican",
      "name": "Mexican"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
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
      "page_url": "https://i-gaming.tools/slot-games/calle-pi-ata-b23/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/calle-pi-ata-b23/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/calle-pi-ata-b23/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/calle-pi-ata-b23/
- **Public page:** https://i-gaming.tools/slot-games/calle-pi-ata-b23/
- **Full schema:** https://i-gaming.tools/api/docs/
