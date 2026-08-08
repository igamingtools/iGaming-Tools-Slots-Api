# Plinko 2 Halloween

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/plinko-2-halloween-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plinko-2-halloween-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/plinko-2-halloween-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/plinko-2-halloween-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/plinko-2-halloween-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "plinko-2-halloween-b10",
  "name": "Plinko 2 Halloween",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "crash",
  "rtp_default": "98.60",
  "rtp_variants": [
    {
      "rtp": "98.60",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "99.00",
      "variant": "default",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Multipliers",
      "cost": "0.60",
      "is_default": true
    },
    {
      "label": "Respin Chance",
      "cost": "0.20",
      "is_default": false
    }
  ],
  "release_date": "2025-10-09",
  "themes": [
    {
      "slug": "halloween",
      "name": "Halloween"
    },
    {
      "slug": "witchcraft",
      "name": "Witchcraft"
    }
  ],
  "features": [
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "plinko-bonus",
      "name": "Plinko Bonus"
    },
    {
      "slug": "respin",
      "name": "Respin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/plinko-2-halloween-b10/"
    }
  },
  "series": {
    "slug": "plinko",
    "name": "Plinko"
  }
}
```

## Search Demand

`GET /api/v1/slots/plinko-2-halloween-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plinko-2-halloween-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/plinko-2-halloween-b10/
- **Public page:** https://i-gaming.tools/slot-games/plinko-2-halloween-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
