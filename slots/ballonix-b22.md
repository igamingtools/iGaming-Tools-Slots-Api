# BalloniX

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/ballonix-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ballonix-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/ballonix-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/ballonix-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/ballonix-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "ballonix-b22",
  "name": "BalloniX",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "crash",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-07-25",
  "themes": [
    {
      "slug": "birds",
      "name": "Birds"
    },
    {
      "slug": "farm",
      "name": "Farm"
    },
    {
      "slug": "sky",
      "name": "Sky"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/ballonix-b22/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/ballonix-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ballonix-b22/demand/
```

**12-month volume (illustrative):** 2,400 · **trend:** growing · YoY +98.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 520 | flat |
| Germany | 180 | growing |
| Belgium | 140 | flat |
| Poland | 110 | flat |
| Spain | 110 | growing |
| France | 100 | growing |
| Italy | 100 | flat |
| Netherlands | 100 | flat |
| Indonesia | 90 | growing |
| United Kingdom | 90 | declining |

> Full per-country breakdown (35 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/ballonix-b22/
- **Public page:** https://i-gaming.tools/slot-games/ballonix-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
