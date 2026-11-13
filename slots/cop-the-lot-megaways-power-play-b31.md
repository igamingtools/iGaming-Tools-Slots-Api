# Cop The Lot Megaways Power Play

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/cop-the-lot-megaways-power-play-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cop-the-lot-megaways-power-play-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/cop-the-lot-megaways-power-play-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/cop-the-lot-megaways-power-play-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/cop-the-lot-megaways-power-play-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "cop-the-lot-megaways-power-play-b31",
  "name": "Cop The Lot Megaways Power Play",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.00",
  "rtp_variants": [
    {
      "rtp": "95.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "95.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "92.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-03-01",
  "themes": [
    {
      "slug": "heist",
      "name": "Heist"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
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
      "page_url": "https://i-gaming.tools/slot-games/cop-the-lot-megaways-power-play-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/cop-the-lot-megaways-power-play-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cop-the-lot-megaways-power-play-b31/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/cop-the-lot-megaways-power-play-b31/
- **Public page:** https://i-gaming.tools/slot-games/cop-the-lot-megaways-power-play-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
