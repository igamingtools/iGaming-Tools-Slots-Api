# RetroVerse

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/retroverse-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/retroverse-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/retroverse-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/retroverse-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/retroverse-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "retroverse-b28",
  "name": "RetroVerse",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.24",
  "rtp_variants": [
    {
      "rtp": "96.24",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.42",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.30",
      "variant": "ante_bet",
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
      "label": "Free Spins",
      "cost": "120.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "280.00",
      "is_default": false
    }
  ],
  "release_date": "2026-04-15",
  "themes": [
    {
      "slug": "arcade",
      "name": "Arcade"
    },
    {
      "slug": "neon",
      "name": "Neon"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/retroverse-b28/"
    }
  },
  "series": {
    "slug": "retro",
    "name": "Retro"
  }
}
```

## Search Demand

`GET /api/v1/slots/retroverse-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/retroverse-b28/demand/
```

**12-month volume (illustrative):** 1,680 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 240 | growing |
| Sweden | 120 | flat |
| Netherlands | 90 | flat |
| United Kingdom | 90 | flat |
| Canada | 80 | flat |
| Latvia | 70 | declining |
| Belgium | 60 | declining |
| Denmark | 60 | flat |
| Switzerland | 60 | flat |
| United States | 60 | growing |

> Full per-country breakdown (42 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/retroverse-b28/
- **Public page:** https://i-gaming.tools/slot-games/retroverse-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
