# Rick And Morty Wubba Lubba Dub Dub

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rick-and-morty-wubba-lubba-dub-dub-b31",
  "name": "Rick And Morty Wubba Lubba Dub Dub",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.14",
  "rtp_variants": [
    {
      "rtp": "96.14",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "93.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-11-01",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "aliens",
      "name": "Aliens"
    },
    {
      "slug": "space",
      "name": "Space"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "gamble",
      "name": "Gamble"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rick-and-morty-wubba-lubba-dub-dub-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/demand/
```

**12-month volume (illustrative):** 3,200 · **trend:** growing · YoY +41.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 1,660 | growing |
| Finland | 160 | flat |
| United States | 160 | growing |
| Canada | 140 | flat |
| Spain | 140 | growing |
| Ireland | 110 | flat |
| Sweden | 100 | flat |
| Netherlands | 80 | growing |
| Italy | 70 | flat |
| Denmark | 50 | flat |

> Full per-country breakdown (39 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rick-and-morty-wubba-lubba-dub-dub-b31/
- **Public page:** https://i-gaming.tools/slot-games/rick-and-morty-wubba-lubba-dub-dub-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
