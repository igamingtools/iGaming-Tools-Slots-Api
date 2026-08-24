# Mines

**Provider:** Turbo Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mines-b27/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mines-b27/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mines-b27/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mines-b27/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mines-b27/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mines-b27",
  "name": "Mines",
  "status": "active",
  "provider": {
    "slug": "turbo-games",
    "name": "Turbo Games"
  },
  "game_category": "crash",
  "rtp_default": "94.71",
  "rtp_variants": [
    {
      "rtp": "94.71",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "95.30",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-05-01",
  "themes": [
    {
      "slug": "gems",
      "name": "Gems"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
    },
    {
      "slug": "prize-ladder",
      "name": "Prize Ladder"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/mines-b27/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mines-b27/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mines-b27/demand/
```

**12-month volume (illustrative):** 197,540 · **trend:** declining · YoY -50.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 108,600 | declining |
| Brazil | 40,830 | declining |
| Pakistan | 5,660 | declining |
| United States | 4,810 | declining |
| Canada | 3,060 | declining |
| Indonesia | 2,920 | declining |
| Greece | 2,730 | declining |
| Italy | 2,700 | declining |
| Philippines | 2,440 | growing |
| Sweden | 1,620 | declining |

> Full per-country breakdown (80 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mines-b27/
- **Public page:** https://i-gaming.tools/slot-games/mines-b27/
- **Full schema:** https://i-gaming.tools/api/docs/
