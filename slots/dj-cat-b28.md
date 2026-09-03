# DJ Cat

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/dj-cat-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dj-cat-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/dj-cat-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/dj-cat-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/dj-cat-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "dj-cat-b28",
  "name": "DJ Cat",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.32",
  "rtp_variants": [
    {
      "rtp": "96.32",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.39",
      "variant": "feature",
      "is_default": false
    },
    {
      "rtp": "96.27",
      "variant": "feature",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 4,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-04-16",
  "themes": [
    {
      "slug": "cats",
      "name": "Cats"
    },
    {
      "slug": "music",
      "name": "Music"
    },
    {
      "slug": "neon",
      "name": "Neon"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
    },
    {
      "slug": "prize-symbols",
      "name": "Prize Symbols"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/dj-cat-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/dj-cat-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dj-cat-b28/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/dj-cat-b28/
- **Public page:** https://i-gaming.tools/slot-games/dj-cat-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
