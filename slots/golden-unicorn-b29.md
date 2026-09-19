# Golden Unicorn

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/golden-unicorn-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-unicorn-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/golden-unicorn-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/golden-unicorn-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/golden-unicorn-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "golden-unicorn-b29",
  "name": "Golden Unicorn",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.11",
  "rtp_variants": [
    {
      "rtp": "96.11",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": null,
  "themes": [
    {
      "slug": "fairies",
      "name": "Fairies"
    },
    {
      "slug": "fairy-tale",
      "name": "Fairy Tale"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/golden-unicorn-b29/"
    }
  },
  "series": {
    "slug": "golden-unicorn",
    "name": "Golden Unicorn"
  }
}
```

## Search Demand

`GET /api/v1/slots/golden-unicorn-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-unicorn-b29/demand/
```

**12-month volume (illustrative):** 1,570 · **trend:** declining · YoY -37.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 1,390 | flat |
| Indonesia | 30 | declining |
| Switzerland | 30 | flat |
| El Salvador | 20 | flat |
| Pakistan | 20 | flat |
| Panama | 20 | flat |
| Brazil | 10 | flat |
| Germany | 10 | flat |
| Italy | 10 | growing |
| Lebanon | 10 | flat |

> Full per-country breakdown (12 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/golden-unicorn-b29/
- **Public page:** https://i-gaming.tools/slot-games/golden-unicorn-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
