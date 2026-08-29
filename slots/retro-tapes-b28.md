# Retro Tapes

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/retro-tapes-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/retro-tapes-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/retro-tapes-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/retro-tapes-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/retro-tapes-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "retro-tapes-b28",
  "name": "Retro Tapes",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.47",
  "rtp_variants": [
    {
      "rtp": "96.47",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.71",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.71",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 9,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins (Singles Feature)",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins (Hits Feature)",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2022-11-23",
  "themes": [
    {
      "slug": "music",
      "name": "Music"
    },
    {
      "slug": "neon",
      "name": "Neon"
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
      "slug": "magnetic-symbol",
      "name": "Magnetic Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/retro-tapes-b28/"
    }
  },
  "series": {
    "slug": "retro",
    "name": "Retro"
  }
}
```

## Search Demand

`GET /api/v1/slots/retro-tapes-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/retro-tapes-b28/demand/
```

**12-month volume (illustrative):** 40,080 · **trend:** declining · YoY -27.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 3,850 | growing |
| Denmark | 3,550 | declining |
| United Kingdom | 3,180 | growing |
| Sweden | 2,950 | flat |
| Germany | 2,820 | flat |
| United States | 2,660 | flat |
| Canada | 2,340 | flat |
| Switzerland | 2,220 | declining |
| Netherlands | 1,740 | declining |
| Ukraine | 1,720 | growing |

> Full per-country breakdown (73 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/retro-tapes-b28/
- **Public page:** https://i-gaming.tools/slot-games/retro-tapes-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
