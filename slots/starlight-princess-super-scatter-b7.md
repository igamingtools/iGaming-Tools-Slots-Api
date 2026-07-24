# Starlight Princess Super Scatter

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/starlight-princess-super-scatter-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/starlight-princess-super-scatter-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/starlight-princess-super-scatter-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/starlight-princess-super-scatter-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/starlight-princess-super-scatter-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "starlight-princess-super-scatter-b7",
  "name": "Starlight Princess Super Scatter",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.49",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 8,
  "rows": 8,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Super Free Spins",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2025-10-30",
  "themes": [
    {
      "slug": "anime",
      "name": "Anime"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/starlight-princess-super-scatter-b7/"
    }
  },
  "series": {
    "slug": "starlight-princess",
    "name": "Starlight Princess"
  }
}
```

## Search Demand

`GET /api/v1/slots/starlight-princess-super-scatter-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/starlight-princess-super-scatter-b7/demand/
```

**12-month volume (illustrative):** 17,230 · **trend:** growing · YoY +3566.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Philippines | 1,990 | growing |
| Brazil | 1,950 | declining |
| Indonesia | 1,570 | growing |
| Greece | 1,510 | declining |
| Canada | 1,120 | declining |
| Malaysia | 660 | growing |
| Germany | 550 | declining |
| Switzerland | 450 | declining |
| United Kingdom | 400 | declining |
| Turkey | 380 | declining |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/starlight-princess-super-scatter-b7/
- **Public page:** https://i-gaming.tools/slot-games/starlight-princess-super-scatter-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
