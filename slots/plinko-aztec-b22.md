# Plinko AZTEC

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/plinko-aztec-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plinko-aztec-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/plinko-aztec-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/plinko-aztec-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/plinko-aztec-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "plinko-aztec-b22",
  "name": "Plinko AZTEC",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "instant_win",
  "rtp_default": "98.00",
  "rtp_variants": [
    {
      "rtp": "98.00",
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
  "release_date": "2025-01-21",
  "themes": [
    {
      "slug": "aztec",
      "name": "Aztec"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "level-progression",
      "name": "Level Progression"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/plinko-aztec-b22/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/plinko-aztec-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plinko-aztec-b22/demand/
```

**12-month volume (illustrative):** 1,680 · **trend:** growing · YoY +223.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 260 | flat |
| Indonesia | 100 | growing |
| Italy | 100 | growing |
| Pakistan | 100 | flat |
| Germany | 70 | flat |
| Brazil | 60 | flat |
| Finland | 60 | flat |
| Romania | 60 | flat |
| Greece | 50 | declining |
| Netherlands | 50 | flat |

> Full per-country breakdown (44 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/plinko-aztec-b22/
- **Public page:** https://i-gaming.tools/slot-games/plinko-aztec-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
