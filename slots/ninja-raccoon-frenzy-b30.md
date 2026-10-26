# Ninja Raccoon Frenzy

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/ninja-raccoon-frenzy-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ninja-raccoon-frenzy-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/ninja-raccoon-frenzy-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/ninja-raccoon-frenzy-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/ninja-raccoon-frenzy-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "ninja-raccoon-frenzy-b30",
  "name": "Ninja Raccoon Frenzy",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.81",
  "rtp_variants": [
    {
      "rtp": "96.81",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2023-10-01",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "japanese",
      "name": "Japanese"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "duplicating-wild",
      "name": "Duplicating Wild"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/ninja-raccoon-frenzy-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/ninja-raccoon-frenzy-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ninja-raccoon-frenzy-b30/demand/
```

**12-month volume (illustrative):** 1,530 · **trend:** declining · YoY -52.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 440 | growing |
| India | 200 | flat |
| Indonesia | 190 | growing |
| Pakistan | 140 | flat |
| Philippines | 110 | declining |
| Thailand | 90 | declining |
| Tunisia | 70 | growing |
| United States | 40 | flat |
| Hungary | 30 | flat |
| Mexico | 30 | flat |

> Full per-country breakdown (26 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/ninja-raccoon-frenzy-b30/
- **Public page:** https://i-gaming.tools/slot-games/ninja-raccoon-frenzy-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
