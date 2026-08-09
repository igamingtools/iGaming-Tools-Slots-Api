# Beast Band

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/beast-band-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/beast-band-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/beast-band-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/beast-band-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/beast-band-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "beast-band-b10",
  "name": "Beast Band",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.88",
  "rtp_variants": [
    {
      "rtp": "96.88",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.88",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.88",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins with High Symbols",
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Disk Respin with Multipliers",
      "cost": "80.00",
      "is_default": false
    }
  ],
  "release_date": "2023-07-20",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "music",
      "name": "Music"
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
      "page_url": "https://i-gaming.tools/slot-games/beast-band-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/beast-band-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/beast-band-b10/demand/
```

**12-month volume (illustrative):** 740 · **trend:** growing · YoY +25.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Australia | 100 | flat |
| Finland | 100 | declining |
| Brazil | 90 | growing |
| United Kingdom | 80 | flat |
| United States | 80 | declining |
| New Zealand | 70 | growing |
| Greece | 40 | flat |
| Ireland | 30 | flat |
| Belgium | 20 | flat |
| Canada | 20 | flat |

> Full per-country breakdown (20 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/beast-band-b10/
- **Public page:** https://i-gaming.tools/slot-games/beast-band-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
