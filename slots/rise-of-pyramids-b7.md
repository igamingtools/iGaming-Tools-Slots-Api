# Rise of Pyramids

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rise-of-pyramids-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rise-of-pyramids-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rise-of-pyramids-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rise-of-pyramids-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rise-of-pyramids-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rise-of-pyramids-b7",
  "name": "Rise of Pyramids",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "95.97",
  "rtp_variants": [
    {
      "rtp": "95.97",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.00",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "95.96",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus Respins",
      "cost": "30.00",
      "is_default": true
    },
    {
      "label": "Buy Free Spins",
      "cost": "80.00",
      "is_default": false
    }
  ],
  "release_date": "2024-05-01",
  "themes": [
    {
      "slug": "egyptian",
      "name": "Egyptian"
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
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rise-of-pyramids-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rise-of-pyramids-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rise-of-pyramids-b7/demand/
```

**12-month volume (illustrative):** 2,090 · **trend:** growing · YoY +15.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 200 | flat |
| Switzerland | 120 | flat |
| Brazil | 110 | declining |
| Germany | 110 | flat |
| India | 100 | flat |
| Malaysia | 100 | growing |
| South Africa | 100 | flat |
| Netherlands | 70 | flat |
| Cyprus | 60 | declining |
| Finland | 60 | flat |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rise-of-pyramids-b7/
- **Public page:** https://i-gaming.tools/slot-games/rise-of-pyramids-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
