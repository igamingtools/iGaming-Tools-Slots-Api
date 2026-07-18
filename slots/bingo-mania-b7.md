# Bingo Mania

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/bingo-mania-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bingo-mania-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/bingo-mania-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/bingo-mania-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/bingo-mania-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "bingo-mania-b7",
  "name": "Bingo Mania",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.52",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.47",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "BUY FREE SPINS",
      "cost": "80.00",
      "is_default": true
    },
    {
      "label": "BUY BINGO BONUS",
      "cost": "80.00",
      "is_default": false
    }
  ],
  "release_date": "2025-10-20",
  "themes": [
    {
      "slug": "bingo",
      "name": "Bingo"
    },
    {
      "slug": "classic",
      "name": "Classic"
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/bingo-mania-b7/"
    }
  }
}
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/bingo-mania-b7/
- **Public page:** https://i-gaming.tools/slot-games/bingo-mania-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
