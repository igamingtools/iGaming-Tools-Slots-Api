# Burning Chilli 243

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/burning-chilli-243-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/burning-chilli-243-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/burning-chilli-243-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/burning-chilli-243-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/burning-chilli-243-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "burning-chilli-243-b10",
  "name": "Burning Chilli 243",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "97.00",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "low",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "60.00",
      "is_default": true
    }
  ],
  "release_date": "2025-10-22",
  "themes": [
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
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
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/burning-chilli-243-b10/"
    }
  },
  "series": {
    "slug": "burning-chilli",
    "name": "Burning Chilli"
  }
}
```

## Search Demand

`GET /api/v1/slots/burning-chilli-243-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/burning-chilli-243-b10/demand/
```

**12-month volume (illustrative):** 210 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Belgium | 20 | growing |
| Czech Republic | 20 | growing |
| Germany | 20 | growing |
| Slovakia | 20 | flat |
| United Kingdom | 20 | flat |
| United States | 20 | declining |
| Australia | 10 | flat |
| Austria | 10 | declining |
| Bulgaria | 10 | growing |
| Greece | 10 | flat |

> Full per-country breakdown (15 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/burning-chilli-243-b10/
- **Public page:** https://i-gaming.tools/slot-games/burning-chilli-243-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
