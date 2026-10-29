# Inferno Mayhem

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/inferno-mayhem-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/inferno-mayhem-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/inferno-mayhem-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/inferno-mayhem-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/inferno-mayhem-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "inferno-mayhem-b30",
  "name": "Inferno Mayhem",
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
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-03-02",
  "themes": [
    {
      "slug": "music",
      "name": "Music"
    }
  ],
  "features": [
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "respin",
      "name": "Respin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/inferno-mayhem-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/inferno-mayhem-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/inferno-mayhem-b30/demand/
```

**12-month volume (illustrative):** 6,620 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 2,500 | flat |
| Indonesia | 1,180 | declining |
| Philippines | 790 | flat |
| India | 420 | declining |
| Thailand | 220 | flat |
| Pakistan | 160 | flat |
| United States | 120 | flat |
| Japan | 80 | flat |
| Germany | 70 | flat |
| Vietnam | 70 | flat |

> Full per-country breakdown (49 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/inferno-mayhem-b30/
- **Public page:** https://i-gaming.tools/slot-games/inferno-mayhem-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
