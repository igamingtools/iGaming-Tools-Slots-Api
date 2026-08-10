# Savage Buffalo Spirit MEGAWAYS™

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/savage-buffalo-spirit-megawaystm-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/savage-buffalo-spirit-megawaystm-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/savage-buffalo-spirit-megawaystm-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/savage-buffalo-spirit-megawaystm-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/savage-buffalo-spirit-megawaystm-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "savage-buffalo-spirit-megawaystm-b10",
  "name": "Savage Buffalo Spirit MEGAWAYS™",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.75",
  "rtp_variants": [
    {
      "rtp": "96.75",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "90.00",
      "is_default": true
    }
  ],
  "release_date": "2023-08-24",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "native-american",
      "name": "Native American"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "megaways",
      "name": "Megaways"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/savage-buffalo-spirit-megawaystm-b10/"
    }
  },
  "series": {
    "slug": "savage-buffalo-spirit",
    "name": "Savage Buffalo Spirit"
  }
}
```

## Search Demand

`GET /api/v1/slots/savage-buffalo-spirit-megawaystm-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/savage-buffalo-spirit-megawaystm-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/savage-buffalo-spirit-megawaystm-b10/
- **Public page:** https://i-gaming.tools/slot-games/savage-buffalo-spirit-megawaystm-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
