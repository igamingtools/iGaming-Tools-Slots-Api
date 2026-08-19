# Jogo Do Bicho

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/jogo-do-bicho-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jogo-do-bicho-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/jogo-do-bicho-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/jogo-do-bicho-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/jogo-do-bicho-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "jogo-do-bicho-b22",
  "name": "Jogo Do Bicho",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "instant_win",
  "rtp_default": "93.00",
  "rtp_variants": [
    {
      "rtp": "93.00",
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
  "release_date": "2024-02-12",
  "themes": [],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/jogo-do-bicho-b22/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/jogo-do-bicho-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jogo-do-bicho-b22/demand/
```

**12-month volume (illustrative):** 1,450 · **trend:** declining · YoY -39.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 700 | declining |
| India | 220 | declining |
| Pakistan | 140 | declining |
| Philippines | 60 | growing |
| Mexico | 50 | flat |
| Peru | 40 | flat |
| Portugal | 40 | declining |
| Ukraine | 30 | flat |
| Vietnam | 30 | declining |
| Canada | 20 | flat |

> Full per-country breakdown (19 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/jogo-do-bicho-b22/
- **Public page:** https://i-gaming.tools/slot-games/jogo-do-bicho-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
