# Burial Warfare

**Provider:** PoggiPlay

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/burial-warfare-b23/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/burial-warfare-b23/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/burial-warfare-b23/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/burial-warfare-b23/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/burial-warfare-b23/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "burial-warfare-b23",
  "name": "Burial Warfare",
  "status": "active",
  "provider": {
    "slug": "poggiplay",
    "name": "PoggiPlay"
  },
  "game_category": "video_slot",
  "rtp_default": "95.23",
  "rtp_variants": [
    {
      "rtp": "95.23",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "med_low",
  "mechanic": "lines",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-06-18",
  "themes": [
    {
      "slug": "halloween",
      "name": "Halloween"
    },
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "zombies",
      "name": "Zombies"
    }
  ],
  "features": [
    {
      "slug": "battle",
      "name": "Battle"
    },
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "exploding-symbol",
      "name": "Exploding Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/burial-warfare-b23/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/burial-warfare-b23/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/burial-warfare-b23/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/burial-warfare-b23/
- **Public page:** https://i-gaming.tools/slot-games/burial-warfare-b23/
- **Full schema:** https://i-gaming.tools/api/docs/
