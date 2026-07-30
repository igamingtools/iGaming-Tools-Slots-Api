# Lucky Dice

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lucky-dice-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-dice-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lucky-dice-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lucky-dice-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lucky-dice-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lucky-dice-b7",
  "name": "Lucky Dice",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.53",
  "rtp_variants": [
    {
      "rtp": "96.53",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-11-10",
  "themes": [
    {
      "slug": "cards",
      "name": "Cards"
    },
    {
      "slug": "casino",
      "name": "Casino"
    },
    {
      "slug": "dice",
      "name": "Dice"
    }
  ],
  "features": [
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "prize-ladder",
      "name": "Prize Ladder"
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
      "page_url": "https://i-gaming.tools/slot-games/lucky-dice-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/lucky-dice-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-dice-b7/demand/
```

**12-month volume (illustrative):** 1,740 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 140 | flat |
| Brazil | 130 | flat |
| South Africa | 110 | flat |
| Greece | 100 | flat |
| Belgium | 80 | flat |
| Pakistan | 80 | flat |
| Peru | 60 | flat |
| Tunisia | 50 | flat |
| Finland | 40 | flat |
| Indonesia | 40 | flat |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lucky-dice-b7/
- **Public page:** https://i-gaming.tools/slot-games/lucky-dice-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
