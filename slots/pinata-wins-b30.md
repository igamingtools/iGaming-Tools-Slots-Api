# Pinata Wins

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/pinata-wins-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pinata-wins-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/pinata-wins-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/pinata-wins-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/pinata-wins-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "pinata-wins-b30",
  "name": "Pinata Wins",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.76",
  "rtp_variants": [
    {
      "rtp": "96.76",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-04-01",
  "themes": [
    {
      "slug": "mexican",
      "name": "Mexican"
    },
    {
      "slug": "party",
      "name": "Party"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
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
      "page_url": "https://i-gaming.tools/slot-games/pinata-wins-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/pinata-wins-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pinata-wins-b30/demand/
```

**12-month volume (illustrative):** 278,870 · **trend:** growing · YoY +181.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 151,300 | growing |
| Philippines | 105,800 | flat |
| India | 5,060 | flat |
| Indonesia | 4,700 | flat |
| Malaysia | 2,160 | flat |
| Pakistan | 1,300 | declining |
| Tunisia | 800 | growing |
| Mexico | 760 | declining |
| United States | 580 | flat |
| Thailand | 570 | growing |

> Full per-country breakdown (73 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/pinata-wins-b30/
- **Public page:** https://i-gaming.tools/slot-games/pinata-wins-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
