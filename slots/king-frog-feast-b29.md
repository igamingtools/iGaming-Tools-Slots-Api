# King Frog Feast

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/king-frog-feast-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/king-frog-feast-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/king-frog-feast-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/king-frog-feast-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/king-frog-feast-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "king-frog-feast-b29",
  "name": "King Frog Feast",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.70",
  "rtp_variants": [
    {
      "rtp": "96.70",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "53.57",
      "is_default": true
    }
  ],
  "release_date": null,
  "themes": [
    {
      "slug": "frogs",
      "name": "Frogs"
    },
    {
      "slug": "royalty",
      "name": "Royalty"
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
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/king-frog-feast-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/king-frog-feast-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/king-frog-feast-b29/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/king-frog-feast-b29/
- **Public page:** https://i-gaming.tools/slot-games/king-frog-feast-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
