# Win Win Fish Prawn Crab

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/win-win-fish-prawn-crab-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/win-win-fish-prawn-crab-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/win-win-fish-prawn-crab-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/win-win-fish-prawn-crab-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/win-win-fish-prawn-crab-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "win-win-fish-prawn-crab-b30",
  "name": "Win Win Fish Prawn Crab",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.72",
  "rtp_variants": [
    {
      "rtp": "96.72",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-05-13",
  "themes": [
    {
      "slug": "casino",
      "name": "Casino"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dice",
      "name": "Dice"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    },
    {
      "slug": "tumble",
      "name": "Tumble"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/win-win-fish-prawn-crab-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/win-win-fish-prawn-crab-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/win-win-fish-prawn-crab-b30/demand/
```

**12-month volume (illustrative):** 770 · **trend:** declining · YoY -35.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 190 | declining |
| Thailand | 110 | declining |
| India | 100 | flat |
| Pakistan | 100 | growing |
| Philippines | 70 | growing |
| Indonesia | 60 | flat |
| Chile | 20 | flat |
| Morocco | 20 | flat |
| Tunisia | 20 | flat |
| Algeria | 10 | flat |

> Full per-country breakdown (17 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/win-win-fish-prawn-crab-b30/
- **Public page:** https://i-gaming.tools/slot-games/win-win-fish-prawn-crab-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
