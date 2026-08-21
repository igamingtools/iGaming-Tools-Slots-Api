# Mermaid's Treasure Trove

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mermaid-s-treasure-trove-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mermaid-s-treasure-trove-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mermaid-s-treasure-trove-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mermaid-s-treasure-trove-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mermaid-s-treasure-trove-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mermaid-s-treasure-trove-b7",
  "name": "Mermaid's Treasure Trove",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.54",
  "rtp_variants": [
    {
      "rtp": "96.54",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.52",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 7,
  "rows": 7,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2025-10-02",
  "themes": [
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "mermaids",
      "name": "Mermaids"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
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
      "page_url": "https://i-gaming.tools/slot-games/mermaid-s-treasure-trove-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mermaid-s-treasure-trove-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mermaid-s-treasure-trove-b7/demand/
```

**12-month volume (illustrative):** 2,280 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 180 | declining |
| Finland | 160 | declining |
| Belgium | 140 | flat |
| Canada | 140 | growing |
| United States | 140 | declining |
| Brazil | 110 | declining |
| Greece | 90 | declining |
| Peru | 90 | declining |
| United Kingdom | 90 | declining |
| Tunisia | 80 | flat |

> Full per-country breakdown (47 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mermaid-s-treasure-trove-b7/
- **Public page:** https://i-gaming.tools/slot-games/mermaid-s-treasure-trove-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
