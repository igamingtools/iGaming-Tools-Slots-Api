# Dragon Tiger

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/dragon-tiger-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dragon-tiger-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/dragon-tiger-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/dragon-tiger-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/dragon-tiger-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "dragon-tiger-b7",
  "name": "Dragon Tiger",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "table",
  "rtp_default": "96.27",
  "rtp_variants": [
    {
      "rtp": "96.27",
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
  "release_date": "2021-04-01",
  "themes": [
    {
      "slug": "asian",
      "name": "Asian"
    },
    {
      "slug": "cards",
      "name": "Cards"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    }
  ],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/dragon-tiger-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/dragon-tiger-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dragon-tiger-b7/demand/
```

**12-month volume (illustrative):** 7,230 · **trend:** flat · YoY +0.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 3,200 | declining |
| Brazil | 1,410 | declining |
| Philippines | 200 | growing |
| Indonesia | 190 | flat |
| Finland | 120 | flat |
| Malaysia | 120 | flat |
| Netherlands | 110 | declining |
| Canada | 100 | flat |
| Portugal | 100 | declining |
| United States | 100 | declining |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/dragon-tiger-b7/
- **Public page:** https://i-gaming.tools/slot-games/dragon-tiger-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
