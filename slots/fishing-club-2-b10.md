# Fishing Club 2

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fishing-club-2-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fishing-club-2-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fishing-club-2-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fishing-club-2-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fishing-club-2-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fishing-club-2-b10",
  "name": "Fishing Club 2",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "instant_win",
  "rtp_default": "97.16",
  "rtp_variants": [
    {
      "rtp": "97.16",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.16",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "97.15",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Fishing Net",
      "cost": "60.00",
      "is_default": true
    },
    {
      "label": "TNT",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2026-04-07",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fishing-club-2-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fishing-club-2-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fishing-club-2-b10/demand/
```

**12-month volume (illustrative):** 60 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Australia | 20 | flat |
| Greece | 10 | declining |
| Poland | 10 | growing |
| Turkey | 10 | declining |
| United Kingdom | 10 | declining |

> Full per-country breakdown (5 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fishing-club-2-b10/
- **Public page:** https://i-gaming.tools/slot-games/fishing-club-2-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
