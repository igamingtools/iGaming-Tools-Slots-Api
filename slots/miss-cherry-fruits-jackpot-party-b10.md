# Miss Cherry Fruits Jackpot Party

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/miss-cherry-fruits-jackpot-party-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/miss-cherry-fruits-jackpot-party-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/miss-cherry-fruits-jackpot-party-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/miss-cherry-fruits-jackpot-party-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/miss-cherry-fruits-jackpot-party-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "miss-cherry-fruits-jackpot-party-b10",
  "name": "Miss Cherry Fruits Jackpot Party",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "94.65",
  "rtp_variants": [
    {
      "rtp": "94.65",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.77",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "94.83",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "48.00",
      "is_default": true
    },
    {
      "label": "Disco Ball Respin",
      "cost": "40.00",
      "is_default": false
    }
  ],
  "release_date": "2022-07-28",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "party",
      "name": "Party"
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
      "page_url": "https://i-gaming.tools/slot-games/miss-cherry-fruits-jackpot-party-b10/"
    }
  },
  "series": {
    "slug": "miss-cherry-fruits",
    "name": "Miss Cherry Fruits"
  }
}
```

## Search Demand

`GET /api/v1/slots/miss-cherry-fruits-jackpot-party-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/miss-cherry-fruits-jackpot-party-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/miss-cherry-fruits-jackpot-party-b10/
- **Public page:** https://i-gaming.tools/slot-games/miss-cherry-fruits-jackpot-party-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
