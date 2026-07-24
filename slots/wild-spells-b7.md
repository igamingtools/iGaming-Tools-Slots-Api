# Wild Spells

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-spells-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-spells-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-spells-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-spells-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-spells-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-spells-b7",
  "name": "Wild Spells",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.40",
  "rtp_variants": [
    {
      "rtp": "96.40",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2017-09-01",
  "themes": [
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "witchcraft",
      "name": "Witchcraft"
    }
  ],
  "features": [
    {
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
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
      "page_url": "https://i-gaming.tools/slot-games/wild-spells-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-spells-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-spells-b7/demand/
```

**12-month volume (illustrative):** 1,620 · **trend:** growing · YoY +44.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 310 | declining |
| Philippines | 90 | flat |
| Peru | 80 | growing |
| Greece | 70 | flat |
| Argentina | 60 | declining |
| Australia | 60 | declining |
| Finland | 60 | flat |
| Switzerland | 60 | flat |
| Germany | 50 | declining |
| Italy | 50 | flat |

> Full per-country breakdown (42 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-spells-b7/
- **Public page:** https://i-gaming.tools/slot-games/wild-spells-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
