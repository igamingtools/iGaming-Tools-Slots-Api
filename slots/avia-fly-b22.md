# Avia Fly

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/avia-fly-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/avia-fly-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/avia-fly-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/avia-fly-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/avia-fly-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "avia-fly-b22",
  "name": "Avia Fly",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "crash",
  "rtp_default": "95.00",
  "rtp_variants": [
    {
      "rtp": "95.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2023-11-23",
  "themes": [
    {
      "slug": "aviation",
      "name": "Aviation"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/avia-fly-b22/"
    }
  },
  "series": {
    "slug": "avia-fly",
    "name": "Avia Fly"
  }
}
```

## Search Demand

`GET /api/v1/slots/avia-fly-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/avia-fly-b22/demand/
```

**12-month volume (illustrative):** 1,110 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 220 | flat |
| Pakistan | 180 | flat |
| Canada | 60 | flat |
| United States | 60 | flat |
| Finland | 40 | declining |
| Germany | 40 | flat |
| Indonesia | 40 | flat |
| Italy | 40 | flat |
| Poland | 40 | flat |
| Ukraine | 40 | flat |

> Full per-country breakdown (31 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/avia-fly-b22/
- **Public page:** https://i-gaming.tools/slot-games/avia-fly-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
