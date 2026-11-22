# Bikini Island Deluxe

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/bikini-island-deluxe-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bikini-island-deluxe-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/bikini-island-deluxe-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/bikini-island-deluxe-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/bikini-island-deluxe-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "bikini-island-deluxe-b29",
  "name": "Bikini Island Deluxe",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.73",
  "rtp_variants": [
    {
      "rtp": "96.73",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.77",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.61",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "49.60",
      "is_default": true
    }
  ],
  "release_date": "2023-09-12",
  "themes": [
    {
      "slug": "party",
      "name": "Party"
    },
    {
      "slug": "travel",
      "name": "Travel"
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
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/bikini-island-deluxe-b29/"
    }
  },
  "series": {
    "slug": "bikini-island",
    "name": "Bikini Island"
  }
}
```

## Search Demand

`GET /api/v1/slots/bikini-island-deluxe-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bikini-island-deluxe-b29/demand/
```

**12-month volume (illustrative):** 530 · **trend:** declining · YoY -60.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 330 | growing |
| Tunisia | 50 | flat |
| Canada | 40 | growing |
| Brazil | 20 | flat |
| Indonesia | 20 | flat |
| Peru | 20 | flat |
| Bulgaria | 10 | flat |
| Croatia | 10 | flat |
| Greece | 10 | flat |
| Panama | 10 | flat |

> Full per-country breakdown (11 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/bikini-island-deluxe-b29/
- **Public page:** https://i-gaming.tools/slot-games/bikini-island-deluxe-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
