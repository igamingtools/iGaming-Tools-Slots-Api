# Triple Pot Plinko – Hercules

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/triple-pot-plinko-hercules-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-pot-plinko-hercules-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/triple-pot-plinko-hercules-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/triple-pot-plinko-hercules-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/triple-pot-plinko-hercules-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "triple-pot-plinko-hercules-b7",
  "name": "Triple Pot Plinko – Hercules",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.55",
  "rtp_variants": [
    {
      "rtp": "96.55",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.57",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.53",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "low",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Bonus",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Bonus",
      "cost": "300.00",
      "is_default": false
    }
  ],
  "release_date": "2026-05-14",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "plinko-bonus",
      "name": "Plinko Bonus"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/triple-pot-plinko-hercules-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/triple-pot-plinko-hercules-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-pot-plinko-hercules-b7/demand/
```

**12-month volume (illustrative):** 920 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 90 | declining |
| Canada | 40 | flat |
| Finland | 40 | flat |
| Malaysia | 40 | flat |
| United States | 40 | flat |
| Greece | 30 | declining |
| Peru | 30 | growing |
| Switzerland | 30 | declining |
| Argentina | 20 | flat |
| Australia | 20 | flat |

> Full per-country breakdown (45 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/triple-pot-plinko-hercules-b7/
- **Public page:** https://i-gaming.tools/slot-games/triple-pot-plinko-hercules-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
