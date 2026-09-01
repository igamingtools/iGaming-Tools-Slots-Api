# Triple Rampage

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/triple-rampage-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-rampage-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/triple-rampage-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/triple-rampage-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/triple-rampage-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "triple-rampage-b28",
  "name": "Triple Rampage",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.23",
  "rtp_variants": [
    {
      "rtp": "96.23",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "med_low",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-08-20",
  "themes": [
    {
      "slug": "cyberpunk",
      "name": "Cyberpunk"
    },
    {
      "slug": "monsters",
      "name": "Monsters"
    },
    {
      "slug": "superheroes",
      "name": "Superheroes"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "nudge",
      "name": "Nudge"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/triple-rampage-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/triple-rampage-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-rampage-b28/demand/
```

**12-month volume (illustrative):** 1,080 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Switzerland | 90 | flat |
| Latvia | 80 | growing |
| United States | 80 | flat |
| Italy | 70 | flat |
| Brazil | 60 | declining |
| Canada | 60 | flat |
| Finland | 60 | flat |
| Greece | 60 | flat |
| Netherlands | 60 | flat |
| Sweden | 40 | flat |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/triple-rampage-b28/
- **Public page:** https://i-gaming.tools/slot-games/triple-rampage-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
