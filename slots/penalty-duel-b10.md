# Penalty Duel

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/penalty-duel-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/penalty-duel-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/penalty-duel-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/penalty-duel-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/penalty-duel-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "penalty-duel-b10",
  "name": "Penalty Duel",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "crash",
  "rtp_default": "96.14",
  "rtp_variants": [
    {
      "rtp": "96.14",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.10",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.10",
      "variant": "bonus_buy",
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
      "label": "Bonus series of five shots",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-07-03",
  "themes": [
    {
      "slug": "sports",
      "name": "Sports"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
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
      "page_url": "https://i-gaming.tools/slot-games/penalty-duel-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/penalty-duel-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/penalty-duel-b10/demand/
```

**12-month volume (illustrative):** 1,560 · **trend:** growing · YoY +1014.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 240 | flat |
| Pakistan | 100 | growing |
| Brazil | 80 | growing |
| Finland | 80 | flat |
| Ukraine | 80 | flat |
| France | 60 | flat |
| Germany | 50 | declining |
| United States | 50 | growing |
| Vietnam | 50 | flat |
| Cyprus | 40 | declining |

> Full per-country breakdown (46 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/penalty-duel-b10/
- **Public page:** https://i-gaming.tools/slot-games/penalty-duel-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
