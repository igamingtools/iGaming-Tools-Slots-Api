# Gorilla Mayhem

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gorilla-mayhem-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gorilla-mayhem-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gorilla-mayhem-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gorilla-mayhem-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gorilla-mayhem-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gorilla-mayhem-b7",
  "name": "Gorilla Mayhem",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "80.00",
      "is_default": true
    }
  ],
  "release_date": "2022-07-28",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
    },
    {
      "slug": "monkeys",
      "name": "Monkeys"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/gorilla-mayhem-b7/"
    }
  }
}
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gorilla-mayhem-b7/
- **Public page:** https://i-gaming.tools/slot-games/gorilla-mayhem-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
