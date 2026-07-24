# Vampy Party

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/vampy-party-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/vampy-party-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/vampy-party-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/vampy-party-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/vampy-party-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "vampy-party-b7",
  "name": "Vampy Party",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.00",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "3X Scatter",
      "cost": "78.00",
      "is_default": true
    },
    {
      "label": "4X Scatter",
      "cost": "150.00",
      "is_default": false
    }
  ],
  "release_date": "2024-10-01",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "party",
      "name": "Party"
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
      "page_url": "https://i-gaming.tools/slot-games/vampy-party-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/vampy-party-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/vampy-party-b7/demand/
```

**12-month volume (illustrative):** 26,250 · **trend:** declining · YoY -17.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 4,170 | declining |
| Brazil | 4,000 | declining |
| Indonesia | 2,390 | declining |
| United Kingdom | 1,100 | declining |
| Philippines | 960 | growing |
| Denmark | 890 | declining |
| Finland | 880 | declining |
| Germany | 850 | declining |
| Switzerland | 750 | declining |
| Hungary | 710 | declining |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/vampy-party-b7/
- **Public page:** https://i-gaming.tools/slot-games/vampy-party-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
