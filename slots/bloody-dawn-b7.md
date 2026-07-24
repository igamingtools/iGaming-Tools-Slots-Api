# Bloody Dawn

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/bloody-dawn-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bloody-dawn-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/bloody-dawn-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/bloody-dawn-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/bloody-dawn-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "bloody-dawn-b7",
  "name": "Bloody Dawn",
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
      "variant": "ante_bet",
      "is_default": false
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
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins 1",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2025-12-01",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "native-american",
      "name": "Native American"
    },
    {
      "slug": "vampires",
      "name": "Vampires"
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
      "slug": "gamble",
      "name": "Gamble"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/bloody-dawn-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/bloody-dawn-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bloody-dawn-b7/demand/
```

**12-month volume (illustrative):** 5,930 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 1,210 | declining |
| Brazil | 340 | flat |
| Finland | 340 | flat |
| Indonesia | 240 | flat |
| Switzerland | 210 | flat |
| Canada | 180 | flat |
| Thailand | 160 | flat |
| United Kingdom | 160 | flat |
| Netherlands | 140 | declining |
| Peru | 140 | flat |

> Full per-country breakdown (57 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/bloody-dawn-b7/
- **Public page:** https://i-gaming.tools/slot-games/bloody-dawn-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
