# Hawaiian Tiki

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/hawaiian-tiki-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hawaiian-tiki-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/hawaiian-tiki-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/hawaiian-tiki-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/hawaiian-tiki-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "hawaiian-tiki-b30",
  "name": "Hawaiian Tiki",
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
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": null,
  "themes": [
    {
      "slug": "tiki",
      "name": "Tiki"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
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
      "page_url": "https://i-gaming.tools/slot-games/hawaiian-tiki-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/hawaiian-tiki-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hawaiian-tiki-b30/demand/
```

**12-month volume (illustrative):** 1,360 · **trend:** declining · YoY -21.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 480 | declining |
| India | 180 | growing |
| Indonesia | 160 | growing |
| Philippines | 150 | declining |
| Mexico | 50 | declining |
| Tunisia | 50 | flat |
| Greece | 40 | flat |
| Pakistan | 40 | declining |
| Ireland | 20 | declining |
| Latvia | 20 | declining |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/hawaiian-tiki-b30/
- **Public page:** https://i-gaming.tools/slot-games/hawaiian-tiki-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
