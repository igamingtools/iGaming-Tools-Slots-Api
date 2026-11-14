# Eye of Horus Megaways

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/eye-of-horus-megaways-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/eye-of-horus-megaways-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/eye-of-horus-megaways-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/eye-of-horus-megaways-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/eye-of-horus-megaways-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "eye-of-horus-megaways-b31",
  "name": "Eye of Horus Megaways",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.49",
  "rtp_variants": [
    {
      "rtp": "95.49",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "93.00",
      "variant": "operator_config",
      "is_default": false
    },
    {
      "rtp": "92.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": null,
  "themes": [
    {
      "slug": "egyptian",
      "name": "Egyptian"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "megaways",
      "name": "Megaways"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/eye-of-horus-megaways-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/eye-of-horus-megaways-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/eye-of-horus-megaways-b31/demand/
```

**12-month volume (illustrative):** 17,430 · **trend:** flat · YoY -0.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 12,240 | flat |
| United States | 1,120 | flat |
| Germany | 670 | growing |
| Spain | 390 | growing |
| Switzerland | 330 | flat |
| Canada | 200 | declining |
| Ireland | 170 | flat |
| Greece | 130 | flat |
| Romania | 130 | flat |
| Finland | 120 | declining |

> Full per-country breakdown (59 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/eye-of-horus-megaways-b31/
- **Public page:** https://i-gaming.tools/slot-games/eye-of-horus-megaways-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
